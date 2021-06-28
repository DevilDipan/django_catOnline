 ![catOnline](https://github.com/indusOnline/catOnline/blob/master/images/logo.png) <br>

# Index
1. [Setup Guide](#setup-guide)
2. [Requirements](#requirements)
3. [Dependencies](#dependencies)
4. [Tips](#tips)
   - [Django in Proxy](#django-in-proxy)
   - [Runserver Port](#runserver-port)

## Setup Guide
To setup this up you need to follow [this](https://github.com/indusOnline/catOnline_backend/blob/master/Setup.md)

## Requirements
1. Python 3.7.3
2. Django 2.2.2

## Dependencies
Get the [requirements.txt](https://github.com/indusOnline/catOnline_backend/blob/master/Requirements.txt) file
```python
pip install requirements.txt
```

## Tips
### Django in Proxy
Install Django in proxy based systems
```python
pip install --proxy http://user:password@proxyserver:port Django
```

### Runserver Port
To use runserver on a different port
```python
python manage.py runserver ip:port
```

## Licensing
### This is under GNU Affero General Public License v3.0
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://github.com/indusOnline/catOnline_backend/blob/master/LICENSE)
