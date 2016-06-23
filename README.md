### Fork of Wordpress Theme Twentyeleven

```
$ wget https://downloads.wordpress.org/theme/twentyeleven.2.4.zip
$ unzip twentyeleven.2.4.zip
$ cd twentyeleven
$ git init && git add . && git ci -m 'clone twentyeleven'
```

### Development

Tools version:

```
$ docker -v
Docker version 1.11.1, build 5604cbe
$ docker-compose -v
docker-compose version 1.7.0, build 0d7bf73
```

Commands:

```
$ docker-compose up -d
Starting twentyeleven_wordpress_1
Starting twentyeleven_mysql_1
$ open http://<docker-ip>:6789
```
