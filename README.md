# nmap-task-1
# Cyber Security Internship – Task 1: Port Scanning

This repository contains my completed work for **Task 1** of the Cyber Security Internship.

---

## 🎯 Objective
To scan local network devices using Nmap, identify open ports, and understand potential network exposure.

---

## 🔧 Tools Used
- **Nmap** (version 7.97)
- **Zenmap GUI** (optional)
- OS: Windows
- IP used: `192.168.20.172`

---

## 📁 Files

### 📝 [`TASK 1.txt`](TASK%201.txt)
Contains all Nmap commands used, their outputs, and explanations.

### 📸 [`/screenshots`](screenshots/)
Screenshots of Zenmap/Nmap outputs:

| File        | Description                        |
|-------------|------------------------------------|
| `1.png`     | Scan result for port 80            |
| `2.png`     | Scan result for ports 1–200        |
| `3.png`     | TCP SYN scan                       |
| `4.png`     | Fast scan (-F) result              |
| `5.png`     | Full port scan (1-65535)           |
| `6.png`     | TCP connect scan (-sT)             |

---

## 📌 Task Summary

### Commands Used:
- `nmap -p 80 192.168.20.172`
- `nmap -p 1-200 192.168.20.172`
- `nmap -sS 192.168.20.172`
- `nmap -F 192.168.20.172`
- `nmap -p - 192.168.20.172`
- `nmap -sT 192.168.20.172`

---

## 📚 Learning Outcomes
- Learned about open ports, TCP scanning, filtered ports.
- Understood how tools like Nmap and Wireshark are used in reconnaissance.
- Gained practical exposure in identifying network vulnerabilities.

---

## 🔗 Submission
GitHub repo link: _[https://github.com/Anishgawade/nmap-task-1.git]_
