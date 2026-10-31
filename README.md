# Flask Blog Platform ✍️

A full-stack blog application built with Flask, SQLite, and SQLAlchemy. It allows users to create, view, edit, and delete blog posts through a Bootstrap-based web interface.

## Features

- Displays all published blog posts.
- Individual blog post pages.
- Create new blog posts.
- Edit existing blog posts.
- Delete blog posts.
- SQLite database integration.
- Rich-text blog content editor using CKEditor.
- Form handling and validation using Flask-WTF and WTForms.
- Responsive interface using Bootstrap.

## Tech Stack

- Python
- Flask
- Flask-Bootstrap
- Flask-SQLAlchemy
- SQLAlchemy
- SQLite
- Flask-WTF
- WTForms
- Flask-CKEditor
- HTML / CSS / JavaScript

## Getting Started

### Prerequisites

- Python 3.x
- pip

### Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/flask-blog-platform.git
cd flask-blog-platform
```

Create and activate a virtual environment:

```bash
python -m venv venv
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### Configure the application

Set a secure Flask secret key using an environment variable. Update the application configuration to read this value instead of using a hardcoded secret.

Example:

```python
import os

app.config["SECRET_KEY"] = os.environ["SECRET_KEY"]
```

Set the variable before starting the application.

### Run the application

```bash
python main.py
```

Open:

```text
http://127.0.0.1:5003
```

The SQLite database is initialized by the application when it starts.

## Project Structure

```text
flask-blog-platform/
├── main.py
├── requirements.txt
├── templates/
│   ├── header.html
│   ├── footer.html
│   ├── index.html
│   ├── post.html
│   ├── make-post.html
│   ├── about.html
│   └── contact.html
├── static/
│   ├── css/
│   ├── js/
│   └── assets/
└── README.md
```

## What I Learned

- Building web applications with Flask.
- Creating database models using SQLAlchemy ORM.
- Implementing CRUD operations.
- Handling web forms using Flask-WTF.
- Integrating rich-text editing with CKEditor.
- Using Jinja templates to render dynamic content.
- Managing application routes and database operations.

## Current Limitations

- The contact page currently displays a form but does not implement message delivery.
- Authentication and role-based access control are not implemented.
- The application is intended as an educational project and requires additional security hardening before public production use.

---

A practical full-stack development project exploring backend engineering, database management, and dynamic web applications.
