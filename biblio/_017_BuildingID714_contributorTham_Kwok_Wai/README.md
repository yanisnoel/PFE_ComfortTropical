# 017 - Building_ID: [714] - "contributor": Tham Kwok Wai
**Année : 2003 - Titre :** Indoor air quality and energy performance of air-conditioned office buildings in Singapore
*(Indoor Air, 13, p. 315–331 — https://doi.org/10.1111/j.1600-0668.2003.00191.x)*

## Conclusion
Article et données ne correspondent pas : 426 questionnaires dans l'article contre 216 votes dans la base, sur un seul building_id alors que l'étude porte sur 5 bâtiments. Les moyennes de la base ne correspondent à aucun bâtiment du Tableau 2 = impossible de relier les données à un bâtiment précis de l'article.

## Revue :
Auteurs : S. C. Sekhar, K. W. Tham, K. W. Cheong (2003) \
Pays : Singapour \
Villes : Singapour \
Climat (Köppen) : « hot and humid climate » = Af \
Saison étudiée : non précisée (faible variation saisonnière à Singapour) \
Type de bâtiment : bâtiment A institutionnel / bâtiments B, C, D et E = tours de bureaux du Central Business District \
Nombre de bâtiments : 5 (22 configurations de mesure, 120 points de mesure) \
Genre : 64 % F / 36 % H (âge moyen 32,74 ans) \
Types de ventilation : climatisation centrale uniquement (centrales de traitement d'air à eau glacée, une par étage) \
Étude de la vitesse d'air ? : vitesse mesurée (0,13 à 0,18 m/s) ; ventilation étudiée par gaz traceur SF6 (renouvellement d'air, âge de l'air, efficacité d'échange) \
Fenêtre, ventilateur… : aucun (ni fenêtres ouvertes, ni ventilateurs de plafond, ni ventilation naturelle)

Nombre de votes : 426 questionnaires \
Nombre de sujets / de votes : 426 (1 questionnaire par personne). Questionnaire qualité de l'air / syndrome du bâtiment malsain (SBS) adapté de l'EC-Audit, pas de vote de sensation ASHRAE en 7 points

<img width="592" height="223" alt="image" src="https://github.com/user-attachments/assets/a7809541-60a8-4c89-8bed-fbe94facc99b" />

--------------------------------------------------------------------------

## Data base :

Villes : Singapour \
Années des données : 1996 (métadonnées), pas de timestamp \
Climat : tropical rainforest (Af) \
Saison étudiée : summer (216) \
Type de bâtiment : office (216) \
Nombre de bâtiments : 1 (building_id 714) \
Genre : NA \
Types de ventilation : air conditioned (216)

Nombre de votes : 216 \
Nombre de sujets / de votes : 216 votes, sujets non identifiables

### Variables disponibles :

Température de l'air dans la zone occupée "ta" : 100 % \
Température extérieure "t_out" : 0 % \
Humidité relative "rh" : 100 % \
Humidité extérieure "rh_out" : 0 % \
Température de globe "tg" : 0 % \
Température radiante "tr" : 100 % \
Vitesse d'air "vel" : 100 % (sans les 3 hauteurs) \
fan / window / air_movement_preference / air_movement_acceptability : 0 % \
Isolation vestimentaire intrinsèque "clo" : 0 % \
Taux métabolique "met" : 0 % \
Activité : 0 % \
Fonction du bâtiment : office

<img width="392" height="256" alt="image" src="https://github.com/user-attachments/assets/e2012979-4198-40fd-93ab-621f03d16db8" />
<img width="291" height="397" alt="image" src="https://github.com/user-attachments/assets/50c72b8a-8d5e-4a1e-ae4a-cfc3c8dc488c" />

-------------------------------------------------------------------
## Comparaison
| Variable | Dans la publi (Tableau 2, moyennes par bâtiment) | Dans la base ASHRAE (bâtiment 714) |
|---|---|---|
| Nombre de votes | 426 | 216 |
| Bâtiments | 5 (A à E) | 1 |
| Genre | 64 % F / 36 % H | NA |
| Ta (°C) | A 23,8 · B 22,6 · C 22,6 · D 21,7 · E 23,6 | moy. 23,3 (22,4 – 24,7) |
| Tr (°C) | A 24,6 · B 23,2 · C 23,4 · D 22,9 · E 24,1 | moy. 24,3 (23,4 – 25,1) |
| RH (%) | A 60 · B 64 · C 59 · D 57 · E 51 | moy. 58,2 (54 – 63,8) |
| Vel (m/s) | A 0,18 · B 0,13 · C 0,15 · D 0,17 · E 0,14 | moy. 0,18 (0,12 – 0,43) |
| T_out / RH_out | non donnés | 0 % |
| Tg | non donné (Tr donnée) | 0 % |
| Sensation thermique | pas de TSV 7 points (échelles qualité de l'air / SBS) | TSV présente, moy. 0,02 (−3 à +3) |

## Écarts publi/base
- **Votes** : 216 dans la base contre 426 dans l'article → environ la moitié manque.
- **Bâtiments** : 1 building_id contre 5 bâtiments → soit un seul bâtiment a été versé, soit les 5 ont été fusionnés.
- **Valeurs** : les moyennes de la base ne correspondent exactement à aucun bâtiment du Tableau 2. Le bâtiment A est le plus proche (vitesse 0,18 identique, Tr 24,6 contre 24,3), mais Ta (23,8 contre 23,3) et HR (60 contre 58,2) diffèrent → rattachement incertain.
- **Questionnaire** : la base contient des votes de sensation thermique (TSV), alors que l'article ne présente que des échelles qualité de l'air / SBS → la TSV vient peut-être d'une partie du questionnaire non publiée.
- **Saison** : l'étiquette « summer » n'a pas de sens à Singapour (Af, pas de saisons marquées).
- **Année** : 1996 dans la base, article reçu en 2000 → cohérent si les mesures datent de 1996.

## Résultats clés
- Le bâtiment A a l'acceptabilité de l'air la plus mauvaise (environ 50 % d'insatisfaits) et le plus d'inconfort thermique.
- Femmes : 1,5 à 2 fois plus de symptômes SBS que les hommes.
- L'indice de symptômes (BSI) est corrélé à l'acceptabilité de l'air et au confort thermique, mais pas à l'indice de polluants (IPSI) → la perception des occupants diffère des mesures de polluants.
- Températures plutôt fraîches (Ta 21,7 à 23,8 °C) et vitesses d'air faibles (0,13 à 0,18 m/s).

## Limites / regard critique
- Étude centrée sur la qualité de l'air et l'énergie, pas sur le confort thermique : pas de TSV publiée, pas de votes individuels associés aux mesures.
- Climatisation seule, vitesse d'air quasi constante → peu utile pour l'axe vitesse d'air du PFE.
- Pas de clo ni de met → PMV non calculable ; palier max 3 (Ta + HR + Tr + vitesse).
- Base incomplète (216/426) et rattachement aux bâtiments impossible → à utiliser avec prudence.

```
```
