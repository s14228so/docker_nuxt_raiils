FROM node:10-alpine
RUN npm install -g vue-cli

RUN mkdir /hack
RUN mkdir /hack/docker_nuxt

ENV APP_ROOT /hack/docker_nuxt
WORKDIR $APP_ROOT

ENV HOST 0.0.0.0
EXPOSE 3000