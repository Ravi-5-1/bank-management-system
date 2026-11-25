# 🏦 Bank Management System

A desktop-based **Bank Management System** developed in **Java** using **Java Swing** and **MySQL**. The application provides a simple and intuitive interface for managing customer accounts and performing day-to-day banking operations such as deposits, withdrawals, balance inquiries, and account management.

Designed with Object-Oriented Programming principles, this project demonstrates Java GUI development, database connectivity using JDBC, and CRUD operations.

---

## ✨ Features

- 👤 Customer account creation
- 🔐 Secure login authentication
- 💰 Deposit money
- 💸 Withdraw money
- 📊 Balance enquiry
- 📝 Account details management
- 🔄 Update customer information
- ❌ Delete/Close account
- 🗄️ MySQL database integration
- 🖥️ Interactive Java Swing GUI

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Language | Java |
| GUI | Java Swing |
| Database | MySQL |
| Connectivity | JDBC |
| IDE | NetBeans / IntelliJ IDEA / Eclipse |

---

## 📂 Project Structure

```
bank_management_system/
│
├── src/
│   ├── bank/                # Java source files
│   ├── model/
│   ├── database/
│   └── ui/
│
├── database/
│   └── bank.sql
│
├── screenshots/
├── README.md
└── ...
```

---

## 🚀 Functionalities

- Create a new bank account
- Authenticate users
- Deposit and withdraw funds
- View customer profile
- Check account balance
- Update account information
- Delete existing accounts
- Store and retrieve records from MySQL

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Ravi-5-1/bank-management-system.git

cd bank-management-system
```

### 2. Create the database

- Open **MySQL**
- Create a new database

```sql
CREATE DATABASE bank_management_system;
```

- Import the provided SQL file (if available).

### 3. Configure the database connection

Update your database credentials in the JDBC configuration file.

```java
String url = "jdbc:mysql://localhost:3306/bank_management_system";
String username = "root";
String password = "your_password";
```

### 4. Run the project

Open the project in your preferred Java IDE and run the main application.

---

## 📸 Screenshots

Add screenshots here to showcase the application.

Example:

```
screenshots/
├── login.png
├── dashboard.png
├── create-account.png
└── transactions.png
```

---

## 🧠 Concepts Demonstrated

- Object-Oriented Programming (OOP)
- Java Swing GUI Development
- JDBC Database Connectivity
- CRUD Operations
- Event Handling
- Exception Handling
- SQL Queries
- Database Design

---

## 📈 Future Improvements

- Transaction history
- Money transfer between accounts
- Admin dashboard
- Password encryption
- Email & SMS notifications
- Loan management module
- Internet banking features
- Role-based authentication

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add feature"
```

4. Push to the branch

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**.


