
# Баг-репорты

## Баг №1 Неправильный код ответа сервера при вводе числа 0 в поле ID ,раздел Authors в эндпоинте POST ​/api​/v1​/Authors/{id 0}


- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Authors

 3. Нажат эндпоинт POST ​/api​/v1​/Authors/{id 0}

- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число 0
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 201

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)


## Баг №2 Неправильный код ответа сервера при вводе числа 0 в поле ID ,раздел CoverPhotos в эндпоинте POST ​/api​/v1​/CoverPhotos/{id 0}


- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел CoverPhotos

 3. Нажат эндпоинт POST ​/api​/v1​/CoverPhotos/{id 0}

- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число 0
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 201

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №3 Неправильный код ответа сервера при вводе числа 0 в поле ID ,раздел Users в эндпоинте POST ​/api​/v1​/Users/{id 0}


- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Users

 3. Нажат эндпоинт POST ​/api​/v1​/Users/{id 0}

- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число 0
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 201

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №4 Неправильный код ответа сервера при вводе числа 0 в поле ID ,раздел Books в эндпоинте POST ​/api​/v1​/Books/{id 0}



- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Books

 3. Нажат эндпоинт POST ​/api​/v1​/Books/{id 0}


- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число 0
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 201

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №5 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел CoverPhotos в эндпоинте POST ​/api​/v1​/CoverPhotos/{id -1}




- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел CoverPhotos

 3. Нажат эндпоинт POST ​/api​/v1​/CoverPhotos/{id -1}



- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №6 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Books в эндпоинте POST ​/api​/v1​/Books/{id -1}




- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Books

 3. Нажат эндпоинт POST ​/api​/v1​/Books/{id -1}



- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №7 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Users в эндпоинте POST ​/api​/v1​/Users/{id -1}




- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Users

 3. Нажат эндпоинт POST ​/api​/v1​/Users/{id -1}



- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №8 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Authors в эндпоинте POST ​/api​/v1​/Authors/{id -1}





- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Authors

 3. Нажат эндпоинт POST ​/api​/v1​/Authors/{id -1}




- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №9 Неправильный код ответа сервера при вводе числа 0 в поле ID ,раздел Activities в эндпоинте POST ​/api​/v1​/Activities/{id 0}


- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Activities

 3. Нажат эндпоинт POST ​/api​/v1​/Activities/{id 0}

- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число 0
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 201

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)


## Баг №10 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Activities в эндпоинте POST ​/api​/v1​/Activities/{id -1}





- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Activities

 3. Нажат эндпоинт POST ​/api​/v1​/Activities/{id -1}




- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №11 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Books в эндпоинте GET​/api​/v1​/Books/{id-1}





- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Books

 3. Нажат эндпоинт GET​/api​/v1​/Books/{id-1}




- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №12 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел CoverPhotos в эндпоинте GET​/api​/v1​/CoverPhotos/{id-1}






- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел CoverPhotos

 3. Нажат эндпоинт GET​/api​/v1​/CoverPhotos/{id-1}





- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №13 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Users в эндпоинте GET​/api​/v1​/Users/{id-1}



- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Users

 3. Нажат эндпоинт GET​/api​/v1​/Users/{id-1}





- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №14 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Authors в эндпоинте GET​/api​/v1​/Authors/{id-1}




- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Authors

 3. Нажат эндпоинт GET​/api​/v1​/Authors/{id-1}






- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №15 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Activities в эндпоинте GET​/api​/v1​/Activities/{id-1}





- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Activities

 3. Нажат эндпоинт GET​/api​/v1​/Activities/{id-1}







- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №16 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Books в эндпоинте PUT ​/api​/v1​/Books/{id -1}




- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Books

 3. Нажат эндпоинт PUT ​/api​/v1​/Books/{id -1}







- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №17 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Users в эндпоинте PUT ​/api​/v1​/Users/{id -1}





- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Users

 3. Нажат эндпоинт PUT ​/api​/v1​/Users/{id -1}








- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №18 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел CoverPhotos в эндпоинте PUT ​/api​/v1​/CoverPhotos/{id -1}



- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел CoverPhotos

 3. Нажат эндпоинт PUT ​/api​/v1​/CoverPhotos/{id -1}




- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №18 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Authors в эндпоинте PUT ​/api​/v1​/Authors/{id -1}


- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Authors

 3. Нажат эндпоинт PUT ​/api​/v1​/Authors/{id -1}


- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №20 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Activities в эндпоинте  PUT ​/api​/v1​/Activities/{id -1}



- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Activities

 3. Нажат эндпоинт  PUT ​/api​/v1​/Activities/{id -1}



- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №21 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Authors в эндпоинте  DELETE ​/api​/v1​/Authors/{id -1}


- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Authors

 3. Нажат эндпоинт  DELETE ​/api​/v1​/Authors/{id -1}


- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №22 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Users в эндпоинте  DELETE ​/api​/v1​/Users/{id -1}


- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Users

 3. Нажат эндпоинт  DELETE ​/api​/v1​/Users/{id -1}



- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №23 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел UseCoverPhotosrs в эндпоинте  DELETE ​/api​/v1​/CoverPhotos/{id -1}


- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел CoverPhotos

 3. Нажат эндпоинт  DELETE ​/api​/v1​/CoverPhotos/{id -1}



- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №24 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел Books​ в эндпоинте  DELETE ​/api​/v1​/Books​/{id -1}



- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел Books​

 3. Нажат эндпоинт  DELETE ​/api​/v1​/Books​/{id -1}




- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №25 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел authors в эндпоинте  GET​/api​/v1​/Authors/authors/books/{idBook -1}



- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел authors

 3. Нажат эндпоинт  GET​/api​/v1​/Authors/authors/books/{idBook -1}



- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)

## Баг №26 Неправильный код ответа сервера при вводе числа -1 в поле ID ,раздел CoverPhotos в эндпоинте  GET​/api​/v1​/CoverPhotos/books/covers/{idBook -1}


- #### Предшествующие условия:

 1. Открыта страница Swagger UI https://fakerestapi.azurewebsites.net/index.html

 2. Открыт раздел CoverPhotos

 3. Нажат эндпоинт  GET​/api​/v1​/CoverPhotos/books/covers/{idBook -1}




- ##### Серьёзность:
Minor

- ##### Шаги для воспроизведения:

1. Нажать на кнопку Try it out
2. Ввести в поле ID число -1
3. Нажать на кнопку Execute

- ##### Ожидаемый результат:

 Ответ сервера с кодом 400

- ##### Фактический результат:

 Ответ сервера с кодом 200

- ##### Окружение:

ПК desktop/ Windows 7.Браузер Chrome 109.0.5414.120 (64 бит)