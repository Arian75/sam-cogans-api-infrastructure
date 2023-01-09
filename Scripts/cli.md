To run a script from CLI which deploys the bicep file along with the parameters file to a RG

 az deployment group create --name SamsDeployment  --resource-group sam-cogans-infra --template-file .\infrastructure\core.bicep --parameters .\configurations\dev.json

 ---
 To have an overview of RGs that are seen:
 Use: az group list