# dataaibootcamp
This repository contains the ARM Templates to create Azure DataFactory, Azure Analysis Services, Virtual Networks, SQL Server and Database.

To deploy the Infrastructure run the below command:

New-AzResourceGroupDeployment -ResourceGroupName "<RGName>" -TemplateUri https://raw.githubusercontent.com/nandakishoresai/dataaibootcamp/master/DataAIARMTemplatesProj/DataAIARMTemplatesProj/DemoARMTemplate.azuredeploy.json -Verbose
