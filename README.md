# User Management API

This repository contains the implementation of middleware for the User Management API, including logging, error handling, and authentication. The API manages user records with CRUD operations.

## Folder Structure

```
UserManagementAPI/
├── Controllers/
│   └── UserController.cs
├── Middleware/
│   ├── LoggingMiddleware.cs
│   ├── ErrorHandlingMiddleware.cs
│   └── AuthenticationMiddleware.cs
├── Models/
│   └── User.cs
├── Program.cs
├── Startup.cs
├── appsettings.json
├── appsettings.Development.json
├── UserManagementAPI.csproj
└── Properties/
    └── launchSettings.json
```

## Features

- CRUD operations for managing users: GET, POST, PUT, DELETE
- Middleware for:
  - Logging HTTP requests and responses
  - Handling errors consistently
  - Token-based authentication
- Validation for user data

## Getting Started

1. Clone the repository.
2. Navigate to the project directory.
3. Run `dotnet restore` to install dependencies.
4. Run `dotnet run` to start the application.

## Testing

Use Postman or a similar tool to test the API endpoints and validate middleware functionality.
