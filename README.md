# AZ-400-WorkShops

## Mind enabling your Devops organization for CI/CD

Check the steps down below

---
Configuration:
    title: 'Validate lab environment'    
---

# Comfiguration: Validate lab environment

## Instructions

1. Get a new Azure Pass promocode (valid for 30-days) from the instructor or other source.
2. Use a private browser session to get a new Microsoft account (MSA) at account.microsoft.com or use an existing one.
3. Using the same browser session, go to Microsoftazurepass.com to redeem your Azure Pass using your Microsoft account (MSA). [Redeem a Microsoft Azure Pass](https://www.microsoftazurepass.com/Home/HowTo?Length=5) Follow the instructions for redemption. 
4. Using the same browser session, go to portal.azure.com, then search for “Azure DevOps”. In the resulting page, click Azure DevOps Organizations. 
5. Next, click on the link called “My Azure DevOps Organizations” (or navigate to https://aex.dev.azure.com/).
![](https://raw.githubusercontent.com/cemvarol/AZ-400-WorkShops/master/DevopsOrgCreate/01-GetInfo.png)
7. In the drop-down box on the left, choose Default, instead of “Microsoft Account”.
![](https://raw.githubusercontent.com/cemvarol/AZ-400-WorkShops/master/DevopsOrgCreate/02-FirstSituation.png)
9. Create a new organization (find blue box in upper right-hand corner of the screen) using the Default directory. 
![](https://raw.githubusercontent.com/cemvarol/AZ-400-WorkShops/master/DevopsOrgCreate/03-ChangeDir.png)
11. Choose the newly created organization, then choose Organization settings on the left-hand side of the screen.
![](https://raw.githubusercontent.com/cemvarol/AZ-400-WorkShops/master/DevopsOrgCreate/04-DoAgain.png)
![](https://raw.githubusercontent.com/cemvarol/AZ-400-WorkShops/master/DevopsOrgCreate/05-SecondSituation%20-%20.png)
![](https://raw.githubusercontent.com/cemvarol/AZ-400-WorkShops/master/DevopsOrgCreate/06-Final.png)
13. Navigate to Organization settings -> Billing -> Setup billing -> Select an Azure subscription, and click Save (It must be Azure Pass subscription)
14. Choose “MS Hosted CI/CD” and set the field “Paid parallel jobs” to 2. Then click SAVE in the blue box at the bottom. 
15. Wait at least 3 hours before using the CI/CD capabilities so that new settings are reflected in the back end. Otherwise, you will still see the message “This agent is not running because you have reached the maximum number of requests…”. This may not be necessary.
16. As an optional step, validate this by creating a new pre-defined project using the newly created org with billing enabled, using https://azuredevopsdemogenerator.azurewebsites.net/. Wait for some time before trying, then run a test build.



### If does not work; ###
### Send an email to azpipelines-freetier@microsoft.com ### 


### [Please read this Article](https://devblogs.microsoft.com/devops/change-in-azure-pipelines-grant-for-private-projects)
