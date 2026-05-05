# SOC PCAP Web Attack Analysis

## 📌 Overview
This project documents a real-world cybersecurity investigation involving a compromised web server.  
The analysis was conducted using a PCAP file to identify how an attacker gained access, established control, and exfiltrated sensitive data.

---

## 🎯 Objectives
- Identify the attacker source and origin
- Detect malicious file upload activity
- Analyze reverse shell communication
- Identify data exfiltration attempts

---

## 🛠 Tools Used
- Wireshark
- TCP Stream Analysis
- HTTP Protocol Inspection

---

## 🧠 Investigation Summary

### 1. Initial Access
- The attacker accessed the web server via HTTP requests.
- Multiple browsing attempts were observed before exploitation.

---

### 2. Malicious File Upload
- A suspicious POST request was identified.
- A malicious web shell was uploaded:
  