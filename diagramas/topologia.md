# Topología del laboratorio

El laboratorio está compuesto por dos máquinas virtuales:

- Kali Linux (máquina auditora)
- AlmaLinux (máquina objetivo)

## Diagrama

Kali Linux
192.168.1.145

↓

Escaneo con Nmap  
Captura de tráfico con tcpdump  
Pruebas de conexión SSH  

↓

AlmaLinux 
192.168.1.144

Servicios:

- OpenSSH
- ACL configuradas
- Reglas iptables
- ICMP restringido