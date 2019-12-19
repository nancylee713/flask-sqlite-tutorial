# flask-sqlite-tutorial

Creating a basic blog with Python and Flask

The tutorial can be found [here](https://flask.palletsprojects.com/en/1.1.x/tutorial/).

## Get Started
### 1. Create a virtual environment for a new project
```python
 $ pip install virtualenv
 $ virtualenv venv -p python3  # this will create venv directory
 $ virtualenv -p python3 venv # this will create bin and include lib dir
 $ source venv/bin/activate
```

### 2. Run the application
```python
  $ export FLASK_APP=flaskr
  $ export FLASK_ENV=development
  $ flask run
```
