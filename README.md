--- install php version manager --- (ada yang lain: phpbrew)
sudo apt install software-properties-common
sudo add-apt-repository ppa:ondrej/php
sudo apt update


--- install php^* ---
sudo apt-get install php8.2 php8.2-fpm
sudo apt-get install php8.2-mysql php8.2-mbstring php8.2-xml php8.2-gd php8.2-curl

--- switch version ---
sudo update-alternatives --config php


--- To change the default version ---
sudo update-alternatives --set php /usr/bin/php7.4

--- Verifikasi Instalasi ---
php8.1 -v

--- cek ekstensi ---
php8.1 -m

--- install ektensi tertentu ---
sudo apt install php8.1-intl

