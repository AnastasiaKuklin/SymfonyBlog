SymfonyBlog - это сайт, блог, главная функция которого создание и редактирование статей.

Вы можете развернуть данный проект у себя на компьютере с помощью команд:
- cd <укажите место, где хотите видеть проект>
- git clone https://github.com/AnastasiaKuklin/SymfonyBlog

Проект создан с пмощью framework symfony. К нему подключена база данных MySQL, для хранения таблиц создана база данных blogdb.
Чтобы заполнить базу данных нужными таблицами, пропишите в терминал в дириктории проекта команду для миграции:
- php bin/console doctrine:migrations:migrate

Чтобы запустить проект, пропишите в терминал в дириктории проекта команду:
- symfony server:start

После запуска перейдите по ссылке: http://127.0.0.1:8000 
