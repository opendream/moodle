[![](https://images.microbadger.com/badges/image/opendream/moodle.svg)](https://microbadger.com/images/opendream/moodle "Get your own image badge on microbadger.com")[![license](https://img.shields.io/github/license/mashape/apistatus.svg)]()[![Docker Build Statu](https://img.shields.io/docker/build/opendream/moodle.svg)]()

# Moodle
A lightweight Docker container for Moodle. 🙏

This image is based on PHP's [fpm-alpine image](https://hub.docker.com/_/php/) with additional PHP extensions that required by **Moodle 3.3+** : `gd`, `zip`, `mysqli`, `opcache`, `xmlrpc`, `soap` and `intl`.

# Installation

* `git clone https://github.com/opendream/moodle.git`
* `cd moodle`
* `docker build -t moodle .`

# Docker Compose

You can try another Docker Compose example that created for `Moodle 3.3+`, `Nginx`, `FPM 7` and `MariaDB` using the following Docker Compose.

* `git clone https://github.com/kengggg/moodle-docker-example.git`
* `cd moodle-docker-example`
* `docker-compose build`
* `docker-compose up`

Your moodle installation can be accessed through `http://localhost:8080`.
