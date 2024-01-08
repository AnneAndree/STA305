Voici les fichiers que nous avons utilisés pour réaliser le projet de l'UE STA305 portant sur les modèles bayésiens dans l’analyse du rôle des vibrations dans la perception de la vitesse tactile. L'article sur lequel s'est basé notre projet est nommé 3_Mezzetti2023_data.pdf.

Le fichier R appelé Analyse_Data_Set_1 est le script issu des auteurs auquel nous avons ajouté quelques modifications. Nous avons rajouté une évaluation de la convergence du modèle situé à la fin du script.
Nous pouvons obtenir avec celui-ci les graphiques présents dans le rapport de notre projet.

Le fichier modello_pse_init est le fichier Rjags permettant de réaliser l'étude de l'article.
Les fichiers appelés modello_pse_dunif et modello_pse_gamma2 sont les fichiers Rjags qui nous ont permis de réaliser l'étude de sensibilité.
Pour utiliser ces fichiers, il suffit de remplacer à la ligne 67 du script R par le nom du fichier Rjags voulu.
modello_pse_dunif remplace la loi gamma en un loi uniforme.
modello_pse_gamma2 est une modification d'un paramètre d'une loi gamma de 0,001 à 0,1.

