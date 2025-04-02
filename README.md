Terraform State Refresh

The terraform refresh command reads the current settings from all managed remote objects found in Terraform state and updates the Terraform state to match.

Refreshing state is the first step of the terraform plan process: 
read the current state of any already-existing remote objects to make sure that the Terraform state is up-to-date. 
If you wish to only perform the first part of the terraform plan process you can execute the plan with a -refresh-only.

     1: terraform refresh command
     2: Show state before refresh
     3: Introduce drift
     4: Refresh state to detect drift
     5: Show state after refresh
     6: Controlling state refresh
