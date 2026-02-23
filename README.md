# Hi there, I'm [TUMHARA NAAM] 👋

## 🚀 DevOps Engineer | Cloud Enthusiast

🔭 **Currently working on:** Kubernetes cluster setup with Kind  
🌱 **Learning:** AWS, Docker, Kubernetes, Terraform  
👯 **Looking to collaborate on:** DevOps open source projects  
💬 **Ask me about:** Kubernetes, Docker, Cloud  
📫 **How to reach me:** [LinkedIn URL]

## 🛠️ Tech Stack

![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazon-aws)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat&logo=terraform)

## 📌 Pinned Projects

### [Kind Multi-Node Kubernetes Cluster](link-to-repo)
4-node Kubernetes cluster (1 control-plane + 3 workers) using Kind on AWS EC2
# Kind Multi-Node Kubernetes Cluster

## 📋 Description
Created a 4-node Kubernetes cluster using Kind on AWS EC2 Ubuntu instance with 1 control-plane and 3 worker nodes.

## 🔧 Tech Used
- Kind (Kubernetes in Docker)
- Kubernetes v1.31.2
- Docker
- AWS EC2
- Ubuntu 24.04
- YAML

## 🐛 Debugging Highlights
- Fixed node role typos (`control-plane` vs `control-plan`)
- Corrected port mapping (`hostPort` vs `hosePort`)
- Resolved GPG key issues for Kubernetes repo

## 🚀 Quick Start
```bash
kind create cluster --name mycluster --config=config.yml
kubectl get nodes
