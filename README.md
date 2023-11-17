# To-Do-List_code
### Problem Statement:
A To-Do List application is a useful project that helps users manage and organize their tasks efficiently. This project aims to create a command-line or GUI-based application using Python, allowing users to create, update, and track their to-do lists.
### Code Explanation:
#### -->Class Definition (TodoList):
The TodoList class represents a to-do list. It has the following methods:
#### ->__init__: Initializes the to-do list by loading existing tasks from a file (todo_list.pkl) if it exists.
##### ->display_tasks: Prints the tasks in the to-do list.
##### ->add_task: Adds a new task to the to-do list and saves the updated list.
##### ->complete_task: Marks a task as completed by removing it from the list and saves the updated list.
##### ->delete_task: Deletes a task from the list and saves the updated list.
#### -->Function:
The main function is the entry point of the program.It creates an instance of the TodoList class to manage tasks.
The program runs in a loop, allowing the user to perform various actions until they choose to exit.
The program presents a menu with options for the user (display tasks, add task, complete task, delete task, exit).
It takes user input to determine the action to perform and executes the corresponding method of the TodoList class.
The program uses print statements to provide information and instructions to the user.
It uses the input function to get user input for choices and task descriptions.
If the user chooses to exit (choice == '5'), the program saves the current tasks to the file and prints a farewell message before breaking out of the loop.
### -->Conclusion:
Overall, this code creates a simple to-do list management system with a command-line interface, allowing users to perform actions on their to-do list. The use of file storage ensures that the to-do list persists between program runs.
