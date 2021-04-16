FROM php:8.0-fpm-alpine

LABEL maintainer="DucLS <ducls.coder@gmail.com>"

ARG DEBIAN_FRONTEND=noninteractive

RUN docker-php-ext-install \
  bcmath \
  pdo_mysql

RUN mkdir -p /var/www/html

COPY ./src /var/www/html