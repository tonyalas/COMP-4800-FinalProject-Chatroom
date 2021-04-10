web: gunicorn django_chatroom.wsgi --log-file -
worker: python manage.py runworker channels --settings=django_chatroom.settings -v2