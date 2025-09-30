# Python & Django CRM REST API
A simple CRM (Customer Relationship Management) REST API built with Django and Django REST Framework.

## Features
- Manage Accounts, Contacts, Activities, Activity Statuses, Contact Sources, and Contact Statuses
- RESTful API endpoints for all major CRM entities
- CORS support for cross-origin requests

## Requirements
- Python 3.8+
- Django 2.1+
- Django REST Framework
- django-cors-headers

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/krishnasaner/DjangoCRM-.git
cd DjangoCRM-
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Apply migrations
```bash
python manage.py migrate
```

### 4. Run the development server
```bash
python manage.py runserver
```

The API will be available at `http://localhost:8000/`

## API Endpoints
| Endpoint                | Description                |
|------------------------|----------------------------|
| `/accounts`            | List/Create Accounts       |
| `/contacts`            | List/Create Contacts       |
| `/activities`          | List/Create Activities     |
| `/activitystatuses`    | List Activity Statuses     |
| `/contactsources`      | List Contact Sources       |
| `/contactstatuses`     | List Contact Statuses      |
| `/admin/`              | Django Admin Panel         |

## Notes
- There is no homepage; access the API endpoints directly.
- You can use tools like Postman or curl to interact with the API.

You can find more details of how we created this REST API from this [tutorial](https://www.techiediaries.com/django-tutorial).
