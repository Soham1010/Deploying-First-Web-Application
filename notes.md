## WSGI
Web Server Gateway Interface
special server to run python

we need to tell our hosting provider about our gunicorn server, what our app is called, and how to run our Flask app. We do that using a config file called a Procfile

With Capital P 

add:-   web: gunicorn main:app          in it 
