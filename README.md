# django-refresh
Bash script for Django &amp; PostgreSQL users in development environment. Automates db deletion, creation, migration all the way up to createsuperuser prompt.

### Run it 

Drop this file in your django project, same root folder as manage.py. If the filepath is in you PATH just run `django-refresh <database name>`. Otherwise, type/paste in your filepath to the script and run: `/filepath/to/script/django-refresh <database name>`. This will delete all migration files, delete the current database, make a new database of the same name, make migrations, migrate then prompt you for e-mail & pw from `python manage.py createsuperuser` command. Enjoy!
