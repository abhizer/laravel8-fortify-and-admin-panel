# Laravel 8 with Fortify and Admin-Panel

## Introduction

The Fortify and Bootstrap part is taken from https://github.com/LaravelDaily/Laravel-8-Fortify-Bootstrap-Demo
The admin panel used is: `encore/laravel-admin` (Documentation: https://laravel-admin.org/docs/en/README)

## Admin Panel Basics
Config file: `config\admin.php`
To import a model to the admin panel: `php artisan admin:controller App\\Models\\User`
Once you do that, you will need to add it to the routes file (`app/Admin/routes.php`): `$router->resource('User', UserController::class);`

## Cloning:
```
composer update
php artisan admin:install
php artisan admin:publish
```
