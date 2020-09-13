# Altérations d'état

L'altération d'état d'un joueur, définit sa situation actuelle. Certains statuts empêchent le joueur d'effectuer certaines actions dans le jeu.

###  Liste des états 

| Symbole | Nom des différentes altérations | Temps d'attente |
| :--- | :--- | :--- |
| 😃  | Pas d'altération d'état | **Ø** |
| [![Emoji Baby](https://vignette.wikia.nocookie.net/draftbot/images/9/93/Emoji_Baby.png/revision/latest/scale-to-width-down/20?cb=20200301093928&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/9/93/Emoji_Baby.png/revision/latest?cb=20200301093928&path-prefix=fr) | Statut de départ | **Ø** |
| [![Emoji Confounded](https://vignette.wikia.nocookie.net/draftbot/images/0/01/Emoji_Confounded.png/revision/latest/scale-to-width-down/20?cb=20200301093840&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/0/01/Emoji_Confounded.png/revision/latest?cb=20200301093840&path-prefix=fr) | Confus | **40min** |
| 🥶  | Gelé | **1h** |
| 😴  | Endormis | **3h** |
| [![Ivre](https://vignette.wikia.nocookie.net/draftbot/images/4/4c/Ivre.png/revision/latest/scale-to-width-down/20?cb=20200422162728&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/4/4c/Ivre.png/revision/latest?cb=20200422162728&path-prefix=fr) | Ivre | **4h** |
| [![Emoji Head-Bandage](https://vignette.wikia.nocookie.net/draftbot/images/f/f1/Emoji_Head-Bandage.png/revision/latest/scale-to-width-down/20?cb=20200301094204&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/f/f1/Emoji_Head-Bandage.png/revision/latest?cb=20200301094204&path-prefix=fr) | Blessé | **6h** |
| [![Emoji Nauseated-Face](https://vignette.wikia.nocookie.net/draftbot/images/9/94/Emoji_Nauseated-Face.png/revision/latest/scale-to-width-down/20?cb=20200229133419&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/9/94/Emoji_Nauseated-Face.png/revision/latest?cb=20200229133419&path-prefix=fr) | Malade | **6h** |
| [![Emoji Dizzy-Face](https://vignette.wikia.nocookie.net/draftbot/images/0/0d/Emoji_Dizzy-Face.png/revision/latest/scale-to-width-down/20?cb=20200229133925&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/0/0d/Emoji_Dizzy-Face.png/revision/latest?cb=20200229133925&path-prefix=fr) | Gravement blessé | **12h** |
| [![Emoji Lock](https://vignette.wikia.nocookie.net/draftbot/images/4/46/Emoji_Lock.png/revision/latest/scale-to-width-down/20?cb=20200301093817&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/4/46/Emoji_Lock.png/revision/latest?cb=20200301093817&path-prefix=fr) | Enfermé | **24h** |
| [![Emoji Clock2](https://vignette.wikia.nocookie.net/draftbot/images/3/35/Emoji_Clock2.png/revision/latest/scale-to-width-down/20?cb=20200301094015&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/3/35/Emoji_Clock2.png/revision/latest?cb=20200301094015&path-prefix=fr) | Occupé | **Variable** |
| 💀  | Mort | **Ø** |

{% hint style="warning" %}
L'altération d'état "Enfermé" est la seule altération d'état à interdire l'accès au magasin
{% endhint %}

{% hint style="danger" %}
L'altération d'état "Mort" bloque la totalité des commandes du bot excepté la commande `!respawn`
{% endhint %}

### Soin des altérations d'état

Les altérations d'état se soignent d'elles même avec le temps \(à l'exception de l'altération "Mort"\).

Il est cependant possible de soigner une altération d'état autrement qu'en attendant.

#### Obtention d'un "soin des altération d'état"

Il est possible d'acheter un soin des altérations d'état dans le magasin en utilisant la commande `!shop`. Cet achat vous coutera 500 d'argent et annulera votre altération d'état. Lorsque votre altération d'état est annulé, votre personnage est enregistré comme si il venait juste d'effectuer un rapport.

{% hint style="info" %}
Le soin d'altération d'état est également une récompense de la récompense journalière de guilde à partir d'un certain niveau de guilde
{% endhint %}

#### Potions et objets permettant de faire avancer le temps plus vite

Certains objets et certaines potions permettent de faire avancer le temps plus rapidement pendant un certain temps, lorsque ces derniers sont utilisés, c'est comme si le temps s'était écoulé mais seulement pour votre personnage.

