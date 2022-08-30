# superset-heroku

## When use...

Change SECRET_KEY in superset_config.py

## After deploy on heroku run the following command

heroku run bash
export FLASK_APP=superset
superset db upgrade
superset fab create-admin
superset init
