Task Manager API <br>
A simple Flask-based REST API for managing tasks. This application allows you to create, read, update, and delete tasks.<br><br>

Features
List Tasks: Retrieve all tasks.<br>
Add Task: Create a new task.<br>
Update Task: Modify an existing task.<br>
Delete Task: Remove a task.<br><br>
Getting Started
Prerequisites
Python 3.x<br>
Flask<br>
Flask-SQLAlchemy<br><br>


API Endpoints
GET /tasks: Retrieve all tasks.<br>
POST /tasks: Add a new task. (Requires JSON body with description)<br>
PUT /tasks/<id>: Update a task by ID. (Requires JSON body with description)<br>
DELETE /tasks/<id>: Delete a task by ID.<br><br>
