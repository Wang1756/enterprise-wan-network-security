# Enterprise WAN and Network Security Simulation

## Overview
This project simulates a secure, multi-site enterprise network infrastructure connecting a Headquarters (Penang) with a Branch Office (Krung Thep). The infrastructure utilizes network segmentation, dynamic routing protocols, and strict Layer 2 security for a robust and controlled enterprise environment.

## Key Features
* **Network Segmentation:** Implementation of VLAN technology to isolate Sales, R&D, Engineering, and Finance into distinct logical domains.
* **Layer 2 Security:** Deployment of Port Security, DHCP Snooping, and Dynamic ARP Inspection (DAI) to prevent MAC flooding, DHCP spoofing, and ARP poisoning attacks.
* **Dynamic Routing:** Configuration of EIGRP (Enhanced Interior Gateway Routing Protocol) to manage Wide Area Network (WAN) connectivity between distributed sites.
* **Traffic Governance:** Implementation of Extended Access Control Lists (ACLs) to regulate inter-departmental communication while permitting essential services.
* **Operational Visibility:** Integration of a Syslog server for centralized event logging and an IoT server for remote monitoring of building infrastructure.

## Technology Stack
* **Simulation Tool:** Cisco Packet Tracer.
* **Protocols:** EIGRP, 802.1Q Trunking, OSPF (comparative analysis), DHCP, SMTP, FTP, HTTPS, Syslog.
* **Security Controls:** VLANs, Port Security, BPDU Guard, Access Control Lists (ACLs), Storm Control.
