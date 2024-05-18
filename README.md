# k8s-clusters
Deploying applications to a Kubernetes clusters with Helm and ArgoCD.

GitOps is a way of implementing Continuous Deployment for cloud-native applications.
It focuses on a developer-centric experience when operating infrastructure using tools developers are already familiar with, including Git and Continuous Deployment tools.

The core idea of GitOps is to have a Git repository that always contain declarative descriptions of the infrastructure currently required in the production environment and
an automated process to make the production environment match the described state of changes to the repository.
If you want to deploy a new or existing application, you only need to update the repository - the automated process handles everything else.
