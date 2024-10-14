## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Database Connection](#database-connection)

# Authentication System

This project is an authentication system built using ASP.NET, designed to provide secure user registration, login, and session management functionalities. It aims to demonstrate best practices in implementing authentication and authorization features in web applications.

## Features

- **User Registration**: New users can create an account with email and password.
- **User Login**: Registered users can log in to the system.
- **Password Hashing**: User passwords are securely hashed using industry-standard algorithms.
- **Session Management**: Manage user sessions efficiently.
- **Role-Based Access Control**: Different user roles can be defined to restrict access to certain functionalities.
- **Email Confirmation**: Users must confirm their email addresses to activate their accounts.

## Technologies Used

- **ASP.NET Core**: A cross-platform framework for building web applications.
- **Entity Framework Core**: ORM for database interactions.
- **SQL Server**: Database for storing user information.
- **Identity Framework**: For managing user identities and authentication.
- **JWT (JSON Web Tokens)**: For stateless authentication.
- **Bootstrap**: For responsive front-end design.

## Getting Started

To set up the project locally, follow these steps:

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (version 6.0 or later)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) (or SQL Server Express)
- A code editor such as [Visual Studio](https://visualstudio.microsoft.com/) or [Visual Studio Code](https://code.visualstudio.com/)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Kunalmishra123/AuthenticationSystem.git

## Database Connection
1. **Create a appsettings.json file in the root directory (if it doesn't already exist).
     Add your database connection string:**
   ```bash
   "ConnectionStrings": {
    "DefaultConnection": "Server=YOUR_SERVER;Database=BankTransactions;Trusted_Connection=True;TrustServerCertificate=True;"
   },
