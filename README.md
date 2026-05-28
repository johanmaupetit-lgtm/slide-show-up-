# slide-show-up-

Slides Scalia BTP. Conforme à la charte graphique v1 · Mai 2026.

## Accès en ligne

Une fois GitHub Pages activé :
- Index des présentations : **https://johanmaupetit-lgtm.github.io/slide-show-up-/**
- Préparer votre RDV : **https://johanmaupetit-lgtm.github.io/slide-show-up-/presentations/preparation-rdv/**

## Structure

```
slide-show-up-/
├── theme.css                              ← charte Scalia (commune à toutes les présentations)
├── template.html                          ← squelette à dupliquer pour une nouvelle présentation
├── index.html                             ← page d'accueil listant les présentations
└── presentations/
    └── preparation-rdv/index.html         ← une présentation = un dossier
```

## Ajouter une nouvelle présentation

1. Copier le dossier `presentations/preparation-rdv/` en `presentations/<nouveau-slug>/`
2. Éditer `index.html` à l'intérieur (le `<link>` vers `../../theme.css` reste valide).
3. Ajouter une ligne dans la liste de `index.html` (racine) pour la lister.

URL finale : `…github.io/slide-show-up-/presentations/<nouveau-slug>/`

## Raccourcis pendant une présentation

- `→` / `Espace` : slide suivante
- `←` : slide précédente
- `F` : plein écran
- `S` : mode présentateur (notes)
- `Esc` : vue d'ensemble

## Activer GitHub Pages (une seule fois)

1. Repo → **Settings** → **Pages**
2. Source : **GitHub Actions**
3. Le workflow `.github/workflows/pages.yml` déploie à chaque push sur `main`.
