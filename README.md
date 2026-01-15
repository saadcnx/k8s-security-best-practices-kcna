# Kubernetes Security Best Practices

![Kubernetes Security Flow](./security-flow.png)

This repository demonstrates practical Kubernetes security implementations aligned with cloud-native and production-grade environments.

The focus is on **securing workloads, controlling network access, hardening containers, and enforcing least-privilege principles**.

---

## 🔐 Security Areas Covered

### Pod Security
- Enforced **Pod Security Standards (Restricted profile)**
- Prevented privilege escalation
- Enforced non-root containers
- Applied seccomp and capability drops

### Network Security
- Implemented **Network Policies**
- Enforced namespace-level isolation
- Allowed only required Pod-to-Pod communication
- Followed zero-trust networking principles

### Container Image Security
- Vulnerability scanning using **Trivy**
- Identified HIGH and CRITICAL vulnerabilities
- Discouraged use of `latest` image tags
- Demonstrated secure Dockerfile practices

### Access Control (RBAC)
- Created service accounts with limited permissions
- Applied role-based access using Roles and RoleBindings
- Verified access using Kubernetes authorization checks

### Resource Protection
- Applied **ResourceQuotas** and **LimitRanges**
- Prevented resource exhaustion
- Enforced CPU and memory boundaries

---

## 🛠 Tools & Technologies
- Kubernetes
- Docker
- Trivy
- Linux
- YAML
- RBAC
- Network Policies

---

## 🎯 Key Outcomes
- Improved Kubernetes workload security
- Reduced attack surface inside the cluster
- Enforced least privilege and zero-trust networking
- Established security foundations for production clusters

---

## 📌 Use Case
This project is suitable for:
- Kubernetes security hardening
- Cloud-native security learning
- KCNA / Kubernetes security preparation
- DevSecOps practice environments
