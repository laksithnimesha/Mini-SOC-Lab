# Setup Guide



This document outlines how the Mini SOC Lab was built in a controlled VMware environment.



---



## Lab Environment



The lab consists of three virtual machines:



- Kali Linux (Attacker)

\- Ubuntu Victim (Monitored Host)

\- Ubuntu SOC Server (Wazuh SIEM)



All systems were connected using a host-only virtual network.



---



## Components Installed



### Kali Linux

Used for attack simulation:

- Nmap

- Hydra



### Ubuntu Victim

Used as the monitored target system:

- Wazuh Agent

- Suricata IDS

- tcpdump

- Wireshark



### Ubuntu SOC Server

Used as the central monitoring server:

- Wazuh Manager

- Wazuh Indexer

- Wazuh Dashboard



---



\## Network Configuration



| System | Role | IP Address |

|------|------|------------|

| Kali Linux | Attacker | 192.168.100.10 |

| Ubuntu Victim | Target | 192.168.100.20 |

| SOC Server | SIEM | 192.168.100.30 |



---



## Setup Summary



1. Created three virtual machines in VMware

2. Configured static IP addresses

3. Installed Wazuh on SOC Server

4. Installed Wazuh Agent on Ubuntu Victim

5. Connected Ubuntu Agent to Wazuh Manager

6. Installed and configured Suricata

7. Forwarded Suricata logs to Wazuh

8. Simulated attacks from Kali

9. Validated detections with packet captures

