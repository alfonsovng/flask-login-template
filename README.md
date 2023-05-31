# flask-login-template

Template project with flask and flask-login

## Set up

Set the  python Virtual Environment

    python3 -m venv venv
    source venv/bin/activate

Install the requirements:

    pip install -r service-flask/requirements.txt

Alternatively, the requirements can be installed manually:

    pip install -U pip
    pip install -U flask flask-login flask-wtf python-dotenv wsgi

To generate the requirements file:

    pip freeze > requirements.txt
    deactivate

## Run it

Execute:

    flask run

And open a browser to [http://127.0.0.1:5000/](http://127.0.0.1:5000/)