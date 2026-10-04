# 015 - Building_ID: [558, 559] - "contributor": Michael Adebamowo
**Année : 2010 - Titre :** Indoor thermal comfort for residential buildings in hot-dry climate of Nigeria
*(Proceedings of Conference: Adapting to Change: New Thinking on Comfort, Cumberland Lodge, Windsor, UK)*

## Conclusion
Article et données ne correspondent pas : la base contient plus de votes (468) que l'article (412) → soit des données ajoutées après la publication, soit une erreur de saisie dans la base.

## Revue :
Auteurs : O. K. Akande et M. A. Adebamowo (2010) \
Pays : Nigeria \
Villes : Bauchi (Liman Katagum) \
Climat (Köppen) : chaud-sec selon l'article (« hot-dry climate ») \
Saison étudiée : hot-dry ; rainy \
Type de bâtiment : logements \
Nombre de bâtiments : 68 \
Genre : 100 F (48,5 %) / 106 H (51,5 %) \
Âge : de 31 à 49 ans \
Types de ventilation : NV (79 % des logements) et ventilateurs (21 %) \
Étude de la vitesse d'air ? : Oui (fenêtres pour la NV, ventilateurs)

Nombre de votes : 412 \
Nombre de sujets / de votes : 206 personnes × 2 saisons = 412 votes

<!-- Capture du tableau de l'article -->
<img width="657" height="214" alt="image" src="https://github.com/user-attachments/assets/35483d96-97a7-471e-b500-eceb65ea25ad" />

--------------------------------------------------------------------------

## Data base :

Villes : Bauchi, Nigeria \
Années des données : 2009 (métadonnées), pas de timestamp \
Climat : tropical wet savanna (Aw) \
Saison étudiée : winter 320 ; spring 148 \
Type de bâtiment : multifamily housing (logement) \
Nombre de bâtiments : 2 (558 : 149 votes ; 559 : 345 votes) \
Genre : 111 F / 357 H \
Types de ventilation : naturally ventilated 468

Nombre de votes : 468 \
Nombre de sujets / de votes : pas de subject_id → impossible de compter les sujets

### Variables disponibles :

Température de l'air dans la zone occupée "ta" : 100 % \
Température extérieure "t_out" : 98,9 % \
Humidité relative "rh" : 98,3 % \
Humidité extérieure "rh_out" : 0 % \
Température de globe "tg" : 0 % \
Température radiante "tr" : 0 % \
Vitesse d'air "vel" : 91 % \
Préférence de mouvement d'air "air_movement_preference" : 84,4 % \
Isolation vestimentaire intrinsèque "clo" : 0 % \
Taux métabolique "met" : 0 % \
Activité : 0 % \
Fonction du bâtiment : OK

<img width="325" height="317" alt="image" src="https://github.com/user-attachments/assets/a49ea7b1-be82-43ee-92b6-12d98ce008a4" />
<img width="374" height="380" alt="image" src="https://github.com/user-attachments/assets/2a979260-0318-4d71-8984-6ff8d1b48296" />

-------------------------------------------------------------------
## Comparaison
| Variable | Dans la publi | Dans la base ASHRAE |
|---|---|---|
| Nombre de votes | 412 (206 × 2 saisons) | 468 |
| Bâtiments | 68 logements | 2 building_id |
| Genre | 100 F / 106 H | 111 F / 357 H |
| Saisons | hot-dry / rainy | winter 320 / spring 148 |
| Climat | hot-dry | tropical wet savanna (Aw) |
| Ventilation | NV 79 % + ventilateurs 21 % | 100 % naturally ventilated |
| Ta | voir capture | 100 % rempli |
| T_out | voir capture | 98,9 % |
| RH | voir capture | 98,3 % |
| RH_out | voir capture | 0 % |
| Tg / Tr | voir capture | 0 % |
| Vel | mesurée | 91 % |

## Écarts publi/base
- **Votes** : 468 dans la base contre 412 dans l'article (+56).
- **Genre** : 357 hommes dans la base, alors que l'article n'a que 206 participants au total → incohérence nette (le genre est mal codé, ou une même personne compte plusieurs votes).
- **Bâtiments** : 68 logements regroupés en 2 building_id → la base ne garde pas le détail par logement.
- **Saisons** : étiquettes winter/spring à faire correspondre à hot-dry/rainy, et la répartition 320/148 n'est pas équilibrée alors que l'article donne 206 + 206.
- **Ventilation** : les 21 % de logements avec ventilateur n'apparaissent pas (tout est classé NV).
- **Climat** : l'article dit « hot-dry », la base « tropical wet savanna » (Aw) → Bauchi est en limite entre Aw et BSh.

## Résultats clés
- 

## Limites / regard critique
- Pas de clo, de met, de tg ni de tr → PMV impossible à calculer, palier max 1.
- Pas de timestamp ni de subject_id → impossible de reconstituer les 206 personnes et leurs 2 votes.
- Les écarts de votes et de genre rendent ces données peu fiables : à utiliser avec prudence ou à écarter.

```
<!-- Coller ici la sortie du notebook : % de remplissage par variable -->
```
