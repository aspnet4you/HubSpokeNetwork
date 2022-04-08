# HubSpokeNetwork
Azure ARM Template to Create Hub Spokes Virtual Network with Two Spokes and a Hub. For simplicity, this template does not create additional resources like Virtual Machine, NAT Gateway, Bastion, Log Analytics, etc. You will need to add them once virtual network is provisioned.

Open PowerShell ISE and change the path to solution folder

Update the Parameters in azuredeploy.json

Update the Parameters Deploy-AzureResourceGroup.ps1 : location, tenant id and subscription id are required.

Run Deploy-AzureResourceGroup.ps1 in PowerShell ISE and Follow the prompt.

