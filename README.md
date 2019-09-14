# django
setup pip in IDE

pip install django

django-admin startproject mysite : TO CREATE NEW PROJECT

python manage.py runserver : TO RUN SERVER or LOCALHOST

python manage.py migrate

python manage.py startapp pages : TO create small module / app

Database connectivity https://www.youtube.com/channel/UC4sG9NWzpLX3rvYE9g3aAQw

1. RUN xampp
2. create database
3. sudo pip insatll mysqlclient (if Environment error sudo apt install default-libmysqlclient-dev)

if we have issues with pip

These steps worked for me.

1- Uninstall the pip update from python.

2- Uninstall pip package from your Ubuntu.

3- Check that pip binary is not longer in your system.

python -m pip uninstall pip

apt remove python-pip

whereis pip

4- Download and install pip. (credits for VanDragt.com)

wget https://bootstrap.pypa.io/get-pip.py -O /tmp/get-pip.py

sudo python3 /tmp/get-pip.py

pip install --user pipenv

pip3 install --user pipenv

echo "PATH=$HOME/.local/bin:$PATH" >> ~/.profile

source ~/.profile

whereis pip

4.  python3 manage.py makemigrations
5.  python3 manage.py migrate

In Windows

pip install virtualenvwrapper-win

mkvirtualenv myproject

workon myproject

pip install django


Important URLS


Database connectivity https://www.youtube.com/channel/UC4sG9NWzpLX3rvYE9g3aAQw

tutorials  https://data-flair.training/blogs/django-views/

Code : https://djangopackages.org

Best practices: two scoops of django 

https://www.fullstackpython.com/django.html

https://www.pythoncheatsheet.org
