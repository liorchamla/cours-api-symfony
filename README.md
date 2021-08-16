# cours-api-symfony
Code du cours sur les API avec Symfony

# Installation

1. Clonez le dépot où vous voulez
2. Installez les dépendances : `composer install`
3. Créer une base de données: `php bin/console d:d:c`
4. Jouez les migrations : `php bin/console make:migration` puis `php bin/console d:m:m`
5. Jouez les fixtures : `php bin/console d:f:l --no-interaction`
6. Lancez le server : `symfony serve` ou `php -S localhost:3000 -t public`
