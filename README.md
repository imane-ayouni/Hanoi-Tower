# Hanoi-Tower

Les Tours de Hanoi, (également appelées Tours de Brahma ou Tours de Lucas en
référence à son créateur et mathématicien français Édouard Lucas) sont un jeu
mathématique ou puzzle inventé en 1883.

3 bâtonnets composent le jeu, ainsi que plusieurs disques de tailles différentes. Les
disques sont enfilés dans des tiges par ordre croissant (formant un petit cône).
Le but du jeu est de déplacer entièrement la pile initiale sur le dernier bâtonnet.
– Le joueur ne doit bouger qu’un disque à la fois
– Seul un petit disque peut être placé sur un plus gros disque.

Si le jeu des tours de Hanoi s'avère fort agréable,créer un programme pour vous aider à le
résoudre est tout aussi intéressant.
Votre programme devra recevoir en entrée une configuration de partie à résoudre, sous la
forme d’une chaine de caractere. Par exemple:
“8, 3” pour une partie a 8 disques et 3 bâtonnets.
“172, 5” pour une partie a 175 disques et 5 bâtonnets


Le programme doit ensuite afficher la liste des coups à jouer. Sous la forme suivante:
1 -> 3
1 -> 4
3 -> 4

....
Signifiant :
“Prendre un disque du bâtonnet 1 et le mettre sur le bâtonnet 3”
“Prendre un disque du bâtonnet 1 et le mettre sur le bâtonnet 4”
“Prendre un disque du bâtonnet 3 et le mettre sur le bâtonnet 4”
Attention, à bien gérer les transitions illégales. Par exemple:
1 -> 3
1 -> 3
Car cela placerait un plateau grand sur un plateau petit sur le bâtonnet numéro 3.
De plus, il est demandé à ce que la solution soit la plus courte possible, surtout lorsque le
nombre de bâtonnets est supérieur à 3.
