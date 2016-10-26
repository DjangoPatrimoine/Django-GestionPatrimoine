# Django-GestionPatrimoine
====
[![Build Status](https://travis-ci.org/DataIsTheNewBlack/Django-GestionPatrimoine.svg?branch=master)](https://travis-ci.org/DataIsTheNewBlack/Django-GestionPatrimoine)
[![Documentation Status](https://readthedocs.org/projects/django-gestionpatrimoine/badge/?version=doc-dev)](http://django-gestionpatrimoine.readthedocs.io/en/doc-dev/)
[![Documentation Status](https://readthedocs.org/projects/django-gestionpatrimoine/badge/?version=doc-user)](http://django-gestionpatrimoine.readthedocs.io/en/doc-user/)
[![Dependency Status](https://gemnasium.com/badges/github.com/DataIsTheNewBlack/Django-GestionPatrimoine.svg)](https://gemnasium.com/github.com/DataIsTheNewBlack/Django-GestionPatrimoine)
[![Issue Count](https://codeclimate.com/repos/5810b7524ccb3e715a0019ff/badges/817135e63224b27e518a/issue_count.svg)](https://codeclimate.com/repos/5810b7524ccb3e715a0019ff/feed)
[![Code Climate](https://codeclimate.com/repos/5810b7524ccb3e715a0019ff/badges/817135e63224b27e518a/gpa.svg)](https://codeclimate.com/repos/5810b7524ccb3e715a0019ff/feed)
[![Test Coverage](https://codeclimate.com/repos/5810b7524ccb3e715a0019ff/badges/817135e63224b27e518a/coverage.svg)](https://codeclimate.com/repos/5810b7524ccb3e715a0019ff/coverage)

###Heroku


## Running Locally

Make sure you have Python [installed properly](http://install.python-guide.org).  Also, install the [Heroku Toolbelt](https://toolbelt.heroku.com/).

```sh
$ git clone git@github.com:heroku/python-getting-started.git
$ cd python-getting-started

$ pip install -r requirements.txt

$ createdb python_getting_started

$ python manage.py migrate
$ python manage.py collectstatic

$ heroku local
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master

$ heroku run python manage.py migrate
$ heroku open
```
or

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Documentation

For more information about using Python on Heroku, see these Dev Center articles:

- [Python on Heroku](https://devcenter.heroku.com/categories/python)
