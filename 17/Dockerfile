FROM php:7.4-cli
COPY . /var/www/docker.loc
WORKDIR /var/www/docker.loc/public
CMD [ "php", "-S", "0.0.0.0:8080"]
EXPOSE 8080
RUN apt-get update && apt-get install -y && docker-php-ext-install pdo_mysql
