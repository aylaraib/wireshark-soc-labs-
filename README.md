# wireshark-soc-labs-
Hands-on implementation of the Networkwalks Academy Wireshark Project. Features 8 practical labs and advanced assessments covering PCAP analysis, live SOC threat hunting, TCP stream carving, credential harvesting defense, and network troubleshooting.
# Wireshark & SOC Network Analysis Labs
This repository documents my completion of the **Networkwalks Academy Wireshark Project**, consisting of 2 comprehensive training modules, 8 practical labs, and advanced assessments. I achieved 100% / exceptional scores across all modules.

## 📊 Lab Breakdown & Skills Demonstrated

### Part 1: Packet Capture & Baseline Analysis
* **Lab 1: Live Packet Capture:** Captured Wi-Fi traffic, identified local/destination IPs, analyzed DNS queries, and verified TLS versions.
* **Lab 2: PCAP Analysis:** Analyzed an offline capture of `microsoft.com` to isolate network protocols without live connectivity.

### Part 2: SOC & Incident Response Labs (Live Simulation)
* **Lab 3 (Attacker Identification):** Isolated malicious traffic to identify the threat actor's source IP.
* **Lab 4 & 5 (TCP Stream Carving):** Followed full TCP streams to rebuild plain-text conversations and extract transmitted data.
* **Lab 6 (Credential Harvesting Defense):** Identified unencrypted HTTP GET/POST requests exposing plain-text usernames and passwords.
* **Lab 7 (Brute Force Detection):** Spotted repetitive, high-frequency login failures to pinpoint an automated brute-force attack.
* **Lab 8 (Scam Investigation):** Analyzed anomalous protocol behaviors to trace and catch a call-scammer's network footprint.

## 🏆 Assessment Results
* **Wireshark Core Quiz:** Passed with exceptional results (Basics, Filters, & Protocols).
* **Wireshark Advanced Quiz:** Passed with exceptional results (Traffic Patterns & Analysis Tools).

## 🛠️ Tools & Technologies Used
* **Wireshark** (Packet List, Details, and Bytes Panes)
* **Display Filters:** `ip.addr`, `tcp.port`, `http`, `dns`, `tls.handshake.type == 1`
* **Analysis Tools:** Follow TCP Stream, Export Objects (HTTP), Expert Information, I/O Graphs
