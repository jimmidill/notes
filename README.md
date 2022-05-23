# notes

## requirements
python 3.7
pip 3.7
pipenv

## env
create .env file and configure db settings:

```
export DB_USERNAME='demo'
export DB_PASSWORD='<password>'
export DB_HOST='<DB Server public IP>'
export DB_PORT='80'
export FLASK_ENV='development'
export FLASK_APP='.'
```

## run
pipenv shell
pipenv install
flask run --host=0.0.0.0 --port=3000
