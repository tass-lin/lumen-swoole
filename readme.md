# php & swoole 

WORKDIR `/var/www/project`


### Quickly up
第一次安裝的會額外起一個container 跑 `composer install`，安裝完後`重啟`就能正常執行囉!
```
docker-compose up -d

docker-compose down
```
或是`composer install`跑完後下
```
docker-compose exec lumen-swoole php artisan swoole:http start
```

### CMD

```
php artisan swoole:http {start|restart|reload|stop|infos}
```