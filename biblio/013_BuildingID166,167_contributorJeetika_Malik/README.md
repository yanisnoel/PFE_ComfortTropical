# 013 - Building_ID: [166, 167] - "contributor": Jeetika Malik
**Année: 2022 - Titre:** Thermal comfort perception in naturally ventilated affordable housing of India — [DOI](https://doi.org/10.1080/17512549.2021.1907224)

## Revue :
Auteurs : Malik et Bardhan (2022) \
Pays : Inde \
Villes : Mumbai \
Climat (Köppen) : tropical savanna climate : Aw \
Saison étudiée : monsoon ; winter ; summer \
Type de bâtiment : logements \
Nombre de bâtiments : 2 \
Genre : 537 F / 168 H \
Types de ventilation : NV \
Étude de la vitesse d'air ? : oui, sonde à hélice (plage 0,1 à 15 m/s) ; sous 0,1 m/s pas mesurable ou pas fiable ; ventilateurs de plafond (free-running, fan-assisted)

Nombre de votes : 705 (monsoon 277 ; winter 253 ; summer 175) \
Nombre de sujets / de votes : ?

<!-- Coller ici la capture du Table 6 : Seasonal averages of outdoor and indoor environmental data -->

--------------------------------------------------------------------------

## Data base :

Villes : Mumbai, Inde \
Années des données : 2018/2019, sur 4 mois de chaque saison : janvier, mai, août, septembre \
Climat : tropical wet savanna : Aw \
Saison étudiée : hot/wet ; cool/dry \
Type de bâtiment : multifamily housing (705) \
Nombre de bâtiments : 2 [166, 167] \
Genre : 537 F / 168 H \
Types de ventilation : naturally ventilated (705)

Nombre de votes : 705 (hot/wet 452 ; cool/dry 253) → monsoon et summer regroupés en hot/wet \
Nombre de sujets / de votes : ?

### Variables disponibles :

Température de l'air dans la zone occupée "ta" : ok 100 % \
Humidité relative "rh" : ok 100 % ; rh_out à 0 % dans la base, alors que l'article la donne \
Température de globe "tg" : ok 100 % \
Température radiante "tr" : nok, mais retrouvable par calcul \
Vitesse d'air "vel" : ok 100 % ; vel_l, vel_m, vel_h à 0 % → pas de détail par hauteur ; fan, window, air_movement_preference à 100 % mais air_movement_acceptability à 0 % \
Isolation vestimentaire intrinsèque "clo" : ok 100 % \
Taux métabolique "met" : ok 100 % \
Activité : nok 0 % \
Fonction du bâtiment : ok, multifamily housing (logement)

-------------------------------------------------------------------
## Comparaison
| Variable | Dans la publi | Dans la base ASHRAE |
|---|---|---|
| Ta | oui (moy/min/max par saison) | oui, 100 % |
| T_out | oui (moyennes journalières) | oui, 100 % |
| RH | oui | oui, 100 % |
| RH_out | oui | non, 0 % |
| Tg | oui | oui, 100 % |
| Tr | non | non (calculable) |
| Vel | oui (V_a, une valeur) | oui, 100 % ; pas de vel_l/m/h |
| clo | max 1,52 | 13 valeurs > 1,52 (max 2,34) |
| met | ? | oui, 100 % |
| CO2 | oui | ? |
| Saisons | 3 (monsoon, winter, summer) | 2 (hot/wet, cool/dry) |

## Écarts publi/base
- Saisons : 3 dans l'article, 2 dans la base → monsoon + summer regroupés en hot/wet (277 + 175 = 452)
- rh_out donnée dans l'article, absente de la base (0 %)
- clo : max 1,52 dans l'article, mais 13 valeurs au-dessus dans la base (max 2,34) → chercher pourquoi
- air_movement_acceptability à 0 % alors que air_movement_preference est à 100 %

## Résultats clés
-

## Limites / regard critique
- Vitesse d'air < 0,1 m/s non mesurable ou pas fiable (sonde à hélice)
- Une seule vitesse d'air, pas de détail par hauteur (vel_l/m/h vides)
```
<!-- Coller ici la sortie du notebook : % de remplissage par variable -->
```
