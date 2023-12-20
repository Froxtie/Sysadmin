# Sysadmin
Final Project OS Server Web Server

# Machine
- Laptop
- Virtual Machine
- Ubuntu 22.04

# Progress
- 16/10/2023 Install Ubuntu 22.04
- 16/10/2023 Install Nginx, MariaDB, dan PHP
- 23/10/2023 Install WordPress
- 25/10/2023 Install OpenSSH
- 9/12/2023 Install Webmin


Step 1 - Install Nginx, MariaDB, dan PHP
- $ sudo apt update
- $ sudo apt install nginx mariadb-server php php-fpm php-curl php-mysql php-gd php-mbstring php-xml php-imagick php-zip php-xmlrpc
- $ ufw allow 80 
- $ Konfigurasi PHP, dan MariaDB

Step 2 - Install WordPress
- $ cd /var/www/html
- $ wget https://wordpress.org/latest.tar.gz
- $ Extract File dengan perintah tar -zxvf latest.tar.gz
- $ chown -R www-data:www-data /var/www/html/wordpress
- $ chmod -R 755 /var/www/html/wordpress
- $ Konfigurasi WordPress dengan perintah nano /etc/nginx/conf.d/wordpress.conf
- $ Bikin Local domain dengan perintah sudo nano /etc/hosts


Step 3 - Install OpenSSH
- $ sudo apt install openssh-server
- $ sudo systemctl enable --now ssh
- $ sudo systemctl status ssh
- $ sudo ufw allow ssh
- $ sudo ufw enable && sudo ufw reload

Step 4 - Install Webmin
- $ wget https://github.com/webmin/webmin/releases/download/2.000/webmin_2.000_all.deb
- $ sudo dpkg -i webmin_2.000_all.deb
- $ sudo apt-get install -f












