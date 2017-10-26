# nginx code
To solve Ubuntu 16.4 install nginx in a no network environment

## Library Version
pcre version 8.41
zlib version 1.2.11
nginx version 1.12.2

## Install on Ubuntu

```bash

$ sudo ./configure --prefix=/usr --sbin-path=/usr/sbin/nginx --conf-path=/etc/nginx/nginx.conf --error-log-path=/var/log/nginx/error.log --http-log-path=/var/log/nginx/access.log --pid-path=/var/run/nginx/nginx.pid --lock-path=/var/lock/nginx.lock --with-pcre=./pcre --with-zlib=./zlib
$ sudo make
$ sudo make install

```

## Documentation
Documentation is available at http://nginx.org
