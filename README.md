# Système de Gestion d'Utilisateur (SGU)

## Project Overview

SGU (Système de Gestion d'Utilisateur) is a web application for managing user registrations and logins securely. It includes functionalities for user registration, login, and CRUD operations on user data, all while implementing key security practices.

## Features and Objectives

- **User Registration and Login**: Secure sign-up and sign-in functionalities.
- **CRUD Operations**: Create, Read, Update, and Delete user records.
- **Security Measures**: Password hashing, SQL injection prevention, XSS protection, and CSRF token implementation.

## Technologies Used

- **HTML5**
- **CSS3**
- **PHP**
- **JavaScript**
- **MySQL**

## Installation Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SiRipo92/APP-SGU.git
2. **Setup XAMPP**:
    - Ensure XAMPP is installed and running.
    - Place the project folder (SGU) in the htdocs directory of XAMPP.
3. **Database Setup**:
    - Create a MySQL database
    - Import the provided SQL schema file to set up the database structure.

## Configuration

1. **Update Configuration**:
    - Edit the config.php file in the includes directory to configure database connection details.

## Usage

1. **Run the application**:
    - Start Apache and MySQL services in XAMPP.
    - Access the application via http://localhost/SGU.
2. **Basic Usage**:
    - Navigate to the registration page to create a new account.
    - Use the login page to access your account.


## Security Considerations
 1) **Password Hashing**: Passwords are hashed using PHP’s password_hash() function to enhance security.
 2) **SQL Injection Prevention**: Prepared statements with parameterized queries are used.
 3) **XSS Protection**: User inputs are sanitized and escaped.
 4) **CSRF Protection**: CSRF tokens are implemented to prevent Cross-Site Request Forgery attacks.

## License

This project is private and not licensed for public use. All rights are reserved to the owner.

## Contact
For any questions or support, please contact contact@sierrawebdev.com .