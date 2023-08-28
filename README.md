# Task List App

This is a simple desktop Task List app built using the Tkinter library in Python. The app allows you to add and manage tasks. Tasks are stored in a text file (`tasklist.txt`) and are displayed in a graphical user interface (GUI) created using Tkinter.

## Features

- Add tasks: You can add tasks to the list by typing the task in the input field and clicking the "ADD" button.
- Display tasks: Tasks are displayed in a scrollable listbox in the main window.
- Delete tasks: You can delete a task by selecting it in the list and clicking the delete button.

## Getting Started

1. **Requirements**: Make sure you have Python installed on your system. The code uses the Tkinter library, which is usually included in standard Python installations.

2. **Clone the Repository**: If the code is not already on your system, you can clone this repository using Git:

   ```bash
   git clone https://github.com/suburban-loner/task-list.git
   cd main
   ```

3. **Run the App**: Open a terminal/command prompt, navigate to the repository directory, and run the following command:

   ```bash
   python main.py
   ```


## App Interface

The app's graphical user interface includes the following components:

- Top bar with an app icon and title.
- A note icon.
- "All Tasks" heading.
- Input field for entering tasks.
- "ADD" button to add tasks.
- Listbox displaying the list of tasks.
- Delete button to remove selected tasks.

## Functionality

- The `addTask` function is responsible for adding a task to both the `task_list` and the text file `tasklist.txt`.
- The `deleteTask` function allows you to delete a selected task from the list and update the text file accordingly.
- The `openTaskFile` function reads tasks from the `tasklist.txt` file and populates the listbox.

## Notes

- Make sure to handle any image paths (`Images/task.png`, etc.) properly so that the images are accessible when running the app.
- If you encounter any issues or errors, ensure that you have the required libraries installed and that the image paths are correct.
