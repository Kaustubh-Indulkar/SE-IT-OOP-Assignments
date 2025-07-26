# Java OOP & Programming Assignments Repository

This repository contains a collection of Java programming assignments focused on Object-Oriented Programming (OOP) concepts, structured to align with various Course Outcomes (CO1–CO5). Each assignment demonstrates key features like classes, inheritance, polymorphism, interfaces, templates, exception handling, and file management.

---

## 📘 Table of Contents

| Index | Assignment Title                 | Course Outcome(s) | Description                                                  |
|-------|----------------------------------|-------------------|--------------------------------------------------------------|
| 1     | Classes and Objects              | CO1, CO2          | Complex number arithmetic using default and parameterized constructors |
| 2     | Polymorphism                     | CO3               | Publication, Book, Magazine class hierarchy                 |
| 3     | Inheritance                      | CO3               | Employee hierarchy with salary computation                  |
| 4     | Dynamic Binding                  | CO3               | Abstract `compute_area()` in shape-based class hierarchy     |
| 5     | Interface                        | CO1, CO3          | Vehicle interface with bicycle, bike, and car implementations |
| 6     | Exception Handling               | CO4               | Arithmetic, index, and number format exception management    |
| 7     | Template                         | CO4               | Generic collection processing for even, odd, prime, palindrome |
| 8     | File Handling                    | CO5               | Student record file operations (CRUD & Search)              |

---

## 📌 Assignments Overview

### 1. Classes and Objects — CO1, CO2

**Objective:**  
Design a `Complex` class with `real` and `imaginary` parts. Include default and parameterized constructors. Implement arithmetic operations (add, subtract, multiply) between two complex numbers.

---

### 2. Polymorphism — CO3

**Objective:**  
Design a class hierarchy with:
- Common attributes: `title`, `price`, `copies`
- Common method: `saleCopy()`

**Differences:**
- `Book`: has `author`, `orderCopies()`
- `Magazine`: has `orderQty()`, `currentIssue`, `receiveIssue()`

Write a program to:
- Count the number of copies ordered
- Display total sales from all publications

---

### 3. Inheritance — CO3

**Objective:**  
Create an `Employee` base class with:
- `emp_name`, `emp_id`, `address`, `mail_id`, `mobile_no`

Inherit:
- `Programmer`, `TeamLead`, `AssistantProjectManager`, `ProjectManager`

Each subclass contains:
- `Basic Pay (BP)`
- Derived attributes:
  - DA = 97% of BP
  - HRA = 10% of BP
  - PF = 12% of BP
  - Staff Club Fund = 0.1% of BP

Generate pay slips with gross and net salary calculations.

---

### 4. Dynamic Binding — CO3

**Objective:**  
Create an abstract base class `Shape` with:
- `double` values
- Method: `compute_area()` (abstract)

Derive:
- `Triangle`, `Rectangle` classes that override `compute_area()`

Demonstrate **dynamic binding** to compute area at runtime.

---

### 5. Interface — CO1, CO3

**Objective:**  
Define an interface `Vehicle` with:
- `gearChange()`
- `speedUp()`
- `applyBrakes()`

Implement:
- `Bicycle`, `Car`, `Bike` classes with their own logic for each method.

---

### 6. Exception Handling — CO4

**Objective:**  
Develop a program to handle exceptions:
- **Arithmetic Exception**: Division by zero
- **ArrayIndexOutOfBoundsException**
- **NumberFormatException**: Non-integer input

Accept user input (`Num1`, `Num2`) and safely handle errors while displaying exceptions.

---

### 7. Template / Generics — CO4

**Objective:**  
Create a **generic program** using collection classes to:
- Count elements satisfying properties:
  - Even numbers
  - Odd numbers
  - Prime numbers
  - Palindromes

Use Java Collections like `ArrayList` or `Set`.

---

### 8. File Handling — CO5

**Objective:**  
Build a **student record management system** using file operations.

Student attributes:
- `student_id`, `name`, `roll_no`, `class`, `marks`, `address`

Functions:
1. Create Database  
2. Display Database  
3. Delete Record  
4. Update Record  
5. Search Record  

Perform read/write operations using `FileInputStream`, `FileOutputStream`, or `BufferedReader`.

---



