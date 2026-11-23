# Loup-garou du corps humain

Un jeu de loup-garou à projeter en classe, où les connaissances en science décident qui survit. Conçu pour la science de **Secondaire 3** (Québec), univers vivant : l'être humain.

Le village de Sainte-Cellule cache des loups-garous. L'enseignant·e mène la partie à l'écran et lit les textes encadrés à voix haute. Une bonne réponse peut sauver la victime des loups ou donner un indice au village, mais le vote du village est sans appel.

## Jouer

Ouvrir `index.html` dans un navigateur (ou la page GitHub Pages du dépôt) et projeter l'écran. Aucune installation, aucun compte, aucune donnée envoyée : les réglages sont gardés dans le navigateur seulement.

**Matériel :** un jeu de fiches A, B, C, D par élève (`fiches-ABCD-loup-garou.pdf`, une page par élève à découper). Chaque lettre a sa couleur et sa forme, les mêmes qu'à l'écran : A rond bleu, B triangle orange, C carré vert, D losange violet.

## Déroulement d'un tour

1. **Nuit** (yeux fermés) : Cupidon répond à une question pour unir deux amoureux (s'il se trompe, il réessaie la nuit suivante). Ensuite, chaque nuit : le médecin protège un joueur (et peut utiliser une injection mortelle), la voyante montre sa fiche pour répondre à une question et, si elle a raison, découvre le rôle d'un joueur, les loups pointent leur victime, puis le joueur de flûte charme deux joueurs.
2. **Lever du jour** : la victime répond à une question de survie en montrant sa fiche au meneur seulement (ou à voix haute). Mauvaise réponse : elle est éliminée et son rôle est révélé.
3. **Laboratoire** : au signal « 3, 2, 1… fiches ! », tous les joueurs en vie montrent leur fiche au meneur. Si la majorité a raison, un innocent est révélé.
4. **Débat et vote** : le village vote pour éliminer quelqu'un. Pas de seconde chance : la personne est éliminée et son rôle est révélé.

Le village gagne quand tous les loups (et le joueur de flûte) sont éliminés. Les loups gagnent quand ils sont aussi nombreux que les autres joueurs. Le joueur de flûte gagne seul quand tous les survivants sont charmés. Un couple d'amoureux formé d'un loup et d'un villageois gagne s'il est le dernier en vie.

## Contenu

- 405 questions à choix multiple avec explication, environ 50 par système, réparties sur 8 systèmes : digestif, respiratoire, circulatoire, lymphatique et immunité, excréteur, nerveux et sens, musculosquelettique, reproducteur. On coche les systèmes déjà vus en classe, ou un seul système pour une révision ciblée.
- Pas de répétition : le jeu retient les questions déjà posées, d'une partie à l'autre, et pige d'abord parmi celles jamais posées. Quand elles ont toutes été vues, la banque repart à neuf (un bouton permet aussi de la remettre à neuf).
- Rôles : loups-garous (nombre automatique ou au choix), villageois et sept rôles spéciaux à activer au choix :

| Rôle | Pouvoir |
|---|---|
| Voyante | Chaque nuit, découvre le rôle d'un joueur (si elle répond bien à une question). |
| Médecin | Chaque nuit, protège un joueur contre les loups. Possède de 0 à 3 injections mortelles par partie. |
| Cupidon | Désigne deux amoureux une seule fois (s'il répond bien; sinon, il réessaie la nuit suivante). Si l'un meurt, l'autre meurt de chagrin. |
| Joueur de flûte | Chaque nuit, charme deux joueurs (s'il répond bien). Gagne seul si tous les survivants sont charmés. |
| Chasseur | Quand il est éliminé, tire une dernière balle (s'il répond bien) et emporte un joueur avec lui. |
| Ancien | Survit à la première attaque des loups. |
| Petite fille | Peut entrouvrir les yeux pour espionner les loups pendant leur tour. |

- Distribution des rôles à l'écran, un élève à la fois, ou liste du meneur à copier pour faire des cartes papier.
- Minuterie par question (facultative), 2 minutes de débat, bilan de réussite par système à la fin.

## Importer ses listes d'élèves

Dans les réglages, section « 1. Les joueurs » :

- **Importer un fichier** : Excel (.xlsx, .xls), LibreOffice (.ods), CSV ou texte. Les colonnes « Prénom » et « Nom » sont reconnues (par exemple dans une liste exportée du système de l'école); les numéros de fiche et les lignes de titre sont ignorés. On peut aussi glisser le fichier dans la boîte, ou coller une colonne copiée d'Excel.
- **Mes groupes** : enregistrez chaque liste une fois (ex. 301, 302), puis choisissez le groupe avant de jouer. Les groupes restent dans le navigateur de l'ordinateur utilisé; ils ne sont envoyés nulle part.

## Ajouter ses propres questions

Dans les réglages, section « Ajouter mes propres questions », une question par ligne :

```
Question | Bonne réponse | Mauvaise 1 | Mauvaise 2 | Mauvaise 3 | Explication (facultatif)
```

L'ordre des choix est mélangé au moment du jeu.

On peut aussi importer un fichier Excel ou CSV de questions, avec une question par ligne et les colonnes dans cet ordre : Question, Bonne réponse, Mauvaise 1, Mauvaise 2, Mauvaise 3, Explication (facultative).

## Mettre en ligne avec GitHub Pages

1. Déposer `index.html`, `fiches-ABCD-loup-garou.pdf` et ce `README.md` à la racine du dépôt.
2. Dans le dépôt : **Settings → Pages**, source **Deploy from a branch**, branche `main`, dossier `/ (root)`.
3. Après une minute ou deux, le jeu est accessible à l'adresse `https://<nom-utilisateur>.github.io/<nom-du-depot>/`.

## Crédits

Questions, textes, icônes et fiches originaux. La mécanique s'inspire du jeu de rôles cachés Mafia (Dimitri Davidoff, 1986). Ce projet n'est pas affilié aux Loups-Garous de Thiercelieux.
