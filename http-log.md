# HTTP Request/Response Log

## Request 1 — Get Post 1

### Request

curl.exe -i https://jsonplaceholder.typicode.com/posts/1


### Response



HTTP/1.1 200 OK
Date: Fri, 14 Aug 2026 20:21:05 GMT
Content-Type: application/json; charset=utf-8
Content-Length: 292
Connection: keep-alive
access-control-allow-credentials: true
Cache-Control: max-age=43200
etag: W/"124-yiKdLzqO5gfBrJFrcdJ8Yq0LGnU"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=UyhbZ%2F0MO1mJoZS7M4Hj8SWBXp3NkwnJgHEYoqocyDE%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1785191026"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=UyhbZ%2F0MO1mJoZS7M4Hj8SWBXp3NkwnJgHEYoqocyDE%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1785191026"
Server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1785191063
Age: 15317
Accept-Ranges: bytes
cf-cache-status: HIT
CF-RAY: a2b2a9f5ecad224e-AMS
alt-svc: h3=":443"; ma=86400

{
  "userId": 1,
  "id": 1,
  "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
  "body": "quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto"
}




### Annotation

- Status: 200 OK — The request was successful and the server returned the requested resource.
- Content-Type: application/json; charset=utf-8 — The response body is JSON encoded using UTF-8.

## Request 2 — Get Post 2

### Request

curl.exe -i https://jsonplaceholder.typicode.com/posts/2

### Response
HTTP/1.1 200 OK
Date: Fri, 14 Aug 2026 20:23:10 GMT
Content-Type: application/json; charset=utf-8
Content-Length: 278
Connection: keep-alive
access-control-allow-credentials: true
Cache-Control: max-age=43200
etag: W/"116-jnDuMpjju89+9j7e0BqkdFsVRjs"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=OEU8njcEseoc%2BWQeH%2FjCu8NTvmnyUb3trHBNEFU0v8Q%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1786302470"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=OEU8njcEseoc%2BWQeH%2FjCu8NTvmnyUb3trHBNEFU0v8Q%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1786302470"
Server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 864
x-ratelimit-reset: 1786302475
Age: 1538
Accept-Ranges: bytes
cf-cache-status: HIT
CF-RAY: a2b2ad005e4723e3-AMS
alt-svc: h3=":443"; ma=86400

{
  "userId": 1,
  "id": 2,
  "title": "qui est esse",
  "body": "est rerum tempore vitae\nsequi sint nihil reprehenderit dolor beatae ea dolores neque\nfugiat blanditiis voluptate porro vel nihil molestiae ut reiciendis\nqui aperiam non debitis possimus qui neque nisi nulla"
}
### Annotation

- Status: 200 OK — The request was successful and the server returned the requested resource.
- Content-Type: application/json; charset=utf-8 — The response body is JSON encoded using UTF-8.

## Request 3 — Get User 1

### Request

curl.exe -i https://jsonplaceholder.typicode.com/users/1

### Response
HTTP/1.1 200 OK
Date: Fri, 14 Aug 2026 20:24:23 GMT
Content-Type: application/json; charset=utf-8
Content-Length: 509
Connection: keep-alive
access-control-allow-credentials: true
Cache-Control: max-age=43200
etag: W/"1fd-+2Y3G3w049iSZtw5t1mzSnunngE"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=m23T6Tj%2BQUZnIwphHAim1ChY9yjwiqMeEy5yHiMrfN0%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1785634999"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=m23T6Tj%2BQUZnIwphHAim1ChY9yjwiqMeEy5yHiMrfN0%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1785634999"
Server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1785635057
Age: 1997
Accept-Ranges: bytes
cf-cache-status: HIT
CF-RAY: a2b2aec87958b94b-AMS
alt-svc: h3=":443"; ma=86400

{
  "id": 1,
  "name": "Leanne Graham",
  "username": "Bret",
  "email": "Sincere@april.biz",
  "address": {
    "street": "Kulas Light",
    "suite": "Apt. 556",
    "city": "Gwenborough",
    "zipcode": "92998-3874",
    "geo": {
      "lat": "-37.3159",
      "lng": "81.1496"
    }
  },
  "phone": "1-770-736-8031 x56442",
  "website": "hildegard.org",
  "company": {
    "name": "Romaguera-Crona",
    "catchPhrase": "Multi-layered client-server neural-net",
    "bs": "harness real-time e-markets"
  }
}


### Annotation

- Status: 200 OK — The request was successful and the server returned the requested user resource.
- Content-Type: application/json; charset=utf-8 — The response body is JSON encoded using UTF-8.

## Request 4 — Get Comm ent 1

### Request

curl.exe -i https://jsonplaceholder.typicode.com/comments/1

### Response
HTTP/1.1 200 OK
Date: Fri, 14 Aug 2026 20:24:53 GMT
Content-Type: application/json; charset=utf-8
Content-Length: 268
Connection: keep-alive
access-control-allow-credentials: true
Cache-Control: max-age=43200
etag: W/"10c-KJ4I9RM/+33TKdV8CFsIvqsDSP0"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=RkJUNhKkOLxIsCcJ8F%2F0pPzTMGx09fxRdqVaqVap%2Fe0%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1786723924"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=RkJUNhKkOLxIsCcJ8F%2F0pPzTMGx09fxRdqVaqVap%2Fe0%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1786723924"
Server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 968
x-ratelimit-reset: 1786723930
Age: 15169
Accept-Ranges: bytes
cf-cache-status: HIT
CF-RAY: a2b2af875aac40a8-SIN
alt-svc: h3=":443"; ma=86400

{
  "postId": 1,
  "id": 1,
  "name": "id labore ex et quam laborum",
  "email": "Eliseo@gardner.biz",
  "body": "laudantium enim quasi est quidem magnam voluptate ipsam eos\ntempora quo necessitatibus\ndolor quam autem quasi\nreiciendis et nam sapiente accusantium"
}

### Annotation

- Status: 200 OK — The request was successful and the server returned the requested comment resource.
- Content-Type: application/json; charset=utf-8 — The response body is JSON encoded using UTF-8.

## Request 5 — Deliberate 404

### Request

curl.exe -i https://jsonplaceholder.typicode.com/abc

### Response
HTTP/1.1 404 Not Found
Date: Fri, 14 Aug 2026 20:25:39 GMT
Content-Type: application/json; charset=utf-8
Content-Length: 2
Connection: keep-alive
access-control-allow-credentials: true
Cache-Control: max-age=43200
etag: W/"2-vyGp6PvFo4RvsFtPoIWeCReyIC8"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=qjG0XLEGXA1B%2Fd8dxE8wvxcP12iz1ZV4ITW6GLuAr60%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1786739139"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=qjG0XLEGXA1B%2Fd8dxE8wvxcP12iz1ZV4ITW6GLuAr60%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1786739139"
Server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1786739170
cf-cache-status: EXPIRED
CF-RAY: a2b2b0a2891766b4-AMS
alt-svc: h3=":443"; ma=86400

{}

### Annotation

- Status: 404 Not Found — The requested resource does not exist on the server.
- Content-Type: application/json; charset=utf-8 — The response body is JSON encoded using UTF-8.