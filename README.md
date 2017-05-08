# Flask-Macaroons

Flask-Macaroons is a Flask extension that provides creation and consumption of macaroons using the libmacaroons package

https://github.com/rescrv/libmacaroons

## Installation

Install the extension with one of the following commands:

    $ easy_install flask-macaroons

of alternatively if you have pip installed:
    
    $ pip install flask-macaroons

## Usage

To use the extension simply import the class wrapper and pass the Flask app
object back to here. Do so like this:
    
    from flask import Flask
    from flask.ext.macaroons import Macaroons
    
    app = Flask(__name__)
    macaroons = Macaroons(app)
