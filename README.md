# Django User Form

A simple Django project that demonstrates how to create, display, and process user input forms using Django’s built-in forms framework.

This project is intended for learning and practicing:
- Django forms
- Handling GET and POST requests
- Basic project structure
- Environment variable configuration

---

## 📂 Project Structure

```text
django-userform/
├── BlogProject/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
├── BlogPost/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── .env
├── .gitignore
├── manage.py
└── README.md

### ⚙️ Requirements
- Python 3.10 or higher  
- Django 5.x  
- pip (Python package manager)

---

### 🧪 How It Works
- Users submit data through a Django form  
- The server validates the input  
- Valid data is processed or prepared for storage  
- Invalid submissions are returned with error messages


### 🔐 Security Considerations
- Sensitive settings such as `SECRET_KEY` are loaded from environment variables  
- `.env` files are excluded from version control using `.gitignore`  
- `DEBUG` should always be set to `False` in production  
- `ALLOWED_HOSTS` must be configured correctly before deployment  

These practices align with Django’s recommended production setup.

---

### 📚 Learning Resources
- Django Forms Documentation  
  https://docs.djangoproject.com/en/stable/topics/forms/
