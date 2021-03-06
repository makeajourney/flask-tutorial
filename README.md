# Flask Tutorial

http://flask.pocoo.org/docs/1.0/tutorial/

## Development Environment

* Python 3.7.0
* Flask

## Export Environment Variables

```sh
export FLASK_APP=flaskr
export FLASK_ENV=development
```

## install the dependent environment

```sh
pip install -e .
```

## Run the Application

```sh
flask run
```

## run the test

```sh
pytest
```

### with coverage report

```sh
coverage run -m pytest
coverage report
coverage html # open htmlcov/index.html in a browser
```