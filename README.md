# learn-django
learning django via Traversy Media Youtube Channel's Python Django Crash Course

# Pre-requisites
- Have the latest Python installed (this repo would be using Python 3.8.x)
- Install Django ($pip install django)

# Instructions
* Project vs Apps
- Project
> The project is your overall website.
- Apps
> You may have several apps within your website


* Creating a Project *
```$ django-admin startproject <name of project>```

* Creating apps for the project
> Ensure that you are first cd into your project directory/folder
```$ python manage.py startapp <name of app>```

* Set-up admin area
```$ python manage.py createsuperuser```
> after typing the command in the command terminal, you will be asked to type in a username