Monitor azure online backup of multiple servers
===============================================

            

This simple script is used to monitor online backup (OB) of azure servers.It reads the server lists,checks the status of the backups and returns the result in csv format.


The O/P of the script is shown below.


![Image](https://github.com/azureautomation/monitor-azure-online-backup-of-multiple-servers/raw/master/Capture.JPG)


The script uses the below command to retreive the backup information.


 

 The script needs to run Enable-PSRemoting to configure winRM service and firewall.

 


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
