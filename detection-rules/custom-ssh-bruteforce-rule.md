\# Custom SSH Brute Force Detection Rule



This custom Wazuh rule detects repeated SSH authentication failures from the same source IP within a short timeframe.



\## Rule Logic



\- Trigger when 5 SSH authentication failures occur

\- Time window: 60 seconds

\- Correlate by source IP

\- Raise high-severity brute-force alert



\## Detection Purpose



This rule improves detection of SSH brute-force attacks beyond default authentication failure alerts.



\## MITRE ATT\&CK Mapping



\- T1110 — Brute Force

