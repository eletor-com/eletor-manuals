---
sidebar_position: 3
title: Notice SC-12
description: Régulateur climatique pour locaux d'élevage avec un courant de sortie
  admissible jusqu'à 12A
keywords:
- eletor sc-12
- régulateur de ventilation
- régulateur climatique
- régulateur de ventilation de porcherie
- régulateur de microclimat
- régulateur pour porcheries
- ventilation de porcherie
- régulateur pour locaux d'élevage
---

# Régulateur SC-12

Régulateur climatique à microprocesseur appartenant à la série SPEED CONTROL. La polyvalence de l'appareil est assurée par le grand nombre d'entrées/sorties du système et par un logiciel intuitif en polonais et en anglais. Outre les réglages de base des températures, de l'aération, du chauffage d'appoint, des niveaux min./max. de ventilation et des alarmes, le programme du régulateur permet de tester et d'enregistrer l'étalonnage des actionneurs associés au régulateur.

**Paramètres et caractéristiques :** 
- Ventilation du groupe I : 
  - courant max. de la sortie à régulation continue 12A,
  - protection thermique du système, 
  - démarrage progressif de la ventilation – démarrage en douceur,
  - relais de dérivation à pleine commande, 
  - étalonnage de la vitesse minimale de rotation, 
  - programme d'économie d'énergie avec système de volets à ouverture anticipée.
- Ventilation du groupe II, contact isolé jusqu'à 6A.
- Chauffage d'appoint, contact isolé jusqu'à 6A
- Sorties d'alarme NO et NC : 
  - signalisation de la coupure d'alimentation,
  - signalisation du franchissement du seuil de température min. ou max.,
  - avertisseur sonore intégré.
- Sorties indépendantes 3 0..10V :
  - fonctionnement avec des modules d'extension,
  - commande du système de volets, 
  - régulation du chauffage à puissance variable.**
- Deux entrées analogiques pour la mesure de température.
- Port numérique pour la mesure de température (jusqu'à 4 capteurs).
- Deux sorties à relais fonctionnelles (au choix) :
  - fonctionnement avec des actionneurs linéaires, 
  - III et IV groupes de ventilation
- Deux entrées analogiques 0-10V.
- Alimentation du potentiomètre DC 10V.
- Alimentation auxiliaire DC 12V.
- Possibilité de fonctionnement avec un ordinateur jusqu'à 1200m.
- Boîtier étanche IP65.
- Tension d'alimentation 230VAC 50Hz.
- Puissance absorbée par le système < 10V

# Installation du régulateur
:::danger 
 Lors de l'installation de l'appareil, l'alimentation électrique doit impérativement être coupée, car la tension présente sur certains composants constitue un danger pour la vie et la santé. Il est recommandé de confier l'installation à une personne qualifiée.  Cette opération est dangereuse
:::

## Choix du lieu de montage
Le lieu de montage doit être choisi de manière rationnelle, en veillant à ce que l'appareil soit facilement accessible aux personnes habilitées, mais inaccessible aux animaux et aux enfants. Il convient également de tenir compte des conditions climatiques : l'appareil doit fonctionner dans une plage de températures de -10°C à 40 °C, dans un endroit non exposé au soleil. L'air doit pouvoir circuler librement autour de l'appareil. L'appareil comprend un capteur de température.  

### Plusieurs règles s'appliquent au montage du capteur de température :
 - le capteur ne doit pas être monté dans un endroit sans circulation d'air ou directement exposé au soleil,
 - le capteur ne doit pas être monté sur un mur porteur (extérieur) du bâtiment,
 - éviter la proximité d'appareils émettant de la chaleur, tels que les radiateurs et les lampes,
 - ne pas placer le capteur directement à proximité des portes et des ouvertures de ventilation,
 - ne pas placer le capteur dans des endroits accessibles aux animaux,
 - il est recommandé de poser le câble de raccordement du capteur à distance des câbles d'alimentation.

# Montage
L'appareil peut fonctionner dans des conditions climatiques agressives. Lorsqu'ils sont correctement montés, le régulateur et le capteur de température résistent aux effets nuisibles de l'environnement.  

### Lors du montage, il convient de prêter attention aux points suivants :
 - avant le vissage, vérifier le joint du couvercle,
 - le couvercle doit être serré à l'aide de toutes les vis,
 - les câbles utilisés pour le raccordement du régulateur doivent être ronds,
 - après le raccordement du câble, serrer les presse-étoupes afin d'assurer l'étanchéité et l'immobilisation du câble ; l'utilisation de silicone est recommandée,
 - obturer les passages (presse-étoupes) inutilisés,
 - fixer le régulateur (la partie inférieure du boîtier) sur un mur plat à l'aide de 4 chevilles à expansion.

# Raccordement électrique
:::danger 
 Avant de raccorder le système, s'assurer que l'alimentation est coupée !
Cette opération est dangereuse
:::

Avant de procéder au raccordement du régulateur, dévisser et retirer le couvercle. Introduire les câbles à travers les presse-étoupes en caoutchouc, puis procéder à leur raccordement. Les bornes du régulateur sont représentées sur la figure ci-dessous.

![Raccordement ](./img/sc-12.png)

**Raccorder le connecteur AC 230V** à l'alimentation (tableau électrique). L'utilisation d'un disjoncteur de protection contre les surintensités 1P-B6 et de parafoudres de type T1 T2 est obligatoire. Lors du raccordement de plusieurs appareils, il est recommandé de répartir les régulateurs sur différentes « phases » (L1, L2, L3), afin d'équilibrer la charge de la ligne d'alimentation.

**Raccorder le connecteur FAN** directement au ventilateur ; en cas de commande de plusieurs ventilateurs, la charge totale ne doit pas dépasser 6A et chaque ventilateur doit être protégé séparément. Ne pas dériver PE et N depuis l'alimentation (tableau électrique) ; les raccorder impérativement aux bornes du régulateur.

**Le connecteur FAN 2** peut être utilisé pour raccorder les ventilateurs du groupe 2 ou les systèmes d'aspersion. La sortie est isolée, le courant maximal du contact est de 6A (un disjoncteur externe de protection contre les surintensités de type 1P-B6 est obligatoire en cas de commande directe de la charge) ; le contact se ferme lorsque la température mesurée est supérieure à la somme de la température de consigne et de la bande de ventilation.

**Le connecteur HOT** peut être utilisé pour raccorder un aérotherme. La sortie est isolée, le courant maximal du contact est de 6A (un disjoncteur externe de protection contre les surintensités 1P-B6 est obligatoire en cas de commande directe de la charge) ; le contact se ferme lorsque la température mesurée descend en dessous de la consigne.

**Le connecteur ALARM** comporte des sorties isolées NC, C et NO destinées au raccordement à une centrale d'alarme. L'alarme se déclenche dans les cas suivants :
    - la température est trop basse ou trop élevée,
    - le régulateur ou le capteur de température est endommagé,
    - la tension d'alimentation du régulateur a disparu,
    - un fonctionnement anormal du régulateur s'est produit (par exemple, une surchauffe du régulateur)
La figure ci-dessous présente le raccordement du ventilateur à la centrale d'alarme.

![Raccordement de l'alarme](./img/alarmsc-s.png)

**Le connecteur FUNC1 et FUNC2** sert à raccorder le mécanisme de levage permettant l'ouverture des entrées d'air, équipé d'un moteur à rotation droite/gauche. Le relais FUNC1 enclenche l'alimentation de l'actionneur et FUNC2 commute le sens de rotation du moteur. Exemple de schéma de raccordement du mécanisme de levage (un disjoncteur externe de protection contre les surintensités 1P-B6 est obligatoire) :
Lorsque la fonction de levage est désactivée, les sorties FUNC1 et FUNC2 fonctionnent respectivement comme contacts des groupes de ventilation 3 et 4.

![Raccordement du mécanisme de levage](./img/Sc-12fan.png)

**Le connecteur 12V** est destiné à l'alimentation des capteurs externes.

**Le connecteur V1 0-10V** sert à raccorder les modules d'extension de puissance. La tension à cette borne est proportionnelle au niveau de ventilation.

**Le connecteur V2 0-10V** sert à raccorder l'actionneur ouvrant les volets d'entrée d'air.

**Le connecteur V3 0-10V** sert à raccorder le système de chauffage à puissance réglable en continu. La tension sur cette sortie augmente proportionnellement à la baisse de température, à partir de la température de chauffage d'appoint.

**Le connecteur 10V** sert à alimenter le potentiomètre du mécanisme de levage ou d'autres systèmes de type 0-10V.

**Raccorder le connecteur SENS1 (SENS2)** au capteur de température 1 TS3 ou TS5 ; la polarité est sans importance. En cas de raccordement simultané de 2 capteurs, les températures mesurées sont moyennées. Il est recommandé d'éloigner les câbles de mesure des câbles d'alimentation.

**Le connecteur 1-WIRE** peut être utilisé pour raccorder un plus grand nombre de capteurs de température numériques, au maximum 4, connectés en parallèle (respecter la polarité appropriée). La longueur maximale du câble reliant les capteurs est de 150m (la longueur n'a aucune influence sur la mesure de température) ; l'utilisation d'un câble blindé est recommandée.

**Le connecteur RS-485** peut être utilisé pour réaliser des systèmes de ventilation et pour communiquer avec un ordinateur PC.

**Le connecteur IN1 0-10** sert à introduire le signal de retour du système d'entrées d'air – il indique la position actuelle des entrées.

**Le connecteur IN2 0-10** sert à raccorder le régulateur à d'autres capteurs, par exemple d'humidité, de CO2, ou à faire fonctionner le régulateur comme extension de puissance.

# Principe de fonctionnement
La tâche principale du régulateur est de maintenir la température du local d'élevage au niveau défini par l'éleveur. Il convient de rappeler que le régulateur n'est qu'un outil destiné à faciliter le maintien de conditions climatiques optimales dans le local d'élevage. Le rôle primordial dans ce processus revient toutefois à l'éleveur, qui doit adapter les réglages de l'appareil aux variations des conditions climatiques extérieures et, avant tout, aux besoins des animaux dans le bâtiment d'élevage, ainsi que surveiller l'état de fonctionnement de l'appareil à l'aide d'une centrale d'alarme.

## Première mise en service du régulateur
:::danger 
 Lors de la première mise en service du régulateur, il est impératif de régler la bande interdite de fonctionnement du moteur.

:::
Le régulateur fonctionne avec des ventilateurs équipés d'un moteur asynchrone monophasé dont le courant total absorbé maximal est de 12A. Après avoir raccordé les ventilateurs de son choix, l'utilisateur doit les adapter au fonctionnement avec le régulateur. En d'autres termes, il est nécessaire de régler le niveau minimal de fonctionnement (vitesse de rotation) du ventilateur. Cette fonction s'appelle « Bande interdite » et se règle une seule fois par l'utilisateur depuis les « Réglages avancés ». Pour effectuer correctement cette opération, l'aide d'une seconde personne est conseillée : elle pourra observer en permanence le comportement du ventilateur pendant que l'autre personne règle la valeur de la « Bande interdite » (la valeur d'usine est de 0). L'absence de réglage de la bande interdite peut entraîner un fonctionnement incorrect de l'appareil. La valeur de la « Bande interdite » peut être considérée comme correcte lorsque la pression produite par le ventilateur commence à soulever légèrement les volets de la cheminée de ventilation. Le réglage de la « Bande interdite » doit être effectué à nouveau lorsque le ventilateur raccordé au régulateur est remplacé.

## Aération périodique
L'aération est une fonction exécutée par le régulateur, qui est activée lorsque la température du local descend en dessous de la température de consigne. Cette fonction assure aux animaux un apport cyclique d'air frais. Le menu Aération comporte 3 paramètres :
- **« Durée de fonctionnement »** - définit le nombre de minutes pendant lesquelles le ventilateur doit être activé ;
- **« Durée de pause »** - définit la durée d'arrêt du ventilateur ;
- **« Niveau d'aération »** - définit la puissance de ventilation pendant la « Durée de fonctionnement ».

Tous les paramètres mentionnés ci-dessus sont réglés par l'utilisateur. 

### Il convient de respecter plusieurs règles lors du réglage des paramètres d'aération :
- l'aération est activée uniquement lorsque la température dans la porcherie descend en dessous de la température de consigne,
- la fonction principale de l'aération est d'assurer aux animaux un apport cyclique d'air frais, et non de maintenir la température de consigne dans le local,
- il est recommandé d'aérer les locaux brièvement, mais fréquemment,
- éviter les longues périodes d'aération, car elles peuvent entraîner des fluctuations de température trop importantes,
- adapter impérativement les paramètres réglés au comportement des animaux et aux conditions régnant tant à l'intérieur qu'à l'extérieur du local.

## Mode de fonctionnement de l'appareil
Le régulateur règle en continu la ventilation de **« Min.1 » à « Max.1 »** dans la plage allant de la **« Température de consigne »** à la somme de la **« Température de consigne »** et de la **« Bande de ventilation 1gr. »**. Au-dessus de cette plage, le groupe de ventilation 2 est activé et le groupe 1 passe au niveau **« Min.2 »** ; si la température continue d'augmenter, la ventilation augmente jusqu'à **« Max.2 »**, à la fin de la plage de la **« Bande de ventilation 2 gr. »**. Lorsque la **« Bande de ventilation 2 gr. »** est réglée sur zéro et que la ventilation fonctionne à **« Max.1 »**, le groupe de ventilation 2 est activé et une augmentation supplémentaire de la température n'entraîne plus aucune modification de la ventilation (partie en pointillés du graphique). Lorsque la température dans le local descend en dessous de la **« Température de consigne »**, le régulateur aère périodiquement le local ; si la température continue de baisser, le chauffage d'appoint est activé. Tout dépend des réglages effectués par l'utilisateur. Le programme du régulateur prévoit également le fonctionnement avec une centrale d'alarme, qui peut être activée lorsque la température dans la porcherie s'écarte des paramètres définis. 

![Ventilation](./img/Sc-12wentyl.png)  

## Programmation du régulateur
Le régulateur possède un ensemble de réglages par défaut, qui sont inscrits dans la mémoire non volatile dans deux cas :
1. Première mise en service de l'appareil,
2. Erreur dans la mémoire de données.
En cas d'absence ou de coupure d'alimentation, le régulateur ne perd pas les réglages utilisateur précédemment saisis et enregistrés.

## Face avant – indicateurs, boutons et afficheur
![Panneau](./img/SC-12panel.png)  
    1. Voyant rouge signalant le dépassement de la température maximale admissible.
    2. Voyant rouge signalant le franchissement de la température minimale admissible.
    3. Voyant jaune signalant le chauffage d'appoint.
    4. Voyant jaune signalant la ventilation du groupe 2.
    5. Voyant vert signalant le réglage manuel du niveau de ventilation.
    6. Voyant vert signalant le fonctionnement de la communication RS485.
    7. Afficheur du menu ; en fonctionnement normal, il indique la température.
    8. Bargraphe indiquant le niveau de ventilation.
    9. Touche permettant de monter dans le menu ou de modifier la valeur d'un paramètre.
    10. Touche ESC - sortie du menu ou d'un paramètre sans enregistrer la valeur.
    11. Touche OK - accès au menu ou validation (enregistrement) d'un paramètre.
    12. Touche permettant de descendre dans le menu ou de modifier la valeur d'un paramètre.

## Utilisation du menu
Le régulateur est équipé de nombreuses fonctions permettant de l'adapter à une application donnée. Ces fonctions sont regroupées dans un menu accessible en appuyant sur l'une des touches **(« + », « - » ou « OK »)**. Les touches **« + »** et **« - »** servent à sélectionner les fonctions ; la modification, l'enregistrement des données ou l'accès au niveau suivant s'effectuent à l'aide de la touche **« OK »**. Appuyer sur la touche **« Esc »** pour revenir au menu supérieur ou renoncer à l'enregistrement d'un paramètre.

## Fonctions du menu de base

| MENU                          | Description       | 
|:-----------                   |:---------- |
| Température 20,8o C W16% A    | **Mode d'information** - fonctionnement normal. L'afficheur indique la température actuelle ainsi que, lorsque le ventilateur est activé, la valeur du niveau de ventilation. Signification des symboles supplémentaires :A-indique une alarme activée,D  - indique un chauffage activé, W - indique une ventilation supplémentaire| 
|   Temp. consigne   20,0o C      |**« Température de consigne »** – Définit la température à partir de laquelle commence la régulation continue de la ventilation. Choisir une valeur appropriée en fonction du type d'animaux d'élevage.| 
| Aération     | **Aération** – deux valeurs de durée sont réglées.    1.**Durée de fonctionnement** Définit le nombre de minutes de fonctionnement de la ventilation.    2.**Durée de pause** Définit le nombre de minutes d'arrêt de la ventilation entre les cycles de fonctionnement successifs.    3.**Niveau d'aération** - Définit l'intensité de la ventilation pendant le fonctionnement de l'aération.| 
| Alarme |  1.**Alarme active Oui** - Activation/Désactivation du contact d'alarme ; pour que le régulateur n'émette pas de signal d'alarme en sortie (vers la centrale d'alarme), sélectionner « NON » dans le menu.  2. **Temp. Min. 15,0o C** - Définit la température minimale absolue à laquelle l'alarme sera déclenchée.  3.**Temp. Max. 25,0o C** - Définit la température maximale absolue à laquelle l'alarme sera déclenchée.  4.**Signal d'alarme Oui** - Activation/Désactivation du signal sonore à l'intérieur du régulateur. | 
|    Ventilation        |  1.**Bande vent. 1 5,0o C**   - Définit la rapidité de réaction du régulateur (variation du niveau de ventilation du minimum 1 au maximum 1) à l'augmentation de la température.  2.**Niveau min. 1 1 %** - Définit le niveau de ventilation correspondant à la température de consigne.  3.**Niveau max. 1 100 %**-Définit le niveau constant de ventilation pour une température dépassant la plage de régulation continue, lorsque « Bande vent. 2gr. » = 0 ; dans le cas contraire, il définit le niveau maximal de ventilation régulée pour une température égale à la somme de la T. de consigne et de la bande du groupe 1.  4.**Bande vent. 2 0,0o C**-Définit la rapidité de réaction du régulateur (variation du niveau de ventilation du minimum 2 au maximum 2) à l'augmentation de la température pour le groupe 2. Fonction inactive lorsque la bande est égale à zéro.  5.**Niveau min. 2 1 %**-Définit le niveau minimal de ventilation du groupe 1 au point de fermeture des contacts du groupe 2.  6.**Niveau max. 2 100 %**-Définit le niveau constant de ventilation pour une température dépassant la plage de régulation continue, lorsque le groupe 2 est activé.  7.**Groupe 3  5,0o C**-Définit le niveau constant de ventilation pour une température dépassant la plage de régulation continue, lorsque le groupe 2 est activé.  8.**Groupe 4 7,0o C**-Définit la température d'activation du groupe de ventilation 4 par rapport à la température de consigne (la fonction de levage doit être désactivée).| 
|    Chauffage d'appoint  |  1.**Temp. chauff. appoint 15,0o C**-Définit la température d'activation du chauffage d'appoint.  2.**Bande chauff. appoint 5,0o C** -Définit la proportion de puissance des systèmes de chauffage d'appoint (sur la sortie V3 0-10V) en fonction de la température. | 

## Fonctions du menu avancé
Le menu avancé est principalement destiné aux installateurs ; il permet d'adapter le régulateur à l'installation et au ventilateur, de tester les circuits et de choisir la langue du menu. Pour accéder aux réglages avancés, appuyer simultanément sur deux touches du menu et les maintenir enfoncées pendant environ 10s. 

| MENU                          | Description       | 
|:-----------                   |:---------- |
|Tests  |Cette fonction sert à vérifier les différents circuits de commande du régulateur ; tous les réglages sont temporaires et ne s'appliquent que tant que l'on reste dans la rubrique de menu concernée. Après un appui sur « ESC » ou « OK », la sortie concernée revient à l'état résultant du fonctionnement du régulateur.  1.**Ventilation 0 %**  Permet de saisir manuellement le niveau de ventilation afin de vérifier le système de ventilation. Après validation de la fonction, le voyant vert (main) s'allume.  2.**Alarme Non** L'activation entraîne l'allumage de 2 voyants rouges, l'activation du signal sonore et du circuit d'alarme.  3.**Chauffage d'appoint Non** L'activation entraîne l'allumage du voyant jaune (flamme) et l'activation du circuit de chauffage d'appoint.  4.**Vent. étage 2 Non** L'activation entraîne l'allumage du voyant jaune (ventilateur) et l'activation du circuit du groupe 2.  5.**Sortie V1 0,0 V  Sortie V2  0,0 V Sortie V3  0,0 V**-Test des sorties 0-10V ; à l'aide des touches « + » ou « - », il est possible d'appliquer la tension choisie aux systèmes suivants, dans l'ordre : modules d'extension, volets d'entrée d'air, chauffage d'appoint à régulation continue. Fonction particulièrement utile lors de l'étalonnage de la Sortie V2 des volets d'entrée d'air.  6.**Levage 0** Permet de vérifier le système de volets d'entrée d'air : « + » - ouvre les entrées, « - » - ferme les entrées ; l'afficheur indique la position actuelle de l'actionneur, lue sur le potentiomètre.  7.**Groupe 3 Non**  L'activation entraîne l'activation du circuit du groupe de ventilation 3. (la fonction de levage doit être désactivée)  8.**Groupe 4 Non**  L'activation entraîne l'activation du circuit du groupe de ventilation 4. (la fonction de levage doit être désactivée)|
|Langue        | Choix de la langue du menu. Les langues disponibles sont le polonais et l'anglais. | 
|Ventilateur         |  1.**Bande interdite 0**- Étalonnage de la vitesse minimale de rotation des ventilateurs raccordés directement au régulateur ; ce paramètre correspond au niveau de ventilation « 1% ». Une valeur positive du paramètre augmente la vitesse de rotation, une valeur négative la diminue.  2.**Module ext. Min. 1,9 V** -Tension minimale appliquée au module d'extension de puissance (sortie V1 0-10V).  3.**Module ext. Max. 10,0 V** -Tension maximale appliquée au module d'extension de puissance (sortie V1 0-10V).  4.**Coupure module Non** - Déconnexion du module d'extension de puissance ; lorsque « OUI » est sélectionné, la tension sur la sortie commandant les modules d'extension (V1 0-10V) descend au niveau 0V et non à la valeur minimale réglée, lorsque le niveau de ventilation atteint 0%.  5.**Inversion  Non**-L'activation inverse la caractéristique de la sortie V1. La tension diminue lorsque le niveau de ventilation augmente dans la plage définie par min.-max. Le signal sur la sortie V1 sera de type 10-0V.| 
| Volets d'entrée d'air       |  1.**Anticipation 0,0o C**-Ouverture anticipée des volets d'entrée d'air. Le paramètre réglé définit l'écart de température en dessous de la « Température de consigne » auquel les volets d'entrée d'air doivent s'ouvrir.  2.**Fermeture complète  Non**- L'activation entraîne une baisse de la tension sur la sortie commandant les volets d'entrée d'air (V2 0-10V) au niveau 0V, et non à la valeur minimale réglée. En l'absence de ventilation (niveau de ventilation 0%).  3.**Volets min.  1,9 V**- Tension minimale appliquée aux volets d'entrée d'air (sortie V2 0-10V).  4.**Volets max.  10,0 V**- Tension maximale appliquée aux volets d'entrée d'air (sortie V2 0-10V).  5.**Inversion   Non**-L'activation inverse la caractéristique de la sortie V2. La tension diminue lorsque le niveau de ventilation augmente dans la plage définie par min.-max. Le signal sur la sortie V2 sera de type 10-0V. |  
| Mesure de température  |  1.**Étalonnage S1 23,0o C -> 23,5o C**,**Étalonnage S2 23,0o C -> 23,2o C** - L'étalonnage des entrées analogiques permet de redimensionner la température lue par les capteurs S1 et S2.  2.**Durée de moyennage 60 s**- Ce paramètre définit la période pendant laquelle les mesures actuelles de température sont moyennées. La valeur de température moyenne est un paramètre fondamental des fonctions du régulateur. Les changements d'état des sorties (ventilation, chauffage d'appoint, volets, groupes de ventilation suivants, alarmes,...) sont étroitement liés à ce paramètre et ne peuvent pas se produire plus fréquemment que la durée définie ici. | 
| Levage      |  1.**Étalonnage ouverture 1024 -> 853**,**Étalonnage fermeture 0 -> 324** -L'étalonnage du mécanisme de levage est indispensable au bon fonctionnement du système d'entrées d'air. La touche « + » ouvre les entrées, la touche « - » ferme les entrées. Pendant l'ouverture des entrées, le paramètre de position doit augmenter ; pendant la fermeture, il doit diminuer. Dans le cas contraire, vérifier le raccordement de l'actionneur (alimentation et potentiomètre). Pour l'étalonnage de l'ouverture, ouvrir les entrées au maximum et valider la position avec la touche « OK ». Pour l'étalonnage de la fermeture, fermer les entrées et valider la position avec la touche « OK ». La touche « ESC » permet de quitter la fonction sans enregistrer. La différence entre la position d'ouverture et celle de fermeture doit être d'au moins 100 unités.  2.**Désactivation Non**-La désactivation libère les contacts FUNC1 et FUNC2 de la commande du mécanisme de levage ; ces contacts assurent alors la ventilation des groupes 3 et 4.| 
| Démarrage en douceur               | Les paramètres de ce groupe de menu concernent le démarrage de la ventilation. L'activation de la ventilation dans le groupe à régulation continue est précédée d'un démarrage progressif jusqu'à 100%, d'un bref fonctionnement à 100%  et d'une diminution jusqu'au niveau de ventilation requis. Ainsi, au démarrage de la ventilation, un souffle d'air facilite l'ouverture des clapets papillon dans les cheminées.   Les valeurs sont exprimées en périodes de la tension d'alimentation pour 1% de ventilation.  1.**Durée d'accélération 5**- Ce paramètre définit la vitesse d'augmentation de la vitesse de rotation de la ventilation du niveau zéro au niveau maximal – démarrage progressif des ventilateurs. La valeur 0 désactive l'accélération progressive.  2.**Durée 100%   100**- Ce paramètre définit la durée de fonctionnement au démarrage à 100% du niveau de ventilation. Le réglage de la durée d'accélération et de 100% sur 0 désactive complètement le souffle d'air au démarrage de la ventilation.  3.**Durée de décélération 5**-  Ce paramètre définit la vitesse de variation du niveau de ventilation. | 
|Chauffage d'appoint              |  1.**Inversion du contact Non**-L'activation inverse la caractéristique de la sortie HOT. Le contact sera  ouvert lorsque la température mesurée diminue.  2.**Hystérésis  0,5o C** - Définit le niveau d'hystérésis de température pour le contact de chauffage d'appoint.  3.**Fonctionnement relatif Non**-L'activation permet de régler la température de chauffage d'appoint de manière relative à la température de consigne. Le menu de base du chauffage d'appoint est modifié : on y indique alors l'écart par rapport à la température de consigne.  4.**Chauffage d'appoint min. 1,9 V** - Tension minimale appliquée à la commande continue du chauffage – aérotherme à débit de ventilateur variable (sortie V3 0-10V).  5.**Chauffage d'appoint max. 10,0 V** - Tension maximale appliquée à la commande continue du chauffage – aérotherme à débit de ventilateur variable (sortie V3 0-10V).| 
| Programme 	|  **ver. 2.4  Avr 13 2018** - 	Lecture de la version du logiciel et de la date de compilation|

## Messages d'erreur et d'avertissement

Les messages d'erreur servent à informer l'utilisateur des anomalies de fonctionnement du régulateur. Les messages d'erreur possibles sont présentés ci-dessous

|E RREUR                            |	DESCRIPTION      |
|:-----------                    |:---------- |
|Alarme     Surcharge 	     |Alarme de surcharge, activée à 75°C. L'appareil suspend son fonctionnement jusqu'à son refroidissement.|
|Alarme  Absence de capteur|Signale l'absence ou la défaillance du capteur ou du câble de raccordement.|

# Remarques et avertissements 
:::danger 
 Lors de l'installation de l'appareil, l'alimentation électrique doit impérativement être coupée, car la tension présente sur certains composants constitue un danger pour la vie et la santé. Il est recommandé de confier l'installation à une personne qualifiée.

:::
- Afin d'éviter les problèmes d'exploitation de l'appareil, il est obligatoire de prendre connaissance de la notice avant de procéder à l'installation et à l'utilisation.
- Il est interdit de modifier la structure de l'appareil ou d'effectuer soi-même des réparations. Cela concerne en particulier les modifications des éléments et des composants. 
- Les opérations de maintenance ou de réparation doivent être effectuées par du personnel habilité (installateur ou service après-vente du fabricant). Dans les bâtiments d'élevage à ventilation forcée, un système d'alarme est obligatoire. Le fabricant de l'appareil n'est pas responsable des dommages causés par une installation incorrecte, une programmation incorrecte des fonctions, les conséquences d'événements fortuits ou des facteurs externes. 
- Le régulateur de ventilation nécessite un réglage des paramètres conforme aux conditions régnant dans le local d'élevage. Ces réglages sont individuels et dépendent de la décision de l'éleveur. Le fabricant de l'appareil se réserve le droit de modifier la conception de l'appareil et le logiciel.

:::caution
<div class="warning-container">
  <p>
    <strong></strong> À la fin de son utilisation, le produit ne doit pas être jeté avec les déchets municipaux non triés, mais éliminé conformément à la réglementation en vigueur (directives DEEE de l'Union européenne 2012/19/UE).
Le produit a été fabriqué conformément aux exigences RoHS (directive de l'Union européenne 2011/65/UE).
  </p>
</div>
:::
:::tip

## Caractéristiques techniques du régulateur
|Paramètre                        |	DESCRIPTION      |
|:-----------                    |:---------- |
|Tension d'alimentation|	230VAC 50Hz|
|Courant maximal de la sortie à régulation continue FAN|	12A|
|Plage de réglage de la tension de sortie|	70V ÷ 230V|
|Courant maximal de la sortie (contact) FAN 2|	6A|
|Courant maximal de la sortie (contact) HOT|	6A|
|Courant maximal de la sortie (contact) ALARM|	4A|
|Courant maximal de la sortie (contact) FUNC1 et FUNC2|	4A|
|Plage de température de fonctionnement|	-10 +40oC|
|Plage de mesure de température|	0 +50oC|
|Résolution de la mesure de température|	0,1oC|
|Détection des défaillances du capteur de température|	OUI|
|Nombre maximal de capteurs analogiques|	2|
|Précision de la mesure de température – entrée analogique|	1oC|
|Dépendance de la mesure à la résistance des câbles – entrée analogique|	15,8Ω/oC|
|Nombre maximal de capteurs numériques|	4|
|Précision de la mesure de température – entrée numérique|	0,5oC|
|Dépendance de la mesure à la résistance des câbles – entrée numérique|	Aucune|
|Longueur maximale de la ligne reliant les capteurs numériques|	150m|
|Tenue aux surtensions (max E)|	210J|
|Protection contre les surcharges|	75oC|
|Dimensions de l'appareil|	34x29x12 [cm]|
|Indice de protection du boîtier|	IP56|
:::

:::info
Le régulateur SPEED CONTROL-12 v2  est livré avec :
 - 1 capteur de température,
 - 4 chevilles à expansion,
 - 2 presse-étoupes PG13,5.
 - 3 presse-étoupes PG11,
 - 4 presse-étoupes PG9.
:::















































































