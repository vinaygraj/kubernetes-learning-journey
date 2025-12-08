# Day 1 — Kubernetes Fundamentals & Local Setup

## 🎯 Goal
Understand what Kubernetes is, why it is used, and create the first local Kubernetes cluster using `kind`.

---

## 🧠 What I Learned Today

### 1️⃣ What Kubernetes Solves
Kubernetes (K8s) is a container orchestration platform that provides:
- **Self-healing** — restarts failed containers automatically  
- **Auto-scaling** — adds/removes replicas based on load  
- **Declarative deployments** — define desired state; K8s maintains it  
- **Service discovery + load balancing**  
- **Zero-downtime rollouts + rollbacks**

### 2️⃣ Kubernetes Architecture (High-Level)
- **Control Plane**: API Server, Scheduler, Controller Manager, etcd  
- **Worker Nodes**: run Pods via Kubelet + container runtime  
- **Pods**: smallest deployable unit, usually 1 container  
- **Deployments**: manage Pods, replicas, rollouts

---

## 🖥️ Local Kubernetes Options
- **kind** → Runs Kubernetes inside Docker containers  
- **minikube** → Runs a single-node VM  
- **colima + k3s** → Another developer-friendly option  

For my setup, I chose **kind**.

---

## 🔧 Commands Used Today

### Install kind (via Homebrew)
```bash
brew install kind
