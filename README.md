# Sysadmim
Tugas Akhir OS Server Web Server

# Progress
- 16/10/2023 Instal Ubuntu 22.04
- 16/10/2023 Instal Nginx 

# Web Server
Using nginx, php, mariadb, cerbot, filezila 
*** Install nginx di ubuntu 22.04 ***
Step - 1 Install Nginx 
- $ sudo apt update
- $ sudo apt install nginx
Step - 2 Menyesuaikan Firewall 
- $ sudo ufw app list
- $ sudo ufw allow 'Nginx Full' // This will allow ports 80 for http and 443 for https.
- $ sudo ufw status
Step - 3 Check Web Server
- systemctl status nginx
- curl -4 icanhazip.com // Ini akan memberikan ip address




