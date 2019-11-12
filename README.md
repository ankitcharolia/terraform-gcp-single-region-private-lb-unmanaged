# Deploying GCP VMs in unmanaged instance group with a load balancer using Terraform

The script will install Apache web server on the virtual machines for testing purposes.

network-firewall.tf --> Configure basic firewall for the network

network.tf --> Define network, vpc, subnet, icmp firewall

provider.tf --> Configure Google Cloud provider

terraform.tfvars --> Defining variables 

variables-auth.tf --> Application and authentication variables

vm.tf --> Create a Ubuntu VM using Apache

vm-output.tf --> Output of VM 

# Notes

Check list of Google Cloud OS images --> https://cloud.google.com/compute/docs/images

Create the Json file for authentication --> https://cloud.google.com/iam/docs/creating-managing-service-account-keys

Read the post for the repo --> https://medium.com/@gmusumeci/getting-started-with-terraform-and-google-cloud-platform-gcp-e718017376d1
