# 🎓 School Task Assignment Website

A full-stack web application built with **Django** for managing and assigning school tasks between administrators and teachers.  
The system provides role-based access, allowing admins to create and prioritize tasks while teachers can view and update their task statuses.

---

## 🚀 Features

- **Role-Based Access Control (RBAC):**
  - Admins can create, assign, and manage tasks.
  - Teachers can view and update their assigned tasks.
- **Task Priority System:** Tasks are categorized by priority level (High, Medium, Low).
- **User Authentication:** Secure login and registration using Django’s built-in authentication.
- **Responsive Frontend:** Designed using **HTML, CSS, JavaScript**, and **Bootstrap** for a clean and mobile-friendly interface.
- **AJAX Integration:** For asynchronous task updates and faster page interactions without reloads.
- **RESTful API:** Backend endpoints built using Django views and serializers.
- **Database Management:** SQLite used for structured data storage.

---

## 🛠️ Tech Stack

| Category | Technologies |
|-----------|--------------|
| **Frontend** | HTML5, CSS3, JavaScript, Bootstrap, AJAX |
| **Backend** | Django (Python) |
| **Database** | SQLite |
| **Version Control** | Git, GitHub |
| **Tools** | VS Code, Django Admin, Postman |

## 🚀 Installation & Setup

### 1. Clone the repository

git clone YOUR_REPOSITORY_URL

cd SchoolTaskAssignment/project

### 2. Create a virtual environment

python -m venv venv

### 3. Activate the virtual environment

**Windows:**

venv\Scripts\activate

**Linux / macOS:**

source venv/bin/activate

### 4. Install dependencies

pip install -r requirements.txt

### 5. Apply database migrations

python manage.py migrate

### 6. Run the development server

python manage.py runserver

Open your browser and visit:

http://127.0.0.1:8000/login
