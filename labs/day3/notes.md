# Day 3 — ConfigMaps, Secrets, and Environment Variables

## Key Concepts
- ConfigMaps store non-sensitive configuration
- Secrets store sensitive values (base64 encoded)
- Deployments can load values using `env.valueFrom`
- Configuration is decoupled from container images

## Commands Used
kubectl apply -f configmap.yaml
kubectl apply -f secret.yaml
kubectl apply -f deployment.yaml
kubectl get configmaps
kubectl get secrets
kubectl logs <pod>
