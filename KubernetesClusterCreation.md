# Kubernetes Cluster Options for Bold BI

Bold BI can be deployed on various Kubernetes cluster configurations, each offering unique advantages and use cases. You can select a cluster based on your specific needs and preferences. Here are several options to consider:

## On-Premises Clusters

- Kind Cluster
Installation: [Kind Cluster Quick Start](https://kind.sigs.k8s.io/docs/user/quick-start/#installation)
- K0s Cluster
Installation: [K0s Cluster Installation](https://docs.k0sproject.io/v1.27.2+k0s.0/install/)
- Rancher Desktop
Installation: [Rancher Desktop Getting Started](https://docs.rancherdesktop.io/getting-started/installation/)
- Kubeadm Cluster
Installation: [Kubeadm Cluster Setup](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/install-kubeadm/)
    
## Cloud Provider Clusters


| Cloud Providers            | Cluster Creation                                                                                   | Cluster Connection                                                                                     |
|----------------------------|----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| Azure Kubernetes Service   | [Azure AKS Walkthrough](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough-portal) | [AKS cluster Connection](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough-portal#connect-to-the-cluster) |
| Google Kubernetes Engine   | [Google GKE Console](https://console.cloud.google.com/kubernetes)                                | [GKE cluster Connection](https://cloud.google.com/kubernetes-engine/docs/quickstart)                                |
| Elastic Kubernetes Service | [AWS EKS Guide](https://docs.aws.amazon.com/eks/latest/userguide/create-cluster.html)             | [EKS cluster Connection](https://aws.amazon.com/premiumsupport/knowledge-center/eks-cluster-connection/)           |
