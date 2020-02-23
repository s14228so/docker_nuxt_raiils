FROM node:12.9.0-alpine

WORKDIR /web
ADD . .

RUN apk update \
  && apk upgrade \
  && npm install \
  && rm -rf /var/cache/apk/*

ENV HOST 0.0.0.0
EXPOSE 3000
