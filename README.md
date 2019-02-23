See http://flask.pocoo.org/docs/1.0/tutorial/

```bash
# $ python -m venv venv
$ source venv/bin/activate
# $ pip install -r requirements.txt
$ export FLASK_APP=flaskr
$ export FLASK_ENV=development
$ flask run
```

or

```bash
# $ pip install waitress
$ waitress-serve --call 'flaskr:create_app'
```
