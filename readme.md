## Création d'un petit jeu sur navigateur web à l'aide du DOM à local

---

![dice-game](https://user-images.githubusercontent.com/44428775/111074974-ed630980-84e5-11eb-8253-fa3f90d9e88c.gif)

---

### Règles du jeu
Le jeu comprend 2 joueurs sur un seul et même écran.
Chaque joueur possède un score temporaire (ROUND) et un score global (GLOBAL).
A chaque tour, le joueur a son ROUND initialisé à 0 et peut lancer un dé autant de fois qu'il le souhaite. Le résultat d'un lancer est ajouté au ROUND.

Lors de sont tour, le joueur peut décider à tout moment de: 
- Cliquer sur l'option "Hold",qui permet d'envoyer les points du ROUND vers le GLOBAL. Ce sera alors le tour de l'autre joueur.
- Lancer le dé. S'il obtient un 1, son score ROUND est perdu et c'est la fin de son tour.

Le premier joueur qui atteint les 100 points sur global gagne le jeu.

---

### Moyens utilisés:

- [Visual Studio Code]
- [PHP 8.2]
- [html 5]
- [CSS 3]
- [Sass]
- [JavaScript]
- Le framework [ionic]
- [google Fonts]

### Test local du projet

- Placez-vous dans indexx.html et cli droit sur la sourie pour lancer le projet avec le PHP server.
- cela va déclencher l'url (http://localhost:3000) sur le navigateur.
- Il ne vous reste plus qu'à tester le jeu en sur le navigateur.
