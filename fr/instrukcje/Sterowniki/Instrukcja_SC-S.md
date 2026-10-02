---
sidebar_position: 2
title: Notice SC-S
description: Régulateur climatique pour locaux d'élevage avec un courant de sortie
  admissible jusqu'à 5A
keywords:
- eletor sc-s
- régulateur de ventilation
- régulateur climatique
- régulateur de ventilation de porcherie
- régulateur de microclimat
- régulateur pour porcherie
- ventilation de porcherie
- régulateur pour locaux d'élevage des jeunes animaux
---


# Régulateur SC-S

Régulateur climatique à microprocesseur appartenant à la gamme SPEED CONTROL. Régulateur fiable, simple à installer et à utiliser, doté d'un logiciel en polonais, anglais, russe et allemand. Le programme du régulateur permet de définir intuitivement les paramètres : températures, aération, chauffage d'appoint, niveaux min./max. de ventilation et alarmes.

**Paramètres et caractéristiques :**  
- Ventilation du groupe I :
  - courant max. de la sortie à régulation continue 6A,
  - protection thermique du circuit,
  - démarrage progressif de la ventilation,
  - étalonnage de la vitesse minimale
- Ventilation du groupe II, contact isolé jusqu'à 3A (1 en option)
- Chauffage d'appoint, contact isolé jusqu'à 3A (1 en option)
- Sorties d'alarme NO et NC :
  - signalisation de la coupure d'alimentation,
  - signalisation du franchissement du seuil de température min. ou max.
- 1 entrée analogique pour la mesure de température
- 2 sorties 0-10V
- Puissance absorbée par le circuit < 3W
- Boîtier étanche IP56
- Tension d'alimentation 230VAC 50Hz

## Installation du régulateur  
:::danger 
Pendant l'installation de l'appareil, l'alimentation électrique doit impérativement être coupée, car la tension présente sur certains composants constitue un danger pour la vie et la santé.  
Il est recommandé de confier l'installation à une personne qualifiée.
:::

### Choix du lieu de montage  

Le lieu de montage doit être choisi de manière rationnelle, en veillant à ce que l'appareil soit facilement accessible aux personnes autorisées, mais inaccessible aux animaux et aux enfants. Il convient également de tenir compte des conditions climatiques, c'est-à-dire que l'appareil doit fonctionner dans une plage de températures de -10°C à 40°C, dans un endroit non exposé au soleil. L'air doit circuler librement autour de l'appareil. L'appareil comprend un capteur de température. Plusieurs règles s'appliquent au montage du capteur de température :  
- le capteur ne doit pas être installé dans un endroit sans circulation d'air ou directement exposé au soleil
- le capteur ne doit pas être installé sur un mur porteur (extérieur) du bâtiment,
- éviter la proximité d'appareils émettant de la chaleur, tels que les radiateurs et les lampes,
- ne pas placer le capteur directement à proximité des portes et des ouvertures de ventilation,
- ne pas placer le capteur dans des endroits accessibles aux animaux,
- il est recommandé de poser le câble de raccordement du capteur à l'écart des câbles d'alimentation.

### Montage  

L'appareil peut fonctionner dans des conditions climatiques difficiles. Correctement installés, le régulateur et le capteur de température résistent aux effets de l'environnement.
Lors du montage, il convient de prêter attention aux points suivants :  
- avant le vissage, vérifier le joint du couvercle,
- le couvercle doit être serré à l'aide de toutes les vis,
- les câbles utilisés pour le raccordement du régulateur doivent être ronds,
- après le raccordement du câble, serrer les presse-étoupes de manière à assurer l'étanchéité et l'immobilisation du câble ; l'utilisation de silicone est recommandée,
- les passages de câbles (presse-étoupes) inutilisés doivent être obturés,
- fixer le régulateur (partie inférieure du boîtier) sur un mur plat à l'aide de 4 chevilles à expansion.

## Raccordement électrique  

:::danger 
Avant de raccorder le circuit, s'assurer que l'alimentation est coupée !
:::

Avant de procéder au raccordement du régulateur, dévisser et retirer le couvercle. Introduire les câbles à travers les presse-étoupes en caoutchouc, puis procéder à leur raccordement. Les bornes du régulateur sont représentées sur la figure ci-dessous.

![Raccordement](./img/Sc-s2.png)

**Raccorder le connecteur AC 230V** à l'alimentation (tableau électrique). L'utilisation d'un disjoncteur de protection contre les surintensités 1P-B6 et de parafoudres de type T1 T2 est obligatoire. Lors du raccordement de plusieurs appareils, il est recommandé de répartir les régulateurs sur différentes « phases » (L1, L2, L3), afin de charger uniformément la ligne d'alimentation.  
**Le connecteur FAN** doit être raccordé directement au ventilateur ; en cas de commande de plusieurs ventilateurs, la charge totale ne doit pas dépasser 6A et chaque ventilateur doit être protégé séparément. Ne pas raccorder PE et N directement à l'alimentation (tableau électrique) ; ils doivent impérativement être raccordés aux bornes du régulateur.  
**Connecteur FUNCTION** : sortie relais isolée, le courant maximal du contact est de 6A (un disjoncteur externe de protection contre les surintensités 1P-B6 est requis en cas de commande directe de la charge),
peut être utilisé pour :  
- **Chauffage d'appoint** – le contact se ferme lorsque la température mesurée descend en dessous de la consigne.  
- **Ventilation du groupe 2 ou systèmes de brumisation** – le contact se ferme lorsque la température mesurée est supérieure à la somme de la température de consigne et de la bande de ventilation.  le contact se ferme lorsque la température mesurée est supérieure à la somme de la température de consigne et de la bande de ventilation.  

La figure ci-dessous présente le raccordement du ventilateur du groupe 2 ou de l'aérotherme.  

![Deuxième groupe](./img/2grupa.png)

**Le connecteur ALARM** comporte les sorties isolées NC, C et NO servant au raccordement à une centrale d'alarme. L'alarme se déclenche dans les cas suivants :  
- la température est trop basse ou trop élevée,
- le régulateur ou le capteur de température est endommagé,
- la tension d'alimentation du régulateur a disparu ;
- un fonctionnement anormal du régulateur s'est produit (par exemple, une surchauffe du régulateur)  

![Alarme](./img/alarmsc-s.png)  

**Le connecteur V1 0-10V** sert au raccordement de modules d'extension de puissance ou de ventilateurs avec un dispositif intégré de régulation de vitesse. La tension sur cette borne est proportionnelle au niveau de ventilation.  
**Le connecteur V2 0-10V** sert au raccordement de l'actionneur ouvrant les volets d'admission d'air.  
**Raccorder le connecteur SENSOR** au capteur de température 1 TS3 ou TS5 ; la polarité n'a pas d'importance.  Il est recommandé d'éloigner les câbles de mesure des câbles d'alimentation.  
**Le connecteur RS-485** peut être utilisé pour la réalisation de systèmes de ventilation et pour la communication avec un ordinateur PC.  

## Principe de fonctionnement  

La fonction principale du régulateur est de maintenir la température du local d'élevage au niveau défini par l'éleveur. Il convient de rappeler que le régulateur n'est qu'un outil destiné à aider à assurer des conditions climatiques optimales dans le local d'élevage. Le rôle prépondérant dans ce processus revient toutefois à l'éleveur, qui doit adapter les réglages de l'appareil aux variations des conditions climatiques extérieures et, avant tout, aux besoins des animaux présents dans le bâtiment d'élevage, ainsi que surveiller l'état de fonctionnement de l'appareil au moyen de la centrale d'alarme.  

### Première mise en service du régulateur  

:::danger
Lors de la première mise en service du régulateur, il est impératif de régler la bande interdite de fonctionnement du moteur.
:::

Le régulateur fonctionne avec des ventilateurs équipés d'un moteur asynchrone monophasé dont le courant total maximal absorbé est de 5A. Après avoir raccordé les ventilateurs de son choix, l'utilisateur doit les adapter au fonctionnement avec le régulateur. Autrement dit, il est nécessaire de régler le niveau minimal de fonctionnement (vitesse) du ventilateur. Cette fonction porte le nom de **« Bande interdite »** et est réglée une seule fois par l'utilisateur depuis les **« Réglages avancés »**. Pour effectuer correctement cette opération, l'aide d'une deuxième personne est recommandée afin qu'elle puisse observer en permanence le comportement du ventilateur pendant que l'autre personne règle la valeur de la **« Bande interdite »**. L'absence de réglage de la bande interdite peut entraîner un fonctionnement incorrect de l'appareil. La valeur de la **« Bande interdite »** peut être considérée comme correcte lorsque la pression produite par le ventilateur commence à soulever légèrement les volets de la cheminée de ventilation. Le réglage de la **« Bande interdite »** doit être effectué de nouveau lorsque le ventilateur raccordé au régulateur est remplacé.  

### Aération périodique  

L'aération est une fonction exécutée par le régulateur, qui s'active lorsque la température du local descend en dessous de la température de consigne. Cette fonction assure aux animaux un apport cyclique d'air frais. L'aération est définie par 3 paramètres :
- **« Durée de fonctionnement »** - détermine le nombre de secondes pendant lesquelles le ventilateur doit être activé,
- **« Durée de pause »** - détermine la durée d'arrêt du ventilateur en secondes,
- **« Niveau d'aération »** - détermine la puissance de ventilation pendant la « Durée de fonctionnement ».  

Un exemple de réglage **60s/120s** signifie que le ventilateur est activé pendant 60s avec une pause de 120s entre les activations successives. 

Tous les paramètres mentionnés ci-dessus sont réglés par l'utilisateur. Il convient de respecter plusieurs règles lors du réglage des paramètres d'aération :
- l'aération est activée uniquement lorsque la température dans la porcherie descend en dessous de la température de consigne,
- la fonction principale de l'aération est d'assurer aux animaux un apport cyclique d'air frais, et non de maintenir la température de consigne dans le local,
- il est recommandé d'aérer les locaux brièvement, mais fréquemment,
- il convient d'éviter les longues périodes d'aération, car elles peuvent entraîner des variations de température trop importantes,
- il est impératif d'adapter les paramètres réglés au comportement des animaux et aux conditions régnant aussi bien à l'intérieur qu'à l'extérieur du local,
- il est possible de désactiver la fonction d'aération ; dans ce cas, tant en mode pourcentage qu'en mode temporisé, les valeurs correspondant à la durée d'aération doivent être réglées sur zéro, par exemple : 0/120s  

### Ventilation à régulation continue  

Le régulateur ajuste la ventilation en continu de la « Vitesse minimale » à la **« Vitesse maximale »** dans la plage allant de la **« Température de consigne »** à la somme de la **« Température de consigne »** et de la **« Bande de ventilation »**. Au-dessus de cette plage, le groupe 2 de ventilation est activé.  

![ventilation](./img/wentylacjia.png)  

Au-dessus de cette plage, le groupe 2 de ventilation est activé. Lorsque la température du local descend en dessous de la **« Température de consigne »**, le régulateur aère périodiquement le local ; si la température continue à baisser, le chauffage d'appoint est activé. Tout dépend des réglages effectués par l'utilisateur. Le programme du régulateur prévoit également le fonctionnement avec une centrale d'alarme, qui peut être activée lorsque la température dans la porcherie s'écarte des paramètres définis.  

## Programmation du régulateur  

Le régulateur possède un ensemble de réglages par défaut, qui sont inscrits dans la mémoire non volatile dans deux cas :  
1. Première mise en service de l'appareil,  
2. Erreur dans la mémoire de données.  
En cas d'absence ou de coupure d'alimentation, le régulateur ne perd pas les réglages utilisateur précédemment saisis et enregistrés.  

### Utilisation du menu  

Le régulateur est équipé de plusieurs fonctions permettant de l'adapter à une application donnée. Ces fonctions sont regroupées dans un menu auquel on accède en appuyant sur l'une des touches **(« Flèche droite », « Flèche gauche »)**. Les paramètres se modifient à l'aide des touches **« + » et « - »** ; le paramètre modifié est automatiquement enregistré dans la mémoire non volatile après un délai de **30s** suivant la dernière pression sur une touche.  

### Fonctions du menu de base  

| MENU                       | Description | 
|:---:                       |:---|
|Température  <br />20,8°C W16% A  |**« Mode information »** - fonctionnement normal. L'afficheur indique la température actuelle et, lorsque le ventilateur est en marche, la valeur du niveau de ventilation. Signification des symboles supplémentaires : A-indique que l'alarme est activée, D  - indique que le chauffage est activé, W - indique la ventilation supplémentaire| 
|Temp. de consigne  <br />20,0°C        |**« Température de consigne »** – valeur de température définissant le début du processus de ventilation à régulation continue.   | 
|Aération  <br />20s / 200s  |**« Aération »** – deux durées sont réglées : 1 « Durée de fonctionnement », 2 « Durée de pause » entre les activations cycliques successives de la ventilation.| 
|Niveau d'aér.  <br />20%        |**« Niveau d'aération »** - niveau de ventilation pendant le fonctionnement de l'aération   | 
|Alarme minimum  <br />12,0°C       |**« Alarme minimum »** - définit la température minimale absolue à laquelle l'alarme est déclenchée. 
|Alarme maximum  <br />28,0°C       |**"Alarme maximum"** - définit la température maximale absolue à laquelle l'alarme est déclenchée.  | 
|Chauffage d'appoint  <br />12,0°C         |Selon la configuration, les fonctions suivantes sont exécutées : **« Chauffage d'appoint »** - le contact se ferme si la température descend en dessous de la valeur indiquée. | 
|Ventilation du niveau 2  <br />25,0  |**« Ventilation du niveau 2 »** - le contact se ferme lorsque la température mesurée dépasse la somme de la température de consigne et de la bande de ventilation. | 
|Bande de ventilation  <br />5,0°C     |**« Bande de ventilation »** - définit la rapidité de réaction du régulateur (variation du niveau de ventilation du minimum 1 au maximum 1) à l'augmentation de la température. | 
|Vitesse minimale  <br />1%        |**« Vitesse minimale »** – état dans lequel l'appareil reste pendant une durée indéterminée, en fournissant à la sortie une tension de la valeur définie. Sert à l'étalonnage de l'appareil avec le moteur et le mécanisme des volets.   | 
|Vitesse maximale  <br />100%      |**« Vitesse maximale »** – état dans lequel l'appareil reste pendant une durée indéterminée, en fournissant à la sortie une tension de la valeur définie. Sert à limiter la puissance consacrée à la ventilation| 

### Menu avancé  

Le menu avancé est principalement destiné aux installateurs ; il permet d'adapter le régulateur à l'installation et au ventilateur. Pour accéder aux réglages avancés, appuyer sur les deux touches du menu et les maintenir enfoncées pendant environ 10s.  

| MENU                                 | Description| 
|:---:                                 |:--- |
|Aucun réglage  <br />avancé   |Ce message indique que le régulateur n'a pas été étalonné avec la ventilation et que son fonctionnement peut être incorrect. Il est nécessaire d'accéder au menu avancé et d'effectuer les réglages de la « Bande interdite ».|
|Réglages <br />avancés         |Signalisation de l'accès aux réglages avancés. | 
|Logiciel Ver:  <br />1907       |Information sur la version du logiciel.| 
|Bande interdite  <br />1000 us       |Étalonnage de la vitesse minimale des ventilateurs raccordés directement au régulateur ; ce paramètre correspond au niveau de ventilation « 1% »|  
|Fonction des contacts  <br />Chauffage d'appoint     |Choix de la fonction des contacts :  <br />• Chauffage d'appoint (par défaut)<br />• Groupe 2 de ventilation | 
|Aération  <br />Temporisée         |Choix du type d'aération : <br />• Temporisée (par défaut) <br />• En pourcentage| 
|Plage V1  <br />de 2,0 à 10,0       |Réglage de la plage de variation de la tension sur la sortie V1 0÷10V. Les réglages concernent les valeurs minimale et maximale de la tension. Ce réglage permet d'adapter le régulateur à une extension de puissance ou à un variateur de fréquence.| 
|Inversion V1  <br />Non                |L'activation inverse la caractéristique de la sortie V1. La tension diminue à mesure que le niveau de ventilation augmente dans la plage définie par min.-max. Le signal sur la sortie V1 sera de type 10-0V.| 
|Coupure V1  <br />Non                |L'activation entraîne l'application à la sortie  V1 0-10V du niveau 0V au lieu de la valeur minimale réglée, lorsque le niveau de ventilation atteint 0%.| 
|Plage V2  <br />de 2,0 à 10,0       |Réglage de la plage de variation de la tension sur la sortie V2 0÷10V. Les réglages concernent les valeurs minimale et maximale de la tension. Ce réglage permet d'étalonner le système de volets.|
|Inversion V2  <br />Non      	       |L'activation inverse la caractéristique de la sortie V2. La tension diminue à mesure que le niveau de ventilation augmente dans la plage définie par min.-max. Le signal sur la sortie V2 sera de type 10-0V.|
|Étalonnage temp  <br />21,0°C -> 22,0°C|L'étalonnage du capteur de température permet de modifier l'échelle de la valeur lue.|
|Démarrage progressif  <br />50%      	           |Définition du niveau de ventilation à chaque démarrage du ventilateur ; le ventilateur accélère jusqu'à la valeur indiquée, puis passe au niveau de consigne.| 
|Langue  <br />Polonais    	           |Choix de la langue du menu : polonais, anglais, allemand, russe|
|Quitter                               |Sortie du menu avancé à l'aide de la touche « + » ; les modifications effectuées sont enregistrées dans la mémoire non volatile.|

### Messages d'erreur et d'avertissement  

Les messages d'erreur servent à informer l'utilisateur des anomalies de fonctionnement du régulateur. Les messages d'erreur possibles sont présentés ci-dessous.  

|ERREUR                                    | DESCRIPTION |
|:---:                                   |:--- |
|Alarme  <br />de surcharge 	         |Alarme de surcharge, activée à 75°C. L'appareil suspend son fonctionnement jusqu'à son refroidissement.|
|CAPTEUR EN CIRCUIT OUVERT !  <br />Vérifier le capteur|Capteur en circuit ouvert ; signale un endommagement du capteur ou du câble de raccordement.|
|CAPTEUR EN COURT-CIRCUIT !  <br />Vérifier le capteur  |Capteur en court-circuit ; signale un endommagement du capteur ou du câble de raccordement.|
|Coupure  <br />d'alimentation                  |Coupure d'alimentation, tension d'alimentation trop basse, fréquence incorrecte ou tension d'alimentation fortement déformée.| 

## Remarques et avertissements  

:::danger 
Pendant l'installation de l'appareil, l'alimentation électrique doit impérativement être coupée, car la tension présente sur certains composants constitue un danger pour la vie et la santé. Il est recommandé de confier l'installation à une personne qualifiée.
:::

- Afin d'éviter tout problème d'exploitation de l'appareil, il est nécessaire de lire la notice avant de procéder à l'installation et à l'utilisation.  
- Il est interdit de modifier la construction de l'appareil ou d'effectuer des réparations soi-même. Cela concerne en particulier les modifications des éléments et des composants.  
- Les opérations de maintenance ou d'entretien doivent être effectuées par du personnel habilité (installateur ou service après-vente du fabricant). Un système d'alarme est obligatoire dans les bâtiments d'élevage à ventilation forcée. Le fabricant de l'appareil n'est pas responsable des dommages causés par une installation incorrecte, une programmation incorrecte des fonctions, les conséquences d'événements fortuits ou des facteurs externes.  
- Le régulateur de ventilation nécessite un réglage des paramètres adapté aux conditions régnant dans le local d'élevage. Ces réglages sont individuels et dépendent de la décision de l'éleveur. Le fabricant de l'appareil se réserve le droit de modifier la construction de l'appareil et le logiciel.  


:::caution
![texte alternatif](./img/trash.svg) À la fin de sa durée d'utilisation, le produit ne doit pas être jeté avec les déchets municipaux non triés, mais éliminé conformément à la réglementation en vigueur (directives DEEE de l'Union européenne 2012/19/UE). <br />Le produit a été fabriqué conformément aux exigences RoHS (directive de l'Union européenne 2011/65/UE).
:::

<!-- \newpage -->
## Caractéristiques techniques du régulateur  

|Paramètre                        |	DESCRIPTION      |
|:-----------                    |:---------- |
|Tension d'alimentation|	230VAC 50Hz|
|Courant maximal de la sortie à régulation continue FAN|	6A|
|Plage de régulation de la tension de sortie|	70V ÷ (Uz-5)V|
|Courant maximal de la sortie (contact) ALARM|	3A|
|Courant maximal de la sortie (contact) FUNCTION|	3A|
|Plage de températures de fonctionnement|	-20 +40oC|
|Plage de mesure de température|	0 +50°C|
|Résolution de la mesure de température|	0,1°C|
|Détection des défauts du capteur de température|	OUI|
|Nombre maximal de capteurs analogiques|	1|
|Précision de la mesure de température – entrée analogique|	1°C|
|Dépendance de la mesure à la résistance des câbles – entrée analogique|	15,8Ω/°C|
|Tenue aux surtensions (E max.)|	210J|
|Protection contre les surcharges|	75°C|
|Dimensions de l'appareil|	20x15x8 [cm]|
|Indice de protection du boîtier|	IP56|
  


:::info
Le régulateur SPEED CONTROL SERVOMOTOR comprend dans son kit :
- 1 capteur de température + accessoires,
- 4 chevilles à expansion,
- 1 fusible 10A.
:::

