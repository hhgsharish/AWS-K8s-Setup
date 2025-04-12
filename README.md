# AWS-K8s-Setup

This creates AWS Kubernetes setup with 1 Master and 2 Worker nodes.

**Steps**
import this to terraform and run 

    terraform init

    terraform plan

    terraform apply -auto-approve

Once completed, run this command in Master node

    kubectl get nodes 
    
**To Destroy**
    terraform destroy 
