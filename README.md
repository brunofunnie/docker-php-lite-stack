# Docker PHP Lite Stack

Here you have the very basic to create a php application
## Containers

This web/http container doesn't have SSL enabled

- NGINX
- PHP 8.1.10 (extra extensions: redis, xdebug, event, intl, opcache, pdo_mysql, mcrypt, pcntl, sockets)
- Composer
- MySQL 5.7
- Mailhog SMTP Mailtrap

## Environment Vars

For Xbebug to work you must export the following environment variable (PS: Change the example IP to your host machine IP address):

```bash
export DOCKER_HOST_IP=192.168.0.1
```

## URLs

Localhost
[http://127.0.0.1:8080](http://127.0.0.1:8080)

PhpMyAdmin
[http://127.0.0.1:8081](http://127.0.0.1:8081)

Mailhog
[http://127.0.0.1:8025](http://127.0.0.1:8025)