This environment is composed of openresty.
Refering to official site.

https://openresty.org/en/

http://nginx.org/en/docs/

Add name resolver to your host machine.
```
192.168.33.60   mypx.app-visor.com myapi.app-visor.com
192.168.33.61   myweb1.app-visor.com
192.168.33.62   myweb2.app-visor.com
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
