## LSJIR
# Laravel 10, LaravelSail, Jetstream, InertiaJS, React 18, Typescript start project

# //Установка Sail 
# curl -s "https://laravel.build/example-app?with=pgsql,redis" | bash

#Выбор комплекта из докер контейнеров
# // mysql, pgsql, mariadb, redis, memcached, meilisearch, minio, selenium, mailpit

# //Установка Jetstream в Laravel
# composer require laravel/jetstream

# //Установка Jetstream этап второй с InertiaJS без SSR
# php artisan jetstream:install inertia
# npx laravel-jetstream-react@latest install

# //Установка Jetstream этап второй с InertiaJS с SSR
# php artisan jetstream:install inertia --ssr 
# npx laravel-jetstream-react@latest install --ssr 

# //Установка Jetstream этап второй с InertiaJS с SSR с командой и тёмной темой
# php artisan jetstream:install inertia --teams --ssr --dark
# npx laravel-jetstream-react@latest install --teams --ssr --dark

# //Vite manifest
# Заменить в файле манифеста файлы с расширением .vue на .tsx
# Путь /public/build/manifest.json

# //Билд фронта
# npm run build
# //Автобилд для разработки
# npm run hot

# //Запуск
# ./vendor/bin/sail up

# //Миграции
# ./vendor/bin/sail artisan migrate
