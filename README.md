# How to Use Chart.js with Django

[![Python Version](https://img.shields.io/badge/python-3.7-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/django-3.0-brightgreen.svg)](https://djangoproject.com)


## Running the Project Locally

First, clone the repository to your local machine:

```bash
https://github.com/julioat2018/django_charts.git
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Apply the migrations:

```bash
python manage.py migrate
```

Load the data from fixtures:

```bash
python manage.py loaddata countries.json cities.json
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000**.
