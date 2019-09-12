````
$ docker-compose build

$ docker-compose up -d
```

.env

```
DB_HOST=mysql
APP_URL=http://localhost:8080
```

```
http://localhost:8080
````

```
$ docker-compose exec php php /var/www/artisan migrate
```

```
$ docker-compose down
```


https://dev.to/aschmelyun/the-beauty-of-docker-for-local-laravel-development-13c0