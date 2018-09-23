# About this Repo

Minimal NGINX custom base image derived from official image built on Alpine 3.8. 
The image is only 6 MB and comes with some useful default configurations e.g. disable server signature, enables gzip compression, activates sending of no-transform header and open file cache configuration.

[![Docker Stars](https://img.shields.io/docker/stars/pritkin/nginx.svg)](https://hub.docker.com/r/pritkin/nginx/)
[![Docker Pulls](https://img.shields.io/docker/pulls/pritkin/nginx.svg)](https://hub.docker.com/r/pritkin/nginx/)
[![Docker Automated build](https://img.shields.io/docker/automated/pritkin/nginx.svg)](https://hub.docker.com/r/pritkin/nginx/builds/)
[![Build Status](https://travis-ci.org/magierjones/docker-nginx.svg?branch=master)](https://travis-ci.org/magierjones/docker-nginx)

## Usage

### Server
* Pull docker image and run:
```
docker pull pritkin/nginx:1.15.3
docker run -d -p 80:80 pritkin/nginx:1.15.3
```
or 

* Build and run container from source:
```
docker build -t nginx:1.15.3 .
docker run -d -p 80:80 nginx:1.15.3
```

## Resources
* https://alpinelinux.org/
* http://nginx.org