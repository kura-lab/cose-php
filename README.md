# cose-php
Constrained Object Signing and Encryption for PHP

### Specification

* https://datatracker.ietf.org/doc/draft-bormann-jose-cose/

### Requirements

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
