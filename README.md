# django_pratice

CRUD rest API in Python using:
 
Django (Python framework)
Django Rest Framework (Django module for building rest APIs)
Postgres (relational database)
Docker (for containerization)
Docker Compose

This project is generated by django-admin CLI.
<ol>
  <ul>pip install django-admin-cli</ul>
  <ul>django-admin startproject django_pratice</ul>
  <ul>python manage.py startapp djangoapp</ul>
</ol>

BUILD:
<ol>
  <ul>docker-compose up -d db</ul>
  <ul>docker ps -a</ul>
  <ul>docker compose logs</ul>
  <ul>docker compose build</ul>
  <ul>docker compose up</ul>
</ol>

ENDPOINTS
localhost:8000/users/  <br/>
localhost:8000/users/read/{id} <br/>
localhost:8000/users/create <br/>
localhost:8000/users/update/{id} <br/>
localhost:8000/users/delete/{id} <br/>
