# Sysadmim
Tugas Akhir OS Server Web Server

# Progress
- 16/10/2023 Instal Ubuntu 22.04
- 16/10/2023 Instal Nginx
- 19/10/2023 Instal PHP

# Web Server 
*** Install nginx di ubuntu 22.04 ***

Step 1 - Install Nginx
- $ sudo apt update
- $ sudo apt install nginx

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







