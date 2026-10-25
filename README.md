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

## Fresque des métiers Tech autour de l'IA

Atelier collectif pour les lycéens, accessible depuis les ressources de l'accueil et à l'adresse `https://nricl.github.io/MyPage/fresque-metiers-tech-ia/`.

- `fresque-metiers-tech-ia/index.html` : jeu autonome avec illustrations intégrées, 16 métiers, 10 situations et 4 phases.
- `fresque-metiers-tech-ia/cartes-metiers-a-imprimer.pdf` : cartes illustrées à distribuer.
- `fresque-metiers-tech-ia/guide-animateur.pdf` : préparation et déroulé de l'atelier.
- Les 12 Awards collectifs correspondent à 3 cases indépendantes par phase : action concrète, relais et vérification utile. Seul l'animateur les attribue ; révéler une réponse ne donne aucun Award. Le tableau de collection est accessible pendant la partie et au bilan.
- La partie est conservée dans cet onglet via `sessionStorage` (propositions, révélations, positions des cartes et Awards), sans données nominatives. Un avertissement signale tout problème de stockage. Une nouvelle partie efface la progression après confirmation.
- Aucune dépendance ni compilation nécessaire pour le déploiement GitHub Pages. Lors d'une mise à jour, conserver le titre public, le retour vers My Page en haut à gauche et les liens PDF du pied de page.

## Parcours et maintenance

- La navigation reste disponible sur mobile. Le haut de page propose trois entrees : articles, ressources et prises de parole.
- Les articles marques `data-selected` composent la selection "Pour commencer". Les autres restent accessibles avec "Tous les articles" ou les filtres thematiques.
- Les compteurs sont calcules depuis les articles, sans nombre a maintenir dans le JavaScript.
- Conserver `data-pillar` sur chaque article et le meme `data-filter` sur le filtre et la conviction correspondants.
- Les points cles se deploient a la demande. Sans JavaScript, tous les articles et leurs points cles restent lisibles.
- Aucun outil de compilation ni dependance ajoutee. La palette bleu nuit et les liens externes existants sont conserves.
- Refonte UX du 11 septembre 2026 : correction du filtre de la publication phare, navigation clavier, et distinction entre objectif de formation et resultat atteint.
