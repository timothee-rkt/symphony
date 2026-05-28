Mediatek86 - Système de Gestion des Formations
📋 Description
Mediatek86 est une application web issue de l'évolution du site de la médiathèque du même nom, développée avec le framework Symfony
. Cette plateforme est spécifiquement conçue pour gérer et mettre à disposition des formations, tout en garantissant une maintenance rigoureuse grâce à l'intégration d'outils de qualité de code et de tests automatisés


Objectifs : 
Faire évoluer le site existant pour intégrer la gestion des formations.
Garantir une haute qualité logicielle via des analyses statiques (Sonar)

Sécuriser l'accès aux fonctionnalités d'administration.
Assurer la non-régression du système par une couverture de tests complète


✨ Fonctionnalités principales
🔐 Authentification et Sécurité
Système de connexion sécurisé pour les administrateurs.
Gestion des accès et protection des routes d'édition.
Intégration des composants de sécurité de Symfony


📚 Gestion de la Médiathèque
Catalogue des formations : Consultation et recherche des formations disponibles.
Gestion des contenus : Ajout, modification et suppression des entrées en base de données
.
Mise à disposition : Interface utilisateur dédiée à l'accès aux ressources pédagogiques.
🧪 Qualité et Tests
Tests Unitaires : Validation de la logique métier avec PHPUnit


Tests Fonctionnels : Vérification des parcours utilisateurs complets


Analyse de code : Suivi de la dette technique et de la qualité via Sonar

🚀 CI/CD et Déploiement
Automatisation des workflows via GitHub Actions


Gestion des versions de la base de données par Migrations


Configuration d'environnements de test dédiés (.env.test)


🛠️ Stack technique
Backend (Serveur & Logique)
Framework : Symfony

Langage : PHP (71%)


Base de données : MySQL / MariaDB (gérée via Doctrine Migrations)

Gestionnaire de dépendances : Composer

Tests : PHPUnit


Frontend (Interface)
Moteur de template : Twig (


Langages : JavaScript &  CSS 


Asset Management : Symfony Importmap


Qualité & DevOps
Analyse Statique : SonarQube / SonarCloud


Automation : GitHub Actions


Internationalisation : Symfony Translation

