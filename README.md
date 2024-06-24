# Task Manager App

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API](#api)
- [Contributing](#contributing)
- [License](#license)

## Overview
Task Manager App is a simple yet efficient task management application built with React.js. It allows users to manage their tasks by adding, deleting, and toggling reminders for tasks. The app interacts with a backend server to fetch and manipulate tasks.

## Features
- **Add Task:** Add new tasks with a title, date, and reminder.
- **Delete Task:** Remove tasks from the list.
- **Toggle Reminder:** Set reminders for tasks with a simple toggle.
- **Fetch Tasks:** Retrieve tasks from the server.
- **Responsive Design:** Optimized for different screen sizes.

## Installation
To get started with the Task Manager App, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/task-manager-app.git
   cd task-manager-app
2. **Install dependencies:**
   ```sh
   npm install
3. **Start the Development Server:**
   ```sh
   npm start
   
## Usage
Once the development server is running, you can access the app at `http://localhost:3000`. The app will fetch tasks from the backend server and display them. You can add, delete, and toggle reminders for tasks using the UI.

### Adding a Task
Click on the "Add Task" button to reveal the task form. Fill in the details and click "Save Task" to add the task to the list.

### Deleting a Task
Click the delete icon next to a task to remove it from the list.

### Toggling a Reminder
Click on a task to toggle the reminder setting.

## API
The app interacts with a backend server running at `http://localhost:8000`. The following endpoints are used:

- **Fetch all tasks:**
  ```sh
  GET /tasks
  ```
  Fetches all tasks from the server.

- **Fetch a single task:**
  ```sh
  GET /tasks/:id
  ```
  Fetches a specific task by its ID.

- **Add a new task:**
  ```sh
  POST /tasks
  ```
  Adds a new task. Requires a JSON body with task details.

- **Delete a task:**
  ```sh
  DELETE /tasks/:id
  ```
  Deletes a specific task by its ID.

- **Update a task:**
  ```sh
  PUT /tasks/:id
  ```
  Updates a specific task. Requires a JSON body with updated task details.

## Contributing
We welcome contributions to improve the Task Manager App. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-branch-name`
5. Submit a pull request.