# Repo-PetClinic-Automation

# 🐾 PetClinic Cloud-Native GitOps Ecosystem (Final Project)

This repository contains the full CI/CD automation for the Spring PetClinic Microservices, following **GitOps** principles and using **Jenkins Shared Libraries**.

## 🚀 Project Overview
An automated pipeline that builds, tests, and deploys 3 Microservices to a Kubernetes cluster using Jenkins, Docker Hub, and ArgoCD.

---

## 🏗️ Architecture & Components

### 1. Source Code (Monorepo)
*   **Service A (Visits):** https://github.com/nadaessam99e-design/-petclinic-service-a.git
*   **Service B (Vets):** https://github.com/nadaessam99e-design/-petclinic-service-b.git
*   **Service C (Customers):** https://github.com/nadaessam99e-design/-petclinic-service-c.git

### 2. Automation Core (Jenkins Shared Library)
*   **Shared Library Repository:** https://github.com/nadaessam99e-design/jenkins-shared-library.git
*   **Functionality:** Centralized logic for Building, Scanning (SonarQube), and Updating GitOps Manifests.

### 3. Continuous Delivery (ArgoCD & GitOps)
*   **GitOps Repository:** https://github.com/nadaessam99e-design/GitOps-Repository.git
*   **ArgoCD Status:** Automated sync is enabled for seamless deployments.

---

## 🛠️ Tech Stack
*   **CI Tool:** Jenkins (Multibranch Pipeline + Shared Library)
*   **CD Tool:** ArgoCD
*   **Containerization:** Docker
*   **Orchestration:** Kubernetes (K8s)
*   **Registry:** Docker Hub
