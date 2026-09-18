# Penetration Testing: Footprinting & Network Scanning

## 📌 Project Overview
This repository contains the documentation and findings for the **Footprinting and Network Scanning** phases of a penetration test, completed as part of the Networkwalks Cybersecurity Program (Week 2). The objective of this project was to demonstrate the progression from passive public information gathering (OSINT) to active internal network mapping.

## 🚀 Modules Completed
* **W2-PM1 (Domain Footprinting):** Active reconnaissance against a target domain using multiple Kali Linux tools.
* **W2-PM2 (Google Hacking Database - GHDB):** Passive reconnaissance and OSINT using advanced Google Dorks to identify exposed assets (unsecured IoT cameras and open directories).
* **W2-PM5 (Network Scanning):** Active discovery of local network subnets, live hosts, and MAC addresses using Zenmap.

## 🛠️ Tools & Technologies Used
* **Operating Systems:** Kali Linux, Windows
* **OSINT & Search:** Google Search Engine, Exploit-DB (GHDB)
* **Reconnaissance Tools:** `whois`, `whatweb`, `nslookup`, `curl`, `wafw00f`, `dnsrecon`
* **Scanning & Mapping:** Nmap / Zenmap

## 📊 Key Learnings & Outcomes
1. **Web Technology & DNS Profiling:** Successfully mapped the target's infrastructure, identifying the CMS (WordPress), WAF (ModSecurity), and DNS records.
2. **OSINT Vulnerability Discovery:** Demonstrated how misconfigured servers and unsecured IoT devices can be discovered globally without ever touching the target systems directly.
3. **Network Topology Mapping:** Successfully mapped a local `/24` subnet, identifying live hosts and routing paths.
4. **Risk Assessment:** Translated technical findings into actionable risk assessments and security recommendations (e.g., disabling directory listing, securing IoT devices behind VPNs, and WAF tuning).

## ⚠️ Legal Disclaimer
All activities documented in this project were performed strictly for educational and research purposes. Active scanning and footprinting were conducted **only** on systems and networks for which explicit, written permission was secured, or on my own local devices. Passive reconnaissance (GHDB) relied entirely on publicly available search engine indexes. Unauthorised access to computer systems is illegal. The author assumes no liability for the misuse of this information.

---
*Completed by Noussaiba Aouad - Master's Student in Cryptography and Information Security | B083-Networkwalks*
