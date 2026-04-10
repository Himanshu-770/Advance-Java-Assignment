# Menu Driven JDBC CRUD Application

## 📌 Project Overview

This project is a **Java-based console application** that demonstrates how to perform basic **CRUD (Create, Read, Update, Delete) operations** on a MySQL database using **JDBC (Java Database Connectivity)**.
The program provides a **menu-driven interface** that allows users to insert, update, retrieve, and delete records from a **student table** in the database.

This project helps understand how Java applications interact with relational databases and how database operations can be managed programmatically.

---

## ⚙️ Technologies Used

* **Java**
* **JDBC (Java Database Connectivity)**
* **MySQL Database**
* **PreparedStatement**
* **ResultSet**
* **Scanner Class (for user input)**

---

## 🗄️ Database Structure

**Database Name:** `college`
**Table Name:** `student`

Example table structure:

```sql
CREATE TABLE student (
    id INT PRIMARY KEY,
    name VARCHAR(50)
);
```

---

## 🚀 Features

* Insert a new student record
* Update an existing student record
* Retrieve and display all student records
* Delete a student record
* Menu-driven interface for repeated operations
* Uses **PreparedStatement** to prevent SQL injection

---

## 📋 Menu Options

```
1 -> INSERT
2 -> UPDATE
3 -> RETRIEVE
4 -> DELETE
5 -> EXIT
```

---

## 🔄 Program Workflow

1. Load the MySQL JDBC driver.
2. Establish a connection with the MySQL database.
3. Display a menu with CRUD operations.
4. Accept user input using the Scanner class.
5. Execute SQL queries using PreparedStatement.
6. Display results using ResultSet.
7. Continue until the user selects the exit option.

---

## ▶️ How to Run the Program

1. Install **Java (JDK)**.
2. Install **MySQL Server**.
3. Add **MySQL Connector/J (JDBC driver)** to your project.
4. Create the database and table in MySQL.
5. Update database credentials in the Java program if needed.
6. Compile and run the program.

Example:

```bash
javac Practice.java
java Practice
```

---

## 📷 Sample Output

```
Connected to MySQL!

===== MENU =====
1 -> INSERT
2 -> UPDATE
3 -> RETRIEVE
4 -> DELETE
5 -> EXIT
Enter choice: 1

Enter id: 101
Enter name: Himanshu

Student inserted successfully
```

---

## 🎯 Learning Objectives

* Understand JDBC architecture
* Learn how to connect Java with MySQL
* Perform CRUD operations using SQL
* Use PreparedStatement and ResultSet
* Implement menu-driven console applications

---

## 👨‍💻 Author

**Himanshu Srivastava**
