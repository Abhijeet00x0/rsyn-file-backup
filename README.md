# rsyn-file-backup
Bash script for easy file level rsync backup. Comes in handy while taking care of backups in the production environment. This script will pull the data from the source. The source can be any server located at the internet with a public IP or whether inside the LAN environment. After the backup is done the scrip will send out the notification & log information to the email address provided.

Script can be used in Crontab to simplify the automation. 

The first time execution will result in a complete backup of the files. If when executed second time the incremental backup will be performed. 
