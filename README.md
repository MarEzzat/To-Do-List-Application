# To-Do List Application

## Overview
This Java console application allows users to manage a to-do list through a menu-driven interface. Users can add, update, delete, and search tasks by title, category, or date intervals. Task data is persistently stored in a file, ensuring data is retained between sessions.

## Features
- **Task Management**: Add, update, or delete tasks with attributes like title, description, creation date, due date, and category.
- **Search and Filter**: Search tasks by title or date intervals (creation or due date) and filter by category.
- **Persistent Storage**: Saves tasks to a file and loads them on startup using file I/O.
- **Console Interface**: Provides a simple, interactive menu for user operations.
- **Error Handling**: Handles invalid inputs and file operations gracefully.

## Requirements
- Java Development Kit (JDK) 8 or higher

No additional libraries are required, as the application uses standard Java libraries (`java.io`, `java.time`, `java.util`).

## Project Structure
- `Main.java`: Entry point, initializes the `UserInterface` and starts the application.
- `Item.java`: Defines the `Item` class for task objects with attributes and methods.
- `ToDoList.java`: Manages the list of tasks, including add, update, delete, and search/filter operations.
- `FileManager.java`: Handles file I/O for saving and loading tasks.
- `UserInterface.java`: Implements the console-based menu and user interaction logic.
- `README.md`: This file, providing project details and instructions.

## Example
To add a task:
- Select option `1` from the menu.
- Input:
  ```
  Enter the title: Finish Homework
  Enter the description: Complete math assignment
  Enter the creation date (yyyy-mm-dd): 2025-06-15
  Enter the due date (yyyy-mm-dd): 2025-06-20
  Enter the category: School
  ```
- The task is saved to the file and can be retrieved later.
