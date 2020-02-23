# docker_nuxt_raiils


# setup

```
$ git clone https://github.com/s14228so/docker_nuxt_raiils
$ cd docker_nuxt_raiils
$ docker-compose run api rails new . --force --database=mysql --api
$ vi config/database.yml(defaultのpasswordをpassword、defaultのhostをlocalhostからdbに編集)
$ docker-compose build 
$ docker-compose run api rails db:create
$ docker-compose run web npx create-nuxt-app .
```
