# graphp/trivial-graph-format [![Build Status](https://travis-ci.org/graphp/trivial-graph-format.svg?branch=master)](https://travis-ci.org/graphp/trivial-graph-format)

[Trivial Graph Format](http://en.wikipedia.org/wiki/Trivial_Graph_Format) (TGF) is a simple text-based file format for describing graphs.

> Note: This project is in beta stage! Feel free to report any issues you encounter.

## Install

The recommended way to install this library is [through composer](http://getcomposer.org). [New to composer?](http://getcomposer.org/doc/00-intro.md)

```JSON
{
    "require": {
        "graphp/trivial-graph-format": "~0.1.0"
    }
}
```

This project aims to run on any platform and thus does not require any PHP
extensions and supports running on legacy PHP 5.3 through current PHP 7+ and
HHVM.
It's *highly recommended to use PHP 7+* for this project.

## Tests

To run the test suite, you first need to clone this repo and then install all
dependencies [through Composer](https://getcomposer.org):

```bash
$ composer install
```

To run the test suite, go to the project root and run:

```bash
$ php vendor/bin/phpunit
```

## License

Released under the terms of the permissive [MIT license](http://opensource.org/licenses/MIT).
