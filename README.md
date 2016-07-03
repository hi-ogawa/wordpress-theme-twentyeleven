### Fork of Wordpress Theme Twentyeleven

```
$ wget https://downloads.wordpress.org/theme/twentyeleven.2.4.zip
$ unzip twentyeleven.2.4.zip
$ cd twentyeleven
$ git init && git add . && git ci -m 'clone twentyeleven'
```

### Features

- Mathjax ([commit](https://github.com/hi-ogawa/wordpress-theme-twentyeleven/commit/0809f054837d389365bb4800a58609a3b2d79ea3)): https://www.mathjax.org/
- Google code prettify ([commit](https://github.com/hi-ogawa/wordpress-theme-twentyeleven/commit/7c7326cb02bf36eb6b90a36646fcb00713ca5b99)): https://github.com/google/code-prettify,
- Ahrefy ([commit](https://github.com/hi-ogawa/wordpress-theme-twentyeleven/commit/820bd75ef5b73bdd0ee913781ef7e73c2de5a361)): https://github.com/hi-ogawa/ahrefy,
- and some style changes


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
-- start wordpress --
$ docker-compose up -d
Starting twentyeleven_wordpress_1
Starting twentyeleven_mysql_1
$ open http://<docker-ip>:6789

-- stop wordpress --
$ docker-compose down    # if you add -v option, it will delete clean up all data
```
