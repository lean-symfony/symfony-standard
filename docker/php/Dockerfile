FROM php:fpm-alpine

MAINTAINER Micha Alt <mail@lean-stack.de>

RUN apk add --update \
    binutils \
    icu-dev

RUN docker-php-ext-install intl
RUN docker-php-ext-enable opcache.so
