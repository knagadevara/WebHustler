- Install PHP

    yum install php php-fpm

- Create a php-fpm site

    touch /etc/php-fpm.d/<site-name>.com

- Configure php-fpm server with [help-doc](https://www.digitalocean.com/community/tutorials/php-fpm-nginx)

- Create a user and group for php-fpm, then map it in fpm conf 

