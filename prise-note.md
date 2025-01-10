- **Petit screenshot** pour la liste des compétences

- **Expression des besoins du projet** : Petit dossier avec plusieurs documents (Contexte et enjeux, analyse des besoins, personnas)

- **Présentation de l'entreprise et du service** :
  - Présentation de l'entreprise Simplon et Simplon HDF
  - Présentation des équipes

- **Environnement humain** :
  - Les équipes avec leurs rôles et les autres teams
  - Deux niveaux :
    - Team bot (4 personnes)
    - Team projet (12 personnes)
  - Objectifs de qualité :
    - Comment allons-nous travailler ?
    - Méthodologie Agile
    - Organisation, planification, distribution des tâches
    - Qualité logicielle

- **Spécifications fonctionnelles** :
  - Pourquoi Discord ? Justification du choix de Discord et contraintes liées
  - Livrables attendus :
    - Une API fonctionnelle
    - Une base de données
    - Le listing des bots
    - La sécurisation
    - Le RBAC (Role-Based Access Control)

- **Architecture logicielle du projet** :
  - Couche N-tier : comment l'application est découpée
  - Diagrammes expliquant le fonctionnement et les connexions entre l'API, les bots, etc.
  - Structure du projet (tri)
  - Précisions sur les plugins utilisés
  - Outils (npm)
  - Middleware

- **Maquettes et enchaînement des maquettes** :
  - Maquettes du front (Figma, wireframes, etc.)

- **Modélisation des données** :
  - MCD (Modèle Conceptuel de Données)
  - MLD (Modèle Logique de Données)
  - MPD (Modèle Physique de Données)

- **Script SQL** :
  - Script pour la création de la base de données

- **Use Case**

- **Diagrammes de séquence** :
  - Les trois fonctionnalités les plus importantes du Use Case (3 diagrammes de séquence)

- **Spécifications techniques** :
  - Dictionnaire de données
  - Choix de la stack API (benchmark)
  - Choix de la stack front (benchmark)
  - Diagramme d'activité
  - Diagramme de classe
  - Stratégie de sécurisation de l'application
  - Conformité RGPD

- **Extraits de code de composants d'accès aux données** :
  - Modèles
  - Un contrôleur qui accède à une donnée
  - Une migration

- **Présentation d'éléments de sécurité de l'application** :
  - Sécurisation de la base de données
  - Interdiction des accès externes
  - Gestion des privilèges (pas de SuperUser)
  - Best practices de sécurisation pour PostgreSQL

- **Jeu d'essai** :
  - Démo de l'application :
    - Avant de lancer la démo, expliquer les objectifs
    - Expliquer l'agencement
    - Expliquer le résultat avec des screenshots

- **Veille technologique** :
  - Faire des recherches : comment créer un bot et éviter les problèmes de sécurité
  - Audit des vulnérabilités avec `pnpm audit` ou `npm audit`
  - Activer Dependabot sur GitHub
  - Consulter les issues ouvertes avec le label "security issues" sur DiscordJS

- **Annexes** :
  - Si une section devient trop volumineuse, déplacer son contenu détaillé dans les annexes
