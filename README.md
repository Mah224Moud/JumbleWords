# Jumble Words

### Bienvenue sur Jumble Words
Jumble est un petit jeu qui permet de deviner des mots générer aléatoirement.

A la base, ce jeu a été fait sur console en `C++` d'ailleurs disponible [ici](https://github.com/Mah224Moud/Jumble-console).
Cette nouvelle version de `Jumble Words` a été faite en `Java` à l'aide de `Java Swing` sur `Netbeans`.

## Explication de l'interface du jeu
Au démarrage du jeu, on appuie sur le bouton `Commencer` pour avoir accès à la totalité de l'interface.

- Au nord, nous avons un texte avec le nom du jeu `JumbleWords`;
- A l'ouest(gauche), nous avons nous 3 zone:
`Entrez votre essai ici`,
`Zone de saisi` pour nos differents essais et bouton `Essayer` pour soumettre nos essais.
- A l'est (droite), nous avons:
Le `Mot à deviner` et `Nombre d'essais` (restant);
- Au centre, nous avons une grosse zone de texte qui affiche toute les infos courantes;
- Au sud, les boutons `Commencer` qui disparaît au premier clic d'ailleurs et `Recommencer`;
- Tout en haut en gauche, on a une barre de menu appélée `option` nous permettant d'accéder au bouton `Quitter` pour fermer le jeu.

## Règles du jeu
- Le jeu ne démarre que lors qu'on appuie sur `Commencer`;
- Il est impératif d'écrire votre essai avant de cliquer `Essayer` pour une soumission. Le cas écheant vous aurez un message qui s'affiche dans la zone de texte dedier vous demandant de bien vouloir entrer un mot et ce tant qu'il est vide ;
- Si le mot que vous entrez est incorrecte, un message s'affiche dans la zone de texte vous encourageant à ressayer. Le nombre d'essais se décremente de 1;
- Après 5 essais sans succès, le jeu s'arrêtre et vous suggère de rejouer ;
- Si lors d'un essai vous trouvez le mot, le jeu s'arrêtre et un message de félicitation s'affiche dans la zone de texte.

### A savoir 
- Le nombre d'essais est limité à 5 ;
- Le titre change en fonction de l'etat dans lequel vous vous trouvé(e) (encours de jeu, victoire ou echec) ;
- Vous pouvez `Recommencer` une partie à tout moment. D'ailleurs un clic sur ce bouton remet tout à nouveau (`Nombre d'essai` à 5, change le `Mot de deviner` et efface les `Zones de textes`).
- Attention le programme est sensible à la casse. Tous les mots à deviner sont en majuscule donc les `Mot à essayer` doivent aussi être majuscules.
### Mots à deviner
Pour l'instant, nous avons plus d'une centaine de mots à deviner ;)
## Createur

- [@Mah224Moud](https://www.github.com/Mah224Moud)

