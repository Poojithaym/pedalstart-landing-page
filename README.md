# pedalstart-landing-page
The Pedalstart Landing Page is a web application designed to facilitate user authentication and securely store login information using HTML, CSS, PHP, and MySQL technologies. It serves as the initial interface for users to sign up for accounts and log in securely, leveraging a MySQL database backend for data storage.

This README provides basic information about the Pedalstart landing page project.


## Features

- **User Authentication:** Allows users to sign up for an account and log in securely.
- **MySQL Database Integration:** Stores user login information securely in a MySQL database.
- **HTML & CSS:** Provides an intuitive and visually appealing user interface.
- **PHP Backend:** Handles user authentication and interacts with the MySQL database to store and retrieve login information.

## Requirements

To run Pedalstart locally or deploy it to a server, you'll need the following:

- Web server (e.g., Apache, Nginx)
- PHP (>= 5.6)
- MySQL server
- Web browser

## Installation

1. Clone the repository:

Set up your MySQL database. You can do this via command line or a tool like phpMyAdmin.

Configure the database connection in config.php:

php
Copy code
<?php
define('DB_SERVER', 'localhost');
define('DB_USERNAME', 'your_username');
define('DB_PASSWORD', 'your_password');
define('DB_NAME', 'your_database_name');
$link = mysqli_connect(DB_SERVER, DB_USERNAME, DB_PASSWORD, DB_NAME);
if($link === false){
    die("ERROR: Could not connect. " . mysqli_connect_error());
}
?>
Import the SQL schema from database.sql to set up the necessary tables in your database.

Place the cloned repository in your web server's document root.

Navigate to the landing page in your web browser.

##Usage
Open your web browser and navigate to the landing page URL.
Sign up for an account if you're a new user, or log in if you already have an account.
Once logged in, you'll have access to any additional features or content provided by Pedalstart.
![pedalstart landingpage](https://github.com/Poojithaym/pedalstart-landing-page/assets/116658536/33979eb2-c459-442f-87b2-3388464e4372)


Contributors

Poojitha Y M
   
