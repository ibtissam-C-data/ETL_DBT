# Se familiariser avec ETL_DBT

## Contexte :
Il s'agit d'une suite d'activités qui ont permis de découvrir DBT (Data Build Tool), lequel servira pour la partie transformation d'un ELT. Ces activités constituent une initiation à l'utilisation de DBT et au fonctionnement autour de cet outil.


## Qu'est-ce que DBT ?
Le **DBT (Data Build Tool)** est un outil **open-source** utilisé principalement pour transformer des données dans un pipeline de données. Il est conçu pour simplifier et automatiser les processus de transformation des données dans un entrepôt de données (data warehouse), en utilisant le langage SQL.


## Objectifs principaux :
- **Modularité et réutilisabilité** : Permet de créer des transformations SQL modulaires et réutilisables sous forme de modèles.
- **Versionning et tests** : DBT permet de versionner les modèles SQL, d'exécuter des tests de données et de valider les résultats.
- **Documenter et versionner** : Facilite la documentation des transformations de données et des relations entre les différentes tables de manière transparente.
- **Automatisation et orchestration** : Exécute automatiquement les transformations sur les données, en enchaînant les différentes étapes du pipeline.


## Fonctionnalités clés :
- **Modèles SQL** : Les utilisateurs écrivent des transformations de données sous forme de modèles SQL. Ces modèles peuvent être organisés dans des fichiers et exécutés dans un ordre défini.
- **Tests et validations** : DBT permet d’ajouter des tests de qualité des données (par exemple, vérifier l'unicité d'une colonne) pour s'assurer que les transformations sont conformes aux attentes. qui dit test unitaire dit bien évidement coût faible de traitement postérieur.
- **Documentation automatique** : Génère automatiquement une documentation détaillée sur les modèles de données et leurs dépendances.
- **Exécution en pipeline** : DBT peut être intégré avec des outils comme Airflow, pour orchestrer des pipelines complexes de transformation de données.

## Exemple d'utilisation :
Dans un projet DBT typique, on commence par créer un modèle SQL qui définit une transformation spécifique. Ensuite, on exécute ce modèle à travers DBT, ce qui générera une table ou une vue dans l'entrepôt de données cible.

## Avantages :
- **Centralisation des transformations** : DBT centralise toutes les transformations SQL, ce qui facilite la gestion des données.
- **Collaboration améliorée** : Le travail sur des modèles SQL versionnés et l'intégration avec des outils de gestion de version (comme Git) favorisent la collaboration en équipe.
- **Support d'une approche "data ops"** : Permet de mettre en place une approche structurée et itérative pour la gestion des données.

## Intégration avec les entrepôts de données :
DBT est compatible avec de nombreux entrepôts de données modernes, tels que :
- **BigQuery**
- **Redshift**
- **PostgreSQL**

## Conclusion
DBT est devenu un incontournable pour les ingénieurs de données et les analystes, car il simplifie et organise le travail de transformation des données dans les pipelines modernes tout en assurant une meilleure gestion de la qualité des données.

