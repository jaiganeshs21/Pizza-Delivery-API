release: python3 manage.py migrate
web: gunicorn pizza.wsgi
web: python3 manage.py runserver 0.0.0.0:$PORT