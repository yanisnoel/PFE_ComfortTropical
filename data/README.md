# Données

## raw/ — non versionné
Base ASHRAE Global Thermal Comfort Database II, v2.1.0 :
- `db_metadata.csv`
- `db_measurements_v2.1.0.csv(.gz)`

Source : https://github.com/CenterForTheBuiltEnvironment/ashrae-db-II/tree/master/v2.1.0
Les notebooks la lisent directement par URL. Ce dossier ne sert qu'en cas de travail hors ligne.
Description des variables : `parameter_description.pdf` du dépôt ASHRAE.

## interim/ — non versionné
Bases de travail produites par les notebooks (ex. `maBaseDeTravailDuPFE.csv`, fusion metadata + measurements sur `building_id`).
Trop lourdes pour GitHub (> 50 Mo) et **régénérables** en relançant le notebook qui les crée.
→ Indiquer ici quel notebook produit quel fichier :

| Fichier | Produit par |
|---|---|
| `maBaseDeTravailDuPFE.csv` | `notebooks/01_...ipynb` |

## processed/ — versionné
Petites tables partagées entre nous (quelques Mo maximum) :
listes d'études tropicales, tableaux de complétude par palier, sélections finales.

## Données hors ASHRAE
Les données non publiées éventuellement transmises par les tuteurs ne sont **pas** mises dans le dépôt sans leur accord.
