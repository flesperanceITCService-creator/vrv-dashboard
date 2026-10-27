# Tableau de bord ITC — Démarrages VRV et suivi de dossiers

Pages publiées via GitHub Pages à partir de ce dépôt :

- `index.html` — page d'accueil
- `tableau-de-bord.html` — KPIs et graphiques des démarrages VRV
- `kanban.html` — kanban des démarrages (En retard / Cette semaine / À venir / Terminés)
- `dossiers.html` — cartes dynamiques de suivi de dossiers (budgets MEM, PO, heures prévues)

Données : exports ProgressionLIVE (tâches de démarrage et dossiers projets),
régénérées par les scripts `build_vrv_*.py`, `build_dossiers_cartes.py` et `rebuild_vrv.py`.
Publication quotidienne : `publier_github.sh` (dépôt local → commit → push → GitHub Pages).
