# Suricata IDS Home SOC Lab

This project demonstrates how network intrusion detection works by generating attack traffic and detecting it using Suricata.

The purpose was to understand real SOC workflow instead of only theory.

---

## Lab Environment

Attacker Machine: Kali Linux
Monitoring Machine: Kali Linux (Suricata IDS)
Hypervisor: VMware Workstation
Network: Host-Only isolated network

---

## Tools Used
- Suricata IDS
- Nmap
- VMware

---

## Activity Performed

1. Installed and configured Suricata
2. Loaded detection rules
3. Generated reconnaissance scan using Nmap
4. Monitored alerts in real time

---

## Result

Suricata successfully generated alerts detecting reconnaissance behaviour.

This confirmed signatures were matching network traffic correctly.

---

## Learning Outcome

I learned the difference between generating traffic and detecting it.

Detection depends on signatures and behaviour, not just running tools.
