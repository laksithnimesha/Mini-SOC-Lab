# Lessons Learned



This project provided practical experience in building and operating a small-scale Security Operations Center.



## Key Lessons



\### SIEM is only one part of detection

Wazuh provided centralized visibility, but meaningful detection required integrating multiple sources such as endpoint logs and Suricata IDS.



### Alerts require validation

An alert alone is not enough. Packet capture was necessary to validate suspicious activity and confirm what actually happened on the network.



\### Detection quality depends on telemetry

Detection accuracy improved significantly after integrating Suricata logs and tuning rules for better visibility.



### Correlation matters

Single authentication failures are low-value alerts. Correlating repeated failures into brute-force behavior produces stronger detections.



### Packet evidence improves investigations

Using tcpdump and Wireshark made it possible to confirm attacks with direct packet-level evidence.



## Outcome



This project improved practical understanding of:

- SOC workflows

- SIEM operations

- IDS integration

- detection engineering

- packet analysis

- alert investigation
