# terraform-for-instance

Terraform to create, update tag/machine type, and destroy Google Cloud instances. 


### Note: machine type cannot change while instance on so used "allow_stopping_for_update argument to true" to ensure the VM stops before updating the machine_type.
