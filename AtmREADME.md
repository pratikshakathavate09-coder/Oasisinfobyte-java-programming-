
# 🏧 ATM Interface System (Java)

![Java](https://img.shields.io/badge/Language-Java-red)
![License](https://img.shields.io/badge/License-MIT-blue)

## 📌 Overview

The **ATM Interface System** is a **console-based Java application** that simulates the basic operations of an Automated Teller Machine (ATM).

This project allows a user to:

* Register a bank account
* Log in using username and password
* Perform banking operations such as deposit, withdrawal, fund transfer, balance enquiry, and viewing transaction history

The project is developed using **Core Java** and focuses on applying **Object-Oriented Programming (OOP)** concepts in a menu-driven environment.

This is an **educational project**, intended for learning and practice purposes.

---

## ✨ Features

* **User Registration**
  Create a new bank account with username and password.

* **User Authentication**
  Login system using registered credentials.

* **Deposit Money**
  Add funds to the account (with defined limits).

* **Withdraw Money**
  Withdraw amount if sufficient balance is available.

* **Fund Transfer**
  Transfer money within allowed transaction limits.

* **Balance Enquiry**
  View current account balance instantly.

* **Transaction History**
  Displays all performed transactions in the session.

* **Menu-Driven Interface**
  Easy-to-use console menu for navigation.

---

## 🧱 Project Structure

```
JavaProject/
├── ATMInterface.java     # Main class (application entry point)
├── BankAccount.java      # Bank account logic
└── README.md             # Project documentation
```

> ⚠️ **Note:**
> The folder name must match the package name:
>
> ```java
> package JavaProject;
> ```

---

## ⚙️ Prerequisites

* Java Development Kit (JDK) 8 or higher
* Any Java-supported IDE:

  * VS Code
  * Eclipse
  * IntelliJ IDEA

---

## ▶️ How to Run the Project (VS Code)

### Step 1: Open Project Folder

Open the parent folder containing `JavaProject` in VS Code.

### Step 2: Verify Package Name

Ensure both Java files start with:

```java
package JavaProject;
```

### Step 3: Compile the Program

```bash
javac JavaProject/ATMInterface.java
```

### Step 4: Run the Program

```bash
java JavaProject.ATMInterface
```

---

## 💰 Default Values & Limits

| Parameter         | Value                   |
| ----------------- | ----------------------- |
| Initial Balance   | ₹10,000                 |
| Deposit Limit     | ₹10,000 per transaction |
| Transfer Limit    | ₹50,000 per transaction |
| User Session Type | Single user             |

---

## 📋 Sample Output

```
******************** WELCOME TO GOVARDHAN ATM INTERFACE ********************

1. Register
2. Exit

Choose one option: 1

Enter your Name:
Rahul

Enter your Username:
rahul123

Enter your Password:
pass123

Registration Successful.
Please log in to your bank account.
```

---

## 🧠 Concepts Used

* Object-Oriented Programming (OOP)
* Classes and Objects
* Methods and Encapsulation
* Conditional Statements
* Loops and Switch Case
* User Input Handling (Scanner)
* String Manipulation

---

## 🚀 Future Enhancements

* Password encryption and validation
* Multiple user account support
* File or database storage
* PIN-based authentication
* Improved error handling
* GUI version using Java Swing or JavaFX

---

## 📄 License

This project is licensed under the **MIT License**.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

## 👤 Author

* GitHub: **@pratikshask09**

---

## ⭐ Support

If this project helped you understand Java and OOP concepts, feel free to give it a ⭐ on GitHub.

---

**Last Updated:** January 29, 2026

 

Say what you want next — clearly.
