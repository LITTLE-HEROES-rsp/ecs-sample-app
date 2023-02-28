# Dockerコマンド一覧

- ビルド  
dockerフォルダの中身を変更した場合は、下記を実行する。  
```console
$ docker compose build --no-cache
```

- コンテナ起動  
```console
$ docker compose up -d
```

- コンテナ停止  
```console
$ docker compose down
```

# サンプルプログラム
テストプログラムでは、phpinfoの情報と、環境変数（ENV_NAME）の情報を表示します。
