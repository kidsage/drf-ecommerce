# Packages

django  
python-dotenv==1.0.0  
djangorestframework==3.14.0  
pytest==7.4.0  
pytest-django==4.5.2  
django-mptt==0.14.0  

# Commands

django-admin startproject drfcommerce .

./manage.py runserver

from django.core.management.utils import get_random_secret_key

print(get_random_secret_key())

## Pytest

pytest - h   # prints options _and_ config file settings  