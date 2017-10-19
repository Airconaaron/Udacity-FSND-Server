# Udacity Server Configuration Project

This README file is for the Udacity Full Stack Nanodegree Final Project on Linux server configuration.

# IP Address and port
The ip address for the server is 54.169.119.93 . Connect to it via port 2200.

# URL
THe url for the app is at 

# Installed Software
* Apache
* PostGresSQL
* Finger
* Memcache
* Python
* PIP
* SQLAlcehmy
* Flask
* requests
* oauth2client
* flask_httpauth

Changes I made were to set up a firewall to allow traffic at ports: 80, 123, 2200.
I also added the public key i generated to the user 'grader'. 
I also stopped apache from starting itself whenever the computer starts. using ` sudo systemctl disable apache2`

# Resources 
https://askubuntu.com/questions/170640/how-to-disable-apache2-server-from-auto-starting-on-boot