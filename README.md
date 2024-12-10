# Login and Signup System

A simple, responsive system using HTML, CSS, PHP, MySQL, and XAMPP.

## Features
- User registration, login, and logout
- Secure authentication with a modern UI

## Setup
1. Install XAMPP and start Apache and MySQL
2. Clone the repo:
```bash
git clone git@github.com:uniquesht1/login-signup.git
```

3. Create the database:
```sql
CREATE DATABASE login_signup;
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    firstName VARCHAR(255),
    lastName VARCHAR(255),
    email VARCHAR(255) UNIQUE,
    password VARCHAR(255)
);
```

4. Update `connect.php` with your database credentials
5. Open in browser:
```
http://localhost/login-signup/index.php
```



