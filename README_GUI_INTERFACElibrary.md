# 📚 Library Management System

A modern desktop-based Library Management System developed using **Python, Tkinter, and SQLite**. The application provides an intuitive graphical interface for managing books, members, book issuance, returns, and transaction history.

##  Features

###  Dashboard

* Overview of total books
* Available books count
* Registered members count
* Active issued books
* Overdue books tracking
* Recent issue activity table

###  Book Management

* Add new books
* Edit existing book details
* Delete books
* Search books by title, author, or genre
* Track total and available copies

###  Member Management

* Add new members
* Edit member information
* Delete members
* Search members
* View active issues per member

###  Issue & Return System

* Issue books to registered members
* Automatic due date generation
* Return books with one click
* Real-time availability updates

###  Transaction History

* Complete issue and return records
* Filter by:

  * All Records
  * Active Issues
  * Returned Books
  * Overdue Books

###  Database Support

* SQLite database integration
* Automatic database creation
* Persistent data storage
* Sample books and members preloaded on first run

---

##  Technologies Used

* Python 3
* Tkinter
* SQLite3
* ttk Widgets
* Object-Oriented Programming (OOP)

---

## Project Structure

```text
Library-Management-System/
│
├── main.py
├── library.db
├── README.md
│
└── assets/
    └── screenshots/
```

---

##  Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/library-management-system.git
cd library-management-system
```

### Run the Application

```bash
python main.py
```

---

## 🗄️ Database Schema

### Books Table

| Column    | Description      |
| --------- | ---------------- |
| id        | Book ID          |
| title     | Book title       |
| author    | Author name      |
| isbn      | ISBN number      |
| genre     | Book genre       |
| year      | Publication year |
| copies    | Total copies     |
| available | Available copies |

### Members Table

| Column | Description       |
| ------ | ----------------- |
| id     | Member ID         |
| name   | Member name       |
| email  | Email address     |
| phone  | Contact number    |
| joined | Registration date |

### Issues Table

| Column      | Description        |
| ----------- | ------------------ |
| id          | Issue ID           |
| book_id     | Book reference     |
| member_id   | Member reference   |
| issue_date  | Date issued        |
| due_date    | Return deadline    |
| return_date | Actual return date |

---

##  User Interface Highlights

* Dark-themed modern interface
* Sidebar navigation
* Interactive tables using Treeview
* Search functionality
* Hover effects on buttons
* Dashboard analytics cards
* Responsive layout

---

##  Screenshots

Add screenshots of:

1. Dashboard
2. Books Management
3. Members Management
4. Issue/Return Section
5. History Page

Example:

```text
screenshots/
├── dashboard.png
├── books.png
├── members.png
├── issue_return.png
└── history.png
```

---

##  Future Enhancements

* User authentication system
* Fine calculation for overdue books
* Barcode scanner integration
* Export reports to PDF/Excel
* Book reservation system
* Email reminders for due dates
* Multi-user support

---

##  Learning Objectives

This project demonstrates:

* GUI Development with Tkinter
* Database Management using SQLite
* CRUD Operations
* Object-Oriented Programming
* Event-Driven Programming
* Data Persistence
* Desktop Application Development

---

## Author
ARAGYA


