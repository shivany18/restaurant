# Restaurant Management System

## Project Overview

This is a Restaurant Management Website developed using **CodeIgniter (PHP Framework)** and **XAMPP**.

The system includes:

- Menu display
- Table reservation form
- Contact form
- Admin login system
- Feedback management (with approval system)

The project follows the MVC (Model-View-Controller) architecture of CodeIgniter.


## Technologies Used

- PHP
- CodeIgniter
- MySQL
- XAMPP
- HTML5
- CSS3
- Bootstrap


## System Requirements

- XAMPP (Apache + MySQL)
- PHP 7+
- MySQL
- Web Browser (Chrome / Firefox / Edge)


## Installation Guide

### Step 1: Install XAMPP
Download and install XAMPP.

### Step 2: Move Project Folder
Copy the project folder into:

```
C:\xampp\htdocs\
```

Example:
```
C:\xampp\htdocs\restaurant_project
```

---

### Step 3: Start Apache & MySQL

Open XAMPP Control Panel and start:

- Apache
- MySQL

---

### Step 4: Create Database

1. Open browser:
   ```
   http://localhost/phpmyadmin
   ```
2. Create a new database:
   ```
   restaurant_db
   ```
3. Import the provided SQL file (if available).

---

### Step 5: Configure Database

Open:
```
application/config/database.php
```

Update:

```php
'hostname' => 'localhost',
'username' => 'root',
'password' => '',
'database' => 'restaurant_db',
```

---

### Step 6: Run the Project

Open browser:

```
http://localhost/restaurant_project/
```

---

## Features

### User Side
- View Menu
- Submit Reservation
- Submit Feedback
- Contact Form

### Admin Side
- Admin Login (Username & Password)
- Approve/Reject Feedback
- Manage Reservations
- Manage Menu Items

---

## Project Structure

```
application/
    controllers/
    models/
    views/

assets/
    css/
    images/

system/
```

---

## Architecture

This project follows **MVC Architecture**:

- Model → Database interaction
- View → User interface
- Controller → Business logic

---

## Future Improvements

- Online payment integration
- Email confirmation for reservations
- Dashboard analytics
- Role-based access control

---

## Author

Developed as a Restaurant Management System using CodeIgniter.

---

## License

This project is created for academic purposes.
