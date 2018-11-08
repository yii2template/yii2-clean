Чистый шаблон на Yii2
===================

Чистый шаблон на Yii2 для быстрого старта разработки.

## Генерация кода

Создание проекта из шаблона:

    composer create-project --prefer-dist yii2template/yii2-clean

Устанавка зависимостей:

    composer install

Генерация приложений:

    php vendor/yii2lab/yii2-app/src/yii

## Настрока

Инициализация проекта:

    php init

Проверьте настроки ссылок и БД в конфиге `env-local.php`

Миграции БД:

    php yii migrate

Импорт данных в БД:

    php yii db/fixture

Запускаем автотесты:

    php yii vendor/test/all

Заходим на сайт за админа:

    login: 77771111111
    password: Wwwqqq111
