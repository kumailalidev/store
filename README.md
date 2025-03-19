# ECommerce Store: ASP.NET Core REST API with Blazor WebAssembly Client

## Overview
This is a **full-stack E-Commerce Web Application** built with **ASP.NET Core RESTful Web API** as the backend and **Blazor WebAssembly** as the frontend. It follows the **N-Tier Clean Architecture** approach, providing secure authentication, role-based authorization, and a seamless shopping experience.

## Features
- **RESTful API**: Endpoints for authentication, products, categories, cart, and payments.
- **Admin Role**: Manage products and categories (CRUD operations).
- **User Role**: Browse products, add items to the cart, and make payments.
- **JWT Authentication**: Secure authentication with token refresh capability.
- **Role-Based Authorization**: Access control for admin and users.
- **Payment Integration**: Implements a **Stripe** payment method.
- **SQL Server Database**: Efficient data storage and retrieval.
- **Blazor WebAssembly**: Modern, interactive, and dynamic frontend UI.

## Installation Instructions

### **Prerequisites**
Ensure you have the following installed:
- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- [Visual Studio Code](https://code.visualstudio.com/)
- [EF Core CLI](https://docs.microsoft.com/en-us/ef/core/cli/dotnet)

### **Setup Steps**

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/kumailalidev/store.git
   cd store
   ```

2. **Apply the Database Migrations:**
- Run the following command to apply the database migrations
    ```sh
    dotnet ef database update --project src/Server
    ```

3. **Run the Project:**
- Run the following command to run ASP.NET Core hosted Blazor WebAssembly project.
    ```sh
    dotnet run --project src/Server
    ```