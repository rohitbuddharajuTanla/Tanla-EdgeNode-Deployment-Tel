# Azure Kubernetes and dependencies Deployment Template

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FrohitbuddharajuTanla%2FTanla-EdgeNode-Deployment-Tel%2Fmaster%2Fdeployment.json" target="_blank">
    <img src="https://azurecomcdn.azureedge.net/mediahandler/acomblog/media/Default/blog/deploybutton.png"/>
</a>


This sample template creates following Azure components and its dependencies.

1. Azure AKS Instance.
2. Virtual network, Subnet, Network Security Group.
3. Event Hub
4. Log Analytics workspace
5. Redis Cache
 
 Create a resource group with below command

PS> New-AzureRmResourceGroup -Name perf-Tan-SI-RG-AKS-01 -Location "South Central US"

The purpose of this template is to deploy AKS cluster with all of dependent resources.

