yii-timeago
===========

Timeago formatter for yii framework

#Installation
Copy yii-timeago to your app extensions folder  
In config main add to componets section:  
```php
...
'components' => array(
	'format'=>array(
		'class'=>'application.modules.timeago.TimeagoFormatter',
    ),
...
```

#Examples

#Supported locales
Now supported en (english), ru (russian), uk (ukrainian).  
In future will be added more locales.  
