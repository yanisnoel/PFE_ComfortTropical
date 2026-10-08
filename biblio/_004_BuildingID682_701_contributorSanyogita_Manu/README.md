# 004 - Building_ID: [682, ... ,701] - "contributor": Sanyogita Manu
**Année: 2016 - Titre:** Field studies of thermal comfort across multiple climate zones for the subcontinent India Model for

## Conclusion :
La publication regroupe 16 bâtiments répartis dans 5 villes indiennes (Ahmedabad, Bangalore, Chennai, Delhi et Shimla), pour un total de 6330 votes. Après application du filtre sur les climats tropicaux, la base ASHRAE II ne conserve que les bâtiments de Bangalore et Chennai, soit 8 bâtiments et 2029 votes. Les principales différences entre la publication et la base sont donc liées au filtrage climatique. Des écarts apparaissent également dans les saisons étudiées (3 dans l'article contre 4 libellés dans la base) ainsi que dans les variables disponibles, notamment tg et tr, absentes de la base alors qu'elles sont utilisées dans la publication.

## Revue :
Auteurs : Sanyogita Manu, Yash Shukla, Rajan Rawal, Leena E. Thomas, Richard de Dear\
Pays : India\
Villes : Ahmedabad, Bangalore, Chennai, Delhi, Shimla\
Climat (Köppen) : non renseigné\
Saison étudiée : Eté, hiver, mousson\
Type de bâtiment : Bureaux\
Nombre de bâtiments : 16\
Genre : F / H 1977,4353\
Types de ventilation : NV, MM, AC\
Étude de la vitesse d'air ? : OK

Nombre de votes : 6330\
Nombre de sujets / de votes :

<!-- Coller ici la capture du tableau de l'article si dispo -->



--------------------------------------------------------------------------

## Data base :

Villes : Bangalore, Chennai\
Années des données : 2012-2013\
Climat : Tropical wet savanna\
Saison étudiée : Summer, cool/dry, winter, hot/wet\
Type de bâtiment : Office\
Nombre de bâtiments : 8\
Genre : F / H 907;1122\
Types de ventilation : AC, NV

Nombre de votes : 2029\
Nombre de sujets / de votes :


### Variables disponibles : 

Température de l'air dans la zone occupée "ta" : 100\
Humidité relative "rh" : 100\
Température de globe "tg" : 0\
Température radiante "tr" : 0\
Vitesse d'air "vel" : 100\
Isolation vestimentaire intrinsèque "clo" : 100\
Taux métabolique "met" : 100\
Activité : \
Fonction du bâtiment : 

-------------------------------------------------------------------
## Comparaison 
| Variable | Dans la publi | Dans la base ASHRAE |
|---|---|---|
| Ta |Oui |100% |
| T_out |Oui |t_out 72,3%; t_out_isd 43,3%; t_out_monthly 100% |
| RH|Oui |100% |
| RH_out |Oui |0% |
| Tg |Oui |0% |
| Vel |Oui |100% |
| ... | | |

## Écarts publi/base
- Périmètre : l'article annonce 16 bâtiments, 5 villes, 6330 réponses ; la base contient 20 building_id (682 à 701) pour ces 6330 votes. Avec le filtre tropical wet savanna, il reste 8 bâtiments (686 à 693), Bangalore + Chennai, 2029 votes. 
- Variables : la température radiante est calculée à partir de mesures de globe dans l'article, mais tg et tr sont vides dans la base.
- Saisons : 3 dans l'article (été, hiver, mousson) ; la base mélange 4 libellés selon la ville (summer, winter, cool/dry, hot/wet).

## Résultats clés
-

## Limites / regard critique
-
```
<!-- Coller ici la sortie du notebook : % de remplissage par variable -->
```
