# MySQL5.6とMySQL8.0をためす

* MySQL5.6 ポート 3305で起動
* MySQL8.0 ポート 3306で起動
* linuxserver/MySQLWorkbenchを試しに

## linuxserver/mysql-workbench の起動

* http://localhost:3000
* https://localhost:3001
* http://127.0.0.1:3000
* https://127.0.0.1:3001
* コンテナのMySQLへ接続するも失敗している。どうやって繋げられるのか？
* MySQL8 CLI から各コンテナのMySQLへ接続できることは確認済み。

## コンテナ起動

```sh
# start
$> cd home/user/mysqltest/
$> docker compose up -d

# stop
$> cd home/user/mysqltest/
$> docker compose stop
```

## 出典
* [Docker Hub MySQL](https://hub.docker.com/_/mysql)
* [linuxserver/mysql-workbench](https://hub.docker.com/r/linuxserver/mysql-workbench)
