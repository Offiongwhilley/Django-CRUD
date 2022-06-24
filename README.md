# Django-
To create virtual environment: virtualenv environment_name.
To activate the virtual environment: environment_name/Scripts/activate
To install django in it: pip install django
To create a project: django-admin startproject project_name
To create app: navigate to the project; python manage.py startapp app_name
To add the app to the main_projects INSTALLED_APPS: go to the file 'settings.py'. in the array of INSTALLED_APPS, add the app name.
To create migrations: python manage.py makemigrations.
To run migrations: python manage.py migrate.
To register Post models: open admin.py and enter the following:
  admin.site.register(title)
  admin.site.register(slug)
  admin.site.register(author)
  admin.site.register(body)
  admin.site.register(published)
  admin.site.register(created)
  admin.site.register(updated)
  admin.site.register(status)
