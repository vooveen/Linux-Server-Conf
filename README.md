# Linux-Server-Conf
Description for my Linux Server Configuration for udacity

## Description
This project is for taking a baseline installation of a Linux distribution on a virtual machine and prepare it to host web applications, to include installing updates, securing it from a number of attack vectors and installing/configuring web and database servers.

## Server Info
- address ip : 3.8.101.12
- ssh port : 2200
- url to the web app : http://ec2-3-8-101-12.eu-west-2.compute.amazonaws.com
- connect via ssh : ssh grader@3.8.101.12 -p 2200 -i ~/.ssh/aws_rsa (passphrase for key : grader )

## Configuration 
- i have created Lightsail account and an ubuntu instance
- i've installed finger to manage linux users
- i've created a new user named grader 
- Adding grader user to sudoers and giving it Sudo access
- Generating Key Pairs with ssh-keygen
- Adding the Key Based Authentification to grader user 
- Forcing Only Key Based Authentification
- Setting a Firewall using UFW
- Denying all incoming trafic using UFW
- Allowing only SSH, HTTP and NTP ports
- Installing apache2 to respond to HTTP requests
- Installing mod_wsgi
- Installing PostgreSQL
- Installing git and cloning the Item catalog project
- Installing virtual envirement 
- Installing Flask and all needed libraries to run the web app (httplib2, requests, flask-seasurf, oauth2client,sqlalchemy, python-psycopg2)
- Creating user and database with postgresql and giving it access permission
- Configuring WSGI file
- Creating a domain name with [wtool.io](https://wtools.io/convert-ip-to-host)

## Resources used to complete this project
- Udacity Courses : Intro to Linux, Linux Security, Web Application servers
- [How To Install Linux, Apache, MySQL, PHP (LAMP) stack on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-14-04)
- [Deploy a Flask Application on an Ubuntu VPS](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
- [How To Install and Use PostgreSQL on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-16-04)
