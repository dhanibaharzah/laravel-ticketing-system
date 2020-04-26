## Installation

1. Clone this git repository

2. edit .env files according with your database configuration

3. Open a terminal at the app directory and Generate app key (i already include the vendor folders, so you dont have to install the composer)
```
php artisan key:generate
```
4. Make the database with utf8mb4 character set and utf8mb4_general_ci collation

5. Migrating to database
```
php artisan migrate --seed
```

7. Run the app, it will run on http://localhost:8000
```
php artisan serve
```
