# Slide Show Up — SCALIA BTP

Slides Scalia BTP. Conforme à la charte graphique v1 · Mai 2026.

## URLs

| Présentation | URL |
|---|---|
| Index | https://johanmaupetit-lgtm.github.io/slide-show-up-/ |
| Show Up — Audit ROI | https://johanmaupetit-lgtm.github.io/slide-show-up-/show-up/ |
| **Diagnostic — Cockpit Phase A** | https://johanmaupetit-lgtm.github.io/slide-show-up-/diagnostic/ |
| Vente — Pitch Système ROI Pilot | https://johanmaupetit-lgtm.github.io/slide-show-up-/vente/ |
| Vente — Calculateur ROI | https://johanmaupetit-lgtm.github.io/slide-show-up-/vente/calculateur-roi/ |

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
└── vente/             ← projet Vente
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
