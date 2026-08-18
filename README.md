# 🚗 Car Showroom Management System

A web-based **Car Showroom Management System (CSMS)** developed to simplify and automate showroom operations such as car inventory management, company management, customer enquiries, and administrative activities.

The system provides separate **User and Admin modules**, allowing customers to browse available cars and submit enquiries while administrators manage cars, companies, users, and customer requests through a centralized dashboard.

---

## 📌 Project Overview

The Car Showroom Management System replaces traditional manual showroom management with a centralized web application.

Users can explore available vehicles, view car details, check company information, and submit enquiries.

Administrators can manage vehicle records, car companies, customer enquiries, website content, and administrative accounts.

---

## 🎯 Objectives

- Automate car showroom management.
- Reduce manual record maintenance.
- Manage vehicle information efficiently.
- Provide easy access to car details.
- Manage customer enquiries.
- Reduce data-entry errors.
- Centralize showroom information.
- Improve customer and administrator experience.

---

## ✨ Features

### 👤 User Module

Users can:

- View the homepage.
- Browse available cars.
- View detailed car information.
- Browse car companies.
- View company information.
- View About Us and Contact Us pages.
- Submit car enquiries.
- Track enquiry status.

### 👨‍💼 Admin Module

Administrators can:

- Login securely.
- Access the admin dashboard.
- Add car companies.
- Update company information.
- Delete/manage companies.
- Add car details.
- Update car information.
- Manage vehicle records.
- View customer enquiries.
- Search enquiries.
- Answer customer enquiries.
- Manage About Us and Contact Us content.
- Manage administrator profile.
- Change password.
- Recover account password.

---

## 🛠️ Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript

### Backend

- PHP

### Database

- MySQL

### Server

- Apache

### Development Environment

- XAMPP
- phpMyAdmin

---

## 🗄️ Database

The system uses a MySQL relational database.

### Main Tables

| Table | Purpose |
|---|---|
| `tbladmin` | Administrator information |
| `tblcompany` | Car company information |
| `tblcars` | Car and vehicle details |
| `tblenquiry` | Customer enquiries |
| `tblpages` | Website page information |

---

## 🔄 System Workflow

```text
                    CAR SHOWROOM SYSTEM
                            │
              ┌─────────────┴─────────────┐
              │                           │
            USER                        ADMIN
              │                           │
              ↓                           ↓
       Browse Cars                 Admin Login
              │                           │
              ↓                           ↓
       View Car Details              Dashboard
              │                           │
              ↓                    ┌──────┴──────┐
       Submit Enquiry               ↓             ↓
              │                 Manage Cars   Manage Users
              ↓                       │             │
       Track Enquiry                  ↓             ↓
                                  Manage Companies
                                        │
                                        ↓
                                  Manage Enquiries
