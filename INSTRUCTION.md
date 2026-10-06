This module creates a resource group and a storage account. 
It accepts variables such as `resource_group_name`, `storage_account_name`, and `location`. 
The outputs are `resource_group_id` and `storage_account_id`.

Module example:

module "resource_group_storage" {
  source               = "trickytenshi/resource_group_storage/azurerm"
  version              = "1.0.0"
  resource_group_name  = "mate-resources1"
  storage_account_name = "matestorage3639"
  location             = "West US"
}
