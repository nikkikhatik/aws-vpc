\# AWS VPC Infrastructure using Terraform (IaC)



Production-grade VPC infrastructure provisioned on AWS using Terraform.



\## Architecture Resources Provisioned

\- \*\*Custom VPC\*\* with CIDR `10.0.0.0/16`

\- \*\*Public Subnet\*\* (`10.0.1.0/24`) with Auto-assign Public IP

\- \*\*Internet Gateway (IGW)\*\* for outbound internet connectivity

\- \*\*Public Route Table\*\* with route associations

\- \*\*Security Group\*\* allowing Ingress on Port 80 (HTTP) \& Port 22 (SSH)



\## How to Deploy



1\. Configure AWS CLI credentials:

&#x20;  ```bash

&#x20;  aws configure

