FROM php:7.4-apache
COPY ./sites-available/ /etc/apache2/sites-available
RUN apt-get update && apt-get upgrade -y
EXPOSE 80
