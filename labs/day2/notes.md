# Day 2 — Pods, Deployments, and Services

## Key Concepts
- Pod = basic unit that runs containers
- Deployment = manages Pods, replicas, updates
- Service = stable networking endpoint for Pods

## Commands Used
kubectl apply -f pod.yaml
kubectl delete pod hello-pod
kubectl apply -f deployment.yaml
kubectl get deployments
kubectl get pods
kubectl apply -f service.yaml
kubectl port-forward svc/hello-service 8080:80
