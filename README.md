# PHP --Doctrine

Projeto com base do curso ALURA.

Doctrine ORM com PHP.


Configure o composer.json na raiz conforme abaixo:
{
    "require": {
        "doctrine/orm": "^2.11.0",
        "doctrine/dbal": "^3.2",
        "doctrine/annotations": "1.13.2",
        "symfony/yaml": "^5.4",
        "symfony/cache": "^5.4"
    },
    "autoload": {
        "psr-4": {
            "Alura\\doctrine\\": "src/"
        }
    }
}


===================================================
* defina o nome space em     
"autoload": {
    "psr-4": {
        "XXXXXXX\\doctrine\\": "src/"
    }"


Após a criação do composer.json execute o "composer install", ele deverá criar o diretório "vendor" com os componentes necessários.