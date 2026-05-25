# Operating Systems Projects Collection

This repository contains a collection of Operating Systems projects implemented in C/C++ as part of coursework and practical system programming exercises. These projects demonstrate core OS concepts such as process scheduling, ELF loading, shell implementation, multithreading, and operating system design.

---

# Projects Included

## 1. SimpleLoader – An ELF Loader in C from Scratch

### Overview

This project implements a basic ELF (Executable and Linkable Format) loader in C. The loader is responsible for reading executable files, parsing ELF headers, loading program segments into memory, and executing the target program.

### Concepts Covered

* ELF file structure
* Memory management
* Program loading
* Low-level systems programming
* Process execution

### Files Included

* `loader.c`
* `loader.h`
* `fib.c`
* `Makefile`

### Features

* Parses ELF executable files
* Loads executable segments into memory
* Transfers control to the loaded program
* Demonstrates manual executable loading without relying on the operating system loader

### Technologies Used

* C Programming
* GCC Compiler
* Linux System Calls

---

## 2. SimpleSmartLoader – An Upgraded SimpleLoader in C

### Overview

This project is an enhanced version of the SimpleLoader. It improves memory handling and executable loading techniques while maintaining low-level control over program execution.

### Concepts Covered

* Advanced ELF loading
* Memory optimization
* Segment management
* Dynamic execution flow

### Files Included

* `loader.c`
* `loader.h`
* `fib.c`
* `sum.c`
* `Makefile`

### Features

* Improved executable loading mechanism
* Better memory handling compared to the basic loader
* Supports execution of sample programs
* Modular loader design

### Technologies Used

* C Programming
* Linux System Programming
* ELF Binary Handling

---

## 3. SimpleShell – A Unix Shell in C from Scratch

### Overview

This project implements a custom Unix shell that can execute commands similarly to a Linux terminal. The shell supports command parsing, process creation, and command execution.

### Concepts Covered

* Process creation using `fork()`
* Command execution using `exec()`
* Shell programming
* Input parsing
* Unix process management

### Files Included

* `simpleshell.c`
* `fib.c`
* `helloworld.c`

### Features

* Executes Linux commands
* Supports child process creation
* Handles command-line input
* Demonstrates basic shell functionality

### Technologies Used

* C Programming
* Unix/Linux System Calls
* GCC Compiler

---

## 4. SimpleScheduler – A Process Scheduler in C from Scratch

### Overview

This project simulates a process scheduler similar to those used in operating systems. It manages multiple jobs and demonstrates scheduling strategies and process handling.

### Concepts Covered

* CPU scheduling
* Job management
* Process queues
* Context switching concepts
* Scheduling algorithms

### Files Included

* `scheduler.c`
* `job.c`
* `simpleshell.c`
* `dummy_main.h`
* `Makefile`

### Features

* Simulates process scheduling
* Handles multiple jobs
* Demonstrates scheduler workflow
* Integrates shell-like command execution

### Technologies Used

* C Programming
* Operating Systems Concepts
* Linux Environment

---

## 5. SimpleMultithreader – Using Multithreading

### Overview

This project demonstrates parallel computation using multithreading in C++. It focuses on improving performance through concurrent execution.

### Concepts Covered

* Multithreading
* Parallel programming
* Thread synchronization
* Concurrent execution
* Performance optimization

### Files Included

* `matrix.cpp`
* `vector.cpp`
* `simple-multithreader.h`
* `Makefile`

### Features

* Parallel matrix operations
* Vector computation using threads
* Demonstrates thread-based execution
* Improves computational efficiency

### Technologies Used

* C++
* POSIX Threads (Pthreads)
* GCC/G++ Compiler

---

## 6. EGOS Operating System

### Overview

EGOS is a small educational operating system project that demonstrates the internal working of an operating system. It includes system-level modules, utilities, process handling, and kernel-level functionality.

### Concepts Covered

* Operating system architecture
* Process management
* File systems
* Shell implementation
* System calls
* Memory management
* Kernel programming

### Features

* Educational operating system environment
* Command-line utilities
* Process and terminal management
* System-level debugging support
* Multiple demo and utility programs

### Technologies Used

* C Programming
* Operating Systems Design
* Low-Level System Programming

---

# How to Run the Projects

## Prerequisites

* Linux Operating System
* GCC/G++ Compiler
* Make Utility
* Basic knowledge of C/C++ and Linux commands

## Build Instructions

```bash
make
```

## Run Example

```bash
./a.out
```

Some projects may generate custom executable names depending on the Makefile configuration.

---

# Learning Outcomes

Through these projects, the following Operating Systems concepts were explored:

* Process creation and scheduling
* ELF executable loading
* Unix shell implementation
* Multithreading and concurrency
* System-level programming
* Memory management concepts
* Kernel and operating system architecture

---

# Repository Structure

```text
Operating-Systems-Projects/
│
├── SimpleLoader/
├── SimpleSmartLoader/
├── SimpleShell/
├── SimpleScheduler/
├── SimpleMultithreader/
└── EGOS-Operating-System/
```

---

# Future Improvements

* Add support for advanced shell commands
* Improve scheduler algorithms
* Extend ELF loader capabilities
* Add synchronization primitives in multithreading projects
* Improve documentation and testing

---
