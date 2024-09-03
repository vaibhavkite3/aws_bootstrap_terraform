# aws_bootstrap_terraform
Create and Manage AWS Infrastructure with this all-in-one Terraform code

Bare Minimum AWS infrastructure Setup for a Medium Sized Company: Example - Travelling Company - MakeMyTrip

This setup assume you have atleast a AWS Root account and one or more sub-account created and running with AWS Profile setup/configured for this secondary account on executor machine
As this will create a Infra in a sub-account.

## Required Parameters

1. init.sh
   
2. plan.sh
   AWS Profile -p
   EnvironmentPreFix -e
   ModuleName -m
   Region -r

3. apply.sh
   AWS Profile -p
   EnvironmentPreFix -e
   ModuleName -m
   Region -r

4. destroy.sh
