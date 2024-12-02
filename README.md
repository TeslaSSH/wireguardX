<h2 align="center">WireGuard VPS Installer <img src="https://img.shields.io/badge/Version-1.0.0-blue.svg"></h2>


<h2 align="center">Supported Linux Distributions</h2>
<p align="center">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=red">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2022.04&message=Jammy&color=orange">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2023.04&message=Lunar&color=orange">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=fedora&label=Fedora&message=37&color=blue">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=centos&label=CentOS%208&message=Stream&color=green">
</p>



 <p align="center"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=powershell&label=Script%20By&message=Tesla%20SSH&color=blue"></p>


<h3 align="center">Screenshots</h3>
<p align="center">
<img src="https://github.com/TeslaSSH/wireguardX/raw/main/assets/shot.jpg">
   </p>

  ## Installation Command :

  ```html
rm -rf main.sh; wget --no-cache -O main.sh "https://raw.githubusercontent.com/TeslaSSH/wireguardX/refs/heads/main/main.sh" && chmod +x main.sh; ./main.sh

  ```

## Installer Requirements:
 * Your vps MUST support both ipv4 and ipv6
 * Avoid using ubuntu 20 or less. always Go for ubuntu 22 or the newest.
 * A licence Key is required to install this script.
   
 ## Usage : 
 * Just run the installation command above in your VPS, reboot when done installing.
 * Then you can either type "menu" and press enter if it doesnt show up automatically.



## Main Features :
* User friendly interface for managing clients. 
* Traffic congestion control engine enabled by default.
* Robust qrcode generator.
* You can ban users.
* And many more!
  
## Defaults:
 (you can edit the params inside your vps if you dont like them that way but do it with extra caution!) 
 
    SERVER_PUB_NIC="eth0"
    SERVER_WG_NIC="wg0"
    SERVER_WG_IPV4="10.66.66.1"
    SERVER_WG_IPV6="fd42:42:42::1"
    CLIENT_DNS_1="1.1.1.1"
    CLIENT_DNS_2="1.0.0.1"
    ALLOWED_IPS="0.0.0.0/0,::/0"

## VPS Providers :
* Digital Ocean
* Akamai
* Zero Contract Devs 👇 

## PURCHASE KEY :  <a href="https://t.me/teslassh" target=”_blank”><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=Telegram&label=Telegram&message=Click%20Here&color=blue"></a>

