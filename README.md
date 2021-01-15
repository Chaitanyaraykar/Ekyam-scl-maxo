
[![Python 3.6](https://img.shields.io/badge/python-3.6-yellow.svg)](https://www.python.org/downloads/release/python-360/)
![Django 3.0](https://img.shields.io/badge/Django-3.0-green.svg)
[![license](https://img.shields.io/github/license/DAVFoundation/captain-n3m0.svg?style=flat-square)]()
# L.C.R(Learn.Connect.Regulate)
This is an attempt to clone the best features of google classroom and educative.io using django.

## Installation

**1. Clone Repository & Install Packages**
```sh
git clone https://github.com/Chaitanyaraykar/Ekyam-scl-maxo.git
pip install -r requirements.txt
```
**2. Setup Environment**
```sh
python -m  venv venv
source venv/bin/activate
cd src
``````



**3. Migrate & Start Server**
```sh
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
