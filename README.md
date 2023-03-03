# Simple Django REST framework
-----------

This is a simple web-app that implement django-rest-framework  This is created by hoangddt and follow this instruction [REST framework tutorial](http://www.django-rest-framework.org/tutorial/1-serialization/)

## Run

Now we syncdb for the first time
```sh
python manage.py migrate
python manage.py createsuperuser
```

And then Run server
```sh
python manage.py runserver
```
And then go ahead at http://localhost:8000/

### Browser API
You can go to /docs to see the API and test
api end point 
```
http://127.0.0.1:8000/api/blog
http://127.0.0.1:8000/api/blog-detail/<int id>

```