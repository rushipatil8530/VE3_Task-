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
## some Pictures of Project:
Home Page(Listview of API)
![image](https://github.com/rushipatil8530/VE3_Task-/assets/145107024/172e690b-ba7f-4b06-a791-b8cc05b81512)
Adding Task By Add Task button
![image](https://github.com/rushipatil8530/VE3_Task-/assets/145107024/407a9b43-03a3-4106-b8b5-18d84e1afffc)
Updating Task by Edit Button
![image](https://github.com/rushipatil8530/VE3_Task-/assets/145107024/58c39e97-d952-4312-abcf-3e7b0959a1d7)
Deleting Task By Delete Button 
![image](https://github.com/rushipatil8530/VE3_Task-/assets/145107024/d5a62385-3326-4b43-bae0-3cc4fd040702)







