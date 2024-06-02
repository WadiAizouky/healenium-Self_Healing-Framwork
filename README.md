1	Selenium-Artificial-Intelligence
2	Objectif :
Faciliter la maintenance des tests automatisés lors qu'il y a des modification sur l'interface utilisateur, en intégrant le self-Healing dans un Framework d'automatisation de test (ex sélénium) qui démunie le temps passé sur la maintenance et sacrer du temps pour améliore ou ajouter des nouvelles fonctionnalités.
3	L'infrastructure :
L'installation ici se fait avec Docker-compose contenant les services suivants:
•	postgres-db (PostgreSQL base de données pour stocker les rapports/sélecteurs..)
•	hlm-proxy (Proxy entre le client et le serveur sélénium)
•	hlm-backend (CRUD services)
•	selector imitator (Convertir healed locateur à convenient format)
•	selenoid/selenium-grid (Selenium server)
4	Les outils et les framework supportés :
Selenuim - RobotFramwork - Appuim - selenoide - WebDriver.IO - CucumberBDD - Serenity
