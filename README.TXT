HALOGY 1.0 INSTALLATION GUIDE
=============================

Thank you for downloading Halogy. This guide provides the basic steps needed in order to get Halogy running on your server. 


QUICK START GUIDE
------------------------------

1. Download the latest repository from http://bitbucket.org/haloweb/halogy-1.0
2. Extract the contents in to your Web Root folder (including the '/static' folder, 'index.php' and the '.htaccess' files).
3. Run the provided SQL dump in your MySQL database.
4. Configure your database settings in the '/halogy/application/config/database.php' file.

-- NOTE: At this point Halogy should run on your domain, but for security reasons we suggest you continue --

5. Move the '/halogy' outside of the Web Root, for example in to the parent directory, or a Code repository folder.
6. Edit the 'index.php' file, go to Line 45, and change the path to your new system folder (e.g. '../halogy').

-- TESTING A NEW SITE --

7. Go to 'mydomain.com/admin'.
8. Login with the default superuser account: (superuser / super123).
9. Change your superuser password to a more secure password and then create a website administrator by clicking on Users.

You should now be good to go.


FURTHER CONFIGURATIONS
------------------------------

Because Halogy is built upon the amazing CodeIgniter framework (http://codeigniter.com), you can easily extend and modify Halogy to
your hearts content. There are also configurations you can make to Halogy using the standard CodeIgniter configuration files, for
example the database.php (in /halogy/application/config), the config.php (for character encoding and compression settings), etc.

PLEASE NOTE: If you modify Halogy we will no longer be able to support it.


MODULES
------------------------------

Official modules can be purchased from our shop at http://www.halogy.com/shop, however you are free to develop your own modules by
just building mini-applications (see the CodeIgniter and HMVC documentation) and dropping them in to the Modules folder inside 
Application. You can then access the modules by going to yoursite.com/module.



YOUR LEGAL OBLIGATION
------------------------------

By using Halogy you agree to be bound by the license terms and conditions stated on our website: 

http://www.halogy.com/license

