web: gunicorn fakeCSV.wsgi --log-file -
worker: celery -A fakeCSV worker -l info