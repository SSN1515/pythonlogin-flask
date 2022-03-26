# pythonlogin-flask
This is a blog created

GitHub Actions PyPI PyPI versions PyPI formats Flask Documentation

Login Extension for Flask
The simplest way to add login to flask!

How it works
First, install it from PyPI:

$ pip install flask_simplelogin
Then, use it in your app:

from flask import Flask
from flask_simplelogin import SimpleLogin

app = Flask(__name__)
SimpleLogin(app)
That's it!
Now you have /login and /logout routes in your application.

The username defaults to admin and the password defaults to secret — yeah that's not clever, check the docs to see how to configure it properly!

Login Screen

Check the documentation for more details!
