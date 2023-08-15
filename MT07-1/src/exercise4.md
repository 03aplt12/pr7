# Отчёт


## 1. GET​/api​/v1​/Activities
URL: https://fakerestapi.azurewebsites.net/api/v1/Activities
## Ожидаемый результат - Код ответа 200
## Заголовки запроса
User-Agent: PostmanRuntime/7.32.3  
Accept: */*  
Cache-Control: no-cache  
Postman-Token: 268fa60e-2d10-4fe7-a2f3-d20b4dd531e6  
Host: fakerestapi.azurewebsites.net  
Accept-Encoding: gzip, deflate, br  
Connection: keep-alive    
## Тело запроса
отсутствует

## Заголовки ответа
Content-Type: application/json; charset=utf-8; v=1.0  
Date: Mon, 03 Jul 2023 17:45:47 GMT  
Server: Kestrel  
Transfer-Encoding: chunked  
## Тело ответа
отсутствует

## 2. POST​/api​/v1​/Activities
URL: https://fakerestapi.azurewebsites.net/api/v1/Activities
## Ожидаемый результат - Код ответа 201 Created
## Заголовки запроса
Content-Type: application/json  
User-Agent: PostmanRuntime/7.32.3  
Accept: */*  
Cache-Control: no-cache  
Postman-Token: 5c2f3cbe-71f6-4e4f-bea4-865f498092f3  
Host: fakerestapi.azurewebsites.net  
Accept-Encoding: gzip, deflate, br  
Connection: keep-alive  
## Тело запроса
{  
  "id": 0,  
  "title": "string",  
  "dueDate": "2023-07-02T15:04:23.165Z",  
  "completed": true  
 Name": "string"    
}    
## Заголовки ответа
Content-Type: application/json; charset=utf-8; v=1.0  
Date: Mon, 03 Jul 2023 17:47:09 GMT  
Server: Kestrel  
Transfer-Encoding: chunked  
api-supported-versions: 1.0   
## Тело ответа
{"id":0,"title":"string","dueDate":"2023-07-02T15:04:23.165Z","completed":true}

## 3. POST​/api​/v1​/Activities
URL: https://fakerestapi.azurewebsites.net/api/v1/Activities
## Ожидаемый результат - Код ответа 405

## Заголовки запроса
Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 0044b0a6-620b-484f-be1d-a2c8fd81acf6
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive


## Тело запроса
{
    "id": -1,
    "title": "string",
    "dueDate": "2023-07-02T15:04:23.165Z",
    "completed": true
}
## Заголовки ответа
Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 11:07:50 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0 
## Тело ответа
{"id":-1,"title":"string","dueDate":"2023-07-02T15:04:23.165Z","completed":true}


## 4. POST​/api​/v1​/Activities
URL: https://fakerestapi.azurewebsites.net/api/v1/Activities
## Ожидаемый результат - Код ответа 400 Bad request
## Заголовки запроса
Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 3b6d426c-5bb7-402a-bb89-3749b292251c
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive


## Тело запроса
{
  "id": 2147483648,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

## Заголовки ответа
Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 11:10:34 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа
{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-8a62ef0e34d96d4d8c585cb21d2ca276-64bb94beb48cd74d-00","errors":{"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 18."]}}

## 5. POST​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities


## Ожидаемый результат - Код ответа 400


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 06e2f613-1c48-491b-b7a5-12185b0ebdd4
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id":  ,
  "title": "string",
  "dueDate": "2023-07-02T15:04:23.165Z",
  "completed": true
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 11:14:08 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-a6004429f0cb924e9f17658d2a410841-b45e6a897848dd46-00","errors":{"$.id":["',' is an invalid start of a value. Path: $.id | LineNumber: 1 | BytePositionInLine: 9."]}}

## 6. POST​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: d21c3108-4eb2-4120-a9f4-ff88c261531e
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": qww,
  "title": "string",
  "dueDate": "2023-07-02T15:04:23.165Z",
  "completed": true
}

## Заголовки ответа

ontent-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 11:21:53 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-704e5874b007844f8bb9e131e22ea1b8-e662f7d5f7c8c447-00","errors":{"$.id":["'q' is an invalid start of a value. Path: $.id | LineNumber: 1 | BytePositionInLine: 8."]}}

## 7. POST​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: d9ee1295-bb56-46a4-9210-91fcdc1085f9
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует 

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 11:27:54 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-1e63156b5fae39468b1ce542f4e8a736-3b6db5a5d9801446-00","errors":{"$":["'a' is an invalid start of a property name. Expected a '\"'. Path: $ | LineNumber: 0 | BytePositionInLine: 1."]}}

## 8. GET​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities


## Ожидаемый результат - Код ответа 200

## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 917704bf-a222-47a5-9f7f-24ce1aaa8438
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа
Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 11:32:12 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

[{"id":1,"title":"Activity 1","dueDate":"2023-07-04T12:32:12.6667819+00:00","completed":false},{"id":2,"title":"Activity 2","dueDate":"2023-07-04T13:32:12.6667839+00:00","completed":true},{"id":3,"title":"Activity 3","dueDate":"2023-07-04T14:32:12.6667843+00:00","completed":false},{"id":4,"title":"Activity 4","dueDate":"2023-07-04T15:32:12.6667846+00:00","completed":true},{"id":5,"title":"Activity 5","dueDate":"2023-07-04T16:32:12.6667848+00:00","completed":false},{"id":6,"title":"Activity 6","dueDate":"2023-07-04T17:32:12.6667852+00:00","completed":true},{"id":7,"title":"Activity 7","dueDate":"2023-07-04T18:32:12.6667856+00:00","completed":false},{"id":8,"title":"Activity 8","dueDate":"2023-07-04T19:32:12.6667858+00:00","completed":true},{"id":9,"title":"Activity 9","dueDate":"2023-07-04T20:32:12.6667861+00:00","completed":false},{"id":10,"title":"Activity 10","dueDate":"2023-07-04T21:32:12.6667866+00:00","completed":true},{"id":11,"title":"Activity 11","dueDate":"2023-07-04T22:32:12.6667869+00:00","completed":false},{"id":12,"title":"Activity 12","dueDate":"2023-07-04T23:32:12.6667872+00:00","completed":true},{"id":13,"title":"Activity 13","dueDate":"2023-07-05T00:32:12.6667875+00:00","completed":false},{"id":14,"title":"Activity 14","dueDate":"2023-07-05T01:32:12.6667878+00:00","completed":true},{"id":15,"title":"Activity 15","dueDate":"2023-07-05T02:32:12.6667881+00:00","completed":false},{"id":16,"title":"Activity 16","dueDate":"2023-07-05T03:32:12.6667884+00:00","completed":true},{"id":17,"title":"Activity 17","dueDate":"2023-07-05T04:32:12.6667887+00:00","completed":false},{"id":18,"title":"Activity 18","dueDate":"2023-07-05T05:32:12.6667891+00:00","completed":true},{"id":19,"title":"Activity 19","dueDate":"2023-07-05T06:32:12.6667894+00:00","completed":false},{"id":20,"title":"Activity 20","dueDate":"2023-07-05T07:32:12.6667897+00:00","completed":true},{"id":21,"title":"Activity 21","dueDate":"2023-07-05T08:32:12.66679+00:00","completed":false},{"id":22,"title":"Activity 22","dueDate":"2023-07-05T09:32:12.6667902+00:00","completed":true},{"id":23,"title":"Activity 23","dueDate":"2023-07-05T10:32:12.6667905+00:00","completed":false},{"id":24,"title":"Activity 24","dueDate":"2023-07-05T11:32:12.6667908+00:00","completed":true},{"id":25,"title":"Activity 25","dueDate":"2023-07-05T12:32:12.6667911+00:00","completed":false},{"id":26,"title":"Activity 26","dueDate":"2023-07-05T13:32:12.6667914+00:00","completed":true},{"id":27,"title":"Activity 27","dueDate":"2023-07-05T14:32:12.6667916+00:00","completed":false},{"id":28,"title":"Activity 28","dueDate":"2023-07-05T15:32:12.6667919+00:00","completed":true},{"id":29,"title":"Activity 29","dueDate":"2023-07-05T16:32:12.6667942+00:00","completed":false},{"id":30,"title":"Activity 30","dueDate":"2023-07-05T17:32:12.6667945+00:00","completed":true}]




## 9. GET​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities/-1


## Ожидаемый результат - Код ответа 405


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: bb46de99-aa93-43f2-b286-6e4d59afdd34
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 11:34:54 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.4","title":"Not Found","status":404,"traceId":"00-540aa57af0da89489452b0509e0d3c20-8201c8b088d62246-00"}


## 10. GET​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities/%7B%7Bactivity-bad-id%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: c0119f70-5622-43e4-a265-8e80fe2eaff0
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 11:39:01 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-898d13c7271c884980dc7cdf400775e9-be7370e9f91d6b47-00","errors":{"id":["The value '{{activity-bad-id}}' is not valid."]}}

## 11. PUT​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities/0

## Ожидаемый результат - Код ответа 200


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 406b3706-2905-4143-a7f3-5cd5b7da9a48
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": 0,
  "title": "string",
  "dueDate": "2023-07-02T16:30:24.267Z",
  "completed": true
}
## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 11:40:29 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":0,"title":"string","dueDate":"2023-07-02T16:30:24.267Z","completed":true}

## 12. PUT​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities/-1

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 8fd5d16a-c275-4b6b-9c7a-668314c3d471
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": 0,
  "title": "string",
  "dueDate": "2023-07-02T16:30:24.267Z",
  "completed": true
}

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 11:44:00 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":0,"title":"string","dueDate":"2023-07-02T16:30:24.267Z","completed":true}



## 13. PUT​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities/%7B%7Bactivity-bad-id%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: text/plain
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 577aa18e-d859-4653-a405-aabe27de64cd
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": 0,
  "title": "string",
  "dueDate": "2023-07-02T16:30:24.267Z",
  "completed": true
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 11:46:56 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.13","title":"Unsupported Media Type","status":415,"traceId":"00-f51c89b1d985bd4f8e1ef78cc44c95d0-0d4d9a4b58383f46-00"}


## 14. PUT​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities/%20

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: debd8fdb-464a-496b-b47a-1a5f56ff4675
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id":   ,
  "title": "string",
  "dueDate": "2023-07-02T16:30:24.267Z",
  "completed": true
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 11:48:46 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-7f1f2973d363674488ae6a445166f6f3-b3bc4b901a305b4f-00","errors":{"id":["The value ' ' is invalid."],"$.id":["',' is an invalid start of a value. Path: $.id | LineNumber: 1 | BytePositionInLine: 10."]}}

## 15. PUT​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities/

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: fa216809-bb99-4815-80be-c6b5c591f592
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Length: 0
Date: Tue, 04 Jul 2023 11:50:47 GMT
Server: Kestrel
Allow: GET, POST

## Тело ответа

Отсутствует

## 16. PUT​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities/qww

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 4fc81893-6644-45d0-9d4b-451936a59fbc
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": dfghj,
  "title": "string",
  "dueDate": "2023-07-02T16:30:24.267Z",
  "completed": true
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 11:52:46 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-ffa0da15ef289648ba6539519f8f2117-0fa92967be86d446-00","errors":{"id":["The value 'qww' is not valid."],"$.id":["'d' is an invalid start of a value. Path: $.id | LineNumber: 1 | BytePositionInLine: 8."]}}

## 17. DELETE​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities/0

## Ожидаемый результат - Код ответа 200

## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 79d4b71a-c4aa-4c5f-8e56-0e3e7f144a52
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Length: 0
Date: Tue, 04 Jul 2023 11:55:08 GMT
Server: Kestrel
api-supported-versions: 1.0

## Тело ответа

Отсутствует


## 18. DELETE​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities/-1


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: d41cc951-6164-4f9d-b856-cd3d934c595c
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Length: 0
Date: Tue, 04 Jul 2023 11:57:20 GMT
Server: Kestrel
api-supported-versions: 1.0

## Тело ответа

Отсутствует

## 19. DELETE​/api​/v1​/Activities


URL: https://fakerestapi.azurewebsites.net/api/v1/Activities/%7B%7Bactivity-bad-id%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 8a8c932b-d745-472b-b05b-14684bb59699
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 12:00:00 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-f9e98254190c9447a83a894e7d89843b-4f5d2d4c583e5841-00","errors":{"id":["The value '{{activity-bad-id}}' is not valid."]}}



=======

## 20. GET​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors

## Ожидаемый результат - Код ответа 200


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: f2988d7e-ae92-452a-9cc7-9d6eb31bdbab
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 12:23:45 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

[{"id":1,"idBook":1,"firstName":"First Name 1","lastName":"Last Name 1"},{"id":2,"idBook":1,"firstName":"First Name 2","lastName":"Last Name 2"},{"id":3,"idBook":2,"firstName":"First Name 3","lastName":"Last Name 3"},{"id":4,"idBook":2,"firstName":"First Name 4","lastName":"Last Name 4"},{"id":5,"idBook":3,"firstName":"First Name 5","lastName":"Last Name 5"},{"id":6,"idBook":3,"firstName":"First Name 6","lastName":"Last Name 6"},{"id":7,"idBook":3,"firstName":"First Name 7","lastName":"Last Name 7"},{"id":8,"idBook":3,"firstName":"First Name 8","lastName":"Last Name 8"},{"id":9,"idBook":4,"firstName":"First Name 9","lastName":"Last Name 9"},{"id":10,"idBook":4,"firstName":"First Name 10","lastName":"Last Name 10"}



## 21. POST​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors


## Ожидаемый результат - Код ответа 201


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 5506ff5a-e9d2-4ab5-8b2e-a20edd3bb029
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": {{authors_minus}},
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 12:26:40 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-fc2cd637e046134eb001756b7c5bc510-0e66b6898a94b14c-00","errors":{"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 9."]}}

## 22. POST​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 9d1b50bc-902c-402b-9a47-eddc8e980d12
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": 2147483648,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 12:28:27 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-ef1fbec7c2bb864e8e567c284755e3ec-6094b0d0099ff549-00","errors":{"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 18."]}}


## 23. POST​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 92a5484a-d402-4408-8bc6-312823fb88c4
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": qww,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 12:29:41 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-ef0a9d58095e1e42b50ba3f91595aec5-878f072b8c1dd44f-00","errors":{"$.id":["'q' is an invalid start of a value. Path: $.id | LineNumber: 1 | BytePositionInLine: 8."]}}


## 24. POST​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 06fb91e0-ed7e-4ccb-9460-9a5ee090d263
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса


{authors_no_body}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 12:30:44 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-41e7e4be0f79394f994aed6cd18c183c-59bd015a5bd7ef4b-00","errors":{"$":["'a' is an invalid start of a property name. Expected a '\"'. Path: $ | LineNumber: 0 | BytePositionInLine: 1."]}}


## 25. GET​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/1

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса


User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: b6e0faf7-ec95-4c7d-98be-8927faee1ec9
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 12:32:29 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

[{"id":1,"idBook":1,"firstName":"First Name 1","lastName":"Last Name 1"},{"id":2,"idBook":1,"firstName":"First Name 2","lastName":"Last Name 2"},{"id":3,"idBook":1,"firstName":"First Name 3","lastName":"Last Name 3"},{"id":4,"idBook":1,"firstName":"First Name 4","lastName":"Last Name 4"}]

## 26. GET​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/-1


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 409f391d-1d62-4a91-9a89-ebf1de2aefd0
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 12:33:54 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

[]

## 27. GET​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/2147483648

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 849e261b-f61e-4c02-939a-1264418e5ec9
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 12:35:29 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-70abf18eb97cbe4db31a8b433ee63d1c-9cf6adbcb25b4346-00","errors":{"idBook":["The value '2147483648' is not valid."]}}


## 28. GET​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/%7B%7Bid_book_no%20-id%7D%7D

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 56072fd0-141b-46d7-a94e-28d2baa21fe6
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 12:36:36 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-c56f6c36f6fd5c4f9583d08f80e1583d-075846223b0c4a4e-00","errors":{"idBook":["The value '{{id_book_no -id}}' is not valid."]}}


## 29. GET​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/0


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: fae6b4d2-0832-43aa-ba1d-9bac47f13d9c
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 12:38:08 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.4","title":"Not Found","status":404,"traceId":"00-c58122715ea14548855c006b392f0e2a-d58ce71a1521f94d-00"}

## 30. GET​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/-1

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 3363d02d-d2bf-462e-a3f8-b76112e8a2b1
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 12:39:28 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.4","title":"Not Found","status":404,"traceId":"00-0e69cb2658fa844d9c98ea61f05e6fb9-16794634b2082a40-00"}

## 31. GET​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/%20


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 6183b778-2b69-42e0-93a9-b749226eb079
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 12:55:26 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-cee9f7ad2fa8484d9ae685ea62785f81-4b646327e2104a4d-00","errors":{"id":["The value ' ' is invalid."]}}


## 32. GET​/api​/v1​/Authors


URL:  https://fakerestapi.azurewebsites.net/api/v1/Authors/2147483648


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 098fd2b2-a16d-4b58-841b-d6eedd615d56
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 12:56:37 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-bb898a4599c9224eab943d1ea9a6b495-12c71fe7883f934e-00","errors":{"id":["The value '2147483648' is not valid."]}}

## 33. PUT​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/0


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: cf8876f1-f029-4da2-beb7-f7d2fd1e34fe
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 12:57:49 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":0,"idBook":0,"firstName":"string","lastName":"string"}

## 34. PUT​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/-1


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: cc70026d-bee8-4ee4-a590-f38d01a92277
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 12:59:25 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":0,"idBook":0,"firstName":"string","lastName":"string"}

## 35. PUT​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/2147483648


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 27bca2ba-2065-4843-a260-785122185960
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": 2147483648,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:00:56 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-c4cc9af77aebf841a97feaacfd6b9b04-c571e5a7bd085f40-00","errors":{"id":["The value '2147483648' is not valid."],"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 18."]}}

## 36. PUT​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/0


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 278d6759-1067-40dd-bf66-99e6b859b527
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": qww,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:02:07 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-145bbd3817eda84183d40576c0a330ac-d7753dc594809244-00","errors":{"$.id":["'q' is an invalid start of a value. Path: $.id | LineNumber: 1 | BytePositionInLine: 8."]}}

## 37. PUT​/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/0


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 571d3f68-6fd4-4dc6-a628-3905834e7ed8
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса


{authors_no_body}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:03:43 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-4e5e27b1d41bb24eaec548feb7481703-b4aa65d042d42e44-00","errors":{"$":["'a' is an invalid start of a property name. Expected a '\"'. Path: $ | LineNumber: 0 | BytePositionInLine: 1."]}}

## 38. DELETE/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/0


## Ожидаемый результат - Код ответа 200


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 8271157e-768d-498e-8c90-8ad545315373
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Length: 0
Date: Tue, 04 Jul 2023 13:07:10 GMT
Server: Kestrel
api-supported-versions: 1.0

## Тело ответа

Отсутствует


## 39. DELETE/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors.-1


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: bc0fdda2-76dd-4de4-9408-2a6d9ebd3cd7
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Length: 0
Date: Tue, 04 Jul 2023 13:08:35 GMT
Server: Kestrel
api-supported-versions: 1.0

## Тело ответа

Отсутствует

## 40. DELETE/api​/v1​/Authors


URL: https://fakerestapi.azurewebsites.net/api/v1/Authors/2147483648


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: b9c37883-6ffe-4580-9d28-7bc63e4e4e24
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:10:11 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-42243eb2a7afb64b8fccaec2b7bfa3a2-033962b3d5f3ea4b-00","errors":{"id":["The value '2147483648' is not valid."]}}


## 41.GET/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books


## Ожидаемый результат - Код ответа 200


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: d74e3a35-5bb0-4e95-8779-0d25368133c4
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 13:14:17 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":1,"title":"Book 1","description":"Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n","pageCount":100,"excerpt":"Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n","publishDate":"2023-07-03T13:14:18.3773102+00:00"},{"id":2,"title":"Book 2","description":"Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n","pageCount":200,"excerpt":"Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n"}


## 42. POST/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books


## Ожидаемый результат - Код ответа 201


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: b32e5316-0f64-49a6-9d61-7266f790ef20
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 13:16:43 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":0,"idBook":0,"firstName":"string","lastName":"string"}


## 43. POST/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: db3d8057-d5fd-4369-95cd-5da3cfa7364a
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id":1,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-07-03T13:43:58.104Z"
}

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 13:18:00 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":1,"title":"string","description":"string","pageCount":0,"excerpt":"string","publishDate":"2023-07-03T13:43:58.104Z"}

## 44. POST/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 1b9dc81c-0858-4605-9ba3-7d36791f836f
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": -1,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 13:19:06 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":-1,"title":null,"description":null,"pageCount":0,"excerpt":null,"publishDate":"0001-01-01T00:00:00"}


## 45. POST/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 1c7ebafb-357a-4471-99ba-5368ec0ec47d
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": 2147483648,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:20:57 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-79cdafe668a63a4aaf770a07f7be1235-eb2289a43fd69941-00","errors":{"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 18."]}}

## 46. POST/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 469da6cd-d041-45b8-8bbe-bd44c1f70a6e
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": qww,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:22:17 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-5fa203f02d51024998aebaf911056cc5-ce0603586f70f044-00","errors":{"$.id":["'q' is an invalid start of a value. Path: $.id | LineNumber: 1 | BytePositionInLine: 8."]}}

## 47. POST/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: c2dc03a2-09f0-4bc7-b3ff-04058e948b85
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{books_no_body}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:23:39 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-c46f2dd33577a24da9abad4b1fa63bab-c8bd91a62e80d342-00","errors":{"$":["'b' is an invalid start of a property name. Expected a '\"'. Path: $ | LineNumber: 0 | BytePositionInLine: 1."]}}


## 48. GET/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books/1


## Ожидаемый результат - Код ответа 200


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: a2b0b505-284d-4dae-b566-06d0b87677e6
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 13:26:53 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":1,"title":"Book 1","description":"Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n","pageCount":100,"excerpt":"Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n","publishDate":"2023-07-03T13:26:53.9080033+00:00"}

## 49. GET/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books/-1


## Ожидаемый результат - Код ответа 405

## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 6efbaf11-c43e-452c-a769-9b1a259a9cd0
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 13:28:08 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.4","title":"Not Found","status":404,"traceId":"00-208ca88dcf3bae48a079b2098683ab19-0fe2137d7a911d48-00"}

## 50. GET/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books/2147483648


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 2caa6081-8b22-4726-82c8-6f07ac5d7932
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:29:18 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-2d12fe2e672699418f309fdf32258901-0f4159d858dd694e-00","errors":{"id":["The value '2147483648' is not valid."]}}


## 51. GET/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books/%20


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: fcc48294-01d1-4797-bd11-4c2ad3a1a205
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:30:54 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-cc83bbc69a7f754aa757edb9cde2b893-d231e75342332b49-00","errors":{"id":["The value ' ' is invalid."]}}

## 52. PUT/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books/1


## Ожидаемый результат - Код ответа 200

## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 548aba19-24b1-4376-89c6-5d49d3b5bc03
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": 1,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-07-03T13:23:36.174Z"
}

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 13:32:49 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":1,"title":"string","description":"string","pageCount":0,"excerpt":"string","publishDate":"2023-07-03T13:23:36.174Z"}

## 53. PUT/api​/v1​/Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books/2147483648

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

ontent-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 69278755-be88-467d-9612-2b899993c628
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": 2147483648,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-07-03T13:23:36.174Z"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:36:36 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-739aee1c90e51c4b9737009237033990-e8048adef7f60d40-00","errors":{"id":["The value '2147483648' is not valid."],"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 18."]}}

## 54. PUT/api​/v1/​Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books/-1


## Ожидаемый результат - Код ответа 405


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 445cc215-ad82-4cbe-8278-49b76c8d8d99
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": -1,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-07-03T13:23:36.174Z"
}

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 13:38:06 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":-1,"title":"string","description":"string","pageCount":0,"excerpt":"string","publishDate":"2023-07-03T13:23:36.174Z"}

## 55. PUT/api​/v1/​Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books/1


## Ожидаемый результат - Код ответа 200


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 207b699f-5f50-4474-9e3b-404ecd226388
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": qww,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-07-03T13:23:36.174Z"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:39:41 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-2e4733a0320e58459c6361ab2bc91c2f-5f81eea74b7fcb4b-00","errors":{"$.id":["'q' is an invalid start of a value. Path: $.id | LineNumber: 1 | BytePositionInLine: 8."]}}

## 56. PUT/api​/v1/​Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 42952e7f-27a0-42ce-81f9-94b923a45808
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{books_no_body}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:41:47 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-c9cbd5c807c52b43a8daac247359ff2f-560fba158609b040-00","errors":{"$":["'b' is an invalid start of a property name. Expected a '\"'. Path: $ | LineNumber: 0 | BytePositionInLine: 1."]}}


## 57. DELETE/api​/v1/​Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books/1


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 08c8d3d1-efb2-4701-8948-661e64b20246
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса



## Заголовки ответа

Content-Length: 0
Date: Tue, 04 Jul 2023 13:43:51 GMT
Server: Kestrel
api-supported-versions: 1.0

## Тело ответа

Отсутствует

## 58. DELETE/api​/v1/​Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books/-1


## Ожидаемый результат - Код ответа 405


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 971f6e59-c417-4989-b668-7dc49f28df21
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Length: 0
Date: Tue, 04 Jul 2023 13:45:30 GMT
Server: Kestrel
api-supported-versions: 1.0



## Тело ответа

Отсутствует


## 59. DELETE/api​/v1/​Books


URL: https://fakerestapi.azurewebsites.net/api/v1/Books/2147483648


## Ожидаемый результат - Код ответа 200

## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 9227aed3-4afa-46cb-b6ed-cd08ecad2ee0
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:49:50 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-2d7d4d4534cbba4fa2272e87b387133a-90f9946f5f15e045-00","errors":{"id":["The value '2147483648' is not valid."]}}

## 60. GET/api​/v1/CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos

## Ожидаемый результат - Код ответа 200

## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 55214517-1916-49fe-9976-9ec631ed412e
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 13:52:09 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":1,"idBook":1,"url":"https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 1&w=250&h=350"},{"id":2,"idBook":2,"url":"https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 2&w=250&h=350"},{"id":3,"idBook":3,"url":"https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 3&w=250&h=350"},{"id":4,"idBook":4,"url":"https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 4&w=250&h=350"},{"id":5,"idBook":5,"url":"https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 5&w=250&h=350"},{"id":6,"idBook":6,"url":"https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 6&w=250&h=350"},{"id":7,"idBook":7,"url":"https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 7&w=250&h=350"},{"id":8,"idBook":8,"url":"https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 8&w=250&h=350"},{"id":9,"idBook":9,"url":"https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 9&w=250&h=350"}

## 61. POST/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos


## Ожидаемый результат - Код ответа 201

## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 16421265-e120-4640-a535-76185c1dc28b
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": {{id}},
  "idBook": 0,
  "url": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:56:14 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-39f3703830adb246930a12ed54876c3b-8715db126000af4f-00","errors":{"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 9."]}}

## 62. POST/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 748bdbab-33ee-4d83-84bb-3242c702d6fa
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": {{id_minus}},
  "idBook": 0,
  "url": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:57:50 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-17f05b5ab428f0469c8515e5653f8734-84c3a4146c9b534a-00","errors":{"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 9."]}}


## 63. POST/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 9bfeac4b-141c-4c95-92ba-0a21b22f1c1f
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": {{bad_id}},
  "idBook": 0,
  "url": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 13:59:35 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-4cefc818d189b642875e8088b1d39b15-638611d0bf1ffb44-00","errors":{"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 9."]}}

## 64. POST/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: d8a78659-973a-4a71-ba70-b890d5a4e0b4
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": {{bad_body}},
  "idBook": 0,
  "url": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:00:57 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа


{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-e0dc6630e11df148ba9b5fe003a6665e-9a5897fca1d48342-00","errors":{"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 9."]}}


## 65. POST/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 8aaab7bb-f3e3-4ab0-9626-bbe85a758dab
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{no_body}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:02:04 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-cbca12714b89db4393886301923b228e-5ccd31931f9afe46-00","errors":{"$":["'n' is an invalid start of a property name. Expected a '\"'. Path: $ | LineNumber: 0 | BytePositionInLine: 1."]}}


## 66. GET/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/1


## Ожидаемый результат - Код ответа 200


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 988de1bd-9652-42ad-97d9-fc0c805e5bb9
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 14:04:49 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

[{"id":1,"idBook":1,"url":"https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 1&w=250&h=350"}]

## 67. GET/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/2147483648


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 669e53a2-1c33-4c87-89ce-fc0cbfa0e311
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:34:29 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-1177090b962b324ab9609e90fba0948c-c2579dabb1f2d74f-00","errors":{"idBook":["The value '2147483648' is not valid."]}}

## 68. GET/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/-1


## Ожидаемый результат - Код ответа 405

## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 0aacfa0c-51a6-45de-a523-05dd5fdf9c57
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 14:35:42 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

[]

## 69. GET/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%20


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

ser-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 69e331ba-992e-4ad0-88d5-9b425b179d84
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса


Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:36:25 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-bb6558a40719d946afd1ca2ca9a6773a-df8b0c60a5e27e4d-00","errors":{"idBook":["The value ' ' is invalid."]}}

## 70. GET/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%7B%7Bid%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса


User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 39ec56ba-1287-4d78-97f6-018f2239186c
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:39:03 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-37ae1be6a007fd439c34873835b8aec7-c07a0206ccce644e-00","errors":{"id":["The value '{{id}}' is not valid."]}}

## 71. GET/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%7B%7Bid_minus%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 9072fbfa-7c5d-4acb-b656-7af640794613
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:40:22 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-d6a92bea315853418d54eb5ce14a7b2a-75b40024bedbb745-00","errors":{"id":["The value '{{id_minus}}' is not valid."]}}

## 72. GET/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%7B%7Bbad_id%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 8ea0ab47-2868-4b61-9f50-dc09316f0d5d
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:41:31 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-7ca0da300e529849953bcc95bab9a93e-911de9b921025a4b-00","errors":{"id":["The value '{{bad_id}}' is not valid."]}}


## 73. GET/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%7B%7Bno_id%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: f7dbe7ef-6c14-4d36-b31d-a7f8404df188
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:42:50 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-b5b27ddb46674847b72a18a6de127fdc-0155ca7d9e9b3e4d-00","errors":{"id":["The value '{{no_id}}' is not valid."]}}


## 74. PUT/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%7B%7Bid%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 9d5bc5ce-3c53-4382-8519-b69b89fea0b6
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
"id": {{id}},
  "idBook": 0,
  "url": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:44:27 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа


{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-ecb715cb0c42224fb7303c1663c3765b-734aa029a42ea541-00","errors":{"id":["The value '{{id}}' is not valid."],"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 7."]}}

## 75. PUT/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%7B%7Bid_minus%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 877a2590-4e4a-4dff-9143-a6824cc1a30a
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
"id": {{id_minus}},
  "idBook": 0,
  "url": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:45:31 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-59570400692eda458c8c1a61c3a3832d-5256f84c29067f4c-00","errors":{"id":["The value '{{id_minus}}' is not valid."],"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 7."]}}


## 76. PUT/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%7B%7Bbad_id%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 66bdf336-d49f-4430-8a7f-b63d5ad9a62f
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
"id": {{id_minus}},
  "idBook": 0,
  "url": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:47:42 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-2238204563f5454da610b273f69cbc1e-f481a3b4e9bf1e4b-00","errors":{"id":["The value '{{bad_id}}' is not valid."],"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 7."]}}

## 77. PUT/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%7B%7Bid%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 05daf820-3f7a-456c-bb43-f4405d1f1d4c
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
"id": {{bad_body}},
  "idBook": 0,
  "url": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:49:17 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа


{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-8689f1a21bda3742a7e25e153b5fd092-ee2e3cb316d6ed4d-00","errors":{"id":["The value '{{id}}' is not valid."],"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 7."]}}

## 78. PUT/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%7B%7Bid%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 7e619b97-d31c-4a9a-90d5-d978808eee1d
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{no_body}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:50:31 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-fb8abf3680379a48ae1259d11d98f377-a8a704a54096064c-00","errors":{"$":["'n' is an invalid start of a property name. Expected a '\"'. Path: $ | LineNumber: 0 | BytePositionInLine: 1."],"id":["The value '{{id}}' is not valid."]}}

## 79. DELETE/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%7B%7Bid%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 694dce3c-2dde-448f-91a8-9f5eab9dbaef
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:52:31 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-85adda438011df4a8aa937e5699cc47f-23b9373d2e5ec041-00","errors":{"id":["The value '{{id}}' is not valid."]}}

## 80. DELETE/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%7B%7Bid_minus%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса


User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: ff13149e-0cd3-45f3-8b09-f2ecd4bb5337
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:53:45 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-c190ff241b99074eb34db1e258e69e0b-91dedb1bb1d38942-00","errors":{"id":["The value '{{id_minus}}' is not valid."]}}


## 81. DELETE/api​/v1/​CoverPhotos


URL: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/%7B%7Bbad_id%7D%7D


## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 93d968ab-7203-44f2-9dde-e55cfc97cf93
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 14:54:42 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-c3359f37885c7044898abba0be3b167f-b509c47b1618c942-00","errors":{"id":["The value '{{bad_id}}' is not valid."]}}

### 82. GET/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users

## Ожидаемый результат - Код ответа 200


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 0c4e2762-6b95-44cb-bc64-efb65a45d11c
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 14:58:56 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

[{"id":1,"userName":"User 1","password":"Password1"},{"id":2,"userName":"User 2","password":"Password2"},{"id":3,"userName":"User 3","password":"Password3"},{"id":4,"userName":"User 4","password":"Password4"},{"id":5,"userName":"User 5","password":"Password5"},{"id":6,"userName":"User 6","password":"Password6"},{"id":7,"userName":"User 7","password":"Password7"},{"id":8,"userName":"User 8","password":"Password8"},{"id":9,"userName":"User 9","password":"Password9"},{"id":10,"userName":"User 10","password":"Password10"}]

## 83. POST/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users

## Ожидаемый результат - Код ответа 201


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 49b8ebe0-8195-477d-8675-bd523e09aaf4
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": 1,
  "userName": "string",
  "password": "string"
}

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 15:00:16 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":1,"userName":"string","password":"string"}

## 84. POST/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 56a01bb6-221f-406b-b620-43b69553c523
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": {{id_minus}},
  "userName": "string",
  "password": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:01:30 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа
{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-24faadde86896846bab6f051704e2c85-6ea33d6f38feaa48-00","errors":{"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 9."]}}


## 85. POST/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 20308f7d-588e-4818-ac05-38be403f3e88
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": {{bad_id}},
  "userName": "string",
  "password": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:03:21 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-86205a9a7ae68e469677cea19a6a2eb3-b5ba6e330cc32144-00","errors":{"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 9."]}}

## 86. POST/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 9bb68fcc-1057-40af-835c-c2cee1a39a23
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id": {{bad_body}},
  "userName": "string",
  "password": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:04:43 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-a4aab4ff8e95af4a8d46ef14535570db-223e13fdfc474246-00","errors":{"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 9."]}}

## 87. POST/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 2928ba56-8f30-41bf-aeb0-138506e1b58e
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{no_body}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:06:25 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-d7a16ef3e9aba343848db73a555f1be3-24957e66eeedbf43-00","errors":{"$":["'n' is an invalid start of a property name. Expected a '\"'. Path: $ | LineNumber: 0 | BytePositionInLine: 1."]}}

## 88. GET/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users/1

## Ожидаемый результат - Код ответа 200


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 55a7bb4c-80ae-4b83-895a-0bad62a20702
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/json; charset=utf-8; v=1.0
Date: Tue, 04 Jul 2023 15:07:44 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

## Тело ответа

{"id":1,"userName":"User 1","password":"Password1"}

# 89. GET/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users/-1

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: cb00e446-393e-48d0-b970-512d285a439e
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:08:58 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-c4aae38aa34d9041aa83aea938346395-10595aecaaf65c43-00","errors":{"id":["The value '{{id_minus}}' is not valid."]}}

# 90. GET/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users/2147483648

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 4ced3a0b-295a-4d10-81d7-e99129855dc4
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:10:03 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-066e8ac0272b894b8a3b3781ce03c307-4ce6960536bd0c4b-00","errors":{"id":["The value '{{bad_id}}' is not valid."]}}

# 91. GET/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 70118972-7680-4396-9f83-ce8d0a0382db
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:11:08 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-c1820863e038bd4b9f35451b32b285d2-18b40b534609ae4f-00","errors":{"id":["The value '{{no_id}}' is not valid."]}}


# 92. PUT/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users/0

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

ontent-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 1def3b65-5dbe-4d13-926c-3fa9bb741d6d
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id":{{id}},
  "userName": "string",
  "password": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:12:43 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-0e35113512548248b113d9b4176756af-65ee618195e4f84e-00","errors":{"id":["The value '{{id}}' is not valid."],"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 8."]}}

## 93. PUT/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users/-1

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 24ccbf21-e7b5-434c-a097-5a24674829a4
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id":{{id}},
  "userName": "string",
  "password": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:14:00 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-eb0a560091ab01478674f14fd9cdb618-c05825579a03064f-00","errors":{"id":["The value '{{id_minus}}' is not valid."],"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 8."]}}

## 94. PUT/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users/2147483648

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 7f20d7d8-64fd-4385-822b-c45690dc751d
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id":{{bad_id}},
  "userName": "string",
  "password": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:15:17 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-38157ee38888454f93d58c59e0b70522-a618a8d9c690a046-00","errors":{"id":["The value '{{bad_id}}' is not valid."],"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 8."]}}

## 95. PUT/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users/0

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 628bae85-da70-466b-9c13-93d3236116c5
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{
  "id":{{bad_body}},
  "userName": "string",
  "password": "string"
}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:20:01 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-42fd8f9ef1594d4d9d1d4165d769345d-312c1e376ecb3d4b-00","errors":{"id":["The value '{{id}}' is not valid."],"$.id":["The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 1 | BytePositionInLine: 8."]}}

## 96. PUT/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users/0

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 134ed3f7-13f5-4c53-8ab9-78ba8f043033
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

{no_body}

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:21:33 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-16e5e437d28e3b4688b02fd159c6f8d2-4d03dae572d76c4d-00","errors":{"$":["'n' is an invalid start of a property name. Expected a '\"'. Path: $ | LineNumber: 0 | BytePositionInLine: 1."],"id":["The value '{{id}}' is not valid."]}}

## 97. DELETE/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users/1

## Ожидаемый результат - Код ответа 200

## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: be3e194b-f64f-42a3-a9a7-37ca420909cd
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:23:12 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-28869a357f4a324392f66a98c4eec208-10d8e2b0c886b244-00","errors":{"id":["The value '{{id}}' is not valid."]}}


## 98. DELETE/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users/-1

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: f3bd8a71-7e0c-4a53-8d21-b0903a71b857
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
## Тело запроса



## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:24:19 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-0e79ffec16347f4b99179d3ef9b05f66-d0830885c2071240-00","errors":{"id":["The value '{{id_minus}}' is not valid."]}}


## 99. DELETE/api​/v1/Users


URL: https://fakerestapi.azurewebsites.net/api/v1/Users/2147483648

## Ожидаемый результат - Код ответа 400 Bad request


## Заголовки запроса

User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 8127ce0b-288c-4fa9-b3f8-6dec87d455ac
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive

## Тело запроса

Отсутствует

## Заголовки ответа

Content-Type: application/problem+json; charset=utf-8
Date: Tue, 04 Jul 2023 15:25:21 GMT
Server: Kestrel
Transfer-Encoding: chunked

## Тело ответа

{"type":"https://tools.ietf.org/html/rfc7231#section-6.5.1","title":"One or more validation errors occurred.","status":400,"traceId":"00-f3184738d9975144b278a4bc3c7680b1-d71c7b5cb0b25a45-00","errors":{"id":["The value '{{bad_id}}' is not valid."]}}


