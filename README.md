# My Friend System

A web-based application developed using PHP, MySQL, HTML, and CSS. Users can create accounts, log in, add friends, and manage their friend lists.

## Features

- **User Registration:** Create an account with email and password validation.
- **User Login:** Authenticate registered users.
- **Friend List:** View and manage existing friendships.
- **Add Friends:** Discover users and add them to your friend list.
- **Friend Management:** Remove friends and update friend counts.
- **Session Management:** Maintain login sessions and log out securely.

## Technologies Used

- **Frontend:** HTML, CSS
- **Backend:** PHP
- **Database:** MySQL
- **Local Development:** XAMPP
- **Version Control:** Git and GitHub

## Getting Started

### Prerequisites

Install [XAMPP](https://www.apachefriends.org/) with Apache and MySQL.

### Installation

1. Clone or download this repository.
2. Copy the project folder into your XAMPP `htdocs` directory.
3. Start Apache and MySQL from the XAMPP Control Panel.
4. Open phpMyAdmin at `http://localhost/phpmyadmin/`.
5. Create a database using your name in lowercase form as its name.
6. Configure the database connection using the example configuration provided in settings.php.
7. Open `http://localhost/assignment2/` in your browser.

### Database Setup

The application uses two tables:

- `friends` — stores user account information and friend counts.
- `myfriends` — stores friendship relationships between users.

Follow the database setup instructions in the project before using the application.

## Project Structure

- `index.php` — Home page and database initialisation.
- `signup.php` — User registration.
- `login.php` — User authentication.
- `friendlist.php` — View and manage friends.
- `friendadd.php` — Add new friends.
- `logout.php` — Log out of the application.
- `about.php` — Project information.
- `settings.php` — Example database configuration.
- `includes/` — Shared page components.
- `style.css` — Stylesheet.

## Author

**Tyler Luc**

