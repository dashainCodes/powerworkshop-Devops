# php-hello-world
A simple hello-world for composer


Installation using docker-compose
------------

Install with composer
``` bash
docker-compose up -d
```

Run composer update
``` bash
composer update silarhi/hello-world
```

Usage
-----

``` php
require_once __DIR__ . '/vendor/autoload.php';

use Silarhi\Hello;

$hello = new Hello();
echo $hello->display() . "\n";
```
#github actions workflows
![image](https://github.com/dashainCodes/powerworkshop-Devops/assets/157484052/d16d6ece-fcec-4d4f-bc4e-b289bb136faf)

