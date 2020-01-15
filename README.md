# Microblog
Final project for course of Principles, Practices, and Patterns of Software Design of MIPT master's degree program.
This is small application written in **Python** with using **Flask** framework
A logged-in user can make posts, read other user's posts, and follow them;

To learn more, install the app!

* Author: Podlozhnyy N., student at MIPT and data scientist at Tinkoff Group. The work is based on https://learn.miguelgrinberg.com/
* The application is not deployed on a real server. To install app, clone the repository to your personal computer.

*Attention! Python 3 must be installed. Flask and it's packages сould be installed with:*

$ pip install flask

$ pip install flask-<need_package>    (All required packages can be found in microblog/app/__init__.py)

 * To start the application run the following commands:
 
$ export FLASK_APP=microblog.py  (set вместо export для Windows)

$ flask run

* To start the testing run this:

$ python tests.py
