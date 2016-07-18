# Laravel Api Tester

![Interface](http://i.imgur.com/XGqXNaI.png) 

## Installation

Require this package with composer:

```
composer require asvae/laravel-api-tester
```

After updating composer, add the ServiceProvider to the providers array in config/app.php

```
Asvae\ApiTester\ServiceProvider::class,
```

That's it. Go to `[your site]/api-tester` and start testing routes. 

## Config

By default, the package is bound to `APP_DEBUG``.env` value. But you can easily override it. First, publish config:

```
php artisan vendor:publish --provider="Asvae\ApiTester\ServiceProvider"
```

Then edit `config/api-tester.php` as you please.

## Features
1) Display all the routes for application.
2) Live search and sortable columns.
2) Define request body in [JSON editor](https://github.com/josdejong/jsoneditor).
3) Preview response depending on type (html or json).
4) [Material design lite](https://getmdl.io/) as theme.
5) Lightweight and no dependencies (except on laravel).

## Live demo
*Coming...*

## Tests
*Coming...*