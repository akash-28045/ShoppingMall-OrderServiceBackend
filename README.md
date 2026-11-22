
  # SHOPPING MALL MANAGEMENT SYSTEM – ORDER SERVICE (SPRING BOOT)

  # PROJECT OVERVIEW:

This project is the backend service of a Shopping Mall Management System, developed using Java and Spring Boot. It is designed as a standalone Order Service module that manages order-related operations through RESTful APIs. The application allows users to create new orders, retrieve all orders, search for a specific order by ID, update order status, and delete orders. It uses PostgreSQL for persistent data storage and Spring Data JPA to simplify database interactions.

# BACKEND DESCRIPTION:

The backend follows a layered architecture consisting of Controller, Service, Repository, and Entity layers, ensuring separation of concerns and organized application logic.

The Controller layer handles incoming HTTP requests and exposes REST API endpoints for order management. The Service layer contains the business logic required to process order-related operations. The Repository layer uses Spring Data JPA to interact with the PostgreSQL database, while the Entity layer represents the order data structure mapped to database tables.

The application supports HTTP operations such as POST, GET, PUT, and DELETE to perform order management functionalities. JSON request and response bodies are used for communication between the frontend and backend. Postman is used to test API endpoints and validate application responses.

## WHAT THIS APPLICATION DOES:
- This application manages order-related operations in a shopping mall through a standalone backend service.
- It allows users to create, view, update, and delete orders using RESTful APIs.
- It processes order requests and handles business logic through Spring Boot.
- It stores and retrieves order information using PostgreSQL and Spring Data JPA.
- It provides API endpoints for communication with the Angular frontend.

### IT ALLOWS USER TO:

- Create a new order

- View all orders

- View order by ID

- Update order status

- Delete an order

- Built as a standalone Order Service module using REST APIs

# TECHNOLOGIES USED:

- Java - Core programming language for backend logic

- Spring Boot - Makes backend development fast and easy

- Spring Data JPA - Handles database operations without writing SQL

- PostgreSQL - Stores order data securely

- Postman API - Used to test REST APIs

- Maven - Manages project dependencies

# CHALLENGES FACED DURING THE PROJECT:

- Understanding REST API flow (Controller → Service → Repository)

- Fixing 404 errors due to incorrect URL mapping

- Connecting Spring Boot with PostgreSQL

- Handling JSON request body correctly in Postman

- Learning how JPA automatically creates tables

 # INSTALLATION SETUP TOOLS AND SETUP USED:

- Installed JDK 17

- Installed Eclipse / Springboot Eclipse

- Installed PostgreSQL & pgAdmin

- Created database for Order Service

- Configured application.properties for DB connection

- Built project using Maven

- Tested APIs using Postman

# ARCHITECTURE USED:

## Layered Architecture:

- Controller Layer

- Service Layer

- Repository Layer

- Entity Layer

- RESTful API design

 # OUTCOME:

- Successfully created a working Order Service

- Data stored and retrieved from PostgreSQL

- APIs tested and validated using Postman
