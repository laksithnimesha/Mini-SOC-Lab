# Mini SOC Lab



A practical Mini Security Operations Center (SOC) built using Wazuh, Suricata, and Ubuntu to simulate, detect, and investigate network attacks in a controlled virtual lab.



---



## Overview



This project demonstrates a complete SOC workflow:



- Simulate attacks from Kali Linux

- Monitor endpoint and network activity on Ubuntu

- Detect threats using Suricata IDS

- Correlate and visualize alerts in Wazuh SIEM

- Validate detections using packet capture (tcpdump/Wireshark)



---



## Architecture



![Mini SOC Architecture](architecture/mini-soc-architecture.png)



---



## Tools Used



- Wazuh

- Suricata

- Kali Linux

- Ubuntu

- Hydra

- Nmap

- tcpdump

- Wireshark



---



## Attack Simulations



- Nmap SYN Scan

- SSH Brute Force (Hydra)



---



## Detection Capabilities



- SSH authentication failures

- SSH brute-force detection

- Network IDS alerts

- Suricata event ingestion

- Packet-level validation



---



## Investigation Workflow



1. Attack simulated from Kali

2. Traffic reaches Ubuntu Victim

3. Suricata inspects packets

4. Wazuh collects and correlates logs

5. Alerts appear in dashboard

6. Packets validated with tcpdump / Wireshark



---



## Screenshots



See `screenshots` for:

- Dashboard

- Alerts

- Suricata detections

- Packet captures

- Wireshark analysis



---



## Key Outcomes



- Built a functioning Mini SOC

- Integrated IDS with SIEM

- Simulated offensive attacks

- Investigated alerts with packet evidence

- Practiced detection and analysis workflow

