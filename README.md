My Test Extension
=================
My Test Extension

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist sidorovav/yii2-test "*"
```

or add

```
"sidorovav/yii2-test": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \sidorovav\test\AutoloadExample::widget(); ?>```