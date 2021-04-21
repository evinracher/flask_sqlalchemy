This is a simple example of a flask + sqlalchemy backend application

Using a virtual environment
```
$ virtualenv <name>
```

Activating virtual environment (on mac)
```
$ source <name>/bin/activate
```
Deactivating virtual environment
```
$ deactivate
```
# Requirements

## Main requirements
- Python3
- pip3
- virtualenv (if you want to use venv)

Installing packages (with venv activated)
```
$ pip3 install flask flask-sqlalchemy flask-marshmallow marshmallow-sqlalchemy pymysql
```
Or (no venv required):
```
$ pip3 install requirements.txt
```
This file was generated by the next command:
```
$ pip3 freeze > requirements.txt
```
# Run on flask
```
$ export FLASK_APP=src/app.py
$ export FLASK_ENV=development
$ flask run
```