# eventregistrationsystem
# Event Registration System (PHP)

## Project Title

**Event Registration System**

## Description

The Event Registration System is a PHP-based web application that allows users to register for events online. The system manages event details, user registrations, and stores all information securely in a MySQL database. It is designed to be simple, user-friendly, and suitable for academic or small-scale event management purposes.

## Features

* User registration for events
* Event creation and management
* Secure database connection using PHP (PDO/MySQL)
* Form validation
* Simple and clean user interface
* Database-driven system

## Technologies Used

* PHP
* MySQL
* HTML5
* CSS3
* JavaScript (optional)
* Apache (XAMPP / WAMP / InfinityFree)

## Project Structure

```
eventregistrationsystem/
│── config/
│   └── db.php
│── public/
│   ├── index.php
│   ├── register.php
│   └── login.php
│── includes/
│   ├── header.php
│   └── footer.php
│── sql/
│   └── database.sql
│── README.md
```

## Database Setup

1. Create a MySQL database (example: `eventregistrationsystem`).
2. Import the SQL file located in the `sql/database.sql` folder.
3. Update database credentials in the configuration file:

```php
$host = "localhost";
$dbname = "eventregistrationsystem";
$username = "root";
$password = "";
```

## How to Run the Project

### Localhost (XAMPP/WAMP)

1. Install XAMPP or WAMP.
2. Copy the project folder into the `htdocs` directory.
3. Start Apache and MySQL.
4. Open a browser and visit:

   ```
   http://localhost/eventregistrationsystem
   ```

### Online Hosting (InfinityFree or similar)

1. Upload project files to the hosting server.
2. Create a MySQL database from the hosting control panel.
3. Update database credentials in the config file.
4. Import the SQL database file.

## Usage

* Open the application in a browser.
* Create or view available events.
* Register users for events.
* View registered participants via the database or admin interface (if implemented).

## Authors

* **Full Name:** Mugema Fabrice
* **Registration Number:** 24RP01072

## License

This project is created for educational purposes. You are free to modify and use it for learning and academic projects.



*End of README*
