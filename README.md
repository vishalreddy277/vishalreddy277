# Hey, I'm Vishal 👋

I'm an SRE who came up through the ops side and gradually figured out that writing code to fix infrastructure problems is way more satisfying than clicking through the console. Most of what you'll find here is stuff I actually built or use at work — cleaned up enough to be useful to someone else.

I spend a lot of time thinking about **reliability**, **cost**, and making sure alerts fire when they should (and only when they should). If your on-call rotation is a nightmare, I've probably already written something for that.

---

## What I work with

```
Cloud      →  AWS (primary), Azure
IaC        →  Terraform, Terragrunt
Containers →  EKS, Kubernetes, Helm, ArgoCD
Observability → Datadog, CloudWatch, Prometheus
CI/CD      →  GitHub Actions, ArgoCD
Scripting  →  Python, Bash
```

---

## What's in here

| Repo | What it solves |
|------|---------------|
| [terraform-aws-platform](../terraform-aws-platform) | Modular multi-account AWS setup. VPC, EKS, RDS, ALB. Born out of doing this manually one too many times. |
| [eks-platform-bootstrap](../eks-platform-bootstrap) | Blank AWS account → working EKS cluster with all the add-ons. Karpenter, ExternalDNS, ALB controller. |
| [datadog-monitors-as-code](../datadog-monitors-as-code) | Manages Datadog monitors + dashboards from git. Includes drift detection. |
| [sre-automation-toolkit](../sre-automation-toolkit) | Python scripts for AWS cost reporting, EC2 rightsizing, K8s namespace cleanup. Each one has a README explaining the actual problem. |
| [terraform-azure-landing-zone](../terraform-azure-landing-zone) | Azure hub-spoke, AKS, Key Vault. Useful if you're in a mixed-cloud shop. |
| [github-actions-sre-workflows](../github-actions-sre-workflows) | Reusable CI/CD workflows I keep copying between projects. |

---

## A few things I've learned the hard way

- Remote state locking is not optional
- An alert with no runbook is just noise with extra steps
- The best automation is the kind that makes on-call boring
- If you're SSHing into prod to fix something, you've already lost

---

> Not everything here is polished. Some of it is a work in progress. I'd rather have something real and slightly rough than a perfectly fake portfolio.

📫 Reach me: [LinkedIn](https://linkedin.com/in/vishalreddy277) · vishalreddy277@gmail.com
