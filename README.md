# Basic File Management System

## Description
This project is a simple file management system written in C, providing basic functionalities like creating, reading, writing, renaming, and deleting files. It features a user-friendly, text-based menu for easy interaction.

## Features
- **Create a File**: Create a new file and input content to save to it.
- **Read a File**: View the content of an existing file.
- **Write to a File**: Append new content to an existing file.
- **Rename a File**: Rename a file with a new name.
- **Delete a File**: Remove a file from the system.
- **Exit**: Exit the program and terminate the session.

## Required Modules
- **stdio.h**: Standard I/O operations (for file handling and user interaction).
- **stdlib.h**: Standard library functions (for memory allocation, file handling, and program control).

These libraries come pre-installed with most C compilers, so no additional installation is necessary.

## Installation Instructions

### 1. Clone the Repository
Clone the repository to your local machine using Git:
```bash
git clone https://github.com/yourusername/basic-file-management-system.git.
```
### 2. Compile the Program
Navigate into the project directory and compile the program using the gcc compiler:
```bash
cd basic-file-management-system
gcc -o file_management file_management.c
```

### 3. Run the Program
Execute the compiled program:
```bash
./file_management
```
The program will display a menu for you to choose an operation. Follow the on-screen instructions to interact with the file management system.

### File Management System Menu
1. Create File: Create a new file and input content to store in the file.
2. Read File: Display the content of an existing file.
3. Write to File: Append new content to an existing file.
4. Rename File: Rename an existing file to a new name.
5. Delete File: Delete an existing file.
6. Exit: Exit the program.
