# Basic-App-Structure;

## Researched Topics Here:
    |- https://flask.palletsprojects.com/en/stable/
    |- Flask Web Development Book By Miguel Grinberg

### Installation: (Follow Step by Step)
    |- mkdir basic-app           --> (Create folder/directory)
    |- cd basic-app/             --> (Go to that directory)
    |- python3 -m venv .venv     --> (Create Virtual Environment)
    |- source .venv/bin/activate --> (Acivate virtual environmnet)
    |- pip install flask         --> (Install flask library)

### Basic App Structure:
    |- app.py
    |     from flask import Flask
    |     app = Flask(__name__)
    |     @app.route("/")
    |     def hello_world():
    |       return "hello, world"
    |
    |- Save file using 'Ctrl-S'
    |- flask run (to run the app)