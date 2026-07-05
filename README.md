# 📚 Library Management System (C++)

## 📌 Project Overview

The **Library Management System (LMS)** is a console-based application developed in **C++** using **Object-Oriented Programming (OOP)** concepts. The system enables users to manage different types of library items such as **Books, DVDs, and Magazines**. Users can add items, display all items, search by title, check out items, and return borrowed items through a menu-driven interface.

This project demonstrates key OOP concepts including **abstraction, encapsulation, inheritance, polymorphism, dynamic memory allocation, and exception handling**.

---

## 🎯 Features

* Add Books, DVDs, and Magazines
* Display all library items
* Search items by title
* Check out library items
* Return borrowed items
* Menu-driven interface
* Dynamic memory allocation using pointers
* Exception handling for invalid inputs

---

## 🛠 Technologies Used

* **Programming Language:** C++
* **Compiler/IDE:** Visual Studio Code / Code::Blocks / Dev-C++ (Any C++ Compiler)

---

## 📚 OOP Concepts Used

* Classes and Objects
* Abstraction (Abstract Base Class)
* Encapsulation
* Inheritance
* Runtime Polymorphism
* Constructors
* Destructor
* Dynamic Memory Allocation (`new` and `delete`)
* Virtual Functions
* Pure Virtual Functions
* Exception Handling

---

## 📋 Class Structure

### 1. LibraryItem (Abstract Base Class)

**Private Data Members**

* Title
* Author
* Due Date

**Public Member Functions**

* Constructors
* Destructor
* Getters & Setters

**Pure Virtual Functions**

* `checkOut()`
* `returnItem()`
* `displayDetails()`

---

### 2. Book (Derived Class)

**Additional Attribute**

* ISBN

**Functions**

* Check Out Book
* Return Book
* Display Book Details

---

### 3. DVD (Derived Class)

**Additional Attribute**

* Duration (Minutes)

**Functions**

* Check Out DVD
* Return DVD
* Display DVD Details

---

### 4. Magazine (Derived Class)

**Additional Attribute**

* Issue Number

**Functions**

* Check Out Magazine
* Return Magazine
* Display Magazine Details

---

### 5. LibraryManagementSystem Class

**Functions**

* Add Library Item
* Display All Items
* Search Item by Title
* Check Out Item
* Return Item

---

## ▶️ Menu

```text
========== Library Management System ==========

1. Add Item
2. Display All Items
3. Search Item
4. Check Out Item
5. Return Item
6. Exit
```

---

## 📷 Sample Output

### Add a Book

```text
========== Library Management System ==========

Enter Your Choice : 1

1. Book
2. DVD
3. Magazine

Enter Choice : 1

Enter Title : C++ Programming
Enter Author : Bjarne Stroustrup
Enter Due Date : 15-08-2026
Enter ISBN : 97812345

Item Added Successfully.
```

---

### Display All Items

```text
====== Library Items ======

----- Book Details -----

Title : C++ Programming
Author : Bjarne Stroustrup
Due Date : 15-08-2026
ISBN : 97812345
```

---

### Search Item

```text
Enter Your Choice : 3

Enter Title : C++ Programming

Item Found!

----- Book Details -----

Title : C++ Programming
Author : Bjarne Stroustrup
Due Date : 15-08-2026
ISBN : 97812345
```

---

### Check Out Item

```text
Enter Your Choice : 4

Enter Title : C++ Programming

Book Checked Out Successfully.
```

---

### Return Item

```text
Enter Your Choice : 5

Enter Title : C++ Programming

Book Returned Successfully.
```

---

### Exception Handling Example

```text
Enter ISBN : 123

Exception : Invalid ISBN!
```

---

### Exit

```text
Enter Your Choice : 6

Thank You! Exiting Library Management System...
```

---

## 📸 Output Screenshots

Add screenshots of your project here.

Suggested screenshots:

* Main Menu
* Add Book
* Add DVD
* Display All Items
* Search Item
* Check Out Item
* Return Item
* Exception Handling
* Exit Screen

---

## 📁 Project Structure

```text
Library-Management-System/
│── LibraryManagementSystem.cpp
│── README.md
└── Screenshots/
    ├── Menu.png
    ├── AddBook.png
    ├── AddDVD.png
    ├── DisplayItems.png
    ├── SearchItem.png
    ├── CheckOut.png
    ├── ReturnItem.png
    ├── ExceptionHandling.png
    └── Exit.png
```

##Video Explaination:

https://drive.google.com/file/d/12uJAkyK2eLCUTIm_iXMqQ9CCQiL4ZoX7/view?usp=sharing
## 👩‍💻 Author

**Name:** Ayesha Bhesania

---

## 📄 Conclusion

The **Library Management System** successfully demonstrates the implementation of Object-Oriented Programming concepts in C++. The project uses an abstract base class, inheritance, runtime polymorphism, encapsulation, dynamic memory allocation, and exception handling to manage different types of library items efficiently. The menu-driven interface makes the system simple to use while showcasing the core principles of OOP.
