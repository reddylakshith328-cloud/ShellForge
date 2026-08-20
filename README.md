# ShellForge

ShellForge is a Unix-like shell developed as part of the Operating Systems and Systems Programming Project-Based Learning course.

The project is developed incrementally, with Week 2 continuing and extending the implementation created in Week 1.

---

## Week 1 – Initial REPL Loop and Project Setup

### Objective

The objective of Week 1 is to create the initial ShellForge project structure and implement a basic interactive REPL (Read-Eval-Print Loop).

### Features

- Interactive REPL loop
- Basic command input
- Makefile-based build
- Git repository setup
- Linux development environment

### Project Structure

```text
ShellForge/
├── include/
│   └── shell.h
├── src/
│   └── main.c
├── Makefile
├── README.md
└── .gitignore
---

# Week 2 – Dynamic Input and Memory Management

## Objective

Week 2 extends the ShellForge project developed in Week 1 by implementing dynamic command input and memory management.

## Features

- Dynamic command input
- Dynamic memory allocation using `malloc()`
- Dynamic buffer resizing using `realloc()`
- Memory deallocation using `free()`
- Separate input-handling module
- Integration with the existing ShellForge REPL

## Project Structure – Week 2

```text
ShellForge/
├── include/
│   ├── shell.h
│   └── input.h
├── src/
│   ├── main.c
│   └── input.c
├── Makefile
├── README.md
└── .gitignore
