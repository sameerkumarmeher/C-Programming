# 📘 C++ Basics – Complete Introduction Guide

---

## 📌 Overview

This document covers the fundamental concepts of C++ programming:

- Introduction to C++
- History of C++
- Compilation Process
- Structure of a C++ Program
- main() Function
- Header Files

These concepts build the foundation for advanced C++ development.

---

# 🟢 1️⃣ Introduction to C++

C++ is a powerful, high-performance programming language developed as an extension of the C language.

It supports:

- Procedural Programming  
- Object-Oriented Programming  
- Generic Programming  

### 💼 Applications of C++

- System Software  
- Game Development  
- Embedded Systems  
- Backend Development  
- Competitive Programming  
- High-Performance Applications  

C++ provides low-level memory control along with high-level abstractions, making it efficient and flexible.

---

# 🟢 2️⃣ History of C++

- Developed by **Bjarne Stroustrup** at Bell Labs (1979)  
- Originally called **"C with Classes"**  
- Renamed to **C++** in 1983  
- Designed to add Object-Oriented features to C  

### 📌 Major Versions

- C++98  
- C++03  
- C++11  
- C++14  
- C++17  
- C++20  

Modern C++ emphasizes performance, safety, and advanced features.

---

# 🟢 3️⃣ Compilation Process

C++ is a **compiled language**, meaning the source code is converted into machine code before execution.

## 🔄 Compilation Stages

Source Code → Preprocessing → Compilation → Linking → Executable File


### 🔹 Step 1: Preprocessing
- Expands header files (`#include`)
- Processes macros
- Removes comments

### 🔹 Step 2: Compilation
- Converts source code into object file (`.o` / `.obj`)

### 🔹 Step 3: Linking
- Combines object files with libraries
- Produces executable file

### 🔹 Step 4: Execution
- Program runs from the executable file

### 🔹 Step 5: Compile Command

g++ main.cpp -o program

./program

program.exe

---

# 🟢 4️⃣ Structure of a C++ Program
- A basic C++ program follows this structure:
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, World!";
    return 0;
}

### 🔍 Components Explained

| Component              | Description                          |
| ---------------------- | ------------------------------------ |
| `#include <iostream>`  | Header file for input/output         |
| `using namespace std;` | Allows use of standard library names |
| `int main()`           | Entry point of program               |
| `cout`                 | Output statement                     |
| `return 0;`            | Program termination status           |

---

# 🟢 5️⃣ main() Function

- The main() function is the starting point of every C++ program.
- Program execution always begins from this function.

### 🔹 Basic Syntax
int main() {
    // Code starts here
    return 0;
}

---

### 📌 Important Points

- int → Return type

- main() → Mandatory function

- return 0; → Indicates successful execution

- ⚠ Without main(), the program will not compile.

---

# 🟢 6️⃣ Header Files

- Header files contain function declarations and library definitions.
- They allow code reuse and access to standard functionality.

---

### 🔹 Example
 
#include <iostream>

# 📚 Common Header Files

| Header       | Purpose                 |
| ------------ | ----------------------- |
| `<iostream>` | Input/Output operations |
| `<cmath>`    | Mathematical functions  |
| `<string>`   | String handling         |
| `<vector>`   | Dynamic array container |
| `<fstream>`  | File handling           |

- Header files are included using the #include directive.