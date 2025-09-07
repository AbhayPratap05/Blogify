# 📝 Blogger Clone (Django)

A simple blogging platform built with **Django**, where users can register, log in, create posts (text + photo), edit, and delete them.  
This project was created while learning Django and covers the basics of authentication and CRUD operations.

---

## 🚀 Features

- User Registration & Login (Django’s built-in auth system)
- User Logout
- Create new blog posts (with text + optional image)
- Edit and Delete posts
- View all posts from all users
- Django Admin panel for managing users & posts

---

## Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/blogger-clone.git
   cd blogger-clone
   ```
2. **Create & activate a virtual environment**

   ```
   python -m venv venv
   source venv/bin/activate   # On macOS/Linux
   ```

3. **Install dependencies**

   ```
   pip install -r requirements.txt
   ```

4. **Run migrations**

   ```
   python manage.py migrate
   ```

5. **Create a superuser (for admin access)**

   ```
   python manage.py createsuperuser
   ```

6. **Start the development server**

   ```
   python manage.py runserver
   ```

7. **Open in browser:**
   ```
   http://127.0.0.1:8000/
   ```

## Tech Stack

- Backend: Django (Python)

- Database: SQLite (default, can be switched to PostgreSQL/MySQL)

- Frontend: HTML, Tailwind CSS

- Authentication: Django’s built-in auth system
