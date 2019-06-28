FROM cloudobjects/php-app-base

RUN yum -y install make
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

ENTRYPOINT ["make"]