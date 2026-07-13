entrepot-donnees-sql-projet

Mise en place d'un entrepôt de données (data warehouse) moderne avec SQL Server, couvrant les processus ELT, la modélisation des données et l'analyse décisionnelle.

🎯 Objectifs du projet

Partie 1 : Construction de l'entrepôt de données (Ingénierie des données)

But
Concevoir un entrepôt de données avec SQL Server permettant de centraliser les données de ventes provenant de plusieurs systèmes, afin de faciliter le reporting analytique et l'aide à la décision.

Détails du projet


Sources de données : récupération des données depuis deux systèmes sources (ERP et CRM), fournies sous forme de fichiers CSV.
Qualité des données : détection et correction des anomalies avant toute exploitation.
Intégration : fusion des deux sources dans un modèle de données unique, pensé pour faciliter les requêtes analytiques.
Périmètre : traitement des données les plus récentes uniquement (pas de gestion de l'historique dans cette version).
Documentation : rédaction d'une documentation claire du modèle de données, destinée aussi bien aux équipes métier qu'aux équipes analytiques.



Partie 2 : Analyse et reporting BI (Analyse de données)

But
Développer des requêtes SQL analytiques pour produire des indicateurs clés sur :


le comportement des clients
la performance des produits
les tendances de vente


Ces indicateurs doivent permettre aux parties prenantes de mieux comprendre l'activité et de prendre des décisions basées sur les données.


🛠️ Technologies utilisées


SQL Server
Fichiers CSV (sources ERP / CRM)


📌 Statut du projet

Projet réalisé dans un cadre d'apprentissage, en cours de développement.  
