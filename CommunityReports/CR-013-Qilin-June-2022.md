# Community Report 0013 - Qilin June 2022
### Contributor Details

- Real Name: N/A
- Online Handle / Links to profiles: @knappresearchlb
- Employer: Private, Threat Intelligence Lead
- Affiliations: Ransom-ISAC

---
### Adversary

- Named adversary: Qilin Ransomware

---
### Incident Details

- Time of Incident: June 2022
- Victim Sector: Unknown
- Victim Country: Unknown
- Victim Size: Unknown
- Victim Name: Unknown

---
### Observed Tools

| Discovery | RMM Tools | Defense Evasion | Credential Theft | OffSec | Networking | LOLBAS | Exfiltration |
|---|---|---|---|---|---|---|---|
| | | | | SystemBC | Used SCCM and VMWare ESXi for lateral movement in network| | Not observed (3 systems encrypted)|
| | | | | Tofsee a modular trojan | RDP | | |
| | | | | Kali Linux | WMI | | |
---

### Indicators of Compromise (IOCs)

| Indicator       | Description                                                           |
| --------------- | ---------------------------------------------------------------- |
|   *.ru   |   Connections to multiple rare external hosts. Many of which were using the “[.]ru” Top Level Domain (TLD).    |


#### Any Related Sources

- 

| Date Published | Report |
|---|---|
| 4/7/2024 |  https://www.darktrace.com/blog/a-busy-agenda-darktraces-detection-of-qilin-ransomware-as-a-service-operator |
|   | |


```mermaid
flowchart TD;
    A[Qilin Ransomware] -->|target| B(Geo: Unknown
Sector: Unknown
Size: Unknown);
    B --> C{Tools};
    C -->|OffSec| H[3];
    C -->|Networking| I[3];
    C -->|Exfiltration| J[1];
```
