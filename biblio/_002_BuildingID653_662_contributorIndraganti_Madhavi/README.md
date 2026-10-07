# 002 - Building_ID: [653, ... ,662] - "contributor": Indraganti Madhavi
**Année: 2014 - Titre: *Adaptive model of thermal comfort for offices in hot and humid climates of India* 

## Conclusion :
L'article d'Indraganti et al. (2014) regroupe 28 bâtiments, répartis entre Chennai et Hyderabad, pour un total de 6048 votes issus de 2787 sujets. Après application du filtre sur les climats tropicaux de la base ASHRAE II, seules les données de Chennai sont conservées, soit 4 bâtiments et 2907 votes. Les bâtiments de Hyderabad sont exclus car ils sont classés dans un climat hot semi-arid dans la base. Les principales différences entre la publication et la base proviennent donc du filtrage climatique, auquel s'ajoutent des écarts dans la description des saisons, des modes de ventilation et de certaines variables (par exemple tg et tr, absentes dans la base).

## Revue :
Auteurs : Madhavi Indraganti, Ryozo Ooka, Hom B. Rijal, Gail S. Brager\
Pays : India\
Villes : Chennai, Hyderabad\
Climat (Köppen) : non précisé\
Saison étudiée : Hiver, été, SWM, NEM\
Type de bâtiment : Office\
Nombre de bâtiments : 28\
Genre : F / H  630;2157\
Types de ventilation : NV, AC, clim.éteinte\
Étude de la vitesse d'air ? : OK

Nombre de votes : 6048\
Nombre de sujets / de votes : 2787 prs

<!-- Coller ici la capture du tableau de l'article si dispo -->



--------------------------------------------------------------------------

## Data base :

Villes : Chennai, Hyderabad\
Années des données : 2012-2013\
Climat : Tropical wet savanna, (hot semi-arid)\
Saison étudiée : cool/dry; hot/wet\
Type de bâtiment : Office\
Nombre de bâtiments : 10\
Genre : F / H \
Chennai : 870;2037\
Types de ventilation : \
Chennai (4bâtiments): AC, MM, NV\

Nombre de votes :\
Chennai : 2907\
Nombre de sujets / de votes : non renseigné\


### Variables disponibles : 

Température de l'air dans la zone occupée "ta" : 100\
Humidité relative "rh" : 100%\
Température de globe "tg" : 0\
Température radiante "tr" : 0\
Vitesse d'air "vel" : 100\
Isolation vestimentaire intrinsèque "clo" : 100\
Taux métabolique "met" : 100\
Activité : \
Fonction du bâtiment : Office
-------------------------------------------------------------------
## Comparaison 
| Variable | Dans la publi | Dans la base ASHRAE |
|---|---|---|
| Ta | Oui|100% |
| T_out |Oui|t_out 78.5% ; t_out_isd 100% ; t_out_monthly 100% |
| RH|Oui |100% |
| RH_out |Oui |0% |
| Tg |Oui |0% |
| Vel |Oui |100% |
| ... | | |

## Écarts publi/base
- Périmètre : l'article couvre Chennai + Hyderabad (28 bâtiments, 6048 réponses, 2787 sujets) ; avec le filtre tropical wet savanna, il reste Chennai seulement (4 bâtiments : 653 à 656, 2907 votes). Hyderabad (657 à 662) est hot semi-arid dans la base.
- Dans le bloc Data base, Villes / Climat / Nombre de bâtiments (10) incluent Hyderabad, mais Genre (870 F ; 2037 H), Types de ventilation et Nombre de votes (2907) sont ceux de Chennai seul. Chennai seul n'a que de l'AC et du MM (pas de NV).
- Saisons : 4 dans l'article (winter, summer, SWM, NEM) contre 2 dans la base (cool/dry, hot/wet).
Variables : tg et tr vides dans la base, donc palier max 1.

## Résultats clés
-

## Limites / regard critique
-
```
<!-- Coller ici la sortie du notebook : % de remplissage par variable -->
```
