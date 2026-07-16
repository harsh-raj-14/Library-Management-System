# 📚 Library Management System

A console-based **Library Management System** developed in **C** that enables efficient management of books, users, and book rentals using file handling. The application provides secure login authentication and supports complete CRUD operations for library records.

---

## 🚀 Features

### 🔐 Authentication
- Password-protected login system
- Three failed login attempts terminate the program

### 👤 User Management
- Add new users
- Modify user details
- Search users
- Delete users
- Display all registered users

### 📖 Book Management
- Add new books
- Modify book information
- Search books
- Delete books
- Display available books

### 📚 Book Rental
- Issue books to registered users
- Maintain rental records
- Track available book quantity
- Prevent issuing out-of-stock books

### 💾 File Handling
- Persistent storage using text files
- Automatic record updates
- Temporary file handling for safe modifications

---

## 🛠️ Technologies Used

- C Programming
- File Handling
- Structures and Functions
- String Manipulation
- Console Application
- Windows API (`windows.h`)
- Standard C Libraries

---


---

## 📋 Functionalities

### User Panel

- Add User
- Modify User
- Search User
- Delete User
- List All Users
- View Rental Records

### Book Panel

- Add Book
- Modify Book
- Search Book
- Delete Book
- List Books
- Rent Book

---

## 📁 Data Storage

The application stores records in plain text files:

| File | Description |
|------|-------------|
| user_Records.txt | Stores registered user information |
| book_Records.txt | Stores book details |
| rent_Records.txt | Stores issued book records |
| temporary.txt | Temporary file used while updating records |

---

## 🔑 Default Login Credentials

```
Password: harsh
```

---

## ▶️ How to Run

### Using GCC

```bash
gcc main.c -o library.exe
library.exe
```

### Using CodeBlocks / Dev-C++

1. Open the project.
2. Compile the source code.
3. Run the executable.

---


## 🔍 Future Improvements

- Return Book functionality with due dates
- Fine calculation
- Admin and Student roles
- Binary Search Tree for faster searching
- Database integration (MySQL/PostgreSQL)
- GUI using Qt or GTK
- Barcode Scanner Support
- Smart Pointer implementation (C++)
- Inventory Analytics Dashboard

---

## 📚 Concepts Used

- File Handling
- Modular Programming
- Functions
- Arrays
- String Handling
- CRUD Operations
- Console Programming
- Authentication
- Record Management

---

## 👨‍💻 Author

**Harsh Raj**


---

## ⭐ If you found this project useful, consider giving it a star!
