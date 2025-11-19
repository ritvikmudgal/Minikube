# Minikube

Minikube is a lightweight tool that lets you run a single-node Kubernetes cluster locally.  
While AWS provides managed Kubernetes via **EKS**, you can still use Minikube **on an AWS EC2 instance** for testing, learning, or development.

---

##  Requirements

### **On your AWS EC2 instance**
- An EC2 VM (t2.medium or larger recommended)
- Ubuntu 20.04+ or Amazon Linux 2
- At least **2 CPU**, **4GB RAM**, **20GB disk**
- Security group allowing:
  - SSH (22)
  - Optional: Kubernetes Dashboard port (30000–32767)

### **Software dependencies**
- Docker or CRI-O (Docker recommended)
- conntrack
- kubectl
- Minikube binary

---

<img src="Screenshot (43).png" alt="____">
