# Azure-Security-and-Governance-Aides
A collection of assets I created to help improve security and governance operations for Azure environments

1. Azure Public IP Address Inventory Workbook- 
  This workbook lists all Azure Public IP Addresses per subscription, resource group and location in the Azure environment. This inventory is collected from the Azure Resource Graph and should enable any organization to stay updated on the Public IP addresses that they are responsible for securing.
  It uses Azure Resource Graph as it provides the most reliable way of identifying which Public IP Address resources that have been provisioned in your Azure environment. It also details the region, subscription or resource groups do these IP Addresses belong or if the allocation method is static versus dynamic.
  Some of the resources you can associate a public IP address resource with are:
  Virtual machine network interfaces, Internet-facing load balancers, VPN gateways, Application gateways and Azure Firewall
