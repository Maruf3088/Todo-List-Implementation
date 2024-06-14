
## Todo List Implementation in C++

## Project Description
The Todo List Implementation in C++ is a console-based application designed to help users manage their personal tasks efficiently. This project showcases fundamental C++ programming concepts such as data structures, file handling, and user interaction via the console.



## Participants

- **Maruf Islam (C233228)**
- **Raktim Chowdhury (C233243)**
- **Mohammad Shihab Uddin (C233247)**

## Features
- **Add Task:** Add new tasks with a description.
- **Show Tasks:** Display all tasks added by the user.
- **Search Task:** Search for specific tasks by their ID.
- **Delete Task:** Remove tasks from the list.
## System Requirements
- **Operating System:** Windows, Linux, or MacOS
- **Compiler:** Any C++ compiler supporting C++11 or higher (e.g., GCC, Clang, MSVC)
- **Development Environment:** Any IDE or text editor suitable for C++ development (e.g., Visual Studio, Code::Blocks, CLion)
Function Descriptions
## main()
The main function serves as the entry point of the application. It displays the main menu and handles user input to perform different operations (add, show, search, delete tasks) in a loop until the application is terminated.

## banner()
This function displays a banner with the application title. It is used for visual consistency across different screens within the application.

## addTask()
This function allows the user to add a new task to the todo list. The user is prompted to enter the task description. The task is then saved to the file (todo.txt). The user can choose to add more tasks or return to the main menu.

## showTask()
This function displays all tasks currently stored in the todo list. It reads tasks from the file (todo.txt) and prints them to the console. The user can choose to exit the task display screen and return to the main menu.

## searchTask()
This function allows the user to search for a specific task by its ID. It prompts the user to enter the task ID and then searches through the tasks stored in the file (todo.txt). If the task is found, its details are displayed; otherwise, a "Not Found" message is shown.

## deleteTask()
This function deletes a task from the todo list. It first calls the searchTask() function to find the task by its ID. If the task is found, the user is prompted to confirm the deletion. The task is then removed from the file (todo.txt) by writing all remaining tasks to a temporary file (temp.txt) and renaming it to replace the original file.
## Acknowledgments
**Thanks to all the participants for their contributions to this project.**
