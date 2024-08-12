# Deploy an HeartBeat Application to an EC2 fleet using AWS CodeDeploy.
We are deploying a sample service application to two Amazon EC2 instances. We are using AWS CodeDeploy to push software onto a fleet of Amazon EC2 instances and have the software automatically deployed, registered, and started.

## Objectives:
- Make systematic deployments to a fleet of EC2 servers using CodeDeploy.
- Verify if the CodeDeploy agent is installed and running on a Windows server.
- Create a deployment application and group in CodeDeploy.
- Review and prepare a deployment package to be installed by CodeDeploy.
- Monitor deployment status in CodeDeploy and deployment targets.

![image](https://github.com/user-attachments/assets/0e0a5ed6-9225-4f5a-b4f1-b3a10fb1ac61)
Diagram depicts the architecture components that have been or is deployed in this project including an S3 bucket, AWS CodeDeploy, the HeartBeat Deployment application, a CodeDeploy deployment group named HeartBeat Deployment Group, and two EC2 instances named HeartBeat Application.



