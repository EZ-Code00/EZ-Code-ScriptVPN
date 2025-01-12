 <p align="center">


<h2 align="center">
Auto Script VPS
Created By EZ-Code
<img src="https://img.shields.io/badge/VERSION-2-blue.svg"></h2>

</p> 
<h2 align="center"> Supported Linux Distribution</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"width="400"></p> 
<p align="center">
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=purple">  
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2011&message=Bullseye&color=purple"> 
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2012&message=BookWorm&color=purple"> 
<p align="center">
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=ubuntu%2018.04 LTS&message=Bionic Beaver&color=red"> 
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=ubuntu%2020.04 LTS&message=Focal Fossa&color=red">
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=ubuntu%2022.04 LTS&message=Jammy Jellyfih&color=red">
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=ubuntu%2024.04 LTS&message=Noble Numbat&color=red">
</p>



<h2 align="center">Network VPN</h2>

<h2 align="center">

![Hits](https://img.shields.io/badge/SSH-Service-8020f3?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)
![Hits](https://img.shields.io/badge/OVPN-Service-8020f3?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)
![Hits](https://img.shields.io/badge/WIREGUARD-Service-8020f3?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)
![Hits](https://img.shields.io/badge/Shadowsocks-Obfs-8020f3?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)
![Hits](https://img.shields.io/badge/XRAY-Vmess-f34b20?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)
![Hits](https://img.shields.io/badge/XRAY-VLess-f34b20?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)
![Hits](https://img.shields.io/badge/XRAY-Trojan-f34b20?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)
</h2>

PLEASE MAKE SURE YOUR DOMAIN SETTINGS IN YOUR CLOUDFLARE AS BELOW (SSL/TLS SETTINGS)<br>
<br>

1. Your SSL/TLS encryption mode is Full
2. Enable SSL/TLS Recommender ✅
3. Edge Certificates > Disable Always Use HTTPS (off)
4. Enable Network Websocket ✅
5. Enable Network GRPC ✅

## Commands : <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=powershell&label=Shell&message=Bash%20Script&color=lightgray">

<br>
♦️ For Debian 10 / 11 / 12 For First Time Installation (Update Repo) <br>

  ```html
 apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
  ```
  ♦️ For Ubuntu 18.04 / 20.04 / 22.04 / 24.04 For First Time Installation (Update Repo) <br>
  
  ```html
 apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot
 ```
♦️ Installation Link <br>

  ```html
apt --fix-missing update && apt update && apt upgrade -y && apt install -y bzip2 gzip coreutils screen dpkg wget vim curl nano zip unzip && wget -q https://raw.githubusercontent.com/EZ-Code00/allow/main/choose.sh && chmod +x choose.sh && screen -S choose ./choose.sh
  ```
<b>

MAIN MENU

![photo_2025-01-10_20-08-50](https://github.com/user-attachments/assets/19bb5b7b-dcb1-44a5-a3aa-f22b96e9c7f7)

SYSTEM MENU

![photo_2025-01-10_20-08-49](https://github.com/user-attachments/assets/702db6e6-d3e4-4064-bd37-db8827afa91b)

[ SERVICES ] <br>
<br>
✅ OPEN SSH 22<br>
✅ SSH DROPBEAR 143/109<br>
✅ SSH SLOW DNS 443/80<br>
✅ SSH STUNNEL5 222/777<br>
✅ OPEN VPN TCP,UDP,SSL 1194/2200/110<br>
✅ OHP SSH 8585/8686<br>
✅ OHP OPEN VPN 8787<br>
✅ SSH WEBSOCKET TLS & NON-TLS 443/80<br>
✅ SQUID PROXY 8080/3128<br>
✅ XRAY VMESS & VLESS WEBSOCKET TLS & NON-TLS 443/80<br>
✅ XRAY VMESS & VLESS XHTTP TLS & NON-TLS 443/80<br>
✅ XRAY VMESS & VLESS HTTP-UPGRADE TLS & NON-TLS 443/80<br>
✅ XRAY TROJAN WEBSOCKET TLS & NON-TLS 443/80<br>
✅ XRAY TROJAN GRPC TLS TLS 443<br>
✅ WIREGUARD 5820<br>
✅ SHADOSOCKS OBFS HTTP,HTTPS 2443/3443<br>
<br>

[ OTHER SERVICES ] <br>
<br>
✅ BANDWITH MONITOR <br>
✅ RAM MONITOR <br>
✅ XRAY-CORE UPDATE <br>
✅ REPLACE DOMAIN NAME <br>
✅ POINTING DOMAIN NAME <br>
✅ CHECK LOGIN USER <br>
✅ CHECK CREATED CONFIG <br>
✅ AUTOMATIC CLEAR LOG <br>
✅ AUTOMATIC VPS REBOOT <br>
✅ BACKUP & RESTORE <br>
✅ VIRTUAL SWAPRAM <br>
✅ IPV6 OFF <br>
✅ TURN ON/OFF MULTILOGIN OPENVPN <br>
✅ TIMEZONE : Asia/Kuala Lumpur (GMT +8) <br>
</br>



━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Telegram

[EZ-Code](https://t.me/EzcodeShop)

[Group EZ-Code](COMING SOON)

[Channel EZ-Code-Code](COMING SOON)

## Credit :

*   Project X

<p align="center">
  <a><img src="https://img.shields.io/badge/Copyright%20©-EzCode%20AutoScriptVPN%202022.%20All%20rights%20reserved...-blueviolet.svg" style="max-width:200%;">
    </p>

```
