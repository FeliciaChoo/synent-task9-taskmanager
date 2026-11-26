# synent-task9-taskmanager-chooenyi
Full Stack Task Manager Web App built with Flask and SQLite
# Task 9: Full Stack Task Manager (Flask & SQLite)

A full-stack web application built for the **Synent Technologies Python Development Internship Program**. It enables users to register, authenticate securely, and manage personal tasks with priority tagging and status filtering.

## Features
- **User Authentication & Sessions:** User registration and login backed by `werkzeug.security` password hashing and Flask session management.
- **User-Scoped Task CRUD:** Create, view, toggle completion status, and delete tasks isolated per authenticated user in SQLite.
- **Priority & Status Filtering:** Assign `High`, `Medium`, or `Low` priority badges and filter tasks by `All`, `Pending`, or `Completed`.
- **Responsive UI:** Built with Jinja2 templates and Bootstrap 5.

## Tech Stack
- **Backend:** Python 3, Flask, Flask-SQLAlchemy
- **Database:** SQLite
- **Frontend:** HTML5, Jinja2, Bootstrap 5

## Setup & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-github-username>/synent-task9-taskmanager-chooenyi.git
   cd synent-task9-taskmanager-chooenyi
