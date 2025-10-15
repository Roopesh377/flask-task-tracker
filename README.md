# Daily Task Tracker - Flask Web App

## Overview
This is a simple Flask-based web application to manage daily tasks. Users can add, edit, delete, and mark tasks as completed. The app uses SQLite for data storage and runs on Flask with Jinja2 templates.

## Features
- Add new tasks with descriptions
- Edit or update existing tasks
- Delete tasks
- Mark tasks as completed
- Tasks persist in SQLite database

## Technologies
- Python 3.10
- Flask
- Flask-SQLAlchemy
- SQLite
- Bootstrap 5 (for UI styling)

## Installation & Local Setup

### 1. Clone the repository: https://github.com/Roopesh377/flask-task-tracker.git
````bash
cd flask-task-tracker
````
### 2. Create and activate a Python virtual environment:
````bash
python -m venv venv
venv\Scripts\activate
````

### 3. Install dependencies:
````bash
pip install -r requirements.txt
````
### 4. Run the app:
````bash
python app.py
````

### 5. Access the app in your browser at `http://127.0.0.1:5000`

## Deployment
### The app is deployed on PythonAnywhere at: https://Roopesh377.pythonanywhere.com


## Challenges & Notes
- Database schema migrations were handled by dropping and recreating the SQLite database during development.
- Future improvements can include user authentication and advanced UI enhancements.


