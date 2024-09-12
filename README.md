# Collaborative Task Manager (JEE)

This is a simple collaborative task management application built using Java Enterprise Edition (JEE). The application allows users to manage their own tasks while viewing the progress of their team members' tasks without making any modifications to them.

![image](https://github.com/user-attachments/assets/69a8985d-f6f9-4071-b6b5-9358f2cb7f56)

## Features 

* Login: Authenticate users with their credentials.
  ![image](https://github.com/user-attachments/assets/68f1a186-e721-496b-beec-b7b463d4e9f6)

* Task Management :
  * View finished and unfinished tasks of team members
  * Add, update (Mark your tasks as finished or unfinished), and delete your own tasks.
    ![image](https://github.com/user-attachments/assets/8d9af4c4-b10d-4cf9-a8b5-3545b030c724)
* View Team Members: See the list of your team members and their respective tasks.
![image](https://github.com/user-attachments/assets/b5cebf94-0771-4146-b615-1c68bdf82a3c)

![image](https://github.com/user-attachments/assets/30bda038-a384-4618-95d1-fb4ea7c00217)


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



















