FROM php:5.6-apache

RUN apt-get update && apt-get install -y \
        zlib1g-dev \
        zip \
        && rm -rf /var/lib/apt/lists/*



RUN docker-php-ext-install mysqli zip

COPY wp-files /var/www/html
