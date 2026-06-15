# DotRidu - Vertical Slice Architecture Template

[![NuGet](https://img.shields.io/nuget/v/dotridu)](https://www.nuget.org/packages/dotridu)
[![NuGet Downloads](https://img.shields.io/nuget/dt/dotridu)](https://www.nuget.org/packages/dotridu)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE.txt)
[![.NET](https://img.shields.io/badge/.NET-10.0-purple)](https://dotnet.microsoft.com/)

A production-ready ASP.NET Core Vertical Slice Architecture template with JWT authentication, MediatR, FluentValidation, and Entity Framework Core.

## 🚀 Quick Start

### Install Template
```bash
dotnet new install dotridu
```

### Create New Project
```bash
# Create your project
dotnet new dotridu -n YourProjectName

# Navigate to project
cd YourProjectName

# Restore packages
dotnet restore

# Run the application
dotnet run
```

### Uninstall Template
```bash
dotnet new uninstall dotridu
```

## 📁 Project Structure
```
YourProjectName/
├── src/
│   ├── YourProjectName.Core/                # Business Logic
│   │   ├── Features/
│   │   │   └── {Feature}/
│   │   │       └── v1/
│   │   │           ├── Create{Feature}/
│   │   │           │   ├── Create{Feature}Endpoint.cs
│   │   │           │   ├── Create{Feature}Command.cs
│   │   │           │   ├── Create{Feature}Handler.cs
│   │   │           │   └── Create{Feature}Validator.cs
│   │   │           ├── GetAll{Feature}/
│   │   │           │   ├── GetAll{Feature}Endpoint.cs
│   │   │           │   ├── GetAll{Feature}Query.cs
│   │   │           │   └── GetAll{Feature}Handler.cs
│   │   │           └── Shared/
│   │   │               ├── {Feature}.cs                  # Domain Entity
│   │   │               └── {Feature}Configuration.cs     # EF Core Mapping
│   │   ├── Shared/
│   │   │   ├── Common/
│   │   │   └── Constants/
│   │   ├── Persistence/
│   │   │   └── DbContext/
│   │   │       ├── ReadDbContext.cs
│   │   │       ├── WriteDbContext.cs
│   │   │       └── BackgroundDbContext.cs
│   │   └── GlobalUsings.cs
│   └── YourProjectName.WebApi/              # Entry Point
│       ├── Program.cs
│       └── appsettings.json
└── YourProjectName.slnx
```

## ✨ Features
- ✅ Vertical Slice Architecture
- ✅ CQRS with MediatR
- ✅ FluentValidation (pipeline behaviour)
- ✅ Entity Framework Core (Read / Write / Background DbContexts)
- ✅ JWT Authentication
- ✅ Minimal API Endpoints
- ✅ Swagger / OpenAPI
- ✅ Global Exception Handling
- ✅ Serilog Logging
- ✅ Health Checks
- ✅ CORS Configuration

## 🔧 Upgrade Template
```bash
# Uninstall old version
dotnet new uninstall dotridu

# Install latest version
dotnet new install dotridu
```

## 🤝 Contributing
Pull requests are welcome!

## 👤 Author
**Hasibul Hasan**
- Portfolio: [abouthasibul.com](https://abouthasibul.com/)
- NuGet: [nuget.org/profiles/iamhasibulhasan](https://www.nuget.org/profiles/iamhasibulhasan)
- GitHub: [github.com/iamhasibulhasan](https://github.com/iamhasibulhasan)

## 📄 License
This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.