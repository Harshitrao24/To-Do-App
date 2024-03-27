# To-Do List App

This is a simple To-Do List application built with HTML, CSS, and JavaScript. It allows users to add tasks, mark tasks as completed, and delete tasks.

## Features

- **Add Task**: Users can input a task in the text box and click the "Add" button to add it to the list.
- **Mark as Completed**: Clicking on a task item marks it as completed. Clicking again unmarks it.
- **Delete Task**: Users can delete a task by clicking on the delete icon (×) next to the task.

## Getting Started

To use this application, simply open the `index.html` file in your web browser.

## Usage

1. Enter a task in the input box provided.
2. Click the "Add" button or press Enter to add the task to the list.
3. Click on a task to mark it as completed.
4. Click again on a completed task to unmark it.
5. Click on the delete icon (×) next to a task to delete it from the list.

## Folder Structure

- `index.html`: HTML file containing the structure of the application.
- `script.js`: JavaScript file containing the application logic.
- `style.css`: CSS file containing styles for the application.
- `/images`: Folder containing images used in the application.

## How it Works

- The `addTask()` function adds a new task to the list when the user clicks the "Add" button.
- Click event listeners are attached to the list items and delete icons (`<span>`) to handle marking tasks as completed and deleting tasks, respectively.
- Completed tasks are visually differentiated by striking through their text.
- Task data is saved and retrieved from the browser's local storage to persist tasks between sessions.

## Author

This To-Do List App is created by Harshit Rao.
