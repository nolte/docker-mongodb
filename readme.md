# RPI MongoDB

[![Build Status](https://travis-ci.org/nolte/docker-mongodb.svg?branch=master)](https://travis-ci.org/nolte/docker-mongodb)


[![Docker Pulls](https://img.shields.io/docker/pulls/nolte/rpi-mongo.svg)](https://hub.docker.com/r/nolte/rpi-mongo/) [![](https://images.microbadger.com/badges/image/nolte/rpi-mongo.svg)](https://microbadger.com/images/nolte/rpi-mongo "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/version/nolte/rpi-mongo.svg)](https://microbadger.com/images/nolte/rpi-mongo "Get your own version badge on microbadger.com")


Simple Armhf docker container for a [mongoDB](https://www.mongodb.com), tested on RPI2 with [hypriot](https://blog.hypriot.com/).

## How To Start

```
docker build -t nolte/rpi-mongo:development -f DockerfileRPI .
```
or use the compose file

```
docker-compose up -d
```
