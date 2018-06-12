FROM phpearth/php7.0-nginx

RUN apk add --no-cache composer
RUN apk add --no-cache phpunit

COPY . /src/app
RUN composer install
