# Dynamic Table Update: Update Table Data With ease.
Easily Update data  using . This package has been tested since Laravel 10.

## Installation

Run this composer command in your laravel application:

support mysql and oracle database 18c

```
composer require rasel9w9/dynamic-table-updater:^1.1
```
To start using Laravel, add the Service Provider and the Facade to your `config/app.php`:

> **Note:** This package supports auto-discovery features of Laravel 5.5+, You only need to manually add the service provider and alias if working on Laravel version lower then 5.5.

```php
'providers' => [
    // ...
    rasel9w9\DynamicTableUpdater\DynamicTableUpdateServiceProvider::class,
]
```

# Basic Usage

To use Dynamic table updater.
firstly clear route cache.
```php
	//to Clear cache of Route
	php artisan route:clear
```

go to the url for dynamic table update
```
    url: your-root-url/rasel9w9/table-list


    routename: rasel9w9.tableList
```