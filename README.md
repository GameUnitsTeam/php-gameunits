# PHP-Gameunits
Gameunits JSON-RPC PHP Helper Class

Composer
---

```
"require": {
  "gameunits/php-gameunits":"1.0.0"
}
```

Usage
---

```
<?php

use gameunits\PHPGameunits\GameUnits;

$gameunits = new GameUnits('rpcuser', 'rpcpassword');
$info = $bgameunits->getinfo(); // Same as $gameunits->callMethod('getinfo');
```
