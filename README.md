# 🚀 Flask Blog Website

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-3.x-black?logo=flask)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange?logo=mysql)
![SQLAlchemy](https://img.shields.io/badge/ORM-SQLAlchemy-red)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?logo=bootstrap)
![License](https://img.shields.io/badge/License-MIT-green)

A modern **Flask Blog Management System** built with **Flask, MySQL, SQLAlchemy, Bootstrap 5, Flask-Login, Flask-WTF, and CKEditor**.

This project demonstrates full-stack web development by implementing authentication, database management, and complete CRUD operations with a clean and responsive user interface.

---

## ✨ Features

### 📝 Blog Management
- Create, Read, Update & Delete (CRUD) blog posts
- Rich text editor using CKEditor
- Upload blog images using URLs
- Automatic post date generation
- Responsive blog layout

### 👤 User Authentication
- User Registration
- Secure Login & Logout
- Password Hashing
- Session Management using Flask-Login
- Protected Routes

### 💾 Database
- MySQL Database
- SQLAlchemy ORM
- Relational Database Models
- Environment Variable Configuration

### 🎨 Frontend
- Bootstrap 5 Responsive UI
- Jinja2 Template Engine
- Custom CSS
- Responsive Navigation
- Modern Layout

---

# 📸 Screenshots

> Add screenshots here

```
static/screenshots/

home.png
login.png
register.png
create-post.png
post.png
```

---

# 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| Framework | Flask |
| Database | MySQL |
| ORM | SQLAlchemy |
| Authentication | Flask-Login |
| Forms | Flask-WTF |
| Rich Text Editor | CKEditor |
| Frontend | HTML5, CSS3, Bootstrap 5 |
| Template Engine | Jinja2 |

---

# 📁 Project Structure

```text
Blog-Website-With-Flask/
│
├── static/
│   ├── assets/
│   ├── css/
│   ├── js/
│   └── screenshots/
│
├── templates/
│   ├── about.html
│   ├── contact.html
│   ├── footer.html
│   ├── header.html
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── make-post.html
│   └── post.html
│
├── forms.py
├── main.py
├── requirements.txt
├── .env.example
├── README.md
└── LICENSE
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/ikundanpatil/Blog-Website-With-Flask.git

cd Blog-Website-With-Flask
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv

venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Create MySQL Database

```sql
CREATE DATABASE posts;
```

---

## 5️⃣ Configure Environment Variables

Create a file named **.env**

```env
SECRET_KEY=your_secret_key

DATABASE_URL=mysql+mysqlconnector://username:password@localhost/posts
```

---

## 6️⃣ Run the Application

```bash
python main.py
```

Visit:

```
http://127.0.0.1:5002
```

---

# 🔐 Environment Variables

| Variable | Description |
|----------|-------------|
| SECRET_KEY | Flask Secret Key |
| DATABASE_URL | MySQL Connection URL |

---

# 📚 Learning Outcomes

Through this project I learned:

- Flask Routing
- Flask Application Structure
- SQLAlchemy ORM
- MySQL Integration
- User Authentication
- Password Hashing
- Session Management
- CRUD Operations
- Flask-WTF Forms
- CKEditor Integration
- Bootstrap 5
- Jinja2 Templates
- Environment Variables
- Git & GitHub

---

# 🚀 Future Improvements

- User Profile Page
- Upload Images Instead of URLs
- Blog Categories
- Search Functionality
- Comments System
- Like & Bookmark Posts
- Admin Dashboard
- Pagination
- REST API
- Dark Mode

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 👨‍💻 Author

## Kundan Patil

**BCA (Data Science & Machine Learning)**

Passionate about Python, Flask, AI/ML, Data Science, Full-Stack Development, and Backend Engineering.

### Connect with Me

- GitHub: https://github.com/ikundanpatil
- LinkedIn: https://www.linkedin.com/in/YOUR-LINKEDIN

---

# 📄 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

It motivates me to build more open-source projects.

Happy Coding! 🚀
