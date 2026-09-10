# DVLD (Driver and Vehicle Licensing Department) Management System

## 📌 Project Overview
A comprehensive full-scale Windows Forms desktop application developed using C#.NET, ADO.NET, and SQL Server. This project simulates a real-world governmental traffic and driving license management system, built following software engineering best practices, Object-Oriented Programming (OOP) principles, and a strict 3-Tier Architecture.

## 🛠️ Tech Stack
* Language: C# [.NET Framework / Windows Forms]
* Database: Microsoft SQL Server
* Data Access: ADO.NET
* Architecture: 3-Tier Architecture (Presentation Layer, Business Logic Layer - BLL, Data Access Layer - DAL)

## 🚀 Key Modules & Features
* People Management: Complete CRUD operations for managing person details, national numbers, and contact info.
* Users & Permissions: Secure user authentication, login mechanisms, and fine-grained permission/access control settings.
* Local & International Driving Licenses: Issuing, renewing, and tracking local and international licenses.
* Applications & Test Types: Managing application types, test appointments (Vision, Written, Street), and passing/failing results.
* License Replacements: Handling replacements for lost or damaged licenses, alongside detaining and releasing procedures.
* Robust Validation & Error Handling: Input validation rules, business logic enforcement, and exception handling across all modules.

## 👨‍💻 Author
Developed as part of the professional C# / .NET backend roadmap.

## ⚙️ How to Run the Project
1. Clone or download the repository.
2. Locate the database backup file inside the repository: **DB_Backup/DVLD.bak**
3. Open SQL Server Management Studio (SSMS) Restorere** the database using this .bak file.
4. Open the solution (.sln) using Visual Studio.
5. Navigate to the DataAccess layer and update the connection string inside the **DataAccessSettings.cs** class to match your local SQL Server instance.
6. Build and run the application!
