# DFIR Incident Investigation Lab

Digital Forensics and Incident Response (DFIR) case studies covering RAM memory analysis and PCAP network analysis.

## Incident Case #1: Cobalt Strike Memory Forensics
* **Tool:** Volatility 3
* **Findings:** Identified injected DLLs in `svchost.exe` process, extracted C2 IP addresses from memory artifacts.
* **MITRE ATT&CK Mapping:** T1055 (Process Injection), T1071.001 (Web Protocols).
