# 🐍 Cowrie Honeypot Project – SSH Threat Analysis

## 📌 Overview
This project showcases the deployment and analysis of an SSH honeypot using **Cowrie**, a low-interaction honeypot written in Python. It simulates a vulnerable SSH service to attract and log real-world attack attempts for educational and research purposes.

> ⚠️ This was deployed in a controlled and isolated environment strictly for learning and cybersecurity research.

---

## 🛠️ Tools & Technologies
- **Cowrie** (SSH/Telnet honeypot)
- **Kali Linux** (Virtual Machine)
- **Python3 + Virtualenv**

---

## ⚙️ What It Does
- Listens on port `2222` for fake SSH access
- Simulates a file system, commands, and shell interaction
- Logs:
  - Username/password attempts
  - Shell commands run by attackers
  - Download attempts (`wget`, `curl`)
  - Full attacker sessions (`tty` logs)

---

## 🔍 Sample Logs

