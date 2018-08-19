This environment is composed of openresty.
Refering to official site.

https://openresty.org/en/

http://nginx.org/en/docs/

Add name resolver to your host machine.
```
192.168.33.50   mypx.app-visor.com myapi.app-visor.com
192.168.33.51   mypxd.app-visor.com
```

Setup a machine.
```
cd ~/work
nginx -p . -c conf/nginx.conf
```
Stop a machine.
```
nginx -p . -s stop
```
Reload a machine.
```
nginx -p . -s reload
```
