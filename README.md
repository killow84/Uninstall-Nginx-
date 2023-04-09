# Uninstall-Nginx

## 1.Uninstalling NGINX in Debian Systems
```
$ sudo systemctl status nginx.service
```
# Remove NGINX
```
$ sudo apt remove nginx
$ sudo apt remove nginx nginx-commons
$ sudo systemctl status nginx.service
```
## 2.Purge Nginx
```
$ sudo apt purge nginx
$ sudo systemctl status nginx.service
$ sudo apt-get autoremove
```
## 3. Nginx Failed to Remove
```
$ sudo apt-get remove --purge nginx*
$ sudo apt-get autoremove --purge
```
## 3. Uninstalling NGINX in RPM Systems
```
$ sudo systemctl stop nginx.service
$ sudo systemctl disable nginx.service
$ sudo chkconfig nginx off
$ sudo rm -rf /etc/nginx
$ sudo rm -rf /etc/init.d/nginx
$ sudo rm -rf /var/log/nginx
$ sudo rm -rf /var/cache/nginx/
$ sudo rm -rf /usr/sbin/nginx
$ sudo rm -rf /usr/lib/systemd/system/nginx.service
$ sudo dnf remove nginx
```
