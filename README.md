# Rage de sucre

Un jeu d'arcade inspiré de *Tapper*, dans un cimetière la nuit. Des monstres sortent de leurs tombes et avancent sur quatre sentiers vers **Léo**, l'apprenti magicien. Aide-le à leur lancer des bonbons avec sa baguette magique : chaque créature a ses favoris… et ceux qu'elle déteste.

- Un monstre qui **aime** son bonbon le dévore et retourne dans sa tombe.
- S'il le **déteste**, il enrage et accélère.
- Sinon, *bof* : il s'arrête un instant puis repart.

Note ce que tu découvres dans le **grimoire** (Échap).

## Jouer

Ouvre `index.html` dans un navigateur. Aucun outil à installer.

| Touche | Action |
| --- | --- |
| ↑ ↓ ou W S / Z S | changer de sentier |
| Espace ou clic | lancer un bonbon |
| 1 à 8 · Q E · molette | choisir le bonbon |
| Échap | grimoire + pause |
| M / N | musique / sons |

## Contenu

- 3 mondes de 3 niveaux, avec chacun son décor, ses créatures et ses bonbons :
  1. **Le cimetière** : zombie, momie, squelette, fantôme
  2. **La forêt des ténèbres** : loup-garou, gobelin, vampire, troll
  3. **Le château maudit** : toutes les créatures réunies
- Un **boss** au 3e niveau de chaque monde (Frankenstein, la sorcière, le roi citrouille) : il lui faut plusieurs bonbons qu'il aime pour s'en retourner, et la musique devient plus lourde quand il sort
- Après le 3e monde, le cauchemar recommence, plus rapide
- **La forêt maléfique** : quand Léo perd sa dernière lanterne, les monstres l'emportent dans la forêt. Donne au Gardien de la forêt les 5 bonbons qu'il réclame dans sa bulle et Léo revient avec toutes ses lanternes. Une seule chance par monde
- **Regagner des lanternes** : touche avec un bonbon la **lanterne magique** qui flotte parfois sur un sentier, ou va chercher la **potion orange** qui apparaît au bout d'un sentier (plus souvent quand il ne reste qu'une lanterne)
- Musique et effets sonores générés dans le navigateur (Web Audio)
- Tableau des records : partagé entre joueurs sur la version publiée sur claude.ai, sinon enregistré sur l'appareil

## Concepteurs

Léo Laganière et Noémi Laganière

## Mettre à jour

Le fichier `version.json` doit contenir la même version que `const VERSION` dans `index.html`. Quand une nouvelle version est publiée, le jeu ouvert sur un téléphone affiche un bouton « Nouvelle version — Mettre à jour ».
