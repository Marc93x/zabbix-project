# Projet Zabbix de Marc

## Objectif
- Mettre en place un environnement de monitoring complet avec Zabbix.

## Étapes réalisées
- Installation de Zabbix sur une VM avec PHP,Apache et une base de données mySQL. 
- Mise en place d'un agent Zabbix sur l'hôte en utilisant Docker.
- Création de la base de donnees pour zabbix. 
- Création de scripts Bash pour :
  - Automatiser la gestion des tâches avec Cron.
  - Gérer les IP dynamiques ppour les agents et le serveur 
- Configuration d'un proxy sur l'agent pour optimiser la transmission des données sur mon hôte. 

## Scripts inclus
- `scripts/update_ip.sh` : Met à jour l'adresse IP de la VM.
- `scripts/monitoring_check.sh` : Vérifie l'état du monitoring.

## Importance
- Montre les bonnes pratiques de configuration pour un environnement de monitoring.
- Souligne les bénéfices de l'automatisation dans un système complexe.

