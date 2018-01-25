## GET /users
APIでuser一覧を取得する.

### Example

#### Request
```
GET /users HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 200
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 259
Content-Type: application/json; charset=utf-8
ETag: W/"722341f69e5350d5ff0ba4cddcb6c5c7"
X-Request-Id: 17862fc0-c3c1-4039-80b0-0e6c9a4d6bb4
X-Runtime: 0.030691

[
  {
    "id": 1,
    "name": "ユーザーテスト",
    "age": 30,
    "created_at": "2018-01-25T15:52:59.528Z",
    "updated_at": "2018-01-25T15:52:59.528Z"
  },
  {
    "id": 2,
    "name": "ユーザーテスト",
    "age": 30,
    "created_at": "2018-01-25T15:52:59.532Z",
    "updated_at": "2018-01-25T15:52:59.532Z"
  }
]
```
