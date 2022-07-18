# php-laravel
(mac)

version (php, composer)
```
php -v
PHP 8.1.8 (cli) (built: Jul  8 2022 10:58:31) (NTS)
:

composer --version 
Composer version 2.3.10 2022-07-13 15:48:23    
:
```

## create laravel new project
using `laravel/installer`
```
composer global require "laravel/installer=~1.1"
```

using `composer`
```
composer create-project laravel/laravel your-project-name --prefer-dist
```

## File Structure 

```
$ tree -L 2
.
├── README.md
└── your-project-name
    ├── README.md
    ├── app
    ├── artisan
    ├── bootstrap
    ├── composer.json
    ├── composer.lock
    ├── config
    ├── database
    ├── lang
    ├── package.json
    ├── phpunit.xml
    ├── public
    ├── resources
    ├── routes
    ├── storage
    ├── tests
    ├── vendor
    └── vite.config.js
```