release: flask db upgrade
web: gunicorn Flask service.app:create_app\(\) -b 0.0.0.0:$PORT -w 3
