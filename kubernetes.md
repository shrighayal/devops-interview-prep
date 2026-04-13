# Kubernetes Interview Questions & Answers

## 🔹 General Questions

### 1. What is Kubernetes?
Kubernetes is a container orchestration tool.

### 2. What is Pod?
Smallest deployable unit.

---

## 🔹 Scenario-Based Questions

### 1. Pod not starting?
- kubectl describe pod
- kubectl logs
- Check YAML

### 2. App not accessible?
- Check service type
- Verify ports
- Check ingress

### 3. Rollback deployment?
kubectl rollout undo deployment <name>