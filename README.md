# College-Notes-Gallery
## A notes management system which helps users to upload,download and manage notes... The whole system is coded in core PHP and MySqli

### Requirements 

- PHP 5.3 or higher recommended 
- MySQL DB
- Ability to write .htaccess file for apache mod_rewrite

### Installation
- Upload College-Notes-Gallery to the directory of your choice. (E.g :  /var/www/html/college-notes-gallery )
- Import MySql Db file to your database software (E.g : PhpMyAdmin -> Create DB -> Import notes.sql  )
- Configure connection between your database and server by modifying the /includes/connection.php file
- Navigate to the installation in your browser ( E.g :  http://localhost/college-notes-gallery )
- Done :)

### Login Details

1. Admin:

username: root

password: adminroot

2. User:

username: user

password: userpass

### Main Features

- Multiple user access:  Allows multiple type of users(teacher/student/admin) to login 
- Functional Admin panel:  Allows admins to manage the whole system
- CRUD functionalities:  Allows all users to create,read,update and delete their notes in a managed format 
- Profile update option:  Allows users to update their profile/account details  
- Secure registration and login option for users
- Allows students and teachers to download/upload their course notes easily
- Allows users to recover their password using forgot password option
