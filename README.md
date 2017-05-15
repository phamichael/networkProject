# networkProject

Incomplet: il manque les iptables -P INPUT/OUTPUT/FORWARD DROP pour le routeur front.
Si je les mets le dns plante..

Adresse du réseau privé: 192.168.110.0/24
        de la zone démilitarisée public: 192.167.17.128/26

Alice: 192.168.110.2
Serveur web: 192.167.17.131
        ssh: 192.167.17.132
        dns: 192.167.17.133
Routeur back:  - eth0: 192.168.110.1
               - eth1: 192.167.17.129
        front: - eth0: 10.0.0.1
               - eth1: 192.167.17.130

