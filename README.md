# Taxi-Service Project

## Introduction

This project is a taxi service application that allows users to create, manage, and delete drivers, cars, and manufacturers using a web-based interface. The application was built using Java, Servlet API, JDBC, JSP, HTML, and JSTL.

## Features

#### The application has the following features:

- User registration and authentication
- Create new drivers, cars, and manufacturers
- View all drivers, cars, and manufacturers
- Edit and delete existing drivers, cars, and manufacturers

## Technologies

#### The project was built using the following technologies:

- Servlet API: a Java API that provides a way to handle HTTP requests and responses
- JDBC: a Java API for connecting and executing SQL queries on a database
- JSP: a technology that allows web developers to create dynamically generated web pages based on HTML, XML, or other document types
- HTML: a markup language used to create web pages
- JSTL: a standard tag library for JavaServer Pages that provides a set of tags for common tasks, such as looping and conditional statements

## Getting Started

#### To run the application, the following prerequisites are needed:

- Java 17 or later
- Apache Tomcat 9 (version 9.0.73 is recommended)
- MySQL 8 or later

#### To install the application, follow these steps:

1. Clone the repository using the command git clone https://github.com/Ukrainets-Oleksii/taxi-service
2. Open the project in your preferred IDE and build the project
3. Create the database schema and tables using the scripts provided in the src/main/resources/init_db.sql
4. In the ConnectionUtil class, change the values of the constants to your own. You need to change 4 constants:
   ````
   private static final String URL = "DB URL";
   private static final String USERNAME = "YOUR USERNAME";
   private static final String PASSWORD = "YOUR PASSWORD";
   private static final String JDBC_DRIVER = "JDBC DRIVER";
   ````
5. Deploy the WAR file in Tomcat
6. Start the application

## Best Practices

#### When working on this project, the following best practices were followed:

- Clear and concise naming conventions were used for variables, classes, and methods
- Code was organized into meaningful packages
- Defensive programming techniques were used to prevent bugs and exceptions
- Version control was used to manage code changes and collaboration between team members
- Code was kept simple and maintainable to reduce the likelihood of introducing bugs and improve future maintainability
- Code was regularly reviewed to identify and correct any issues