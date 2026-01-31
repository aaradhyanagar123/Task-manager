# Task-manager
A simple Task Manager application built using HTML, CSS, and JavaScript.
Task Manager is a web-based application built using HTML, CSS, and JavaScript that helps users efficiently manage their daily tasks. 
It allows users to add new tasks, edit existing ones, delete tasks, and mark tasks as completed. 
All tasks are stored in the browser using localStorage, ensuring they persist across page reloads. T
This project demonstrates dynamic DOM manipulation, user-friendly UI design, and frontend data management without a backend. 


# Approach

Frontend: HTML, CSS, JavaScript

Data Storage: Browser localStorage to persist tasks

# Main Features:

Add a new task

Edit an existing task

Delete a task

Mark task as completed

# Logic:

On page load, tasks are loaded from localStorage.

Tasks are updated dynamically using JavaScript DOM manipulation whenever added, edited, or deleted.

Completed tasks are styled differently to indicate status.


# Here we test user interactions and display. Example scenarios for a Task Manager UI:


Add Task : Enter a valid task and click "Add" ; Task appears in the list
Add Task : Leave input empty and click "Add" ; Error message or no task added
Delete Task	: Click delete on a task ; Task disappears from the list
Complete Task : Click checkbox on a task ; Task shows as completed (maybe strikethrough)
Task List Display : Add multiple tasks	; All tasks display in order, no duplicates
UI Responsiveness : Resize browser or use mobile device	UI elements adjust, buttons visible and clickable
Button Disabled	: Try clicking "Add" with empty input ; Button disabled or no action occurs
