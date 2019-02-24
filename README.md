# django

https://code.visualstudio.com/docs/python/tutorial-django

https://github.com/Microsoft/python-sample-vscode-django-tutorial


This includes a Dockerfile to build a production-ready container image that uses uwsgi and nginx; the uwsgi.ini file provides uwsgi configuration.

To run the sample:

Create a virtual environment as described in the tutorial.
Install packages with pip install -r requirements.txt.
Activate the virtual environment by running source env/bin/activate (Linux/MacOS) or env\scripts\activate (Windows).
Create and initialize the database by running python manage.py migrate.
Create a superuser as described at the end of the tutorial.

In the Terminal, run the:

    command python manage.py collectstatic 
and observe that hello/site.css is copied into the top level static_collected folder alongside manage.py.
In practice, run collectstatic any time you change static files and before deploying into production.