ЮПИ! - CMS на Yii
=================

[![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/yupe/yupe/badges/quality-score.png?s=7530a908ed160af10407a051474a9064325510cc)](https://scrutinizer-ci.com/g/yupe/yupe/)
[![Total Downloads](https://poser.pugx.org/yupe/yupe/downloads.png)](https://packagist.org/packages/yupe/yupe)
[![Dependencies Status](https://d2xishtp1ojlk0.cloudfront.net/d/1477472)](http://depending.in/yupe/yupe)

**Юпи! — простая и легкая CMS, написанная на Yiiframework** (http://www.yiiframework.com/)

Юпи! позволяет быстро и легко создавать проекты следующих типов:

* сайты-визитки
* корпоративные порталы
* коллективные и персональные блоги
* каталоги товаров


**На Юпи! уже работает более 200 проектов, Юпи! активно используются несколькими студиями и командами разработчиков**

Прежде всего Юпи! рассчитан на PHP-разработчиков, знакомых с Yii

Удобная и простая панель управления позволяет управлять контентом сайта даже домохозяйке!

Процесс установки очень прост и занимает не более 5 минут!

Для успешной работы проекта на Юпи! вполне достаточно самого простого (и дешевого) хостинга, минимальные требования:

Требования
----------
* PHP >= 5.3.7
* Yiiframework >= 1.1.14
* YiiBooster >= 2.0
* Nested Set Behavior
* Imperavi Redactor Widget
* Yii2-debug
* MySQL/PostgreSQL
* Apaсhe/Nginx
* Composer

Ссылки
------
* [Официальный сайт](http://yupe.ru/)
* [Блог Юпи!](http://yupe.ru/index.php/blog/yupe-mini-cms-yii)
* [Репозиторий модулей](https://github.com/yupe/yupe-ext)
* [Официальная документация](http://yupe.ru/docs/index.html)
* [Подробнее о проекте](http://yupe.ru/pages/about)
* [Команда](http://yupe.ru/docs/yupe/team.html)
* [Форум](http://yupe.ru/talk/)
* [Контакты](http://yupe.ru/feedback/index)
* [Как помочь проекту](http://yupe.ru/pages/help)
* [twitter](https://twitter.com/#!/YupeCms)
* [Коммерческая поддержка](http://amylabs.ru/contact)

Возможности
-----------

Из коробки Вы получаете (всё разделено на модули - используйте только то, что необходимо):

* [Регистрация](http://yupe.ru/registration), [аутентификация](http://yupe.ru/login), [восстановление пароля](http://yupe.ru/recovery) ([модуль user](https://github.com/yupe/yupe/tree/master/protected/modules/user))
* Модуль пользователей, для управление пользователями сайта (блокировка, активация, редактирование и т.д.) через административный интерфейс ([модуль user](https://github.com/yupe/yupe/tree/master/protected/modules/user))
* Модуль новостей для [создания и публикация новостей на сайте](http://yupe.ru/story/ocherednoy-sayt-na-yupi) ([модуль news](https://github.com/yupe/yupe/tree/master/protected/modules/news))
* Модуль статических страниц, для создания и управление статическими страницами сайта ([модуль page](https://github.com/yupe/yupe/tree/master/protected/modules/page))
* Модуль категорий, для создания и управление категориями вашего сайта (разделами) ([модуль category](https://github.com/yupe/yupe/tree/master/protected/modules/category))
* Модуль меню, для создания и редактирование меню вашего сайта ([модуль menu](https://github.com/yupe/yupe/tree/master/protected/modules/menu))
* Модуль комментариев (можно комментировать любую сущность с выстраиванием древовидных комментариев, пример [http://yupe.ru/post/logotip-dlya-yupi.html](http://yupe.ru/post/logotip-dlya-yupi.html) ([модуль comment](https://github.com/yupe/yupe/tree/master/protected/modules/comment))
* Модуль простых справочников (хранение и управление справочной информацией) ([модуль dictionary](https://github.com/yupe/yupe/tree/master/protected/modules/dictionary))
* Модуль для ведения блогов ([как индивидуальных, так и коллективных](http://yupe.ru/blog/yupe-mini-cms-yii)) ([модуль blog](https://github.com/yupe/yupe/tree/master/protected/modules/blog))
* Модуль для "Обратной связи" + [раздел FAQ](http://yupe.ru/feedback/faq) ([модуль feedback](https://github.com/yupe/yupe/tree/master/protected/modules/feedback))
* Модуль для работы с Wiki - работает через [модуль yeeki](http://rmcreative.ru/blog/post/yeeki)
* Модуль документации, который позволяет создавать документацию для вашего сайта ([модуль docs](https://github.com/yupe/yupe/tree/master/protected/modules/docs))
* Модуль изображений ([модуль image](https://github.com/yupe/yupe/tree/master/protected/modules/image))
* Модуль галерея изображений, позволяющий организовать галереи изображений на вашем сайте ([модуль gallery](https://github.com/yupe/yupe/tree/master/protected/modules/gallery))
* Модуль для создания и редактирования произвольных блоков контента ([модуль contentblock](https://github.com/yupe/yupe/tree/master/protected/modules/contentblock))
* Модуль для создания заданий ([модуль queue](https://github.com/yupe/yupe/tree/master/protected/modules/queue))
* Модуль управления почтовыми сообщениями ([модуль mail](https://github.com/yupe/yupe/tree/master/protected/modules/mail))
* Модуль для установки системы ([модуль install](https://github.com/yupe/yupe/tree/master/protected/modules/install))
* Удобная админ панель в стиле Twitter Bootstrap  ([Выглядит вот так](http://yupe.ru/gallery/gallery/show/1))
* [Возможность генерировать CRUD в стиле Twitter Bootstrap](https://github.com/yupe/yupe/tree/master/protected/modules/yupe/extensions/yupe)


Лицензия
--------

Исходный код, макеты дизайна и вёрстка распространяются по [лицензии BSD](http://ru.wikipedia.org/wiki/%D0%9B%D0%B8%D1%86%D0%B5%D0%BD%D0%B7%D0%B8%D1%8F_BSD).

Сообщество будет благодарно если на сайте будет присутствовать ссылка на [http://yupe.ru/](http://yupe.ru/)


(c) 2009 - 2013 [amyLabs](http://amylabs.ru) && [Yupe! team](http://yupe.ru/)


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/yupe/yupe/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

