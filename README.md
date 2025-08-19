# CS300_Project

# Course Planner Project

## Project Overview
The goal of this project was to design and implement a command-line program in C++ that manages course information for a Computer Science advising team. The program needed to load course data from a file, store the courses in an efficient data structure, and provide users with features such as viewing all courses in alphanumeric order and displaying individual course details with prerequisites.

---

## Problem Solved
The problem addressed was creating a reliable and efficient way for advisers to manage and retrieve course information. Specifically, the program needed to:
- Parse and load course data from a file into a data structure.
- Display all courses in sorted (alphanumeric) order.
- Retrieve and display information about individual courses, including prerequisites.
- Provide a user-friendly menu with input validation and error handling.

---

## Approach
I approached the problem by focusing on the importance of **data structures** in software design. Data structures are critical because they directly affect performance, memory usage, and how easily data can be manipulated. After evaluating options, I chose to implement a **Binary Search Tree (BST)** to store the course information. This allowed:
- Efficient insertion and retrieval of courses.
- Automatic alphanumeric ordering when traversing the tree.
- Scalability for larger datasets in the future.

---

## Overcoming Roadblocks
During development, I faced challenges such as:
- **File parsing**: Ensuring that the program correctly handled courses with variable numbers of prerequisites.
- **Error handling**: Designing robust validation for invalid file inputs, incorrect course numbers, and unexpected menu selections.
- **BST logic**: Debugging insertion and traversal logic to guarantee that the tree maintained correct ordering.

I overcame these issues by breaking problems down into smaller steps, testing individual components (like the parser and tree insertions) before integrating them, and adding clear error messages for edge cases.

---

## Lessons in Software Design
This project expanded my approach to designing software by showing me how important it is to match the problem with the correct data structure. The BST not only simplified the sorting requirement but also made retrieval more efficient. It also highlighted the importance of planning program flow with pseudocode before jumping into coding.

---

## Writing Maintainable Code
Through this project, I evolved my programming practices by:
- Using **clear function names** and consistent **naming conventions**.
- Adding **inline comments** to explain logic and complex sections of code.
- Applying **modularity** so that each function had a single responsibility.
- Building in **input validation and error messages** to make the program more user-friendly and reliable.

These practices ensure the program is **maintainable, readable, and adaptable**, which are essential qualities for long-term software development.

---
