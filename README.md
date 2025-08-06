# nmap-recon-audit

Mapping internal networks and checking open ports using Nmap helps to improve recon skills, uncover possible vulnerabilities, and build a strong base in network security.

---

## Objective

To actively scan and audit devices within a local subnet, identify open ports and services, and gather useful insights into internal network visibility. 

---

## Why This Project?

Because every device tells a story.  
Knowing what's running on your network isn't optional; it's necessary.  
This repository captures the hands-on process of real-world network reconnaissance using Nmap.

---

## Tools & Stack

- **Nmap** – The original network scanner.
- **xsltproc** – Converts XML into clean HTML reports.
- **Linux Terminal** – Straight command-line interface.
- *(Optional)* **Wireshark** – Packet-level visualizer.

---

## Techniques Used

| Technique        | Command Example                                         |
|------------------|----------------------------------------------------------|
| Fast Scan        | `nmap -F 10.189.176.0/24`                                |
| TCP SYN Scan     | `nmap -sS 10.189.176.0/24`                               |
| OS Detection     | `nmap -O 10.189.176.0/24`                                |
| Version Scan     | `nmap -sV 10.189.176.0/24`                               |
| Aggressive Scan  | `nmap -A 10.189.176.0/24`                                |
| HTML Reporting   | `xsltproc output.xml -o scan_results.html`              |

---

## Files Inside

| File Name              | Description                                         |
|------------------------|-----------------------------------------------------|
| `aggressive_scan.txt`  | OS & service detection with traceroute              |
| `fast_scan_results.txt`| Quick scan output                                   |
| `os_scan.txt`          | OS fingerprinting results                           |
| `version_scan.txt`     | Detected services and versions                      |
| `scan_results.txt`     | Summary scan result                                 |
| `output.xml`           | Raw XML output for parsing/reporting                |
| `scan_results.html`    | Finished scan report for easy reading              |

---

## What I Learned

- Conducting stealthy and comprehensive scans across subnets.
- Understanding what exposed ports can indicate.
- Identifying risky services (e.g., Telnet, FTP, etc.).
- Creating clear, shareable scan reports.
- Practicing ethical recon on authorized networks.

---

## Insights

This project focuses on action, not just theory.

"Know your network before someone else does."

---

## Ethical Use Only

This tool is used only on authorized networks.  
No part of this project supports illegal activities or scanning unauthorized systems.  
Practice responsibility. 
Stay sharp. Stay legal.

---
