
# Projet de Planning pour Tous les Niveaux de Classe

Description:


Ce projet a pour objectif de créer un système de gestion de plannings pour les écoles, permettant d'organiser les emplois du temps des étudiants, des professeurs, et des salles. Le système offre des fonctionnalités pour la génération automatique d'emplois du temps, la gestion des créneaux, et les modifications en temps réel.




## Fonctionnalités principales

Gestion des données :
Enregistrement des informations des étudiants, professeurs, et salles.

Création des plannings : Génération automatique des emplois du temps pour les différentes classes, options, et niveaux.

Modification et gestion : Gestion des changements de créneaux horaires et des salles.

Export des données : Export des emplois du temps en format .ical pour une intégration dans des outils externes (Google Calendar, etc.).
## Technologies utilisées

Backend : Python, Django REST Framework

Frontend : JavaScript (React), Redux

Base de données : MySQL (en production), SQLite (pour le développement)

Notifications et authentification (optionnel) : Firebase

Autres outils : JSON pour les configurations et sauvegardes temporaires
## Installation

Backend :

·Installer Python 3.x

·Cloner le dépôt et naviguer vers le répertoire du projet

·Installer les dépendances via pip install -r requirements.txt

·Configurer la base de données MySQL et lancer les migrations avec python manage.py migrate

·Démarrer le serveur avec python manage.py runserver

Frontend :

·Installer Node.js et npm

·Installer les dépendances avec npm install

·Lancer l'application frontend avec npm start
## Structure du projet

Backend (Django) :

API pour gérer les classes, les professeurs, les créneaux, et les emplois du temps.

Modèles définissant les relations entre les entités (étudiants, salles, etc.).

Frontend (React) :
Interface utilisateur pour l'administration et la gestion des plannings.

Intégration avec l'API pour la récupération et la gestion des données.
## Organisation du développement

Préparation de la base de données : 

Responsable – My Anh / Samuel

Développement du backend : Responsable – Sully

Développement du frontend : Responsable – Zihao

Création de l'interface graphique   : Responsable– Clémence

Tests et intégration : Responsable – Thi My Anh
## Tests

Backend : Utilisation de Pytest pour les tests unitaires.

Frontend : Utilisation de Jest pour les tests des composants React.
## Améliorations futures

Ajouter un système de notifications en temps réel pour informer les professeurs et les étudiants des modifications d’emploi du temps.

Filtrer les emplois du temps par niveau, matière ou salle.
## Contribution

Les contributions sont les bienvenues. Veuillez suivre le workflow GitHub et créer une branche pour chaque fonctionnalité ou correctif avant de soumettre une demande de tirage (pull request).
## License

Ce projet est sous licence MIT License.
