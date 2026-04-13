🔹 General

1. Kubernetes?
Container orchestration tool.

2. Pod?
Smallest unit (container group).

3. Deployment?
Manages pods.

4. Service?
Exposes application.

5. Types of service?

ClusterIP
NodePort
LoadBalancer

6. ConfigMap?
Stores config data.

7. Secret?
Stores sensitive data.

8. Ingress?
HTTP routing.

9. Helm?
Package manager.

10. Autoscaling?
HPA scales pods.

🔹 Scenario

1. Pod not starting?

kubectl describe
Check logs

2. App down?

Check pods/services

3. Rolling update?

kubectl apply

4. Rollback?

kubectl rollout undo

5. Scale app?

kubectl scale

6. Pod not accessible?

Check service

7. Secure secrets?

Use Kubernetes secrets

8. Monitor cluster?

Prometheus + Grafana

9. Node down?

Pods rescheduled

10. HA cluster?

Multiple master nodes