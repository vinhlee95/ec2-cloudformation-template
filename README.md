# AWS CloudFormation template for EC2 instance

## Update stack
```bash
aws cloudformation update-stack --stack-name ec2 --template-body  file://ec2.yaml --parameters file://parameters.json
```