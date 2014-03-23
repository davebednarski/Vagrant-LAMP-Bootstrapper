Vagrant LAMP Bootstrapper
======================================
Use this Vagrant virtual machine to get going on any web project using the LAMP stack.

## Linux
Ubuntu 12.04 LTS

## Apache
Not using Virtual hosts, but a virtual host template is included.


## PHP
 Extensions:
    'php5',
    'php-apc',
    'php5-curl',
    'php5-dev',
    'php5-fpm',
    'php5-gd',
    'php5-json',
    'php5-mysql',
    'php-pear',
    'php5-xdebug'

    See all configs in the pre-loaded phpinfo.php file http://localhost:8080/phpinfo.php

## MySQL
    root password is not set, set it before you launch in the mysql init.pp
