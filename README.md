Notes App (Django + React) 

What it does

Register & login (JWT)

Create notes, list notes, delete notes

Stack

Backend: Python, Django, Django REST Framework, SimpleJWT

DB: SQLite (dev) / PostgreSQL (prod)

Frontend: React (Vite), Axios, HTML/CSS

Config

Backend uses backend/.env (e.g. SECRET_KEY, DJANGO_DB, DB_*)

Frontend uses frontend/.env (VITE_API_URL=http://127.0.0.1:8000)
