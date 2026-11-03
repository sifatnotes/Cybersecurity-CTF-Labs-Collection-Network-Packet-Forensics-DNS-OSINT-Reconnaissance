# Cybersecurity-CTF-Labs-Collection-Network-Packet-Forensics-DNS-OSINT-Reconnaissance
A curated, searchable index of hands-on CTF labs covering TCP/IP protocol analysis, packet forensics, ARP spoofing hunts, DNS security, Shodan exposure, Google dorking, metadata analysis, and Maltego OSINT from Learn SecByte.
# Network Packet Forensics, DNS & OSINT Reconnaissance CTF Labs Collection

A structured, searchable index of hands-on cybersecurity labs focusing on Network Traffic Analysis & Packet Forensics (TCP/IP Protocols, ARP Spoofing Intrusion Hunting, Packet Pathology, DNS Resolution Mechanics, Core Networking Fundamentals) and OSINT & Reconnaissance Tradecraft (Passive Infrastructure Discovery, Shodan Internet Exposure, Google Dorking Search Operators, DNS Record Enumeration, WHOIS Breadcrumb Tracking, Metadata Extraction Forensics, and Maltego Link Analysis) hosted on Learn SecByte.

This collection is designed for network security analysts, incident responders, threat hunters, OSINT investigators, bug bounty researchers, and penetration testers seeking practical experience in packet-level investigation and external attack surface mapping.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
  - [Network Protocol Pathology & Packet Forensics](#network-protocol-pathology--packet-forensics)
  - [Active & Passive OSINT Reconnaissance](#active--passive-osint-reconnaissance)
  - [Domain Mapping, Metadata & Link Analysis](#domain-mapping-metadata--link-analysis)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Effective threat detection and target discovery require proficiency at two key layers: analyzing raw network packet flow and mapping external attack surfaces. At the network level, dissecting TCP/IP handshakes, hunting ARP poisoning attacks, and analyzing DNS traffic are fundamental to identifying intrusions and exfiltration channels. On the reconnaissance front, leveraging Open Source Intelligence (OSINT)—via search engines, asset search engines like Shodan, WHOIS records, document metadata, and visual link graphs—enables security teams to uncover exposed assets before adversaries exploit them.

This repository organizes hands-on network forensics and OSINT labs from Learn SecByte into structured learning paths covering packet-level analysis and external reconnaissance.

---

## Lab Collection & Index

| Lab Title | Technical Domain | Primary Focus Category | Access Link |
| :--- | :--- | :--- | :--- |
| **DNS in Action** | Network Protocols | DNS Resolution, Query Types & Mechanics | [Access Lab](https://learn.secbyte.org/ctf/dns-in-action) |
| **ARP Intrusion Hunt** | Network Forensics | ARP Poisoning, Spoofing & Layer-2 Hunts | [Access Lab](https://learn.secbyte.org/ctf/arp-intrusion-hunt) |
| **Packet Trail Investigator** | DFIR / Network | Packet Capture Triage & Traffic Analysis | [Access Lab](https://learn.secbyte.org/ctf/packet-trail-investigator) |
| **TCP/IP Deep Dive** | Network Protocols | Packet Pathology & Flag Anomaly Analysis | [Access Lab](https://learn.secbyte.org/ctf/tcp-ip-deep-dive-packet-pathology-lab) |
| **Networking Fundamentals** | Core Networking | Packets to Incident Response Workflows | [Access Lab](https://learn.secbyte.org/ctf/networking-fundamentals-from-packets-to-incidents) |
| **Reconnaissance Masterclass** | OSINT / Recon | Passive & Active Target Reconnaissance | [Access Lab](https://learn.secbyte.org/ctf/reconnaissance-masterclass) |
| **Shodan Essentials** | Attack Surface | Internet Exposure & Unfiltered Recon | [Access Lab](https://learn.secbyte.org/ctf/shodan-essentials-internet-exposure-reconnaissance) |
| **Google Dorking** | OSINT | Search Engine Operators & Asset Leaks | [Access Lab](https://learn.secbyte.org/ctf/google-dorking-search-engine-reconnaissance) |
| **DNS Enumeration** | OSINT / DNS | Zone Transfers, Subdomains & Records | [Access Lab](https://learn.secbyte.org/ctf/dns-enumeration-from-records-to-real-insights) |
| **WHOIS Investigation** | OSINT | Domain Breadcrumbs, Registrants & History | [Access Lab](https://learn.secbyte.org/ctf/whois-investigation-following-the-domain-breadcrumbs) |
| **Metadata Forensics** | DFIR / OSINT | Hidden Document & Image Data Extraction | [Access Lab](https://learn.secbyte.org/ctf/metadata-forensics-the-hidden-story) |
| **Maltego Investigation Lab** | OSINT / Analysis | Graphical Link Analysis & Infrastructure Trees | [Access Lab](https://learn.secbyte.org/ctf/maltego-investigation-lab) |

---

## Categories

### Network Protocol Pathology & Packet Forensics
Hands-on CTF labs detailing low-level protocol inspection, packet capture analysis, ARP cache poisoning detection, and network incident investigation:

* **Networking Fundamentals (Packets to Incidents):** Understanding OSI/TCP-IP models, packet encapsulation, frame headers, and bridging protocol analysis with incident response scenarios.
  * Lab Link: https://learn.secbyte.org/ctf/networking-fundamentals-from-packets-to-incidents
* **TCP/IP Deep Dive (Packet Pathology):** Inspecting TCP handshakes, flag anomalies (SYN-FIN, NULL scans), sequence number tracking, fragment reassembly, and malformed IP packets.
  * Lab Link: https://learn.secbyte.org/ctf/tcp-ip-deep-dive-packet-pathology-lab
* **Packet Trail Investigator:** Analyzing PCAP files in Wireshark/tshark to reconstruct HTTP/DNS streams, carve file attachments, and detect data exfiltration channels.
  * Lab Link: https://learn.secbyte.org/ctf/packet-trail-investigator
* **ARP Intrusion Hunt:** Hunting layer-2 attacks, detecting gratuitous ARP poisoning, identifying Man-in-the-Middle (MitM) gateways, and writing detection rules.
  * Lab Link: https://learn.secbyte.org/ctf/arp-intrusion-hunt
* **DNS in Action:** Analyzing recursive/authoritative DNS lookups, inspecting A, AAAA, MX, TXT, and CNAME records, and identifying covert DNS tunneling channels.
  * Lab Link: https://learn.secbyte.org/ctf/dns-in-action

### Active & Passive OSINT Reconnaissance
Practical labs focused on public search operators, exposed device discovery, and mapping external organization footprints:

* **Reconnaissance Masterclass:** Developing systematic passive and active reconnaissance frameworks to enumerate target domains, IPs, and organization assets.
  * Lab Link: https://learn.secbyte.org/ctf/reconnaissance-masterclass
* **Shodan Essentials (Internet Exposure Reconnaissance):** Querying Shodan filters to locate exposed industrial control systems, unauthenticated databases, open ports, and vulnerable services.
  * Lab Link: https://learn.secbyte.org/ctf/shodan-essentials-internet-exposure-reconnaissance
* **Google Dorking (Search Engine Reconnaissance):** Utilizing advanced search operators (`filetype:`, `inurl:`, `intitle:`, `site:`) to discover exposed config files, backup archives, and administrative portals.
  * Lab Link: https://learn.secbyte.org/ctf/google-dorking-search-engine-reconnaissance

### Domain Mapping, Metadata & Link Analysis
Security labs covering domain ownership tracking, document metadata extraction, and graphical intelligence relationship mapping:

* **DNS Enumeration (Records to Real Insights):** Performing automated subdomain enumeration, attempting DNS zone transfers (`AXFR`), and discovering hidden infrastructure endpoints.
  * Lab Link: https://learn.secbyte.org/ctf/dns-enumeration-from-records-to-real-insights
* **WHOIS Investigation:** Analyzing historic domain registration data, privacy protection bypass clues, registrar details, and tracking related threat actor domains.
  * Lab Link: https://learn.secbyte.org/ctf/whois-investigation-following-the-domain-breadcrumbs
* **Metadata Forensics (The Hidden Story):** Extracting EXIF camera data, author details, software versions, and internal file paths from PDF, DOCX, and image files.
  * Lab Link: https://learn.secbyte.org/ctf/metadata-forensics-the-hidden-story
* **Maltego Investigation Lab:** Building visual entity graphs, executing transforms, and mapping complex relations across IP blocks, domain names, emails, and social profiles.
  * Lab Link: https://learn.secbyte.org/ctf/maltego-investigation-lab

---

## Learning Path

Follow this structured roadmap to master network packet forensics and OSINT reconnaissance:

1. **Network Protocol Mechanics & Packet Inspection**
   - Study Networking Fundamentals and DNS in Action to understand frame structures.
   - Deep-dive into packet anomalies with TCP/IP Deep Dive and solve network incidents in Packet Trail Investigator.
2. **Layer-2 Attacks & Traffic Threat Hunting**
   - Detect internal spoofing and MitM attacks using ARP Intrusion Hunt.
3. **Passive OSINT & Search Engine Reconnaissance**
   - Master search operators via Google Dorking and discover exposed Internet nodes using Shodan Essentials.
   - Structure intelligence collection with Reconnaissance Masterclass.
4. **Domain Intelligence, Metadata & Entity Graphing**
   - Map domain infrastructures via DNS Enumeration and WHOIS Investigation.
   - Extract hidden document data with Metadata Forensics and visually map attack surfaces using Maltego.

---

## How to Use the Labs

1. Select a practice scenario from the index table or category breakdown above.
2. Launch the target lab environment directly on Learn SecByte using the provided access link.
3. Complete hands-on tasks using network and OSINT tools (Wireshark, tshark, tcpdump, NetworkMiner, Shodan CLI, Maltego, ExifTool, dig, whois, and Amass).
4. Review post-lab threat reports, network defense signatures, and attack surface remediation steps to apply in production environments.

---

## Disclaimer

This repository is strictly intended for educational research, authorized security investigations, and defensive network training. All concepts, tools, and lab environments are provided to help cybersecurity practitioners build practical expertise and defend enterprise networks. Unsanctioned network packet interception, unauthorized OSINT scraping, or port scanning against external systems without explicit written permission are strictly illegal.
