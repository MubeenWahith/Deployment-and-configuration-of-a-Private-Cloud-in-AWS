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


<img width="1917" height="961" alt="Screenshot 2026-10-29 152444" src="https://github.com/user-attachments/assets/fd6f75f4-509b-47c7-a872-6902cb9dbfae" />

 
Snapshot 2: Configuring Subnets
 
<img width="1917" height="965" alt="Screenshot 2026-10-29 153121" src="https://github.com/user-attachments/assets/c7b86694-779a-4f6c-bf11-b8131e645a0f" />


Snapshot 3: Configure Subnets
 
<img width="1917" height="965" alt="Screenshot 2026-10-29 153121" src="https://github.com/user-attachments/assets/12440fc4-95f1-4f39-b356-fe2e1ba5ad26" />


Snapshot 4: Setting Internet gateway


 
Snapshot 5: Setting Internet gateway


<img width="1917" height="962" alt="Screenshot 2026-10-29 153327" src="https://github.com/user-attachments/assets/92ad3217-4473-4c0b-a45e-d10096b55ce2" />

 

Snapshot 6: Setting Internet gateway

<img width="1917" height="962" alt="Screenshot 2026-10-29 153327" src="https://github.com/user-attachments/assets/03af3e5c-f942-4cd1-af28-ad5eb50ad462" />

 
Snapshot 7: Creating route table

 <img width="1917" height="958" alt="Screenshot 2026-10-29 154055" src="https://github.com/user-attachments/assets/9241d37e-c080-48d8-bc21-c9f1c369844f" />


Snapshot 8: Configuring route table


 <img width="1917" height="957" alt="Screenshot 2026-10-29 162111" src="https://github.com/user-attachments/assets/4b8644ff-6bc5-4443-b5ed-63b3108404d4" />

Snapshot 9: Editing routes
<img width="1917" height="950" alt="Screenshot 2026-10-30 141222" src="https://github.com/user-attachments/assets/1aa705d6-6df6-439f-86ba-8e57acb2dc9c" />

 
Snapshot 10: Creating route table

<img width="1917" height="957" alt="Screenshot 2026-10-30 141329" src="https://github.com/user-attachments/assets/50628f79-07cd-4c9c-a458-d5181b78d29e" />






## Result:
<img width="1917" height="1013" alt="Screenshot 2026-10-30 141659" src="https://github.com/user-attachments/assets/9d79034f-1a9f-46c6-8e90-7a7dbad47466" />



## GRADE:
<img width="606" height="642" alt="image" src="https://github.com/user-attachments/assets/ccc3024d-8a41-4fa2-a5c9-e7c33a3fbba7" />









Result:
Thus, a  private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.
 
