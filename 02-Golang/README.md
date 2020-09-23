# 使い方

```
$ docker-compose build
$ docker-compose run --rm golang go mod init
$ docker-compose up -d
```

src/server/main.goがホットリロード環境で動作します。
go modulesを使用しているため、ginを使っていますが、go getコマンドは使用する必要がありません。
※ 以降も依存モジュールをgo getする必要はありません。