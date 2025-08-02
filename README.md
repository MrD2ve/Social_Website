# Social_Website
# 👥 Django Social Image Sharing Platform

A feature-rich Django project where users can **register, log in, manage profiles**, and **share images socially**.  
This stage of the project focuses on **user account management** and prepares the foundation for full social interaction in the next stages.

---

## ✨ New Features

The current build includes:

- 🔐 User registration, login/logout, and profile management
- 🔑 Password change and reset functionality
- 🧾 Custom user profile model extension
- 📥 Media file upload configuration
- 📢 Flash messages using Django’s messages framework
- 🛡️ Custom authentication backend
- ❌ Duplicate email prevention

---

## 🚀 Getting Started

Follow these steps to get the project running locally:

```bash
# 1️⃣ Clone the repository
git clone https://github.com/your-username/django-social-app.git
cd django-social-app

# 2️⃣ Create and activate a virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Apply migrations
python manage.py makemigrations
python manage.py migrate

# 5️⃣ Create a superuser (optional but useful)
python manage.py createsuperuser

# 6️⃣ Run the development server
python manage.py runserver
```

---

## 📄 License

This project is licensed under the MIT License.
