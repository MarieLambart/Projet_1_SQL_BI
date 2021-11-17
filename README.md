## Projet_1_SQL_BI

# Présentation

Vous êtes mandaté par une entreprise de vente de maquettes et modèles réduits. L'entreprise dispose déjà d'une base de données qui répertorie les employés, les produits, les commandes et bien plus encore. Vous êtes invités à parcourir et découvrir cette base de données. Le dirigeant de l'entreprise souhaite disposer d'un tableau de bord qu'il pourrait rafraîchir chaque matin pour avoir les dernières informations afin de gérer l'entreprise.

# Objectif

Votre tableau de bord doit s'articuler autour de ces 4 thèmes principaux : les ventes, la finance, la logistique et les ressources humaines.
Voici les indicateurs qui devraient être présents dans votre tableau de bord. Des visualisations seraient également appréciées. Et vous êtes invité à exercer votre rôle de conseil, par proposer des KPI et des graphiques supplémentaires.
Ventes: Le nombre de produits vendus par catégorie et par mois, avec comparaison et taux d'évolution par rapport au même mois de l'année précédente.
Finances: 
Le chiffre d'affaires des commandes des deux derniers mois par pays. 
Les commandes qui n'ont pas encore été payées.
Logistique: Le stock des 5 produits les plus commandés.
Ressources Humaines: Chaque mois, les 2 vendeurs avec le chiffre d'affaires le plus élevé.

# Ressources

Voici le schéma de la base de données :

![alt tag](https://user-images.githubusercontent.com/90702580/142235696-7bf21a69-cfd3-4dc2-ae4a-981e997931d1.png)

# Outil

Le gestionnaire ne veut pas faire de SQL, il veut pouvoir accéder aux données automatiquement et graphiquement. Vous pouvez donc proposer un outil de votre choix, à condition que le tableau de bord soit pertinent.

Pour information, la base de données est disponible sur un serveur d'entreprise. Vous pouvez y accéder en mode lecture seule avec un utilisateur fourni ci-dessous.
La société vous fournit également le script que vous pouvez exécuter sur votre serveur MySQL local. Les données sont identiques, et il s'arrête à la fin du mois précédent.
Le matin de la démo, les données seront actualisées avec des données nouvelles et fraîches (et vous pourrez recevoir le script de mise à jour si vous le faites localement). La démo devrait donc afficher les dernières données disponibles.

# Outil de reporting

Vous pouvez utiliser l'outil de votre choix. Pour information, la société utilisait auparavant la feuille de calcul LibreOffice Calc, donc si vous souhaitez l'utiliser, vous pouvez voir le PrintScreen pour le connecter. Pour être plus collaboratif, nous avons quelques printscreens sur la connexion de Google Data Studio au serveur cloud. Et bien sûr, vous pouvez utiliser de superbes outils de Business Intelligence de reporting comme Tableau Software. A vous de présenter le meilleur tableau de bord possible sur l'outil de votre choix.
Attention : vous avez choisi votre propre outil de reporting. Mais le but est de pratiquer SQL. Vous devez donc obtenir les données dans les requêtes SQL. Par exemple, pour les "2 vendeurs avec le chiffre d'affaires le plus élevé pour chaque mois" : 
ce que nous voudrions : une requête SQL avec uniquement les "2 vendeurs avec le chiffre d'affaires le plus élevé pour chaque mois", et une dataviz pour montrer cela.
ce qu'on ne veut pas : une requête SQL avec chaque vendeur, puis des filtres dans votre outil de reporting.
