Falko Hamanns Catalog
=======================
Project: Build an Item Catalog


What Is This?
-------------

This is a python web server for an item catalog based on Flask, SQLAlchemy 
and SQlite. You can view categories and items which belong to a category.

If you log in with Google oauth you are able to create, edit, delete 
categories and items.


What is included?
-----------------------

/static

holds the css file(s)

/templates

holds the html files

/holds the python, db and plugin files


How to run the webserver?
-----------------------

python application.py

The database will be created with no elements through
the python file database_setup.py


JSON endpoints
-----------------------

There are two JSON Endpoints:

/mainCatalog/JSON

Shows a JSOn view of all categories.

/category/<int>/JSON

Shows all items which belong to the category


