# liber-rekonek

## install libermod (WAJIB INSTALL LIBERNET ORI/FRESH INSTALL)
- buat yg blm install libernet bisa klik [di sini!](https://github.com/lutfailham96/libernet)
- Buat yg udh pernah install bisa fresh install untuk menghindari error bisa [klik sini!](https://github.com/lutfailham96/libernet#fresh-install--fresh-update)

- Install MOD auto rekonek
```sh
rm /root/libernet/bin/auto_recon.sh
wget -O "/root/libernet/bin/auto_recon.sh" --no-check-certificate https://raw.githubusercontent.com/veriramadan/liber-rekonek/main/auto_recon/auto_recon.sh && chmod +x /root/libernet/bin/auto_recon.sh
rm /root/libernet/bin/service.sh && wget -O "/root/libernet/bin/service.sh" --no-check-certificate https://raw.githubusercontent.com/veriramadan/liber-rekonek/main/auto_recon/service.sh && chmod +x /root/libernet/bin/service.sh
rm /www/libernet/api.php && wget -O "/www/libernet/api.php" --no-check-certificate https://raw.githubusercontent.com/veriramadan/liber-rekonek/main/auto_recon/api.php && chmod +x /www/libernet/api.php
rm /www/libernet/js/index.js && wget -O "/www/libernet/js/index.js" --no-check-certificate https://raw.githubusercontent.com/veriramadan/liber-rekonek/main/auto_recon/index.js && chmod +x /www/libernet/js/index.js
rm /www/libernet/index.php && wget -O "/www/libernet/index.php" --no-check-certificate https://raw.githubusercontent.com/veriramadan/liber-rekonek/main/auto_recon/index.php && chmod +x /www/libernet/index.php
rm /root/libernet/system/config.json && wget -O "/root/libernet/system/config.json" --no-check-certificate https://raw.githubusercontent.com/veriramadan/liber-rekonek/main/auto_recon/config.json && chmod +x /root/libernet/system/config.json
```
jangan lupa clear cache browser sehabis install mod untuk menghindari error


## fix auto rekonek unceklist

- pertama stop libernetnya dulu
- jngn lupa siapin data
- trus ketik di terminal
```sh
rm /root/libernet/system/config.json && wget -O "/root/libernet/system/config.json" --no-check-certificate https://raw.githubusercontent.com/veriramadan/liber-rekonek/main/auto_rekon/config.json && chmod +x /root/libernet/system/config.json
```
**kalo udh jngn lupa clear cache browser "ini wajib biar ga error"**

**untuk jaga2 jangan lupa reboot stb dulu
