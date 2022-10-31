## Install with Docker

- git clone ... && cd UDOY-LARAVEL
- git branch
- git fetch --all
- sudo git fetch --all
- sudo git checkout --track origin/develop
- git checkout develop
- `docker-compose up -d`
- `docker exec -it udoy /bin/bash`
- `composer install`
- `cp .env.example .env`
- `php artisan key:generate`
- `php artisan migrate`
- `php artisan db:seed`
  
### Site URL

- Application http://localhost:8888
- Adminer for Database Your Ip:8800


DB credentials:
```
Server: db:3307
Username: root
Password: 123456@udoy 
Database: udoy
```

### How to refresh a specific migrations 
```
 php artisan migrate:refresh --path=/database/migrations/tablename.php
```
