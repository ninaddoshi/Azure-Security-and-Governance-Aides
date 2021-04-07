# Azure-Security-and-Governance-Aides
A collection of assets I created to assist  security and governance operations for Azure environments

1. Azure Public IP Address Inventory Workbook- 
  This workbook lists all Azure Public IP Addresses per subscription, resource group and location in the Azure environment. This inventory is collected from the Azure Resource Graph and should enable any organization to stay updated on the Public IP addresses that they are responsible for securing.
  It uses Azure Resource Graph as it provides the most reliable way of identifying which Public IP Address resources that have been provisioned in your Azure environment. It also details the region, subscription or resource groups do these IP Addresses belong or if the allocation method is static versus dynamic.
  Some of the resources you can associate a public IP address resource with are:
  Virtual machine network interfaces, Internet-facing load balancers, VPN gateways, Application gateways and Azure Firewall
  
  To import the workbook into your environment:
  1. Open the workbook asset in this repo and click on the [RAW] button.
  2. Copy the file content.
  3. Open Azure Monitor, Azure Sentinel or Azure Security Center. in your Azure environment. Go Workbooks and click to create a new workbook.
  4. Select the </> icon to enter the Advanced Editor.
  5. Paste the copied JSON from step 2 to replace the existing JSON content.
  6. Click Apply and then click Save
  7. Enter the required details for saving the workbook and save the workbook.
    
