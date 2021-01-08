![PHP OOP Concepts](./images/banner.png)

Setup
-----

### 1) Database Setup

A) open `init_db.php` and modify the `$databaseUser` and `$databasePassword` variables.
Make sure the user has permissions to create a database!

B) To create and pre-populate your database, open your favorite terminal application
and run:

```bash
cd /path/to/the/project
php init_db.php
```
That's it! Your database is ready to go!

### 2) Composer Autoload Setup

A) Run `composer install` (from this project directory):

```bash
composer install
```

### 3) Web Server Setup

To get this code working, start the php built-in web server

```bash
cd /path/to/the/project
php -S localhost:8000
```
