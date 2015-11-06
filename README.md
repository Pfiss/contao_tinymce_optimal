[![Version](http://img.shields.io/packagist/v/pfiss/contao_tinymce_optimal.svg?style=flat-square)](http://packagist.com/packages/pfiss/contao_tinymce_optimal)
[![License](http://img.shields.io/packagist/l/pfiss/contao_tinymce_optimal.svg?style=flat-square)](http://packagist.com/packages/pfiss/contao_tinymce_optimal)
[![Downloads](http://img.shields.io/packagist/dt/pfiss/contao_tinymce_optimal.svg?style=flat-square)](http://packagist.com/packages/pfiss/contao_tinymce_optimal)
[![Contao Community Alliance coding standard](http://img.shields.io/badge/cca-coding_standard-red.svg?style=flat-square)](https://github.com/contao-community-alliance/coding-standard)


# Pfiss_tinyMCE_optimal
Simple module for contao to customise the tinyMCE to the „optimal“ configuration.

It made use of the following plugins (which are not included with the standard version of contao):

 * anchor
 * autoresize
 * contextmenu
 * wordcount
 
 Furthermore it removes ``H1`` and ``H5``, ``H6`` from text formats and uses a custom toolbar.
 
 ![Toolbar](tinyMCE_toolbar.png)

## Installation
```
$ php composer.phar require pfiss/contao_tinymce_optimal:~1.0
```

## License
This module is licensed under the GNU LESSER GENERAL PUBLIC LICENSE Version 3. For more information see LICENSE file.


