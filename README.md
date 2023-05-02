## 環境構築

```shell
# dockerコンテナを作成します.
$ docker compose up -d

# dockerコンテナに入ります.
$ docker exec -it postgres bash

# PosstgreSQLへ接続します.
$ psql -h localhost -p 5432 -U postgres postgres

# dockerコンテナを削除します.
$ docker compose down --rmi all --volumes --remove-orphans
```
