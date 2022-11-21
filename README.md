# sam-cogans-api-infrastructure
Bicep for Real training

Deploy regularly to test if resources are successfully deployed via code.
<!-- Open powershell -->
<!-- Create resource group in location west europe-->
az group create --name sam-api-dev --location westeurope
<!-- deploy infra via bicep -->
az group deployment create -g sam-api-dev --template-file .\directory\core.bicep

or

az deployment group create --resource-group sam-api-dev --template-file .\directory\core.bicep

