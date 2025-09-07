# 6th-Lab-Optimized-cutom-skill-Search-
This is optimized final lab. This lab guide will ignore the creation of Azure storage account and Azure Function app. creation of these resourcs will be handled by the ARM template provided with this guide. 
During the deployment it will ask for unique prefix to make things unique. enter some string during ARM template deployment.

#to deploy ARM template

`az group create --name omnicorp-customskillsearch --location eastus`

`az deployment group create --resource-group omnicorp-customskillsearch --template-file azuredeploy.json`
