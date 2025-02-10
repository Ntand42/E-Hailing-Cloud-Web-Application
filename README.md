█▓▒▒░░░E-Hailing Cloud Webb Application░░▒▒▓█

A .NET-based application designed for managing student projects and registrations.

Features
-User registration and authentication
-Data management with Student, Project, and Register classes
-Database connectivity using Connections.cs
-Secure and scalable architecture
-Simple and intuitive UI

Requirements
-NET 7.0 or later
-Visual Studio
-SQL Server (for database support)

Installation
1.Clone the repository:
git clone <repository-url>

2.Open the solution in Visual Studio

3.Restore dependencies:
dotnet restore

4.Build and run the project:
dotnet run

5.Set up the database:
Update the connection string in Connections.cs
Run the necessary migrations

File Structure
prog6212-poe-ST10208122-main/
├── Connections.cs  # Handles database connections
├── Poelast3.csproj # Project file
├── Project.cs      # Project-related logic
├── Register.cs     # Handles user registration
├── Student.cs      # Student-related operations
├── bin/            # Compiled binaries
├── obj/            # Build artifacts
├── README.md       # Project documentation

