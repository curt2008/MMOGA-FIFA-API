MMOGA-FIFA-API
==============

### Starting
<i>Let's go ahead and initialise the class</i>
```php
require "Guzzle/autoload.php";
require "mmoga.class.php";
	
$mmoga = new MMOGA("your_username", "your_api_key");
```
### Making an example call
<i>Here's we're going to grab the latest prices for each platform</i>
```php
$mmoga->getPrices()
```
Copyright
=================
Copyright (c) 2014 Curtis Crewe. Released under the terms of the MIT license. See LICENSE for details.
