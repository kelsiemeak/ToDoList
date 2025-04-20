To-Do List App

This project is a basic, interactive to-do list built with HTML, CSS, and JavaScript. It allows users to add tasks, mark them as complete, delete them, and automatically saves the task list using `localStorage`.

Features

- Add new tasks  
- Mark tasks as completed  
- Delete individual tasks  
- Save tasks to local storage  
- Restore tasks on page reload  

How It Works

1. `addTask()`
- Validates the input: if it's empty, it shows an alert.
- Creates a new `<li>` with the task text.
- Clears the input field and saves the data to localStorage.

2. `listContainer.addEventListener("click", ...)`
- Toggles the `checked` class when a task is clicked to mark it as done.
- Removes the task if the close button (`×`) is clicked.
- Updates localStorage after every change.

3. `saveData()`
- Stores the current state of the task list in `localStorage`.

4. `showTask()`
- Loads the saved task list from `localStorage` and displays it on page load.

