# Azure ScalSet VM 
This repo for Azure Scale set to spin up VMs using terraform. This help to spin infrastructure just single command. 

## Terraform State

- Local State


| Variable      | Value | Description |
| ------------- | ------------- | ------------- | 
| location       | west europe   | Location use for spin up the resouces for that location |
| tags       | development   | tags are used for mapping the resouces to specfic tags like development, department, requester name |
| resource_group_name        | nsadiq-rg   | resouce group are use to keep all resouces in a specfic resouce group, its just like resouce container |
| application_port        | 80  | Port 80 will use for application  |
| admin_user        | adminuser  | username for the VM if you want to SSH or login  |
| admin_password        | Anything compatible with password policy  | use for login to machine  |