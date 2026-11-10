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

## Travailler avec l’IA

Parcours de lecture et support d’animation : `https://nricl.github.io/MyPage/travailler-avec-ia/`.

- La carte « Travailler avec l’IA. Transformer le travail. » figure dans la rubrique « Mes réalisations personnelles » de la section Ressources et pointe vers `https://nricl.github.io/MyPage/travailler-avec-ia/?v=263740d`.
- `travailler-avec-ia/index.html` conserve les textes développés, les trois situations professionnelles et le mode « Animer ».
- `travailler-avec-ia/masterclass-illustrations/` contient uniquement les 14 PNG finaux. Les messages courts suivent les fiches éditoriales de l’index validé le 10 novembre 2026.
- En projection, chaque illustration apparaît seule ; les messages se révèlent ensuite un par un. Les flèches permettent de parcourir la présentation, Échap de revenir à la lecture.
- L’expertise, l’apprentissage permanent et les compétences relationnelles sont rattachés à l’illustration 08 : les deux messages courts restent inchangés, les paragraphes complets sont conservés dans la consultation, sans écrans autonomes supplémentaires en projection.
- Conclusion : « L’IA doit rimer avec Ingéniosité Amplifiée », synthèse éditoriale validée et distinguée du Word en consultation, après la conclusion originale conservée. Les six messages se révèlent un par un en grand, sans accumulation ni réduction du texte ; la phrase finale apparaît à la commande suivante. Retour permet de revoir chaque message, y compris depuis la phrase finale. Aucune illustration ajoutée.
- Le bandeau du mode Animer affiche le grand titre de la partie, son numéro et les étapes de cette partie sur une ligne de points : étapes parcourues colorées, étape actuelle cerclée, étapes à venir vides. Les compteurs distinguent les étapes, les messages révélés et la position globale ; ils suivent aussi les retours en arrière.
- Conserver les liens vers My Page en haut à gauche et en pied de page. Le compteur de projection est calculé depuis les diapositives.
- Le site est statique, sans dépendance ni compilation. Les prompts, documents de travail et variantes abandonnées ne sont pas publiés.

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
