# Slide Show Up — SCALIA BTP

Slides Scalia BTP. Conforme à la charte graphique v1 · Mai 2026.

## URLs

| Présentation | URL |
|---|---|
| **Pitch public (RACINE, sans mot de passe)** | https://johanmaupetit-lgtm.github.io/slide-show-up-/ |
| Accueil (index interne) | https://johanmaupetit-lgtm.github.io/slide-show-up-/accueil/ |
| Show Up — Audit ROI | https://johanmaupetit-lgtm.github.io/slide-show-up-/show-up/ |
| **Diagnostic — Cockpit Phase A** | https://johanmaupetit-lgtm.github.io/slide-show-up-/diagnostic/ |
| Présentation Système — Pitch ROI Pilot | https://johanmaupetit-lgtm.github.io/slide-show-up-/presentation-systeme/ |
| Présentation Système — Calculateur ROI | https://johanmaupetit-lgtm.github.io/slide-show-up-/presentation-systeme/calculateur-roi/ |

Le pitch lit la session via `?session=SLUG` (auto-rempli depuis le diagnostic). Touche `N` pendant le pitch pour afficher / masquer les notes prospect.

## Structure

```
slide-show-up-/
├── theme.css          ← charte Scalia (commune)
├── template.html      ← squelette à copier
├── index.html         ← page d’accueil
├── show-up/           ← projet Show Up (slides)
│   └── index.html
├── diagnostic/        ← cockpit Phase A (cocher critères + notes en RDV)
│   └── index.html
└── presentation-systeme/   ← présentation système (ex-vente)
    ├── index.html             ← slides pitch (lit `?session=SLUG`)
    └── calculateur-roi/       ← app calculateur ROI
        └── index.html
```

## Raccourcis clavier

- `→` / `Espace` : slide suivante
- `←` : précédente
- `F` : plein écran
- `Esc` : vue d’ensemble
- `N` (pitch) : afficher / masquer les notes prospect
