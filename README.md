# docker-django-postgre

### ローカル環境
- docker 20.10
- docker-compose 1.27.4
- git 2.25

### 作成する環境
- Python 3.9.6
- PostgreSQL 13.4
- nginx 1.20.1

### サービスの構築
```
$ docker-compose build
```

### コンテナの作成と立ち上げ
```
$ docker-compose up
```

### アプリのコンテナに接続
```
$ docker-compose exec app bash
```

### Djangoインストールコマンド
```
$ docker-compose exec app django-admin.py startproject app .
```
