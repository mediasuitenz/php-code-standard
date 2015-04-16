Mediasuite PHP code standard
----------------------------

This is to be used by codesniffer:

https://github.com/squizlabs/PHP_CodeSniffer

See the [partsworld project](https://github.com/mediasuitenz/partsworld) for example use in which:

 - Composer installs codesniffer and this as dependencies into the ```vendor``` folder.
 - Grunt has a ```copy``` task in it's ```setup``` task which puts a copy of this standard into the codesniffer set of standards
 - Grunt has a ```phpcs``` task which is configured to use this standard

## Setup

`pear install PHP_CodeSniffer`
or
`composer global require "squizlabs/php_codesniffer=*"`
Clone this repo or obtain a copy of the `ruleset.xml` somehow
In sublime install package "phpcs"
In the package settings, specify
- The executable path e.g. `/Users/you/.composer/vendor/bin/phpcs`
- The standard to use as additional args e.g. `"--standard": "/Users/you/src/php-code-standard"`
