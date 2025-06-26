# 🔍 Nmap-Based Vulnerability Assessment

## 📌 Project Overview

This project documents a vulnerability assessment conducted on a target machine using **Nmap**, a powerful network scanning tool. Although the original intention was to use **OpenVAS** or **Nessus Essentials**, due to technical and licensing constraints (Kali Linux not functioning and Nessus trial expired), the assessment was carried out entirely using Nmap and its scripting engine.

---

## 🎯 Objective

- Perform network scanning to identify open ports and services.
- Detect potential vulnerabilities using Nmap scripts.
- Recommend basic security mitigations for the findings.

---

## 🛠️ Tools Used

- **Nmap v7.97** – For scanning and service/version detection.
- **Nmap Scripting Engine (NSE)** – To check for specific vulnerabilities.
- **Windows Command Line (cmd)** – As the scanning host.

---

## 🧪 Scanning Methodology

1. **Service Detection**
   ```bash
   nmap -sV 10.1.41.73
# cybersecuritytask-3
