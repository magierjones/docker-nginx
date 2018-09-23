# About this Repo

NGINX custom base image derived from official image with
some useful default configurations e.g. disable server signature, enables gzip compression, activates sending of no-transform header and open file cache configuration.

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