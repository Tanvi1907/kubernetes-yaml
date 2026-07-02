# 🚀 Kubernetes YAML Practice

A hands-on Kubernetes practice repository covering concepts from beginner to production level using **Kubernetes**, **Minikube**, **Docker**, and **kubectl**.

This repository contains Kubernetes YAML manifests that I created while learning Kubernetes through practical implementation. Every concept has been tested in a local Kubernetes cluster using Minikube.

---

# 📚 Topics Covered

## 🔹 Kubernetes Basics

* Pod
* Namespace
* Labels & Selectors
* Deployment
* Rolling Updates
* Rollback
* Advanced Deployment

## 🔹 Services

* ClusterIP Service
* NodePort Service
* Application Service

## 🔹 Configuration Management

* ConfigMap
* ConfigMap as Environment Variables
* ConfigMap as Volume
* Secret
* Secret as Environment Variables

## 🔹 Storage

* Volumes
* hostPath Volume
* Persistent Volume (PV)
* Persistent Volume Claim (PVC)
* Dynamic PVC

## 🔹 Health Checks

* Liveness Probe
* Readiness Probe
* Health Check Deployment

## 🔹 Resource Management

* Resource Requests
* Resource Limits

## 🔹 Stateful Workloads

* Headless Service
* StatefulSet
* Persistent Storage with StatefulSet

## 🔹 Cluster Workloads

* DaemonSet
* Job
* CronJob

## 🔹 Networking

* Namespace
* Ingress

---

# 📁 Repository Structure

```text
kubernetes-yaml/
│
├── pod.yaml
├── deployment.yaml
├── deployment-v1.yaml
├── advanced-deployment.yaml
│
├── service.yaml
├── app-service.yaml
│
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
│
├── daemonset.yaml
├── job.yaml
├── cronjob.yaml
│
└── README.md
```

---

# 🛠️ Tools & Technologies

* Kubernetes
* Minikube
* Docker
* kubectl
* YAML
* Visual Studio Code
* Git
* GitHub

---

# 🎯 Learning Outcomes

Through this repository, I gained hands-on experience with:

* Creating and managing Pods
* Deployments and rolling updates
* Kubernetes Services
* ConfigMaps and Secrets
* Persistent Storage (PV & PVC)
* Health Checks
* Resource Management
* Stateful Applications
* DaemonSet
* Job & CronJob
* Namespaces
* Ingress
* Production-oriented Kubernetes YAML manifests

---

# ▶️ Prerequisites

Before using these YAML files, make sure you have:

* Docker installed
* Minikube installed
* kubectl configured
* A running Kubernetes cluster

Start Minikube:

```bash
minikube start
```

Apply any manifest:

```bash
kubectl apply -f <filename>.yaml
```

Example:

```bash
kubectl apply -f deployment.yaml
```

---

# 📈 Repository Status

* ✅ Kubernetes Basics
* ✅ Deployments
* ✅ Services
* ✅ ConfigMaps
* ✅ Secrets
* ✅ Volumes
* ✅ PV & PVC
* ✅ Health Checks
* ✅ Resource Management
* ✅ StatefulSet
* ✅ DaemonSet
* ✅ Job
* ✅ CronJob
* ✅ Namespace
* ✅ Ingress

---

## ⭐ About

This repository is part of my DevOps learning journey and focuses on mastering Kubernetes through hands-on practice and production-oriented examples.

If you find this repository useful, feel free to explore the YAML manifests and follow along.
