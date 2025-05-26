# 🔍 Network Scanning & Analysis Project

This project involves scanning a local network using **Nmap**, capturing network packets using **Wireshark**, and analyzing open ports to assess potential security risks.

---

## 🧠 Objective

To explore and analyze the local network by identifying active hosts, discovering open ports, capturing traffic using Wireshark, and highlighting potential security risks based on the findings.

---

## 🛠️ Tools Used

| Tool        | Use                                      |
|-------------|------------------------------------------|
| Nmap        | Network scanning (TCP SYN scan)          |
| Wireshark   | Live packet capturing and inspection      |
| Kali Linux  | Operating System / Testing Environment   |

---

## 🌐 IP Configuration

- **Local IP Address:** `10.0.2.15`
- **Target Subnet:** `10.0.2.0/24`
- **Interface Used:** `eth0`

To find your IP and interface:
```bash
ip a
```
---


To run TCP SYN scan:
```bash
sudo nmap -sS 10.0.2.0/24
```
---

To start Wireshark capture:
```bash
sudo wireshark
```
---

To save scan results as a Text file:
```bash
sudo nmap -sS 10.0.2.0/24 -oN nmap_scan.txt
```
---
