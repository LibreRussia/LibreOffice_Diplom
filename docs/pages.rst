Настройки страницы
=====================

Нумерация
---------

Для удобной работы с нумерацией нужно установить плагин — Pager (http://myooo.ru/content/view/106/99/). После скачивания добавьте плагин в LibreOffice через меню *«Сервис → Управление расширениями»* [#]_.

.. [#] Руководство по установке расширений LibreOffice: https://wiki.documentfoundation.org/Documentation/Publications/ru

После установки во вкладке *«Вставка»* появится пункт *«Вставка — Номера страниц»*. Данный плагин позволяет легко управлять положением, типом и началом нумерации. В том числе, упрощает вставку альбомных страниц.

.. figure:: img/lo-diplom-001.png
   :scale: 70 %
   :alt: Диалоговое окно плагина Pager
   :align: center

   Диалоговое окно плагина Pager
   
Формат страницы
---------------

* *«Формат → Страница»*

Под форматом страницы подразумевается размер листа (обычно используется размер А4 равный 210×297 мм), его ориентация и размер полей. LibreOffice позволяет задать формат для каждой страницы документа, вплоть до изменения размера отдельных листов. Последнее достигается при помощи разрывов страниц (подробнее смотрите пункт :ref:`pages-plane`).

Титульная страница
------------------

* *«Формат → Титульная страница»*

Для создания титульного листа используется команда *«Формат → Титульная страница»*.  В появившемся меню можно настроить количество титульных страниц, их положение и нумерацию. Титульную страницу можно вставить в любое место в документе.

Титульеая страница, по сути, является силем страницы. Поэтому можно создать свой стиль страницы и использовать его для создания титульных страниц, применяя разрывы страниц с присвоением стиля.

Разрыв страницы
----------------

* *«Вставка → Разрыв → Разрыв страницы»*

Функция без которой невозможно оформить многостраничный документ. При вставке разрыва, все содержимое документа, которое находится после него, автоматически переносится на новый лист и всегда остается на новом листе. Т.е. если до разрыва будет добавлено какое-то содержимое, то все что после разрыва не сместится в середину листа, а останется в его начале. Обычно разрывом отделяются новые главы.

.. _`pages-plane`:

Смена ориентации отдельных страниц
----------------------------------

С помощью разрыва страницы можно изменять ориентацию отдельных страниц. Например, если требуется вставить страницу альбомной ориентации.  Для этого в меню *«Вставка → Разрыв → Разрыв страницы»* нужно выбрать стиль *«Альбомный»*. Чтобы следом вновь шли страницы портретной ориентации, нужно установить ещё один разрыв со стилем *«Обычный»*.

Колонтитулы
-----------

Колонтитул — заголовочные данные (название произведения, части, главы, параграфа и т. п.), помещаемые над или под текстом на нескольких или на всех страницах книги, газеты, журнала или другого многостраничного издания. Различаются верхний и нижний колонтитулы.

Настройка колонтитулов осуществляется через меню *«Формат → Страница»* во вкладках *«Верхний колонтитул»* и *«Нижний колонтитул»*. Можно задать высоту колонтитула, интервалы и внешнее оформление.

.. note:: Вставка страниц в LibreOffice осуществляется с помощью колонтитулов, которые не относятся к высоте нижнего или верхнего поля. Если колонтитул имеет высоту в 0,5 см и интервал от него до текста 0,5 см, т. е. в сумме занимает 1 см, а поле 2 см. То общее расстояние от края листа до текста составит 3 см.

    Поэтому если в требованиях написано, что поле (со стороны которого проставляется нумерация) должно иметь высоту 2 см, то целесообразно в настройках страницы выставить высоту этого поля в 1 см, а высоту колонтитула 0,5 см и интервал до текста 0,5 см. И обязательно снять галочку с параметра *«Автоподбор высоты»*.