# Basic-Nmap-Scan
Basic network scanning using Nmap to identify open ports and services on a virtual machine.
ap

## Objective
To perform a basic network scan on a virtual machine to identify open ports and running services using Nmap.

## Tool Used
- Nmap 7.95

## Target
- Virtual Machine IP: 192.168.1.8

## Services Enabled
- SSH (Port 22)
- Apache HTTP Server (Port 80)

## Commands Used
- nmap 192.168.1.8
- nmap -sV 192.168.1.8

## Scan Results
- Port 22 (SSH): OpenSSH service detected for secure remote access.
- Port 80 (HTTP): Apache web server detected.

## Significance
Identifying open ports and services helps security analysts understand exposed services and potential attack surfaces.

## Conclusion
The Nmap scan successfully identified active services on the virtual machine, demonstrating basic network reconnaissance skills.
