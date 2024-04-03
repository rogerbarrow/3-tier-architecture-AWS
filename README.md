# 3-tier-architecture-AWS

![image](https://github.com/rogerbarrow/3-tier-architecture-AWS/assets/46138186/c67faf5b-bc24-485c-aea8-4b1c7afdfb27)
# Make a folder on your PC and Clone Project
``` 
git clone https://github.com/aws-samples/aws-three-tier-web-architecture-workshop.git

```
![image](https://github.com/rogerbarrow/3-tier-architecture-AWS/assets/46138186/de005163-0735-47da-8bd5-4700dd98e113)

#S3 Bucket Creation
![image](https://github.com/rogerbarrow/3-tier-architecture-AWS/assets/46138186/9a37efaf-c5bd-4273-aabb-bd0e73bd3afa)
# Create a New IAM role by going to the IAM dashboard
* ![image](https://github.com/rogerbarrow/3-tier-architecture-AWS/assets/46138186/3023e0a2-6154-4195-886b-b3aefa7aab91)

#Select Ec2 as the trusted entity
* ![image](https://github.com/rogerbarrow/3-tier-architecture-AWS/assets/46138186/cc982460-aaed-4104-b011-d560785f93d7)
   When adding permissions, Include the following AWS Managed policies
  * amazonSSMManagedinstancecore
  * AmazonS3ReadOnlyAccess
# Network and Security
* Create an isolated network with the folling components
* VPC
* Subnets
* Route Tables
* Internet Gateway
* NAT Gateway
* Security Group
# Create a VPC
* ![image](https://github.com/rogerbarrow/3-tier-architecture-AWS/assets/46138186/505bd9b8-82a3-4668-b42b-499aa8bd8d2b)
* Create subnet (We will Create 6 Subnets in 2 Availability Zones)
* ![image](https://github.com/rogerbarrow/3-tier-architecture-AWS/assets/46138186/4eefaa5d-1a49-4ce2-9d68-6473784676cf)
* ![image](https://github.com/rogerbarrow/3-tier-architecture-AWS/assets/46138186/27b49be6-e070-4924-9c26-442a0243687e)
* ![image](https://github.com/rogerbarrow/3-tier-architecture-AWS/assets/46138186/99c1611e-0c67-4ba2-882f-603d6a6012a6)
# Next We Create a Internet Gateway
 * ![image](https://github.com/rogerbarrow/3-tier-architecture-AWS/assets/46138186/90de7f4f-6e9e-4997-9a1a-ef62941124a0)





