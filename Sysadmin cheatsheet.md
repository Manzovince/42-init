# System Administration Cheatsheet

> Project 42-init
Discover the basic system and network commands as well as the many services used on a server machine, and some scripting ideas that can be useful on a daily basis for an adminsys.

___
## Basic commands
man top: List process
man ps: Show process status
man kill: Kill process
man df: Display free disk space
man ifconfig: Configure network interface parameters
man ping: send ICMP ECHO_REQUEST packets to network hosts
man netstat:
man route:
man traceroute:
man hosts:
man networks:
man host.conf:
man resolv.conf:
man interfaces:

___
## Some examples
Liste des interfaces réseau: `ifconfig -l`

Statut du réseau: `netstat`

Table de routage: `netstat -r`

Requêtes serveurs: `nslookup`

en0 : interface Ethernet

en1: carte Wi-Fi

## LINKS
- [101 commandes UNIX](https://buzut.net/101-commandes-indispensables-sous-linux/)
- [Installer Debian](https://cdiese.fr/installation-de-debian-sur-une-machine-virtuelle-virtualbox/)
- [Fonctionnement général d'un réseau](https://openclassrooms.com/fr/courses/1561696-les-reseaux-de-zero/1561759-les-reseaux-presentation-generale)
- [Fonctionnement des réseaux TCP-IP](https://openclassrooms.com/fr/courses/857447-apprenez-le-fonctionnement-des-reseaux-tcp-ip/855562-rendre-mes-applications-joignables-sur-le-reseau)
- [Init 42 project example](https://github.com/acuD1/init)
