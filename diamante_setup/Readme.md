Diamante Application is Open Sourced by Ukraine based Startup company called Eltrino @ https://github.com/eltrino/diamantedesk-application

We’ve forked the application source and used “2.0-api-fix” branch containing fixes for REST API available @ https://github.com/birender-s/diamantedesk-application/tree/2.0-api-fix 

Installation can be readily achieved by leveraging shell script file “Diamante_Installation_Script_v1.sh” that wraps big list of commands to make life easier.
Steps
Create new VM instance - Ubuntu 16.04
Login to VM instance and creat new shell script (say setup.sh) and add content copied from atached file
Switch to sudo user - “sudo su”

run script and provide mysql password 123456

Enter root password - 123456


Select No (anything except yes) for all other options 




Once script completes, final output looks something like this:


Login to app via browser e.g. - http://35.184.38.171/install.php 
Note: use http instead of https






create new database named “diamante” as follows:
mysql -u root -p
mysql> create database diamante;

provide db details in web console as follows (password 123456)



Keep system settings as default (no chage)

In below section, replace localhost with IP address e.g. “35.184.38.171” shown below and provide username, password details.



Final step looks somewhat like this:



