<h1> Analyse de l'attrition des clients chez CapitalFlow - 2023 </h1>


<h2>Présentation du projet</h2>

Dans un contexte de forte concurrence sur le marché bancaire, la fidélisation des clients est un enjeu stratégique majeur. <b>CapitalFlow Bank</b>, établissement bancaire, observe une augmentation progressive du taux d’attrition de ses clients au cours des dernières années en France, en Espagne mais aussi en Allemagne.

À la demande conjointe des équipes <b>Marketing</b> et du <b>Head of Customer Relationship Management</b>, j'ai mené une analyse afin de mieux comprendre les facteurs qui influencent le départ des clients dans le but de mettre en place des actions ciblées limitant ce phénomène. L’objectif est d’identifier les variables clés liées à la perte de clients, à partir de données démographiques, financières et comportementales.



<h2>Contenu du projet</h2>

- [Customer_Churn_Records.csv](https://github.com/KatiaG-data/CapitalFlow-Project/blob/main/Customer-Churn-Records.csv) : Document comprenant les données brutes des clients
issu du site Kaagle [Capital Flow Data - Kaagle](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn)
- [Customer-Churn-Records-clean.xlsx](https://github.com/KatiaG-data/CapitalFlow-Project/blob/main/Customer-Churn-Records-clean.xlsx) : Données nettoyées et prêtes pour l'analyse
- [Dasboard CapitalFlow.pbix](https://github.com/KatiaG-data/CapitalFlow-Project/blob/main/Dashboard%20CapitalFlow.pbix) : Tableau de bord Power BI avec visualisations interactives


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



<h2> Outils utilisés</h2>

- **Power BI** pour la création de visualisations interactives.
- **Excel & Power Query** pour le nettoyage et la préparation des données.


<h2>Aperçu du dashboard interactif crée sur Power BI:</h2>

<img src="https://github.com/KatiaG-data/CapitalFlow-Project/blob/main/Screenshot%202025-03-19%20163720.png">


<h2> Résultats Clés</h2>


Cette analyse met en évidence plusieurs facteurs déterminants. Tout d’abord, <b>l’ancienneté et l’activité du client</b> jouent un rôle clé. Les clients ayant une faible ancienneté, soit moins de trois ans, affichent un taux d’attrition nettement plus élevé, suggérant une difficulté à les fidéliser à long terme. En outre, l’inactivité est un facteur critique : les clients peu actifs sont <b>2,5 fois plus susceptibles</b> de quitter la banque, indiquant un manque d’engagement vis-à-vis des services bancaires proposés.

Par ailleurs, <b>le score de crédit et le solde du compte</b> influencent fortement la rétention. Un <b>CreditScore inférieur à 600</b> augmente nettement la probabilité d’attrition, illustrant une potentielle corrélation entre le risque financier perçu et la fidélité des clients. Aussi, les clients ayant un <b>solde inférieur à la médiane</b> sont <b>40 % plus enclins</b> à fermer leur compte, soulignant l’importance des offres adaptées aux clients à faible revenu pour améliorer la rétention.

Le <b>nombre de produits bancaires souscrits</b> est également un indicateur clé. Les clients possédant un seul produit bancaire montrent un taux d’attrition davantage plus élevé que ceux qui en détiennent plusieurs, ce qui démontre l’impact de la diversification des services sur la fidélisation. À l’inverse, les clients ayant <b>plus de trois produits bancaires</b> restent en majorité fidèles, suggérant qu’une offre multi-services renforce l’attachement à la banque.

Enfin, le <b>profil démographique</b> influence également la perte de clients. Les jeunes adultes de <b>moins de 30 ans</b> présentent une plus grande volatilité, probablement en raison de leurs attentes évolutives et de leur propension à tester plusieurs services bancaires. Par ailleurs, une différence est observée entre les genres, <b>les femmes ayant un taux d’attrition légèrement plus élevé</b>, ce qui pourrait être lié à des différences de besoins ou de préférences en matière de services financiers. 


