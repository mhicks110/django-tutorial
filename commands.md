# Packages
asgiref==3.8.1
colorama==0.4.6
Django==5.0.6
djangorestframework==3.15.1
iniconfig==2.0.0
packaging==24.0
pluggy==1.5.0
pytest==8.2.0
pytest-django==4.8.0
python-dotenv==1.0.1
sqlparse==0.5.0
tzdata==2024.1

# Commands
django-admin startproject drfcommerce
./manage.py runserver
py manage.py shell

pip install -r requirements.txt

from django.core.amangement.utils import get_random_secret_key
print_r(get_random_secret_key())
exit()

## Pytest
pytest - h # prints options _an_ config file settings