# Flask Blog Website

A modern and responsive **Blog Management System** built with **Flask**, **MySQL**, **SQLAlchemy**, **Bootstrap 5**, and **CKEditor**. The application provides complete CRUD functionality for managing blog posts through an intuitive user interface.

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-3.x-000000?style=for-the-badge&logo=flask)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap)
![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)

</p>

---

## Overview

This project demonstrates how to build a full-stack web application using Flask and SQLAlchemy while implementing complete CRUD (Create, Read, Update, Delete) functionality.

Users can:

- Create blog posts
- View blog posts
- Edit existing posts
- Delete posts
- Write rich-text content using CKEditor
- Store data in a MySQL database

The project was built as part of my Flask learning journey and focuses on clean architecture, responsive UI, and backend development.

---

# Features

- Full CRUD operations
- Responsive Bootstrap 5 interface
- Rich Text Editor (CKEditor)
- MySQL database integration
- SQLAlchemy ORM
- WTForms validation
- Dynamic Jinja2 templates
- Automatic post date generation
- Image support using URLs
- Modular Flask project structure

---

# Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| Framework | Flask |
| Database | MySQL |
| ORM | SQLAlchemy |
| Forms | Flask-WTF |
| Rich Text | CKEditor |
| Frontend | HTML5, CSS3, Bootstrap 5 |
| Template Engine | Jinja2 |

---

# Project Structure

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
│   ├── make-post.html
│   └── post.html
│
├── app.py
├── requirements.txt
├── .env.example
├── README.md
└── LICENSE
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/ikundanpatil/Blog-Website-With-Flask.git

cd Blog-Website-With-Flask
```

---

## Create Virtual Environment

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

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Create Database

```sql
CREATE DATABASE posts;
```

---

## Configure Environment Variables

Create a file named `.env`

```env
SECRET_KEY=your_secret_key

DATABASE_URL=mysql+mysqlconnector://username:password@localhost/posts
```

---

## Run Application

```bash
python app.py
```

Open your browser:

```
http://127.0.0.1:5003
```

---

# Environment Variables

| Variable | Description |
|----------|-------------|
| SECRET_KEY | Flask Secret Key |
| DATABASE_URL | MySQL Database URL |

---

# Learning Outcomes

Through this project, I gained hands-on experience with:

- Flask routing
- SQLAlchemy ORM
- MySQL integration
- CRUD operations
- WTForms
- CKEditor
- Jinja2 Templates
- Bootstrap 5
- Environment Variables
- Git & GitHub

---

# Contributing

Contributions are welcome.

1. Fork the repository

2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# Author

**Kundan Patil**

BCA (Data Science & Machine Learning)

Passionate about Python, Flask, AI/ML, Data Science, and Full Stack Development.

### Connect with me

- GitHub: https://github.com/ikundanpatil
- LinkedIn: *Add your LinkedIn profile*

---

# License

This project is licensed under the MIT License.

---

## Show your support

If you found this project useful, consider giving it a ⭐ on GitHub.
