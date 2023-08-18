# Weekly AWS challenge
1. Amazon EC2
- Resource provision (windows & Linux)
- Deploy simple html page on windows & linux and check it's publicly accessible
- Create custom AMI creation
- Install Apache server via user data in EC2 machines

2. Amazon Virtual Private Cloud
- Create a simple VPC architecture with public and private subnet. Create EC2 machine on both subnets and Try to access private subne from public subnet.
- Check Internet Gateway & Nat Gateway components
- Check VPC peering (Region 1 connects to Region 2)

3. S3
- Host a simple static website in S3
- Versioning
- Access S3 bucket content via private link

4. Load balancer
- Routing based on URL path (ALB)
- Redirect http traffic to https traffic
- Network Load balancer
- Send request from ALB to EC2 machines

5. ECS fargate
- Deploy .Net app in ecs fargate
- Configure load balancer with ECS fargate
- Auto scaling
	
6. Cloudformation
- Create a complete VPC (Private subnet, Public subnet, Internet gateway, Nat gateway, Security groups configuation, Create EC2 machines on both subnets)

7. Terraform
- Create a complete VPC (Private subnet, Public subnet, Internet gateway, Nat gateway, Security groups configuation, Create EC2 machines on both subnets)

8. Secrets Manager
- Add secrets via console and fetch secrets via aws CLI.

9. AWS Certificate Manager
- Create a certificate and configure ALB to use it.
	
10. AWS CLI
- Configure 2 profiles in a machine and switch profiles and access resources.
	- User1 should have access to bucket1
	- User2 should have access to bucket2
	
