# DjangoGirls Tutorial

Docker composeも試しつつ検証

$ docker-compose up -d

$ docker container stop  djangogirls-tutorial_web_1

通常コンテナ内で操作する必要があるため先頭に
docker-compose run web
を入れる必要があり

$ docker-compose run web python3 manage.py migrate


