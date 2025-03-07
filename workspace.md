# mi promer proyecto de laravel 12 com filamen

    git commit -m "1  inicio"

    git branch -M main

    git push -u origin main


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

## Instalacion de Filament

    composer require filament/filament:"^3.2" -W 
    php artisan filament:install --panels

###   Crear un usuario

    php artisan make:filament-user

    user: vroa74
    email:vroa74@gmail.com
    passsword: casacasa

### #Creando un recurso

    php artisan make:filament-resource user --generate
