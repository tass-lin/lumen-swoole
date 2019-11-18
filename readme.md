# php & swoole 

WORKDIR `/var/www/project`


### Quickly up
第一次安裝的會額外起一個container 跑 composer install，安裝完後就能正常執行囉!
```
docker-compose up -d
```

### CMD

```
php artisan swoole:http {start|restart|reload|stop|infos}
```