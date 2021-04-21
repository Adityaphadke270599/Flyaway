# Flyaway Ticket Booking App in JAVA - Servlet&JSP

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Using the application](#using-the-application)


## General info
A small flight booking demo project in <b>JAVA</b> 

## Technologies
<b>Frontend</b> - JSP, HTML, CSS, Bootstrap (CSS framework used for front end webapp development.) <br>
<b>Backend</b> - JAVA Servlets <br>
<b>Database</b> - MySQL - Hosted on a remote server at AWS RDS <br>
<b>Application Server</b>  - Tomcat 8.5 with Corretto 11 running on 64bit Amazon Linux 2/4.1.6 on AWS Elasticbeanstalk <br>

## Using the application
Home displays the application name (FlyAway) and two options - Book Flights and Admin Panel Access
<br><br>
<b>Book Flights</b>  - <br>
The user enters flight details (i.e.; date, source, destination, travellers). 
A query is sent to the remote database to fetch related flights and displayed to user.
The User enters other details and proceeds to book the flight.
<br><br>
<b>Admin</b>  - <br>
Admin dashboard is accessed with a preset username and password.
Admin can see all entries in database table.
Admin can change his password after Login.


