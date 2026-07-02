# Kubernetes YAML Practice

This repository contains my hands-on Kubernetes practice files, covering concepts from beginner to production-level. All examples are tested using Minikube and kubectl.

---

## Topics Covered

### Kubernetes Basics
- Pod
- Namespace
- Labels & Selectors
- Deployment
- Rolling Updates
- Rollback
- Advanced Deployment Strategies

### Services
- ClusterIP Service
- NodePort Service
- Application Service

### Configuration Management
- ConfigMap
- ConfigMap as Environment Variables
- ConfigMap as Volume
- Secret
- Secret as Environment Variables

### Storage
- Volumes
- hostPath Volume
- Persistent Volume (PV)
- Persistent Volume Claim (PVC)
- Dynamic Persistent Volume Claim (Dynamic PVC)

### Health Checks
- Liveness Probe
- Readiness Probe
- Startup & Health Check Deployment

### Resource Management
- Resource Requests
- Resource Limits

### Stateful Applications
- Headless Service
- StatefulSet
- Persistent Storage with StatefulSet

### Cluster Workloads
- DaemonSet
- Job
- CronJob

### Networking
- Namespace
- Ingress

---

## Repository Structure

```text
kubernetes-yaml/
│
├── pod.yaml
├── deployment.yaml
├── deployment-v1.yaml
├── advanced-deployment.yaml
├── service.yaml
├── app-service.yaml
├── namespace.yaml
├── ingress.yaml
│
├── configmap.yaml
├── app-config.yaml
├── pod-configmap.yaml
├── pod-configmap-volume.yaml
│
├── secret.yaml
├── app-secret.yaml
├── pod-secret.yaml
│
├── volume-pod.yaml
├── hostpath-pod.yaml
├── pv.yaml
├── pvc.yaml
├── dynamic-pvc.yaml
├── pod-pvc.yaml
│
├── liveness-pod.yaml
├── readiness-pod.yaml
├── healthcheck-deployment.yaml
├── resource-deployment.yaml
│
├── mysql-headless-service.yaml
├── mysql-statefulset.yaml
├── daemonset.yaml
├── job.yaml
├── cronjob.yaml
│
└── README.md
```

---

## Tools Used

- Kubernetes
- Minikube
- Docker
- kubectl
- Visual Studio Code

---

## Learning Outcome

Through this repository, I practiced:

- Kubernetes core concepts
- Application deployment
- Networking
- Configuration management
- Storage management
- Health checks
- Stateful workloads
- Batch workloads
- Production-oriented Kubernetes YAML manifests

---

⭐ This repository is part of my DevOps learning journey and is continuously updated with new Kubernetes concepts.