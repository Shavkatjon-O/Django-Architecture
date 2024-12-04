```
.
├── apps
│   ├── common
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── __init__.py
│   │   ├── migrations
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   ├── tests.py
│   │   └── views.py
│   ├── __init__.py
│   └── users
│       ├── admin.py
│       ├── apps.py
│       ├── __init__.py
│       ├── migrations
│       │   └── __init__.py
│       ├── models.py
│       ├── tests.py
│       └── views.py
├── bin
│   └── setup.sh
├── compose
│   └── django
│       └── Dockerfile
├── core
│   ├── asgi.py
│   ├── __init__.py
│   ├── mixins.py
│   ├── settings
│   │   ├── base.py
│   │   ├── develop.py
│   │   ├── __init__.py
│   │   └── production.py
│   ├── urls.py
│   └── wsgi.py
├── docker-compose-develop.yml
├── docker-compose-production.yml
├── gunicorn_conf.py
├── LICENSE
├── Makefile
├── manage.py
├── README.md
├── requirements
│   ├── base.txt
│   ├── develop.txt
│   └── production.txt
├── services
│   └── __init__.py
└── utils
    └── __init__.py
```