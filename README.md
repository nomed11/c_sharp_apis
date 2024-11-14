# API Development with C# and ASP.NET Core

This repository contains a comprehensive example of a RESTful API built with C# and ASP.NET Core, showcasing best practices in API design and development.

## Project Overview

This API project demonstrates:

- **RESTful API principles** for creating scalable and maintainable endpoints.
- **Entity Framework Core** for streamlined data persistence.
- **Controller setup and OpenAPI integration** for automated API documentation.
- **Validation and error handling** for reliable user interactions.
- **Middleware and Dependency Injection** to support modularity and maintainability.
- **Database migrations and data seeding** for a seamless database setup.

## Technologies Used

- **C# and .NET Core**
- **ASP.NET Core**
- **Entity Framework Core**
- **SQLite** (or another database of your choice)
- **XUnit** for testing
- **Swagger/OpenAPI** for API documentation

## Installation and Setup

1. **Clone the repository**:

```bash
git clone https://github.com/yourusername/aspnetcore-api-project.git
cd aspnetcore-api-project
```

2. **Install dependencies**:

```bash
dotnet restore
```

3. **Set up the database**:
   - Update `appsettings.json` with your database configuration.
   - Run migrations:

```bash
dotnet ef database update
```

4. **Run the application**:

```bash
dotnet run
```

5. **Access API Documentation**:
   - Visit `http://localhost:<port>/swagger` for the OpenAPI documentation provided by Swagger.

## Usage

The API provides endpoints to manage a variety of resources, following REST principles. Refer to the Swagger UI for detailed information on each endpoint.

## Testing

To execute tests, use:

```bash
dotnet test
```
