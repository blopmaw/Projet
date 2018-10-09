Projet Node : Paul CRABOT, Livia FABY, Quentin RATEL, Kevin SCHOUBERT
M2 2019
Réflexion et synopsis projet

Synthèse du sujet :
Le but de notre projet est de pouvoir choisir une ville de France et choisir une date dans le futur pour connaître la probabilité d’avoir beau temps ce jour dans cette ville. Pour avoir cette probabilité, nous nous baserons sur les différentes météos des années précédentes.

Analyse :
Le but principal de ce projet est de permettre à des utilisateurs de savoir s’ils peuvent partir en vacances pendant une période qu’ils auront choisi. Grâce à ce projet, ils pourront déterminer de manière simple les périodes où la météo sera la meilleure. Le problème principal qui émerge de ce but, est qu’il faut pouvoir récupérer les bases de données qui référencient toutes les météos des 10 années précédentes.
Les sous-problèmes de notre projet sont que, si un utilisateur sélectionne une ville, il faut que :
-	La météo affichée corresponde bien à la ville demandée,
-	La moyenne des météos des années précédentes soit bien effectuée,
-	 Le jour corresponde bien à ce que l’utilisateur demande.
 

Conception :

Pour pouvoir réaliser à bien ce projet, nous devons tout d’abord récupérer toutes les informations relatives aux météos des 10 dernières années sur le site https://www.worldweatheronline.com/. Grâce à cette base de donner, nous pourrons mettre en relation la météo d’une ville à même date durant toutes ces années, pour ensuite pouvoir faire la moyenne des températures, calculer la vitesse moyenne du vent, calculer la probabilité qu’il pleuve, qu’il fasse soleil, etc…
Pour faciliter l’utilisation de notre application, il faudra un design du site très clair pour que l’utilisateur puisse choisir la ville et la date de son choix très facilement. Il faut que le site internet soit accessible par un maximum de personnes.
Un exemple d’utilisation serait le suivant :
-	Un utilisateur entre sur le site,
-	Il choisit la région où se trouve la ville désirée puis il choisit la ville où il veut se rendre ou il entre directement le noms de la ville dans la barre de recherche du site,
-	Il choisit la date à laquelle il veut se rendre dans cette ville,
-	Toutes les informations concernant la météo (température, précipitation, vent, etc…) à cette date pour cette ville s’afficheront.
Utiliser NodeJS pour réaliser notre projet est une bonne solution puisque notre application sera disponible sur un site web et nous savons que NodeJS est une technologie très performante pour le Web. Ce qui permettra de gagner du temps sur la réalisation et donc de l’argent.
 

Feuille de route du projet :

09/10 : Début projet
09/10 – 16/10 : Récupérer et pouvoir accéder aux météos d’île de France des années précédentes -> Paul et Livia
Pouvoir accéder aux différentes villes d’île de France -> Kevin et Quentin
16/10 -23/10 : Savoir la probabilité de chance qu’il fasse beau ou non à une date donnée -> Paul et Livia
Un début de design pour le site -> Kevin et Quentin
23/10 – 30/10 : Approximer le maximum d’informations possibles sur le temps (température, force du vent, pourcentage de précipitation, etc…) -> Paul et Livia
Site clair et accessible -> Kevin et Quentin
30/10 – 6/11 : Etendre toutes les informations sur la météo à la France entière -> Paul et Livia
Site fini -> Kevin et Quentin
6/11 – 12/11 : Améliorer le design du site et les approximations faites -> Paul et Livia
Ajouter d’autres capitales d’Europe -> Kevin et Quentin
12/11 : Rendu projet.

Une réunion sera effectuée chaque début de semaine pour savoir les tâches qui ont été réalisées ainsi que celles qui restent à faire dans le but de réajuster le calendrier des actions à mener. 


Objectifs du prototype initial :

Pour commencer, nous ne voulons pas avoir la météo de toutes les villes de France, mais juste d’une seule région, comme l’île de France par exemple. Nous nous étendrons sur toute la France par la suite, et même toute l’Europe.
Les objectifs principaux que nous voulons mettre en œuvre le plus rapidement possible sont :
-	Que l’utilisateur puisse choisir le nom d’une ville d’île de France et la date laquelle il veut partir,
-	Savoir s’il y a plus de chance qu’il pleuve ou qu’il fasse beau,
-	Le design du site n’est pas une priorité pour le prototype initial.
Pour utiliser ce prototype, l’utilisateur devra se connecter au site pour pouvoir accéder à une liste afin de sélectionner la ville d’île de France dont il souhaite connaître la météo. Il pourra ensuite choisir la date qu’il souhaite sur un calendrier.
