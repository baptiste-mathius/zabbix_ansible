# README

## Playbook Ansible pour le deployer Zabbix 

- Sur les containers : 
    - s'assurer des mises a jour. 
    - créer un répertoire pour le playbook et le fichier hosts. 
    - installer ansible, git et sudo. 
    - avant la création de la clé ssh, aller dans le fichier de conf sshd et mettre le PermitRootLogin Yes et enelever le #.
    - Si besoin doc ansible : https://baptiste-mathius.github.io/img/BTS2/Documentation%20Ansible.pdf 
- git clone a faire sur le container Ansible. 

## Monitoring avec Zabbix

- Login / MDP : Admin / Zabbix
- Vérifier les agents SNMP sur les machines a monitorer et les installer si besoin. 
