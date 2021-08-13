# homework-custom-package

## Usage

### Add following code to your app:

```

use Otus\homework\App;

require 'vendor/autoload.php';

try {
    
    $app = new App();

    echo $app->run();

} catch(Exception $e) {
    echo $e->getMessage();
}

```
