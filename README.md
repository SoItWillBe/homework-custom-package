# homework-custom-package

## Usage

### Require package:
```
composer require so-it-will-be-php/homework-3
```


### Add following code to your index.php file:

```
<?php

require 'vendor/autoload.php';

use Otus\homework\App;

try {
    
    $app = new App();

    echo $app->run();

} catch(Exception $e) {
    echo $e->getMessage();
}

```
