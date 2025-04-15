# Django REST Tutorial

This repository contains a simple project that follows the official [Django REST Framework tutorial](https://www.django-rest-framework.org/tutorial/quickstart/). It's intended as a learning resource to understand the fundamentals of building APIs using Django and the Django REST Framework (DRF).

## Features

- Django project setup with REST framework integration
- Basic CRUD API for code snippets
- Token-based authentication
- Permissions and ownership logic
- DRF's browsable API for interactive exploration

## Project Structure
```plaintext
django-rest-tutorial/ 
├── manage.py 
├── snippets/ # Contains models, serializers, views, URLs 
├── tutorial/ # Project settings and configuration 
└── requirements.txt
```


## Getting Started

To get the project up and running locally:

1. **Clone the repository**

```bash
git clone https://github.com/lorainemg/django-rest-tutorial.git
cd django-rest-tutorial
```

2. **Create and activate a virtual environment**
```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Apply migrations**

```bash
python manage.py migrate
```

5. **Create a superuser (optional)**

```bash
python manage.py createsuperuser
```

6. **Run the development server**

```bash
python manage.py runserver
```

Access the API at: http://localhost:8000/

## Useful Links

- [Django REST Framework](https://www.django-rest-framework.org)
- [Official DRF Tutorial](https://www.django-rest-framework.org/tutorial/quickstart/)