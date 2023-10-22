## This is an eLearning platform including a CMS - Made in Django

![application image](./docs/img/course%20home.png)

The features of this application are:

- Implements a content management system using class-based views and mixins
- Restricts access using groups and permissions
- Implements formsets to manage course contents
- Implements drag-and-drop functionality to reorder content in-place using JavaScript and Django
- Uses generic mixins from [django-braces](https://github.com/brack3t/django-braces)
- Implements public views and student enrolment views
- Renders different type of contents and use [django-embed-video](https://github.com/jazzband/django-embed-video)
- Implements restful APIs using [Django REST Framework](https://www.django-rest-framework.org/)
- Implements a real-time chat server using Django [Channels](https://github.com/django/channels)
- Implements a WebSocket consumer/client using Django and JavaScript
- Uses Redis to set up a channel layer
- Makes your WebSocket fully-asynchronous
- Configure a production environment using [Docker Compose](https://docs.docker.com/compose/) with PostgreSQL, Redis, [Nginx](https://www.nginx.com/), [uWSGI](https://uwsgi-docs.readthedocs.io/en/latest/) and [Daphne](https://github.com/django/daphne)
- The project is served securely through HTTPS
- Uses the Django system check framework
- Implements custom management commands
