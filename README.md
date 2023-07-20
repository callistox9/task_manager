![9](https://github.com/callistox9/task_manager/assets/77205073/c581d049-1d22-42f1-8aa3-cbe0710d3a03)
# Task Manager with PHP and MySQL
Simple Task Manager web app with PHP and MySQL.

## Technologies Used
1. Core PHP Programming Language (Procedural Programming)
2. MySQL Database
3. HTML
4. CSS

## How to Download and Run on your PC?

### Pre-Requisites:

1. Download and Install XAMPP

[Click Here to Download](https://www.apachefriends.org/index.html)

2. Install any Text Editor (Sublime Text or Visual Studio Code or Atom or Brackets)

### Installation

1. Download as as Zip or Clone this project
2. Move this project to Root Directory
```
Local Disc C: -> xampp -> htdocs -> 'this project'
```
*Local Disk C is the location where xampp was installed*

3. Open XAMPP Control Panel and Start 'Apache' and 'MySQL'

4. Import Database

a. Open 'phpmyadmin' in your browser
b. Create a Database
c. Import the SQL file provided with this project

5. Make Changes to settings

Go to 'config' folder and Open 'constants.php' file. Then make changes on following constants
```php
<?php 
//Start Session
session_start();

//Create Constants to save Database Credentials
define('LOCALHOST', 'localhost');
define('DB_USERNAME', 'root'); //Your Database username instead of 'root'
define('DB_PASSWORD', ''); //Your Database Password instead of null/empty
define('DB_NAME', 'task_manager'); //Your Database Name if it's not 'task_manager'

define('SITEURL', 'http://localhost/task-manager/'); //Update the home URL of the project if you have changed port number or it's live on server

?>
```

6. Now, Open the project in your browser. It should run perfectly.

   Here are some practical screenshots of my project and also how to configure it on your system.
   <1> Open the localhost/phpmyadmin/ address 
   ![1](https://github.com/callistox9/task_manager/assets/77205073/59a4a670-3e0a-404d-80a7-357a38729084)

   <2> Import the task-manager.sql present in the project.
   ![2](https://github.com/callistox9/task_manager/assets/77205073/503db09b-029d-41ab-bd77-bd97bf39748f)

   <3> Start xampp server.Apache and MySQL.
   ![3](https://github.com/callistox9/task_manager/assets/77205073/29941e47-84f9-4a14-b1f1-c52d8dacfba9)

   <4> Edit the 'constants.php' file according to your database configuration.Here is mine.
   ![4](https://github.com/callistox9/task_manager/assets/77205073/94c84839-9f22-45da-be85-5e2180e7f1c6)

   <5> Now open the link in your browser localhost/task_manager-main/.(task_manager-main is the name of the 
       project folder.
   ![5](https://github.com/callistox9/task_manager/assets/77205073/800c487e-d008-4866-a6bb-f29ec1bf7385).

   Here are working Screenshots.
   ![6](https://github.com/callistox9/task_manager/assets/77205073/5f247521-f58c-466c-b5e0-8d9413782a64)
   ![7](https://github.com/callistox9/task_manager/assets/77205073/2855fe68-75fb-42c9-a4fe-ef2dba938f4e)
   ![8](https://github.com/callistox9/task_manager/assets/77205073/d6ed5a8e-20ed-4df9-9502-87bbdb486bf3)
   ![9](https://github.com/callistox9/task_manager/assets/77205073/9cec057d-7750-4fcd-8169-244350408ba9)
   ![10](https://github.com/callistox9/task_manager/assets/77205073/cd25a8d5-d1ed-4dd9-92e5-a378da27a802)



