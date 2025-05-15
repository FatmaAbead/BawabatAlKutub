release: python manage.py migrate
web: python manage.py collectstatic --no-input; gunicorn BawabatAlKutub.wsgi --log-file - --log-level debug