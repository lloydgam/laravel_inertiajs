# Project Sample CRM No API SPA

A demo application to illustrate how Inertia.js works.
Building Application both Backend and Frontend without creating API.
Lazy Version of SPAs

Dockerized Version

## Installation

Docker:

```sh
docker-compose build
docker-compose up -d
```


Install PHP dependencies:

```sh
docker exec -it project_app bashc
composer install
```

Install NPM dependencies:

```sh
npm ci
```

Build assets:

```sh
npm run dev
```

Generate application key:

```sh
php artisan key:generate
```

Run database migrations:

```sh
php artisan migrate
```

Run database seeder:

```sh
php artisan db:seed
```

Run the dev server (the output will give the address):

```sh
php artisan serve
```

You're ready to go! Visit Ping CRM in your browser, and login with:

- **Username:** johndoe@example.com
- **Password:** secret

## Running tests

To run the Ping CRM tests, run:

```
phpunit
```

## Running PHPMYADMIN

To run the Ping CRM tests, run:

```
http://127.0.0.1:8080/
```
