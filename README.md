## Getting started
Copy all the files into the htdocs/ directory inside the Xampp. (You have installed [xampp](https://www.apachefriends.org/download.html), right?)

Afterward, start the Apache server and MySql inside the Xampp control panel,
go to phpmyadmin in the browser via clicking the `admin` button beside the MySql,
and create a database name `preschool_system`. While selecting that database,
go to `import` tab and select the preschool_system.sql from this repo.
Remember to disable the foreign key checks while importing the file.

At last, go to `localhost/index.html` with browser of your choice.

# KidsPreschoolLearningSystem
role: 1 - student
      2 - teacher

status: 1 - active
        2 - inactive

Li Sheng's work
Play around with courses table.

For teacher:
manageCourse.php
-----------
course#index (with edit, delete options)
course#new
course#update
course#delete
embedded youtube video via youtube id (?)

For Student:
courselist.php
--------------
course#index

viewcourse.php
-------------
course#show (course info and... education stage?)

Vincent's work:
mainly use user table.
manageStudent.php
----------------
add student
delete student
edit student
create a table list show all student by filter who is active with edit delete option
