stunnel: stunnel extras/stunnel.cnf
web: env PYTHONUNBUFFERED=true python manage.py runserver
ssl: env PYTHONUNBUFFERED=true HTTPS=1 python manage.py runserver 8001
worker: env PYTHONUNBUFFERED=true celery worker -A mailme -l INFO
compass: compass watch
