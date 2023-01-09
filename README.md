# LKT PHP 7.3 Apache

A pre-configured docker file, so you can have an apache php 7.3 server working in just five minutes.

## Included configuration:
- Apache2 mod_rewrite
- PDO, PDO MySQL, mysqli, mariadb-client
- Zip
- Intl

## Installation
Simply clone this repo.

## Build the image
Move to this directory and type in a terminal:

```shell
sudo docker build -t lkt-php73-apache:latest .
```

## Launch a container
```shell
sudo docker run -d -p 80:80 --name lkt-php73-apache lkt-php73-apache:latest
```

## Open container terminal
```shell
sudo docker exec -ti lkt-php73-apache bash
```

## Stop
```shell
sudo docker stop lkt-php73-apache
```

## Remove
```shell
sudo docker rm lkt-php73-apache
```