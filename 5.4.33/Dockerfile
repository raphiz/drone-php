FROM raphiz/drone-php:5.4.33-minimal

# Install composer
RUN php -r "readfile('https://getcomposer.org/installer');" | php
RUN mv composer.phar /usr/local/bin/composer

# Install phpunit
RUN curl -O https://phar.phpunit.de/phpunit.phar
RUN chmod a+x phpunit.phar
RUN mv phpunit.phar /usr/local/bin/phpunit
