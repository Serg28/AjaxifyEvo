AjaxifyEvo
==========

Плагин для MODX evo. 
Для браузеров поддеживающих HTML5 History API превращает сайт в одностраничный.

Установка
------------------------

Плагин оформлен в пакет для установки через MODX store.

Использование.
------------------------------

- В настройках плагина укажите шаблоны для которых его активировать.
- Укажите для блоков которые нужно обновлять атрибут data-ajaxifity="имя блока".
Например:```<div class="large-3 pull-9 columns" data-ajaxify="menu">
      [[Wayfinder? &startId=`1` &outerClass=`side-nav`]]       
    </div>```
- Для  блоков при обновлении которых нужно затухание укажите класс fade
- Укажите класс no-ajaxy для ссылок при переходе по которым, не нужно использовать ajax. 
 