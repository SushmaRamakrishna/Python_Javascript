https://developer.okta.com/blog/2018/12/20/crud-app-with-python-flask-react 

JavaScript application using React in the front-end and a ReST API written in Python which is going to persist. 

Flask to help put together a ReST API. 

A few things you will need:

macOS or Linux operating system
Python 3 installed
MongoDB or the Docker toolbox installed
A free-forever Okta account

step 1:
spin up a MongoDB container is:
$ docker-compose up
MongoRepository class reads a environment variable MONGO_URL . To export the environment variable, run:
$ export MONGO_URL=mongodb://mongo_user:mongo_secret@0.0.0.0:27017/

step 2:
run your ReST API with the command below:

FLASK_APP=$PWD/app/http/api/endpoints.py FLASK_ENV=development pipenv run python -m flask run --port 4433

Step 3:
To Run your React Front End Javascript
$ npm start
