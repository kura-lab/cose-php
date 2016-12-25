# cose-php
Constrained Object Signing and Encryption for PHP

[![Packagist](https://img.shields.io/packagist/v/kura-lab/cose-php.svg)](https://packagist.org/packages/kura-lab/cose-php)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/kura-lab/cose-php/blob/master/LICENSE)

### Specification

* https://datatracker.ietf.org/doc/draft-bormann-jose-cose/

### Requirements

[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%205.4.0-8892BF.svg?style=flat-square)](https://php.net/)
* PHP 5.4.0 or higher.

### Installation

At first, install composer.

```
$ mkdir workspace
$ cd workspace
$ curl -s http://getcomposer.org/installer | php
```

Create composer.json.

```
{
    "minimum-stability": "dev",
    "require": {
        "kura-lab/cose-php": "1.*"
    }
}
```

Install cose library.

```
$ php composer.phar install
```

### Development

Check coding style with CodeSniffer.

```
$ vendor/bin/phpcs --standard=PSR2 src/
```

Execute unit test with PHPUnit.

```
$ vendor/bin/phpunit
```

Fix source code with PHP Coding Standards Fixer.

```
$ vendor/bin/php-cs-fixer fix --config-file .php_cs --verbose --diff --dry-run
$ vendor/bin/php-cs-fixer fix --config-file .php_cs --verbose --diff
```
