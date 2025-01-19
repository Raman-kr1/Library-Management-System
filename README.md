# Library Management System

## Overview
The Library Management System is a console-based program written in C++ to streamline the management of library resources. It supports book management, user handling, and fine calculation while maintaining a seamless user experience for librarians, students, and professors.

---

## Features
- **Librarian Features**:
  - Add, delete, and update books and users.
  - View all books and users.
  - Check which user has issued a specific book.
  - Clear fines for users.
  - Search for books and users.

- **Student/Professor Features**:
  - View available books.
  - Issue and return books.
  - View issued books and their due dates.
  - Calculate and pay fines.

- **Authentication**:
  - Role-based login for librarians, students, and professors.

---

## Prerequisites
- A C++ compiler (e.g., GCC).
- Basic knowledge of running C++ programs in a console.

---

## How to Run
1. Compile the program:
   ```bash
   g++ main.cpp -o library_system
   ```
2. Execute the compiled file:
   ```bash
   ./library_system
   ```
3. Follow the prompts to interact with the system.

---

## How It Works
1. **Login**:
   - Librarian: Access administrative functions with predefined credentials.
   - Students/Professors: Login with their unique IDs.

2. **Librarian Actions**:
   - Manage users and books.
   - Track issued books and overdue fines.

3. **Student/Professor Actions**:
   - Issue books and check due dates.
   - Return books and settle fines.

---

## Data Storage
Data is temporarily stored in memory during runtime. Persistent storage can be added in future versions using file handling or databases.

---

## Contribution
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

---

## License
This project is licensed under the MIT License. Feel free to use and modify it as per your needs.

