# Student Record Management System

A console-based Student Record Management System developed using **C programming**. This project manages student information using structures, singly linked lists, dynamic memory allocation, and file handling.

## Features

- **Add Student:** Add new student records with automatically generated roll numbers.
- **Delete Student:** Delete student records using roll number or name.
- **Modify Student:** Update student details such as name and percentage.
- **Display Students:** View all stored student records.
- **Sort Records:** Sort student records by name or percentage.
- **File Handling:** Save student records permanently in a file and retrieve them when the program starts.
- **Dynamic Memory Allocation:** Manage student records dynamically using `malloc()` and `free()`.

## Technologies Used

- C Programming
- Structures
- Singly Linked Lists
- Pointers
- Dynamic Memory Allocation
- File Handling
- String Manipulation
- Makefile
- Linux (Ubuntu)

## Project Structure

```text
Student-Record-Management/
│
├── main.c
├── student.h
├── stud_add.c
├── stud_del.c
├── stud_mod.c
├── stud_show.c
├── stud_sort.c
├── stud_save.c
├── file_read.c
├── Makefile
├── student.dat
└── README.md
```

## Compilation and Execution

### 1. Clone the repository

```bash
git clone <repository-url>
```

### 2. Navigate to the project directory

```bash
cd Student-Record-Management
```

### 3. Compile the project

```bash
make
```

### 4. Run the application

```bash
./a.out
```

### 5. Clean object files

```bash
make clean
```

## Concepts Implemented

| Concept | Application |
|---|---|
| Structures | Store student information |
| Linked Lists | Manage student records |
| Pointers | Access and manipulate nodes |
| Dynamic Memory Allocation | Allocate and release memory |
| File Handling | Store and retrieve student records |
| `strcmp()` | Compare student names |
| `strcpy()` | Modify student names |
| `memcpy()` | Swap student data during sorting |
| Makefile | Automate compilation |

## Learning Outcomes

- Gained practical experience in C programming.
- Implemented linked-list operations.
- Improved understanding of pointers and dynamic memory allocation.
- Learned file handling for persistent data storage.
- Practised modular programming using multiple C source files.

## Author

**Vasanthamukilan M**

---

If you find this project useful, feel free to star the repository!
