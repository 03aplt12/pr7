## Алгоритмы балансировки нагрузки

Алгоритм балансировки нагрузки – это набор правил, которым следует балансировщик нагрузки для определения наилучшего сервера для каждого из различных клиентских запросов. 

1.	Round Robin
Round Robin, или алгоритм кругового обслуживания, представляет собой перебор по круговому циклу: первый запрос передаётся одному серверу, затем следующий запрос передаётся другому и так до достижения последнего сервера, а затем всё начинается сначала.
В числе несомненных плюсов этого алгоритма следует назвать, во-первых, независимость от протокола высокого уровня. Для работы по алгоритму Round Robin используется любой протокол, в котором обращение к серверу идёт по имени.
Балансировка на основе алгоритма Round Robin никак не зависит от нагрузки на сервер: кэширующие DNS-серверы помогут справиться с любым наплывом клиентов.
Использование алгоритма Round Robin не требует связи между серверами, поэтому он может использоваться как для локальной, так и для глобальной балансировки.
Наконец, решения на базе алгоритма Round Robin отличаются низкой стоимостью: чтобы они начали работать, достаточно просто добавить несколько записей в DNS.
Алгоритм Round Robin имеет и целый ряд существенных недостатков. Чтобы распределение нагрузки по этому алгоритму отвечало упомянутым выше критериями справедливости и эффективности, нужно, чтобы у каждого сервера был в наличии одинаковый набор ресурсов. При выполнении всех операций также должно быть задействовано одинаковое количество ресурсов. В реальной практике эти условия в большинстве случаев оказываются невыполнимыми.
Также при балансировке по алгоритму Round Robin совершенно не учитывается загруженность того или иного сервера в составе кластера. Представим себе следующую гипотетическую ситуацию: один из узлов загружен на 100%, в то время как другие — всего на 10 — 15%. Алгоритм Round Robin возможности возникновения такой ситуации не учитывает в принципе, поэтому перегруженный узел все равно будет получать запросы. Ни о какой справедливости, эффективности и предсказуемости в таком случае не может быть и речи.
В силу описанных выше обстоятельств сфера применения алгоритма Round Robin весьма ограничена.

2.	Weighted Round Robin
Это — усовершенствованная версия алгоритма Round Robin. Суть усовершенствований заключается в следующем: каждому серверу присваивается весовой коэффициент в соответствии с его производительностью и мощностью. Это помогает распределять нагрузку более гибко: серверы с большим весом обрабатывают больше запросов. Однако всех проблем с отказоустойчивостью это отнюдь не решает. Более эффективную балансировку обеспечивают другие методы, в которых при планировании и распределении нагрузки учитывается большее количество параметров.
Недостатком метода, является то, что веса для вычислительных узлов устанавливаются вручную и при изменениях в системе (улучшении характеристики определенного узла путём добавления новых аппаратных решений или резком неожиданном снижении вычислительной мощности другого узла из-за возникших аппаратных или программных неисправностей), количество отправляемых запросов на обработку останется неизменным.

3.	Least Connections
В предыдущем разделе мы перечислили основные недостатки алгоритма Round Robin. Назовём ещё один: в нём совершенно не учитывается количество активных на данный момент подключений.
Рассмотрим практический пример. Имеется два сервера — обозначим их условно как А и Б. К серверу А подключено меньше пользователей, чем к серверу Б. При этом сервер А оказывается более перегруженным. Как это возможно? Ответ достаточно прост: подключения к серверу А поддерживаются в течение более долгого времени по сравнению с подключениями к серверу Б.
Описанную проблему можно решить с помощью алгоритма, известного под названием least connections (сокращённо — leastconn). Он учитывает количество подключений, поддерживаемых серверами в текущий момент времени. Каждый следующий вопрос передаётся серверу с наименьшим количеством активных подключений.
Существует усовершенствованный вариант этого алгоритма, предназначенный в первую очередь для использования в кластерах, состоящих из серверов с разными техническими характеристиками и разной производительностью. Он называется Weighted Least Connections и учитывает при распределении нагрузки не только количество активных подключений, но и весовой коэффициент серверов.
Недостатком метода является то, что количество соединений не учитывает возможности вычислительного узла. Узел в системе может обладать низкой производительностью и, соответственно, малым количеством соединений. Обладая малым числом соединений, он может быть полностью нагруженным и не в состоянии принять новые запросы на обработку.



4.	Source IP Hash
Source IP Hash – метод балансировки нагрузки, который использует исходный и целевой IP-адреса клиента и сервера и производит их объединение, которое необходимо для генерации уникального ключа хешфункции. Этот ключ используется для размещения запросов клиента на определенном вычислителе. Поскольку ключ может быть восстановлен после разрыва связи, то этот метод гарантирует то, что запрос клиента будет отправлен именно на тот же сервер, который был использован ранее.
Таким образом, каждый клиент подключается к определенному вычислительному узлу, что позволяет распределить нагрузку между вычислителями, однако при определенных обстоятельствах (например, большое количество тяжелых запросов) эффективность алгоритма снижается.



5.	Sticky Sessions

Sticky Sessions — алгоритм распределения входящих запросов, при котором соединения передаются на один и тот же сервер группы. Он используется, например, в веб-сервере Nginx. Сессии пользователя могут быть закреплены за конкретным сервером с помощью метода IP hash.
С помощью этого метода запросы распределяются по серверам на основе IP-aдреса клиента. Как указано в документации (см. ссылку выше), «метод гарантирует, что запросы одного и того же клиента будет передаваться на один и тот же сервер». Если закреплённый за конкретным адресом сервер недоступен, запрос будет перенаправлен на другой сервер.
Применение этого метода сопряжено с некоторыми проблемами. Проблемы с привязкой сессий могут возникнуть, если клиент использует динамический IP. В ситуации, когда большое количество запросов проходит через один прокси-сервер, балансировку вряд ли можно назвать эффективной и справедливой. Описанные проблемы, однако, можно решить, используя cookies.


6.	Least Traffic/Weighted Least Traffic
Least Traffic/Weighted Least Traffic – алгоритм балансировки нагрузки, в котором диспетчер контролирует битрейт, исходящий из каждого вычислительного узла системы и отправляет запросы на вычислитель с наименьшим исходящим трафиком.
Недостатком является то, что диспетчеру балансировки нагрузки неизвестна производительность сервера. Таким образом, небольшой трафик может исходить из малопроизводительного узла системы и при его дополнительной нагрузке, запросы будут накапливаться в очереди. Поэтому, для гетерогенной вычислительной системы применяются взвешенный алгоритм.
