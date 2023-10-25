Azure resource group
This template deploys a Linux virtual machine (VM) with infrastructure that includes a virtual network, subnet, public IP address, and more.

Terraform resource types
random_pet

azurerm_resource_group

azurerm_virtual_network

azurerm_subnet

azurerm_public_ip

azurerm_network_security_group

azurerm_network_interface

azurerm_network_interface_security_group_association

random_id

azurerm_storage_account

azurerm_linux_virtual_machine

azapi_resource

azapi_resource_action

Variables
Name	Description	Default
resource_group_name_prefix	Prefix of the resource group name that's combined with a random ID so name is unique in your Azure subscription.	rg
resource_group_location	Location of the resource group.	eastus
username	The username for the local account that will be created on the new VM.	azureadmin
Example
To see how to run this example, see Quickstart: Configure a Linux virtual machine in Azure using Terraform.
