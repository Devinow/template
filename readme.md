### Installation

```
composer require devinow/template
```
### Usage

```php
<?php

require __DIR__.'/vendor/autoload.php';

use TAG\Blade\Blade;

$views = __DIR__ . '/views';
$cache = __DIR__ . '/cache';

$blade = new Blade($views, $cache);
echo $blade->view()->make('hello')->render();
```

You can use all blade features as described in the Laravel 10.x documentation:
https://laravel.com/docs/10.x/blade
