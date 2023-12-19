# Sysadmin
Final Project OS Server Web Server


# Progress
- 16/10/2023 Install Ubuntu 22.04
- 16/10/2023 Install Nginx, MariaDB, dan PHP
- 23/10/2023 Install WordPress 


Step 1 - Install Nginx, MariaDB, dan PHP
- $ sudo apt update
- $ sudo apt install nginx mariadb-server php php-fpm php-curl php-mysql php-gd php-mbstring php-xml php-imagick php-zip php-xmlrpc

Step 2 - Menyesuaikan firewall
- $ sudo ufw app list
- $ sudo ufw allow 'Nginx Full' // This will allow ports 80 for http and 443 for https.
- $ sudo ufw status

Step 3 - Check Webserver
- systemctl status nginx
- curl -4 icanhazip.com // Ini akan memberikan ip address

*** Instal PHP ***
- $ sudo apt update && sudo apt upgrade  // update and upgrade ubuntu
- $ sudo apt install software-properties-common ca-certificates lsb-release apt-transport-https
- $ $ LC_ALL=C.UTF-8 sudo add-apt-repository ppa:ondrej/php 
- $ LC_ALL=C.UTF-8 sudo add-apt-repository ppa:ondrej/nginx
- $ sudo apt update  // update the Apt package manager cache.
- $ sudo apt install php8.1 // Install php. Use the version that you need.
- $ sudo apt install php8.1-mysql php8.1-mbstring php8.1-xml php8.1-curl 
- $ sudo apt install php-fpm







