## install php version manager (ada yang lain: phpbrew)

```bash
$ sudo apt install software-properties-common
$ sudo add-apt-repository ppa:ondrej/php
$ sudo apt update
```

## install php^\*

```bash
$ sudo apt-get install php8.2 php8.2-fpm
$ sudo apt-get install php8.2-mysql php8.2-mbstring php8.2-xml php8.2-gd php8.2-curl
```

## switch version

```bash
$ sudo update-alternatives --config php
```

## To change the default version

```bash
$ sudo update-alternatives --set php /usr/bin/php7.4
```

## Verifikasi Instalasi

```bash
$ php8.1 -v
```

## cek ekstensi

```bash
$ php8.1 -m
```

## install ektensi tertentu

```bash
$ sudo apt install php8.1-intl
```
