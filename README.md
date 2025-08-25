# 🛒 Retail Store Sample App – GitOps on Amazon EKS Auto Mode

A **cloud-native microservices demo application** built to showcase **GitOps, Kubernetes, and AWS EKS Auto Mode**.

## 📌 What it is

This project is a **retail store application** composed of multiple microservices, deployed using **ArgoCD (GitOps)** and managed with **Terraform (IaC)**. It demonstrates how modern teams can build, ship, and operate scalable apps on Kubernetes.

## ⚙️ Microservices

- **UI (Java)** – Customer-facing storefront  
- **Catalog (Go)** – Product listings  
- **Cart (Java)** – Shopping cart management  
- **Orders (Java)** – Order processing  
- **Checkout (Node.js)** – Checkout and payment flow  

## 🏗 Architecture

- **Infrastructure**: Amazon EKS Auto Mode + VPC via Terraform  
- **App Deployment**: Helm charts synced by ArgoCD  
- **CI/CD**: GitHub Actions pipelines  
- **Ingress & Certificates**: NGINX Ingress + Cert-Manager  
- **Images**: Public Docker Hub or Private ECR  


## 🎯 Purpose

This repo is designed for:

- Learning **GitOps workflows with ArgoCD**  
- Exploring **microservices on Kubernetes**  
- Understanding **Terraform-based infra automation**  
- Demonstrating **CI/CD with GitHub Actions**  

## 🌟 Why this project matters

- Shows **real-world cloud-native patterns**  
- End-to-end demo: Infra → GitOps → App lifecycle  
- Can be extended for **training, POCs, or workshops**  

---


