# reading Notes 27

## Django models

- Each Django model maps to a single database table, and each attribute of the model maps to a database field

- a model is a class with fields of info

- databases are defined as configuration dictionaries.

## Django Admin

- application can use your models to automatically build a site area that you can use to create, view, update, and delete records

- admin area is automatically built

- to log into the admin site, we need a user account with Staff status enabled

- create a "superuser" account that has full access to the site and all needed permissions using manage.py