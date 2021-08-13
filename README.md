# homework-custom-package

## Usage

### Add following code to your app:

```
require 'vendor/autoload.php';

use Otus\homework\App;

try {
    
    $app = new App();

    echo $app->run();

} catch(Exception $e) {
    echo $e->getMessage();
}

```
