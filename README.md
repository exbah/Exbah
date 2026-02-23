# Hi there, I'm [Isbah Amin] 👋

## 🚀 DevOps Engineer | Aws Certified DevOps Eng

🔭 **Pro on:** Kubernetes
🌱 **AWS, Docker, Kubernetes, Terraform  
👯 **Looking to collaborate on:** DevOps open source projects  
💬 **Ask me about:** Kubernetes, Docker, Cloud  
📫 **How to reach me:** [https://www.linkedin.com/in/isbah-amin-662401248/]

## 🛠️ Tech Stack



<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=2C93F7&center=true&vCenter=true&width=435&lines=Kubernetes+Enthusiast;Docker+Expert;AWS+Cloud+Practitioner" alt="Typing SVG" />
</p>

---

## 🛠️ **Tech Stack**

<p align="center">
  <!-- Cloud & Infrastructure -->
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/bash.png" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" />
  <br>
  
  <!-- Container & Orchestration -->
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" />
  <br>
  
  <!-- IaC & Config -->
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" />
  <br>
  
  <!-- CI/CD -->
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />
  <br>
  
  <!-- Monitoring -->
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
</p>

---

## 📌 **Featured Projects**

### 🚢 **Kind Multi-Node Kubernetes Cluster**

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
