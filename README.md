# La Voie lactée

Jeu de fusion de planètes, sans pub, jouable sur téléphone et ordinateur.

## Principe

- Glisse le doigt pour viser, lâche pour lancer une planète.
- Deux planètes identiques qui se touchent fusionnent en une planète plus grosse.
- Échelle : Pluton › Mercure › Mars › Terre › Neptune › Saturne › Jupiter › Soleil.
- Deux Soleils qui se rencontrent font une supernova (+200 points).
- Si une planète reste plus de 2 secondes au-dessus de la ligne rouge, la partie est perdue.

Le record est gardé dans le navigateur.

## Jouer

Ouvre `index.html` dans un navigateur, ou publie le dépôt avec GitHub Pages
(Settings › Pages › branche `main`, dossier `/`).

Sur iPhone : ouvre la page dans Safari, puis Partager › « Sur l'écran d'accueil ».

## Technique

Un seul fichier HTML. Physique avec [Matter.js](https://brm.io/matter-js/) 0.19.0 (chargé depuis cdnjs),
planètes dessinées en Canvas.
