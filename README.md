# Student Management System (SMS)

## Overview
The **Student Management System (SMS)** is a web-based application developed using **C# and ASP.NET Core** to manage student information, including courses, grades, and enrollments.

## Technologies Used
- **Backend:** C#, ASP.NET Core, Entity Framework
- **Frontend:** (To be developed by frontend team)
- **Database:** SQL Server / PostgreSQL
- **API Documentation:** Swagger
- **Version Control:** Git & GitHub

## Project Setup
### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/StudentManagementSystem.git
cd StudentManagementSystem
```

### 2. Install Dependencies
Ensure you have **.NET SDK** installed. Run:
```sh
dotnet restore
```

### 3. Setup Database
Apply database migrations:
```sh
dotnet ef database update
```

### 4. Run the Application
```sh
dotnet run
```
Application will be available at: `https://localhost:5001`

## Collaboration Guide
### 1. Git Branching Strategy
- **`main`**: Stable version
- **`dev`**: Active development
- **Feature branches (`feature-xyz`)**: New features

### 2. Creating a Feature Branch
```sh
git checkout -b feature-api
# Make changes...
git add .
git commit -m "Added student API"
git push origin feature-api
```

### 3. Submitting a Pull Request
1. Push changes to GitHub
2. Open a **Pull Request (PR)** to `dev`
3. Request a review
4. Once approved, merge into `dev`

### 4. API Documentation
- **Swagger:** Available at `https://localhost:5001/swagger`
- **Postman Collection:** (To be provided by backend team)

### 5. Project Management
We use **GitHub Projects** / **Trello** for task tracking. Please check the board for assigned tasks.

## Contribution Guidelines
- Follow **Git Flow**
- Write **clear commit messages**
- Document API endpoints
- Update the **README** for any major changes

## Contact
For any questions, reach out to **@BackendLead** on Slack/WhatsApp.

---
**Happy coding! 🚀**

