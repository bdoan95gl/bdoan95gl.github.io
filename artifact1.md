---
videoId: hOXqmy-QKZs
---

### Artifact Enhancement 1

## Artifact 1 Demo Video
{% include videoPlayer.html id=page.videoId %}

## Narratives
The artifact I have here is an Authentication System that I have created as a final project for my IT-145 Foundation in Application Development course.  An overview of Authentication System project is to take in user’s username and password input.  Then compare those credentials with existing credentials under MD5 hash on a text file.  If the credentials match, the system will display appropriate content from other text files that match with user job roles.  There are total of three different job roles: zookeeper, admin, and veterinarian.  This project was originally developed to take input and display output via IDE’s console.  For the first enhancement, I have decided to implement the project with Java graphical user interface, where the project will display java panels and allow users to interact on panels with feature such as buttons, labels, windows, and different text sizes/fonts.  With this project, I will be able to display my skills in: implementation of Java SWING library, displaying Java language knowledge, implementation of MD5 hash string, usage of pseudocode to segment functionality of software, solve logic problems and implement them in software, applying coding best practices, employ iterative algorithm, implement classes in a way that could apply to future changes to classes and objects, find potential security vulnerabilities or bugs from project, fix potential security vulnerabilities and bugs, create industry-standard software design.

Also to enhance my capability in software design and engineering, algorithms and data structure, and databases management. 
This enhancement was done through NetBeans IDE and the utilization of Java swing GUI libraries.  I have implemented flowchart approach when working on this enhancement.  Where I drew out a pictorial representation of my Authentication System algorithm and work from node to node to build the project. Since this is my first time interacting with Java Swing, I have learned new techniques in developing graphical user interface.  I found that NetBeans IDE is very convenient with resizing and generating buttons.  Instead of typing in boundary values, mouse drag and drop movement could be used to resize the button to the appropriate size via NetBeans design function.  The struggling part with this enhancement is implementing MD5 hash with JLabel input.  An issue came up when I was trying to convert hashed MD5 value into string.  After couple of searches on the internet, the solution I came up with is to store byte value into BigInteger datatype and use “toString()” function to convert it to string value.  From there hashed value can be read and compared to values on credential text file.  

[Link to Artifact Enhancement 1](https://github.com/bdoan95gl/bdoan95gl.github.io/tree/Artifact-1)
