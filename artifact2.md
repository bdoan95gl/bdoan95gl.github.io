---
videoId: WYtAXJTa4ws
---

# Artifact Enhancement 2

## Artifact 2 Demo Video
{% include videoPlayer.html id=page.videoId %}

## Flowchart

<img src="https://github.com/bdoan95gl/bdoan95gl.github.io/blob/main/images/pseudo2.PNG?raw=true"/>

## Narratives

For this second enhancement, I have implemented SHA-256 hashing to my program instead of MD5 hashing as well as adding “Create Account” function for my program.  Both MD5 and SHA-256 are hashing algorithm that take in input values and return a fixed-length value that have no discernable pattern.  MD5 produce 128-bit hash value while SHA-256 produce 256-bit hash value.  Current researched indicate that SHA-256 hash algorithm is considerably more secure than MD5 hash algorithm.  For my program, switching from MD5 to SHA-256 was a smooth process since Java security message digest library contains both algorithms.  I only had to replace “getInstance” value from MD5 to SHA-256.  

The second portion of this enhancement is adding “Create Account” function.  This function will take in three fields of input: username, password, and re-enter password.  Once all three fields are filled out and password and re-enter password field matched, password string will be hashed with SHA-256 algorithm.  The function contains a loop condition that only allow account creation when password and re-enter password field match.  It will then store all three fields into a credentials text file using Print Writer method provided by Java.  This function included quit button and designed in graphical user interface layout.  It was created as a separate class file and can be called by “Create Account” button click from main GUI.  I also added a new job role for this function which is new user job role.  Instead of zookeeper, admin, and veterinarian, newly account will be defaulted with new user job role and will output appropriate job description when credentials matched at main GUI.  Both main authentication GUI and create account class will share access to credential text file.  

The reason I chose this second enhancement project because it satisfies algorithm and data structure aspect of computer science requirement.  SHA-256 hashing will touch base with algorithm side and creating account class will touch base with data structure side.  Also this second enhancement allow myself to display skills such as: articulate approach to solving complex logic, employing various data structures when constructing program, design simple object-oriented with data abstraction and information hiding, implementation of hashing algorithm, usage of software libraries, compilers, editors, and debuggers to produce effective software, and display understanding of essential semantic structures of programming language such as values, types, storage, control flow, and etc.

## Repository Link

[Link to Artifact Enhancement 2 Repository](https://github.com/bdoan95gl/bdoan95gl.github.io/tree/Artifact-2)

## Table of Contents Links
[Home Page](https://bdoan95gl.github.io)

[Professional Self-Assessment](https://bdoan95gl.github.io/selfassessment)

[Informal Code Review](https://bdoan95gl.github.io/codereview)

[Artifact Enhancement 1](https://bdoan95gl.github.io/artifact1)

[Artifact Enhancement 2](https://bdoan95gl.github.io/artifact2)

[Artifact Enhancement 3](https://bdoan95gl.github.io/artifact3)
