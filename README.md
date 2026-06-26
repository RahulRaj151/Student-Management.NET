# Student Management System with .NET and React

This project is a full-stack Student Management System built with .NET 9 for the backend and React 19 for the frontend. It allows users to manage student records with a simple and modern interface.

## Features

- Add new students
- View a list of all students
- Update existing student details
- Delete student records
- Clean and responsive UI for easy management

## Tech Stack

- Backend: .NET 9 Web API
- ORM: Entity Framework Core
- Database: SQLite
- Frontend: React 19
- Routing: React Router
- Forms and validation: React Hook Form
- Notifications: React Hot Toast

## Project Structure

- Backend: ASP.NET Core API with EF Core and SQLite
- Frontend: Vite + React application for the user interface

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/RahulRaj151/Student-Management.NET.git
cd Student-Management.NET
```

### 2. Run the backend

```bash
cd Backend/Backend
 dotnet ef database update
 dotnet run
```

Keep the backend running, then open a new terminal window.

### 3. Run the frontend

```bash
cd ../../client
npm install
npm run dev
```

Open your browser and visit:

```text
http://localhost:5173
```

## Notes

If you encounter an npm dependency issue on Linux, you may need to remove the installed modules and lockfile and reinstall them:

```bash
rm -rf node_modules package-lock.json
npm install
```
