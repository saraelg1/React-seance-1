# React — Séance 1

Support de la première séance de soutien React (2 heures), avec le cours PowerPoint et le projet utilisé pendant la séance.

## Contenu

- `Cours/React-Seance-1-Cours-et-exercices.pptx` : cours et exercices.
- `src/App.jsx` : composant principal, qui affiche deux instances de `Test`.
- `src/test.jsx` : composant affichant le nom, la capacité et la disponibilité d'un local.
- `src/local.js` : données du local.
- `src/calculs.js` : fonction de calcul du prix.
- `src/main.jsx` : point d'entrée React.
- `src/style.css` : styles du projet.

## Prérequis

Node.js 22.12 ou une version plus récente compatible, avec npm.

## Installation et démarrage

```bash
git clone https://github.com/saraelg1/React-seance-1.git
cd React-seance-1
npm ci
npm run dev
```

Ouvrir l'adresse locale indiquée dans le terminal. Garder le terminal ouvert pendant le travail.

Le premier téléchargement des dépendances nécessite une connexion Internet. Le fichier `package-lock.json` conserve les versions utilisées. Le dossier `node_modules` est recréé par `npm ci` et ne figure pas dans le dépôt.

## Travail pendant la séance

Ouvrir le PowerPoint du dossier `Cours`, puis modifier les fichiers du dossier `src` pour réaliser les exercices. Les exemples travaillent les composants, le JSX, les expressions JavaScript et l'affichage conditionnel.

Le projet reprend les fichiers modifiés par la formatrice. Les deux instances de `Test` utilisent actuellement les mêmes données importées depuis `local.js`.

## Compilation

```bash
npm run build
npm run preview
```

La compilation crée le dossier `dist`. La commande de prévisualisation permet de consulter cette version localement.
