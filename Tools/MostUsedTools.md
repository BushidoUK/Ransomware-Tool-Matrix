## Most Used Tools

> [!TIP]
> This is a list compiled from the Ransomware Tool Matrix to highlight the most used tools by at least 10 or more ransomware gangs. If you can detect, block, or hunt for these, you can likely stop at least half of all ransomware gang templated attacks.

| Tool Name | Type | Threat Group Usage | MITRE ATT&CK TTPs | Detection Rules |
|---|---|---|---|---|
| SoftPerfect NetScan | Discovery | BlackSuit, Royal, Black Basta, Akira, LockBit, BianLian, Conti, BlackCat, Dagon Locker, Nokoyawa, Trigona, Hive, BlackByte | [T1046](https://attack.mitre.org/techniques/T1046/) | [Detection.FYI Rules](https://detection.fyi/search/?query=netscan) |
| Advanced IP Scanner | Discovery | MAZE, BlackSuit, Royal, Akira, LockBit, Diavol, GoGoogle, INC Ransom, Hive, Zola, DarkSide, PYSA | [T1018](https://attack.mitre.org/techniques/T1018/) | [Detection.FYI Rules](https://detection.fyi/search/?query=advanced%20ip%20scanner) |
| AdFind | Discovery | BlackSuit, Royal, PLAY, LockBit, Conti, Dagon Locker, Nokoyawa, Quantum, Diavol, XingLocker, REvil, Ryuk, NetWalker, INC Ransom | [S0552](https://attack.mitre.org/software/S0552/) | [Detection.FYI Rules](https://detection.fyi/search/?query=adfind) |
| GMER | Evasion Tool| BlackSuit, Royal, PLAY, LockBit, Bassterlord*, Conti, 8BASE, TargetCompany, Hive, Avaddon | [T1562.001](https://attack.mitre.org/techniques/T1562/001/) | [Detection.FYI Rules](https://detection.fyi/search/?query=gmer) | 
| Cobalt Strike | OffSec | BlackSuit, Royal, Black Basta, Phobos, BlackCat, PLAY, Cuba, Karakurt, AvosLocker, Snatch, LockBit, CL0P, Vice Society, Trigona, Conti, Dagon Locker, Nokoyawa, Hive, Quantum, Diavol, XingLocker, REvil, Ryuk, NetWalker, RansomEXX | [S0154](https://attack.mitre.org/software/S0154/) | [Detection.FYI Rules](https://detection.fyi/search/?query=cobalt%20strike) |
| Mimikatz | Credential Theft | BlackSuit, Royal, Black Basta, Akira, Phobos, PLAY, Karakurt, Scattered Spider, AvosLocker, LockBit, Conti, Bassterlord, Quantum, PYSA, NetWalker, GoGoogle, 8BASE, Trigona, Cuba, RansomEXX | [S0002](https://attack.mitre.org/software/S0002/) | [Detection.FYI Rules](https://detection.fyi/search/?query=mimikatz) |
| AnyDesk | RMMM Tool | BlackSuit, Royal, Akira, BlackCat, Karakurt, LockBit, Rhysida, AvosLocker, Conti, Dagon Locker, Nokoyawa, Quantum, Diavol, Trigona, BlackByte, Cactus | [T1219](https://attack.mitre.org/techniques/T1219/) | [Detection.FYI Rules](https://detection.fyi/search/?query=anydesk) |
| Splashtop | RMM Tool |  Black Basta, LockBit, AvosLocker, BianLian, Scattered Spider*, Hive, Quantum, Conti, Trigona, RansomHub, Cactus | [T1219](https://attack.mitre.org/techniques/T1219/) | [Detection.FYI Rules](https://detection.fyi/search/?query=splashtop) |
| PsExec | LOLBAS | BlackSuit, Royal, Black Basta, PLAY, Cuba, Rhysida, AvosLocker, BianLian, Bassterlord, Conti, Nokoyawa, Quantum, PYSA, NetWalker, 8BASE, INC Ransom, Cactus | [S0029](https://attack.mitre.org/software/S0029/) | [Detection.FYI Rules](https://detection.fyi/search/?query=psexec) |
| RClone | Exfil Tool | BlackSuit, Royal, Black Basta, Akira, Karakurt, AvosLocker, LockBit, BianLian, Hive, Daixin, Conti, Dagon Locker, Trigona, Quantum, REvil, 8BASE | [S1040](https://attack.mitre.org/software/S1040/) | [Detection.FYI Rules](https://detection.fyi/search/?query=rclone) | 
| MEGA | Exfil Tool| Akira, Phobos, BlackCat, Karakurt, Scattered Spider, LockBit, BianLian, Hive, Trigona, Quantum | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | [Detection.FYI Rules](https://detection.fyi/search/?query=mega) |
