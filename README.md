# Loup-garou du corps humain

Un jeu de loup-garou à projeter en classe, où les connaissances en science décident qui survit. Conçu pour la science de **Secondaire 3** (Québec), univers vivant : l'être humain.

Le village de Sainte-Cellule cache des loups-garous. L'enseignant·e mène la partie à l'écran et lit les textes encadrés à voix haute. Une bonne réponse peut sauver la victime des loups, faire acquitter une personne accusée ou donner un indice au village.

## Jouer

Ouvrir `index.html` dans un navigateur (ou la page GitHub Pages du dépôt) et projeter l'écran. Aucune installation, aucun compte, aucune donnée envoyée : les réglages sont gardés dans le navigateur seulement.

**Matériel :** un jeu de fiches A, B, C, D par élève (`fiches-ABCD-loup-garou.pdf`, une page par élève à découper). Chaque lettre a sa couleur et sa forme, les mêmes qu'à l'écran : A rond bleu, B triangle orange, C carré vert, D losange violet.

## Déroulement d'un tour

1. **Nuit** (yeux fermés) : le médecin protège un joueur, la voyante montre sa fiche pour répondre à une question et, si elle a raison, découvre le rôle d'un joueur. Les loups pointent leur victime.
2. **Lever du jour** : la victime répond à une question de survie en montrant sa fiche au meneur seulement (ou à voix haute). Mauvaise réponse : elle est éliminée et son rôle est révélé.
3. **Laboratoire** : au signal « 3, 2, 1… fiches ! », tous les joueurs en vie montrent leur fiche au meneur. Si la majorité a raison, un innocent est révélé.
4. **Débat et vote** : le village accuse quelqu'un, qui répond à une question de défense pour sauver sa peau.

Le village gagne quand tous les loups sont éliminés. Les loups gagnent quand ils sont aussi nombreux que les villageois.

## Contenu

- 85 questions à choix multiple avec explication, réparties sur 8 systèmes : digestif, respiratoire, circulatoire, lymphatique et immunité, excréteur, nerveux et sens, musculosquelettique, reproducteur. On coche les systèmes déjà vus en classe.
- Rôles : loups-garous (nombre automatique ou au choix), voyante, médecin, villageois.
- Distribution des rôles à l'écran, un élève à la fois, ou liste du meneur à copier pour faire des cartes papier.
- Minuterie par question (facultative), 2 minutes de débat, bilan de réussite par système à la fin.

## Ajouter ses propres questions

Dans les réglages, section « Ajouter mes propres questions », une question par ligne :

```
Question | Bonne réponse | Mauvaise 1 | Mauvaise 2 | Mauvaise 3 | Explication (facultatif)
```

L'ordre des choix est mélangé au moment du jeu.

## Mettre en ligne avec GitHub Pages

1. Déposer `index.html`, `fiches-ABCD-loup-garou.pdf` et ce `README.md` à la racine du dépôt.
2. Dans le dépôt : **Settings → Pages**, source **Deploy from a branch**, branche `main`, dossier `/ (root)`.
3. Après une minute ou deux, le jeu est accessible à l'adresse `https://<nom-utilisateur>.github.io/<nom-du-depot>/`.

## Crédits

Questions, textes, icônes et fiches originaux. La mécanique s'inspire du jeu de rôles cachés Mafia (Dimitri Davidoff, 1986). Ce projet n'est pas affilié aux Loups-Garous de Thiercelieux.
