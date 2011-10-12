web: bin/gunicorn_django --workers=4 --bind=0.0.0.0:$PORT  HelloDjango/settings.py
worker: bin/python HelloDjango/manage.py celeryd -E -B --loglevel=INFO
