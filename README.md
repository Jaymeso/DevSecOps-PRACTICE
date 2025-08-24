# DevSecOps-PRACTICE
A DevSecOps practice - embedding security within DevOps and automation processes.

DevSecOps-Practice/
│
├── README.md               # Documentation (see template below)
├── pipeline-examples/
│   ├── github-actions.yml  # Example pipeline with security scans
│   ├── gitlab-ci.yml       # Example GitLab CI/CD with SAST/DAST
│
├── IaC-security/
│   ├── terraform-aws-iam.tf    # Secure IAM Terraform example
│   ├── checkov-scan-results.md # Example scan report
│
├── container-security/
│   ├── dockerfile             # Example hardened Dockerfile
│   ├── trivy-report.md        # Container vulnerability scan example
│
├── docs/
│   ├── devsecops-overview.md  # Why DevSecOps matters
│   ├── tool-comparison.md     # Snyk vs Trivy vs Anchore
│   └── governance-mapping.md  # Linking DevSecOps to NIST CSF, DORA
