# Library Management System – README

## 📚 Project Title

**Library Management System using C**

## 📖 Description

This project is a simple **Library Management System** developed in the **C programming language**.
It helps in managing library operations such as adding books, searching books, issuing books, returning books, and viewing issued books records.

The project uses **file handling** to store and manage data permanently.

---

## ✨ Features

* Add new books
* Display all books
* Search books by Book ID
* Issue books to students
* Return books
* Calculate fine for late return
* View issued books records
* Prevent duplicate book IDs
* Prevent issuing the same book twice to the same student

---

## 🛠️ Technologies Used

* C Programming
* File Handling
* Structures
* Functions
* Binary Files

---

## 📂 Files Used

| File Name       | Purpose                                   |
| --------------- | ----------------------------------------- |
| `hardik.cpp`    | Main source code                          |
| `books.dat`     | Stores book records                       |
| `issue.dat`     | Stores issued book records                |
| `temp.dat`      | Temporary file for updating books         |
| `tempissue.dat` | Temporary file for updating issue records |

---

## 📌 Functions Included

### 1. Add Book

Adds a new book to the library database.

### 2. Display Books

Displays all available books.

### 3. Search Book

Searches for a book using Book ID.

### 4. Issue Book

Issues a book to a student if available.

### 5. Return Book

Returns the issued book and calculates fine if delayed.

### 6. View Issued Books

Shows all currently issued books.

---

## 💰 Fine Calculation

* No fine for first **7 days**
* After 7 days:

  Fine = ₹5 per extra day

---

## ▶️ How to Run

### Step 1: Compile the Program

```bash
gcc hardik.cpp -o library
```

### Step 2: Run the Program

```bash
./library
```

---

## 🖥️ Sample Menu

```text
====== LIBRARY MANAGEMENT SYSTEM ======
1. Add Book
2. Display Books
3. Search Book
4. Issue Book
5. Return Book
6. View Issued Books
7. Exit
```

---

## 📚 Concepts Used

* Structures in C
* File Handling
* Functions
* Loops
* Conditional Statements
* Binary File Operations

---

## 🚀 Future Improvements

* Add login system
* Add book deletion feature
* Add update/edit book feature
* GUI based interface
* Store issue dates automatically
* Use database integration

---

## 👨‍💻 Author

Developed as a mini project for learning **C Programming and File Handling**.
