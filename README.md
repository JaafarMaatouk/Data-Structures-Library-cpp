# Custom Data Structures Library (C++)

A comprehensive C++ library that implements core Data Structures from scratch using Object-Oriented Programming (OOP) and Templates. This project demonstrates a deep understanding of memory management, pointers, and generic programming without relying on the Standard Template Library (STL).

## Project Overview
This library provides custom-built, reusable data structure classes that can handle any data type using C++ Templates. It includes implementations for both Linked List-based and Array-based structures, offering flexibility and performance.

## Implemented Data Structures
The library includes the following custom classes:

1. **Doubly Linked List (`dsDblLinkedList`)**
   - Supports insertion, deletion, searching, and updating nodes.
   - Provides operations like `InsertAfter`, `InsertBefore`, `UpdateItem`, and more.
2. **Dynamic Array (`dsDynamicArray`)**
   - A resizable array that manages its own memory dynamically.
3. **Stack (`dsMyStack` & `dsMyStackArr`)**
   - Implemented using both Linked Lists and Arrays.
   - Supports LIFO (Last-In-First-Out) operations.
4. **Queue (`dsMyQueue` & `dsMyQueueArr`)**
   - Implemented using both Linked Lists and Arrays.
   - Supports FIFO (First-In-First-Out) operations.

## Architecture & Technical Highlights
- **Object-Oriented Design:** Encapsulation of data and methods within classes.
- **Generic Programming:** Uses C++ Templates (`template <class T>`) to allow the data structures to store any data type (e.g., int, string, custom objects).
- **Memory Management:** Handles dynamic memory allocation (`new` / `delete`) safely for nodes and arrays.
- **Modularity:** Each data structure is separated into its own header file (`.h`) for clean code organization.

## How to Run
1. Clone this repository or download it as a ZIP file.
2. Open the `.sln` file in Visual Studio.
3. The library is ready to be included in your C++ projects. You can test it by running the `main` function included in the source file.
4. Press `F5` or `Ctrl + F5` to build and test.

## License
This project is open-source and available under the MIT License.
