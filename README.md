# ASP.NET API Project<br>

## Description<br>
This project demonstrates the development of a robust RESTful API using ASP.NET Core. It employs a clean architecture design pattern, including controllers, services, and DTOs for data abstraction. Key features include the integration of ORM for database interaction, HTTPS for secure communication, and logical layers to handle business rules efficiently.<br><br>

## Key Concepts<br>
1. **Controller-Service Design Pattern**<br>
   - Controllers: Handle incoming HTTP requests and return appropriate responses.<br>
   - Services: Encapsulate business logic and are injected into controllers for separation of concerns.<br><br>

2. **Data Transfer Objects (DTOs)**<br>
   - Simplify and standardize data exchanged between layers.<br>
   - Avoid direct exposure of database entities to the API consumers.<br><br>

3. **Object-Relational Mapping (ORM)**<br>
   - Utilizes Entity Framework Core to interact with the database.<br>
   - Provides database-agnostic models and support for migrations.<br><br>

4. **HTTPS and Certificates**<br>
   - The API enforces secure communication using HTTPS.<br>
   - Uses development certificates during local testing to simulate a secure environment.<br><br>

5. **Async/Await for Asynchronous Operations**<br>
   - Implements asynchronous programming to improve API performance.<br>
   - Ensures non-blocking execution for database and external calls.<br><br>

6. **Program.cs Configuration**<br>
   - Centralized setup for middleware, services, and endpoints.<br>
   - Configures Swagger for API documentation and testing.<br><br>

7. **Swagger Integration**<br>
   - Provides an interactive API documentation page.<br>
   - Supports testing endpoints directly through the Swagger UI.<br><br>

## Features<br>
- CRUD operations for database entities.<br>
- Clear separation of business logic and data access.<br>
- Asynchronous methods for scalable operations.<br>
- Swagger UI for testing and exploring the API.<br>
- HTTPS for secure client-server communication.<br><br>

## Requirements<br>
- .NET SDK (version 8.0).<br>
- A configured SQL Server instance.<br>
- A modern web browser to access Swagger UI.<br><br>

## Author<br>
Diego Rousseaux<br>
