# CodeIgnitorBlogCode
This repository contains Blog code developed in CodeIgnitor PHP Framework.
Database also kept in .sql file format, so that you can directly import the DB in PhpMyAdmin.

<b> How to import and connect your Database to CIBlog Application. </b> <br/>
Step 1 : Extract ZIP file to folder (Ex. your folder name is "ciblog") and place that folder to path "\wamp\www\ciblog\".
[Here "ciblog" is your folder in which you have placed all the files and folders from downloaded clone]

Step 2 : now open PhpMyAdmin and create a database with name as "ciblogs". with 'charset' = 'UTF-8'.

Step 3 : Now Import the DB "ciblog.sql" placed in folder "Database" in your clone. And remove the Database folder from wamp\www\ciblog\.

Step 4 : Now go to browser and open the url "localhost/ciblog/". 

And you're all set.
This is basic code in this project you can Add Posts without login, Add Categories, Users can Register, check Categories, Comments Section is also developed.

NOTE:
If you want to change the Database name in code go to path ..\application\config\database.php and edit database.php file edit 'database' => 'ciblog' [ Where "ciblog" is your DB Name] 

You can freely use this code to develop your application/website.

