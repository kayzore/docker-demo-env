FROM php:7.2-fpm

RUN { \
        echo 'error_reporting  =  E_ALL'; \
        echo 'log_errors = On'; \
        echo 'display_errors = Off'; \
    } > /usr/local/etc/php/php.ini

CMD ["php-fpm"]

WORKDIR /usr/local/apache2/htdocs/

EXPOSE 9000