# Supermarket Management System

Welcome to the Supermarket Management System repository! This project is a web-based application that helps manage a supermarket's operations efficiently. It includes features for user authentication, billing, stock and financial management, analytics, and user account management. The system is built using a combination of HTML, PHP, and MySQL, and it is designed to run on the XAMPP server.

## System Requirements

To run this application locally, ensure you have the following software and tools installed:

XAMPP Server: XAMPP is required to set up the local development environment, including Apache, PHP, and MySQL.

## Installation

Follow these steps to set up the Supermarket Management System:

1. Move the project files to the appropriate directory in your XAMPP server's webroot folder.

2. Start XAMPP and ensure that Apache and MySQL services are running.

3. Import the database into phpMyAdmin:

   Open a web browser and navigate to http://localhost/phpmyadmin.
   Create a new database named supermarket_management_system.
   Select the newly created database and import the provided supermarket_management_system.sql file.

4. Configure the database connection:

   Open the config.php file located in the project's root directory.
   Modify the $db_username, $db_password, and $db_name variables to match your database credentials.

5. Now, the application should be accessible by navigating to http://localhost/supermarket-management-system in your web browser.

## MODULES

- **Notification of insufficient stock module.**
- **Normal employee:**
- Generate bill module
- **Stock manager:**
- Generate bill module
- View and update stock module
- Add product module
- Update product details module
- **Admin:**
- Generate bill module
- View and update stock module
- Add product module
- Update product details module
- Auditing payments and adding supplier module
- Sales report module
- User account management module
- Organization information module

## Features

The Supermarket Management System includes the following features:

Login Page: Users can log in to access the system by providing their username and password.

Home Page: Upon successful login, users are directed to the home page. The home page contains the following options:

Billing: Allows users to create bills for customers, including product selection, quantity, and discounts.

Stock and Financial Management: Deals with financial aspects and stock management of the organization.

Analytics: Provides analysis of the organization's past purchase and sales reports.

Manage Account: Allows user account management, including employees of the organization.

Update Details: Allows updates to the organization's information (not related to the database management system).

Logout: Allows users to log out of the system.

Upload Employee Profile: Users have the option to upload their profile information.
