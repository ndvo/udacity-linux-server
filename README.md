# Udacity Linux Server

A repo for the linux server configuration assignment from the Udacity FullStack Nanodegree

### The IP address and SSH port so your server can be accessed by the reviewer.

The public IP is 35.182.224.148
The SSH connection is available on port 2200

### The complete URL to your hosted web application.

http://35.182.224.148/

### A summary of software you installed and configuration changes made.
I installed Apache2 with Modwsgi and Python. I also installed pip in order to install the requirements.
Some requirements couldn't be installed from pip and I had to install manually.

The persistance is done with Sqlite. PostgreSQL was installed because the instructions required so.

I configured Apache to serve the Flask application.


### A list of any third-party resources you made use of to complete this project.

I used the content provided in the course, complemented by the following list of documents:
- http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/
- https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
- http://www.devfuria.com.br/python/flask-apache/
- https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstancesLinux.html
