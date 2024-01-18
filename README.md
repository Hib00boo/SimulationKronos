# Simulation de vol de Kronos
Ce projet est une simulation de vol de la fusée à moteur hybride Kronos. La simulation a été conçue à partir des données obtenues lors de la fabrication des composantes et des données d'une ancienne itération de la fusée. Afin de faciliter la lecture du code et la compréhension des modèles, Jupyter Notebook a été utilisé. Ainsi, les graphes s'affichent directement dans l'environnement de développement.

La simulation du vol de Kronos se retrouve dans le fichier [SimulationKronosV2.ipynb](SimulationKronosV2.ipynb). Elle contient une liste de tous les données nécessaires, des graphiques qui illustrent des simulations et une illustration de la fusée. Tous les données qui portent sur la masse ou la longueur des composantes sont tirés du fichier excel [Bilan_masses_2023.xlsx](Bilan_masses_2023.xlsx). Il manque toujours des données sur le moteur puisque le fichier [HYB30kpar.eng](HYB30kpar.eng) ne détient pas toutes les informations nécessaires pour la simulation. Aussi, certaines données ne sont toujours pas à jour.
## Simulation du vol
Objectifs :
* Faire le plot des différents simulations du vol de la fusée Kronos sur RocketPy
* Comparer les données calculées sur RocketPy aux données fournies sur RasAero II
* Tout documenter
* Centraliser les données
## Données à ajouter
Pour savoir quelles données sont à ajouter, il faut se référer au fichier [SimulationKronosV2.ipynb](SimulationKronosV2.ipynb), dans les sections de chargement de fichiers. Tous les données ayant 0 comme valeur sont à mettre à jour avec les données courantes.
Les données à ajouter au moment d'écriture du README (15-01-2024) sont :
* Inertie de la masse solide du moteur (liste en kg*m^2)
* Centre de masse de la masse solide du moteur (m)
* Rayon du throat de l'injecteur (m)
* Densité du grain (kg/m^3)
* Hauteur initiale du grain (m)
* Centre de masse du grain (m)
* Date du launch
* Longitude et latitude du spaceport (m)
* Centre de masse de la fusée (m)
* Ratio entre rayons du tip du nose cone
* Position des ailettes (m)
* Position du boattail (m)
* Coefficient drag des parachutes
* Hauteur d'éjection des parachutes (m)
* Temps entre trigger éjection et éjection réelle (s)
* Position des boutons du rail (m)
* Position angulaire des boutons du rail (degrés)
* Longueur de la surface attachée à la fusée du rail
