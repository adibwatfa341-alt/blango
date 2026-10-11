# blango

A Django blog with a REST API built with **Django REST Framework**.

## Features

- `Post` model (title, slug, summary, content, publish dates) registered in the Django admin
- REST API with serializers and views under `blog/api/`

## Stack

Python · Django · Django REST Framework

## Run it

```bash
pip install django djangorestframework
python manage.py migrate
python manage.py runserver
```
