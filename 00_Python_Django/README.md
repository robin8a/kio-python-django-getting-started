# Reference:
- [Python Django Tutorial for Beginners](https://www.youtube.com/watch?v=rHux0gMZ3Eg)

# Getting Started 

```sh
# Pipenv is a packaging tool for Python that solves some common problems associated with the typical workflow using pip , virtualenv , and the good old requirements.
pipenv install django

Creating a virtualenv for this project...
Pipfile: /Users/robin8a/Documents/python_ws/mag-storefront-django-app/Pipfile
Using /usr/local/bin/python3 (3.10.2) to create virtualenv...
⠸ Creating virtual environment...created virtual environment CPython3.10.2.final.0-64 in 2375ms
  creator CPython3Posix(dest=/Users/robin8a/.local/share/virtualenvs/mag-storefront-django-app-iWuRQGg3, clear=False, no_vcs_ignore=False, global=False)
  seeder FromAppData(download=False, pip=bundle, setuptools=bundle, wheel=bundle, via=copy, app_data_dir=/Users/robin8a/Library/Application Support/virtualenv)
    added seed packages: pip==22.0.4, setuptools==60.9.3, wheel==0.37.1
  activators BashActivator,CShellActivator,FishActivator,NushellActivator,PowerShellActivator,PythonActivator

✔ Successfully created virtual environment! 
Virtualenv location: /Users/robin8a/.local/share/virtualenvs/mag-storefront-django-app-iWuRQGg3
Creating a Pipfile for this project...
Installing django...
Adding django to Pipfile's [packages]...
✔ Installation Succeeded 
Pipfile.lock not found, creating...
Locking [dev-packages] dependencies...
Locking [packages] dependencies...
Building requirements...
Resolving dependencies...
✔ Success! 
Updated Pipfile.lock (79baf8)!
Installing dependencies from Pipfile.lock (79baf8)...
  🐍   ▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉ 0/0 — 00:00:00
To activate this project's virtualenv, run pipenv shell.
Alternatively, run a command inside the virtualenv with pipenv run.
```

```sh
pipenv shell

Launching subshell in virtual environment...
 . /Users/robin8a/.local/share/virtualenvs/mag-storefront-django-app-iWuRQGg3/bin/activate
➜  mag-storefront-django-app  . /Users/robin8a/.local/share/virtualenvs/mag-storefront-django-app-iWuRQGg3/bin/activate
```

## django admin
```sh
django-admin # Available commands
django-admin startproject mag_storefront_django_app .
python manage.py # Available commands
python manage.py runserver 9000
# or default is 8000
python manage.py runserver
# check where is my env 
pipenv --venv # Configure the virtual env in VS Code with Cmd + P => Python => Select enterpreter
python manage.py startapp playground


```