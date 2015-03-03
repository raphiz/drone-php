FROM php:5.5.20

# Install git
RUN apt-get update -yqq
RUN apt-get install git -yqq

# Install composer
RUN php -r "readfile('https://getcomposer.org/installer');" | php
RUN mv composer.phar /usr/local/bin/composer

# Install phpunit
RUN curl -O https://phar.phpunit.de/phpunit.phar
RUN chmod a+x phpunit.phar
RUN mv phpunit.phar /usr/local/bin/phpunit
