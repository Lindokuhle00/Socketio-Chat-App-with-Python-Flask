"# Socketio-Chat-App-with-Python-Flask" 
In this project I was creating a miniatur chat app using python flask and sockio.
Socket.IO is a powerful JavaScript library that enables real-time, bidirectional, and event-based communication between web clients and servers. It's designed to work on every platform, browser, or device, focusing equally on reliability and speed.

The application works by using web sockets to connect the front-en (html templates) with the back-end (flask-server).
The application runs an the local machine, but can also be tweaked to run on different machines and even networks.

Sorry for not including a requirements.txt file for all the dependencies. but for this applican you must have python on your machine and the following libraries installed as follows;

from flask import Flask, render_template, request, session, redirect, url_for
from flask_socketio import join_room, leave_room, send, SocketIO
import random
from string import ascii_uppercase

Lastly, to test/run the app you can run the python file and past your local-port url on two browsers, you can then fill the forms and generate the room code needed for entering a particular room. Thank you.
