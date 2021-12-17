<div align="center"><img src="https://user-images.githubusercontent.com/60578902/146579816-eaa296f1-c401-436b-9c3c-57bcb5aece11.png" width="200" height="200"/></div>


# Hospital-Management-System: _Covid Care for All_

## Tech Stack
- Frontend: _HTML, and Bootstrap_
- Backend: _Flask_
- Database: _MySQL_
- Languages: _Python, and Javascript_

## Installation

Install with pip:

```
$ pip install -r requirements.txt
```

## Flask Configuration

#### Example

```
app = Flask(__name__)
app.config['DEBUG'] = True
```
### Configuring From Files

#### Example Usage

```
app = Flask(__name__ )
app.config.from_pyfile('config.Development.cfg')
```


## Flask settings
```
DEBUG = True  # True/False
TESTING = False
```
## Run Flask
### Run flask for develop
```
$ python webapp/run.py
```
In flask, Default port is `5000`

## Reference

Offical Website

- [Flask](http://flask.pocoo.org/)
- [Flask Login](https://flask-login.readthedocs.io/en/latest/)
- [Flask Mail](https://pythonhosted.org/Flask-Mail/)
- [Flask-SQLalchemy](http://flask-sqlalchemy.pocoo.org/2.1/)
- [Flask-MySQL](https://flask-mysql.readthedocs.io/en/stable/)
- [Jinja](https://jinja.palletsprojects.com/en/3.0.x/)
- [gunicorn](http://gunicorn.org/)
