# 020 - Building_ID: [789, 797] - "contributor": Antonio Augusto Xavier
**Année : 2000 - Titre :** Predição de conforto térmico em ambientes internos com atividades sedentárias – Teoria física aliada a estudos de campo
*(Prédiction du confort thermique dans les ambiances intérieures à activité sédentaire – théorie physique et études de terrain. Thèse de doctorat, Universidade Federal de Santa Catarina, Florianópolis)*

> PDF : Predição de conforto térmico em ambientes internos com atividades sedentárias - Teoria física aliada.pdf

## Conclusion
Les données correspondent à la thèse, mais **ce ne sont pas des votes individuels**. Chaque ligne de la base = 1 jeu de mesures (mesure d'ambiance + **moyenne** des sensations, clo et met des personnes présentes). Brasília : 24 lignes = 24 jeux de mesures de l'Annexe B. Recife : 27 lignes = 27 jeux de mesures. Les 51 « votes » sont en réalité 51 moyennes de groupe, inutilisables comme des votes individuels.

## Revue :
Auteurs : Antonio Augusto de Paula Xavier (thèse dirigée à l'UFSC, 2000) \
Pays : Brésil \
Villes : Florianópolis (non tropical), **Brasília** et **Recife** (tropicales, les seules dans notre base) \
Climat (Köppen) : Brasília Aw (savane tropicale) ; Recife As/Am (tropical humide) ; Florianópolis Cfa \
Saison étudiée : toutes les saisons de 1997 à 1999 sur l'ensemble de l'étude. Brasília : **28 au 30 avril 1998** (automne austral). Recife : **17 au 19 novembre 1999** (printemps austral) \
Type de bâtiment : bureaux climatisés (Brasília : Banque centrale du Brésil ; Recife : Caixa Econômica Federal, salles de saisie, travail de jour et de nuit). Salles de classe en ventilation naturelle seulement à Florianópolis \
Nombre de bâtiments : 7 sur toute l'étude (Eletrosul, SESI, hôpital universitaire, UFSC, ETFSC, Banque centrale, Caixa Econômica) → **1 à Brasília + 1 à Recife** \
Genre : adultes de 18 à 50 ans, « des deux sexes », pas de répartition F/H donnée pour Brasília et Recife (le sous-échantillon pour le métabolisme : 15 F / 15 H) \
Types de ventilation : bureaux = climatisation centrale ; salles de classe (Florianópolis) = ventilation naturelle \
Étude de la vitesse d'air ? : vitesse mesurée (station BABUC-A : Ta, Tg, HR, vitesse), utilisée comme entrée du bilan thermique, pas étudiée en soi

Nombre de votes : toute l'étude = 279 jeux de mesures, 3 521 jeux de données personnelles, 841 jeux de caractéristiques individuelles \
Nombre de sujets / de votes : Brasília = 24 jeux de mesures (172 présences cumulées) ; Recife = 27 jeux de mesures (394 présences cumulées). Une même personne est comptée à chaque mesure horaire → nombre de personnes réel inconnu

Échelle de sensation : 7 points, de −3 (très froid) à +3 (très chaud), ISO 10551

<!-- Capture Annexe B (Tableau B.1, p. 187-192) : lignes 66-89 Brasília, 253-279 Recife -->

--------------------------------------------------------------------------

## Data base :

Villes : Brasília (24) ; Recife (27) \
Années des données : 2000 dans les métadonnées (= année de la thèse ; mesures en réalité 1998 et 1999). Pas de timestamp \
Climat : Brasília = tropical wet savanna (Aw) ; Recife = tropical monsoon (Am) \
Saison étudiée : autumn 24 (= Brasília) ; spring 27 (= Recife) \
Type de bâtiment : office (51) \
Nombre de bâtiments : 2 (789 = Brasília ; 797 = Recife) \
Genre : vide (0 %) \
Types de ventilation : air conditioned (51)

Nombre de votes : 51 \
Nombre de sujets / de votes : 51 lignes = 51 moyennes de groupe (pas de subject_id)

### Variables disponibles :

Température de l'air dans la zone occupée "ta" : 100 % \
Humidité relative "rh" : 100 % \
Température de globe "tg" : 0 % \
Température radiante "tr" : 100 % (probablement calculée à partir de Tg) \
Vitesse d'air "vel" : 100 % (sans les 3 hauteurs) \
Isolation vestimentaire intrinsèque "clo" : 100 % (moyenne du groupe) \
Taux métabolique "met" : 100 % (moyenne du groupe) \
Activité : 0 % \
Fonction du bâtiment : office \
Sensation thermique : 100 % (moyenne du groupe) ; PMV, PPD et SET : 100 % (calculés) \
t_out, rh_out, préférence, acceptabilité, fan, window, âge, genre : 0 %

-------------------------------------------------------------------
## Comparaison
| Variable | Dans la publi | Dans la base ASHRAE (moy. / min – max) |
|---|---|---|
| Lignes Brasília | 24 jeux de mesures (28-30/04/1998) | 24 (autumn) |
| Lignes Recife | 27 jeux de mesures (17-19/11/1999) | 27 (spring) |
| Unité d'une ligne | moyenne des personnes présentes | traitée comme 1 vote |
| Ta Brasília (°C) | zone de confort 21,58 – 22,87 ; optimum 21,68 | 23,0 (20,5 – 25,2) |
| Ta Recife (°C) | 22,75 = moins d'insatisfaits (≈ 52 %) | 25,55 (23,6 – 28,4) |
| Tr (°C) | non donnée directement (calculée à partir de Tg) | Brasília 24,05 · Recife 26,98 |
| RH Brasília (%) | confort entre 62 et 100 % ; optimum ≈ 83 % | 60,9 (54,4 – 69,1) |
| RH Recife (%) | — | 60,2 (48,5 – **99,7**) |
| Vel (m/s) | mesurée (BABUC-A) | Brasília 0,16 (0,08 – 0,23) · Recife 0,12 (0,02 – 0,34) |
| Tg | mesurée | 0 % |
| T_out / RH_out | non relevés | 0 % |
| Genre | « deux sexes » | 0 % |

## Écarts publi/base
- **Nature des données** : la base présente 51 « votes », la thèse décrit 51 moyennes de groupe (1 à 24 personnes par mesure) La sensation, le clo et le met sont des moyennes, pas des votes individuels
- **Dates** : la thèse donne date et heure pour chaque mesure, la base n'a aucun timestamp ; l'année 2000 est celle de la thèse, pas celle des mesures (1998 et 1999)
- **Tg** : mesurée dans la thèse, absente de la base (seule Tr)
- **Recife** : RH max 99,7 % dans un bureau climatisé
- **Climat Recife** : « tropical monsoon » (Am) dans la base, souvent classé As
- Le reste de Xavier (Florianópolis, 7 building_id) est classé « humid subtropical »  hors tropical

## Résultats clés
- **Brasília** : optimum 21,68 °C, zone de confort très étroite (21,58/22,87 °C), forte sensibilité au froid ; HR entre 62 et 100 %
- **Recife** : 52 % d'insatisfaits (à 22,75 °C), toujours au-dessus de la limite de 34 % fixée par l'auteur
- L'auteur attribue ces deux cas à la **charge mentale** du travail (salle des marchés à la Banque centrale, saisie sous forte supervision à Recife), pas au climat

## Limites / regard critique
- Données agrégées pas individuelle, effectif réel inconnu = biais si on les mélange avec des votes individuels du reste de la base
- Échantillon tropical très petit (51 lignes, 2 bâtiments, 3 jours chacun) et climatisé uniquement rien sur la ventilation naturelle ni les ventilateurs en climat tropical
- Vitesses d'air faibles (≤ 0,34 m/s)
- L'auteur reconnaît un facteur non mesuré (charge mentale) qui fausse les résultats de Brasília et Recife

<img width="273" height="270" alt="image" src="https://github.com/user-attachments/assets/b0125d4e-6669-4e7d-ab40-833367317f13" />
<img width="334" height="781" alt="image" src="https://github.com/user-attachments/assets/c900a8b5-8f45-4fbc-bb9c-a6ee9d944ae8" />
<img width="341" height="392" alt="image" src="https://github.com/user-attachments/assets/58f0ce46-ac33-4e6a-bbdf-70827868093b" />

```
