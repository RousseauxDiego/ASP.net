ASP.NET API Project
Description
This project demonstrates the development of a robust RESTful API using ASP.NET Core. It employs a clean architecture design pattern, including controllers, services, and DTOs for data abstraction. Key features include the integration of ORM for database interaction, HTTPS for secure communication, and logical layers to handle business rules efficiently.

Key Concepts
1. Controller-Service Design Pattern
Controllers: Handle incoming HTTP requests and return appropriate responses.
Services: Encapsulate business logic and are injected into controllers for separation of concerns.

2. Data Transfer Objects (DTOs)
Simplify and standardize data exchanged between layers.
Avoid direct exposure of database entities to the API consumers.

3. Object-Relational Mapping (ORM)
Utilizes Entity Framework Core to interact with the database.
Provides database-agnostic models and support for migrations.

4. HTTPS and Certificates
The API enforces secure communication using HTTPS.
Uses development certificates during local testing to simulate a secure environment.
5. Async/Await for Asynchronous Operations
Implements asynchronous programming to improve API performance.
Ensures non-blocking execution for database and external calls.

6. Program.cs Configuration
Centralized setup for middleware, services, and endpoints.
Configures Swagger for API documentation and testing.

7. Swagger Integration
Provides an interactive API documentation page.
Supports testing endpoints directly through the Swagger UI.
Features
CRUD operations for database entities.
Clear separation of business logic and data access.
Asynchronous methods for scalable operations.
Swagger UI for testing and exploring the API.
HTTPS for secure client-server communication.
Requirements
.NET SDK (version 8.0).
A configured SQL Server instance.
A modern web browser to access Swagger UI.

Author
Diego Rousseaux
 
 
