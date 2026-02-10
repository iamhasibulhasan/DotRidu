# DotRidu - Clean Architecture Template

[![.NET](https://img.shields.io/badge/.NET-8.0-purple)](https://dotnet.microsoft.com/)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

A production-ready ASP.NET Core Clean Architecture template with JWT authentication, Repository Pattern, and Entity Framework Core.

## 🚀 Quick Start

### Install Template
```bash
# Install from GitHub
dotnet new install https://github.com/iamhasibulhasan/DotRidu
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

## 📁 Project Structure
```
YourProject/
├── API/                    # Presentation Layer
├── Application/       # Business Logic Layer
├── Domain/             # Domain Layer (Entities, Interfaces)
└── Infrastructure/    # Infrastructure Layer (Data Access)
```

## ✨ Features
- ✅ Clean Architecture
- ✅ JWT Authentication
- ✅ Repository Pattern + Unit of Work
- ✅ Entity Framework Core
- ✅ Swagger/OpenAPI
- ✅ Global Exception Handling
- ✅ Serilog Logging
- ✅ Health Checks
- ✅ CORS Configuration

## 🔧 Advanced Usage

### Install Specific Version
```bash
# Install from specific branch/tag
dotnet new install https://github.com/iamhasibulhasan/DotRidu#main
```

### Uninstall Template
```bash
dotnet new uninstall https://github.com/iamhasibulhasan/DotRidu
```

## 📚 Documentation
- [Getting Started Guide](docs/getting-started.md)
- [Architecture Overview](docs/architecture.md)
- [API Documentation](docs/api.md)

## 🤝 Contributing
Pull requests are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.