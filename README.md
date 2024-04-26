# WEB GALLERY

## Tentang Website

Aplikasi Web Galery Ujikom yang dibuat sederhana

## Fitur

Untuk Fitur masih minim:
- sign up
- log in
- log out
- add poto
- add album
- add comment
- like
- delete poto
- delete album

## Tampilan Website
![Screenshot (4)](https://github.com/nabillanatha/nabilla-ujikom/assets/141295106/1eac005e-89fc-4d0a-b50e-d604ce36fcd9)

![Screenshot (5)](https://github.com/nabillanatha/nabilla-ujikom/assets/141295106/407896cb-ee8d-4ca2-84d8-306f0b0737e7)

![Screenshot (6)](https://github.com/nabillanatha/nabilla-ujikom/assets/141295106/e310dffb-fab7-4aec-98ad-8a0784388641)


## ERD, Relasi dan UML Use Case

- ERD
![ERD](https://github.com/nabillanatha/nabilla-ujikom/assets/141295106/10b72e80-83f0-48e4-8da0-fdb1d998975d)


- Relasi
![relasi](https://github.com/nabillanatha/nabilla-ujikom/assets/141295106/de637ebd-59fa-4bf0-89a1-dd3e7c594814)


- UML
![use case](https://github.com/nabillanatha/nabilla-ujikom/assets/141295106/52ae54ae-f1b4-47dc-a912-c2cb7e3997a0)


## Prasyaratan

- PHP 8.2.8 & Web Server (Apache, Lighttpd, atau Nginx)
- Database (MariaDB dengan v11.0.3 atau PostgreSQL)
- Web Browser (Firefox, Safari, Opera, Microsoft Edge dll)

## Instalasi
1. Clone Repository
```
https://github.com/Wanzzy1/galeriwahdan2
```

2. Install Composer
```
composer install
```
atau
```
composer update
```

3. Copy .Env
```
copy .env.example .env
```

4. Setting database di .env
```
DB_PORT=3306
DB_DATABASE=laravel_gallery
DB_USERNAME=root
DB_PASSWORD=
```

5. Generate key
```
php artisan key:generate
```

6. Jalankan migrate dan seeder
```
php artisan migrate --seed
```

7. Buat Storage Link
```
php artisan storage:link
```

8. Jalankan Serve
```
php artisan serve
```

