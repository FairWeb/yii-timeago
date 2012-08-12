yii-timeago
===========

Timeago formatter for yii framework

#Instalation
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
Now supported en (+en-short), ru, uk.
In future will be added more locales.