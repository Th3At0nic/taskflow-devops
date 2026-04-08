# TaskFlow DevOps

A production-ready task management web application built with Django and deployed on cloud infrastructure. This project demonstrates full-stack development along with deployment and DevOps practices.

---

## 🌐 Live Demo

👉 https://taskflow-devops-7vk3.onrender.com/

---------------

## 📌 Overview

TaskFlow DevOps is a Todo/task management system designed to showcase:

* Backend development using Django
* Clean project structure and modular design
* Cloud deployment using Render
* Production-ready configurations (Gunicorn, environment-based setup)

---------------


## ✨ Features

* ✅ Create, Read, Update, and Delete tasks
* ✅ Mark tasks as completed/active
* ✅ Filter tasks by status (All, Active, Completed)
* ✅ Add due dates and descriptions
* ✅ Responsive UI with Tailwind CSS
* ✅ AJAX-based task status toggle
* ✅ Django messages framework for feedback

-----------------

## 🧰 Tech Stack

* **Backend**: Python + Django
* **Frontend**: Django Templates + Tailwind CSS
* **Database**: SQLite (development), easily replaceable with PostgreSQL
* **Server**: Gunicorn (production)
* **Deployment**: Render

---------------

## ⚙️ Deployment Highlights

This project includes:

* 🚀 Cloud deployment on Render
* 🔒 Host validation via `ALLOWED_HOSTS`
* 🌐 Public port binding (`0.0.0.0:$PORT`)
* ⚡ Production server using Gunicorn
* 📦 Dependency management via `requirements.txt`

----------------

## 🛠️ Local Setup

### Prerequisites

* Python 3.8+
* pip

-------------

### Installation

```bash
git clone https://github.com/Th3At0nic/taskflow-devops.git
cd taskflow-devops
```

```bash
python3 -m venv venv
source venv/bin/activate
```

```bash
pip install -r requirements.txt
```

```bash
python manage.py migrate
```

```bash
python manage.py runserver
```

---

### Access locally:

```
http://127.0.0.1:8000/
```

---

## 🏗️ Project Structure

```
todo_project/
├── manage.py
├── requirements.txt
├── todo_project/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
├── tasks/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
├── templates/
```

---

## 🧪 Running Tests

```bash
python manage.py test
```

---

## 📈 Future Improvements

* 🔄 Switch to PostgreSQL for production database
* 🔐 Add authentication (login/signup)
* 📡 REST API with Django REST Framework
* 🐳 Dockerize the application
* ⚙️ CI/CD pipeline (GitHub Actions)

---

## 📄 License

This project is open source and intended for learning and demonstration purposes.
