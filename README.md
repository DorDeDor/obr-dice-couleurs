# Dice (couleurs) — Owlbear Rodeo

Fork du [lanceur de dés officiel d'Owlbear Rodeo](https://github.com/owlbear-rodeo/dice) qui permet de choisir une couleur pour chaque dé, pour distinguer facilement plusieurs dés dans un même lancer.

## Installer dans Owlbear Rodeo

Profil → Extensions → « + » (Add custom extension) → coller :

```
https://dordedor.github.io/obr-dice-couleurs/manifest.json
```

## Utilisation

- Le bouton pastille sous le choix du style ouvre la palette de couleurs.
- Les dés ajoutés ensuite prennent la couleur choisie (« aucune » = couleur d'origine).
- Les couleurs sont visibles par tous les joueurs de la room.
- Rendu le plus net sur les styles clairs (Glass, Gemstone, Sunrise).

## Fonctionnement du dépôt

Ce dépôt ne contient que `dice-couleurs.patch`. À chaque push sur `main`, GitHub Actions récupère le Dice officiel à un commit figé, applique le patch, compile et publie sur GitHub Pages.

## Licence

GPL-3.0, comme le projet d'origine (© Owlbear Rodeo).
