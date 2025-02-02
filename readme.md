# 📊 Analyse des Ventes avec Talend et Data Warehouse

## 📝 Description
Ce projet a pour objectif de mettre en place un **entrepôt de données** pour analyser les ventes d’une entreprise en utilisant **Talend**. Il repose sur l’extraction, la transformation et le chargement (ETL) des données issues d’une base de données Access vers un schéma multidimensionnel (R-OLAP).

## 🏗️ Structure du Projet
Le projet est divisé en plusieurs étapes :

1. **Conception et Implémentation de la Base de Données "Comptoir"**
   - Création du schéma de la base de données.
   - Chargement des données à l’aide du script `comptoir_data.sql` (si nécessaire).
   - Connexion et importation du schéma dans Talend.

2. **Construction de l’Entrepôt de Données**
   - Conception du **schéma multidimensionnel** pour l’analyse des ventes (schéma en étoile).
   - Création des **tables de dimensions** (Client, Produit, Temps).
   - Création de la **table de faits** `Vente_F`.

3. **Intégration des Données avec Talend**
   - Définition des mappings ETL dans **Talend Open Studio**.
   - Extraction et transformation des données sources.
   - Chargement des données vers l’entrepôt.

4. **Analyse des Ventes**
   - Mise en place d’une **analyse journalière, mensuelle et annuelle**.
   - Création d’un entrepôt complémentaire avec un **grain mensuel**.
   - Réalisation de tableaux de bord avec **BIRT**.

## 🛠️ Outils Utilisés
- **Talend Open Studio** : Intégration ETL des données.
- **MySQL / Access** : Base de données source.
- **BIRT (Business Intelligence Reporting Tool)** : Tableaux de bord et reporting.
- **SQL** : Requêtes pour transformation et chargement.

## 📌 Installation et Exécution
1. Cloner le projet :
   ```bash
   git clone https://github.com/votre-repo/talend-data-warehouse.git
   cd talend-data-warehouse
