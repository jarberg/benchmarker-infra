# benchmarker-infra

Infrastructure and deployment configuration for Benchmarker.

## Structure

```
.github/workflows/   # CI/CD pipelines (future Terraform/ArgoCD automation)
argocd/              # ArgoCD app-of-apps and application definitions
k8s/                 # Kubernetes manifests (Kustomize base + overlays)
scripts/             # Cluster management scripts
terraform/           # Infrastructure as code (VPC, EKS, RDS, ECR)
tools/               # Dockerfile for ops tooling
docker-compose.yml   # Local infrastructure stack
```

## Related

App source lives in [benchmarker-app](../benchmarker-app).
