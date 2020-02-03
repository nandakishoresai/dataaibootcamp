# dataaibootcamp
This repository contains the ARM Templates to create Azure DataFactory, Azure Analysis Services, Virtual Networks, SQL Server and Database.

For multiple subscriptions: 
Set-AzContext -SubscriptionId <SubscriptionId> 

To deploy the Infrastructure run the below command:

New-AzResourceGroupDeployment -ResourceGroupName "<RGName>" -TemplateUri https://raw.githubusercontent.com/nandakishoresai/dataaibootcamp/master/DataAIARMTemplatesProj/DataAIARMTemplatesProj/DemoARMTemplate.azuredeploy.json -Verbose  

To deploy the Azure Analysis Service

New-AzResourceGroupDeployment -ResourceGroupName "<RGName>" -TemplateUri https://raw.githubusercontent.com/nandakishoresai/dataaibootcamp/master/DataAIARMTemplatesProj/DataAIARMTemplatesProj/Foundation/CreateAnalysisService.json -Verbose

