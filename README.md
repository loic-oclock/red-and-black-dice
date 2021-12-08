# Le jeu du rouge et du noir

Le jeu du rouge et du noir est un jeu qui se joue avec trois dés. Pour gagner, le joueur doit deviner la somme des faces des trois dés après que le croupier a lancé les deux premiers dés et avant qu'il lance le troisième.

Voici comment se déroule une partie :

1. Le croupier lance les deux premiers dés.

2. Le joueur annonce une couleur en fonction du résultat qu'il prédit pour le troisième dé :

    - le joueur annonce la couleur <b style="color: red;">rouge</b> s'il estime que la somme des dés lancés sera supérieure ou égale à 11, ou si les deux premiers dés ont sorti chacun un 1 et s'il pense que le troisième sortira aussi un 1

    - le joueur annonce la couleur <b style="color: black;">noir</b> s'il estime que la somme des dés lancés sera inférieure à 11, ou si les deux premiers dés ont sorti chacun un 6 et s'il pense que le troisième sortira aussi un 6

3. Le croupier lance le troisième dé.

4. Le joueur a gagné s'il avait prédit la bonne couleur.


## Croupier numérique 🤖

Ton défi, si tu l'acceptes, et tu vas l'accepter parce que t'as pas peur, c'est d'implémenter le jeu du rouge et du noir pour le lancement de ton grand casino virtuel.

Bien entendu, ton programme sera le croupier (sinon c'est pas drôle).

*Oh mais je ne sais pas comment je vais faire ! C'est trop duuuuuuur ! Maman !*

Pas de panique ! Tu vas procéder comme tout bon développeur : **par étapes** !


### Étape 1 : on traduit, on traduit !

Dans un premier temps, on ne va pas du tout coder. On ne va même pas penser au HTML, ni aux fonctions de JavaScript ou de PHP.

Tu vas juste *traduire* le déroulé du jeu sous la forme d'instructions simples, en français ou en anglais, que devra exécuter ton croupier.

Par exemple, pour lancer le premier dé, on peut imaginer que ceci suffira :

```
Lancer le premier dé
```

Tu peux même déjà intégrer un peu d'indentation pour structurer ta pensée :

```
Si le ciel est dégagé
    Si il fait plus de 30°C
        je vais me baigner
    Sinon si il fait plus de 20°C
        je vais jardiner
    Sinon
        je mets une doudoune
        et je vais me promener
Sinon
    je reste chez moi
    Si il fait plus de 30°
        je mets la clim
    Sinon si il fait moins de 15°C
        je mets le chauffage
```
(cet exemple n'a aucun rapport avec le jeu - tu croyais qu'on allait te mâcher le travail ?)

Allez, c'est à toi de jouer dans `algo.txt` !

#### Rappels
> Il n'y a pas une solution, il y a **des** solutions. Peu importe que ton raisonnement sois fouillis, brouillon, te paraisse trop compliqué ou trop simple : l'important, c'est que tu essaies de retranscrire les règles du jeu en instructions pour ton croupier.