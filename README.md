# 🏥 Hospital Management System

A comprehensive **Hospital Management System** built with **Python** and **MySQL**.  
This project streamlines hospital operations such as patient registration, doctor management, appointment scheduling, billing, and medical record handling.

---

## 📌 Features
- **Patient Management**: Register, update, and track patient details.
- **Doctor Management**: Add doctors, assign patients, and manage schedules.
- **Appointments**: Book, reschedule, and cancel appointments.
- **Billing System**: Generate invoices and track payments.
- **Medical Records**: Store and retrieve patient history securely.
- **Authentication**: Secure login for administrators and staff.

---

## 🛠️ Tech Stack
- **Language**: Python
- **Database**: MySQL
- **Libraries**:
  - Tkinter (GUI interface)
  - PyMySQL / mysql-connector-python (database connectivity)
  - SQLAlchemy (optional ORM layer)

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x installed
- MySQL server installed and running
- Git (for cloning the repository)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yashu1402/Hospital-Management-System.git
   cd Hospital-Management-System

---

### Install dependencies:
- pip install -r requirements.txt

---

### Configure database:
-- Create a new MySQL database (e.g., hospital_db).
-- Update config.py with your MySQL credentials (host, user, password, database).
-- Run the provided SQL script to set up tables.

### Run the application:
-- python main.py

### 📂 Project Structure
Hospital-Management-System/

│── main.py               # Entry point

│── config.py             # Database configuration

│── models/               # Database models

│── views/                # GUI components

│── controllers/          # Business logic

│── requirements.txt      # Dependencies

│── README.md             # Documentation
