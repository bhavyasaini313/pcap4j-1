# Network Packet Sniffer (Java & Pcap4j) 🛡️

## Overview
This project is a functional network traffic analyzer developed during my B.Tech in Cyber Security at Chandigarh Engineering College. It interfaces with the Data Link Layer to intercept live packets and analyze protocol vulnerabilities.

## Features
* **Live Capture:** Hooks into the Network Interface Card (NIC) via Pcap4j.
* **TCP Stream Reconstruction:** Analyzes packet payloads to identify plaintext data.
* **Maven Integration:** Managed dependencies for native library bridging.

## Technical Stack
* **Language:** Java
* **Libraries:** Pcap4j, Slf4j
* **Tools:** Wireshark (for validation), Maven (for build management)

## Security Impact
Developed as a Proof-of-Concept for **Man-in-the-Middle (MITM)** vulnerability assessment. Successfully identified plaintext exposure in unencrypted HTTP traffic, demonstrating the necessity of TLS/SSL encryption.