# Luego de clonarte sigue los siguentes pasos

# 1. Vaya al directorio del proyecto:
    cd nombre_de_la_carpeta
# 2. Instale las dependencias del proyecto:
    composer install
# 3. Copia el archivo el contenido del .env.example y crea un archivo .env:
    Si linux:
        cp .env.example .env
    Si windows:
        copy .env.example .env
# 4. Cree la clave de la aplicación:
    php artisan key:generate
# 5. Inicie el servidor laravel:
    php artisan serve
# 6. Dirigete a tu navegador preferido e ingresa el siguiente enlace:
    http://127.0.0.1:8000
