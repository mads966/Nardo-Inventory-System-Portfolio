# Nardo's Inventory Management System

A Java desktop inventory and sales management application developed as a team software engineering project for COMP2140.

This portfolio copy preserves the original application code and demo behavior while documenting the project in a recruiter-friendly format.

## Overview

Nardo's Inventory Management System supports day-to-day inventory operations through a Java desktop interface backed by MySQL. The application is organized into dedicated packages for authentication, products, sales, stock movement, suppliers, reporting, alerts, and database access.

## Key Features

- Product and inventory management
- Product search and filtering
- Supplier records
- Sales processing and sales history
- Stock movement tracking
- Low-stock alerts and notifications
- User authentication and session management
- Role-based access controls
- Password-strength validation and salted password hashing
- Inventory and sales reporting
- MySQL-backed data persistence through JDBC

## Technologies

- Java
- Java Swing
- MySQL
- JDBC / MySQL Connector/J
- Object-Oriented Programming
- DAO and service-layer organization
- Git / GitHub

## Project Structure

```text
src/
├── alert/       # Alert persistence and management
├── database/    # Database connection management
├── enums/       # Shared application enums
├── login/       # Authentication, users, sessions, and password handling
├── main/        # Main dashboard and application panels
├── product/     # Product models, services, validation, and search/filtering
├── report/      # Inventory/sales reporting
├── sale/        # Sales processing, history, and statistics
├── stock/       # Stock movements and low-stock notifications
├── supplies/    # Supplier data access
└── resources/   # Database schema, images, connector, and project documentation
```

## Software Engineering Concepts Demonstrated

- Separation of application concerns across packages
- Object-oriented design
- Data-access objects for database operations
- Service/manager classes for business logic
- Input validation
- Authentication and session handling
- Database-backed CRUD workflows
- Requirements, UML/design documentation, and testing artifacts

## Running the Project

The project was developed as an IntelliJ-based Java desktop application.

1. Install Java and MySQL/XAMPP.
2. Load `src/resources/database.sql` into a local MySQL instance.
3. Ensure the included MySQL Connector/J library is configured in the project.
4. Open the project in IntelliJ IDEA.
5. Run `src/login/LoginPage.java` to start the application from the login screen.

> **Note:** This is an academic/demo application. Development credentials and local database settings are included for demonstration and should not be reused in a production environment.

## Team Project

This application was developed collaboratively as part of COMP2140 Software Engineering. This repository is maintained as a portfolio presentation of the completed project and does not represent a claim of sole authorship.

## Portfolio Notes

The source code and demo functionality in this portfolio copy are intentionally preserved. Presentation-focused improvements include this documentation and any screenshots added later.
