# Linux Hardening Lab

![Platform](https://img.shields.io/badge/platform-linux-purple)
![Focus](https://img.shields.io/badge/focus-cybersecurity-red)
![Topic](https://img.shields.io/badge/topic-linux%20hardening-green)
![Lab](https://img.shields.io/badge/type-security%20lab-orange)

Laboratorio de bastionado de un equipo informático sobre **AlmaLinux** con validación y pruebas desde **Kali Linux**.

## Objetivo

Este proyecto documenta un laboratorio de securización de un sistema Linux, incluyendo:

- descubrimiento inicial de puertos y servicios
- configuración segura de OpenSSH
- restricción de acceso mediante SFTP chroot
- gestión de permisos con ACL
- filtrado de tráfico con iptables
- mitigación de tráfico ICMP
- verificación mediante herramientas de red

## Entorno del laboratorio

- **Máquina auditora:** Kali Linux
- **Máquina objetivo:** AlmaLinux
- Herramientas usadas:
  - Nmap
  - tcpdump
  - Wireshark
  - OpenSSH
  - ACL POSIX
  - iptables
  - rsyslog
  - logwatch
  - GoAccess

## Estructura del repositorio

```text
linux-hardening-lab/
├─ README.md
├─ .gitignore
├─ docs/
├─ evidencias/
├─ comandos/
├─ configs/
```

## Resultados del bastionado

Tras aplicar las medidas de seguridad se obtuvieron los siguientes resultados:

- acceso SSH controlado
- usuario SFTP restringido mediante chroot
- permisos avanzados gestionados mediante ACL
- reglas de firewall configuradas con iptables
- mitigación de respuestas ICMP
- reducción de superficie de exposición del sistema

Las evidencias de cada fase pueden consultarse en la carpeta `evidencias`.
## Conocimientos aplicados

Este laboratorio demuestra conocimientos en:

- hardening de sistemas Linux
- configuración de OpenSSH
- gestión de permisos con ACL
- configuración de firewall con iptables
- análisis de red con tcpdump
- reconocimiento de servicios con Nmap
