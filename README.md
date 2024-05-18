# k8s-clusters
Deploying applications in multiple Kubernetes clusters with ArgoCD and Helm.

GitOps is a way of implementing Continuous Deployment for cloud-native applications.
It focuses on a developer-centric experience when operating infrastructure using tools developers are already familiar with, including Git and Continuous Deployment tools.

The core idea of GitOps is to have a Git repository that always contains declarative descriptions of the infrastructure currently desired in the production environment and an automated process to make the production environment match the described state in the repository.
If you want to deploy a new or existing application, you only need to update the repository - the automated process handles everything else. It's like having cruise control for managing your applications in production.