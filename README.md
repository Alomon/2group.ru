## Создание пустого проекта на Laravel 11 в OSPanel
Запускаем OSPanel и открываем консоль
```shell
cd domains
```
Создаем папку для проекта
```shell
mkdir laravel-11.loc 
```
Переходим в папку с проектом
```shell
cd laravel-11.loc
```
Создаем новый проект на Laravel в текущей директории
```shell
composer create-project laravel/laravel .
```
Устанавливаем поддержку API и модуль Sanctum
```shell
php artisan install:api
```
Публикуем конфигурационный файл Cors
```shell
php artisan config:publish cors
```
Создание символической ссылки из директории 
public/storage к директории storage/app/public
```shell
php artisan storage:link
```

