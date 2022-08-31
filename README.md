# tf-eks

# Learn Terraform - Provision an EKS Cluster

This repo is a companion repo to the [Provision an EKS Cluster learn guide](https://learn.hashicorp.com/terraform/kubernetes/provision-eks-cluster), containing
Terraform configuration files to provision an EKS cluster on AWS.


# terraform init     # on you own machine
# terraform apply    # on you own machine
# Now that you've provisioned your EKS cluster, you need to configure kubectl
# aws eks --region $(terraform output -raw region) update-kubeconfig --name $(terraform output -raw cluster_name)
                                         # Run the following command to retrieve the access credentials for your cluster and configure kubectl
                                         # You can now use kubectl to manage your cluster and deploy Kubernetes configurations to it.
# kubectl cluster-info
# kubectl get nodes
# terraform destroy     # on you own machine



