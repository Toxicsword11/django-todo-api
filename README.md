To-Do List API (Django-Ninja)
Introduction
This is a simple To-Do List API built using Django-Ninja, a fast API toolkit for Django. The API allows users to create, read, update, and delete tasks efficiently.
Features
•	CRUD Operations: Add, view, update, and delete tasks.
•	User Authentication: Secure API endpoints (if implemented).
•	Django-Ninja Swagger UI: Interactive API testing.
•	Database Integration: Uses Django ORM for data storage.
Tech Stack
•	Backend: Django, Django-Ninja
•	Database: SQLite 
•	Authentication: Django Auth 
Installation
1. Clone the Repository
git clone <repo-link>
cd todolist
2. Create a Virtual Environment
python -m venv todo
source todo/bin/activate  # On Windows: todo\Scripts\activate
3. Install Dependencies
pip install -r requirements.txt
4. Apply Migrations
python manage.py migrate
5. Run the Server
python manage.py runserver


API Endpoints
Base URL: http://127.0.0.1:8000/api/

Method	Endpoint	Description
GET	/tasks/	Retrieve all tasks
POST	/tasks/	Create a new task
GET	/tasks/{id}/	Retrieve a specific task
PUT	/tasks/{id}/	Update a task
DELETE	/tasks/{id}/	Delete a task

Testing the API
1.	Open your browser and go to: 
2.	http://127.0.0.1:8000/api/docs
3.	This will open Django-Ninja's Swagger UI, where you can interact with the API.
Contribution Breakdown
1. API Development (Arosh Krushnaji Goannade - Lead Developer)
•	Implemented Django-Ninja framework.
•	Developed API endpoints.
2. Database & Models (Renuka Balaji Biradar - Database Designer)
•	Designed the task model (todoapp).
•	Configured Django migrations.
3. API Testing & Debugging (Vivek Jalindar Jadhav - API Tester)
•	Used Ninja API's Swagger UI to test endpoints.
•	Debugged request handling issues.
4. Authentication & Security (Aditya Ashok Jadhav - Security Expert)
•	Implemented user authentication .
•	Ensured API security.
5. Documentation & Report Writing (Pranjali Pandurang Bodke - Technical Writer)
•	Wrote API documentation.
•	Created this README file.
