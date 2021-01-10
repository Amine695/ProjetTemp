Étude de l'évolution de la température au niveau des couches supérieures du sol

Notre groupe a été chargé de la modélisation de la température au niveau des couches supérieures du sol en fonction du temps et de la région étudiée.
Nous avons donc dans un premier temps résolu l'équation de la chaleur à 1D analytiquement, puis numériquement à l'aide de deux méthodes : le schéma explicite et celui de Crank-Nicholson.

Le projet github "ProjetTemp" regroupe plusieurs fichiers:

- "implementation_methode_analytique" correspond à une implémentation de la résolution analytique. 

- "implementation_methode_cn" correspond au programme du schéma de Crank-Nicolson. Celui-ci est un fichier Jupyter Notebook, il contient donc des commentaires d'explications pour chaque partie. Il faut tout de même noter que celui-ci a besoin du dossier "Données" afin de fonctionner pour pouvoir importer les données. De plus, une cellule de code nécessite le codec ffmepg pour se lancer. Ce Notebook contient aussi une implementation de la résolution analytique afin de pouvoir faire une comparaison et plusieurs moyens d'afficher les résultats : graphes, heatmap, vidéo.

- "implementation_methode_explicite.ipynb" correspond au programme du schéma explicite : pour le tester il est nécessaire d'avoir accès à Jupyter Notebook, 
il suffit alors d'ouvrir le code sur Jupyter puis d'exécuter toutes les cases (on peut utiliser pour cela la commande "Restart & Run All" qui se trouve dans l'onglet "Kernel"). Par ailleurs, il est nécessaire

- Le dossier "Donnees" regroupe les fichiers répertoriant les différentes températures à la surface du sol en fonction de la localisation (France ou Algérie) et du cycle étudié (heure,mois,année). Ce dossier doit être présent dans le même répertoire que les fichiers des programmes (excepté pour - "implementation_methode_analytique"). 

- "RapportProjet" est le fichier correspondant à la version finale de notre rapport.
