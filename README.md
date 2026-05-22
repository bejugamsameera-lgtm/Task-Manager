# Flask Mini Project – Task Manager

## 📌 Project Overview
This is a simple **Task Manager Web Application** built using Python and Flask.  
It demonstrates backend fundamentals like routing, form handling, and CRUD operations with a clean UI.

---

## 🎯 Features
- Add new tasks
- View all tasks
- Edit tasks
- Delete tasks
- Form handling (GET & POST)
- Data stored in JSON file
- Simple UI with Bootstrap

---

## 🛠️ Technologies Used
- Python
- Flask
- HTML
- Bootstrap
- JSON

---

## 📁 Project Structure

```
flask-task-manager/
│── app.py
│── tasks.json
│── requirements.txt
│
├── templates/
│   ├── index.html
│   └── edit.html
│
├── static/
│   └── style.css
│
└── README.md
```

---

## 🚀 Installation & Setup

### 1. Install Python
Download from:
https://www.python.org/downloads/

---

### 2. Clone Repository
```bash
git clone <your-repo-link>
cd flask-task-manager
```

---

### 3. Install Flask
```bash
python -m pip install flask
```

---

### 4. Create Requirements File
Generate `requirements.txt` using:

```bash
python -m pip freeze > requirements.txt
```

---

### 5. Run Application
```bash
python app.py
```

---

### 6. Open in Browser
```
http://127.0.0.1:5000/
```

---

## 📌 How It Works
- User enters task in form
- Data is stored in `tasks.json`
- Flask renders tasks dynamically
- User can edit or delete tasks

---


---

## 🎯 Learning Outcomes
- Flask routing
- Form handling (GET & POST)
- CRUD operations
- JSON file handling
- Backend + frontend integration

---

---

## 👨‍💻 Author
Bejugam Sameera


---
git init
git add .
git commit -m "Task-Manager"
git branch -M main
git remote add origin https://github.com/bejugamsameera-lgtm/Task-Manager.git
git push -u origin main