# ComfortTropiques — PFE M2 GC PRISME 2026-2027

**Analyse de base de données environnementale et de confort thermique prenant en compte la vitesse d'air et les conditions chaudes et humides.**

Projet R&D III, Université de La Réunion — laboratoire PIMENT.
Base étudiée : [ASHRAE Global Thermal Comfort Database II](https://github.com/CenterForTheBuiltEnvironment/ashrae-db-II) (v2.1.0).

| | |
|---|---|
| **Équipe** | Randriambololona Nekena Cassy · Rakotoarisoa Lanjaniaina Erick Josua · Yanis Noël |
| **Encadrement** | Maxime Boulinguez (ENSA La Réunion) · Charles Voivret |
| **Calendrier** | 28 août 2026 → soutenance février 2027 |

---

## Questions de travail

1. **Complétude des données en climat tropical** — recensement des études, disponibilité des variables par paliers :
   Tdb + RH → + Tg/Tr → + V (vitesse d'air) → + clo → + métabolisme / type de bâtiment. Analyse critique des études concernées.
2. **Conditions similaires hors climat tropical** — critères de sélection argumentés, sélection selon les mêmes paliers, discussion de la pertinence.

---

## Organisation du dépôt

```
ComfortTropiques/
├── notebooks/          Notebooks Jupyter, numérotés dans l'ordre de la démarche
├── data/
│   ├── raw/            Base ASHRAE brute (non versionnée, voir data/README.md)
│   ├── interim/        Bases de travail intermédiaires, lourdes et régénérables (non versionnées)
│   └── processed/      Petites tables de résultats partagées (listes d'études, tableaux de complétude…)
├── biblio/
│   ├── PFE_26-27.bib   Export Zotero de la bibliographie commune
│   └── fiches/         Une fiche de lecture par étude (modèle : _modele_fiche.md)
├── docs/
│   └── reunions/       Comptes rendus des points avec les tuteurs (modèle : _modele_cr.md)
├── figures/            Figures exportées pour le rapport
└── rapport/            Rapport final / pré-protocole
```

---

## Démarrage

```bash
git clone https://github.com/<compte>/ComfortTropiques.git
cd ComfortTropiques
pip install -r requirements.txt
jupyter lab
```

Les notebooks lisent la base ASHRAE directement depuis le dépôt GitHub du CBE : aucune donnée à télécharger à la main.

---

## Règles de travail (à 3)

- **Toujours `pull` avant de commencer**, `commit` + `push` en fin de séance.
- **Un notebook = un propriétaire.** On ne modifie pas le notebook d'un autre : on copie la cellule dans le sien ou on en parle. Git gère mal les conflits dans les `.ipynb`.
- **Nommage des notebooks** : `NN_sujet_initiales.ipynb` (ex. `02_completude_paliers_YN.ipynb`).
- **Avant chaque commit d'un notebook** : *Kernel → Restart & Run All* (il doit tourner de bout en bout), puis vérifier qu'il n'embarque pas de sorties énormes.
- **Messages de commit courts et explicites** : `ajout fiche Karyono 1996`, `palier V : filtre vitesse d'air`, `CR réunion 03/10`.
- **Pas de PDF de publications dans le dépôt** : références dans le `.bib`, PDF dans Zotero.
- Toute décision méthodologique (critère de sélection, seuil, exclusion d'étude) est **écrite** : dans le CR de réunion ou en Markdown dans le notebook, avec sa justification.

---

## Répartition des lectures (études tropicales 1-20)

| Qui | Études |
|---|---|
| Cassy | 1 à 6 |
| Lanja | 7 à 12 |
| Yanis | 13 à 20 |

---

## Source des données

Földváry Ličina V. et al. (2018). *Development of the ASHRAE Global Thermal Comfort Database II.* Building and Environment, 142, 502-512. https://doi.org/10.1016/j.buildenv.2018.06.022

Hello
