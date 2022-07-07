## ALXT Infrastructure as Code Challenge
This project creates the required Infrastructure-as-code scripts for a new cloud environment in AWS
The infrastructures are:
 - VPC
 - Internet Gateway (for internet access into and out of the vpc)
 - 2 private subnets (where our web services would be running on)
 - 2 public subnets (for direct interaction of users). All act as a facade for the private subnets.
 - Nat Gateways (facades for our running services).
 - Route table (for traffic control within the vpc and between the subnets).
