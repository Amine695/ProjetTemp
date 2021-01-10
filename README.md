Étude de l'évolution de la température au niveau des couches supérieures du sol

Le projet github "ProjetTemp" regroupe plusieurs fichiers:

- "implementation_methode_explicite.ipynb" correspond au programme du schéma explicite : pour le tester il est nécessaire d'avoir accès à Jupyter Notebook, 
il suffit alors d'ouvrir le code sur le notebook puis d'exécuter toutes les cases (on peut utiliser pour cela la commande "Restart & Run All" qui se trouve dans l'onglet "Kernel"

- "RapportProjet" est le fichier correspondant à la version finale de notre rapport

- "Implémentation C-N.ipynb" correspond au programme du schéma de Crank-Nicolson. Celui-ci est un fichier Jupyter Notebook, il contient donc des commentaires d'explications pour chaque partie. Il faut tout de meme noter qu'il a besoin du dossier "Données" afin de fonctionner pour pouvoir importer les données. De plus, une cellule de code nécessite le codec ffmepg pour se lancer. 

- Le dossier "Données" comporte les températures avec lesquelles nous travaillons, sa présence dans le meme répertoire lors de l'excution des NoteBooks est obligatoire. 

- Les Notebooks Test_ana_alg et Test_ana_fr permettent de tester la résolution analytique de l'équation de la chaleur. 
