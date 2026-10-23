# Copilot Instructions — telegram-app

## Project
Laravel 11 web application (PHP 8.2, Blade templates, Vite + Tailwind CSS frontend).

## Setup
- Install PHP dependencies: `composer install`
- Copy `.env.example` to `.env` and run `php artisan key:generate`
- Frontend assets: `npm install` and `npm run build`

## Coding rules
- Follow standard Laravel conventions (PSR-12, Laravel naming).
- Keep changes small and focused on the assigned issue; do not refactor unrelated code.
- Never commit real secrets: no `.env` file, no database dumps (`.sql`), no `error_log` files.
- Do not edit `vendor/` or `node_modules/`.

## Testing
- Run PHP syntax check on changed files: `php -l <file>`
- If tests exist for the changed area, run: `php artisan test`
