---
videoId: lulCQJjcNxU
---

# Artifact Enhancement 3

## Artifact 3 Demo Video
{% include videoPlayer.html id=page.videoId %}

## Flowchart

<img src="https://github.com/bdoan95gl/bdoan95gl.github.io/blob/main/images/pseudo3.PNG?raw=true"/>

## Narratives

For this third enhancement, I have implemented database storage instead of text file storage from the previous enhancements.  The functionality of the authentication program remains the same.  It still able to perform login, create account, SHA-256 string hash, failed login attempts, and display GUI.  But instead of storing and comparing values from a text file, the program will now connect to a database for storage and comparing value.  Mysql-connector-java-8.0.13.jar file and phpMyAdmin were utilized to establish database connection and database management.   Mysql connector jar file enables the building of database, database connection, and perform java query command toward database.  phpMyAdmin program allow me to the view content of the database and make sure my third enhancement can manipulate data on the database.  The default database information for this third enhancement includes “authdb” for database name, database server will be on local host, root access privilege with “bao123” for password.  I’m using MySQL as relational database management system for this third enhancement.  Beside database conversion, I also added a feature on my program to check for existing username within database.  When user trying to create an account with existing username, the program will display appropriate matched credentials message and decline account creation.

The reason I chose this third enhancement is to display my ability in implement approach to ensure data are explicitly validated, implementation of database, display mySQL techniques CRUDs and query concepts, implementation of java to database cross platform, arrays and control structures with database, and implementation of external database software such Xampp and PHP.

## Repository Link

[Link to Artifact Enhancement 3 Repository](https://github.com/bdoan95gl/bdoan95gl.github.io/tree/Artifact-3)

## Table of Contents
[Home Page](https://bdoan95gl.github.io)

[Professional Self-Assessment](https://bdoan95gl.github.io/selfassessment)

[Informal Code Review](https://bdoan95gl.github.io/codereview)

[Artifact Enhancement 1](https://bdoan95gl.github.io/artifact1)

[Artifact Enhancement 2](https://bdoan95gl.github.io/artifact2)

[Artifact Enhancement 3](https://bdoan95gl.github.io/artifact3)
