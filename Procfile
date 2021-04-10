web: daphne django_chatroom.asgi:application --port $PORT --bind 0.0.0.0 -v2
chatworker: python manage.py runworker --settings=django_chatroom.settings -v2