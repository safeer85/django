how to check the version of the django is 
py -m django --version

how to upgrade the django
 pip install --upgrade django

how to start a project
django-admin startproject mysite djangotutorial

here when we give above command it will clreate a project called mysite in the folder of djangotutorial

now let's know why there is so many default files
1. manage.py - it is the command line helper script for the specific django project it let run of commands with our project 
2. setting.py - it is the brain of our project it is the main configuration file in the porject it has the which database should run which apps are installed 
3.urls.py - it has the urls that  which code run for which url if you user give a url in a browser it need to run a specific function so in this file it is mapped to the specic function to that url
4. wsgi.py is the production base file it similar to the manage.py but  manage.py is used when the development phase but when it come to the production it will use this file 
5. asgi.py - lets django handle real-time and async features
6. init.py tells that this folder is a package

