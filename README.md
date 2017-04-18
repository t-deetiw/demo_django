# Python Version: 3.6.1 and Django Version: 1.11

## Model and Migration
 - Change your models (in models.py).
 # commands
  1. View sql statements for migration
    - python manage.py sqlmigrate polls 0001
  2. To create migrations for those changes
    - python manage.py makemigrations
  3. To apply those changes to the database.
    - python manage.py migrate
