DobJS is Detect old browsers plugin
===================================

Описание
========
При создании сайтов иногда сложно (долго, дорого) поддержать все существующие браузеры (особенно старые версии).  
Чтобы избежать недовольства пользователей им можно выводить уведомление о том, что нужно обновить или сменить браузер.

Установка
=========
Для установки плагина нужно добавить в конец `<body>` *.html* файла две строки:

    <script>dob_settings = { browsers: { ie: 7 }</script>
    <script src="dob.js"></script>

Пример использования
====================
[Минимальные настройки](http://tit.github.io/dobjs/examples/minimal.html)  
[Расширенные настройки](http://tit.github.io/dobjs/examples/full.html)  

API
===
Параметр: `browsers`   
Описание: Браузеры и их версии.  
Тип: `object`  
Значение по умолчанию: отсутствует
  
Параметр: `cookie_day_expires`   
Описание: Количество дней, которые баннер не будет показываться, если его скрыли.  
Тип: `number`  
Значение по умолчанию: 3
  
Параметр: `language`  
Описание: Язык сообщений.  
Тип: `string`  
Значение по умолчанию: en  
  
Параметр: `background_color`  
Описание: Цвет фона баннера.  
Тип: `string`  
Значение по умолчанию: red  
  
Параметр: `notification_text`  
Описание: Текст уведомления на баннере.  
Тип: `string`  
Значение по умолчанию: For correctly view the site, update or change your browser  
  
Параметр: `close_text`  
Описание: Текст закрытия баннера.  
Тип: `string`  
Значение по умолчанию: Close for 3 days  