# 💬 Django Based Chat App

A real-time chat application built with Django and WebSockets. This project allows users to communicate instantly using WebSocket technology, and supports basic user relations like friend connections.

## ✨ Features

- 👤 User registration and login
- ⚡ Real-time messaging using Django Channels
- 🤝 Friend relationships between users
- 🔗 REST API endpoints with Django REST Framework
- 🖥️ Responsive UI with HTML/CSS (from the templates directory)

## 🗂️ Project Structure

```
Django based Chat App/
├── app1/                  # Core chat functionality
│   ├── models.py          # Database models
│   ├── views.py           # REST API views
│   ├── consumers.py       # WebSocket consumers
│   ├── serializers.py     # Serializers for API
│   ├── routing.py         # WebSocket routing
│   └── migrations/        # Django migrations
├── static/                # Static files (CSS, JS)
├── templates/             # HTML templates
├── manage.py              # Django CLI utility
├── db.sqlite3             # SQLite database
├── requirements.txt       # Python dependencies
```

## 🛠️ Installation

### 📋 Prerequisites

- 🐍 Python 3.8+
- 📦 pip (Python package manager)

### 🚀 Setup Instructions

```bash
# Clone the repository or extract the zip
cd "Django based Chat App"

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver
```

## 🧪 Usage

- 🌐 Navigate to `http://127.0.0.1:8000/` to access the app
- 🔐 Register or log in
- 💬 Add friends and start chatting in real-time

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

**Developed with ❤️ using Django.**
