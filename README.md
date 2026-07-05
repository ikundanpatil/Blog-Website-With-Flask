# 📝 Flask Blog Website

A modern **Blog Management System** built with **Flask**, **MySQL**, **SQLAlchemy**, **Bootstrap 5**, and **CKEditor**. This project demonstrates complete CRUD (Create, Read, Update, Delete) functionality with a clean and responsive user interface.

---

## 🚀 Demo

> **Live Demo:** *(Coming Soon)*

---

## 📸 Screenshots

> Add screenshots of your application inside a `screenshots/` folder.

### 🏠 Home Page
![Home](screenshots/home.png)

### 📖 Blog Post
![Blog](screenshots/post.png)

### ✍️ Create Post
![Create](screenshots/create-post.png)

### ✏️ Edit Post
![Edit](screenshots/edit-post.png)

---

# ✨ Features

- 📝 Create new blog posts
- 📖 View individual blog posts
- ✏️ Edit existing posts
- 🗑️ Delete posts
- 🖼️ Add image URL for each post
- 📝 Rich Text Editor (CKEditor)
- 📅 Automatic post date
- 💾 MySQL Database
- ⚡ SQLAlchemy ORM
- 🎨 Responsive Bootstrap 5 UI
- 🔄 Full CRUD Operations

---

# 🛠️ Built With

| Technology | Purpose |
|------------|---------|
| Python | Backend |
| Flask | Web Framework |
| SQLAlchemy | ORM |
| MySQL | Database |
| Bootstrap 5 | UI Framework |
| Flask-WTF | Forms |
| WTForms | Form Validation |
| CKEditor | Rich Text Editor |
| Jinja2 | Template Engine |

---

# 📂 Project Structure

```
Flask-Blog/
│
├── static/
│   ├── assets/
│   ├── css/
│   └── js/
│
├── templates/
│   ├── header.html
│   ├── footer.html
│   ├── index.html
│   ├── post.html
│   ├── make-post.html
│   ├── about.html
│   └── contact.html
│
├── screenshots/
│
├── .env.example
├── .gitignore
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/flask-blog.git
```

```bash
cd flask-blog
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

Create a `.env` file:

```env
SECRET_KEY=your_secret_key
DATABASE_URL=mysql+mysqlconnector://username:password@localhost/posts
```

Example:

```env
SECRET_KEY=your_super_secret_key
DATABASE_URL=mysql+mysqlconnector://root:password@localhost/posts
```

---

## 6️⃣ Run the Project

```bash
python app.py
```

Open your browser:

```
http://127.0.0.1:5003/
```

---

# 📚 Learning Outcomes

This project helped me learn:

- Flask Routing
- Template Inheritance
- Jinja2
- SQLAlchemy ORM
- CRUD Operations
- WTForms
- Flask-WTF
- CKEditor Integration
- Bootstrap 5
- MySQL Database
- MVC Design Pattern
- Debugging Flask Applications

---

# 🚧 Future Improvements

I plan to add the following features:

- 🔐 User Authentication (Login & Signup)
- 👤 User Roles (Admin & User)
- 💬 Comment System
- ❤️ Like & Bookmark Posts
- 🔍 Search Functionality
- 🏷️ Categories & Tags
- 📄 Pagination
- 🌙 Dark Mode
- 📧 Contact Form with Email
- 📤 Image Upload Instead of URL
- 📊 Dashboard for Admin
- ☁️ Deploy on Render/Railway
- 🐳 Docker Support
- 🧪 Unit Tests
- 🔒 Environment Variables using `.env`
- 📱 Mobile UI Improvements
- ⚡ Better Error Handling (404 & 500 Pages)

---

# 🔒 Security Improvements

- Store credentials using Environment Variables
- Never upload `.env`
- Use `.gitignore`
- Hide Secret Key
- Hide Database Password

---

# 📋 TODO

- [x] Create Blog
- [x] Read Blog
- [x] Update Blog
- [x] Delete Blog
- [x] CKEditor Integration
- [x] MySQL Integration
- [ ] User Authentication
- [ ] Search Feature
- [ ] Categories
- [ ] Pagination
- [ ] Deployment

---

# 👨‍💻 Author

## Kundan Patil

BCA (Data Science & Machine Learning)

### Skills

- Python
- Flask
- SQL
- MySQL
- HTML
- CSS
- JavaScript
- Bootstrap
- SQLAlchemy
- Git & GitHub

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# ⭐ Show Your Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

---

# 📄 License

This project is licensed under the MIT License.

---

## 📧 Contact

**GitHub:** https://github.com/your-username

**LinkedIn:** https://linkedin.com/in/your-profile *(optional)*

**Email:** your-email@example.com *(optional)*
