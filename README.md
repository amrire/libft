# libft

`libft` is a custom implementation of various standard C library functions, along with additional utility functions. It is often used as a foundational project in the 42 School curriculum to deepen understanding of C programming and low-level programming concepts.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Features

- Reimplementation of standard C library functions such as `strlen`, `strcpy`, `atoi`, etc.
- Additional utility functions not included in the standard library.
- Provides a solid foundation for other C projects.

## Getting Started

To get started with `libft`, you'll need a working C compiler and `make` utility installed on your system.

### Prerequisites

Ensure you have the following installed:
- GCC or Clang
- GNU Make

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/amrire/libft.git
    cd libft
    ```

2. Compile the library:
    ```bash
    make
    ```

This will generate a `libft.a` file, which is the static library you can include in your C projects.

## Usage

To use `libft` in your project:
1. Include the header file in your source files:
    ```c
    #include "libft.h"
    ```

2. Link the compiled library when building your project:
    ```bash
    gcc -o my_program my_program.c -L. -lft
    ```

## Project Structure

- **`src/`**: Contains the source files for the library functions.
- **`includes/`**: Contains the `libft.h` header file.
- **`Makefile`**: Contains build instructions for the library.
