<h1> Analyse de l'attrition des clients chez CapitalFlow </h1>


<h2>Présentation du projet</h2>

Ce projet vise à analyser l'attrition des clients de la banque CapitalFlow afin d'identifier les facteurs influençant le départ des clients et proposer des actions pour améliorer la fidélisation. L'analyse repose sur des données clients comprenant des informations démographiques, financières et comportementales. Un dashboard interactif Power BI est également disponible pour visualiser les insights clés.



<h2>Présentation du projet</h2>

- [Customer_Churn_Records.csv](https://github.com/KatiaG-data/CapitalFlow-Project/blob/main/Customer-Churn-Records.csv) : Document comprenant les données brutes des clients
issu du site Kaagle [Capital Flow Data - Kaagle](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn)
- [Customer-Churn-Records-clean.xlsx](https://github.com/KatiaG-data/CapitalFlow-Project/blob/main/Customer-Churn-Records-clean.xlsx) : Données nettoyées et prêtes pour l'analyse
- [Dasboard CapitalFlow.pbix](https://github.com/KatiaG-data/CapitalFlow-Project/blob/main/Dashboard%20CapitalFlow.pbix) : Tableau de bord Power BI avec visualisations interactives



<h2> Outils utilisés</h2>

- **Power BI** pour la création de visualisations interactives.
- **Excel** pour le nettoyage et la préparation des données.

<h2> Structure des Données</h2>

Les principales variables utilisées sont :

- CustomerID : Identifiant unique du client
- Age : Âge du client
- Gender : Sexe du client
- AccountBalance : Solde du compte
- CreditScore : Score de crédit
- Tenure : Ancienneté du client en années
- NumOfProducts : Nombre de produits souscrits
- HasCreditCard : Possession d'une carte de crédit (1 = Oui, 0 = Non)
- IsActiveMember : Activité du client (1 = Actif, 0 = Inactif)
- Exited : Variable cible (1 = Client parti, 0 = Client resté)

<h2> Résultats Clés</h2>

Le churn est fortement corrélé avec l'ancienneté, le solde du compte et l'activité du client.
Les clients avec un faible CreditScore et peu de produits bancaires sont plus susceptibles de partir.
Une segmentation client a permis d’identifier des groupes à risque sur lesquels CapitalFlow peut agir.



