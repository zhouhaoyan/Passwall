# Passwall
[![visitor badge](https://img.shields.io/badge/Chat%20on-Telegram-blue.svg)](https://t.me/AmirHosseinTSL) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
# How to install Passwall + Xray on openwrt

* [IF you have Xiaomi 4a Gigabit , Openwrt 22.03.3 Recommended](https://archive.openwrt.org/releases/22.03.3/targets/ramips/mt7621/openwrt-22.03.3-ramips-mt7621-xiaomi_mi-router-4a-gigabit-squashfs-sysupgrade.bin)
  
* when you want downgrade openwrt please Uncheck ( Keep setting ) . it's for clear installation .

![This is an image](https://pars-space.ir/wp-content/uploads/2023/09/v2ray-openwrt.jpg)




# System Requirements :

- CPU : +700 MHz ✅

- RAM : +256 MB  ✅


# INSTALL PASSWALL : 

Run this command in openwrt remote ssh
```
rm -f passwallx.sh && wget https://raw.githubusercontent.com/amirhosseinchoghaei/Passwall/main/passwallx.sh && chmod 777 passwallx.sh && sh passwallx.sh
```
Done !

# IF You are Using SNAPSHOT 👈
```
rm -f passwalls.sh && wget https://raw.githubusercontent.com/amirhosseinchoghaei/Passwall/main/passwalls.sh && chmod 777 passwalls.sh && sh passwalls.sh
```
📍in case you use a snapshot build.

# Help

- After installation , settings will be change :
 
⚠️ LAN IP ADDRESS : 192.168.27.1

📶 WiFi 2Ghz SSID : VPN 2G

🔑 Password : 10203040

# Types Support

VLESS (XRAY ✅ SING-BOX ✅)

VMESS (XRAY ✅ SING-BOX ✅)

REALITY (XRAY ✅ SING-BOX ✅)

TROJAN (XRAY ✅ SING-BOX ✅)

HYSTERIA2 (XRAY ❌ SING-BOX ✅)

TUC (XRAY ❌ SING-BOX ✅)

SHADOWSOCKS (XRAY ✅ SING-BOX ✅)

WIREGUARD (XRAY ✅ SING-BOX ✅)

SOCKS (XRAY ✅ SING-BOX ✅)

HTTP (XRAY ✅ SING-BOX ✅)

XRAY Fragment tlshello & 1-3 ✅

↘️
Recommended Router : [Xiaomi AX3000T](https://openwrt.org/inbox/toh/xiaomi/ax3000t)



✅ Tested On : Xiaomi 4a Gigabit , TP-Link C6 v3 , Mikrotik Hap ac2 , GL.iNet AR300M (NOR) , Linksys ea7500. v1-v2 , Linksys ea8100 v1-v2 , ASUS RT-N66U , Xiaomi AX3600 , Xiomi AX3200 , Xiaomi AX6000 , Xiaomi AX3000T

# Features

⚡ Full Automatic installation Packages Just in one step

⚡ Install XRAY On Temp Space if You Don't Have Enough Disk Space (Smart)

⚡ IRAN IP & Domain Traffic Direct (100%)

⚡ Improve Performance

⚡ Server WARP Connection Fixed

⚡ Default Kill Switch

