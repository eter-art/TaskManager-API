# TaskManager API

A RESTful API for managing tasks, built with ASP.NET Core and Entity Framework Core.

## Tech Stack

- **C# / .NET 10**
- **ASP.NET Core Web API**
- **Entity Framework Core 9**
- **SQLite**
- **Swagger / OpenAPI**

## Features

- Create, read, update and delete tasks (CRUD)
- SQLite database with Entity Framework Core
- API documentation via Swagger UI

## Getting Started

### Prerequisites
- .NET 10 SDK

### Run the project

```bash
git clone https://github.com/eter-art/TaskManager-API
cd task-manager-api
dotnet run
```


Open your browser at `https://localhost:7244/swagger` to explore the API.

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/tasks | Get all tasks |
| GET | /api/tasks/{id} | Get task by ID |
| POST | /api/tasks | Create a new task |
| PUT | /api/tasks/{id} | Update a task |
| DELETE | /api/tasks/{id} | Delete a task |