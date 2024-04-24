ARG php_version
FROM php:${php_version}-fpm

LABEL version="1.0"
LABEL name="PHP"

## install the PHP extensions we need
RUN docker-php-ext-install mysqli

