# Student API Project with SQL Database - C#

This is a C# ASP.NET Core Web API project for managing student data. The project connects to a SQL Server database to perform CRUD (Create, Read, Update, Delete) operations on student records. It uses Entity Framework Core for database access and follows RESTful API principles.

## ✅ Features
- Add new students to the database
- Retrieve all students
- Retrieve a single student by ID
- Update student information
- Delete a student
- SQL Server database integration
- RESTful API endpoints

## 🧠 How It Works
- The project uses ASP.NET Core Web API to expose endpoints for student operations
- Entity Framework Core is used to interact with the SQL Server database
- The database file `StudentDB.bak` is provided and should be restored in SQL Server
- Controller methods handle HTTP requests and return JSON responses
- Routes are defined using attributes like `[HttpGet]`, `[HttpPost]`, `[HttpPut]`, `[HttpDelete]`
- Dependency Injection is used for the database context

## 🖥 Example Endpoints
- `GET /api/students` → Get all students
- `GET /api/students/{id}` → Get a student by ID
- `POST /api/students` → Add a new student
- `PUT /api/students/{id}` → Update a student
- `DELETE /api/students/{id}` → Delete a student

## ▶️ How to Run
1. Restore the `StudentDB.bak` file in SQL Server
2. Update the `appsettings.json` connection string to point to your SQL Server instance
3. Open the project in Visual Studio 2022
4. Build the solution
5. Run the project (it will open Swagger UI in the browser to test API endpoints)

## 📦 Requirements
- Visual Studio 2022 or later
- .NET 6.0 or later
- SQL Server (for restoring the `.bak` file)
- Entity Framework Core

## 👤 Author
Mohamed Mostafa - A simple and practical API project with SQL Server database integration.
