Mediasuite PHP code standard
----------------------------

This is to be used by codesniffer:

https://github.com/squizlabs/PHP_CodeSniffer

See the [partsworld project](https://github.com/mediasuitenz/partsworld) for example use.

 - Composer installs codesniffer and this as dependencies into the ```vendor``` folder.
 - Grunt has a ```copy``` task in it's ```setup``` task which puts a copy of this standard into the codesniffer set of standards
 - Grunt has a ```phpcs``` task which is configured to use this standard

