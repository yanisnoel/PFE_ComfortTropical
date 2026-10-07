# 014 - Building_ID: [147, ..., 153] - "contributor": Tri Karyono
**Année : 1996 - Titre :** Thermal Comfort in the Tropical South East Asia Region
*(Architectural Science Review, 39(3), p. 135-139 — https://doi.org/10.1080/00038628.1996.9696808)*

> PDF : Karyono - 1996 - Thermal Comfort in the Tropical South East Asia Region.pdf

## Conclusion
**Pas de vitesse d'air ni de Tg dans la base** !! \
Article et base concordent : 596 sujets, 7 bâtiments (5 AC / 1 NV / 1 hybride), genre 345 H / 227 F / 24 non renseignés, identiques. L'article est une revue de littérature sur l'Asie du Sud-Est, la partie Jakarta (2.1) résume l'étude de terrain de l'auteur (1993). Une revue de plusieurs études de terrain pas que Jakarta

## Revue :
Auteurs : Tri H. Karyono (University of Sheffield / BPPT Indonésie) \
Pays : Indonésie (étude de terrain) et revue : Indonésie, Singapour, Thaïlande, Papouasie-Nouvelle-Guinée \
Villes : Jakarta \
Climat (Köppen) : Af (chaud et humide équatorial) \
Saison étudiée : 1993, mois non précisés, mesures entre 10 h et 16 h \
Type de bâtiment : bureaux \
Nombre de bâtiments : 7 (5 AC, 1 VN, 1 hybride) \
Genre : 227 F / 345 H (24 non renseignés) \
Âge : 19 à 53 ans (moyenne 32,6, écart-type 7,4) \
Types de ventilation : AC (5 bâtiments), NV (1), hybride (1) \
Étude de la vitesse d'air ? : **Non**
Instruments :  \
Clo : 0,6 clo (93 % des sujets), 0,8 clo (6,7 %), 1,0 et 1,2 clo (0,3 %) \
Met : 1 met pour tous (assis depuis environ 15 min) \
Échelle de sensation : ASHRAE 7 points (−3 froid, +3 chaud)

Nombre de votes : 596 \
Nombre de sujets / de votes : 596 sujets, 1 vote chacun

<img width="771" height="637" alt="image" src="https://github.com/user-attachments/assets/14c2eb83-1cfc-44b5-bfcf-bc7de653a5bd" />

--------------------------------------------------------------------------

## Data base :

Villes : Jakarta (596) \
Années des données : 1993 (timestamps du 19 avril au 18 juin 1993, 22 dates) \
Climat : wet equatorial (Af) \
Saison étudiée : cool/dry (596) \
Type de bâtiment : office (596) \
Nombre de bâtiments : 7 (147 à 153) \
Genre : 227 F / 345 H (24 non renseignés = gender 96 %) \
Types de ventilation : air conditioned 458 (147 à 151), naturally ventilated 97 (152), mixed mode 41 (153)

Nombre de votes : 596 \
Nombre de sujets / de votes : 596 (subject_id 100 %)

### Variables disponibles :

Température de l'air dans la zone occupée "ta" : 100 % \
Humidité relative "rh" : 100 % \
Température de globe "tg" : 0 % \
Température radiante "tr" : 100 % (**recalculée** à partir de To et Ta) \
Vitesse d'air "vel" : 0 % \
Isolation vestimentaire intrinsèque "clo" : 96 % \
Taux métabolique "met" : 100 % \
Activité : 0 % \
Fonction du bâtiment : office \
Autres : top 100 % / t_out et rh_out 100 % / t_out_isd 100 % / t_mot_isd 60,9 % / âge 82 % / sensation thermique 100 % / préférence, acceptabilité, fan, window, pmv, ppd : 0 %

-------------------------------------------------------------------
## Comparaison
| Variable | Dans la publi | Dans la base ASHRAE |
|---|---|---|
| Votes / sujets | 596 | 596 |
| Bâtiments | 7 (5 AC, 1 NV, 1 hybride) | 7 (5 AC, 1 NV, 1 MM) |
| Genre | 345 H / 227 F / 24 manquants | 345 H / 227 F / 24 vides |
| Âge | 19 - 53 ans, moy. 32,6 | 82 % rempli |
| Ta (°C) | neutralité 26,4 °C | moy. 26,98 (23 - 32) |
| To (°C) | neutralité 26,7 °C (mesurée, B&K 1212) | top 100 % |
| Teq (°C) | neutralité 25,3 °C | absente |
| Tr (°C) | non mesurée | moy. 27,59 (21 – 33) (visiblement recalculée) |
| RH (%) | mesurée (pression de vapeur 1,8 - 3,0 kPa) | moy. 65,2 (52 - 80) |
| T_out / RH_out | non donnés | valeur unique (27,56 °C) |
| Tg | non mesurée | 0 % |
| Vel | non mesurée | 0 % |
| Clo | 0,6 (93 %) / 0,8 (6,7 %) / 1,0-1,2 (0,3 %) | 96 % rempli, moy. = 0,59 |
| Met | 1,0 pour tous | 100 %, = 1,0 |
| Dates | 1993, 10 h - 16 h | 19/04 au 18/06/1993 |

## Écarts publi/base
- **Aucun écart de chiffres** : votes, bâtiments, ventilation et genre identiques
- **Tr** : absente de l'article (non mesurée) mais 100 % dans la base donc recalculée par les auteurs de la base à partir de To et Ta. Pas mesurée
- **Clo** : 96 % dans la base alors que l'article donne une valeur à tous les sujets = 24 valeurs perdues (les mêmes que pour le genre ?)
- **T_out / RH_out** : non donnés dans l'article, valeur unique dans la base = moyenne climatique ajoutée, pas une mesure au moment du vote
- **Saison** : l'article ne précise pas les mois, base = « cool/dry », avril-juin = début de saison sèche à Jakarta

## Résultats clés
- Température neutre à Jakarta : **26,4 °C Ta / 26,7 °C To / 25,3 °C Teq**
- **Pas de différence nette** de température neutre entre bâtiments en ventilation naturelle et climatisés

## Limites / regard critique
- **Aucune mesure de vitesse d'air** l'étude ne dit rien sur l'effet du mouvement d'air **Inutilisable pour l'axe vitesse d'air**
- Pas de globe, Tr reconstruite
- Ta arrondie au degré
- Clo et met **estimés**, pas mesurés (met = 1 pour tous)
- Un seul bâtiment NV (97 votes) et un seul hybride (41), la conclusion « pas de différence NV/AC » repose sur peu de données

<img width="269" height="793" alt="image" src="https://github.com/user-attachments/assets/11d63398-21a3-4dd6-bdab-9f07ba8d9ac9" />
<img width="256" height="774" alt="image" src="https://github.com/user-attachments/assets/b780b45b-4210-4f60-a59c-8fdcab40b374" />
<img width="225" height="240" alt="image" src="https://github.com/user-attachments/assets/bcdd9dd6-9401-45b6-8ac8-8907078d25d9" />

```
