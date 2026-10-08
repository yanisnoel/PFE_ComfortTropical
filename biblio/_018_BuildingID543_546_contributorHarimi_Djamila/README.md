# 018 - Building_ID: [543, ..., 546] - "contributor": Harimi Djamila
**Année : 2020 - Titre :** Evaluating assumptions of scales for subjective assessment of thermal environments – Do laypersons perceive them the way, we researchers believe?

> PDF : Schweiker et al. - 2020 - Evaluating assumptions of scales for subjective assessment of thermal environments.pdf

## Conclusion
PAS QUE TROPICAL / VITESSE AIR PARCIELLE / PEU DE VERIF POSSIBLE PAPIER/BASE
Étude multi-pays (26 pays, 8 225 questionnaires) pas sur l'étude de climat pur et tropical. Seule la partie Malaisie (Kota Kinabalu, 171 votes, 4 salles de classe climatisées). Les valeurs de l'article sont globales tous pays mélangés donc pas comparables directement. 

## Revue :
Auteurs : M. Schweiker et al. / Partie Malaisie : Djamila Harimi \
Pays : 26 pays (nous 1 Malaisie) \
Villes : nombreuses villes du monde \
Climat (Köppen) : tous les climats \
Saison étudiée : au moins 2 saisons par ville. Malaisie : non précisé dans l'article \
Type de bâtiment : salles de cours (questionnaires distribués en fin de cours élèves assis depuis au moins 30 min) \
Nombre de bâtiments : 00 \
Genre : 46,3 % F / 51,6 % H sur l'ensemble des pays (0,3 % autre, 1,8 % sans réponse) \
Âge : étudiants, 45 % ont moins de 21 ans et 43,9 % entre 21 et 25 ans \
Types de ventilation : non précisé \
Étude de la vitesse d'air ? : non elle n'a été relevée que pour 2 101 votes sur 8 189

Méthode : questionnaire papier, les participants placent les termes des échelles (sensation, confort, acceptabilité), ils donnent aussi leur sensation, leur confort et leur acceptabilité au moment du questionnaire \
Règles de collecte : au moins 100 répondants par ville, au moins 2 saisons, au moins 50 par saison s'il y a plus de 2 saisons, chaque personne ne répond qu'une fois.

Nombre de votes : 9 111 questionnaires distribués, 8 225 analysés \
Nombre de sujets / de votes : 1 questionnaire par personne. Répartition par pays non donnée

<img width="835" height="340" alt="image" src="https://github.com/user-attachments/assets/16e710e4-8df8-4d1f-b5f3-b0aa543a6095" />


--------------------------------------------------------------------------

## Data base :

Villes : Kota Kinabalu \
Années des données : 2017 et 2018 (4 dates : 15/12/2017, 17/05/2018, 18/05/2018, 01/11/2018) \
Climat : tropical rainforest (Af) \
Saison étudiée : cool/dry 98 ; hot/wet 73 \
Type de bâtiment : classroom (171) \
Nombre de bâtiments : 4 (543 à 546) \
Genre : 88 F / 82 H / 1 non défini \
Types de ventilation : air conditioned (171)

Nombre de votes : 171 \
Nombre de sujets / de votes : 171 (subject_id 100 %)

### Variables disponibles :

Température de l'air dans la zone occupée "ta" : 100 % (une seule valeur par salle) \
Humidité relative "rh" : 69,6 % (manque pour le bâtiment 546) \
Température de globe "tg" : 0 % (tg_h, tg_m, tg_l aussi à 0 %) \
Température radiante "tr" : 0 % \
Vitesse d'air "vel" : 48,5 % (seulement bâtiments 543 et 545) \
Isolation vestimentaire intrinsèque "clo" : 0 % \
Taux métabolique "met" : 0 % \
Activité : activity_10, 20, 30 à 100 % ; activity_60 à 57,3 % \
Fonction du bâtiment : classroom \
Autres : thermal_sensation, thermal_preference, thermal_acceptability 100 % ; t_out_isd, rh_out_isd, t_mot_isd 100 % (station météo) ; fan, window, door, blind_curtain, heater 100 % ; t_out et rh_out 0 % ; âge 0 %

-------------------------------------------------------------------
## Comparaison
| Variable | Dans la publi (tous pays) | Dans la base ASHRAE (Malaisie) |
|---|---|---|
| Nombre de votes | 8 225 | 171 |
| Genre | 46,3 % F / 51,6 % H | 51 % F / 48 % H |
| Ta (°C) | 17,4 - 33,3 (1 % - 99 %) | 25,7 - 28,5, dans la plage |
| RH (%) | 18 - 82 | 64 - 72,8, dans la plage |
| Vel (m/s) | 0,0 - 0,7 | 0,10 - 0,15, dans la plage |
| T_out | 8 189 valeurs | t_out vide, t_out_isd 100 % |
| RH_out | 8 189 valeurs | rh_out vide, rh_out_isd 100 % |
| Tg | non mesurée | 0 % |

## Écarts publi/base
- Batiment : l'article compte 5 en Malaisie, la base 4. Les bâtiments 808 et 809 du même contributeur (100 votes, 2014, type « others ») ne sont pas les données manquantes : dates et type de bâtiment différents
- Mesures : une seule valeur de Ta, d'HR et de vitesse par salle. Ce sont des mesures d'ambiance, pas par votes
- HR manquante pour le bâtiment 546, vitesse manquante pour 544 et 546
- T_out et RH_out : relevées dans l'étude (station météo proche) mais rangées dans t_out_isd et rh_out_isd au lieu de t_out et rh_out
- Fenêtre : window = 1 pour 169 votes alors que les salles sont classées climatisées. Si 1 veut dire « ouverte », c'est incohérent avec une salle climatisée
- Ventilateurs : fan = 1 pour 54 votes, non mentionné dans l'article.
- Aucune valeur propre à la Malaisie dans l'article, sauf la phrase sur les 5 recherches/bats.

## Résultats clés
- interpréter les votes de la même façon dans tous les pays peut fausser les comparaisons entre études.

## Limites / regard critique
- L'article porte sur les échelles, pas sur le confort lui-même 
- Pas de mesure individuelle, pas de Tg, pas de clo ni de met
- 4 études, une valeur de Ta par salle : pas de variabilité de Ta à l'intérieur
- Climatisation seulement et vitesse d'air de 0,10 à 0,15 m/s

<img width="387" height="676" alt="image" src="https://github.com/user-attachments/assets/979df80f-c759-414e-aa33-17bfed8bc257" />
<img width="247" height="781" alt="image" src="https://github.com/user-attachments/assets/ba7b8919-5021-4578-8774-7b5b6fad2da2" />
<img width="315" height="323" alt="image" src="https://github.com/user-attachments/assets/f5fd6d2d-ba70-46ce-8330-22e91f0ad60b" />

```
