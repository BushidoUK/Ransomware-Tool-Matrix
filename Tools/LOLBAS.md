## Living-off-the-Land Binaries and Scripts

> [!TIP]
> Windows environments are equipped with a wide array of command-line utilities. These tools collectively provide robust support for efficient system management, troubleshooting, and optimization, helping administrators maintain secure, stable, and high-performing Windows environments. 

> [!IMPORTANT]
> Cybercriminals often exploit legitimate Windows administrative tools to execute malicious actions while evading detection. These tools, used for tasks such as remote execution, file transfers, and system management, allow attackers to move laterally across networks, download and execute malware, manipulate logs, and gather sensitive information. By leveraging these built-in utilities, attackers can conduct their activities stealthily, blending their actions with normal administrative operations.

| Tool Name | Threat Group Usage |
|---|---|
| BCDEdit | LockBit, Snatch, Hive, Zola, BlackCat, Cicada3301, Embargo |
| BITSAdmin | Black Basta, Hive, REvil, Conti, Medusa, RansomHub, Lockean* |
| fsutil | Qilin |
| NTDS Utility (ntdsutil) | Rhysida, Conti, Yanluowang, Lapsus$, Vice Society |
| PAExec | *Prophet Spider, FiveHands  |
| Process Explorer | Zola |
| PsExec | MAZE, BlackSuit, Royal, Black Basta, PLAY, Cuba, Rhysida, AvosLocker, BianLian, Bassterlord*, Conti, Nokoyawa, Quantum, PYSA, NetWalker, 8BASE, INC Ransom, RansomHub, EvilCorp*, Fog, Medusa, Yanluowang, Scattered Spider*, FiveHands, DarkSide, RagnarLocker, Vice Society, BlackCat, LockBit, Cicada3301, Medusa Locker, Qilin, RA World |
| Minidump | *Prophet Spider, Vice Society |
| Quick Assist | Black Basta |
| ServiceControl (sc.exe) | Snatch, Embargo |
| Windows Event Utility (wevtutil) | Rhysida, Hive, GoGoogle, Yanluowang, BlackCat |
| WinExe | *Prophet Spider |
| WMIC | MAZE, Conti, Hive, Quantum, TargetCompany, PYSA, AvosLocker, RagnarLocker, Vice Society, Rhysida, BlackCat, Cicada3301, Ghost/Cring |
| WinRM | Qilin |
