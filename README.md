## Detecting nmap scans and bruteforce attempts using Wazuh and Suricata
This project simulates detecting nmap scan, and ssh bruteforce using wazuh and suricata.
## Tools Used
- Wazuh agent and manager
- Suricata
- Hydra
- Ubuntu server
- Kali linux
## Steps Performed
- Setup suricata
- Setup Wazuh agent and manager
- Launched a nmap scan and detected it using Wazuh manager.
- Found that port 22 ssh is open in target system.
- Lauched a bruteforce attack against ssh.
- Detected the attack.
- Blocked the attacker's ip using ufw (firewall).
- Attacker cannot do nmap scan, bruteforce, etc... anymore.
## Screenshots
![1760337040084](https://github.com/user-attachments/assets/c8047e7e-d763-4437-a9c9-94b5409f2d8a)
![1760337008823](https://github.com/user-attachments/assets/da645e93-b08c-4dc2-96f4-17da791f9935)
![1760337005798](https://github.com/user-attachments/assets/c6f81276-a431-4dba-9f5e-c232f9e03289)
![1760337048512](https://github.com/user-attachments/assets/b783e06e-a17e-4290-abe2-f8ca75efa0fb)
## Outcome
Successfully detected and blocked nmap scan and bruteforce attempts.
## Note
This was a self-simulated lab exercise for learning and practicing.
