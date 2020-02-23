# setup

```
$ git clone https://github.com/s14228so/docker_nuxt_raiils
$ cd docker_nuxt_raiils
$ docker-compose run api rails new . --force --database=mysql --api
$ vi api/config/database.yml(defaultのpasswordをpassword、defaultのhostをlocalhostからdbに編集)
$ docker-compose build (no such file or directory, open '/web/package.json'とかエラーが出るけど無視でok)
$ docker-compose run api rails db:create
$ docker-compose run web sh
$ npm install -g create-nuxt-app (コンテナの中で)
$ create-nuxt-app . (コンテナの中で)
$ exit
$ docker-compose up -d 
```
