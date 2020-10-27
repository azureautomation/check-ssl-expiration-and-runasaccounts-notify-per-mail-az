Check SSL expiration and RunAsAccounts - notify per mail [Az]
=============================================================

            

 

This runbook will check all certificates, within your subscription, on expiration date.
It now checks for the expiry of your RunAsAccounts as well.
By default it uses sendgrid for mail notifications.

 


#This script has been created by Bram Stoop
#Feel free to visit my website https://bramstoop.com/ and leave me comments/give me feedback on this runbook
#You can also follow me on twitter https://twitter.com/bramstoopcom



Make sure you have the Az.Accounts, Az.resources, Az.websites and Az.automation modules installed withing Azure Automation.
 Keep in mind that the Sendgrid username has this format azure_somekindofnumber@azure.com - this can be found in the azure portal


 








        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
