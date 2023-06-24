# CloudFormation_EXAMPLE
CloudFormation exercise: infrastructure as code.

With this template I'm trying to create a whole infrastructure compose by:

*VPC
*Public and private subnets
*Route tables for public and private subnets above
*Routes
*Internet Gateway to allow any IPv4 traffic
*Security groups to limit access to SSH (:22) and HTTP (:80)
*Amazon Linux EC2 instance to simulate an app server instance.

To run the attached template please go to the CloudFormation Designer:

https://us-east-1.console.aws.amazon.com/cloudformation/designer/home?region=us-east-1

Enjoy it!
