# Django-Workshop-Regex

Step-1: pip install django in CMD

Step-2: Download and install Sublime text editor

Step 3: To create a project write --- django-admin startproject Reg in CMD.

Check the folder where you created the folder. 

Step-4: Try to run Server. Type the following in CMD:

C:\Users\lenovo>cd Reg

C:\Users\lenovo\Reg>python manage.py runserver

Step-5: On your Browser type: http://127.0.0.1:8000/ and you can see the page that conveys that Django is perfectly running. If there is any error check the above steps again.

Now we will create .py files. Some of the important ones are:

* views.py : we define different functions that will be invoked as response to URL hit.

* models.py : for defining data model (data settings)

* forms.py : for django form

Step 6: Stop the server by Ctrl+C in CMD.

Step 7: Open settings.py in sublime text editor. Write your app name in Installed app section as shown:

INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'regfirstapp'
]

Step 8: Open Views.py. 

The simple responses are called http response. Edit the settings.py, url.py, views.py files.

Step 9: Start the Server again and run again.


Step 10 Create a folder named templates in app folder. And create Html file in this.

You can write any html code here.

Step 11 Using Database in Django. It uses SQlite data base. Download https://sqlitebrowser.org/dl/ to view data.
