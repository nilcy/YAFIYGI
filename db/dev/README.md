# DBマイグレーション / 開発環境

## DBコンテナ / PostgreSQL
- up / stop / rm
```
$ docker-compose up -d db
$ docker-compose stop
$ docker-compose rm
```

## DBマイグレーション / Flyway
- clean / migrate / info
```
$ docker-compose run --rm clean
$ docker-compose run --rm migrate
$ docker-compose run --rm info
```