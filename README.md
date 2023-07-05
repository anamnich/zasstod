## INSTALL COMMAND
```apt update```
```cd /var/www/pterodactyl```
```yarn build:production```
```php artisan optimize:clear```
## IZINKAN ROOT
```ssh
sudo nano /etc/ssh/sshd_config
```
```To enable password :
PasswordAuthentication yes
PermitRootLogin yes
PubkeyAuthentication no
```
```Setting passwd root :
sudo passwd root
```
```Restart ssh :
sudo systemctl restart sshd && sudo systemctl restart ssh
```

## CLEAR
```apt-get update && apt-get upgrade -y
ls
git clone https://github.com/SFams21/clear-cache-vps.git
cd clear-cache-vps
chmod +x cleaner-tools.sh
sh cleaner-tools.sh
```
```echo 1 > /proc/sys/vm/drop_caches
echo 2 > /proc/sys/vm/drop_caches
echo 3 > /proc/sys/vm/drop_caches
script otomatis flush cache:

# crontab -e
0 * * *  * sync; echo 3 > /proc/sys/vm/drop_caches
perintah diatas akan menjalankan perintah sync; echo 3 > /proc/sys/vm/drop_caches setiap 1 jam

untuk memeriksa cache memory

free -m```
## UPDATE & UPGRADE
```sh
sudo apt update -y && sudo apt upgrade -y
```

## PANEL & WINGS
#1
```sh
bash <(curl https://pterodactyl-installer.se)
```
#2
```sh
bash <(curl https://raw.githubusercontent.com/anamnich/zas/main/install-wings.sh)
```

## TEMA
Install script:
```sh
bash <(curl https://raw.githubusercontent.com/anamnich/Utama/main/install.sh)
```

## ZASSVCJ OFFICIAL
