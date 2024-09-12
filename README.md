# Collaborative Task Manager (JEE)

This is a simple collaborative task management application built using Java Enterprise Edition (JEE). The application allows users to manage their own tasks while viewing the progress of their team members' tasks without making any modifications to them.

## Features 

* Login: Authenticate users with their credentials.
* Task Management :
  * View finished and unfinished tasks of team members
  * Add, update (Mark your tasks as finished or unfinished), and delete your own tasks.
* Logout: Safely disconnect from the session.

## Database Setup

The database schema follows the Merise model (MCD and MLD). You can find the schema image in the repository. To set up the database:

* Import the provided SQL file into phpMyAdmin using XAMPP.
* Ensure the MySQL server is running.

## Tools and Technologies Used

* IDE: PyCharm Ultimate Edition
* Database: MySQL (using mysql-connector.jar)
* Server: Tomcat 10.1.10
* Frontend: JSP, HTML, CSS
* Backend: Java Servlets, JSP

## Installation

* Set up XAMPP and run Apache and MySQL.
* Import the database schema into phpMyAdmin.
* Clone the project and open it in PyCharm Ultimate Edition.
* Add mysql-connector.jar to the project's libraries.
* Deploy the application on Tomcat 10.1.10.
* Start the Tomcat server and access the app via the browser.



















