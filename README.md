# 📰 Django Newspaper App

Welcome to my Django Newspaper App! This is a simple yet powerful web app where users can create, read, update, and delete news articles. It comes with user authentication and permission-based access — all built using Django.

This project is based on the *Django for Beginners* book by William S. Vincent, which I followed to strengthen my web development and backend skills.

---

## 🌟 What It Does

- Users can **sign up**, **log in**, and manage their own articles
- Admins can **edit and delete** any article
- Clean, responsive design with **Bootstrap**
- Easy-to-use **admin dashboard** for managing content
- Uses Django’s built-in **auth system** and template engine

---

## 🧰 Tech Used

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite (local setup)
- **Extras:** Django Admin, Django Auth, Crispy Forms

---

## 🚀 Getting Started

Here’s how to run it locally:

```bash
# Clone the project
git clone https://github.com/yourusername/django-newspaper-app.git
cd django-newspaper-app

# Set up virtual environment
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create a superuser (for admin access)
python manage.py createsuperuser

# Start the server
python manage.py runserver
