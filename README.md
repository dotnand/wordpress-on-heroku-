
# wordpress-on-heroku

This is a project where you can run wordpress on heroku..........With PostgreSQL

Installation
============

Clone the repository from Github

    $ https://github.com/dotnand/wordpress-on-heroku-.git

    
Deploy to Heroku

Add a database to your app
 use following command to add database
              a) heroku addons:docs heroku-postgresql:dev
              b)  heroku pg:promote HEROKU_POSTGRESQL_BLACK (change the name)

Main important database setting use like folling
	DATABASE_URL: postgres://thinga:thingb@ec2-23-21-119-36.compute-1.amazonaws.com:5432/thingc
	Database Name: thingc
	Host: ec2-23-21-119-36.compute-1.amazonaws.com
	Username: thinga
	Password: thingb
           

For any help you can contact me dotnand@gmail.com