Étude de l'évolution de la température au niveau des couches supérieures du sol

Notre groupe a été chargé de la modélisation de la température au niveau des couches supérieures du sol en fonction du temps et de la région étudiée.
Nous avons donc dans un premier temps résolu l'équation de la chaleur à 1D analytiquement, puis numériquement à l'aide de deux méthodes : le schéma explicite et celui de Crank-Nicholson.

Le projet github "ProjetTemp" regroupe plusieurs fichiers:

- Le dossier "Donnees" regroupe les fichiers répertoriant les différentes températures à la surface du sol en fonction de la localisation (France ou Algérie) et du cycle étudié (heure,mois,année). Par ailleurs, ce dossier doit être enregistré dans le même répertoire que les fichiers des programmes (excepté pour - "implementation_methode_analytique"), si vous souhaitez évidemment exécuter ces derniers.

- "RapportProjet" est le fichier correspondant à la version finale de notre rapport.

- "implementation_methode_analytique.ipynb" correspond à une implémentation numérique de la résolution analytique. 

- "implementation_methode_cn.ipynb" correspond au programme du schéma de Crank-Nicolson. Il s'agit d'un fichier de type Jupyter Notebook, il contient des commentaires d'explications pour chaque partie. Il est tout de même à noter que celui-ci a besoin du dossier "Donnees" pour fonctionner afin de pouvoir importer les données sans erreurs. De plus, une cellule de code nécessite le codec "ffmepg" pour se lancer. En outre, ce Notebook contient également une implémentation de la résolution analytique afin de comparer non seulement les différentes méthodes, mais aussi d'afficher les résultats sous diverses formes : graphes, heatmap, vidéo.

- "implementation_methode_explicite.ipynb" correspond au programme du schéma explicite : pour le tester il est nécessaire d'avoir accès à Jupyter Notebook, 
il suffit alors d'ouvrir le code sur Jupyter puis d'exécuter toutes les cases (on peut utiliser pour cela la commande "Restart & Run All" qui se trouve dans l'onglet "Kernel"). Les résultats seront présentés sous deux formes: gif et graphique statique en 2D. Il est à noter que des gifs peuvent être téléchargés dans le même répertoire où se situe le programme lorsque vous exécuterez ce dernier.

Les résultats sous forme de GIFs de ce projet sont disponibles à l'adresse suivante : 
https://drive.google.com/drive/folders/1eJTlo4ErnwQQfzG-EfC-OiVsIi6m9TVW

Ici, vous trouverez les résultats de notre projet que nous avons décidé de ne pas inclure. Ils sont intéressants dans la mesure où il est possible de visualiser de manière dynamique l’évolution de la température au sein des couches supérieures du sol.


N'oubliez pas : la plupart des programmes ont besoin du dossier "Donnees" pour fonctionner correctement.
Pensez donc bien à enregistrer dans un même répertoire le dossier "Donnes" ainsi que les fichiers des programmes que vous souhaitez tester.
Il est important de ne pas modifier le nom du dossier "Donnees".
