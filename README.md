# Dynamic Web Project - User Registration System

## Overview

This dynamic web project implements a user registration system using Java Servlets and JSP. It provides functionality for users to register with a username and password, encrypts the passwords for security, and stores user data in a database.
The project also includes client-side validation, CAPTCHA generation, and session management.

## Features

- User registration with encrypted password storage.
- Session management to handle user authentication and expiration.
- Password strength validation.
- CAPTCHA generation to prevent automated submissions.
- Error handling for null or empty inputs and encryption failures.

## Technologies & Tools Used

- Apache Tomcat9 Server
-  Eclipse IDE for Enterprise Java and Web Developers
- HTML/CSS
- JavaScript
- MySQL WorkBench
- JAR files(mysql-connector-java-8.0.19.jar, javax.servlet.jsp.jstl-1.2.1.jar, javax.servlet.jsp.jstl-api-1.2.1.jar)

## Project Structure

The project consists of the following components:

1. **Servlets**:
   - `RegisterControllerServlet.java`: Handles user registration requests.

2. **Utility Classes**:
   - `EncryptionUtil.java`: Provides methods for encrypting and decrypting passwords.
   - `RegisterDBUtil.java`: Handles database operations related to user registration.

3. **Web Pages**:
   - `index.jsp`: Provides the user interface for the registration form.
   - `sessionExpired.jsp`: Displays a message when the session expires.
   - `successRegistration.jsp`: Indicates successful user registration.

4. **Database Configuration**:
   - `context.xml`: Configuration file for defining the data source/connection pool.

5. **Front-end Resources**:
   - `style.css`: CSS styles for the registration form.
   - `script.js`: JavaScript for form validation and CAPTCHA generation.

## Installation

To run this project locally, follow these steps:

1. Unzip the contents of Security Program and open the folder on your IDE 
2. Set up a compatible database server MySQL Workbench and create a database schema using the sql user file provided in the bi56kz folder.
3. Update the database configuration in `context.xml` with your database credentials and schema details.
4. Configure your servlet container,Tomcat to deploy the project.
5. Build and deploy the project to your servlet container by running it on your server.
6. Access the registration form through the appropriate URL.

## Usage

Once the project is deployed and running on your local server, users can access the registration form through the provided URL.
They can then register by providing a username, password, and completing the CAPTCHA verification.

## Acknowledgements

- Thanks to the developers of Java Servlets, JSP, JDBC, and Tomcat Server for providing robust tools for web development.
- Special thanks to Aobakwe Robyn Pelonomi Kenosi for their contributions to the development of this project.
