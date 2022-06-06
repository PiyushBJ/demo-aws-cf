# demo-aws-cf

1. Create VPC With pvt and public subnet with igw and nat in aws
2. Create two vm one for jenkins and app server
3. Jenkins Pipeline to build and save
4. Deploy the artifact to app server

# aws cloudformation create-stack --stack-name ee-demo-aws --region eu-west-1 --template-body file://network.yaml --parameters file://network-param.json
# aws cloudformation create-stack --stack-name e2-demo-aws --region eu-west-1 --template-body file://ec2.yaml --parameters file://ec2-param.json

