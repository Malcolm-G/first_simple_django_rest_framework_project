# DRINKS

This is a simple project created to learn to use Django Rest Framework to create an API that can be consumed by any frontend. Need to learn to implement associations as this project on includes one model.

In terms of sparating concerns, instead of one views file, we can have a views directory with many modules that handle their own tasks. Then have a file name '\__init__.py' that will have all the modules imported in it and acts as the entry point of the directory thus one can keep their paths in the urls.py file asthey would normally have it. Find more info [here](https://simpleisbetterthancomplex.com/tutorial/2016/08/02/how-to-split-views-into-multiple-files.html)