# Analyse des performances commerciales d’AdventureWorks avec Power BI



**Projet personnel — Business Intelligence, Power BI et analyse de données**



## Contexte et problématique



L’analyse des données commerciales permet aux entreprises de mieux comprendre leur activité et d’identifier les facteurs qui influencent leur rentabilité. Ce projet porte sur AdventureWorks Cycles, une entreprise fictive spécialisée dans la vente de vélos, de vêtements et d’accessoires cyclistes, à travers deux canaux de distribution : Internet et les revendeurs.



L’objectif est de transformer un fichier Excel contenant plus de 121 000 lignes de ventes, réparties sur sept tables, en un tableau de bord interactif permettant d’analyser le chiffre d’affaires, les marges, les performances des produits et des revendeurs ainsi que l’évolution des ventes dans le temps.



## Démarche méthodologique



### 1. Exploration et préparation des données



- Importation et exploration des sept tables du fichier Excel.

- Vérification des types de données, des valeurs manquantes et de la cohérence des informations.

- Nettoyage et transformation des données avec Power Query.

- Fusion de tables pour récupérer les informations relatives aux canaux de vente.

- Création de variables facilitant la distinction entre les ventes Internet et les ventes via revendeurs.



### 2. Modélisation des données



- Construction d’un modèle en étoile autour de la table de faits `Sales_data`.

- Mise en relation des dimensions produits, clients, revendeurs, territoires et dates.

- Configuration des relations entre les tables et gestion des différentes dates associées aux ventes.

- Mise en place d’une table de dates pour les analyses temporelles.



### 3. Création des indicateurs avec DAX



Développement de mesures DAX pour répondre aux principales questions commerciales :



- Calcul du chiffre d’affaires, des coûts, de la marge et du taux de marge.

- Comparaison de la rentabilité entre les canaux Internet et Revendeur.

- Analyse de l’évolution des ventes par rapport aux périodes précédentes.

- Classement des principaux revendeurs selon leur chiffre d’affaires.

- Estimation des remises effectives et analyse de leur évolution selon les quantités commandées.



### 4. Conception et analyse des tableaux de bord



Réalisation d’un rapport Power BI composé de cinq pages complémentaires :



- Vue d’ensemble des indicateurs commerciaux.

- Analyse des performances par produit et catégorie.

- Analyse des clients et des revendeurs.

- Suivi de l’évolution temporelle des ventes.

- Exploration détaillée des performances d’un produit.



Intégration de filtres interactifs, d’une navigation entre les pages, d’info-bulles personnalisées et d’une fonctionnalité de *drill-through* pour approfondir les analyses.



## Principaux résultats



L’analyse met en évidence un chiffre d’affaires global de **109,81 M€**, une marge de **12,55 M€** et un taux de marge de **11,43 %**.



Les revendeurs représentent environ **73 % du chiffre d’affaires**, mais affichent un taux de marge nettement inférieur à celui des ventes Internet. L’étude des remises effectives révèle également des écarts tarifaires plus importants sur certaines commandes de gros volumes.



## Environnement technique



**Power BI Desktop** · **Power Query** · **DAX** · **Excel**



## Compétences acquises



- **Préparation des données :** nettoyage, transformation et fusion de requêtes.

- **Modélisation décisionnelle :** schéma en étoile et gestion des relations.

- **DAX et analyse temporelle :** mesures, KPI et Time Intelligence.

- **Data Visualisation :** tableaux de bord interactifs et drill-through.

- **Analyse métier :** suivi des ventes, des marges et de la rentabilité.

- **Data Storytelling :** interprétation et restitution des résultats.



## Apports du projet



Réalisé dans le cadre de mon apprentissage autodidacte de Power BI, ce projet m’a permis de mettre en pratique les différentes étapes d’un processus de Business Intelligence, depuis la préparation des données jusqu’à leur restitution dans un rapport interactif.



Il m’a également appris à structurer une analyse autour de questions métier, à vérifier la fiabilité des indicateurs et à présenter des résultats compréhensibles pour faciliter la prise de décision.

