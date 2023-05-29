# 概要
- dbmap.AddTableWithNameを使ってDB名と構造体をマッチさせる。
- db tagを使ってDBと構造体をマッピングする。

```shell
# 手元で実行する
# 削除系の処理をコメントアウトして実行
go run main.go
```

```shell

# DBを触る
sqlite3 /tmp/post_db.bin
.table
.schema posts
 select * from posts;
.exit
```

# 初期設定
```shell
go get 	github.com/go-gorp/gorp
```

# 参考
https://github.com/go-gorp/gorp