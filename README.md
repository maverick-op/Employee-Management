# Employee-Management
Employee Management System – CRUD Web Application

A full-stack Employee Management System (EMS) built using Java Spring Boot, Thymeleaf, and MySQL. This application provides complete CRUD (Create, Read, Update, Delete) operations for managing employee records with an intuitive UI and robust backend architecture.

🚀 Features

Add new employees with details such as name, email, department, and salary

View all employee records in a clean, paginated dashboard

Update existing employee details

Delete employees from the system

Form validations for accurate and clean data entry

Search employees by name or email (optional enhancement)

🛠️ Tech Stack

Backend: Java, Spring Boot, Spring MVC, JPA/Hibernate
Frontend: Thymeleaf, HTML, CSS, Bootstrap
Database: MySQL
Build Tool: Maven
Version Control: Git & GitHub

📂 Architecture

The application is structured in a clean layered architecture:

Controller Layer: Handles HTTP requests and maps them to appropriate service methods.

Service Layer: Contains all business logic for employee management.

DAO (Data Access Object) Layer: Abstraction layer for database operations using Hibernate/JPA.

Repository Layer: JPA repository interfaces for CRUD operations.



📘 Core Modules

Employee creation and registration

Employee listing with dynamic tables

Employee update and edit module

Employee deletion with confirmation

Input validation and error handling

Optional: Search, sort, and pagination support



▶️ How to Run the Project

Clone the repository

Configure the MySQL database in application.properties

Run the project using Maven or your IDE

Open in browser:
http://localhost:8080/

📌 Future Enhancements

Role-based access (Admin/User)

Export employee data to Excel/PDF

REST API endpoints for external integration

Improved dashboard with charts and analytics
