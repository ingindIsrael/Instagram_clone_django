pip install -r requirements.txt
python manage.py runserver
python manage.py collectstatic --noinput
DISABLE_COLLECTSTATIC=1
.venv/scripts/activate