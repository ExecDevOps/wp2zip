# wp2zip
Wordpress backup to .ZIP including MySQL dump

When this PHP script is called it reads database connection settings from Wordpress' wp-config.php and dumps the MySQL database to the Wordpress root directory. It then creates a zip file of all Wordpress files and downloads it so the caller can save it to disk.

**N.B.** the script does not encrypt the .ZIP nor does it delete the generated .SQL oc .ZIP files leaving these available for anyone to download should they know the name of the files. Also, there is no access control which means that anyone can call the script. 
