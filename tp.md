## Aguer
# hugo

# Connection au serveur
```
 ssh root@Wilfart.fr -p 6201
```
# installer nginx
```
 apt install nginx
 ```
  # configuration du firewall
  ```
  apt install ufw
  ```
  ```
  ufw enable
  ```
  ```
  ufw allow from 192.168.1.94 to any port 22
  ufw allow from 192.168.1.94 to any port 80
  ufw allow from 192.168.1.94 to any port 443
  ```