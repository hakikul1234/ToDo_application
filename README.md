# 📝 Task Manager (Flask Web App)

A simple and clean **Task Manager Web Application** built using Flask and SQLAlchemy.
This app allows users to **add, update, and delete tasks** easily with a user-friendly interface.

---

## 🚀 Features

* ✅ Add new tasks
* 📝 Update existing tasks
* ❌ Delete tasks
* 📅 Automatic date tracking
* 🎨 Clean and responsive UI using CSS
* ⚡ Fast and lightweight Flask backend

---

## 🛠️ Tech Stack

* **Backend:** Python (Flask)
* **Database:** SQLite (SQLAlchemy ORM)
* **Frontend:** HTML, CSS (Jinja Templates)

---

## 📁 Project Structure

```
task_manager/
│
├── main.py
├── tasks.db
├── requirements.txt
├── Procfile
├── static/
│   └── css/
│       └── main.css
└── templates/
    ├── base.html
    ├── index.html
    └── update.html
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/yourusername/task_manager.git
cd task_manager
```

---

### 2️⃣ Create virtual environment

```
python -m venv env
env\Scripts\activate   # Windows
```

---

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

### 4️⃣ Create database

```
python
>>> from main import app, db
>>> with app.app_context():
...     db.create_all()
```

---

### 5️⃣ Run the app

```
python main.py
```

Open in browser:

```
http://127.0.0.1:5000
```

---

## 🌐 Deployment

This project can be deployed on platforms like:

* Render
* Heroku
* Railway

### Example (Render)

* Add `Procfile`
* Use `gunicorn main:app`
* Push to GitHub and connect to Render

---

## ⚠️ Notes

* SQLite is used for development
* For production, use PostgreSQL or another database
* Debug mode should be OFF in production

---

## 📸 Screenshots

(Add your project screenshots here)

---

## 💡 Future Improvements

* ✔ Task completion checkbox
* 🔍 Search functionality
* 🔐 User authentication (Login/Signup)
* 🌙 Dark mode UI
* 📱 Mobile responsive improvements

---

## 🤝 Contributing

Feel free to fork this project and improve it!
Pull requests are welcome.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgement

Built as a beginner-friendly project to learn:

* Flask
* CRUD operations
* Web development basics

---

⭐ If you like this project, give it a star on GitHub!
