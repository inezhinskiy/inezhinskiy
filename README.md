# Hi, I'm Ivan 👋

**DevOps / Infrastructure Engineer** based in Kyiv, Ukraine.

10+ years of running production IT infrastructure — virtualization, networking, security, identity and monitoring — now focused on DevOps: Kubernetes, Terraform, GitOps and CI/CD on Google Cloud.

## 🛠 Tech stack

- **Containers & orchestration:** Kubernetes (GKE, k3d, kind) · Docker · Helm · ArgoCD · Flux
- **Infrastructure as Code:** Terraform (reusable modules, GCS remote state) · Infracost
- **CI/CD:** GitHub Actions · Jenkins · GitHub Container Registry
- **Cloud:** Google Cloud Platform (GKE, GCS, Cloud KMS, IAM, Workload Identity)
- **Security:** SOPS · gitleaks · pfSense · VPN · TLS
- **Infrastructure:** Linux (Debian, Ubuntu) · Windows Server · VMware vSphere / ESXi / vCenter · Zabbix · PRTG · Microsoft 365 / Entra ID
- **Scripting:** Bash · Python · PowerShell · Go (basics)

## 🚀 Featured projects

| Project | What it does | Stack |
| --- | --- | --- |
| [tf-flux](https://github.com/inezhinskiy/tf-flux) | One `terraform apply` provisions a GKE cluster, bootstraps Flux (GitOps) and sets up SOPS secret encryption with Cloud KMS via Workload Identity | Terraform, GKE, Flux, SOPS, Cloud KMS |
| [kbot](https://github.com/inezhinskiy/kbot) | Telegram bot in Go with a full CI/CD pipeline: build → test → image to ghcr.io → Helm values update → ArgoCD auto-sync | Go, Docker, GitHub Actions, Helm, ArgoCD, Jenkins |
| [tf](https://github.com/inezhinskiy/tf) + [tf-google-gke-cluster](https://github.com/inezhinskiy/tf-google-gke-cluster) | GKE cluster from a reusable Terraform module with state in a versioned GCS bucket | Terraform, GCP |
| [pre-commit-gitleaks](https://github.com/inezhinskiy/pre-commit-gitleaks) | Go pre-commit hook that blocks commits containing secrets, installed with one command | Go, gitleaks, Git hooks |
| [kubeplugin](https://github.com/inezhinskiy/kubeplugin) | kubectl plugin that prints CPU/memory usage for resources in a namespace | Bash, kubectl |

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/ivan-nezhinskiy-265388a0) · Open to DevOps / Platform / Infrastructure Engineer roles — remote, hybrid or Kyiv.
