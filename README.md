<div align="center"><img src="https://user-images.githubusercontent.com/60578902/146579816-eaa296f1-c401-436b-9c3c-57bcb5aece11.png" width="200" height="200"/></div>

# <div align="center">🧑‍⚕️ _Covid Care for All_ 💉</div>
## <div align="center">📅 Hospital Management System 📑</div>
_<div align="center">A website that helps hospitals to keep data for maintaining covid bed slots on the emergency basis.</div>_

## Tech Stack
- Frontend: _HTML, and Bootstrap_
- Backend: _Flask_
- Database: _MySQL_
- Languages: _Python, and Javascript_

## Installation

Install with pip:

```
pip install -r requirements.txt
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

## Screenshots of the application:
<h3>Home Page: </h3>
<img width="800" alt="image" src="https://user-images.githubusercontent.com/60578902/147438394-8c5ee1f1-2765-44ba-be72-3cdfebec53dd.png">

<h3>Patient Login: </h3>
<img width="800" alt="image" src="https://user-images.githubusercontent.com/60578902/147438397-107d0b95-d1aa-491d-af58-2046a72f7ad1.png">

<h3>Patient Details: </h3>
<img width="800" alt="image" src="https://user-images.githubusercontent.com/60578902/147438402-c53a959c-fec1-4b59-b0a7-5851ba1f4724.png">

<h3>Slot Booking: </h3>
<img width="800" alt="image" src="https://user-images.githubusercontent.com/60578902/147438406-43fc01c4-0274-4ba9-8dc7-9617a1b813b7.png">

<h3>Hospital Login: </h3>
<img width="800" alt="image" src="https://user-images.githubusercontent.com/60578902/147438409-cbc136ad-3a54-4cf8-9c98-b8dd82fdae92.png">

<h3>Hospital Details: </h3>
<img width="800" alt="image" src="https://user-images.githubusercontent.com/60578902/147438415-a768ad1c-34ed-4738-9583-f3dadbf36448.png">

<h3>Contact Details: </h3>
<img width="800" alt="image" src="https://user-images.githubusercontent.com/60578902/147438421-9411e270-6401-4c6e-a9bc-34a42a0aefa8.png">


## Reference

Offical Website

- [Flask](http://flask.pocoo.org/)
- [Flask Login](https://flask-login.readthedocs.io/en/latest/)
- [Flask Mail](https://pythonhosted.org/Flask-Mail/)
- [Flask-SQLalchemy](http://flask-sqlalchemy.pocoo.org/2.1/)
- [Flask-MySQL](https://flask-mysql.readthedocs.io/en/stable/)
- [Jinja](https://jinja.palletsprojects.com/en/3.0.x/)
- [gunicorn](http://gunicorn.org/)
