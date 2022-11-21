# Installation

- composer require lnch\laravel-admin
- php artisan migrate
- php artisan laravel-admin:link-assets
- OR... php artisan vendor:publish --provider=lnch\laraveladmin\LaravelAdminServiceProvider --tag=public
 - php artisan vendor:publish --provider=lnch\laraveladmin\LaravelAdminServiceProvider --tag=config
