web: bin/start-nginx gunicorn -c gunicorn.conf {{ project_name }}.wsgi:application
release: python manage.py migrate
