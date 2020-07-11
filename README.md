# flask-tutorial

My flask study project.
I will use the blog created in the tutorial and expand it  to further study flask 


You can follow the tutorial [here](https://flask.palletsprojects.com/en/1.1.x/tutorial/)!

### How to run
This application is run using docker, so first build the image.
```sh
docker build --tag flask-tutorial .
```
Now you need to create the database

- First setup the env for the flask app
```sh
export FLASK_APP=flaskr
```
- Then create the database
```sh
flask init-db
```


Now you can run the project using the script run
```sh
./run.sh
```

You can also test the application with
```sh
./run-test.sh
```
