## k8s-nginx-minikube

This project demonstrates deploying an NGINX application on a local Kubernetes cluster using **Minikube and Terraform**.

### Tech Stack
- Terraform
- Kubernetes
- Minikube
- Docker
- NGINX
- Linux

### What this project does
- Uses Terraform to manage Kubernetes resources
- Configures Kubernetes provider using local kubeconfig
- Creates Kubernetes namespace via Terraform
- Deploys NGINX application
- Exposes the app using NodePort service
- Simulates cloud-native deployment locally without AWS/GCP

### Why this project?
This project focuses on **Infrastructure as Code (IaC)** practices and Kubernetes fundamentals without relying on cloud platforms, making it ideal for understanding real-world DevOps workflows.

### Status
🚧 Project is actively being improved
