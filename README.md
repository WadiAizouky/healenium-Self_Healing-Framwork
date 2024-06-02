# Selenium-Artificial-Intelligence

# Objectif : 
Faciliter la maintenance des tests automatisés lors qu'il y a des modification sur l'interface utilisateur, en intégrant le self-Healing dans un Framework d'automatisation de test (ex sélénium) qui démunie le temps passé sur la maintenance et sacrer du temps pour améliore ou ajouter des nouvelles fonctionnalités. 

## L'infrastructure : 
L'installation ici se fait avec Docker-compose contenant les services suivants:

* postgres-db (PostgreSQL base de données pour stocker les rapports/sélecteurs..)
* hlm-proxy (Proxy entre le client et le serveur sélénium)
* hlm-backend (CRUD services)
* selector imitator (Convertir healed locateur à convenient format)
* selenoid/selenium-grid (Selenium server)


<img width="877" alt="230408855-11aefcb9-6e46-4c3a-a3da-bdad66a52a9c" src="https://github.com/WadiAizouky/healenium-Self_Healing-Framwork/assets/105659142/95d5620d-d618-4926-8b5f-831418f314a4">

## Les outils et les framework supportés : 

Selenuim - RobotFramwork - Appuim - selenoide - WebDriver.IO - CucumberBDD - Serenity

## Exécution
docker-compose -f docker-compose-selenoid.yaml up -d
