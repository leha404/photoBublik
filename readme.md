Learning Django.

Inspired by DjangoGirls:
https://tutorial.djangogirls.org/ru/django/

PreRequesites:
0) Delete all inner folders for clean project.
There are should be: readme and requirements

Instructions:
1) Install virtual env (macOS):
python3 -m venv myvenv

2) Run virtual environment:
source myvenv/bin/activate

3) Update Python package manager:
python3 -m pip install --upgrade pip

4) Get requirement packages (check requirements.txt):
pip install -r requirements.txt

5) *optional: Get Django default project structure (if needed!):
django-admin startproject mysite .

6) Apply migrations to database:
python manage.py migrate

7) Run server:
python manage.py runserver

8) *optional: Creating app (Register it in settings.py):
python manage.py startapp blog

9) Create migrations, if has changes (blog - app name, mey be different):
python manage.py makemigrations blog