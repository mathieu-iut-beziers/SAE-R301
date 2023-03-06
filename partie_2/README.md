# Seconde partie : Cas d'étude

<link rel="stylesheet" type="text/css" href="style.css">

</br></br></br></br></br></br>

Tables des matières :

- Contexte
- Notre solution
- Les coûts (financiers et humains)

</br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br>

Avec la participation de Caubel Aksel, Alleaume Julien et Puig Mathieu.

<div style="page-break-after: always; visibility: hidden"></div>

</br></br></br>

## Contexte

</br></br></br>

Contexte :
Nous sommes confrontés à la problématique de raccorder un immeuble de haut standing à la fibre optique. Cet immeuble est constitué de sept logements répartis sur trois étages (RDC, 1er, 2ème et 3ème). L'immeuble est situé à Metz, en périphérie de la ville, dans une zone arborée où de nombreuses constructions sont prévues, dont au moins deux bâtiments de 18 habitations, un de 12 habitations et un de 8 habitations. Nous devons donc prévoir une infrastructure capable de relier facilement ces futurs bâtiments au réseau.

Objectifs :
Notre objectif est de mettre en place une infrastructure de fibre optique qui permettra de raccorder l'immeuble de haut standing ainsi que les futurs bâtiments de la zone. Pour cela, nous devons prévoir tous les équipements nécessaires pour le raccordement et assurer une facilité de mise en place pour les futurs raccordements.

Équipements nécessaires :
Nous devons prévoir tous les équipements nécessaires pour le raccordement à la fibre optique, tels que les câbles en fibre optique, les boîtiers de raccordement, etc. Nous devons également tenir compte de la capacité du réseau pour supporter la connectivité de plusieurs bâtiments.

Estimation :
Nous devons réaliser une estimation de l'ensemble des coûts pour le déploiement de l'infrastructure de fibre optique. Cette estimation doit comprendre les coûts liés à l'acquisition des équipements, les coûts de main-d'œuvre, les coûts de raccordement, les coûts de maintenance et les coûts liés aux permis et autorisations nécessaires pour la réalisation du projet. Il est important que cette estimation soit précise et réaliste pour assurer la faisabilité du projet.

En résumé, notre problématique est de raccorder un immeuble de haut standing à la fibre optique, ainsi que les futurs bâtiments de la zone. Pour cela, nous devons prévoir tous les équipements nécessaires, réaliser une estimation précise des coûts et garantir une facilité de raccordement pour les futurs bâtiments.

<div style="page-break-after: always; visibility: hidden"></div>

## Solution envisagé

</br></br></br>

Plan envisagé :

</br></br></br>

![plan_envisagé](./img/plan.drawio.svg)

<div style="page-break-after: always; visibility: hidden"></div>

</br></br></br>

### Explication de la solution envisagé

</br></br></br>

Afin de répondre à notre problématique, nous avons opté pour un raccordement de l'immeuble de haut standing à la fibre optique avec des câbles souterrains. Nous avons prévu des chambres de tirage pour faciliter le tirage de la fibre optique jusqu'aux immeubles.

Nous avons ajouté deux chambres de tirage supplémentaires. CT2 pour les futurs bâtiments (B1 et B2) ainsi que CT4 pour l'extension future sur la nouvelle route goudronnée. Pour les bâtiments B3 et B4 , nous avons prévu une longueur de fibre supplémentaire pour permettre la création d'un PM mutuel pour les relier dans le futur. Nous avons fait de même pour les bâtiments B1 et B2.

Nous avons choisi de tirer uniquement les 4 fibres des opérateurs principaux depuis le NRO pour desservir l'immeuble et les futurs bâtiments. Nous avons également prévu des fourreaux pour permettre le passage de futures fibres en cas de futurs logements. Cette solution est optimale car une fibre peut desservir jusqu'à 128 habitations, ce qui est plus que suffisant pour notre cas.

En résumé, nous avons prévu une solution de passage de câble souterrain avec des chambres de tirage pour raccorder l'immeuble de haut standing à la fibre optique. Nous avons également prévu de faciliter l'installation fibre des différents futurs immeubles. Chaque opérateurs principaux (Orange, SFR, Free, Bouygues Telecoms) possèdera sa fibre dédiée. Cette solution est optimale pour répondre à notre problématique.

<div style="page-break-after: always; visibility: hidden"></div>

## Les couts

### Partie optique & matérielle

Nous avons pris en compte les spécificités de la mise en place de la gaine selon le type de chemin. Pour les chemins goudronnés, nous avons prévu que la gaine soit mise sous 80cm de profondeur pour protéger la fibre optique. La gaine sera en acier ou en PVC rigide pour garantir sa résistance. Elle sera également entourée de sable ou de gravier pour assurer sa solidité.

Pour les chemins sableux, nous avons décidé d'enterrer la gaine à 80cm de profondeur, au lieu des 60cm préconisés en cas de futur goudronnage. Cette mesure vise à renforcer la solidité de la gaine et à prévoir d'éventuels travaux de construction ultérieurs.

Nous avons prévu des répartiteurs optiques dans les chambres de tirage CT2 et CT3 pour les futurs raccordements des nouveaux bâtiments. Dans la chambre de tirage CT2, nous avons opté pour un répartiteur optique un vers trois car les deux futurs bâtiments auront leurs propres PM (selon les normes de ZTD). Pour la chambre de tirage CT3, nous avons choisi un coupleur un vers deux car les deux futurs bâtiments de CT3 pourront avoir un PM mutualisé pour les deux bâtiments.

Différentes longueurs utiles pour notre projet :

Point A   | Point B           | Distance a parcourir A <-> B
--------- |----------         |---------
 NRO      | CT1               | 1125 m
 CT1      | CT2               | 112.5 m
 CT2      | CT3               | 72.5 m
 CT3      | CT4               | 207.5 m
 CT4      | Immeuble standing | 48.5 m
 NRO      | Immeuble standing | 1566 m

Prevision des longueurs de fibres :

Point A   | Point B            | Distance de la liaison A <-> B
--------- |----------          |---------
NRO       | PM                 | 1.0km
PM        | CT1                | 102.5m
CT1       | CT2                | 112.5m
CT2       | CT3                | 72.5m
CT3       | CT4                | 207.5m
CT4       | Immeuble Standing  | 48.5m

Étant donné que nous estimons qu'aucun logement n'est actuellement relié en fibre optique, il est nécessaire de prévoir de la fibre pour le raccordement de l'immeuble entier. Nous avons choisi la fibre optique G.657.A2 pour cette liaison, qui coûte 2 314,34 € TTC par kilomètre. Nous avons estimé que la longueur totale de fibre nécessaire sera d'environ 1,6 km, mais nous avons ajouté une marge de sécurité de 20%, soit un total de 1,9 km. Le coût total de la fibre s'élève donc à 4 397,24 € TTC.
  
Prevision des longueurs de fourreau :

Point A   | Point B            | Distance de la liaison A <-> B
--------- |----------          |---------
CT2       | B1                 | 37.5m
CT2       | B2                 | 37.5m
CT3       | CT4 :              | 207.5m
CT4       | Immeuble Standing  | 48.5m

La longueur totale de fourreau nécessaire pour le raccordement de l'immeuble est de 331 mètres. Nous avons ajouté une marge de sécurité de 20% pour tenir compte des éventuels imprévus, soit un total de 397,2 mètres, arrondi à 390 mètres car les tronçons font 30 mètres. Au prix de 115,95 € TTC par tronçon, le coût total des fourreaux est de 1 507,42 € TTC.

Matériel Optique :

Matériel  | Quantité       | Prix unitée   | Total
--------- |----------      |---------      |---------
ONU       | 7              | 76,80€        | 560€
PTO       | 7              | 27,39€        | 191,73€
PBO       | 3 (1/étage)    | 75,10€        | 225,30€
PMImmeuble| 1              | 138€          | 138€

### Budget Optique Total

Donc pour récapituler, voici un tableau résumant les coûts de la solution envisagée :

|Matériel                       |Prix TTC    |
|-------------------------------|----------  |
|Fourreau (397,2m)              | 1 507,42 € |
|Chambre de Tirage (x2)         | 244,44  €  |
|Fibre Optique (1.9km)          | 4 397,24 € |
|ONU (x7)                       | 560 €      |
|PTO (x7)                       | 191,73 €   |
|PBO (x3)                       | 225,30 €   |
|PMImmeuble                     | 138 €      |
|Répartiteur Optique 1*2(x1)    | 10,20 €    |
|Répartiteur Optique 1*3(x1)    | 15,60 €    |
|Coût Total                     | 7289,93 €  |

Ces coûts incluent les coûts des équipements optiques ainsi que les coûts de la fibre optique et des fourreaux nécessaires pour le raccordement ou l'extension du réseau.

<div style="page-break-after: always; visibility: hidden"></div>

### Source des prix

|Matériel                     |Lien|
|---                          |--- |
|Chambre de tirage            |https://www.mypum.fr/reseaux-secs/chambres-regards-et-bornes-telecom/chambres-de-telecommunication/chambres-telecom-beton/produits/P2738?articleId=46728|
|Bobine Fibre                 |https://www.fs.com/fr/products/70220.html|
|Gaine                        |https://www.fs.com/fr/products/70220.html|
|ONU                          |https://www.amazon.fr/Elfcam%C2%AE-Fibre-Optique-Monomode-Ethernet/dp/B0BFFQ2VPN|
|Répartiteur optique 1 vers 3 |https://www.fs.com/fr/products/145746.html?attribute=31852&id=592533|
|Répartiteur optique 1 vers 2 |https://www.fs.com/fr/products/12493.html?attribute=31845&id=592467|
|PTO                          |https://www.cdiscount.com/informatique/cables-connectiques/elfcam-20-mtres-cable-fibre-optique-renforc-sc-a/f-1072030-elf3760325002826.html|

## Partie genie civil

Pour l'étude préliminaire, on peut estimer le temps nécessaire est d'environ 40 heures d'ingénieur RT. Pour réaliser ces tâches : la collecte des données de terrain, l'étude de faisabilité, la conception de l'infrastructure, la préparation des plans et des documents techniques, l'évaluation des coûts et des risques, l'obtention des autorisations réglementaires auprès des autorité local.
Pour la partie génie civil du chantier, il faudra environ 30 heures de travail d'un technicien supérieur génie civil, 20 heures d'un technicien bâtiment et 20 heures d'un technicient RT. Soit un temps 110 heures.

Pour la démolition de la dalle de goudron, la location d'une micropelle d’1 tonne est d'environ 200 € par jour et des autres équipements et l'essence il y en a pour 500€ de plus donc un total de 700€ par jour soit pour une semaine 4900€.

Pour l'évacuation des gravats il y en a pour 500€ de location par jour en moyenne pour un aspirateur à gravats qui vas accélérer les travaux, donc pour 207.5m x 1m x 0.80m = 166 m3 de gravats. 65€ le m3 x par 166m3 = 10790€.

La partie goudronnée est de 207.5m. Pour creusé de 0.80m de profondeur(Norme pour les gaines situésous du goudrons) et installer les fourreaux il faut compter 2 jours pour 50 mètres donc 1 semaine (35 heure) de travail. Pour reboucher la tranché de groudrons on ajoute 22,50€ le mètre carré de bitume soit 207.5m*22.50€ = 4668,75€.

Pour la partie goudronné de 207.5m allant du CT3 au CT4 prendra donc 35 heures, 4668.75€ + (700€*7) = 9568,75€ sans compte les salaires.

Pour l'allée sablonneuse il faut compter 0.80m de profondeur au lieu de 0.50m habituellemment comme la route sera probablement goudronnée, ce qui amène à 16 heures de travails et 1000€ de locations de matériels. Etant donnée que c'est du sable il n'y as pas besoins de deblayer les gravats.

Nettoyer les fourreaux existant afin d'avoir une facilité de tirage pour le projet et future projet. Il y a 1310m d'ancien fourreau à nettoyer cela coutera en moyenne 400€ par 100m ce qui fera un coût de 13,1*400 = 5240€. Durant environs 8 heures.

D'après les étude du marché il faudrait 1 heure pour 100 mètre de fibre, la longueur de fourreaux à déployer étant de 2000m il faudra 20h pour installer et tirer la fibre à travers les nouveaux et anciens fourreaux.

Le temps de pose des chambre de tirage est au minimum d'une demie journée et au maximum 2 jours pour les pose compliqué. Je prend en moyenne 1 jours pour la pose des deux ce qui mène à 14h de travail. Le temps de pose d'un PMI 1/2 journée par un techncient RT et les PTO en 1 journée pour les 7 apaprtements.

La durée total des travaux est estimé à 217 heures soit environ 5 semaines de travaux :

| Poste                             | Heures   | Total    |
| ---                               | ---      | ---      |
| Partie étude                      | 110      |  |
| Technicien RT                     | 35       |    
| Technicien bâtiment               | 16       | 3 185 €  |
| Ouvrier bâtiment                  | 8        | 36 608 € |
| Technicien supérieur génie civil  | 20       | 1 560 €  |
|                                   |          |          |
|                                   |          |          |
|                                   |          |          |
| Total                             | 14       | 76 401€  |

### Cout en main d'oeuvre

| Poste                             | Employés  | Heures | Salaire horaire         | Total    |
| ---                               | ---       | ---    | ---                     | ---      |
| Bureau d'étude : d'ingénieur RT   | 3         | 40     | 154 €  (40 x 1,3 x 3)   | 24 024 € |
| Technicien RT                     | 2         | 40     | 106 €  (40 x 1,3 x 2)   | 11 024 € |
| Technicien bâtiment               | 1         | 25     | 98 €   (25 x 1,3 x 98)  | 3 185 €  |
| Ouvrier bâtiment                  | 4         | 36     | 88 €   (80 x 1,3 x 4)   | 36 608 € |
| Technicien supérieur génie civil  | 1         | 10     | 120 €  (10 x 1.3)       | 1 560 €  |
| Total                             |           |        |                         | 76 401€  |

Les salaires sont calculés en coût total employeur : 1,3 x salaire brut.

### Cout en materielle

Donc pour récapituler, voici un tableau résumant les coûts de la solution envisagée :

|Type de coût                                           |Prix TTC   |
|---------                                              |--------   |
| Location matériel : 5 semaines                        |  4 900€   |
| Evacuation gravats et location camions aspirateurs    |  10 790€  |
| Travaux de la rue CT3 vers CT4                        | 9 568,75€ |
| Travaux chemin de  sable :                            |  1 000€   |
| Nettoyage des fourreaux                               |  5 240€   |
| Prix de l'étude préliminaire et projet civil          |  9 984€   |
| Les salaires :                                        |  76 401€  |

Soit un coût total de 137 483,75€.

### Source materielle

|Matérielle                             |Lien|
|---                                    |---|
|Goudrons                               | https://www.travaux.com/jardin-et-exterieur/guide-des-prix/prix-goudronnage-bitume |
|Gravats                                | https://www.prix-pose.com/evacuation-gravats/ |
|Grillage de Chantier en Plastique Vert | https://prozon.com/barrieres-separateurs/2618-grillage-plastique-h12m-vert-50m.html?gclid=CjwKCAiAu5agBhBzEiwAdiR5tO2CBbo43-yisL6CsN3N7a1Kxtxb4jF32MUEMJvcvl6rwIX5KbFkLxoC0z8QAvD_BwE |
