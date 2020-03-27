https://developer.okta.com/blog/2018/12/20/crud-app-with-python-flask-react 

JavaScript application using React in the front-end and we are also going to build a ReST API written in Python which is going to persist. 

Flask to help you to quickly put together a ReST API. 

A few things you will need:

macOS or Linux operating system
Python 3 installed
MongoDB or the Docker toolbox installed
A free-forever Okta account

step 1:
spin up a MongoDB container is:
$ docker-compose up

step 2:
run your ReST API with the command below:

FLASK_APP=$PWD/app/http/api/endpoints.py FLASK_ENV=development pipenv run python -m flask run --port 4433

Step 3:
To Run your React Front End Javascript
$ npm start
