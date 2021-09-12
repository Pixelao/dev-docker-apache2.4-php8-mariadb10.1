# Docker Containers ready for Development 

__Apache2.4, PHP-8-FPM & Mariadb10.1__

### Dependencies and needs

- [Install Docker](https://docs.docker.com/install/)
- [Install Docker Compose](https://docs.docker.com/compose/install/)

### Installing

* First, create a new directory at the root called "public_html", here inside you must clone or init your project
* Start the containers with command:
    ```bash
    docker-compose up -d
    ```

### Help

The docker-project is based on 3 containers

* skeleton-docker.apache __(Apache 2.4, container image httpd:2.4-alpine)__
* skeleton-docker.php __(PHP-8, container image php:8-fpm-alpine)__
* skeleton-docker.mariadb __(MariaDb 10.1, container image mariadb:10.1)__

You can check Apache and PHP logs on __docker/apache/logs__

### Versions and modules

- [Apache-2.4](https://httpd.apache.org/docs/2.4/en/)
- [MariaDB-10.1](https://downloads.mariadb.org/mariadb/10.1.41/)
- [PHP-8-FPM](https://www.php.net/ChangeLog-8.php)
  - [PHP Modules]
    - bcmath
    - Core
    - ctype
    - curl
    - date
    - dom
    - exif
    - fileinfo
    - filter
    - ftp
    - gd
    - hash
    - iconv
    - intl
    - json
    - libxml
    - mbstring
    - mysqli
    - mysqlnd
    - openssl
    - pcre
    - PDO
    - pdo_mysql
    - pdo_pgsql
    - pdo_sqlite
    - Phar
    - posix
    - rar
    - readline
    - redis
    - Reflection
    - session
    - SimpleXML
    - soap
    - sodium
    - SPL
    - sqlite3
    - standard
    - tokenizer
    - xdebug
    - xml
    - xmlreader
    - xmlwriter
    - xsl
    - Zend OPcache
    - zip
    - zlib

  - [Zend Modules]
    - Xdebug
    - Zend OPcache

## Authors

Contributors names and contact info

__[@Pixelao](https://github.com/pixelao), Adrián Martín__

## Version History

* __0.1__
    * Initial Release

