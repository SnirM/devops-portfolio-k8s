# devops-portfolio-k8s

Kubernetes manifests for the DevOps portfolio project.

## Apply order
```bash
kubectl apply -f namespaces/app-namespace.yaml
kubectl apply -f database/
kubectl apply -f app/
