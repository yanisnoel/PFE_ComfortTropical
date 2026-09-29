# ComfortTropiques - PFE M2 GC PRISME 2026-2027

**Analyse de base de données environnementale et de confort thermique prenant en compte la vitesse d'air et les conditions chaudes et humides.**

Projet R&D III, Université de La Réunion
Base étudiée : [ASHRAE Global Thermal Comfort Database II](https://github.com/CenterForTheBuiltEnvironment/ashrae-db-II) (v2.1.0).

| | |
|---|---|
| **Équipe** | Randriambololona Nekena Cassy; Rakotoarisoa Lanjaniaina Erick Josua; Yanis Noël |
| **Encadrement** | Maxime Boulinguez (ENSA La Réunion); Charles Voivret |
| **Calendrier** | 28 août 2026 - soutenance février 2027 |

---

## Questions de travail

1. **Complétude des données en climat tropical** - recensement des études, disponibilité des variables :
   Tdb + RH / + Tg/Tr / + V (vitesse d'air) / + clo / + métabolisme, type de bâtiment. Analyse critique des études concernées.
2. **Conditions similaires hors climat tropical** - critères de sélection argumentés, sélection selon les mêmes paliers, discussion de la pertinence.

---

## Organisation du dépôt

```
ComfortTropiques/
├── notebooks/          Notebooks Jupyter, numérotés dans l'ordre de la démarche
├── data/
│   └──>                Base ASHRAE brute
├── biblio/
│   └──>                Une fiche de lecture par étude (modèle : _modele_fiche.md) / PDF
├── docs/
│   └── reunions/       Comptes rendus des points avec les tuteurs (modèle : _modele_cr.md)
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

## Répartition des lectures (études tropicales 1-20)
Tout les fiches/pdf dans biblio 

| Qui | Études |
|---|---|
| Cassy | 1 à 6 |
| Lanja | 7 à 12 |
| Yanis | 13 à 20 |
