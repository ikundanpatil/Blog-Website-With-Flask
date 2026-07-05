# Flask Blog

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.x-blue.svg)

A blog management system built with Flask, MySQL, SQLAlchemy, Bootstrap 5, and CKEditor. Full CRUD for blog posts, with a rich text editor and a responsive UI.

## Contents

- [Features](#features)
- [Built With](#built-with)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- Create, read, update, and delete blog posts
- Rich text editing via CKEditor
- Image support via URL
- Automatic post timestamps
- MySQL persistence through SQLAlchemy ORM
- Responsive Bootstrap 5 layout

---

## Built With

| Technology | Purpose |
|------------|---------|
| Python | Backend |
| Flask | Web framework |
| SQLAlchemy | ORM |
| MySQL | Database |
| Bootstrap 5 | UI framework |
| Flask-WTF / WTForms | Forms and validation |
| CKEditor | Rich text editor |
| Jinja2 | Templating |

---

## Project Structure

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
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/flask-blog.git
cd flask-blog
```

### 2. Create a virtual environment

**Windows**
```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Create the MySQL database

```sql
CREATE DATABASE posts;
```

### 5. Configure the database connection

Config is hardcoded in `app.py` — no `.env` support yet (tracked in [Roadmap](#roadmap)). Open `app.py` and set the database URI and secret key to match your local MySQL credentials.

### 6. Run the app

```bash
python app.py
```

Then open `http://127.0.0.1:5003/` in your browser.

---

## Roadmap

Ordered by what unblocks the most other work:

- [ ] Load config (`SECRET_KEY`, database URI) from a `.env` file instead of hardcoding in `app.py`
- [ ] User authentication (login/signup) and roles (admin/user)
- [ ] Image upload instead of image-by-URL
- [ ] Pagination
- [ ] Search
- [ ] Categories/tags
- [ ] Comment system
- [ ] Custom 404/500 error pages
- [ ] Unit tests
- [ ] Docker support
- [ ] Deployment (Render/Railway)

---

## Contributing

1. Fork the repo
2. Create a feature branch: `git checkout -b feature-name`
3. Commit: `git commit -m "Add feature"`
4. Push: `git push origin feature-name`
5. Open a pull request

If you're picking up a Roadmap item, mention it in the PR description so effort doesn't overlap.

---

## License

MIT License.
