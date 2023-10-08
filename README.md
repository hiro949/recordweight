# recordeihts

SQLコンテナの起動

```
docker-compose up -d --build
```

ORM APIの起動
```
go run main.go
```

操作方法

- phpAdmin: localhost:8080 (モニタリング)
- API: localhost:8000
  - POST: /item (upload new record)
  - DELETE: /item (delete)
  - PUT: /item (update)
  - GET: /items (fetch all record)
  - GET: /iteme/{id} (fetch a record)

Ref:
- https://qiita.com/stranger1989/items/914bef8cc6ad77ef8350
- https://qiita.com/leafeon00000/items/e190cf92af3a487cc749
