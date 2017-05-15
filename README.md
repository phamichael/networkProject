# networkProject

Problème non résolu: il manque les iptables -P INPUT/OUTPUT DROP sur le routeur front

Si je les mets le dns plante..

Réseau privé: 192.168.110.0/24

Zone démilitarisée public: 192.167.17.128/26

Alice: 192.168.110.2

Serveur web: 192.167.17.131

Serveur ssh: 192.167.17.132

Serveur dns: 192.167.17.133

Routeur Back:
- eth0: 192.168.110.1
- eth1: 192.167.17.129
               
Routeur Front:
- eth0: 10.0.0.1
- eth1: 192.167.17.130

Mot de passe pour la connexion ssh à alice: guest

Celui pour la connexion au serveur ssh: root
