## Defense Evasion Tools

> [!TIP]
> Various freely available malware detection tools specialize in identifying and removing stealthy threats like rootkits. They offer capabilities such as scanning for hidden processes, files, and drivers, analyzing system memory for malicious modules, and monitoring system hooks for unauthorized modifications. These tools provide detailed insights into system internals, helping to uncover deeply embedded malware that standard antivirus programs might miss.

> [!IMPORTANT]
> Malicious actors can abuse these rootkit detection tools to interfere with security tools, file and registry tampering to disrupt tool functionality, and memory corruption to prevent detection. By using these tools for privilege escalation, an adversary can disable or alter the operation of security software, removing the method systems use to detect or prevent threats.

| Tool Name | Threat Group Usage |
|---|---|
| Avast Anti-Rootkit driver | Cuba, AvosLocker, MONTI |
| Backstab (Process Explorer driver) | Black Basta, LockBit | 
| Bedevil | Scattered Spider* |
| BEST_uninstallTool | BabLock |
| Bluetooth Stack for Windows by Toshiba (toshdpdb.exe) | RA World |
| Darkside (TrueSight driver) | CosmicBeetle* |
| Defender Control | LockBit, Zola |
| Dell Client driver (BYOVD) | BlackByte |
| EDRSandBlast | Cicada3301, Qilin, Medusa |
| EMCO UnLock IT | Zola | 
| Eraser | BlackSuit, Royal |
| FileShredder | BlackCat |
| GIGABYTE Motherboard driver (BYOVD) | BlackByte |
| GMER | BlackSuit, Royal, PLAY, LockBit, Bassterlord*, Conti, 8BASE, TargetCompany, Hive, Avaddon, MONTI |
| HRSword | Medusa Locker |
| IOBit | PLAY |
| Intel Ethernet driver (BYOVD) | Scattered Spider* |
| KillAV | Medusa |
| McAfee OEM Info Copy Files (mcoemcpy.exe) | NailaoLocker | 
| MSI Afterburner driver (BYOVD) | BlackByte |
| NSudo | Royal |
| PCHunter | LockBit, Conti, 8BASE, TargetCompany, Hive, Qilin, FiveHands, Medusa Locker |
| PowerTool | BlackSuit, Royal, Akira, Phobos, PLAY, LockBit, Qilin, Avaddon |
| ProcessHacker | Phobos, LockBit, 8BASE, Zola, Medusa Locker |
| RealBlindingEDR | CosmicBeetle* |
| Reaper | CosmicBeetle* |
| s4killer (Minifilter Driver) | Embargo |
| TDSSKiller | LockBit, Avaddon |
| ThreatFire System Monitor driver (BYOVD) | RansomHub |
| ThrottleStop driver | Medusa |
| Toshiba power management driver (BYOVD) | Qilin |
| Universal Virus Sniffer | Phobos |
| Updater for Carbon Black’s Cloud Sensor AV (upd.exe) | Qilin | 
| VirtualBox | RagnarLocker |
| YDArk | Qilin |
| Zemana Anti-Rootkit driver | Qilin, Akira, BlackByte |
