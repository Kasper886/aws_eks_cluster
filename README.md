# AWS EKS cluster creation
---
Usage
---
1. The first of all you need to create VPCs and subnets with VPC_CloudFormation.yaml.
2. Install AWS cli, eksctl, kubectl.
3. Setup credentials for your AWS account.
4. By default the cluster works in us-west2 region.
5. Change subnet IDs to yours in EKS.yaml file, created earlier.
6. Change path to your public key in eks.yaml file.
7. Run the command.
```
eksctl create cluster -f eks.yaml
```
