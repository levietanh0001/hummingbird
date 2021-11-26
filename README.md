# Humming Bird Ecommerce Web Application - OOAD 2021

Installation
---

Clone project into your local system
```bat
git clone https://github.com/vietanh2000april/hummingbird.git
```

Change into project directory
```cmd
cd hummingbird
```

Activate virutal environment
```cmd
oscar\Scripts\activate
```

Install required modules
```cmd
pip install -r requirements.txt
```

Create admin user (optional)
```cmd
python manage.py createsuperuser
```

Migrate changes
```cmd
python manage.py migrate
```

Run server in localhost:8000
```cmd
python manage.py runserver
```

Admin List
---
1. **user**: admin, **email**: admin@gmail.com, **password**: admin
2. **user**: lva, **email**: vietanh2000april@gmail.com, **password**: 123321
