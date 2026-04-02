# ☸️ Kubernetes Certification Prep (CKAD & CKA)

This repository tracks my journey and study notes for the Certified Kubernetes Application Developer (CKAD) and Certified Kubernetes Administrator (CKA) exams.

## 📊 Exam Progress Dashboard
- [ ] **CKAD** (Target Date: MM/YYYY) - ⏳ In Progress
- [ ] **CKA** (Target Date: MM/YYYY) - 📅 Planned

---

## 📚 Study Modules

### 🚀 CKAD (Application Developer)
1. **Core Concepts** - [Notes](./ckad/01-core-concepts/README.md)
2. **Configuration** - [Notes](./ckad/02-configuration/README.md)
3. **Multi-Container Pods** - [Notes](./ckad/03-multi-container/README.md)

### 🛠️ CKA (Administrator)
1. **Cluster Architecture** - [Notes](./cka/01-cluster-architecture/README.md)
2. **Troubleshooting** - [Notes](./cka/02-troubleshooting/README.md)

---
## 💡 Essential Aliases (Exam Time Savers)
Add these to your `~/.bashrc` or run them at the start of the exam:
```bash
alias k=kubectl
alias kgp="kubectl get pods"
export do="--dry-run=client -o yaml" # Example: k run nginx --image=nginx $do
