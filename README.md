# TodoList App

TodoList App is a web-based application for managing tasks effectively.

## Motivation

The motivation behind this project is to learn about ETL (Extract, Transform, Load) pipelines and gain experience with frameworks like Airflow and Argo.

## Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite

## Features

- **Task Management:** Create, edit, and delete tasks.
- **Priority Levels:** Set priorities for tasks (e.g., high, medium, low).
- **Due Dates:** Assign due dates to tasks for better organization.
- **Categories and Tags:** Organize tasks into categories or tag them for easy filtering.
- **User Authentication:** Register and authenticate users to manage their tasks securely.
- **Responsive Design:** Ensures the app works seamlessly on desktop and mobile devices.

## Working

The application utilizes Django to manage tasks:
1. Users can perform CRUD operations on tasks.
2. Prioritize tasks and set due dates.
3. Organize tasks into categories or tags.
4. Authenticate users for secure access.

## Installation

1. Clone the repository:
   git clone https://github.com/your-username/todo-list-app.git
   cd todo-list-app
   
2. Install dependencies:
   pip install -r requirements.txt

3. Apply Database Migration :
   python manage.py migrate

4.Run the development server :
  python manage.py runserver

5.Access the application at http://localhost:8000 in your web browser.
