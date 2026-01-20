# laravel-template

## セットアップ手順

1. `docker compose up -d --build`
2. `docker compose exec php composer install`
3. `docker compose exec php cp .env.example .env`
4. `docker compose exec php php artisan key:generate`
5. `docker compose exec php php artisan migrate`
