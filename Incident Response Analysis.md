
# 🛡️ Incident Response Analysis – DDoS Attack

This project is a structured **incident response case study** analyzing a DDoS attack on a fictional multimedia company. It follows the **NIST Cybersecurity Framework (CSF)** and demonstrates how to apply professional cybersecurity analysis and response planning without coding.

---

## 📘 Project Summary

* **Type:** Non-technical simulation (no coding involved)
* **Scenario:** DDoS attack using ICMP flood through an unconfigured firewall
* **Objective:** Analyze the incident and develop a security improvement plan
* **Framework Used:** [NIST Cybersecurity Framework (CSF)](https://www.nist.gov/cyberframework)

---

## 🧩 Scenario Overview

A **multimedia company** offering web and social media services experienced a **two-hour DDoS attack** due to a flood of ICMP packets exploiting a misconfigured firewall. Internal network traffic was completely disrupted during the incident. The organization responded quickly to contain the threat and later conducted a structured investigation.

---

## 🔍 Key Takeaways from the Incident

### ✅ Root Cause

* A misconfigured firewall allowed unrestricted ICMP traffic
* No rate-limiting or IP verification was in place

### ✅ Immediate Fixes

* Blocked ICMP traffic
* Took down non-critical systems
* Restored critical services

---

## 🧱 NIST CSF-Based Analysis

### 1. **Identify**

* Audited network devices and firewall settings
* Assessed unprotected entry points and ICMP-related risk
* Established baseline network behavior

### 2. **Protect**

* Applied ICMP rate limiting and firewall filtering
* Trained staff to detect DDoS symptoms
* Implemented segmentation and cloud-based DDoS defenses

### 3. **Detect**

* Deployed traffic monitoring tools and IDS/IPS
* Tuned logging policies
* Performed threat hunting for early indicators

### 4. **Respond**

* Executed incident response plan
* Blocked malicious IPs
* Documented response actions and conducted post-mortem review

### 5. **Recover**

* Restored mission-critical systems in phases
* Validated data integrity
* Updated business continuity plans and stakeholder communication

---

## 📄 Included Files

```
incident-response-analysis/
│
├── Incident report analysis.pdf    
├── Incident Response Analysis.md                       
```

## 💭 Reflections

> "This exercise showed me how even short-lived attacks can expose significant security weaknesses. The structured use of the NIST CSF helped me identify gaps and create a plan to harden systems and prepare better for future threats."
> — *Tshepang*

---

## 🙋 About Me

I'm **Tshepang**, a beginner cybersecurity analyst building a practical portfolio. This project was created as part of my journey through the **Google Cybersecurity Certificate** and my personal interest in defensive security and risk management.

