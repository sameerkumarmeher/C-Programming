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

```bash
g++ main.cpp -o program


▶ Run the Program (Linux / Mac)
./program

▶ Run the Program (Windows)
program.exe

