# 📚 Library Management System

A PHP & MySQL-based web application for managing library operations such as book management, member registrations, issue/return handling, and more.  

---

## 🚀 Features
- **User Authentication**: Secure login/logout for librarians and members.
- **Librarian Panel**:
  - Add, update, and delete books.
  - Manage book requests and registrations.
  - Track due dates and balances.
- **Member Panel**:
  - View available books.
  - Request and borrow books.
  - Manage profile and membership.
- **Database Integration**:
  - MySQL database with pre-designed schema (`librarygh.sql`).
  - Handles book records, member details, and transactions.

---

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS
- **Backend**: PHP
- **Database**: MySQL
- **Version Control**: Git & GitHub

---

## 📂 Project Structure
Libraryms-PHP/
│── index.php
│── db_connect.php
│── header.php
│── logout.php
│── message_display.php
│── verify_logged_out.php
│
├── css/ # Stylesheets
├── DATABASE FILE/ # SQL schema (librarygh.sql)
├── img/ # Images/icons
├── librarian/ # Librarian dashboard & features
└── member/ # Member dashboard & features


---

## ⚙️ Installation & Setup
- **1. Clone this repository:
   ```bash
   git clone https://github.com/keshavreddy04/LibraryManagementSystem.git
  Move project files into your server directory (e.g., htdocs for XAMPP).

- **2. Import database:

  Open phpMyAdmin.

  Create a new database (e.g., libraryms).

  Import DATABASE FILE/librarygh.sql.

3. Update db_connect.php with your database credentials.

4. Start Apache & MySQL in XAMPP/WAMP.

5.Open in browser: http://localhost/Libraryms-PHP/

---

## 🔑 Default Login

Check 01 LOGIN DETAILS & PROJECT INFO.txt for sample usernames and passwords.

---

## 📜 License

This project is open-source and available under the MIT License.

