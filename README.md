# Deployment-and-configuration-of-a-Private-Cloud-in-AWS
Ex.4 Deployment and configuration of a Private Cloud  in AWS

Aim:
To set up of a Private Cloud  in AWS.
         Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources. This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.
Procedure:
1. Plan Your VPC:
● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.
● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
● Plan internet connectivity:
Determine if you need public internet access and how to configure it.
● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.
2. Create Your VPC:
•	Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
•	 Choose "Create VPC": Initiate the VPC creation process.
•	Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
•	other necessary settings.
•	Create subnets: Define subnets within your VPC to isolate different parts of your
•	network.
•	Create route tables: Specify how traffic is routed within and outside the VPC.
•	 Create security groups: Define access control rules for your resources.
3. Deploying Resources:
•	Launch EC2 instances: Create and launch virtual machines within your VPC.
•	 Set up RDS instances: Deploy databases for your applications.
•	Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.
•	Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.
4.Managing and Monitoring:
•	Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.
•	Configure logging and auditing: Track access and activity within your VPC for
security and compliance.
•	Implement security best practices: Regularly review and update your security
configuration.
•	Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.

Snap Shot:

 

Snapshot 1: Create VPC

 <img width="1917" height="962" alt="Screenshot 2026-10-29 152403" src="https://github.com/user-attachments/assets/4ba2ea57-dc6c-4604-b8f3-4643ec24f0c3" />

<img width="1917" height="961" alt="Screenshot 2026-10-29 152444" src="https://github.com/user-attachments/assets/7baef7c4-397a-418f-a9de-f814447481e9" />


Snapshot 2: Configuring Subnets
 
<img width="1917" height="962" alt="Screenshot 2026-10-29 153327" src="https://github.com/user-attachments/assets/8848c56d-1e29-4dcf-be56-e5594487090c" />


Snapshot 3: Configure Subnets
 
<img width="1917" height="962" alt="Screenshot 2026-10-29 153327" src="https://github.com/user-attachments/assets/e97be227-b811-4b92-9c90-d337a8b03474" />

Snapshot 4: Setting Internet gateway
<img width="1917" height="951" alt="Screenshot 2026-10-29 153823" src="https://github.com/user-attachments/assets/95ee93ab-7b41-410e-9d4a-a97a2a4632cf" />

 
Snapshot 5: Setting Internet gateway

<img width="1917" height="958" alt="Screenshot 2026-10-29 154055" src="https://github.com/user-attachments/assets/dd148e76-5ff7-4e5b-9ca4-36871c251888" />


 

Snapshot 6: Setting Internet gateway

<img width="1917" height="950" alt="Screenshot 2026-10-30 141222" src="https://github.com/user-attachments/assets/ddbf7ee0-8247-49fb-8f6e-16dff575d723" />

 
Snapshot 7: Creating route table

 
<img width="1917" height="957" alt="Screenshot 2026-10-30 141329" src="https://github.com/user-attachments/assets/1fec97c0-d251-49f6-a0a0-5c1f541168e6" />


 
Snapshot 10: Creating route table






<img width="1917" height="1013" alt="Screenshot 2026-10-30 141659" src="https://github.com/user-attachments/assets/64d96d7c-61ac-4269-9e2f-8a339dc38cbe" />








# Grade:
<img width="606" height="642" alt="image" src="https://github.com/user-attachments/assets/f88864e1-d27e-4cee-bddf-9bf04834e207" />





Result:
Thus, a  private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.
 
