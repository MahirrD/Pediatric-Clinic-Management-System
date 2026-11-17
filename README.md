<div align="center">

# 🏥 Pediatrics Clinic Hospital Management System

**A console-based Hospital Management System built in C featuring role-based portals, appointment scheduling, and file-based data persistence.**

![Language](https://img.shields.io/badge/Language-C-blue?style=for-the-badge&logo=c)
![Storage](https://img.shields.io/badge/Storage-CSV%20%26%20TXT-success?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Console-lightgrey?style=for-the-badge)

</div>

---

## 📖 Overview

The **Pediatrics Clinic Hospital Management System (HMS)** streamlines daily clinic operations across four dedicated portals. Designed around structured file handling in C, it manages staff rosters, patient records, doctor availability, appointment workflows, and automated billing.

---

## ✨ Features

### 🛡️ Staff Management Portal (Admin)
* **Authentication:** Protected admin access with credential verification.
* **Full CRUD Operations:** View, add, search, edit, and delete staff records seamlessly.
* **Auto-Incrementing IDs:** Automatically generates sequential IDs for newly registered staff members.

### 🩺 Staff Portal
* **Staff Login:** ID and password authentication for doctors and clinic personnel.
* **Profile Viewer:** Displays specialization, contact details, and assigned schedule.

### 👶 Patient Portal
* **Account Management:** Self-service patient registration and secure login.
* **Appointment Scheduling:** Browse available doctors, book new slots, search bookings by doctor name, reschedule, or cancel appointments.
* **Medical & Billing Access:** View personal health profiles, ward/bed assignments, active prescriptions, and itemized bills.

### 💳 Billing & Payment Portal
* **Automated Bill Calculation:** Consolidates consultation fees, bed charges, and medication costs by Patient ID.
* **Payment Processing:** Supports Cash and Credit Card transactions, updating bill statuses from *Pending* to *Paid* with instant receipt generation.
* **Transaction Logs:** Tracks and displays complete payment history for settled accounts.

---

## 🚀 Getting Started

1. **Download the Project:** Clone or download all project files into a single folder.
2. **Keep Data Files Together:** Ensure all `.txt` and `.csv` data files remain in the exact same directory as `cse115 project_final version.c`.
3. **Compile & Run:** Open `cse115 project_final version.c` in your preferred C IDE (Code::Blocks, VS Code, or Dev-C++), build, and execute.

---

## 🔐 Default Login Credentials

| Portal | Username / ID | Password |
| :--- | :--- | :--- |
| **Staff Management (Admin)** | `admin` | `1234` |
| **Billing Portal** | `billing` | `1111` |
| **Staff Portal** | `001` *(or any valid staff ID)* | `S` *(matches staff profile)* |
| **Patient Portal** | `001` *(or register a new account)* | `1234` |

---

## 👥 Contributors

| Name | Role & Module |
| :--- | :--- |
| **Mahir Daiyan** | Staff Management Portal & Staff Portal |
| **Sawom** | Patient Portal & Appointment System |
| **Zahra** | Billing & Payment Portal |
