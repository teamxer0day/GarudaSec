# GarudaSec
End-to-end web app pentest lab

**GarudaSec** is a **Rust (Axum + SQLx + SQLite)** based intentionally vulnerable web application designed for **end-to-end penetration testing, exploitation, and remediation** practice.  
This 4-week lab demonstrates the **complete lifecycle** of a web application pentest — from vulnerability discovery to secure code remediation and CVSS-scored reporting.

---

## 📘 Overview

GarudaSec provides a controlled, containerized environment for studying and demonstrating real-world web vulnerabilities such as:

- SQL Injection (SQLi)  
- Cross-Site Scripting (XSS)  
- Insecure Authentication  
- Weak Input Validation  

The lab includes intentionally insecure modules for educational use, exploit PoCs, verified remediation patches, and a full penetration testing report.

> ⚠️ **Security Disclaimer:**  
> This project is intentionally vulnerable and is provided strictly for **educational, research, and training purposes**.  
> Do **NOT** deploy this application in production or on public networks.  
> The author assumes **no responsibility** for misuse or damage caused by this software.

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Language** | Rust (Edition 2021) |
| **Web Framework** | [Axum](https://github.com/tokio-rs/axum) |
| **Database** | SQLite (via [SQLx](https://github.com/launchbadge/sqlx)) |
| **Containerization** | Docker + docker-compose |
| **Security Tooling** | Burp Suite, SQLMap, Nmap, Metasploit |
| **Reporting** | CVSS v3.1 scoring, Markdown → PDF |


---

## 📅 Project Timeline

| **Phase** | **Focus** | **Deliverables** |
|------------|------------|------------------|
| **Week 1** | Build intentionally vulnerable app | - Initial commit<br>- Dockerized application |
| **Week 2** | Perform penetration testing | - Findings documentation<br>- Exploit proofs and methodology |
| **Week 3** | Implement remediation | - Secure code implementation<br>- Proof-of-fix verification |
| **Week 4** | Report + Portfolio Release | - Comprehensive PDF security report<br>- GitHub release version<br>- LinkedIn announcement post |
