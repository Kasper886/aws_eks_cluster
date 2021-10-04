# aws_eks_cluster
---
Usage
---
1. The first of all you need to create VPCs and subnets with VPC_CloudFormation.yaml.
2. Install AWS cli, eksctl, kubectl.
3. Setup credentials for your AWS account.
4. Change path to your public key in eks.yaml file.
5. Run the command eksctl create cluster -f eks.yaml . (without dot)
