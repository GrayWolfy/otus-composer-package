# Рисовалка пингвина

Добавляет пакет с возможностью рисовать пингвина

## Требования

- PHP 8.1

```bash
$ composer require graywolfy/otus-composer-package
```

## Использование

```php
$pinguinDrawer = new PinguinDrawer();

echo $pinguinDrawer->draw();

/*
   _~_     
  (o o)    
 /  V  \   
/(  _  )\  
  ^^ ^^   
 
*/
```