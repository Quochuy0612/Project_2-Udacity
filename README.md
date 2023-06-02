# Udacity Project 2 || Cloud DevOps Engineer

## Deploy a High-Availability Web App using CloudFormation

## Website Link : http://udagramloadbalancer-1796769441.us-east-1.elb.amazonaws.com/

## Script Create CloudFormation:

### VPC
	./create.sh UdagramVPC Infrastructure/udagramVPC.yaml Infrastructure/Parameters/udagramVPC.json

### SecurityGroup
	./create.sh UdagramSecurityGroup Infrastructure/udagramSecurityGroup.yaml Infrastructure/Parameters/udagramSecurityGroup.json

### IAMRole
	./create.sh UdagramIAMRole Infrastructure/udagramIAMRole.yaml Infrastructure/Parameters/udagramIAMRole.json

### S3
	./create.sh UdagramS3 Infrastructure/udagramS3.yaml Infrastructure/Parameters/udagramS3.json

### Bastion
	./create.sh UdagramBastion Infrastructure/udagramBastion.yaml Infrastructure/Parameters/udagramBastion.json

### AutoScalingGroup
	./create.sh UdagramAutoScalingGroup Infrastructure/udagramAutoScalingGroup.yaml Infrastructure/Parameters/udagramAutoScalingGroup.json

### LoadBalancer
	./create.sh UdagramLoadBalancer Infrastructure/udagramLoadBalancer.yaml Infrastructure/Parameters/udagramLoadBalancer.json
	
## Script Update CloudFormation:

### VPC
	./update.sh UdagramVPC Infrastructure/udagramVPC.yaml Infrastructure/Parameters/udagramVPC.json

### SecurityGroup
	./update.sh UdagramSecurityGroup Infrastructure/udagramSecurityGroup.yaml Infrastructure/Parameters/udagramSecurityGroup.json

### IAMRole
	./update.sh UdagramIAMRole Infrastructure/udagramIAMRole.yaml Infrastructure/Parameters/udagramIAMRole.json

### S3
	./update.sh UdagramS3 Infrastructure/udagramS3.yaml Infrastructure/Parameters/udagramS3.json

### Bastion
	./update.sh UdagramBastion Infrastructure/udagramBastion.yaml Infrastructure/Parameters/udagramBastion.json

### AutoScalingGroup
	./update.sh UdagramAutoScalingGroup Infrastructure/udagramAutoScalingGroup.yaml Infrastructure/Parameters/udagramAutoScalingGroup.json

### LoadBalancer
	./update.sh UdagramLoadBalancer Infrastructure/udagramLoadBalancer.yaml Infrastructure/Parameters/udagramLoadBalancer.json

## Script Delete CloudFormation:

### VPC
	./delete.sh UdagramVPC Infrastructure/udagramVPC.yaml Infrastructure/Parameters/udagramVPC.json

### SecurityGroup
	./delete.sh UdagramSecurityGroup Infrastructure/udagramSecurityGroup.yaml Infrastructure/Parameters/udagramSecurityGroup.json

### IAMRole
	./delete.sh UdagramIAMRole Infrastructure/udagramIAMRole.yaml Infrastructure/Parameters/udagramIAMRole.json

### S3
	./delete.sh UdagramS3 Infrastructure/udagramS3.yaml Infrastructure/Parameters/udagramS3.json

### Bastion
	./delete.sh UdagramBastion Infrastructure/udagramBastion.yaml Infrastructure/Parameters/udagramBastion.json

### AutoScalingGroup
	./delete.sh UdagramAutoScalingGroup Infrastructure/udagramAutoScalingGroup.yaml Infrastructure/Parameters/udagramAutoScalingGroup.json

### LoadBalancer
	./delete.sh UdagramLoadBalancer Infrastructure/udagramLoadBalancer.yaml Infrastructure/Parameters/udagramLoadBalancer.json
