# Laravel Sample Blog Setup

## Steps

- Clone the repo first.

- Navigate to the cloned repo directory.

```cmd
cd sample_laravel_blog
```

- Run the following command in Terminal. it will create .env file

```cmd
cp .env.example .env
```

- Update the database connection details in created .env file

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```

- Install all the dependancies

```php
composer install
```

- Now run below command to start the project

```php
php artisan serve
```
