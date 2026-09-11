# MyPage

Page personnelle IA Bloomer d'Eneric Lopez.

## Mise à jour

La page est volontairement statique : `index.html` + `assets/`.

Process retenu :

1. Scanner les nouveaux articles et drafts dans le vault.
2. Proposer une carte de publication ou une nouvelle conviction.
3. Prévisualiser localement.
4. Publier uniquement après validation.
5. Pousser sur GitHub Pages.

URL cible : `https://nricl.github.io/MyPage/`

## Parcours et maintenance

- La navigation reste disponible sur mobile. Le haut de page propose trois entrees : articles, ressources et prises de parole.
- Les articles marques `data-selected` composent la selection "Pour commencer". Les autres restent accessibles avec "Tous les articles" ou les filtres thematiques.
- Les compteurs sont calcules depuis les articles, sans nombre a maintenir dans le JavaScript.
- Conserver `data-pillar` sur chaque article et le meme `data-filter` sur le filtre et la conviction correspondants.
- Les points cles se deploient a la demande. Sans JavaScript, tous les articles et leurs points cles restent lisibles.
- Aucun outil de compilation ni dependance ajoutee. La palette bleu nuit et les liens externes existants sont conserves.
- Refonte UX du 11 septembre 2026 : correction du filtre de la publication phare, navigation clavier, et distinction entre objectif de formation et resultat atteint.
