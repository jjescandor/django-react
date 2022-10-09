### To build this app, follow the following steps:


## Django Server
    - pip intall django
    - django-admin startproject music_controller
    - python manage.py startapp api
    - add your apps and rest_framework to settings.py
    - configure urls.py
        - import include
        - add the paths to urlpatterns
    - python.py migrate
    - create your model
    - python manage.py makemigrations
    - python manage.py migrate
    - touch and configure serializer.py (to transfrom model into json)
        - import serializers
    - configure views
        - import generics
        - create a class that would inherit from generics
    - touch and configure urls.py in your app
        


## React.js FrontEnd
    - 