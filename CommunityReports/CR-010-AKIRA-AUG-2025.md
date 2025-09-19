# Community Report 010 - Akira August 2025 

### Contributor Details
```
- Real Name: Ben Folland
- Online Handle: @polygonben
- Employer: Huntress
```
---
### Adversary
```
- Named adversary: Akira
```
---
### Incident Details
```
- Time of Incident: August 2025
- Victim Sector: Engineering
- Victim Country: USA
- Victom Size: 1-100
```
---
### Observed Tools
 
| Discovery | RMM Tools | Defense Evasion | Credential Theft | OffSec | Networking | LOLBAS | Exfiltration |
|---|---|---|---|---|---|---|---|
| Advanced IP Scanner  |   |   |   |   | Cloudflared  | vssadmin  | WinRAR  |
|   |   |   |   |   | OpenSSH  | netsh  | FileZilla  |
---
### Indicators of Compromise (IOCs)
```
Process Chain / Command Lines:

- powershell.exe -Command "Get-WmiObject Win32_Shadowcopy | Remove-WmiObject"
- "C:\WINDOWS\system32\netsh.exe" advfirewall set allprofiles state off
- "C:\WINDOWS\system32\vssadmin.exe" delete shadows /all /quiet
- "C:\WINDOWS\system32\NOTEPAD.EXE" C:\ProgramData\shares.txt
- "C:\Program Files\WinRAR\WinRAR.exe" a -ep1  -scul -r0 -iext   -imon1 -- . C:\SHARE1 C:\SHARE2 C:\SHARE3
- "C:\Program Files\FileZilla FTP Client\fzsftp.exe" -v
- "C:\WINDOWS\System32\msiexec.exe" /i "C:\Users\[REDACTED]\Desktop\OpenSSHa.msi"

Staging:
- C:\ProgramData\

Ransomware Binary:
- w.exe -p=\\[REDDACTED].local\C$ -n=1
```
---
 
---
| Date Published | Report |
|---|---|
| 04/08/2025 | https://www.huntress.com/blog/exploitation-of-sonicwall-vpn |
