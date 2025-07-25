# Ivy League Microfinance System

This is a SQL Server and C#-based microfinance system that manages client loans, employees, reports, and transactions for Ivy League Microfinance. Built with Visual Studio 2022, it features a user-friendly GUI and robust database design.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Database Schema](#database-schema)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributors](#contributors)
- [License](#license)

---

## Project Overview

This system enables users to:
- Add, update, and delete client records.
- Manage loan applications and statuses.
- Generate administrative reports.
- Maintain employee records.
- Provide a graphical user interface for ease of use.

---

## Features

- **Client Management** (Insert, Update, Delete)
- **Loan Management** with Status Tracking
- **Employee Data Management**
- **Report Generation**
- **SQL Secure Queries (Parameterized)**
- **User Interface using C# and WinForms**

---

## Database Schema (Tables)

- **Clients**: ClientID, FirstName, LastName, Email
- **Loans**: LoanID, Status, Amount, Client_ID
- **Employee**: Employee_ID, First_Name, Last_Name, Date
- **Admin**: adminID, admin_Name, admin_Surname, EmployeeID
- **Reports**: reportID, adminID, locationID, itemID

---

## Installation Instructions

### Prerequisites:
- Windows 10 or higher
- Visual Studio 2022
- SQL Server
