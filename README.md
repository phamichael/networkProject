# networkProject

Incomplet: il manque les iptables -P INPUT/OUTPUT/FORWARD DROP pour le routeur front.
Si je les mets le dns plante..

Réseau privé: 192.168.110.0/24
Zone démilitarisée public: 192.167.17.128/26

Alice: 192.168.110.2

Serveurs:
Web: 192.167.17.131
Ssh: 192.167.17.132
Dns: 192.167.17.133

Routeurs: 
Back:  - eth0: 192.168.110.1
               - eth1: 192.167.17.129
Front: - eth0: 10.0.0.1
               - eth1: 192.167.17.130

