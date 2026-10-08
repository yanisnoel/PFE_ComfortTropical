# 016 - Building_ID: [560] - "contributor": Myla Mary Andamon
**Année : 2006 - Titre :** Thermal Comfort and Building Energy Consumption in the Philippine Context

> PDF : Andamon - 2006 - Thermal Comfort and Building Energy Consumption in the Philippine Context.pdf

## Conclusion
Article et base concordent sur l'essentiel : 277 votes dans les deux. Cependant les 5 bâtiments de l'article sont regroupés en un seul building_id. La température de globe est bien présente, mais seulement dans la colonne tg_h et pas dans tg. Avec Tr recalculée à partir de tg_h, cette étude a toutes les variables nécessaires (Ta, HR, Tr, vitesse, clo, met).

## Revue :
Auteurs : Mary Myla Andamon \
Pays : Philippines \
Villes : Makati City (Manille), quartier d'affaires \
Climat (Köppen) : chaud et humide selon l'article (Manille = Aw, savane tropicale) \
Saison étudiée : non précisée (données de 2002-2003) \
Type de bâtiment : bureaux \
Nombre de bâtiments : 5, dont Ayala Tower One étudiée en détail \
Genre : non donné \
Types de ventilation : climatisation uniquement \
Étude de la vitesse d'air ? : mesurée (anémomètre omnidirectionnel) mais pas analysée dans l'article

Questionnaires et entretiens : sensation thermique, acceptabilité, préférence, questions ouvertes sur les attentes et le confort

Nombre de votes : 277 \
Nombre de sujets / de votes : 277 employés de bureau, 1 vote chacun

<img width="1057" height="755" alt="image" src="https://github.com/user-attachments/assets/37ccbc4b-73a2-4810-b505-fe410a872193" />
<img width="1026" height="707" alt="image" src="https://github.com/user-attachments/assets/45464b59-0373-4417-8216-92cd2be63b8b" />
<img width="838" height="486" alt="image" src="https://github.com/user-attachments/assets/520d5a61-6ca9-4e73-8ae6-c87afc052367" />

--------------------------------------------------------------------------

## Data base :

Villes : Makati \
Années des données : 0 pas de timestamp \
Climat : tropical wet savanna (Aw) \
Saison étudiée : summer (277) \
Type de bâtiment : office (277) \
Nombre de bâtiments : 1 (building_id 560) \
Genre : 171 F (62 %) / 106 H (38 %) \
Types de ventilation : air conditioned (277)

Nombre de votes : 277 \
Nombre de sujets / de votes : pas de subject_id, 277 votes

### Variables disponibles :

Température de l'air dans la zone occupée "ta" : 100 % \
Humidité relative "rh" : 100 % \
Température de globe "tg" : 0 % (mais tg_h : 100 %) \
Température radiante "tr" : 0 % (calculable à partir de tg_h, ta et vel) \
Vitesse d'air "vel" : 100 % \
Isolation vestimentaire intrinsèque "clo" : 100 % \
Taux métabolique "met" : 100 % \
Activité : 0 % \
Fonction du bâtiment : office \
Autres : t_out 100 % ; rh_out 0 % ; thermal_sensation, thermal_preference, thermal_acceptability 100 % ; thermal_comfort 99,6 % ; air_movement_acceptability 99,3 % ; air_movement_preference 97,1 % ; âge, taille, poids 0 % ; fan et window 0 %

-------------------------------------------------------------------
## Comparaison
| Variable | Dans la publi | Dans la base ASHRAE (moyenne, min - max) |
|---|---|---|
| Nombre de votes | 277 | 277 |
| Bâtiments | 5 | 1 building_id |
| Genre | non donné | 171 F / 106 H |
| Ta (°C) | 23,7 (20,9 - 27,7) | 23,76 (20,9 - 27,7), médiane 23,7 |
| Tg (°C) | mesurée, valeurs non données | tg_h : 23,38 (20,0 - 26,7) |
| To (°C) | 23,4 en moyenne à Ayala Tower One | 0 %, mais Tg_h moyenne 23,38 °C, très proche |
| T_out (°C) | non donnée | 29,4 (24 - 36) |
| RH (%) | mesurée, valeurs non données | 47,4 (29,3 - 72), médiane 46,2 |
| RH_out | non donnée | 0 % |
| Vel (m/s) | mesurée, valeurs non données | 0,14 (0,03 - 0,72), médiane 0,13 |
| Clo / met | non donnés | clo 0,65 (0,39 - 1,09) / met 1,28 (0,9 - 1,8) |
| Sensation thermique | votes plutôt du côté frais | moyenne -1,04 (-3 à +2) |
| Acceptabilité | majorité acceptable | 247 acceptable / 30 unacceptable (89 %) |
| Préférence | préfèrent plus frais ou pas de changement | 165 no change / 79 cooler / 33 warmer |

## Écarts publi/base
- Bâtiments : 5 dans l'article, regroupés en un seul building_id dans la base.
- Tg : rangée dans tg_h. Tr et To ne sont pas remplies dans la base mais peuvent être recalculées à partir de tg_h, ta et vel.
- Genre : présent dans la base (171 F / 106 H), absent de l'article.
- Saison et année : « summer 2003 » dans la base, non précisées dans l'article.

## Limites / regard critique
- Article de conférence court : saison, dates, HR, vitesse d'air, clo et met ne sont pas détaillés.
- Climatisation seule, vitesse d'air faible (médiane 0,13 m/s) : peu utile pour l'effet du mouvement d'air, mais les votes d'acceptabilité et de préférence du mouvement d'air dans la base peuvent servir
- Tg seulement dans tg_h, Tr et To vides : il faut recalculer Tr 
- 5 bâtiments fusionnés en un seul identifiant : impossible d'étudier l'effet du bâtiment
- Pas de timestamp ni de subject_id
- L'article met surtout l'accent sur les facteurs sociaux et l'énergie, pas sur l'analyse détaillée des mesures

<img width="388" height="542" alt="image" src="https://github.com/user-attachments/assets/eecc6787-9485-4dc7-b549-04d553b6e4b5" />
<img width="266" height="777" alt="image" src="https://github.com/user-attachments/assets/e6771f52-4634-4c00-8836-e74098bbc251" />
<img width="335" height="335" alt="image" src="https://github.com/user-attachments/assets/427c8af2-df75-40ec-84d5-a2a8674b8296" />

```
