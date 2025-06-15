# 🍽️ Dairy Restaurant Server – ASP.NET Core Backend

This project is a multi-layered C# server application for managing a dairy restaurant. It includes order processing, menu management, inventory control, and user handling – built using ASP.NET Core with clean architecture.

## 🧱 Project Structure

- **WebApp/** — Main web interface (ASP.NET or Razor Pages)
- **Bll/** — Business Logic Layer: handles all core logic and processing
- **Dal/** — Data Access Layer: communicates with the database
- **Dto/** — Data Transfer Objects: shared data models across layers
- **I_Bll/** & **I_Dall/** — Interfaces that abstract logic and database layers for better testing and flexibility

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-user/project-name.git
   ```

2. Open `PROJECT_C#.sln` in Visual Studio 2022 or later.

3. Restore NuGet packages:
   ```bash
   Tools > NuGet Package Manager > Manage NuGet Packages for Solution
   ```

4. Run the application (`F5` or `Ctrl + F5`).

## 🔍 Requirements

- .NET 6 or later
- Visual Studio 2022+
- SQL Server or supported database (optional)

## 🧪 Testing

Tests can be added in a separate test project targeting the `Bll` or `WebApp` layers, depending on the architecture.

## 📦 NuGet Packages (Typical examples)

- Microsoft.AspNetCore.*
- Microsoft.EntityFrameworkCore.*
- AutoMapper
- Swashbuckle (for Swagger API Docs)

## 📁 Solution Overview

This structure supports high testability, maintainability, and clear separation of responsibilities. Ideal for medium to large-scale systems.

---

> Created using Visual Studio 2022 – clean, layered, and scalable.
