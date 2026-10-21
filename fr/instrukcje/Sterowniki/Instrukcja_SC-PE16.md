---
id: sc-pe16
title: SC-PE16 — notice d’utilisation
sidebar_label: SC-PE16
sidebar_position: 5
description: Notice de l’extension de puissance SC-PE16 — montage, raccordement, mise
  en service, menu et protections.
slug: /sc-pe16
toc_min_heading_level: 2
toc_max_heading_level: 3
---


L’extension de puissance SC-PE16 sert à commander les ventilateurs lorsque la charge dépasse les capacités du contrôleur maître. L’appareil régule la tension d’alimentation des ventilateurs en fonction d’un signal analogique ou d’une consigne manuelle. Le courant total maximal de sortie est de 16 A.

![Extension de puissance ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Paramètres et caractéristiques

- modes AUTO et MANUAL et mise en veille de l’appareil ;
- écran graphique et clavier tactile ;
- commande analogique 2–10 V ou 4–20 mA ;
- seuil d’activation programmable du groupe de ventilation 2 ;
- byPASS à un niveau stabilisé de 100% ;
- protection thermique du circuit de puissance ;
- safeRUN : niveau de fonctionnement de secours réglable ;
- étalonnage du niveau minimal de ventilation ;
- test de la ventilation, du relais et de l’alarme ;
- verrouillage du clavier et verrouillage pour le nettoyage ;
- langue polonaise, anglaise ou ukrainienne ;
- alimentation 230 V AC, 50 Hz ; boîtier IP65.

:::info Version du logiciel

La description des fonctions concerne le logiciel fourni **version 2.1**. La disponibilité des fonctions doit être vérifiée en fonction de la version installée dans l’appareil.

:::

## Installation du contrôleur

:::danger Couper l’alimentation

Lors de l’installation de l’appareil, il est impératif de couper l’alimentation électrique, car la tension présente sur certains composants est dangereuse pour la vie et la santé. Il est recommandé de confier l’installation à une personne qualifiée.

:::

### Choix de l’emplacement de montage

L’appareil doit être monté dans un endroit accessible au personnel d’exploitation, hors de portée des enfants et des animaux, à l’abri du rayonnement solaire direct. La plage de température ambiante s’étend de −10°C à +40°C. Assurer une libre circulation de l’air autour du boîtier et du dissipateur thermique. Ne pas couvrir le dissipateur thermique ni monter l’appareil à proximité de sources de chaleur.

### Montage

Fixer la partie inférieure du boîtier sur un mur plat à l’aide de quatre chevilles, en utilisant les trous de montage situés à l’extérieur du compartiment étanche. Monter le couvercle avec la charnière fournie. Avant de fermer, vérifier l’état et le positionnement du joint.

Utiliser des câbles de section extérieure circulaire, adaptés aux presse-étoupes. Serrer les presse-étoupes de manière à assurer l’étanchéité et l’immobilisation du câble. Obturer les passages inutilisés. Serrer toutes les vis du couvercle. L’étanchéité dépend du montage correct du boîtier et des passages de câbles.

### Préparation des raccordements

Effectuer tous les travaux à l’intérieur du boîtier après avoir coupé l’alimentation et vérifié l’absence de tension. Si la dépose du panneau nécessite de débrancher la nappe, la débrancher avec précaution et la remettre en place avant de fermer le boîtier. Ne pas brancher ni débrancher la nappe lorsque l’alimentation est sous tension.

Acheminer les câbles de signal INPUT et ENABLE séparément des câbles d’alimentation et de sortie. Respecter les repérages des bornes figurant sur l’exemplaire de l’appareil concerné. La masse des entrées de signal et la borne de protection PE remplissent des fonctions différentes et ne sont pas interchangeables.

## Raccordement électrique

:::danger Couper l’alimentation

Avant de raccorder le système, s’assurer que l’alimentation est coupée !

:::

![Bornes d’alimentation, des ventilateurs, GR 2, ENABLE, CAN et INPUT](./img/sc-pe16/zaciski.png)

| BORNE | AFFECTATION |
| --- | --- |
| L, N, PE — alimentation | Alimentation 230 V AC, 50 Hz : L — phase, N — conducteur neutre, PE — conducteur de protection. La documentation d’origine indique une protection B20 ; le choix des protections et des câbles doit tenir compte de l’installation et de la charge. |
| U, N, PE — ventilateurs | U — sortie de phase régulée ; N et PE — bornes communes correspondantes de l’appareil. La somme des courants des ventilateurs ne doit pas dépasser 16 A. Chaque ventilateur nécessite une protection distincte. Utiliser des moteurs homologués pour la régulation par variation de tension. |
| GR 2: C, NO | Contact isolé du relais du groupe 2. Il se ferme lorsque le niveau de ventilation demandé est égal ou supérieur au seuil « Groupe de ventilation 2 ». Courant maximal du contact selon la notice fournie : 6 A. En cas de commande directe d’une charge, la documentation indique une protection externe B6. |
| INPUT: V, masse | Entrée de tension. Sélectionner « Type de commande → Entrée V ». Dans le programme analysé, la plage de régulation est de 2–10 V. Ne pas raccorder à cette entrée la tension secteur ni la sortie régulée d’alimentation des ventilateurs. |
| INPUT: I, masse | Entrée de courant 4–20 mA. Sélectionner « Type de commande → Entrée I ». Raccorder le signal conformément aux repérages de la source et du récepteur. |

Pour la commande, utiliser l’entrée V ou I sélectionnée. SC-PE16 nécessite sa propre alimentation secteur ; l’entrée analogique transmet uniquement la valeur de commande.

## Entrée ENABLE et communication

### ENABLE : E et masse

L’entrée fonctionne avec un contact libre de potentiel. Les bornes E et masse doivent uniquement être reliées ou séparées par ouverture du contact ; ne pas appliquer de tension externe. La fermeture autorise le fonctionnement, l’ouverture impose le niveau 0%. L’arrêt dépend du réglage « Temps de décélération ».

La prise en compte d’ENABLE s’active séparément pour AUTO et MANUAL dans le menu « Avancé → Ventilateur ». Les deux fonctions sont désactivées en usine ; aucun cavalier n’est alors nécessaire. L’ouverture d’ENABLE ne correspond pas à une mise en veille : le panneau reste actif. En AUTO, lorsque le blocage ENABLE est actif, le programme ignore la lecture du signal de commande et n’active pas safeRUN.

### CAN et Wi-Fi

Les options « Entrée CAN » et « Entrée WiFi » figurent dans le menu, mais n’assurent pas la commande dans le logiciel version 2.1 : les deux fonctions renvoient le niveau 0%. Pour mettre l’appareil en service avec ce programme, sélectionner l’entrée V ou I. Ne pas configurer l’installation sur la base de CAN ou de Wi-Fi sans confirmation de leur prise en charge par la version du logiciel installée.

## Principe de fonctionnement

SC-PE16 est un régulateur de puissance qui exécute les commandes du contrôleur maître ou de l’opérateur. Il ne mesure pas la température du local et ne possède pas de réglages propres de température, d’aération, de chauffage d’appoint ou de volets d’admission d’air. Le niveau de ventilation exprimé en pourcentage représente une valeur de commande et non une mesure de la vitesse réelle du moteur.

| SIGNAL NOMINAL | NIVEAU DE VENTILATION DEMANDÉ |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

Entre les valeurs limites, le programme détermine le niveau de manière linéaire et l’arrondit à un pourcentage entier. Pour l’entrée V, l’augmentation commence lorsque la valeur lue dépasse 2,04 V, et pour l’entrée I, 4,04 mA. L’état final de la sortie dépend également d’ENABLE, du démarrage et de la protection thermique.

## Fonctionnement de secours et protections

### safeRUN — perte du signal d’entrée

En mode AUTO, l’alarme « Entrée » apparaît lorsque la tension lue est inférieure à 1,50 V ou le courant inférieur à 2,00 mA, selon l’entrée sélectionnée. Le programme impose alors le niveau « Fonctionnement de secours » dans la plage 0–100% ; réglage d’usine 30%. Lorsque le signal revient au seuil de détection ou au-dessus, l’alarme d’entrée disparaît et l’appareil revient à la commande analogique.

Les plages 1,50–2,04 V et 2,00–4,04 mA donnent le niveau 0% sans alarme d’entrée. Dans cette version, le signal 0 V n’est pas une commande d’arrêt ordinaire — il déclenche le fonctionnement de secours. Le contrôleur maître doté d’une sortie 0–10 V doit être configuré pour la plage 2–10 V sans coupure à 0 V. En MANUAL, le signal analogique ne commande pas la ventilation et l’alarme d’entrée est effacée.

### Protection thermique

L’alarme « Surchauffe » est activée lorsque la température lue du dissipateur thermique dépasse 87°C. Elle est effacée lorsque la température descend en dessous de 80°C. Pendant l’alarme, le programme modifie le niveau demandé : pour une valeur au moins égale à 50%, il impose 100%, et pour une valeur inférieure à 50%, il impose 0%. La modification de la sortie est soumise à l’algorithme de démarrage et de décélération. La protection ne garantit pas le fonctionnement continu de la ventilation dans tous les cas.

L’état du relais GR 2 est déterminé avant la correction thermique : il dépend du niveau antérieur à l’imposition de 0% ou 100%. Le niveau de fonctionnement de secours est également soumis à la correction thermique. En cas de surchauffe, vérifier les conditions de refroidissement, l’encrassement du dissipateur thermique et la charge ; confier les travaux à l’intérieur du boîtier à une personne habilitée.

### byPASS et démarrage progressif

Lorsque le niveau de sortie est stabilisé à 100%, le programme active le relais de dérivation du circuit de régulation par angle de phase. Le démarrage peut comprendre une montée jusqu’à 100%, un maintien à 100% et un passage au niveau demandé. Les paramètres « Démarrage progressif » influent également sur la vitesse de réaction de la sortie à une modification de la demande.

## Première mise en service du contrôleur

:::warning Étalonnage des ventilateurs

Attention ! Lors de la première mise en service de l’appareil, il est impératif de régler la bande de fonctionnement interdite du moteur.

:::

1. L’alimentation étant coupée, vérifier les raccordements de l’alimentation, de PE, des ventilateurs et du signal analogique. Confirmer que les moteurs sont homologués pour la régulation par variation de tension et que le courant total ne dépasse pas 16 A.
2. Mettre sous tension. Si un choix de langue est proposé, appuyer sur OK et sélectionner la langue. Déverrouiller le clavier à l’aide de la touche portant le symbole du cadenas.
3. Dans « Type de commande », sélectionner « Entrée V » ou « Entrée I ». Régler le niveau « Fonctionnement de secours » et le seuil « Groupe de ventilation 2 ». Si nécessaire, activer ENABLE séparément pour le mode concerné.
4. Accéder à « Avancé → Ventilateur → Bande interdite ». Dans cette option, le programme impose le niveau 1% et toute modification du paramètre agit immédiatement sur la sortie. La plage s’étend de −20 à 200, avec un réglage d’usine de 0. Une valeur positive augmente le niveau minimal de commande, une valeur négative le diminue.
5. Choisir une valeur permettant à tous les ventilateurs de tourner de manière stable, sans arrêt ni échauffement excessif. Observer chaque ventilateur, de préférence avec l’aide d’une deuxième personne. Le simple soulèvement du volet ne remplace pas la vérification du bon fonctionnement du moteur. Valider avec OK ; ESC rétablit le réglage précédent.
6. Vérifier la sortie à plusieurs niveaux, notamment 0%, à un faible niveau et à 100%. Répéter l’étalonnage après le remplacement des ventilateurs ou une modification de leur configuration.
7. En AUTO, vérifier la réaction aux signaux minimal et maximal. Vérifier ensuite la coupure du signal et le passage au fonctionnement de secours, ainsi que le retour après rétablissement du signal. Si ENABLE est actif, vérifier également son fonctionnement.
8. Vérifier GR 2 et la signalisation d’alarme dans le menu « Tests ». À la fin des tests, quitter cette option et sélectionner le mode de fonctionnement prévu.

:::warning Activation réelle des sorties

Les tests et l’étalonnage commandent les sorties réelles. Ils peuvent démarrer les ventilateurs, et le test de ventilation impose un niveau indépendamment de la commande normale. Assurer des conditions d’essai sûres et une surveillance permanente.

:::

## Programmation du contrôleur

### Panneau avant — voyants et touches

| ÉLÉMENT | UTILISATION |
| --- | --- |
| Alimentation / veille | La touche portant le symbole d’alimentation affiche une demande de confirmation de mise en veille ; valider avec OK. Une nouvelle pression réveille l’appareil. La mise en veille impose l’état désactivé aux sorties ; elle ne coupe pas la tension secteur. |
| Cadenas | Active ou désactive le verrouillage du clavier. Après déverrouillage, le voyant situé près du cadenas s’allume. Sur l’écran principal, le verrouillage se réactive après environ 30 s d’inactivité. |
| A — AUTO | Sélectionne la commande par l’entrée analogique après validation avec OK. Le voyant A indique le mode sélectionné. |
| M — MANUAL | Sélectionne la commande manuelle après validation avec OK. Sur l’écran principal, les touches + et − modifient la consigne 0–100%. Le voyant M indique le mode sélectionné. |
| +, −, OK, ESC | OK ouvre le menu, accède à une option et valide une valeur. + et − sélectionnent une option ou modifient une valeur. ESC revient au niveau précédent ou annule la modification. |
| Alarme et groupe 2 | Le voyant rouge signale une alarme. Le voyant situé près du symbole de ventilateur « 2 » signale l’activation du relais GR 2. |
| Écran | En AUTO, il affiche le niveau de ventilation demandé, la valeur lue sur l’entrée sélectionnée, un bargraphe et les alarmes. Lorsque ENABLE est actif, il affiche également son état. En MANUAL, la valeur principale représente la consigne manuelle ; les protections peuvent modifier la sortie. |

### Mémorisation des réglages

Les paramètres du menu sont enregistrés dans la mémoire non volatile après validation avec OK. Les modifications du niveau MANUAL prennent effet immédiatement, et l’enregistrement intervient après une courte période d’inactivité. Après une coupure d’alimentation, les réglages enregistrés sont rétablis, notamment le mode AUTO/MANUAL, le niveau manuel et l’état de veille. Ne pas couper l’alimentation immédiatement après une modification de la consigne manuelle.

En cas de somme de contrôle incorrecte ou de valeur hors plage, le programme rétablit les valeurs d’usine. Il faut alors vérifier à nouveau tous les réglages, en particulier l’étalonnage des ventilateurs, l’entrée de commande et le fonctionnement de secours.

## Fonctions du menu de base

| MENU | PLAGE / RÉGLAGE D’USINE | DESCRIPTION |
| --- | --- | --- |
| Type de commande | Entrée V | Sélection de V, I, CAN ou Wi-Fi. Pour la version analysée, utiliser V (2–10 V) ou I (4–20 mA). CAN et Wi-Fi n’assurent pas la commande. |
| Groupe de ventilation 2 | 1–100% / 100% | Seuil de fermeture du contact GR 2. Le contact est fermé lorsque le niveau est égal ou supérieur au seuil, et ouvert en dessous du seuil. Le programme ne définit pas d’hystérésis distincte. |
| Fonctionnement de secours | 0–100% / 30% | Niveau imposé en cas de perte du signal analogique sélectionné en AUTO. La valeur 0% signifie l’arrêt en cas de perte du signal. |
| Verrouillage nettoyage | 60 s | Bloque l’utilisation des touches pendant 60 secondes et affiche un compte à rebours. La régulation de la ventilation continue de fonctionner. Cette fonction sert à essuyer le panneau, et non à effectuer des travaux électriques ou à laver l’intérieur. |
| Avancé | Sous-menu | Accès aux tests, à la langue, à l’étalonnage du ventilateur, à ENABLE, au démarrage progressif, au son de l’alarme, aux réglages d’usine et aux informations sur le programme. |

## Fonctions du menu avancé

| MENU / PARAMÈTRE | PLAGE / RÉGLAGE D’USINE | DESCRIPTION |
| --- | --- | --- |
| Tests → Ventilation | 0–100% | Forçage temporaire de la sortie régulée. Les modifications prennent effet pendant l’édition. Après sortie par OK ou ESC, la commande normale reprend. |
| Tests → Vent. étage 2 | Non / Oui | Forçage temporaire du contact GR 2 et de son voyant. |
| Tests → Alarme | Non / Oui | Test temporaire de la signalisation d’alarme, y compris sonore, indépendamment du réglage normal « Signal d’alarme ». |
| Langue | Polonais | Choix entre le polonais, l’anglais et l’ukrainien. |
| Ventilateur → Bande interdite | −20–200 / 0 | Étalonnage du niveau 1%. Pendant l’édition, la sortie réelle 1% est forcée. Le paramètre n’est exprimé ni en pourcentage ni en secondes. |
| Ventilateur → Activation EN AUTO | Non / Oui ; Non | Active la dépendance du mode AUTO à l’entrée ENABLE. |
| Ventilateur → Activation EN MANUAL | Non / Oui ; Non | Active la dépendance du mode MANUAL à l’entrée ENABLE. |
| Démarrage progressif → Temps d’accélération | 0–50 / 5 | Vitesse de montée du niveau au démarrage jusqu’à 100%. Une valeur plus élevée correspond à une variation plus lente. La valeur 0 supprime la phase de montée. |
| Démarrage progressif → Temps 100% | 0–250 / 100 | Maintien du niveau 100% pendant le démarrage. La valeur 0 supprime la phase de maintien. Le réglage simultané de l’accélération et du maintien sur 0 supprime la ventilation initiale jusqu’à 100%. |
| Démarrage progressif → Temps de décélération | 0–50 / 5 | Vitesse d’évolution vers le niveau demandé, y compris lors de sa modification. La valeur 0 correspond à une modification sans transition progressive. |
| Signal d’alarme | Non / Oui ; Non | Active le signal sonore d’alarme. Le réglage Non ne supprime ni le message à l’écran ni la signalisation par voyant. |
| Réglages d’usine | Non / Oui | Après sélection de Oui, rétablit et enregistre les valeurs par défaut, y compris l’étalonnage 0, l’entrée V, AUTO, le fonctionnement de secours 30%, le seuil GR 2 égal à 100% et ENABLE désactivé. Après l’opération, reconfigurer et vérifier l’appareil. |
| Programme | version 2.1 + date de compilation | Affiche la version et la date de compilation du programme. La présente description a été élaborée à partir des sources fournies SC_PX16_v02. |

Les paramètres de démarrage progressif sont des réglages sans unité des compteurs du programme, et non des durées exprimées en secondes. À 50 Hz, un pas correspond approximativement à (réglage + 1) × 20 ms : pour l’accélération et la décélération, il s’agit du temps de variation de 1 point de pourcentage ; pour « Temps 100% », du temps de maintien. La valeur 0 a la signification décrite dans le tableau. Les durées réelles dépendent de la phase de l’algorithme.

## Messages d’erreur et d’avertissement

| MESSAGE | SIGNIFICATION ET MESURES À PRENDRE |
| --- | --- |
| Entrée | Valeur lue trop faible du signal sélectionné en AUTO. L’appareil impose le fonctionnement de secours. Vérifier la source du signal, les câbles, la masse commune et la sélection V/I. |
| Surchauffe | Valeur lue du dissipateur thermique &gt;87°C ; effacement &lt;80°C. Ventilation imposée à 0% ou 100%, conformément à la description de la protection thermique. Vérifier le refroidissement et la charge. |
| Alimentation | Perturbation de la synchronisation du circuit de puissance avec le secteur. Vérifier l’alimentation et l’installation. En cas de coupure totale de l’alimentation, l’écran ne fonctionne pas. |
| Mémoire CRC | Erreur de somme de contrôle ou de plage des réglages enregistrés. Le programme rétablit les valeurs par défaut. Vérifier la configuration et répéter l’étalonnage ; si l’erreur se reproduit, contacter le service après-vente. |

## Remarques et avertissements

:::danger Couper l’alimentation

Lors de l’installation de l’appareil, il est impératif de couper l’alimentation électrique, car la tension présente sur certains composants est dangereuse pour la vie et la santé. Il est recommandé de confier l’installation à une personne qualifiée.

:::

Lire la notice avant l’installation et l’utilisation. Confier les réparations et les travaux à l’intérieur de l’appareil à du personnel habilité. La mise en veille, le verrouillage du clavier, ENABLE et la consigne 0% ne constituent pas une coupure de l’alimentation et ne garantissent pas des conditions sûres pour les travaux électriques.

Choisir les réglages de ventilation et de fonctionnement de secours en fonction des besoins des animaux et de l’installation. Contrôler régulièrement le fonctionnement réel de tous les ventilateurs. La signalisation SC-PE16 ne remplace pas une surveillance indépendante des conditions dans le bâtiment et des coupures d’alimentation. Le bornier présenté ne comporte pas de contact ALARM distinct destiné à une centrale.

:::note Élimination de l’appareil

À la fin de son utilisation, le produit ne doit pas être jeté avec les déchets municipaux non triés, mais éliminé conformément à la réglementation en vigueur (directives DEEE de l’Union européenne 2012/19/UE).

:::

Le produit a été fabriqué conformément aux exigences RoHS (directive de l’Union européenne 2011/65/UE).

## Caractéristiques techniques du contrôleur

| PARAMÈTRE | VALEUR |
| --- | --- |
| Alimentation / consommation propre | 230 V AC, 50 Hz / &lt;10 W |
| Courant total maximal de la sortie U | 16 A |
| Courant maximal du contact GR 2 | 6 A ; contact C–NO, isolé |
| Entrée V / entrée I | 2–10 V / 4–20 mA, sélection dans le menu |
| Seuil de perte du signal (valeur lue par le programme) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Contact libre de potentiel E–masse ; activation séparée pour AUTO/MANUAL |
| Protection thermique (valeur lue du dissipateur thermique) | Alarme &gt;87°C ; retour &lt;80°C |
| Température ambiante / boîtier | −10°C à +40°C / IP65 |
| Dimensions / tenue aux surtensions | 34 × 29 × 12 cm / 210 J |
| Langues du menu | Polonais, anglais, ukrainien |

Contenu du kit selon la documentation fournie : 4 chevilles à expansion, 2 presse-étoupes PG13,5, 1 presse-étoupe PG9 et 1 charnière.

## Conditions de garantie

Le contenu des conditions de garantie a été conservé à partir du document fourni par le fabricant.

1. Le fabricant ELETOR, dont le siège est en Pologne, à l’adresse : Pod Sosno 28, 87-305 Zbiczno (ci-après dénommé le garant), accorde à l’Acheteur une garantie de qualité du produit pour lequel la présente carte de garantie a été établie, sous réserve d’une utilisation conforme à sa destination et aux règles définies dans la notice d’utilisation remise à l’Acheteur avec ce produit.
2. La période de garantie est de 24 mois à compter de la date de vente. Les dysfonctionnements ou défauts du produit révélés pendant cette période seront éliminés gratuitement. Après l’expiration de la période de garantie ou en cas de perte des droits à la garantie, les dysfonctionnements ou défauts seront éliminés à titre payant.
3. La garantie ne couvre pas :

   - tout défaut survenu en raison d’une mauvaise utilisation du produit (y compris l’exécution d’opérations non décrites dans la notice d’utilisation, etc.) ;

   - tout défaut résultant d’une réparation, d’une modification, etc., effectuée par une personne autre que le garant ;

   - tout défaut ou dommage résultant du transport ou de la chute du produit, si ces événements ont eu lieu après l’achat du produit, ainsi que les dommages mécaniques dus à une mauvaise manipulation par l’utilisateur ;

   - tout défaut ou dommage résultant d’un incendie, d’un tremblement de terre, d’une inondation, de la foudre ou d’autres catastrophes naturelles, de la pollution de l’environnement, de l’action d’un rayonnement ionisant externe ou d’un champ magnétique, ainsi que d’une alimentation électrique irrégulière ou présentant des caractéristiques non conformes aux exigences ;

   - tout défaut résultant d’un stockage incorrect (par exemple, stockage du produit en dehors de la plage de température ou d’humidité indiquée dans les spécifications, à proximité de produits chimiques), d’un entretien ou d’un nettoyage inapproprié, etc. ;

   - tout défaut résultant de l’épuisement des piles d’alimentation, etc. ;

   - tout défaut causé par du sable, de la boue, des poussières, de l’eau et d’autres liquides, etc., ayant pénétré à l’intérieur du boîtier du produit ;

   - les dommages résultant de l’usure naturelle, partielle ou totale du produit, conformément à ses propriétés ou à sa destination ;

   - les opérations indiquées dans la notice d’utilisation que l’utilisateur est tenu d’effectuer lui-même.

4. L’Acheteur perd ses droits à la garantie dans les cas suivants :

   - réalisation de toute réparation ou modification du produit par une personne autre que le garant ;

   - constatation de l’altération, de la détérioration ou de la rupture de l’un quelconque des scellés ;

   - constatation de la détérioration, de l’altération, du masquage ou de la suppression des numéros de série ou d’autres marquages permettant d’identifier le produit.

5. Le délai de réparation est de 21 jours ouvrables au maximum à compter de la date de signalement du défaut et de la livraison du produit complet au centre de service du garant. Dans des cas particulièrement justifiés, liés à la nécessité de faire venir de l’étranger des éléments ou des sous-ensembles, ou à un dommage particulièrement complexe ou difficile à réparer ou à diagnostiquer, le délai de réparation peut être prolongé de la durée nécessaire à l’exécution des obligations de garantie.
6. Les droits de l’Acheteur au titre de la garantie ne peuvent être exercés que sur présentation d’une carte de garantie valide et correctement remplie le jour de l’achat, ainsi que d’une preuve d’achat (facture, ticket de caisse, etc.). Toute modification non autorisée des mentions figurant sur la carte de garantie (y compris les ratures, effacements, ajouts, etc.) entraîne la perte des droits au titre de la garantie. Une carte de garantie ne comportant pas le nom, le modèle, le numéro de série du produit, la date et le lieu d’achat du produit, ainsi qu’un cachet lisible et la signature du Vendeur, est invalide et ne permet pas de déposer valablement une réclamation.
7. L’Acheteur est tenu de livrer le produit à ses frais dans un emballage adapté à l’équipement, assurant un transport et un stockage sûrs et appropriés, ou de prendre en charge les frais de déplacement du garant. S’il est constaté que le produit remis pour réparation est techniquement en état de fonctionnement et exempt de défauts, ou si le dysfonctionnement constaté n’est pas couvert par la garantie, les frais de service et de transport sont facturés à l’Acheteur.
8. L’Acheteur est tenu de retirer le produit réparé dans un délai de 90 jours à compter de la notification de la réparation par le garant. Si l’acheteur ne retire pas le produit dans ce délai, il supporte le risque de perte ou de détérioration accidentelle du produit.
9. La période de garantie est prolongée de la durée de la réparation, calculée à compter de la date de livraison du produit jusqu’à la date convenue pour son retrait après réparation. Le garant est tenu de délivrer un document précisant la période et l’étendue des défauts du produit éliminés.

10. L’Acheteur adresse ses réclamations par l’intermédiaire du Vendeur du produit ou directement à l’adresse du garant : ELETOR, Pod Sosno 28, 87-305 Zbiczno, Pologne.

11. Le garant décline toute responsabilité :

    - pour les pertes de revenus résultant de l’apparition d’un défaut et du temps nécessaire à son élimination ;

    - pour les pertes résultant de l’apparition d’un défaut et pour tous les dommages résultant d’une installation, d’une utilisation ou d’une programmation incorrecte des fonctions de l’appareil.
