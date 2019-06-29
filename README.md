# CRUD-Symfony_4.2

*bin/console doctrine:database:create
*bin/console make:entity
*bin/console make:migration
*bin/console doctrine:migrations:migrate
*composer require orm-fixtures --dev
*bin/console make:fixtures
*bin/console doctrine:fixtures:load
*bin/console doctrine:query:sql "select * from article"
*bin/console make:crud
*bin/console server:run