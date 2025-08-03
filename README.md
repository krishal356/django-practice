# KrishalPortfolio - Django Personal Portfolio Website

This is a **clean and simple Django-based portfolio website** created by **Krishal**. It showcases the fundamentals of Django such as templates, static files, views, and URL routing — all wrapped in a responsive and modular structure.

---

## 🚀 Features

* Homepage with typing animation effect
* Modular Django project structure
* Static files for CSS and JS
* Clean UI ready for customization
* Easy to expand with About, Projects, Contact pages

---

## 🗂️ Project Structure
```
Django\ krishal/
├── manage.py
├── db.sqlite3
├── krishal_site/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── portfolio/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   ├── migrations/
│   │   └── __init__.py
│   ├── static/
│   │   └── portfolio/
│   │       ├── css/
│   │       │   └── style.css
│   │       └── js/
│   │           └── script.js
│   └── templates/
│       └── portfolio/
│           └── home.html
```

---

## ⚙️ Installation

```bash
# Step 1: Clone this repo
git clone https://github.com/krishal356/django-practice.git
cd django-practice

# Step 2: (Optional) Create virtual environment
python -m venv env
# Activate it
# On Windows:
env\Scripts\activate
# On macOS/Linux:
source env/bin/activate

# Step 3: Install Django
pip install django

# Step 4: Run the development server
python manage.py runserver

# Step 5: Open in your browser
http://127.0.0.1:8000/
```
---

## 🧩 Customization

- Edit `home.html` inside `portfolio/templates/portfolio/` to personalize content  
- Add styling in `static/portfolio/css/style.css`  
- Add new pages in `portfolio/views.py` and map them in `urls.py`  
- Use Django’s admin panel for content management (after configuring models)

---

## 📄 License

This project is open-source and available under the **MIT License**.
