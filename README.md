# Task Manager Web Application

A simple Task Manager web application built with Django and React.




## Overview

Task Manager is a web application that allows users to manage their tasks and to-do lists. It provides a user-friendly interface for creating, editing, and deleting tasks, as well as marking tasks as completed or incompleted. The backend is built with Django, which provides RESTful API endpoints for interacting with tasks, while the frontend is built with React.





## Features

- Create, Read, Update, and Delete tasks.
- Mark tasks as completed or incompleted.
- Filter tasks by completion status (completed/incompleted).
- User-friendly and responsive design.
- Seamless integration of Django and React.

## Getting Started

1. **Clone the repository:**

   https://github.com/rushipatil8530/VE3_Task-.git
   ```

2. **Backend (Django):**

   ```bash
   cd backend
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   ```

   The Django server should now be running at `http://localhost:8000`.

3. **Frontend (React):**

   ```bash
   cd frontend
   npm install
   npm start
   ```

   The React development server should now be running at `http://localhost:3000`.


## Usage

1. Access the web application by opening your web browser and navigating to `http://localhost:3000`.

2. Create a new task by clicking the "Add Task" button.

3. Edit or delete tasks using the provided buttons.

4. Mark tasks as completed or incompleted by clicking on them.

## API Endpoints

The backend Django server provides the following API endpoints:

- `GET /api/task/`: Get a list of all tasks.
- `POST /api/task/`: Create a new task.
- `GET /api/task/<task_id>/`: Get details of a specific task.
- `PUT /api/task/<task_id>/`: Update a specific task.
- `DELETE /api/task/<task_id>/`: Delete a specific task.

You can use these endpoints to interact with the task data programmatically.




