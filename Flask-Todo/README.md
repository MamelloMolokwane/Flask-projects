# Flask-Todo

Flask-Todo is a simple To-Do List web application built with Python and Flask. It lets you add tasks, view your tasks, update them, and delete them.

I built this project to practise working with Flask, HTML, CSS, forms and a database using SQLite.

## Features

* Add a new task
* View all tasks
* Update an existing task
* Delete a task
* Store tasks in a SQLite database
* Simple responsive interface

## Technologies Used

* Python
* Flask
* Flask-SQLAlchemy
* SQLite
* HTML
* CSS
* JavaScript

## Project Structure

```text
Task-Master/
│
├── app.py
├── requirements.txt
├── test.db
│
├── static/
│   ├── style.css
│   └── script.js
│
└── templates/
    ├── base.html
    ├── index.html
    └── update.html
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/MamelloMolokwane/Flask-projects/tree/main/Flask-Todo
```

Move into the project folder:

```bash
cd Task-Master
```

### 2. Create a virtual environment

It is recommended to use a virtual environment for the project.

On Windows:

```bash
python -m venv venv
```

Activate it:

```bash
venv\Scripts\activate
```

On macOS/Linux:

```bash
python3 -m venv venv
```

Activate it:

```bash
source venv/bin/activate
```

### 3. Install the dependencies

Install the packages from `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 4. Run the application

Run:

```bash
python app.py
```

You should see Flask start the development server.

Open the address shown in the terminal, normally:

```text
http://127.0.0.1:5000
```

### 5. Using the application

Once the application is running, you can:

1. Enter a task in the input field.
2. Click **Add Task**.
3. Your task will appear in the task table.
4. Click **Update** to change a task.
5. Click **Delete** to remove a task.

## Database

The application uses SQLite through Flask-SQLAlchemy.

The database is stored locally as:

```text
test.db
```

The database is created when the application is set up and used to store the tasks.

## Requirements

The main Python dependencies are:

```text
Flask
Flask-SQLAlchemy
```

They can be installed with:

```bash
pip install -r requirements.txt
```

## Notes

This is a small learning project and was mainly created to practise building a basic CRUD application with Flask.

There are a few things that could be added in the future, such as marking tasks as completed, adding due dates, user accounts and improving the task filtering.
