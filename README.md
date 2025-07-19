# 🌐 Hybrid DevOps Lab – GitHub Pages Site

This GitHub Pages site documents the **Hybrid DevOps Lab**, a multi-phase, enterprise-grade DevSecOps project designed and built by **Temitayo Charles Akinniranye**. The site serves as a live portfolio, case study, and educational resource showcasing how to simulate real-world CI/CD, Kubernetes, and GitOps workflows using modern tools.
## 🔥 Live Site

> **[View the Project Website](https://temitayocharles.github.io/hybrid-devops-lab-site/)**  
> (Enable GitHub Pages in repo settings to activate)

## 📚 What's Inside?

The site includes a fully styled, dark-theme multi-page layout with glowing effects and navigational links:

| Page            | Description                                                |
|-----------------|------------------------------------------------------------|
| `index.html`    | Landing page and lab overview                              |
| `architecture.html` | System architecture, diagrams, and tool integration flow |
| `ci.html`       | CI/CD pipeline with GitHub Actions + Jenkins + SonarQube   |
| `security.html` | Vault + OIDC, container security, and secrets injection    |
| `monitoring.html` | Prometheus, Grafana, and Alertmanager setup              |
| `gitops.html`   | GitOps pipeline using ArgoCD with Helm & Rollouts          |
| `docs.html`     | Full documentation, folder structure, setup instructions   |
| `contact.html`  | Links to GitHub, LinkedIn, Docker Hub, and email           |

## 🛠 Technologies Used

- **CI/CD**: GitHub Actions, Jenkins, SonarQube, Maven
- **Kubernetes**: KIND, Helm, ArgoCD, Argo Rollouts
- **Security**: Vault, OIDC, Trivy, SOPS, KMS
- **Monitoring**: Prometheus, Grafana, Alertmanager
- **Storage & Registry**: MinIO (S3-compatible)
- **Deployment Strategy**: ClusterIP + NGINX Ingress (no LoadBalancer/NodePort)

## 💡 Purpose

This lab demonstrates:
- Simulating full-stack DevOps workflows on local/dev environments
- Secure, cost-effective CI/CD pipelines
- GitOps-based progressive delivery with audit, rollback, and sync
- Monitoring, drift detection, and alert routing


## 📦 How to Use

1. **Clone This Repo**  
   ```bash
   git clone https://github.com/temitayocharles/hybrid-devops-lab-site.git
   cd hybrid-devops-lab-site

   2.	Enable GitHub Pages
Go to Settings > Pages and choose:
	•	Source: main
	•	Folder: / (root) or /docs
	3.	Publish & Share
Your portfolio will be live at:
https://<your-username>.github.io/hybrid-devops-lab-site/

🤝 Contributing

This project is a solo-authored lab used for education, demonstration, and job interviews.
If you’re interested in collaborating on open-source DevOps tooling or content—reach out via LinkedIn.

🧑‍💻 Author

Temitayo Charles Akinniranye
DevOps | CI/CD | Kubernetes | AWS | Security-First Infrastructure
📫 Email • GitHub • Docker Hub
