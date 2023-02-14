---------------------------
Règles de Mastermind
---------------------------

L'ordinateur choisi une permutation aléatoire de quatre des six couleurs qui est gardé en secret du joueur (les couleurs peuvent se)
répéter. Le but est de deviner la combinaison avec seulement un nombre limité de devinette selon la difficulté choisi (facile=12; 
médium=10; difficile=8). Après chaque devinette, le joueur reçois un indice avec les cases rouges et blanches. Chaque case blanche
indique que le joueur a placé une bonne couleur mais à la mauvaise position et une case rouge indique qu'il a placé la bonne 
couleur à la bonne place. Ce n'est pas spécifié quelle couleur chaque case rouge et blanche réfère et certaine couleur ne seront
pas dans la solution alors n'auront pas de case blanche ou rouge. Si le joueur devine la solution dans le montant de devinette donné,
le joueur gagne. Sinon il perd. 



---------------------------
Couleurs
---------------------------

Les couleurs du jeu sont les suivantes:

Couleur à deviner: orange, jaune, bleu, vert, magenta et mauve 
Couleur d'indice: rouge et blanc
Arrière-plan: noir
Texte: blanc
Style de fonte: à déterminer



---------------------------
Design et Gameplay
---------------------------

Il y aura une grille de 5 colonne dont 4 sont pour la devinette et la dernière pour l'indice de la devinette dans la même rangé. 
Le nombre de rangé sera défini par la difficulté (facile=12; médium=10; difficile=8). Le joueur clique sur une couleur et ensuite 
clique sur une case pour placer cette couleur dans cette position. Il y aura un bouton pour soumettre la devinette ce qui donnera
l'indice, un ecran de victoire si la devinette est correcte ou un ecran game over s'il n'y a plus de rangé de devinette.
Il y aura aussi le titre du jeu au haut de la page et un lien pour un explication du jeu.