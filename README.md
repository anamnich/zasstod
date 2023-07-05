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
