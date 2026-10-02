---
sidebar_position: 4
title: Manuel IC-AC
description: Contrôleur IC-AC des entrées d'air pour les locaux d'élevage avec un
  courant de sortie admissible jusqu'à 2A
keywords:
- eletor IC-AC
- contrôleur des entrées d'air
- contrôleur climatique
- contrôleur de ventilation de porcherie
- contrôleur de microclimat
- contrôleur pour porcheries
- ventilation de porcherie
- contrôleur pour locaux de post-sevrage
---


# Contrôleur IC-AC

  Contrôleur d'actionneurs et de systèmes de levage des entrées d'air utilisant des moteurs AC à rotation droite/gauche avec un potentiomètre pour la lecture de la position actuelle. Le contrôleur convertit le signal 0-10V en niveau d'ouverture des entrées d'air et permet également une commande manuelle.

## Paramètres et caractéristiques :  
- Modes de fonctionnement :
  - MANUAL – commande manuelle à l'aide des touches « + », « - » ;
  - AUTO – fonctionnement automatique dans la plage étalonnée, proportionnel au signal 0-10V ;
  - SECOURS – en cas de perte du signal de commande, les entrées d'air s'ouvrent au niveau défini en pourcentage ; 
- Sortie relais (droite/gauche) 2A ;
- Signal de commande : 0-10V ;
- Possibilité d'inversion du signal de commande ;
- Mesure de la position à l'aide d'un potentiomètre 1-100kΩ ;
- Hystérésis et durée de moyennage des relevés programmables ; 
- Boîtier étanche IP56 ;
- Tension d'alimentation 230VAC 50Hz ;
- Menu en langue : 
  - polonaise
  - anglaise
  - ukrainienne
  - russe

# Installation du contrôleur  
:::danger 
Lors de l'installation de l'appareil, il est impératif de couper l'alimentation électrique, car la tension présente sur certains composants est dangereuse pour la vie et la santé. Il est recommandé de confier l'installation à une personne qualifiée.
:::

## Choix de l'emplacement de montage  

  L'emplacement de montage doit être choisi de manière rationnelle, en veillant à ce que l'appareil soit facilement accessible aux personnes autorisées, mais inaccessible aux animaux et aux enfants. Il convient également de tenir compte des conditions climatiques : l'appareil doit fonctionner dans une plage de températures de -10°C à 40 °C, dans un endroit non exposé au soleil.

# Montage

L'appareil peut fonctionner dans des conditions climatiques agressives. Correctement monté, l'appareil résiste aux effets nocifs de l'environnement. 

  Lors du montage, il convient de prêter attention aux points suivants : 
- le couvercle doit être serré à l'aide de toutes les vis,
- les câbles utilisés pour raccorder l'appareil doivent avoir une section circulaire,
- après le raccordement du câble, les presse-étoupes doivent être serrés afin d'assurer l'étanchéité et l'immobilisation du câble ; l'utilisation de silicone est recommandée,
- les passages de câbles (presse-étoupes) inutilisés doivent être obturés,
- la partie inférieure du boîtier doit être fixée sur un mur plat à l'aide de 4 chevilles à expansion.


# Raccordement électrique  

:::danger 
Avant de raccorder le système, assurez-vous que l'alimentation est coupée !
:::

  Après avoir dévissé l'appareil, retirez le panneau avant. Pour ce faire, débranchez la nappe du connecteur repéré P1. Faites passer les câbles par les presse-étoupes en caoutchouc, puis procédez à leur raccordement. Le raccordement doit être effectué conformément à la description. Les bornes du contrôleur sont présentées sur la figure ci-dessous.

![Raccordement](./img/ic-acpołącz.png)

## Raccordez l'alimentation 230V AC provenant du tableau de distribution aux bornes suivantes :  
 - **Connecteur L** borne de phase. L'utilisation d'un disjoncteur de protection contre les surintensités (de type « S » B3) et de parafoudres est obligatoire.  
 - **Connecteur N** borne de neutre.  
 - **Connecteur PE** borne de protection.

## Sortie vers l'actionneur : 
 - **Connecteur L** à relier par un câble au connecteur C afin d'alimenter les relais.  
 - **Connecteur N** borne de neutre de l'actionneur.  
 - **Connecteur PE** borne de protection de l'actionneur – boîtier.  
 - **Connecteur NO** borne de l'actionneur dans le sens d'ouverture des entrées d'air.  
 - **Connecteur NC** borne de l'actionneur dans le sens de fermeture des entrées d'air.
 - **Connecteur du potentiomètre** – à raccorder conformément aux indications du schéma de l'actionneur. La polarité de l'alimentation du potentiomètre doit être choisie de manière à ce que les unités de position augmentent lors de l'ouverture des entrées d'air et diminuent lors de leur fermeture. Dans le cas contraire, inversez les fils de l'alimentation du potentiomètre.  
 - **Connecteur In** – à raccorder au contrôleur afin de fournir le signal de commande aux systèmes de levage.  


# Principe de fonctionnement  

  En mode automatique, le contrôleur convertit le signal de commande de la plage 0-10V en position  correspondante de l'actionneur des entrées d'air. Il est nécessaire d'étalonner l'actionneur aux positions d'ouverture maximale et de fermeture des entrées d'air. Pendant l'étalonnage, veillez à ce que les câbles  allant aux entrées d'air restent constamment tendus. Lors de l'étalonnage, la touche « + » doit ouvrir les entrées d'air et la touche « - » doit les fermer. Dans le cas contraire, inversez les fils sur les bornes NO et NC.
  Les positions lues sur le potentiomètre pour l'ouverture et la fermeture doivent présenter un écart supérieur à 100 unités. Les unités de position lues sur le potentiomètre doivent augmenter lors de l'ouverture des entrées d'air et diminuer lors de leur fermeture. Dans le cas contraire, inversez les fils de l'alimentation du potentiomètre.
  Après un étalonnage correct, le contrôleur est prêt à fonctionner en mode automatique et contrôlera la position de l'actionneur. Un signal de commande inférieur à 1,5V entraîne le positionnement des entrées d'air en position de secours. 

## Utilisation 

  Le contrôleur des entrées d'air peut fonctionner dans l'un des deux modes : manuel ou automatique. Le mode sélectionné est mémorisé et n'est pas affecté par une coupure d'alimentation – lors du rétablissement de l'alimentation, le contrôleur revient au dernier mode utilisé. Le mode actuellement sélectionné est indiqué sur l'afficheur :  
   - **MANUAL** - un appui prolongé sur « + » ou « - » active le mode manuel. Dans ce mode, les entrées d'air sont commandées manuellement par les touches : « + » - ouverture, « - » - fermeture.           
   - **AUTO**   - un appui prolongé sur « Esc » active le mode automatique. Dans ce mode, les entrées d'air fonctionnent automatiquement et sont commandées par le signal 0-10V provenant du connecteur In.

## Fonctions du menu de base  

| MENU                       | Description | 
|:---:                       |:---|
|MANUAL  STOP    POT 539  |  **« Mode d'information »** – du fonctionnement manuel. Informations affichées :  - **STOP** – actionneur immobilisé ;  - **OPEN** – ouverture des entrées d'air après appui sur la touche « + » ;  - **CLOSE** – fermeture des entrées d'air après appui sur la touche « - » ;  - **POT 539** – paramètre de position actuelle de l'actionneur déterminé par le potentiomètre.  •Passage au mode automatique par un appui prolongé sur la touche « Esc »| 
|AUTO  20 % = In 3,70 POT 511       |  **« Mode d'information »**  du fonctionnement automatique. Informations affichées :    **20 %**  Valeur de consigne de la position d'ouverture des entrées d'air    **« = »**   entrées d'air à la position définie    **« – »**    fermeture des entrées d'air jusqu'à la position définie    **« + »**    ouverture des entrées d'air jusqu'à la position définie    **In 3,70**  mesure de la tension de commande aux bornes In     **POT 511**  paramètre de position actuelle de l'actionneur déterminé par le potentiomètre.  Passage au mode manuel par un appui prolongé sur la touche « + » ou « - » | 
|Volets en secours 30 %  |**« Volets en secours »** – définition de la valeur d'ouverture de secours des volets (entrées d'air) en cas de perte du signal de commande. Les entrées d'air s'ouvriront au niveau défini en cas de défaillance du contrôleur ou du câble de signal.| 
|Étalonnage Ouvert 671 -> 311        |**« Étalonnage de l'ouverture »** – l'étalonnage de l'ouverture des entrées d'air s'effectue en réglant leur ouverture maximale (position extrême) à l'aide des touches « + » et « - ». La première valeur affichée représente le dernier réglage enregistré, la seconde la position actuelle de l'actionneur. La touche « Ok » enregistre les réglages saisis en mémoire, « Esc » quitte le mode d'étalonnage sans enregistrement.   | 
|Étalonnage Ferm 281 -> 311      |**« Étalonnage de la fermeture »** – l'étalonnage de la fermeture des entrées d'air s'effectue en réglant leur position minimale à l'aide des touches « + » et « - ». La première valeur affichée représente le dernier réglage enregistré, la seconde la position actuelle de l'actionneur. La touche « Ok » enregistre les réglages saisis en mémoire, « Esc » quitte le mode d'étalonnage sans enregistrement.|  
|Durée de moyennage 5 s       |**« Durée de moyennage »** – durée de moyennage du signal de commande provenant du connecteur In, assurant une protection contre les oscillations à l'entrée de commande.  | 
|Inversion   Non |**« Inversion »** – l'activation de cette fonction adapte le contrôleur au signal de commande 10-0V  | 
|Langue   Polonais |**« Langue »** – choix de la langue du menu  | 
|Hystérésis Pot  5   | **« Hystérésis du potentiomètre »** – une variation du paramètre de position de l'actionneur inférieure à la valeur définie n'est pas prise en compte lors du positionnement. Ce paramètre vise à éliminer les très petits mouvements de l'actionneur ainsi que les perturbations provenant du potentiomètre. | 
 

# Remarques et avertissements  

:::danger 
Lors de l'installation de l'appareil, il est impératif de couper l'alimentation électrique, car la tension présente sur certains composants est dangereuse pour la vie et la santé. Il est recommandé de confier l'installation à une personne qualifiée.
:::

- Afin d'éviter les problèmes d'exploitation de l'appareil, il est obligatoire de prendre connaissance du manuel avant de procéder à l'installation et à l'utilisation. Il est interdit de modifier la construction de l'appareil ou d'effectuer soi-même des réparations. Cela concerne en particulier la modification des éléments et des composants.
- Les opérations de maintenance ou d'entretien doivent être effectuées par du personnel habilité (installateur ou service après-vente du fabricant). Un système d'alarme est obligatoire dans les bâtiments d'élevage à ventilation forcée. 
- Le fabricant de l'appareil décline toute responsabilité pour les dommages causés par une installation incorrecte, une programmation incorrecte des fonctions, les conséquences d'événements fortuits ou des facteurs externes.
- Les paramètres de l'appareil doivent être réglés en fonction des conditions régnant dans le local d'élevage. Ces réglages sont individuels et dépendent de la décision de l'éleveur. Le fabricant se réserve le droit de modifier la construction de l'appareil et son logiciel.  


:::caution
![alt](./img/trash.svg) À la fin de son utilisation, le produit ne doit pas être jeté avec les déchets municipaux non triés, mais doit être éliminé conformément à la réglementation en vigueur (directives DEEE de l'Union européenne 2012/19/UE).  Le produit a été fabriqué conformément aux exigences RoHS (directive de l'Union européenne 2011/65/UE).
:::

<!-- \newpage -->
# Caractéristiques techniques du contrôleur  

|Paramètre                        |	DESCRIPTION      |
|:-----------                    |:---------- |
|Tension d'alimentation alternative|	230VAC 50Hz|
|Courant de sortie maximal|	2A|
|Filtre antiparasite de sortie|	RC|
|Impédance d'entrée|	100kΩ|
|Protection contre les surtensions des entrées et sorties|	OUI|
|Alimentation du potentiomètre|	10VDC|
|Courant maximal des sorties du potentiomètre|	30mA|
|Plage de températures de fonctionnement|	-10 +40oC|
|Dimensions de l'appareil|	20x15x8 cm |
|Indice de protection du boîtier|	IP65|

:::info
Le contrôleur IC-AC est fourni avec :
- 4 chevilles à expansion,
- 2 presse-étoupe PG11,
- 2 presse-étoupe PG9.
:::

