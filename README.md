# 💫 About Me
👋 Hi, I'm **Umar Shaikh** – a DevOps & Cloud Engineer passionate about building scalable, secure, and automated cloud infrastructure.

☁️ **Cloud Infrastructure** – Hands-on experience designing and deploying production-grade architectures on AWS using VPC, EKS, ALB, Auto Scaling, EFS, Aurora, and managed databases.

🐳 **Containers & Orchestration** – Experienced with Docker and Kubernetes for containerizing applications, managing distributed microservices, and GitOps-based deployments via ArgoCD.

⚙️ **DevSecOps & CI/CD** – Building multi-stage Jenkins pipelines with integrated security scanning (Trivy, SonarQube, OWASP), infrastructure-as-code with Terraform, and GitOps delivery workflows.

🤖 **AIOps & Agentic AI** – Architecting AIOps platforms using Amazon Q CLI and MCP servers for autonomous incident investigation and human-in-the-loop cluster remediation on EKS.

🔐 **Systems & Security** – Practical experience in Linux administration, networking, Active Directory, and enterprise IT infrastructure with a focus on security and compliance.

🚀 **Current Focus**
- AWS EKS & Cloud-Native Infrastructure
- DevSecOps Pipelines & GitOps
- AIOps & Agentic AI on Kubernetes
- Observability: Prometheus, Grafana, Loki, AlertManager

📫 **Let's Connect** – Feel free to explore my repositories or reach out for collaboration.

---

# 🚀 Featured Projects

### 🤖 AIOps Platform using Agentic AI for Incident Response on AWS EKS
- Architected an AIOps observability platform leveraging **Amazon Q CLI** as an Agentic AI reasoning layer that autonomously investigates pod logs, events, and metrics via **EKS MCP server**
- Implemented a **human-in-the-loop approval gate** – Agentic AI executes cluster remediations (scale, rollout restart, rollout undo) only after human approves via Discord reply; no automated writes without approval
- Provisioned AWS infrastructure (**VPC, EKS Auto Mode, NLB**) with Terraform and deployed 5 microservices via GitOps with ArgoCD
- Configured full observability stack: **Prometheus, Grafana, Loki, AlertManager** with custom alert rules routing to the AIOps webhook

---

### 🔐 DevSecOps & GitOps Pipeline for a 3-Tier Trip Planner App
- Built a **10-stage Jenkins CI pipeline** with Shared Library – Trivy filesystem scan, OWASP Dependency Check, SonarQube Quality Gate run before every Docker build, blocking vulnerable code from reaching registry
- Implemented **GitOps delivery via ArgoCD** with auto-sync and self-heal – CD pipeline commits updated image tags to GitHub, ArgoCD detects the diff and rolls out to EKS automatically with zero manual kubectl commands
- Provisioned entire AWS infrastructure (**EKS, VPC, EC2, NLB, Prometheus/Grafana** monitoring stack) using modular Terraform – deployed 5-service microservice app with PostgreSQL StatefulSet, Redis, and EBS persistent storage

---

### ☁️ Scalable Moodle Deployment on AWS
- Architected a fault-tolerant, production-grade Moodle environment on AWS using **Terraform** – VPC, multi-AZ architecture, ALB, Auto Scaling, EFS, and Aurora RDS
- Implemented enterprise-grade security with **IAM roles, private subnets, and NAT Gateways**, ensuring compliance and resilience
- Delivered a cloud-native solution with **multi-AZ failover, EFS shared storage, and Auto Scaling** to ensure high availability and fault tolerance

---

# 🌐 Socials
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/umar-shaikh-723765191/)
[![GitHub](https://img.shields.io/badge/GitHub-181717.svg?logo=github&logoColor=white)](https://github.com/umar-sk-07)

---

# 💻 Tech Stack

### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)

### 🐳 Containers & Orchestration
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326CE5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/helm-%230F1689.svg?style=for-the-badge&logo=helm&logoColor=white)

### ⚙️ CI/CD & GitOps
![Jenkins](https://img.shields.io/badge/jenkins-%23D24939.svg?style=for-the-badge&logo=jenkins&logoColor=white)
![ArgoCD](https://img.shields.io/badge/argo-%23EF7B4D.svg?style=for-the-badge&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

### 🔐 Security & Monitoring
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![SonarQube](https://img.shields.io/badge/sonarqube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)

### 🖥️ Systems & Scripting
![Linux](https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Shell Script](https://img.shields.io/badge/shell_script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

### 💾 Databases
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)

---

# 📊 GitHub Stats
![](https://github-readme-stats.vercel.app/api?username=umar-sk-07&theme=dark&hide_border=false&include_all_commits=true&count_private=true)
![](https://github-readme-streak-stats.herokuapp.com/?user=umar-sk-07&theme=dark&hide_border=false)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=umar-sk-07&theme=dark&layout=compact)

---

# 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=umar-sk-07&theme=radical&no-frame=false&no-bg=true&margin-w=4)

---

![Visitor Count](https://visitcount.itsvg.in/api?id=umar-sk-07&icon=0&color=0)
