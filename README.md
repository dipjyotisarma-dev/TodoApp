# TodoApp

A simple Todo application built with **FastAPI** featuring user authentication and CRUD operations.

## Tech Stack

- FastAPI
- SQLAlchemy
- SQLite
- Jinja2
- HTML, CSS, JavaScript

## Run Locally

```bash
git clone https://github.com/<your-username>/TodoApp.git
cd TodoApp
pip install -r requirements.txt
```

Create a `.env` file:

```env
SECRET_KEY=your_secret_key
ALGORITHM=HS256
```

Run the application:

```bash
uvicorn main:app --reload
```

## Live Demo

https://todoapp-iqut.onrender.com