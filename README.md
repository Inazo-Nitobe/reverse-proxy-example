Add name resolver to your host machine.
```
192.168.33.50   mypx.app-visor.com myshare.app-visor.com
192.168.33.51   myapi.app-visor.com
```

Setup a machine.
```
cd ~/work
nginx -p . -c conf/nginx.conf
```

