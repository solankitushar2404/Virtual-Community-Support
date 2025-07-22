<h1 align="center">🌐 Virtual Community Support Platform</h1>
<h3 align="center">💻 TatvaSoft Summer Internship Project (2025) | Full Stack Development</h3>

<p align="center">
  <a href="https://dotnet.microsoft.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original.svg" alt=".NET" width="40"/></a>
  <a href="https://angular.io/" target="_blank"><img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="Angular" width="40"/></a>
  <a href="https://www.postgresql.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="40"/></a>
  <a href="https://swagger.io/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swagger/swagger-original.svg" alt="Swagger" width="40"/></a>
  <a href="https://aws.amazon.com/" target="_blank"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/amazonaws.svg" alt="AWS" width="40" height="40"/></a>
</p>

---
# 🌐 Virtual Community Support Platform

**💻 TatvaSoft Summer Internship Project (2025)**  
`Full Stack Web Application using .NET Core | Angular | PostgreSQL | AWS`

> **Empowering organizations to make a meaningful difference.**

---

## 📋 About the Project

The **Virtual Community Support Platform** is a **feature-rich, full-stack CSR management system** developed as part of the **TatvaSoft Summer Internship 2025**. It provides a platform for organizations to create and manage socially impactful missions, while employees can engage in volunteering opportunities that align with company goals and personal interests.

> Built with modern tech stack, secure authentication, role management, and cloud deployment support.

---

## 🎯 Use Case

This platform simplifies **Corporate Social Responsibility (CSR)** efforts for organizations by:

- 🏢 Allowing **admins** to manage users, missions, themes, and skills
- 👨‍💼 Enabling **employees** to browse, filter, apply, and contribute to missions
- 📈 Tracking community involvement with a clean and responsive UI

---

## 🚀 Key Features

| Category                  | Feature                                                                 |
|---------------------------|-------------------------------------------------------------------------|
| 🔐 Authentication          | Secure JWT-based login for Admin and Users                             |
| 👥 Role Management         | Admin/User access separation with proper authorization logic           |
| 🎯 Mission Control         | Create, Update, Delete missions with full filter & status options      |
| 🔎 Search & Filter         | Smart mission listing with sorting, filters, and real-time updates     |
| 🧠 Skills & Themes         | CRUD operations for mission themes and required skills                 |
| 🖼️ Profile & Media Uploads | User profile management with image upload                              |
| ☁️ Deployment Ready        | API & frontend built for deployment on AWS (EC2 + S3 support)          |

---

## 🛠️ Tech Stack

| Layer      | Technology                                      |
|------------|-------------------------------------------------|
| 🌐 Frontend | Angular 16, HTML5, CSS3, TypeScript              |
| 🧠 Backend  | .NET Core Web API, Entity Framework Core         |
| 💾 Database | PostgreSQL (Code First with Migrations)          |
| 📦 Dev Tools| Swagger, LINQ, Visual Studio, VS Code            |
| ☁️ Cloud    | AWS EC2 (backend), S3 (frontend) – optional      |

---

## 🧱 System Architecture

```
Client (Angular)   →   API (.NET Core)   →   PostgreSQL DB
        ↑                     ↓
  HTTPClient         EF Core + LINQ Queries
```

- RESTful APIs with clean route structuring
- Role-Based Access Control (RBAC)
- Image upload folder structure maintained
- PostgreSQL schema generated via Code First approach

---

## 🧑‍💻 Project Modules Overview

### 🔹 Admin Panel
- Manage Missions
- Manage Themes & Skills
- View All Applications
- Role-based secured access

### 🔹 User Portal
- View all missions
- Apply or withdraw from a mission
- Update profile with image
- View applied history

### 🔹 Mission System
- Mission has details: Title, Description, Start/End Dates, Required Skills
- Each mission linked to Skills & Themes
- Display filters (City, Skill, Category)

---

## 📂 Folder Structure

```
Backend/
└── Mission/
    ├── Mission.Api/
    │   ├── Controllers/
    │   ├── Services/
    │   ├── UploadMissionImage/
    │   └── Program.cs
    ├── Mission.Entities/
    ├── Mission.Repositories/
    └── Mission.Services/

Frontend/
└── src/
    ├── app/
    │   ├── components/
    │   ├── pages/
    │   └── services/
    ├── assets/
    └── environments/
```

---

## 🔧 Prerequisites

| Tool               | Purpose                         | Command/Link                      |
|--------------------|----------------------------------|-----------------------------------|
| .NET SDK           | Run backend API                 | [Download .NET](https://dotnet.microsoft.com/en-us/download) |
| Node.js & npm      | Run Angular frontend            | [Download Node.js](https://nodejs.org/) |
| Angular CLI        | Angular commands support        | `npm install -g @angular/cli`    |
| PostgreSQL         | Database                        | [PostgreSQL Download](https://www.postgresql.org/) |
| Git                | Clone & manage repo             | [Git](https://git-scm.com/)      |
| Visual Studio Code | Code editor                     | [VS Code](https://code.visualstudio.com/) |

---

## ▶️ How to Run the Project Locally

### 1️⃣ Run the Backend

```bash
cd Backend/Mission/Mission.Api
dotnet restore
dotnet run
```

Ensure PostgreSQL is running and update `appsettings.json` with your DB credentials.

---

### 2️⃣ Run the Frontend

```bash
cd Frontend
npm install
ng serve
```

Frontend will be available at: `http://localhost:4200`

---

## 📈 Deployment Strategy (Optional)

| Layer     | Service |
|-----------|---------|
| API       | AWS EC2 |
| Frontend  | AWS S3  |
| Database  | AWS RDS (optional) |

---

## 🎓 Internship Summary

- 🏫 **Organization**: TatvaSoft Pvt. Ltd.  
- 📅 **Program**: Summer Internship 2025  
- 🔧 **Duration**: 15 Days  
- 💼 **Role**: Full Stack Developer Intern  
- 💡 **Focus**: Practical implementation of secure, scalable CSR portal

---

## 🙋 About the Developer

**Tusharkumar Solanki**  
📍 Gujarat, India  
🧑‍💻 Passionate Full Stack Developer  
🚀 Strong grasp on Angular, .NET Core, and PostgreSQL  
🌱 Always building meaningful software for real-world use

---

## ⭐ Feedback & Contributions

If you like this project, please consider ⭐ starring the repo.  
For suggestions, feel free to open issues or create pull requests.

Let’s build communities — one mission at a time. 🌍


