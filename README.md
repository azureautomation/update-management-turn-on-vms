Update Management - Turn On VMs
===============================

            


This script is intended to be run as a part of Update Management Pre/Post scripts.

It requires the ThreadJobs modules from the PowerShell gallery.


UpdateManagement-TurnOnVms.ps1 requires a RunAs account.
AUpdateManagement-TurnOnVms.ps1 uses Az cmdlets and System Managed Identity.

This script will ensure all Azure VMs in the Update Deployment are running so they recieve updates.
This script works with the [Turn Off VMs](https://gallery.technet.microsoft.com/Update-Management-Turn-Off-be60ed99) script. It will store the names of machines that were started in an Automation variable so only those machines are turned back off when the deployment is finished.


 





        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
