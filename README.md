# giftd-umi-cms
Giftd module for UMI.CMS


Russian Instruction
===============

Установка модуля в магазин
--------------------------


1. [Скачайте архив модуля](https://github.com/Giftd/giftd-umi-cms) из репозитория.
2. Откройте для редактирования файл config.ini, который располагается в корневой папке сайта, найдите параметр «buffer-send-event-enable» и установите ему значение «1».
3. Загрузите содержимое архива через FTP в корень вашего сайта. Замените все существующие файлы при необходимости.
4. Перейдите в админ панель сайта «Модули» > «Конфигурация» > «Модули». В поле «Путь до инсталляционного файла» наберите classes/components/giftd/install.php и нажмите «Установить».
5. Откроте страницу ваш_сайт/admin/giftd/config/ и заполните поля настроек:
* ID пользователя GIFTD
* Ключ API GIFTD
* Код партнера Giftd
* Префикс кодов подарочных карт
* Класс к которому привязывать поле ввода кода купона – класс блока, после которого в корзине будет добавлен блок для ввода купона. Данный класс обязательно должен быть уникальным.
6. Нажмите «Сохранить»
