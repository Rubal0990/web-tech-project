# Web-tech-project

This is a *Todo List* web app. This app has ability for user login and add/delete todos. It helps managing todos and events much like a notelog.

https://notelog-web-app.herokuapp.com/

## Getting Started
Setup project environment with [virtualenv](https://virtualenv.pypa.io/en/latest/) and [pip](https://pip.pypa.io/en/stable/).
```
$ virtualenv project-env
$ source project-env/bin/activate

# Clone the project repository
$ git clone https://github.com/kashishbagadia/web-tech-project.git

# Download all the dependencies needed to run this project
$ cd project/
$ pip install -r requirements.txt

# Run Django Server
$ python manage.py migrate
$ python manage.py runserver
```

## Features
* User login system.
* Maintaining todo lists.
