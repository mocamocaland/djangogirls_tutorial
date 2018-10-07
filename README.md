# DjangoGirls Tutorial

`docker-compose` も試しつつ検証
```
$ docker-compose up -d

$ docker container start  `container NAMES`

$ docker container stop  'container Names'
```
通常コンテナ内で操作する必要があるため先頭に

`docker-compose run web` を入れる必要があり
```
$ docker-compose run web python3 manage.py migrate
```

コンテナ内にアクセス
```
$ docker container exec -it  djangogirls-tutorial_web_1  /bin/bash
```