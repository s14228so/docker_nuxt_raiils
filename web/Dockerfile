FROM node:10-alpine


RUN apk update && \
  apk add git && \
  npm install -g npm  \
  npm install --global @vue/cli 

WORKDIR /web

ENV HOST 0.0.0.0
EXPOSE 3000