# HireNest

HireNest is a modern hiring platform designed to connect employers with qualified talent and help job seekers discover relevant opportunities faster.

## Project overview
This project is built as a full-stack ASP.NET Core MVC application for managing job listings, employer profiles, categories, and vendor onboarding. It includes a secure admin flow, role-based access, and a public-facing job portal experience.

## Key features
- Job listing management for vendors and admins
- Category-based job organization
- Employer and vendor profile management
- Upload support for company images and logos
- Role-based access with ASP.NET Identity
- Soft delete tracking for safer record management
- Dashboard summary for operational visibility

## Tech stack
- ASP.NET Core MVC
- Entity Framework Core
- SQL Server
- ASP.NET Core Identity
- Bootstrap-based frontend

## Project structure
- `Elevate Workforce solution` - main web application
- `Elevate Workforce SolutionAPI` - API scaffold
- `Elevate workforce.sln` - solution file

## Default admin credentials
The application seeds a default SuperAdmin account during setup:
- Email: bipindhakal05@gmail.com
- Password: Bipin@123

## Getting started
1. Open the solution in Visual Studio.
2. Restore NuGet packages.
3. Update the SQL Server connection string in `appsettings.json` if needed.
4. Run database migrations or initialize the database.
5. Start the application and log in using the default admin account.

## Purpose
The platform was designed to showcase a professional recruitment workflow in a simple, custom-built MVC system with an emphasis on usability, role separation, and hiring operations.
