
# 🚖 Taxi Service 🚖

### ⚡️ Project description

This is a Taxi Service project that aims to create a simple and efficient system for managing a taxi service. The project provides functionality for adding cars, them manufacturers, and adding taxi-drivers to cars.
A web app supports user authentication, registration and represent all information from database using CRUD principles.

### 🎯 Features

* registration/authentication like a driver
* create/update/remove a driver
* create/update/remove a car
* create/update/remove a manufacturer
* display list of all drivers
* display list of all cars
* display list of all manufacturers

### 📖 Architecture
Project consists main layer:
* dao;
* service;
* controller;

### 🤖 Technologies Used

* <b>Java11</b>: The project is implemented in Java, making use of object-oriented programming principles.
* <b>MySQL 8.0.24</b>: The MySQL database is used to store and retrieve data related to drivers, cars and manufacturers.
* <b>JDBC 4.3</b>: Java Database Connectivity (JDBC) is used to interact with the MySQL database.
* <b>Maven 4.0.0</b>: Maven is used as the build and dependency management tool for the project.
* <b>Tomcat 9.0.50</b>: Tamcat is used as a web server
* <b>JSTL 1.2</b>: Jakarta Standard Tag Library - it extends the JSP specification by adding a JSP tag library for common tasks such as XML data processing, conditional execution, database access, loops, and internationalization.
* <b>Servlet 4.0.1</b>: Standardized API for creating dynamic content to a web server
* <b>JSP 4.0.1</b>: Jakarta Server Pages - technology that allows us to dynamically generate web pages.

### ⚙️ Getting Started

To get started with the Taxi Service project, follow these steps:
1. Clone the repository: git clone https://github.com/chrisnyrka/taxi-service
2. Configure Tomcat server.
3. Set up the MySQL database and configure the connection details in the project.
4. Edit ConnectionUtil class where you should fill your own url, username and password.
5. Run the application.
