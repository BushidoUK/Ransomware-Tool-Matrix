# Ransomware Tool Matrix
- This repository contains a list of which tools each ransomware gang or extortionist gang uses
- As defenders, we should exploit the fact that many of the tools used by these cybercriminals are often reused
- We can threat hunt, deploy detections, and block these tools to eliminate the ability of adversaries to launch intrusions
- This project will be updated as additional intelligence on ransomware gang TTPs is made available

You can find the introduction blog post here: [The Ransomware Tool Matrix](https://blog.bushidotoken.net/2024/08/the-ransomware-tool-matrix.html)

> [!TIP]
>  This Ransomware Tool Matrix has several use cases, which are as follows:
> - As a list of leads for threat hunting inside the environments available to you
> - As a list of leads to look for during incident response engagements
> - As a checklist of tools to identify patterns of behaviour between certain ransomware affiliates

## Ransomware Tool Matrix
- [RMM Tools](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/Tools/RMM-Tools.md)
- [Exfiltration Tools](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/Tools/Exfiltration.md)
- [Credential Theft Tools](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/Tools/CredentialTheft.md)
- [Defense Evasion Tools](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/Tools/DefenseEvasion.md)
- [Networking Tools](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/Tools/Networking.md)
- [Discovery Tools](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/Tools/DiscoveryEnum.md)
- [Offensive Security Tools](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/Tools/Offsec.md)
- [Living-off-the-Land Binaries and Scripts](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/Tools/LOLBAS.md)

## Ransomware Gang's Most Used Tools
- [List of Tools used by +10 Ransomware Gangs](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/Tools/MostUsedTools.md)

## Threat Intel Sources
- [List of CISA's Threat Groups](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/ThreatIntel/CISAThreatGroups.md)
- [List of The DFIR Report's Threat Groups](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/ThreatIntel/TheDFIRReportGroups.md)
- [List of Trend Micro's Threat Groups](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/ThreatIntel/TrendMicroThreatGroups.md)
- [The Conti Playbook](https://blog.talosintelligence.com/conti-leak-translation/)
- [The Bassterlord Networking Manual](https://ecirtam.net/autoblogs/autoblogs/wwwecirtamnetlinks_0241ee9d15822b0727e62c15c61de467d47742f3/media/eb33778a.2021-08-3120-20Bassterlord20FishEye20Networking20Manual20X.pdf)
- [Extra Threat Intel](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/ThreatIntel/ExtraThreatIntel.md)

## Challenges
> [!IMPORTANT]
> Using the Ransomware Tool Matrix comes with its own challenges. While it is undoubtedly useful to have a list of tools commonly used by ransomware gangs to hunt, detect, and block, there are some risks. 

- Many of the tools referenced in this repository may be currently used by your IT team or even your Cybersecurity team.
- When hunting for these tools, you may uncover many installations of these tools inside your environment.
- Deciphering whether a tool is being used legitimately, by an employee, with permission is difficult in a large or global environment.
- If you create a detection rule, you may generate a large amount of alerts, which may get ignore or turned off without investigating them.
- If you block these tools without investigating for legitimate usage, you may cause disruption to legitimate business operations and potentially impose costs on your own organisation.

#### How To Contribute
- Please see the following [guidelines](https://github.com/BushidoUK/Ransomware-Tool-Matrix/blob/main/HowToContribute.md) to contribute to this repo.

#### Integrations
- [Ransomware.live](https://x.com/JMousqueton/status/1824434279251665259)
- [eCrime.ch](https://x.com/ecrime_ch/status/1824469830613021070)
