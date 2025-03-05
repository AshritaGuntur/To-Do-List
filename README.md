# To-Do-List
Overview
This is a simple To-Do List application built using Python and Tkinter for the graphical user interface (GUI). It allows users to add, delete, and manage tasks. The tasks are stored in an SQLite database for persistence.

Features
Add Tasks: Users can enter a task and add it to the list.
Delete Tasks: Users can remove a selected task from the list.
Delete All Tasks: Users can clear the entire task list.
Persistent Storage: Tasks are stored in an SQLite database, ensuring they remain available even after the application is closed.

Requirements
Python 3.x
Tkinter (comes pre-installed with Python)
SQLite3 (comes pre-installed with Python)
Installation
Clone the repository or download the script.
git clone https://github.com/Asha0509/ToDoLIst---python.git
Navigate to the project directory.
cd ToDoLIst---python
Run the script.
python todo_list.py

Usage
Run the script to open the To-Do List application.
Enter a task in the input field and click Add to save it.
Select a task and click Remove to delete it.
Click Delete All to remove all tasks.
Click Exit / Close to close the application.

File Structure
todo_list.py - Main script containing the application logic.
listOfTasks.db - SQLite database file (automatically created).
