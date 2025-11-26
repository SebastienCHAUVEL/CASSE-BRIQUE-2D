# 🎮 Jeu de Casse-Briques 2D en JavaScript pur

![Démonstration du jeu](docs/mdn-breakout-gameplay.png)

---

## 📖 Description
Ce projet est une implémentation d’un **jeu de casse-briques 2D** développé en **JavaScript pur**, sans dépendance externe. Le rendu graphique est assuré par la balise HTML5 `<canvas>`, et la logique du jeu repose sur des concepts fondamentaux de la programmation : gestion des collisions, boucles d’animation, et écouteurs d’événements.

Le projet a été réalisé en suivant le **[tutoriel MDN](https://developer.mozilla.org/fr/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript)**.

---

## 🌐 Démo en ligne
👉 **[Jouer à la démo](https://sebastienchauvel.github.io/CASSE-BRIQUE-2D/)**

---

## 🎯 Fonctionnalités
- **Mécaniques de jeu classiques** :
  - Déplacement de la raquette avec les touches **fléchées gauche/droite**.
  - Rebond de la balle sur les briques, les murs et la raquette.
  - Détection des collisions entre la balle et les briques.
  - Game Over si la balle touche le bas de l’écran.
- **Code optimisé** :
  - Gestion fluide des animations avec `requestAnimationFrame` (alternative à `setInterval` pour une meilleure performance).
  - Structure modulaire pour une maintenance facile.
- **Responsive** :
  - Adapté aux écrans de différentes tailles (ajustement du canvas).

---

## 🛠 Technologies utilisées
- **HTML5** : Structure de base avec la balise `<canvas>`.
- **JavaScript (ES6+)** :
  - Manipulation du DOM et du contexte 2D.
  - Gestion des événements clavier (`keydown`, `keyup`).
  - Logique de collision et boucles de jeu.
- **CSS** : Styles minimaux pour une intégration propre.

---

## 💡 Ce que j’ai appris
En réalisant ce projet, j’ai approfondi mes connaissances sur :

✅ **L’API Canvas** : Dessiner des formes, gérer les animations.

✅ **La gestion des collisions** : Détection entre la balle, les briques et la raquette.

✅ **Les boucles de jeu** : Utilisation de `setInterval` et alternatives comme `requestAnimationFrame`.

✅ **Les événements clavier** : Capture des entrées utilisateur en temps réel.

✅ **La logique de jeu** : États, conditions de victoire/défaite, et redémarrage.
