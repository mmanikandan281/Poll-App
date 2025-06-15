# 🗳️ Django Poll App

**Django Poll App** is a feature-rich, user-authenticated polling platform built with Django. Users must register to view and vote in polls. Each user can vote only once per poll. Poll owners have full control to manage polls and choices—including creating, updating, deleting, and ending polls. Once a poll is ended, users can only view the final results.

✨ Features:

* User registration & login
* One vote per user per poll
* Poll management (CRUD) by owner
* Choice management
* Ended polls show results only
* Search & filter by name, publish date, vote count
* Pagination support even after filtering

---

## 🚀 Getting Started

These instructions will help you set up the project locally for development and testing.

### ✅ Prerequisites

```bash
Python >= 3.5  
Django >= 2.0
```

---

## 📦 Installation

### Clone the Repository

```bash
git clone https://github.com/mmanikandan281/Poll-App.git
cd Poll-App
```

### Database Setup

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create Superuser (for admin panel)

```bash
python manage.py createsuperuser
```

---

## 🧪 Optional: Create Dummy Data

```bash
pip install faker
python manage.py shell
>>> import seeder
>>> seeder.seed_all(30)
```

*(Change `30` to your desired number of entries)*

---

## ▶️ Run the Project

```bash
python manage.py runserver
```

Open your browser and go to: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🖼️ Project Snapshots

### 🔹 Home Page

![Home](https://user-images.githubusercontent.com/19981097/51409444-0e40a600-1b8c-11e9-9ab0-27d759db8973.jpg)

### 🔹 Login Page

![Login](https://user-images.githubusercontent.com/19981097/51409509-36c8a000-1b8c-11e9-845a-65b49262aa53.png)

### 🔹 Registration Page

![Register](https://user-images.githubusercontent.com/19981097/51409562-5cee4000-1b8c-11e9-82f6-1aa2df159528.png)

### 🔹 Poll List Page

![Polls](https://user-images.githubusercontent.com/19981097/51409728-d423d400-1b8c-11e9-8903-4c08ba64512e.png)

### 🔹 Add Poll Page

![Add Poll](https://user-images.githubusercontent.com/19981097/51409796-fe759180-1b8c-11e9-941b-c1202956cca4.png)

### 🔹 Polling Page

![Vote](https://user-images.githubusercontent.com/19981097/51409843-1e0cba00-1b8d-11e9-9109-cceb79a6a623.png)

### 🔹 Poll Result Page

![Results](https://user-images.githubusercontent.com/19981097/51409932-60ce9200-1b8d-11e9-9c83-c59ba498ca8b.png)

### 🔹 Poll Edit Page

![Edit Poll](https://user-images.githubusercontent.com/19981097/51410008-92dff400-1b8d-11e9-8172-c228e4b60e28.png)

### 🔹 Choice Update/Delete Page

![Choice](https://user-images.githubusercontent.com/19981097/51410442-dc7d0e80-1b8e-11e9-8f8e-18e6d7bb70fb.png)

---

## 👤 Author

> **Manikandan M**
> 📧 [mmanikandan281@gmail.com](mailto:mmanikandan281@gmail.com)

---

<div align="center">
  <h3>🎉 Thank you for checking out this project!</h3>
</div>


