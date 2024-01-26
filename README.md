# Habit Tracker ToDo App with Blazor

This is a simple ToDo application built using Blazor Server, SQL Server Express, and Entity Framework. It allows users to create, view, update, and delete tasks in a ToDo list.

## Prerequisites

- [.NET 6.0 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
- [SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone <repository_url>

2. Open the appsettings.json file in the ToDoApp project and update the connection string to point to your SQL Server Express instance:

   ```bash
   "ConnectionStrings": {
    "DefaultConnection": "Server=<ServerName>;Database=ToDoAppDb;Trusted_Connection=True;"
    }

3. Build the solution and apply database migrations to create the database.


