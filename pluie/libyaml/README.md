# pluie/libyaml

- [index][1]
- [pluie/alpine][2]                       ( ~  9 MB ) Alpine/3.5
    - [pluie/alpine-apache][3]            ( ~ 50 MB ) Apache/2.4.25 Php/5.6.30
    - [pluie/alpine-apache-fpm][7]        ( ~ 51 MB ) Apache/2.4.25 Php/5.6.30 Fpm
        - [pluie/alpine-symfony][6]       ( ~ 83 MB ) Symfony2.8 or 3.2
    - [pluie/alpine-apache-php7][8]       ( ~ 45 MB ) Apache/2.4.25 Php/7.0.16
        - [pluie/alpine-symfony-php7][9]  ( ~ 77 MB ) Symfony2.8 or 3.2 Php/7.0.16
    - [pluie/alpine-mysql][4]             ( ~181 MB ) Mysql/5.6 ( MariaDB )
    - [pluie/libecho][10]                 ( ~288 MB ) Vala 0.34.2 pluie-echo-0.2
        - [pluie/libyaml][11]                 ( ~299 MB ) Vala 0.34.2 pluie-yaml-0.4
- [docker tips][5]


demo image demonstrating pluie-yaml, a shared vala library managing yaml files (v 1.2) and yaml nodes in vala language.
As json is now a valid subset of yaml, you can use this lib to load json files too

you can run a container with :

```
docker run --rm -it pluie/libyaml
```

then execute any samples :

./yaml-loader
./json-loader
./yaml-config
./yaml-traversing
./yaml-finder
./yaml-imports
./yaml-node

## repository

https://github.com/pluie-org/lib-yaml

## samples

./yaml-config source code

![Sample yaml-config code](https://www.meta-tech.academy/img/lib-yaml-config-code.png?tmp=1)

./yaml-config output

![Sample yaml-config output1](https://www.meta-tech.academy/img/lib-yaml-docker-config1.png?tmp=1)
![Sample yaml-config output2](https://www.meta-tech.academy/img/lib-yaml-docker-config2.png?tmp=1)


 [1]: https://github.com/pluie-org/docker-images
 [2]: https://github.com/pluie-org/docker-images/tree/master/pluie/alpine
 [3]: https://github.com/pluie-org/docker-images/tree/master/pluie/alpine-apache
 [4]: https://github.com/pluie-org/docker-images/tree/master/pluie/alpine-mysql
 [7]: https://github.com/pluie-org/docker-images/tree/master/pluie/alpine-apache-fpm
 [5]: https://github.com/pluie-org/docker-images/blob/master/DOCKER.md
 [6]: https://github.com/pluie-org/docker-images/tree/master/pluie/alpine-symfony
 [8]: https://github.com/pluie-org/docker-images/tree/master/pluie/alpine-apache-php7
 [9]: https://github.com/pluie-org/docker-images/tree/master/pluie/alpine-symfony-php7
 [10]: https://github.com/pluie-org/docker-images/tree/master/pluie/libecho
 [11]: https://github.com/pluie-org/docker-images/tree/master/pluie/libyaml