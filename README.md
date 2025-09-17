Scavix Software Web Development Framework
=========================================
This is a package for the Scavix Software Web Development Framework.
It contains functions to minify and combine css and js files.

Deprecation
===========
The code is very old and has not been tested for a long time. So better just dont use.

Installation
============
Install the package with `composer require scavix/wdf-minify`.

Configuration
=============
```
$GLOBALS['CONFIG']['minify'] =
[
    'target_path' => 'path/to/folder',
    'base_name => 'base_name_for_files',
    'url' => '//base/url/where/targte_path/is/served',
];
```

Uses
====

* [CssMin (3.0.1)](http://code.google.com/p/cssmin/)
* [jsmin-php (1.1.2)](https://github.com/rgrove/jsmin-php)

Dependencies
------------
* [scavix/wdf-core (^1.0.2)](https://packagist.org/packages/scavix/wdf-core#v1.0.2)
