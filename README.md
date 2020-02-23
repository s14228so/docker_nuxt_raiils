# docker_nuxt_raiils


# setup

```
$ git clone https://github.com/s14228so/docker_nuxt_raiils
$ cd docker_nuxt_raiils
$ docker-compose run api bundle exec rails new . --force --database=mysql --skip-bundle
$ vi config/database.yml(defaultのpasswordをpassword、defaultのhostをlocalhostからdbに編集)
$ docker-compose run api rails db:create
$ docker-compose build && docker-compose up -d
$ docker exec -it web /bin/sh
```
