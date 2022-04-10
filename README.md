# Project_S2_FIMI
This is a school project.

This project is entirely written in python with an approximative syntax and optimization.

It recreates the "jeu de dames", with our own rules :

Principe du jeu :
Chaque joueur commence avec 20 pions sur un damier sur la couleur noire.
Les joueurs déplacent un de leurs pions l’un après l’autre.
Les pions se déplace en diagonale et uniquement vers l'avant (selon le joueur).
Le plateau du jeu est un plateau de 10 cases par 10 cases dont les couleurs des cases s’alternent.

Pour capturer un pion : Pour capturer le pion il faut qu’il y ait un pion devant lui et que la case suivante soit vide (dans la diagonale). Si la situation de la capture se répète, la capture continue, durant une capture multiple on peut changer de diagonale.

Attention : le pion ne peut pas reculer.


Quand un pion atteint la dernière ligne de l’adversaire, il se transforme en une DAME.
    la capture pour la dame :
La capture se fait dans la diagonale. Si deux pions adverses sont côte à côte dans la diagonale, la dame ne peut pas capturer.

La dame se déplace en diagonale du nombre de cases désirées.


Le joueur gagne quand il n’y a plus de pions adverses sur le plateau.
