# AmazonLightsailConf - Linux Server
This is the description for the my Linux server on AmazonLightsail
## Server Info
- **IP address(static):** 18.216.74.102
- **SSH port:** 2020
- **Web app URL:** http://18.216.74.102/

## Web app config
This web app is a website showing description of different items in different categories. It is developed on Python Flask framework that supports CRUD functionality and a Google login

### Requirements
  * Python 2.7
  * flask
  * sqlalchemy
  * PostgreSQL
  
Along with the above installed for all users on the server, some configures were made:
* The database for this web was created by admin in PostgreSQL
* The role "www-data" was created with all privileges granted on the database
* A WSGI file was created to run the Flask application
