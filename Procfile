web: gunicorn config.wsgi:application
worker: newrelic-admin run-program celery worker --app=base_project.taskapp --loglevel=info
