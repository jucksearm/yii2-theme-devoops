yii2-theme-devoops / Yii2 extension
=

Yii2 Admin theme modify from **[DevOOPS](https://github.com/nnmware/devoops)** bootstrap 3 template

# Installation

## Install via composer:
```
  composer require "jucksearm/yii2-theme-devoops"
```
OR add this to your composer.json require section

```json
  "jucksearm/yii2-theme-devoops": "*",
```
## Install via zip:

download file https://github.com/jucksearm/yii2-theme-devoops/archive/master.zip

extract file to `vendor` folder as:
```php
   vendor
   |- jucksearm
     |- yii2-theme-devoops
       | ......
```

# How to use

This extensions is design for widgets, You can call it every where.
Example code here:

```php

<?php echo jucksearm\sly\Sly::widget([
    'id' => 'slider',                           ** unique id
    'items'=> [
        ['content' => '<img src=""></img>'],    ** insert images
        ['content' => '<div>test</div>'],       ** insert html DOM
        ...
    ],
    'htmlOptions' => [
        'style' => 'height:200px;',             ** custom options
        'class' => 'slider-h',
        ...
    ],
    'widgetOptions' => [
        'itemNav' => 'basic',                   ** setting widgets
        ...
    ]
]); ?>

```
# Example

You can copy example code in [example.php](example.php) to your view render in some controller.


## [Option](Option.md)

Detailed description of all available yii2sly widget options.
