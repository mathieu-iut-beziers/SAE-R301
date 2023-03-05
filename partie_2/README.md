# Seconde partie : cas d'étude

<link rel="stylesheet" type="text/css" href="style.css">

</br></br></br></br></br></br>

Tables des matieres :

- Contexte
- Notre solution
- Les couts

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

### Explication de ka solution envisagé

</br></br></br>

Afin de répondre à notre problématique, nous avons opté pour une solution de passage de câble souterrain pour raccorder l'immeuble de haut standing à la fibre optique. Nous avons prévu des chambres de tirage pour faciliter le tirage de la fibre optique jusqu'aux immeubles.

Nous avons ajouté deux chambres de tirage supplémentaires. CT2 pour les futurs bâtiments (B1 et B2) ainsi que CT4 pour extension future sur la nouvelle route goudronnée. Pour les bâtiments B3 et B4 , nous avons prévu une longueur de fibre supplémentaire pour permettre la création d'un PM mutuel pour les relier dans le futur. Nous avont fait de même pour les batiments B1 et B2.

Nous avons choisi de tirer uniquement les 4 fibres des opérateurs principaux depuis le NRO pour desservir l'immeuble et les futurs bâtiments. Nous avons également prévu des fourreaux pour permettre le passage de futures fibres en cas de futurs logements. Cette solution est optimale car une fibre peut desservir jusqu'à 128 habitations, ce qui est plus que suffisant pour notre cas.

En résumé, nous avons prévu une solution de passage de câble souterrain avec des chambres de tirage pour raccorder l'immeuble de haut standing à la fibre optique. Nous avons également prévu de faciliter l'installation fibre des différents futurs immeubles. Chaque opérateurs principaux (Orange, SFR, Free, Bouygues Telecoms) possèdera sa fibre dédiée. Cette solution est optimale pour répondre à notre problématique.

<div style="page-break-after: always; visibility: hidden"></div>

Gaine Optique :

    - Chemin Goudronés :

    ```
    - Il faut que la gaine soit mise sous 80cm.
    - Doit être en acier ou en PVC rigide. 
    - Entouré de Sable / de gravier pour la soliditer 
    ```

    - Chemin Sableux :

Longueur :

- NRO -> CT1 = 1125 m
- CT1 -> CT2 = 112.5 m
- CT2-> CT3 = 72.5 m
- CT3 -> CT4 = 207.5 m
- CT4 -> Immeuble standing = 48.5m
Donc NRO -> immeuble = 1566m
Partie goudronnée =

Longueur dans l'allée sablonneuse à creuser et reboucher = 48.5m
Longueur de trottoir à excaver et reboucher = 207.5m
Longueur de fourreau à acheter = 256m
Chambre de tirage à rajouter = 2

Coût matériaux :

Fibre optique G.657.A2 :

- prix : 1.928,62 € HT /km | 2.314,34 € TTC /km
- norme : G.657.A2

On considère un immeuble = 5/6 étages -> 20m de hauteur.
5 * 20 = 100m pour les back-bones
Raccordement par logement (10m)

On estime que aucun logement présent est relié en optique et que les logements déjà existant sont en ADSL.
Il nous faut donc prévoir pour la liaison dans les fourreau et l'avenir :

    Liaison NRO -> PM : 1km
    Liaison PM -> CT1 : 102.5m 
    Liaison CT1 -> CT2 : 112.5m
    Liaison CT2 -> CT3 : 72.5m
    Liaison CT3 -> CT4 : 207.5m
    Liaison CT4 -> Immeuble Standing :  48.5m
    Liaison CT2 -> Future B1 / B2 : 37.5m / 37.5m

  Total longueur fibre optique = 1,6185km -> On prend une marge de +- 20% -> 1.9km

  coût fibre fourreau : 3.628,60 € HT | 4397,24€ TTC
  
    Gain a ajouter : 
     - CT2 -> B1/B2 : 37.5m *2
     - CT3 -> Immeuble Standing : 48.5m

    Total longueur de gaine : 123.5m -> On prend une marge de +-20% -> 148.2m arrondi à 150m
  A raison de 30m pour 96,63 € HT  / 115,96 € TTC :
  
    coût gaine : 483,15€ HT | 579,8 € TTC

Matériel Optique :

ONU * 7 : 64€ HT/unité -> 448€ HT

PTO * 7 : 27,42 € HT/unité -> 191.94€ HT

PBO * 3(1/étage) : 58,77 € HT/unité -> 176,31€ HT



### Budget Optique Total : 

|Matériel|Prix HT|Prix TTC|
|---|---|---|
|Gaine optique (150m)|483,15€|579,80€|
|Fibre Optique (1.9km)|3 628,60€|4 397,24€|
|ONU (x7)|448€|560€|
|PTO (x7)|191,94€|230,32€|
|PBO (x3)|176,31€|211,57|

|Coût Total|HTT|TTC|
|---|---|---|
||4928€ HT|5978,93€ TTC|



Génie civil :

Nettoyer les fourreaux existant.

salaire net ingénieur RT: 154 €
salaire net technicien RT: 106 €
salaire net technicien bâtiment : 98 €
salaire net ouvrier bâtiment : 88 €
salaire net technicien supérieur génie civil: 120 €
salaire net technicien supérieur : 103 €
salaire net technicien supérieur informatique : 110 €
salaire net technicien supérieur réseau : 113 €

salaire brut: 1,28 x salaire net
coût total employeur : 1,3 x salaire brut

D'àpres les étude du marché il faudrait 30min à 1 heure pour 1 mètre de fibre à déployer dans une rue non équipé de goutière. Ce qui signifie creuser, déployer et remblayer.

Pour effectuer ceci il faut compter 1310m x 0.5h = 655h minimum et 1310 x 1h = heure maximum. Donc en moyenne 983 h. Si j'ajoute à ça le temps de pose d'une chambre de tirage au minimum une demie journée et au maximum 2 jours pour les pose les plus compliqué. Je prend en moyenne 1 jours pour la pose, cela mène à 1007h de travail.

## A calculer plus tard l'etude du chantier ingénieurs NOUS

Le technicien supérieur génie civil peut intervenir pour les travaux d'infrastructures de génie civil, notamment la création de tranchées pour le passage des câbles de fibre optique et la mise en place des PM, PBO et PTO. Il peut également superviser les travaux de terrassement et d'installation de poteaux et armoires de rue si nécessaire.

Le technicien supérieur informatique peut intervenir pour l'installation des équipements actifs (switchs, routeurs, etc.) qui permettent d'assurer la connectivité des logements à la fibre optique. Il peut également intervenir pour la configuration et la mise en service des équipements et des réseaux.

Le technicien supérieur réseau peut intervenir pour la mise en place des équipements passifs (câbles, boîtiers de raccordement, etc.) et pour la configuration des réseaux de fibre optique. Il peut également intervenir pour le test et la validation de la qualité de la connexion et de la bande passante.

En supposant une durée totale des travaux de 3 semaines (soit environ 140 heures de travail), nous pouvons estimer le coût total de la main d'œuvre comme suit:

Ingénieur RT (40 heures) : 7 936 € (198,40 € x 45 x 1,3)
Technicien RT (40 heures) : 5 518 € (136,96 € x 45 x 1,3)
Technicien bâtiment (20 heures) : 2 528 € (126,40 € x 25 x 1,3)
Ouvrier bâtiment (60 heures) : 8 579,2 € (112,64 € x 65 x 1,3)

Ensuite, il faudra poser des câbles de type G657A2, qui sont des câbles adaptés pour la desserte d'immeubles. En effet, ces câbles sont plus souples que les câbles standards, ce qui les rend plus facilement installables dans les parties communes d'un bâtiment. Ils ont également une meilleure résistance à la courbure, ce qui permet de les courber sans risquer de les endommager. Il est donc judicieux d'utiliser ce type de câble pour la desserte des logements dans l'immeuble.

Pour l'étude préliminaire, on peut estimer le temps nécessaire à environ 40 heures d'ingénieur RT et 20 heures de technicien RT, soit un coût total d'environ 8 820 euros. Pour la partie génie civil du chantier, il faudra environ 400 heures de travail d'un technicien supérieur génie civil, 160 heures d'un technicien bâtiment, 80 heures d'un ouvrier bâtiment et 20 heures d'un ingénieur RT. Cela correspond à un coût total d'environ 49 200 euros.

En prenant en compte l'ensemble des coûts, on peut estimer que le projet coûtera environ 80 000 euros, avec une durée totale d'environ 4 semaines pour la partie génie civil

Bureau d'étude : 50 heures d'ingénieur RT à 154 €/jour, soit 7 700 €.
Génie civil : 200 heures de technicien supérieur
