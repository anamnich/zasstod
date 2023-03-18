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

## ZASSTDR OFFICIAL
