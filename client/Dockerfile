FROM node:lts-alpine

WORKDIR /src

EXPOSE 3000

RUN apk update \
    && apk upgrade \
    && apk add --no-cache --upgrade bash