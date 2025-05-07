# 📝 To-Do List with Authentication

A full-featured To-Do List web application built with Django, incorporating user registration, login, logout, and complete CRUD (Create, Read, Update, Delete) functionalities. This project serves as a practical implementation of Django's authentication system and form handling.

---

## 🚀 Features

- **User Authentication**: Secure registration, login, and logout functionalities.
- **Task Management**:
  - Create new tasks.
  - View a list of existing tasks.
  - Update task details.
  - Delete tasks.
- **Search Functionality**: Easily search through tasks.
- **Responsive Design**: User-friendly interface compatible with various devices.

---

## 🛠️ Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS
- **Database**: SQLite (default Django database)

---

## 🖥️ Installation & Setup

Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Divyanshu1Dubey/To_Do_with_Auth.git
   cd To_Do_with_Auth
Create a Virtual Environment:

bash
Copy
Edit
python -m venv venv
Activate the Virtual Environment:

On Windows:

bash
Copy
Edit
venv\Scripts\activate
On macOS/Linux:

bash
Copy
Edit
source venv/bin/activate
Install Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Apply Migrations:

bash
Copy
Edit
python manage.py migrate
Run the Development Server:

bash
Copy
Edit
python manage.py runserver
Access the Application:

Open your web browser and navigate to http://127.0.0.1:8000/ to use the application.

📂 Project Structure
pgsql
Copy
Edit
To_Do_with_Auth/
├── manage.py
├── db.sqlite3
├── Pipfile
├── Pipfile.lock
├── todo_list/
│   ├── migrations/
│   ├── templates/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── base/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
└── README.md
✅ Usage
Register: Create a new user account.

Login: Access your personalized to-do list.

Add Tasks: Create new tasks to manage.

Edit Tasks: Update existing task details.

Delete Tasks: Remove tasks that are no longer needed.

Search Tasks: Use the search bar to find specific tasks.
