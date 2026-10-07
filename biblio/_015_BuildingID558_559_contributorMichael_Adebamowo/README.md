# 015 - Building_ID: [558, 559] - "contributor": Michael Adebamowo
**Année : 2010 - Titre :** Indoor thermal comfort for residential buildings in hot-dry climate of Nigeria
*(Proceedings of Conference: Adapting to Change: New Thinking on Comfort, Cumberland Lodge, Windsor, UK)*

> PDF : Akande et Adebamowo - 2010 - Indoor Thermal Comfort for Residential Buildings in Hot-Dry Climate of Nigeria.pdf

## Conclusion
Article et base ne correspondent pas. La base contient 468 votes alors que l'article annonce 206 sujets (103 par saison). Le genre ne correspond pas non plus (357 H / 111 F dans la base contre 53 H / 50 F par saison dans l'article). Surtout, les valeurs de la saison des pluies sont très différentes : 22,4 °C de Ta moyenne dans l'article contre 33,0 °C dans la base. Les données de la base ne semblent donc pas être celles décrites dans l'article, ou les saisons ont été mal codées. L'article lui-même a des incohérences internes sur les effectifs.

## Revue :
Auteurs : O. K. Akande (Abubakar Tafawa Balewa University, Bauchi) et M. A. Adebamowo (University of Lagos) \
Pays : Nigeria \
Villes : Bauchi (quartier Liman Katagum, sud de la ville) \
Climat (Köppen) : chaud et sec selon l'article (« hot-dry »). Saison sèche d'octobre à avril, saison des pluies de mai à septembre. HR moyenne de 16,5 % en février à 66,5 % en août \
Saison étudiée : saison sèche et saison des pluies 2009 (mois non précisés) \
Type de bâtiment : logements \
Nombre de bâtiments : 68 logements \
Genre : 100 F (48,5 %) / 106 H (51,5 %), soit 50 F / 53 H par saison \
Âge : moyenne entre 31 et 49 ans (min 16, max 70) \
Types de ventilation : ventilation naturelle. 79 % des logements avec fenêtres seulement, 21 % avec ventilation mécanique (ventilateurs) \
Étude de la vitesse d'air ? : oui, mesurée au thermo-anémomètre numérique à 1,1 m, seulement en saison sèche. Vote sur le mouvement d'air (échelle de -3 « very low » à +2 « breezy »)

Instruments : thermomètres à cristaux liquides (séjour, chambre, extérieur), hygromètres à bulbe sec et humide (intérieur et extérieur), thermo-anémomètre numérique. Relevés 3 fois par jour (7-10 h, 12-15 h, 17-20 h) \
Échelles : sensation ASHRAE 7 points, préférence McIntyre 3 points, humidité 7 points, mouvement d'air, confort global 7 points

Nombre de votes : 206 selon le Tableau 2 (103 saison sèche + 103 saison des pluies) \
Nombre de sujets / de votes : 206 sujets d'après le texte. Incohérence dans l'article : plus loin, il parle de 79 répondants en saison sèche et 100 en saison des pluies

Tableau 3 de l'article (paramètres mesurés) :

| | Saison sèche moy. (max - min) | Saison des pluies moy. (max - min) |
|---|---|---|
| Ta intérieure (°C) | 33,7 (39 - 21) | 22,4 (29 - 18) |
| T extérieure (°C) | 35,7 (42 - 25) | 22,1 (25 - 18) |
| HR intérieure (%) | 50,4 (80 - 28) | 68,4 (75 - 35) |
| HR extérieure (%) | 45,2 (75,3 - 18) | 65,8 (85 - 55) |
| Vitesse d'air (m/s) | 0,13 (0,50 - 0) | non mesurée |

--------------------------------------------------------------------------

## Data base :

Villes : Bauchi, Nigeria \
Années des données : 2009 (métadonnées), pas de timestamp \
Climat : tropical wet savanna (Aw) \
Saison étudiée : winter 320 (associé à Dry Season) ; spring 148 (associé à Rainy Season) \
Type de bâtiment : multifamily housing (logement) \
Nombre de bâtiments : 2 (558 : 149 votes ; 559 : 345 votes) \
Genre : 111 F / 357 H \
Types de ventilation : naturally ventilated 468

Nombre de votes : 468 \
Nombre de sujets / de votes : pas de subject_id, impossible de compter les sujets

### Variables disponibles :

Température de l'air dans la zone occupée "ta" : 100 % \
Température extérieure "t_out" : 98,9 % \
Humidité relative "rh" : 98,3 % \
Humidité extérieure "rh_out" : 0 % \
Température de globe "tg" : 0 % \
Température radiante "tr" : 0 % \
Vitesse d'air "vel" : 91 % \
Isolation vestimentaire intrinsèque "clo" : 0 % \
Taux métabolique "met" : 0 % \
Activité : 0 % \
Fonction du bâtiment : OK \
Autres : thermal_sensation 90,6 % ; thermal_preference 88 % ; air_movement_preference 84,4 % ; thermal_comfort 20,9 % ; âge 99,4 % ; taille 28,2 % ; poids 20,9 % ; fan et window 0 %

<img width="325" height="317" alt="image" src="https://github.com/user-attachments/assets/a49ea7b1-be82-43ee-92b6-12d98ce008a4" />
<img width="374" height="380" alt="image" src="https://github.com/user-attachments/assets/2a979260-0318-4d71-8984-6ff8d1b48296" />

-------------------------------------------------------------------
## Comparaison
| Variable | Dans la publi | Dans la base ASHRAE |
|---|---|---|
| Nombre de votes | 206 (103 + 103) | 468 (320 + 148) |
| Bâtiments | 68 logements | 2 building_id |
| Genre | 50 F / 53 H par saison | 111 F / 357 H |
| Ventilation | NV, 21 % avec ventilateurs | 100 % naturally ventilated, fan 0 % |
| Ta sèche (°C) | 33,7 (21 - 39) | 34,8 (29 - 39) |
| Ta pluies (°C) | 22,4 (18 - 29) | 33,0 (27 - 39) |
| T_out sèche (°C) | 35,7 (25 - 42) | 38,0 (30 - 43) |
| T_out pluies (°C) | 22,1 (18 - 25) | 37,6 (30 - 42) |
| RH sèche (%) | 50,4 (28 - 80) | 69,2 (18,5 - 93) |
| RH pluies (%) | 68,4 (35 - 75) | 70,9 (34 - 93) |
| RH_out (%) | 45,2 sèche / 65,8 pluies | 0 % |
| Tg / Tr | non mesurées | 0 % |
| Vel (m/s) | 0,13 (0 - 0,50), saison sèche seulement | 0,1 (0 - 3,1), les deux saisons |
| Préférence thermique | mesurée (McIntyre) | 88 % |
| Mouvement d'air | vote mesuré | air_movement_preference 84,4 % |
| Confort global | mesuré | thermal_comfort 20,9 % |
| Taille / poids | donnés (Tableau 2) | 28,2 % / 20,9 % |

## Écarts publi/base
- Votes : 468 dans la base contre 206 dans l'article, et la répartition 320 / 148 n'est pas équilibrée alors que l'article donne 103 / 103.
- Genre : 357 hommes dans la base, plus que le nombre total de participants de l'article.
- Saison des pluies : Ta et T_out de la base (33 °C et 37,6 °C) sont environ 11 à 15 °C au-dessus de l'article (22,4 °C et 22,1 °C). Les deux « saisons » de la base ont presque les mêmes valeurs. L'étiquette spring ne correspond probablement pas à la saison des pluies (mars à mai = saison chaude au Nigeria).
- Humidité : en saison sèche, 69,2 % de moyenne dans la base contre 50,4 % dans l'article.
- Vitesse d'air : max 3,1 m/s dans la base contre 0,50 m/s dans l'article. Valeurs présentes en saison des pluies dans la base alors que l'article n'en a pas mesuré.
- RH_out : donnée dans l'article, absente de la base.
- Ventilateurs : 21 % des logements en ont, mais la colonne fan est vide et tout est classé NV.
- Bâtiments : 68 logements regroupés en 2 building_id.
- Climat : « hot-dry » dans l'article, Aw dans la base. Bauchi est à la limite entre Aw et BSh.
- Article : effectifs incohérents entre eux (206 sujets, 103 par saison, puis 79 et 100 répondants).

## Résultats clés
- Température neutre par régression sur les votes : 28,44 °C en saison sèche et 25,04 °C en saison des pluies, soit 3,4 °C d'écart entre les deux saisons.
- Température neutre selon le PMV : 25,1 °C (saison sèche) et 22,4 °C (pluies). Les valeurs réelles sont 3,34 °C et 2,64 °C plus élevées que le PMV.
- Plage de confort en saison sèche : 25,5 à 29,5 °C.
- Votes dans les 3 catégories centrales : 68 % en saison sèche et 51 % en saison des pluies, sous les 80 % demandés par ASHRAE 55. Pourtant 86 % jugent leur confort global acceptable.
- Humidité : 80 % des votes entre très sec et légèrement sec, 85 % voudraient plus d'humidité.
- Mouvement d'air : la majorité vote « very low » ou « low (still) ». Les occupants trouvent qu'il n'y a pas assez d'air.
- Résultats proches d'autres études en climat chaud (de Dear à Singapour 28,5 °C, Busch en Thaïlande 28,5 °C, Adebamowo à Lagos 29,09 °C).
- Freins au confort cités : vêtements, fenêtres trop petites ou pas assez nombreuses, plafonds bas.

## Limites / regard critique
- Article court (actes de conférence), méthode peu détaillée, effectifs contradictoires dans le texte.
- Pas de Tg ni de Tr, pas de clo ni de met dans la base : PMV impossible à recalculer, palier max 1.
- Vitesse d'air mesurée seulement en saison sèche et très faible (0,13 m/s en moyenne), alors que les occupants se plaignent du manque d'air. Intéressant pour l'axe vitesse d'air, mais les données de la base ne sont pas fiables (max 3,1 m/s).
- Pas de timestamp ni de subject_id : impossible de retrouver les 103 sujets ni leurs 2 votes.
- Les valeurs de la saison des pluies dans la base ne correspondent pas à l'article. Ces données sont à écarter, ou à utiliser seulement en saison sèche et avec prudence.

<img width="315" height="370" alt="image" src="https://github.com/user-attachments/assets/6f43b290-8125-434a-bb66-3a88869a8b10" />
<img width="258" height="801" alt="image" src="https://github.com/user-attachments/assets/7ce83a36-fa43-4314-8d0e-f599743b5ae7" />
<img width="280" height="304" alt="image" src="https://github.com/user-attachments/assets/36834715-5dbf-4bde-be26-a3b92fbc3a5e" />

```
