<div align="center">
<h1>🛡️ Cloud Security Engineer Portfolio</h1>

![AWS](https://img.shields.io/badge/AWS-Certified-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Security-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Security](https://img.shields.io/badge/Security-Purple_Team-blue?style=for-the-badge)
![Supply Chain](https://img.shields.io/badge/Security-Supply_Chain-red?style=for-the-badge)

**Cloud Security Engineering | Purple Team Approach | Home Lab Practitioner**

</div>

---

## 👋 About Me

I'm a Data Center Operations Technician transitioning into **Cloud Security Engineering** with a focus on defense-in-depth architectures. I learn by building—deploying vulnerable applications, exploiting them with real attack techniques, then engineering the defensive controls to detect and prevent those same attacks.

My approach combines **offensive security research** with **defensive automation**, treating every vulnerability as an opportunity to build stronger security controls.

**Current Focus:** Kubernetes Hardening (CKS) | Linux OS Hardening (CIS) | Supply Chain Security | Identity & Access Management

---

## 🔬 Featured Projects (The Big 5)

### 1️⃣ 🕵️‍♂️ Purple Team & AppSec Pipeline
![Status](https://img.shields.io/badge/Status-Production-success?style=flat-square)
![Tools](https://img.shields.io/badge/Tools-Wazuh%20%7C%20Burp%20Suite-blue?style=flat-square)

**DVWA & Juice Shop Exploitation vs. Wazuh Detection**

* **Offensive Components:** Simulated **OWASP Top 10** attacks (SQLi, XSS, CSRF) and JWT manipulation on **DVWA** and **Juice Shop** using **Burp Suite Professional**
* **Defensive Components:** Deployed **Wazuh SIEM/EDR** to monitor attack signatures and authored custom detection rules for web-based exploitation attempts
* **Active Response:** Engineered automated scripts to isolate compromised hosts and block malicious IPs at the firewall level upon high-severity triggers
* **Impact:** Reduced detection time from manual analysis (hours) to automated alerts (<60 seconds)

[**📂 View Project**](https://github.com/monachy92/appsec-detection) | [**📊 Detection Dashboard**](link-to-dashboard)

---

### 2️⃣ 🏗️ Secure Supply Chain & Infrastructure Hardening
![Status](https://img.shields.io/badge/Status-Production-success?style=flat-square)
![Security](https://img.shields.io/badge/Scanners-5_Tools-critical?style=flat-square)

**Automating Security-First Infrastructure at Scale**

* **Infrastructure-as-Code Security:** Automated security scanning with Checkov, Kubescape, and ansible-lint across CloudFormation, Terraform, and Ansible playbooks
* **Secret Protection:** Integrated Gitleaks for continuous secret detection with zero-tolerance enforcement across the entire codebase
* **Vulnerability Management:** Trivy scanning for HIGH/CRITICAL CVEs in containers and infrastructure dependencies
* **Multi-Cloud Provisioning:** Production-ready templates for AWS (CloudFormation/Terraform) and Azure (Bicep) with CIS-hardened defaults
* **Configuration Management:** Ansible playbooks with Vault-encrypted secrets for automated system hardening and deployment
* **Policy-as-Code:** OPA/Rego policies enforcing security guardrails across all infrastructure deployments
* **CI/CD Security Pipeline:** GitHub Actions workflow requiring all security checks to pass before merge

**Security Posture:** 5 automated security scanners | Zero secrets exposed | 100% policy compliance

[**📂 View Project**](https://github.com/CloudSec-Jay/IaC) | [**📝 Security Pipeline Docs**](link-to-docs)

---

### 3️⃣ 🔐 Identity & Cloud Security Lab
![Status](https://img.shields.io/badge/Status-Active_Development-yellow?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Hybrid_IAM-blue?style=flat-square)

**Hybrid IAM Automation & Zero Trust Implementation**

* **Identity Lifecycle:** PowerShell automation for AD user provisioning, Entra ID sync monitoring, and enforcing least privilege across hybrid environments
* **Access Governance:** RBAC auditing scripts to detect shadow admins, stale accounts, and privilege creep in Azure/AD
* **Endpoint Hardening:** Automated Windows Server & workstation baselines implementing CIS benchmarks and security policies
* **Hybrid Architecture:** Active Directory to Entra ID integration with Conditional Access policy enforcement and MFA implementation
* **Why This Matters:** Identity is the new perimeter—proper IAM prevents lateral movement and privilege escalation attacks

[**📂 View Project**](https://github.com/CloudSec-Jay/identity-security-lab) | [**📖 Architecture Docs**](link-to-docs)

---

### 4️⃣ ⚓ Kubernetes Security & Hardening
![Status](https://img.shields.io/badge/Status-In_Progress-yellow?style=flat-square)
![Target](https://img.shields.io/badge/Cert-CKS-326CE5?style=flat-square)

**Defense-in-Depth for Cloud-Native Workloads**

* **Cluster Hardening:** Implementing RBAC, Pod Security Standards, and API server hardening to mitigate container escape risks
* **Network Security:** Utilizing Network Policies and CNI configurations to enforce micro-segmentation within the cluster
* **Runtime Monitoring:** Researching **Falco** and eBPF-based tools to detect and alert on anomalous behavior in real-time
* **Compliance:** Working toward CIS Kubernetes Benchmark compliance for production-grade cluster security

[**📂 View Project**](https://github.com/yourusername/k8s-security-lab) | [**🎯 Learning Roadmap**](link-to-roadmap)

---

### 5️⃣ 🤖 AI Safety & LLM Security Research
![Status](https://img.shields.io/badge/Status-Active_Research-blue?style=flat-square)
![Framework](https://img.shields.io/badge/Framework-OWASP_LLM_Top_10-red?style=flat-square)

**Hardening Generative AI Implementations**

* **Input Sanitization:** Developed a Python-based security gateway to intercept and mitigate **Prompt Injection** attempts before they reach the LLM
* **Threat Modeling:** Researching architectural weaknesses in private LLM deployments based on the **OWASP Top 10 for LLMs**
* **Testing Framework:** Building proof-of-concept exploits for prompt injection, data poisoning, and model theft scenarios
* **Goal:** Create reusable security patterns for organizations deploying internal AI systems

[**📂 View Project**](https://github.com/yourusername/llm-security-research) | [**📝 Research Notes**](link-to-notes)

---

## 🛠️ Technical Skills

### Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white) 
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) 
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) 
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

### Security & Monitoring
![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=flat-square&logo=wazuh&logoColor=white) 
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burp-suite&logoColor=white) 
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white)
![Checkov](https://img.shields.io/badge/Checkov-6B4FBB?style=flat-square)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Falco](https://img.shields.io/badge/Falco-00B4C5?style=flat-square)

### Languages & Scripting
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat-square)
![Rego](https://img.shields.io/badge/Rego-7B42BC?style=flat-square)

---

## 🎓 Education & Certifications

### Education
* 🎓 **B.S. Cloud Computing** - Western Governors University (Expected May 2026)
* 🎓 **M.S. Cybersecurity & Information Assurance** - WGU (Starting Nov 2026)

### Certifications Earned
**CompTIA Stack:**
* ✅ Security+ (Sec+) 
* ✅ Network+ (Net+)
* ✅ Linux+ 
* ✅ A+

**Cloud Foundations:**
* ✅ AWS Certified Cloud Practitioner (CCP)
* ✅ Microsoft Azure Fundamentals (AZ-900)

### Active Certification Roadmap
```
Q1 2025  → 🎯 AWS Certified Solutions Architect Associate (SAA-C03)
Q2 2025  → 🎯 Cisco CCNA (200-301)
Q3 2025  → 🎯 Certified Kubernetes Administrator (CKA)
Q4 2025  → 🎯 AWS Security Specialty (SCS-C02)
2026     → 🎯 Certified Kubernetes Security Specialist (CKS)
```

---

## 📫 Let's Connect

I'm always interested in discussing cloud security architecture, purple team methodologies, or interesting detection engineering problems. 

**Best ways to reach me:**
* 💼 [LinkedIn](your-linkedin-url) - Professional updates and articles
* 📧 [Email](mailto:your-email) - Direct contact for opportunities
* 🐙 [GitHub](your-github-url) - All my public security research

**What I'm looking for:**
* Cloud Security Engineer roles (entry to mid-level)
* Purple Team / Detection Engineering positions  
* Organizations that value hands-on lab work and continuous learning

---

<div align="center">

### **"To build the shield, you must first master the sword."**

*Security through understanding—I break systems to learn how to defend them.*

---

![Profile Views](https://komarev.com/ghpvc/?username=yourusername&color=blue&style=flat-square)
![Last Updated](https://img.shields.io/badge/Last_Updated-February_2025-success?style=flat-square)

</div>
