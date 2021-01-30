## CS499 ePortfolio

By: Bao Doan

### Authentication System Code Review Video

{% include videoPlayer.html id=page.youtubeId %}

### Artifact Enhancement 1

[Link to Artifact Enhancement 1](https://github.com/bdoan95gl/bdoan95gl.github.io/blob/main/artifact1.md)


### Artifact Enhancement 2

For this second enhancement, I have implemented SHA-256 hashing to my program instead of MD5 hashing as well as adding “Create Account” function for my program.  Both MD5 and SHA-256 are hashing algorithm that take in input values and return a fixed-length value that have no discernable pattern.  MD5 produce 128-bit hash value while SHA-256 produce 256-bit hash value.  Current researched indicate that SHA-256 hash algorithm is considerably more secure than MD5 hash algorithm.  For my program, switching from MD5 to SHA-256 was a smooth process since Java security message digest library contains both algorithms.  I only had to replace “getInstance” value from MD5 to SHA-256.  

The second portion of this enhancement is adding “Create Account” function.  This function will take in three fields of input: username, password, and re-enter password.  Once all three fields are filled out and password and re-enter password field matched, password string will be hashed with SHA-256 algorithm.  The function contains a loop condition that only allow account creation when password and re-enter password field match.  It will then store all three fields into a credentials text file using Print Writer method provided by Java.  This function included quit button and designed in graphical user interface layout.  It was created as a separate class file and can be called by “Create Account” button click from main GUI.  I also added a new job role for this function which is new user job role.  Instead of zookeeper, admin, and veterinarian, newly account will be defaulted with new user job role and will output appropriate job description when credentials matched at main GUI.  Both main authentication GUI and create account class will share access to credential text file.  

The reason I chose this second enhancement project because it satisfies algorithm and data structure aspect of computer science requirement.  SHA-256 hashing will touch base with algorithm side and creating account class will touch base with data structure side.  Also this second enhancement allow myself to display skills such as: articulate approach to solving complex logic, employing various data structures when constructing program, design simple object-oriented with data abstraction and information hiding, implementation of hashing algorithm, usage of software libraries, compilers, editors, and debuggers to produce effective software, and display understanding of essential semantic structures of programming language such as values, types, storage, control flow, and etc.

[Link to Artifact Enhancement 2](https://github.com/bdoan95gl/bdoan95gl.github.io/tree/Artifact-2)

### Artifact Enhancement 3

For this third enhancement, I have implemented database storage instead of text file storage from the previous enhancements.  The functionality of the authentication program remains the same.  It still able to perform login, create account, SHA-256 string hash, failed login attempts, and display GUI.  But instead of storing and comparing values from a text file, the program will now connect to a database for storage and comparing value.  Mysql-connector-java-8.0.13.jar file and phpMyAdmin were utilized to establish database connection and database management.   Mysql connector jar file enables the building of database, database connection, and perform java query command toward database.  phpMyAdmin program allow me to the view content of the database and make sure my third enhancement can manipulate data on the database.  The default database information for this third enhancement includes “authdb” for database name, database server will be on local host, root access privilege with “bao123” for password.  I’m using MySQL as relational database management system for this third enhancement.  Beside database conversion, I also added a feature on my program to check for existing username within database.  When user trying to create an account with existing username, the program will display appropriate matched credentials message and decline account creation.

The reason I chose this third enhancement is to display my ability in implement approach to ensure data are explicitly validated, implementation of database, display mySQL techniques CRUDs and query concepts, implementation of java to database cross platform, arrays and control structures with database, and implementation of external database software such Xampp and PHP.

[Link to Artifact Enhancement 3](https://github.com/bdoan95gl/bdoan95gl.github.io/tree/Artifact-3)
