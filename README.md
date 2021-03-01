This is a fork of the repo by USAePay here: https://github.com/usaepay/usaepay-php

This does not include the test files.
Added Composer support with autoload.

I originaly tried using the repository @ https://github.com/portsidedesign/usaepay-php. 
I could not get it to work as there were issues with the autoload to do with folders/files/filenames/namespaces(?).

**USAGE**

`composer require ylitc/usaepay-php`
```php
require_once __DIR__ . '/vendor/autoload.php';
$tran = new usaepay\umTransaction();
```

MORE INFO FROM USAePay
=================================

USAePay PHP Library
=================================

[http://www.usaepay.com](http://www.usaepay.com)

[http://help.usaepay.com/developer/phplibrary](http://help.usaepay.com/developer/phplibrary)

SYNOPSIS
--------
The USAePay PHP library is a class for running transactions on the USAePay
gateway.  Its feature set roughly follows the [transaction api](http://help.usaepay.com/developer/transaction).  If
you are looking for more features, take a look at [soap api](http://help.usaepay.com/developer/soap/).

SUPPORT
-------
If you have any questions on the use of this library, please contact
the developer integration support department:
   devsupport@usaepay.com
   866-872-3729 x706
   
For more documentation on using the library, please see
http://help.usaepay.com/developer/phplibrary



REQUIREMENTS
------------
-PHP 4.3.x or higher (http://www.php.net) 

-HTTPs streams support in PHP
or
-Curl/ssl module installed (http://curl.haxx.se/) 


