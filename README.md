# wp2zip
Wordpress backup to .ZIP including MySQL dump

Upload script to Wordpress root directory, i.e. where wp-config.php resides. It reads database connection settings from wp-config.php and dumps the MySQL database to an .sql file. It then creates a compressed .zip archive of all Wordpress files/dirs and triggers the browser to download .zip archive to the caller's computer.

**N.B.** the script does not encrypt the .zip nor does it delete the generated .sql or .zip files making them available for anyone to download should they know the name of the files. Also, there is no access control which means that anyone can call the script. Additional work needs to be done in order to eliminate these issues.
