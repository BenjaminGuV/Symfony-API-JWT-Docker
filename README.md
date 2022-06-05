# API SIMPLE SYMPHONY 5.4 & JWT CON DOCKER

API simple con autentificacion token

#Comandos

Activar docker

cmd: docker-compose up -d --build

Instalar symphony

cmd: docker-compose exec php bash

cmd: git config --global user.email "you@example.com"

cmd: git config --global user.name "Your Name"

cmd: symfony new . --version=5.4

cmd: composer require symfony/orm-pack

cmd: composer require --dev symfony/maker-bundle

cmd: composer require symfony/security-bundle

cmd: composer require lexik/jwt-authentication-bundle

cmd: php bin/console lexik:jwt:generate-keypair

# Cambiar la configuracion de conexion

cmd: php bin/console make:user

cmd: php bin/console make:migration

cmd: php bin/console doctrine:migrations:migrate

cmd: php bin/console security:hash-password

cmd: php bin/console make:controller ProjectController

# Desinstalar

cmd: docker-composer down

# Documentación

https://symfony.com/doc/5.4/

https://github.com/lexik/LexikJWTAuthenticationBundle

https://www.youtube.com/watch?v=PxToeu4ySxU&ab_channel=VinixCode