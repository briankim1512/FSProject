# Connecting
To connect to the server, the IP is grader@13.113.191.157 and the SSH port is configured to port 2200

The URL to connect to the server through HTTP is the standard IP as well, 13.113.191.157

## Installs and Changes
I installed apache, mod_wsgi, sqlite, fingers and pip to download other python modules such as 
Flask, Oauth2client, Requests, Virtualenv, and SQLAlchemy.

The changes I've made from the vanilla installs are:

/etc/apache2/sites-available/000-default.conf (Make the WSGI app work for apache)
/var/www/html (Added all necessary files and made a virtual environment for WSGI to read python)

## Post Script
The grader key will be provided through other means
