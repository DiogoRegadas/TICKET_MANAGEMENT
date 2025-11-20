# Ticket Management System (ASP.NET MVC)

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Framework](https://img.shields.io/badge/framework-ASP.NET%20MVC-blue)
![Language](https://img.shields.io/badge/language-C%23-purple)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

A full-featured **Ticket Management System** built with **C#** and **ASP.NET MVC**, designed to simulate a real helpdesk or support workflow.  
The system includes a visual interface where users can create, update, assign, and manage support tickets through a clean and structured web UI.

This project demonstrates skills in **full-stack development**, **MVC architecture**, **C#**, **SQL databases**, and **software engineering best practices**.

---

## 🎯 Features

### 🎫 Ticket Management
- Create tickets with title, description, priority, and category  
- Assign tickets to specific agents  
- Update status (Open → In Progress → Resolved → Closed)  
- Track creation date and last update  

### 👥 User Interface (ASP.NET MVC Views)
- Full visual UI built with Razor Views  
- Organized layout with navigation and dynamic content  
- Forms with validation and error handling  

### 🗂️ Data Storage
- SQL database (SQL Server local DB or other configured provider)  

### 🔐 Additional Features (If included in your project)
- Login & authentication  
- User roles (Admin, Agent, User)  
- Filtering, sorting, or searching tickets  

---

## 🛠️ Technologies Used

- **C#**  
- **ASP.NET MVC**  
- **SQL Server / LocalDB**  
- **Razor Views**  
- HTML, CSS, JavaScript  
- Visual Studio (development environment)

---

## 🧠 How It Works

- Follows Model–View–Controller architecture
- Uses models for representing Tickets and Users
- Controllers handle all business logic (CRUD operations)
- Razor Views render the interface
- SQL database stores all ticket data

---

## 🔮 Future Improvements

- Dashboard with charts (open vs closed tickets, resolution times)
- Email notifications
- Ticket activity logs
- API version (REST endpoints) + React frontend
- Dark mode
- Attachments (upload files to tickets)

---

## 📦 Installation

1. Clone the repository and open the solution in **Visual Studio**.
2. Restore NuGet packages automatically when prompted.
3. Configure your database connection in the `appsettings.json` file.
4. Run the project using **IIS Express**.
