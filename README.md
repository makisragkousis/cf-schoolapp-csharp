# Rest10mfpro

Rest10mfpro is a .NET 10 ASP.NET Core Web API for a school management system. It provides JWT-based authentication, user authorization, and a SQL Server-backed persistence layer built with Entity Framework Core.

## Overview

This repository contains the `SchoolApp` backend project, which exposes REST APIs for:

- user registration
- login and JWT authentication
- authorized user lookups
- paginated user listing
- school-domain data management

The project is structured as a layered backend service with controllers, services, repositories, data models, and DTOs.

## Features

- ASP.NET Core Web API
- .NET 10
- SQL Server with Entity Framework Core
- JWT Bearer authentication
- Role/capability-based authorization
- BCrypt password hashing
- Swagger/OpenAPI support
- Serilog logging
- Docker Compose support for local development

## Repository Structure

```text
Rest10mfpro/
├── SchoolApp/
│   ├── Configuration/
│   ├── Controllers/
│   ├── Core/
│   ├── Data/
│   ├── DTO/
│   ├── Exceptions/
│   ├── Helpers/
│   ├── Migrations/
│   ├── Models/
│   ├── Repositories/
│   ├── Security/
│   ├── Services/
│   ├── appsettings.json
│   ├── appsettings.Development.json
│   ├── Program.cs
│   ├── SchoolApp.csproj
│   ├── SchoolApp.http
│   └── db/
├── .env.example
├── .dockerignore
├── Dockerfile
├── docker-compose.yml
├── Rest10mfpro.slnx
├── .gitignore
└── README.md
