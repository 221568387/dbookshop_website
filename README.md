# TECH WRLD BOOKSHOP - README

## Overview
This is an online bookstore project that allows users to browse and purchase books. Users must log in to access the shop.

## Features
- User authentication (Login system)
- Book listing from database
- Shopping cart functionality
- Secure database connection

## Installation & Setup

### 1. Install XAMPP (or any local server)
- Download and install [XAMPP](https://www.apachefriends.org/download.html).
- Ensure Apache and MySQL are running.

### 2. Set Up Database
- Open **phpMyAdmin** (`http://localhost/phpmyadmin`).
- Create a new database named **tech_wrld**.
- Import the `tech_wrld.sql` file provided in the project folder.

### 3. Configure Database Connection
Edit the `db.php` file to match your database settings:
```php
$servername = "localhost:3307"; // Change if needed
$username = "root";
$password = "";
$dbname = "tech_wrld";
```
If your MySQL runs on the default port (`3306`), update `localhost:3307` to `localhost`.

### 4. Start the Server
Place the project folder inside `htdocs` (for XAMPP).
Start Apache and MySQL from the XAMPP control panel.

### 5. Access the Website
Open a browser and go to:
```
http://localhost/Bookshop-Website-Web-Assignment/index.php
```

### 6. Login to Shop
Use a registered user account or create a new one.

## Troubleshooting
- If login fails, check that the `users` table contains valid credentials.
- Verify MySQL is running on the correct port (`3307` or `3306`).
- Check the session settings in `shop.php` to ensure users are authenticated before accessing the shop.

## License
This project is for educational purposes. Modify as needed.

