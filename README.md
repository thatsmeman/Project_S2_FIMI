division du programme en fonctions:

Partie Backend :

définir les règles de mouvement selon la classe (pion blanc, pion noir, dame blanche, dame noire).

Conditions :
Ne peut aller que vers l’avant (l’avant change selon le joueur)
Ne peut pas avancer s' il y a un pion sur la case (mais peut le capturer)
Ne peut avancer que sur la diagonale
si un pion de l’autre couleur est sur le chemin, appeler la fonction : règles de capture

entrée :   Ligne, Colonne, matrice
sortie :  déplacement_possible=True/False, capture=True/False
3H

définir les règles de capture (en fonction du pion sélectionné, de la case sélectionnée et des autre pions (matrice)
entrée : matrice, ligne, colonne
sortie : True/False
1H

Vérifier si un joueur gagne
entrée :  matrice
sortie :      True/False
20min

Détecter quand le pion à atteint la fin du damier et devient donc une dame
entrée :  Matrice
sortie :    Dame blanche / Dame noire, ligne, colonne
40min

initialisation :
générer le damier avec les pions au bons endroits.
entrée : taille du plateau
sortie : matrice avec valeur en string des classes de pions (pour mieux comprendre)
30min

départager quel joueur commence (choix des blanc/au hasard)
entrée : aléatoire : True/False, 
sortie : joueur1/ joueur2
20min

main: dans un boucle qui utilise (Vérifier si un joueur gagne)
Permettre au joueur de déplacer son pion (selon les règles de mouvement et de capture).
    on vérifiie que le pion est jouable par le joueur appel la fonction : règles de mouvement
entrée : position1 (pion sélectionné) position2 (lieu de destination), joueur
sortie : nouvelle matrice 25min

Permettre au joueur de valider la fin de son tour (si le joueur n’a pas vu la capture pour s’assurer qu’il veut vraiment mettre fin à son tour)
entrée : “click” 
sortie : appel de la fonction suivante/ rien 30min

Donner le droit de jeu à l’autre joueur (bouger ses propres pions selon les mêmes règles que l’autre joueur.
entrée : joueur-jouant
sortie : joueur1/joueur2 20min

end :
afficher le gagnant de la partie
entrée : 1 ou 2
sortie : “Le joueur 1 gagne” ou “Le joueur 2 gagne” 15min


Bonus :
Partie Frontend :
On utilise Tkinter comme interface:
on affiche le damier à chaque étape (refresh)
on détecte les clics, et selon l’emplacement on détermine quelle case est sélectionnée (si ca ne correspond à aucune case, on n’en tient pas compte)

jouer contre un ordinateur
affichage réaliste
