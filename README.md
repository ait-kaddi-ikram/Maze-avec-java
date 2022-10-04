# Maze-avec-java
une application Desktop Java qui permet de manipuler un agent, l’unique objet mobile
de la scène, à l’aide du clavier, pour atteindre la sortie du labyrinthe. Le joueur dispose d’un score
nul au début qu’il peut alimenter en gagnant des bonus, 5 points par bonus. Il perd 2 points quant-il
traverse un obstacle, aussi il perd des points lorsqu’il demande de l’aide pour visualiser
temporairement un chemin pour atteindre un bonus ou la sortie (1 point pour un bonus et 3xa
points pour la sortie, a dépend de la stratégie à utiliser).
Les obstacles se trouvent initialement sur un des chemins vers la sortie et les bonus sont répartis
aléatoirement sur le labyrinthe. Chaque fois qu’un bonus est consommé, un autre apparait dans une
autre zone choisie aléatoirement.
L’application doit prendre en considération ce qui suit :

• Lors de la demande de d’aide, permettre le choix de la méthode de résolution : recherche en
profondeur d’abord (a=1/3), recherche en largeur d’abord (a=2/3) ou A* (a=1) ;

• Choisir un des modèles de labyrinthes, chargés à partir des fichiers ;

• Fixer le nombre des obstacles et le nombre des bonus ;
