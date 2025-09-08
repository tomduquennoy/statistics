# statistics

L'objectif de ce cours est de présenter/rappeler les bases de statistiques et de probabilités nécessaires au traitement et l'analyse de données. Dans l'ensemble les thématiques abordée seront :
1) Rappels de statistiques descripte et de représentation graphique. 
2) Principaux résultats probabilites utile pour l'estimation.
3) Tests statistiques : méthodes et tests classiques.
4) Modélisation aléatoire.
5) Regression linéaire et validation de modèle.
6) Analyse en composantes principales et application à la réduction de dimension.
7) Introduction au clustering.

Pour les séances 1, 2, 3, 6 et 7 le format seras du cours/TP intégré. Venez avec vos machine. Sur ce point, ce sera l'occasion de découvrir le fabuleux logiciel de statistique R ! Il est alors préférable de l'installer à l'avance. Les BE seront dans au format notebook, vous devrez donc avoir le noyau R. Pur la démarche : (Il faut bien entendu avoir Jupyter en amont de la seconde étape mais je pense que c'est déjà le cas pour tout le monde).
Installer R : https://www.r-project.org/ la version importe peu.
Installer le noyau IRkernel : https://cran.r-project.org/web/packages/IRkernel/readme/README.html

En bonus si vous voulez utilisez R dans un autre conseil je vous conseil l'environement de développement Rstudio : https://posit.co/download/rstudio-desktop/ Il ne seras pas utile pour ce cours mais peut être à l'avenir. 

Pour l'évaluation des partie  1, 2, 3, 6 et 7 : C'est un projet, à rendre par groupe de 5, pour le 01/10/2025.
L'objectif est de mettre en oeuvre les méthodes vue dans le cours et les BE sur un jeux de données réelles.

Le prejet consite en l'étude du jeu de donnée météo : https://public.opendatasoft.com/api/explore/v2.1/catalog/datasets/donnees-synop-essentielles-omm/exports/csv?lang=fr&qv1=(date%3A%5B2015-08-03T22%3A00%3A00Z%20TO%202025-09-03T21%3A59%3A59Z%5D)&timezone=Europe%2FBerlin&use_labels=true&delimiter=%3B.

Pour récupérer le jeu de données, récupérer le fichier CSV (première ligne de la page)

Le document rendus, sous la forme d'un \textbf{notebook Jupyter}, devra contenir au moins :

1) Une présentation des données avec des résumées numériques et graphiques des données. (Plusieurs évidement)
2) Un calcul et étude d'estimateur.
3) Des tests (au moins un sur un parametres et une ANOVA).
4) Une regression et étude de corrélation.
5) Une ACP et une PLS.
6) Une méthode de clustering.

L'objectif étant, pour chaque méthode utilisée et illustrée, de répondre aux questions suivante :

1)Quelle question je me pose sur les données ? Qu'est ce que je veux illustrer ? 
2)Pourquoi la méthode que je vais utiliser est pertinente ? 
3)Quelles conclusions j'en retire ? 
4)Quelles sont les possible limitation de ce que je propose ? 
