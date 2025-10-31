# L'Odyssée de l'IA — Présentation & Docs

> Des syllogismes d'Aristote aux usines intelligentes : 18 révolutions qui ont transformé le monde.  
> **Auteur : Olivier Bonnin — Septembre 2025**

Ce dépôt contient :
- la **présentation PowerPoint (22 slides)** ;
- les **documents demandés** (contexte, plan, bibliographie, anecdotes/annexes) ;
- la structure pour ajouter images, données, notebooks et code si besoin.

## Arborescence

```
odyssee-ia-presentation/
├── slides/
│   └── L_Odyssee_de_l_IA_Mixte_22slides.pptx
├── docs/
│   ├── 00_sommaire.md
│   ├── 01_contexte.md
│   ├── 02_plan_projet.md
│   ├── 03_bibliographie.md
│   └── annexes/
│       └── anecdotes.md
├── images/            # ressources visuelles (.gitkeep)
├── data/
│   ├── raw/           # données sources (.gitkeep)
│   └── processed/     # données transformées (.gitkeep)
├── notebooks/         # notebooks Jupyter (.gitkeep)
├── src/               # scripts (build, export, etc.) (.gitkeep)
├── .gitignore
└── LICENSE
```

## Usage rapide

1) **Cloner et pousser vers GitHub**

```bash
git init
git add .
git commit -m "feat: dépôt initial — slides + docs Odyssée de l'IA"
git branch -M main
# Remplace par TON URL de dépôt vide créé sur GitHub :
git remote add origin https://github.com/<ton-user>/odyssee-ia-presentation.git
git push -u origin main
```

2) **Mettre à jour les documents**  
- Édite les fichiers dans `docs/` (sommaire, contexte, plan, bibliographie, anecdotes).
- Ajoute tes visuels dans `images/` et mets à jour les slides si besoin.

3) **Bonnes pratiques**  
- Commits clairs (`feat:`, `fix:`, `docs:` …)  
- Une section par PR si tu travailles à plusieurs.

---

© 2025 Olivier — Licence MIT.
