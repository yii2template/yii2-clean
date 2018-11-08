Чистый шаблон на Yii2
===================

Чистый шаблон на Yii2 для быстрого старта разработки.

## Генерация кода

Создание проекта из шаблона:

    composer create-project --prefer-dist yii2template/yii2-clean

### Зависимости

Установка ``oauth-token`` от ``Github``

    composer config -g github-oauth.github.com <токен>

Удаление плагинов ``Composer`` для зависимостей ``bower`` и ``npm``

    composer global remove "fxp/composer-asset-plugin"

Устанавка зависимостей для разработки

    composer install

Генерация приложений:

    php vendor/yii2lab/yii2-app/src/yii

## Настрока

Инициализация проекта:

    php init

Проверьте настроки веб-домена и БД в конфиге `common/config/env-local.php`

Миграции БД:

    php yii migrate

Импорт данных в БД:

    php yii db/fixture

## Данные для входа

Заходим на сайт за админа:

    login: 77771111111
    password: Wwwqqq111

## Автотесты

Местоположение ``codeception`` задаем в файле ``console/config/params-local.php``

Запуск:

    php yii vendor/test/all
