---
sidebar_position: 4
title: Notice du bloc d’alimentation DC50W24VB
description: Bloc d’alimentation DC50W24VB  de secours pour le système d’entrées d’air.
keywords:
- eletor IC-AC
- contrôleur d’entrées d’air
- contrôleur climatique
- contrôleur de ventilation de porcherie
- contrôleur de microclimat
- contrôleur pour porcherie
- ventilation de porcherie
- contrôleur pour bâtiment d’élevage
---


# Bloc d’alimentation DC50W24VB

Bloc d’alimentation de secours avec fonction d’ouverture automatique et manuelle des entrées et des sorties d’air. Utilisé pour assurer la sécurité des animaux d’élevage en cas de coupure de l’alimentation ou de défaillance du contrôleur. Après avoir détecté une anomalie, l’appareil déclenche une alarme et ouvre les treuils jusqu’au niveau défini.

## Paramètres et caractéristiques : 
-  Sélecteur de mode de fonctionnement : 
    - MANUAL
    - AUTO.
-  Bouton de réglage du degré d’ouverture des entrées d’air.
-  Standards pris en charge :
    - 0-10, 2-10, 10-0, 10-2.
-  Possibilité d’inversion du signal de commande.
-  Sorties d’alarme NO et NC.
-  Signalisation de la coupure de l’alimentation.
-  Surveillance de la tension de commande 2-10V.
-  Surveillance des courts-circuits des sorties 24VDC.
-  Surveillance des courts-circuits des sorties 0-10V.
-  2 entrée 0-10V.
-  2 sorties 0-10V.
-  Protections électroniques des entrées, des sorties et de la ligne 24V.
-  Batterie d’accumulateurs 24V 4.0 Ah.
-  Boîtier étanche IP65.
-  Tension d’alimentation 85~264VAC 47~63Hz.

# Installation du contrôleur  
:::danger 
Lors de l’installation de l’appareil, l’alimentation électrique doit impérativement être coupée, car la tension présente sur certains composants constitue un danger pour la vie et la santé. Il est recommandé de confier l’installation à une personne qualifiée.
:::

## Choix du lieu de montage  

Le lieu de montage doit être choisi de manière judicieuse, en tenant compte de la facilité d’accès à l’appareil pour les personnes habilitées, tout en le rendant inaccessible aux animaux et aux enfants. Il convient également de tenir compte des conditions climatiques, c’est-à-dire que l’appareil doit fonctionner dans une plage de températures de -10°C à 40 °C, dans un endroit non exposé au soleil. L’air doit pouvoir circuler librement autour de l’appareil.

# Montage  

L’appareil peut fonctionner dans des conditions climatiques agressives. Correctement monté, l’appareil résiste aux effets nuisibles de l’environnement.

### Lors du montage, il convient de prêter attention aux points suivants : 
 - le couvercle doit être serré à l’aide de toutes les vis,
 - les câbles utilisés pour le raccordement de l’appareil doivent avoir une section circulaire,
 - après le raccordement du câble, les presse-étoupes doivent être serrés afin d’assurer l’étanchéité et l’immobilisation du câble ; l’utilisation de silicone est recommandée,
 - les passages de câbles (presse-étoupes) inutilisés doivent être obturés,
 - la partie inférieure du boîtier doit être fixée sur un mur plat à l’aide de 4 chevilles à expansion.


# Raccordement électrique  

:::danger 
Avant de raccorder le système, s’assurer que l’alimentation est coupée !
:::

Après avoir dévissé l’appareil, retirer le panneau avant. Pour ce faire, retirer la nappe du connecteur désigné par P1. Faire passer les câbles à travers les presse-étoupes en caoutchouc, puis procéder à leur raccordement. Le raccordement doit être effectué conformément à la description.

![Raccordement](./img/DC50W24VB.png)

**Alimentation 230V CA :** raccorder à l’alimentation (tableau de distribution). L’utilisation d’un disjoncteur de protection contre les surintensités (de type « S » B6) et de parafoudres de classe « C » est obligatoire. L’appareil peut être alimenté dans une large plage de tensions allant de 85V à 264V et de fréquences allant de 47 à 63Hz, sans incidence sur son fonctionnement.  

**Connecteur In1 et In2** à raccorder au contrôleur afin de fournir le signal de commande aux systèmes de treuils. L’appareil peut prendre en charge deux contrôleurs ou un seul avec des sections d’entrées et de sorties d’air séparées (les bornes I1 et I2 doivent être pontées).  

**Connecteur ALARM** à raccorder à la centrale d’alarme, selon le système – contact fermé (NO et C), contact ouvert (NC et C). L’alarme se déclenche dans les cas suivants :  •disparition de la tension d’alimentation de l’appareil,  •disparition du signal de commande 2-10V sur au moins une des entrées,  •court-circuit du signal de sortie ou valeur de ce signal différente de la valeur mesurée,  •court-circuit sur le bus +24V alimentant les treuils.  

**Connecteur Ouput 1 et Ouput 2** à raccorder à l’actionneur (treuil) de la manière requise pour l’appareil utilisé ; la description du raccordement doit figurer dans la notice de l’actionneur (treuil) concerné.  

**Sélecteur de mode de fonctionnement S1** sélectionner le mode de fonctionnement adapté à l’actionneur (treuil) utilisé. Par défaut, les commutateurs 1,2,3,4,5,6 sont en position off – fonctionnement 2-10V.
 
| Canal 1 | Canal 2| Fonction |
|------|------|----------|
| 1 – off | 4 – off | Mode de fonctionnement dans la plage de signaux 2-10V, une tension de commande inférieure à 1,5V génère une alarme.   |
| 1 – on| 4 – on  | Mode de fonctionnement dans la plage de signaux 0-10V, aucune réaction d’alarme à un signal inférieur à 1,5V.   |
| 2 – off | 5 – off  | Mode de fonctionnement proportionnel, signaux de sortie dans la plage 0-10V ou 2-10V.  |
| 2 – on | 5 – on  | Mode de fonctionnement inversé, signaux de sortie dans la plage 10-0V ou 10-2V.   |
| 3 – off | 6 – off  | Inversion de l’entrée désactivée.  |
| 3 – on | 6 – on   | Inversion de l’entrée activée.   |

# Principe de fonctionnement  

En fonctionnement normal, le bloc d’alimentation de secours alimente les actionneurs (treuils) 24V et charge ou maintient en charge les accumulateurs, qui fourniront l’alimentation en cas de coupure de l’alimentation.  Le sélecteur AUTO/MANUAL définit le mode de fonctionnement de l’appareil.  

**Le mode MANUAL** permet de commander directement les actionneurs (treuils) à l’aide du bouton de réglage situé sur le panneau de l’appareil.  

**Le mode AUTO** – mode de fonctionnement principal, transmet le signal de commande de l’entrée à la sortie, en effectuant le traitement approprié selon les réglages du commutateur « S1 », et surveille le niveau du signal d’entrée.  En cas de détection d’une anomalie sur une entrée donnée, l’appareil applique à sa sortie le signal du bouton de réglage situé sur le panneau avant.  Le relais d’alarme se déclenche dans les cas suivants :  •signal d’entrée trop faible (Uin < 1,5V) – commutateur « S1 » 1-off, 4-off,  •court-circuit du signal de sortie à la masse ou à 24V,  •absence de tension d’alimentation,  •court-circuit de la tension 24V.

## Utilisation 

L’utilisateur sélectionne le mode MANUAL à l’aide du sélecteur et règle, à l’aide du bouton de réglage, le degré d’ouverture des entrées d’air adapté aux besoins – les actionneurs fonctionnent conformément au réglage du bouton. Après avoir terminé le réglage des entrées d’air, sélectionner le mode AUTO à l’aide du sélecteur et laisser l’appareil fonctionner – les entrées d’air se positionneront au niveau requis par le contrôleur de ventilation. En situation d’urgence, les entrées d’air se positionneront conformément au réglage du bouton.  

## Panneau avant 

| MENU                       | Description | 
|:---:                       |:---|
|![Raccordement](./img/paneldcw50.png) |**Voyant POWER** – signale la présence de l’alimentation et la charge des accumulateurs.  1.**Voyant CHECK** – reste allumé en mode automatique lorsque le signal du contrôleur est transmis à la sortie ; clignote lorsque le signal du bouton de réglage est appliqué à la sortie.  2.**OUT 1** – signale les anomalies du canal 1.  3.**OUT 2** – signale les anomalies du canal 2.  4.**AUTO** – mode de fonctionnement automatique.  5.**MANUAL** – mode de fonctionnement manuel.  6.**Bouton de réglage 0%-100%** - sélection du degré d’ouverture des entrées d’air.| 

# Messages d’erreur et d’avertissement

Les messages d’erreur servent à informer l’utilisateur des anomalies de fonctionnement de l’appareil. Les messages d’erreur possibles sont présentés ci-dessous :
 -  Voyant POWER – ne s’allume pas en vert – absence d’alimentation secteur.
 -  Voyant CHECK – clignote en jaune – le signal du potentiomètre est appliqué aux sorties.
 -  Voyant OUT 1 – s’allume en rouge - détection d’une anomalie (absence de signal de commande, court-circuit à la sortie ou court-circuit sur le bus 24VDC) dans le premier canal.
 -  Voyant OUT 2 – s’allume en rouge - détection d’une anomalie (absence de signal de commande, court-circuit à la sortie ou court-circuit sur le bus 24VDC) dans le deuxième canal.

# Remarques et avertissements  

:::danger 
Lors de l’installation de l’appareil, l’alimentation électrique doit impérativement être coupée, car la tension présente sur certains composants constitue un danger pour la vie et la santé. Il est recommandé de confier l’installation à une personne qualifiée.
:::

 - Afin d’éviter les problèmes liés à l’exploitation de l’appareil, il est obligatoire de lire la notice avant de procéder à l’installation et à l’utilisation. Il est interdit de modifier la construction de l’appareil ou d’effectuer des réparations soi-même. Cela concerne en particulier les modifications des éléments et des composants.
 - Les opérations de maintenance ou d’entretien doivent être effectuées par du personnel habilité (installateur ou service après-vente du fabricant). Un système d’alarme est obligatoire dans les bâtiments d’élevage à ventilation forcée. 
 - Le fabricant de l’appareil n’est pas responsable des dommages causés par une installation incorrecte, une programmation incorrecte des fonctions, les conséquences d’événements fortuits et des facteurs externes. Les paramètres de l’appareil doivent être réglés en fonction des conditions régnant dans le local d’élevage.Ces réglages sont individuels et dépendent de la décision de l’éleveur. 
 - Le fabricant de l’appareil se réserve le droit de modifier la construction de l’appareil et le logiciel.
L’appareil comprend une batterie d’accumulateurs ; il convient d’éviter toute décharge excessive, qui pourrait endommager la batterie. 
Un court-circuit entre les bornes de la batterie peut provoquer un incendie.  


:::caution
![texte alternatif](./img/trash.svg) À la fin de son utilisation, le produit ne doit pas être jeté avec les déchets municipaux non triés, mais doit être éliminé conformément à la réglementation en vigueur (directives DEEE de l’Union européenne 2012/19/UE).  Le produit a été fabriqué conformément aux exigences RoHS (directive de l’Union européenne 2011/65/UE).
:::

<!-- \newpage -->
# Caractéristiques techniques du contrôleur  

|Paramètre                        |	DESCRIPTION      |
|:-----------                    |:---------- |
|Tension d’alimentation alternative|	85~264VAC 47~63Hz|
|Tension d’alimentation continue|	120~370VDC|
|Tension de sortie|	27,6VDC|
|Courant de sortie maximal|	1,8A|
|Rendement|	85%|
|Courant maximal des sorties de commande 0-10V|	30mA|
|Courant maximal de la sortie (contact) ALARM|	3A|
|Protection contre les surtensions des entrées et des sorties|	OUI|
|Protection contre les courts-circuits|	Automatique |
|Batterie d’accumulateurs|	4Ah 24V|
|Plage de températures de fonctionnement|	-10 +40oC|
|Dimensions de l’appareil|	20x15x8 cm|
|Indice de protection du boîtier|	IP65|

:::info
Le contrôleur IC-AC est fourni avec :
 - chevilles à expansion - 	4 pièces, 
 - accumulateurs 12V 4Ah - 	2 pièces, 
 - presse-étoupe PG13,5 -	1 pièces,
 - presse-étoupe PG11 -	3 pièces, 
 - presse-étoupe PG9 -	3 pièces.
:::

