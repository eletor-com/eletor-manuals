---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Questions les plus fréquentes concernant le choix, la configuration,
  le diagnostic et le service après-vente des appareils ELETOR.
keywords:
- ELETOR
- FAQ
- contrôleurs de ventilation
- régulateurs
- ventilateurs
- actionneurs
- alarmes
- variateurs de fréquence
- service après-vente
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Questions fréquemment posées

Cette FAQ a été élaborée à partir d’une analyse anonymisée de conversations réelles avec les utilisateurs et les clients de ELETOR. Les réponses ont été généralisées afin d’apporter une aide dans les cas courants et de ne contenir aucune donnée concernant des personnes ou des installations particulières.

:::note Champ d’application de la FAQ

Les réponses concernent les cas courants. Les désignations des bornes, les fonctions et les modalités de raccordement peuvent varier selon les modèles et les versions des appareils. En cas de doute, consultez la documentation correspondant au produit concerné.

:::

:::warning Sécurité

Effectuez les travaux sur l’installation électrique conformément à la documentation de l’appareil et aux règles de sécurité en vigueur. Les travaux sous tension secteur doivent être effectués par une personne possédant les qualifications appropriées.

:::

## Choix du contrôleur et de la puissance

### Comment choisir un contrôleur pour les ventilateurs ?

Le choix repose avant tout sur le courant total des ventilateurs, et non uniquement sur leur nombre.

:::tip Préparez les données avant de faire votre choix

Plus les données concernant les moteurs et le mode de fonctionnement de l’installation sont précises, plus le choix du contrôleur est fiable.

:::

Avant de faire votre choix, il est utile de préparer :

- le nombre de ventilateurs,
- la tension d’alimentation,
- la puissance ou le courant nominal de chaque ventilateur,
- l’information indiquant si tous les ventilateurs doivent fonctionner avec une régulation continue,
- l’information indiquant si les ventilateurs peuvent être répartis en groupes,
- les informations sur les appareils supplémentaires, par exemple les appareils de chauffage ou les entrées d’air.

Le contrôleur ne doit pas être dimensionné exactement à la limite de ses capacités. Il convient de conserver une marge appropriée par rapport à la charge maximale.

### Suffit-il d’additionner la puissance des ventilateurs en watts ?

La puissance peut servir à une estimation préliminaire, mais le choix définitif doit reposer sur le courant nominal des appareils et sur la nature de la charge.

Au démarrage, un moteur peut consommer davantage de courant qu’en fonctionnement normal. C’est pourquoi deux ensembles de ventilateurs présentant une puissance nominale similaire ne constituent pas toujours une charge équivalente pour le contrôleur.

### J’ai plusieurs petits ventilateurs. Puis-je les raccorder en parallèle à une seule sortie ?

Oui, à condition que :

- ils soient conçus pour ce mode de commande,
- ils doivent fonctionner ensemble,
- la somme des charges ne dépasse pas le courant admissible de la sortie,
- le raccordement soit conforme à la documentation du contrôleur.

Lorsque le nombre de ventilateurs est important, il est utile d’envisager leur répartition en groupes ou l’utilisation d’une extension de puissance.

### Quand une extension de puissance est-elle nécessaire ?

Une extension de puissance est utilisée lorsque la charge dépasse les capacités de la sortie du contrôleur ou lorsque l’installation doit être agrandie par l’ajout de ventilateurs.

Le contrôleur transmet alors le signal de commande, tandis que la charge proprement dite est prise en charge par un module supplémentaire.

### Peut-on agrandir ultérieurement l’installation en ajoutant des ventilateurs ?

Oui, dans de nombreuses installations. Les solutions les plus courantes sont :

- une extension de puissance supplémentaire,
- un groupe de ventilation supplémentaire,
- un contacteur mettant en marche un groupe supplémentaire,
- un variateur de fréquence dans le cas de moteurs triphasés.

Il est préférable de prévoir l’extension envisagée dès le choix initial du contrôleur.

### Tous les ventilateurs doivent-ils fonctionner avec une régulation continue ?

Non. Deux solutions sont courantes :

1. tous les ventilateurs fonctionnent avec une régulation continue,
2. le premier groupe fonctionne avec une régulation continue, tandis que les groupes suivants sont mis en marche par paliers, par exemple au moyen de contacteurs.

La deuxième solution permet de gérer une installation plus importante sans régulation continue de chaque ventilateur.

### J’ai 10 ventilateurs. Ai-je besoin d’un contrôleur de très grande capacité ?

Pas toujours. Plusieurs modes de commande peuvent être utilisés :

- la répartition en groupes,
- les extensions de puissance,
- les contacteurs,
- un variateur de fréquence.

Le choix définitif dépend des caractéristiques électriques des ventilateurs et de la nécessité ou non de faire varier simultanément la vitesse de tous les ventilateurs.

### Les contrôleurs 6 A et 12 A diffèrent-ils uniquement par leur charge admissible ?

Il ne faut pas supposer que la seule différence est la valeur du courant. Les différentes versions et générations d’appareils peuvent présenter des différences d’équipement ou de conception.

Lors du remplacement d’un appareil, il convient de vérifier le modèle exact et la documentation actuelle.


## Ventilateurs et commande de la ventilation

### Le contrôleur assure-t-il une régulation continue des ventilateurs ?

Dans les contrôleurs conçus pour la régulation continue de la ventilation, la vitesse des ventilateurs varie en fonction des besoins résultant notamment de la température.

Il convient toutefois de vérifier que le type de moteur concerné est adapté au mode de régulation utilisé.

### Que signifie la température de consigne ?

La température de consigne est la valeur à laquelle le contrôleur compare la mesure actuelle de la température.

Sur cette base, le contrôleur augmente ou diminue l’intensité de la ventilation conformément aux autres réglages, par exemple la bande de régulation et les niveaux minimal et maximal.

### Que signifie le niveau minimal de ventilation ?

Il s’agit de la valeur minimale de commande du ventilateur en fonctionnement automatique.

Ce réglage empêche le fonctionnement en dessous d’un niveau auquel le ventilateur pourrait fonctionner de manière instable ou assurer un renouvellement d’air insuffisant.

### Que signifie le niveau maximal de ventilation ?

Il s’agit de la limite supérieure de la valeur de commande de la ventilation.

Par exemple, le réglage d’une valeur inférieure à 100% peut limiter la vitesse maximale du ventilateur si l’installation l’exige.

### Que signifie la bande de ventilation ?

La bande de ventilation définit la plage de températures dans laquelle le contrôleur passe du niveau minimal au niveau maximal de ventilation.

Plus la bande est étroite, plus la commande réagit rapidement à une variation de température en augmentant le débit.

### Après le démarrage, le ventilateur atteint d’abord 100%, puis ralentit. Pourquoi ?

Une fonction de démarrage peut être active ; elle sert à faire démarrer brièvement le moteur à une puissance plus élevée.

Selon la version du contrôleur, il convient de vérifier les réglages liés :

- à la fonction Soft Start,
- au temps d’accélération,
- au temps de fonctionnement à 100%,
- au temps de décélération.

Si cette fonction n’est pas nécessaire dans l’installation concernée, les paramètres correspondants peuvent être modifiés conformément à la notice de l’appareil.

### Pourquoi le ventilateur peut-il être brièvement mis en marche à pleine puissance au démarrage ?

Ce type de démarrage peut faciliter un démarrage fiable du ventilateur ainsi que le fonctionnement dans les installations où les éléments mécaniques peuvent opposer une résistance plus importante au démarrage.

Cela n’est toutefois pas nécessaire dans toutes les installations.

### Que signifient le temps d’accélération et le temps de décélération ?

**Le temps d’accélération** définit la manière dont la commande augmente pendant le démarrage du ventilateur.

**Le temps de décélération** définit la manière dont la vitesse diminue.

Ces deux paramètres permettent de limiter les variations brusques de vitesse et de fonctionnement de l’installation.

### Pourquoi deux contrôleurs identiques peuvent-ils démarrer les ventilateurs différemment ?

La cause la plus fréquente est une différence de réglages.

Il est utile de comparer en priorité :

- la température de consigne,
- la bande de ventilation,
- le minimum et le maximum,
- les réglages de Soft Start,
- les temps d’accélération et de décélération,
- la configuration des groupes de ventilation.

### Le contrôleur peut-il mettre périodiquement la ventilation en marche indépendamment de la température ?

Selon le modèle, une fonction d’aération périodique est disponible.

Elle peut mettre la ventilation en marche pendant une durée déterminée, à des intervalles définis, même lorsque la régulation de température ne nécessite pas d’augmentation de la ventilation.

### À quoi servent les groupes de ventilation ?

Les groupes permettent d’augmenter le débit de l’installation par paliers.

Par exemple :

- le groupe 1 fonctionne avec une régulation continue,
- le groupe 2 met en marche des ventilateurs supplémentaires,
- le groupe suivant se met en marche lorsque les besoins augmentent encore.

Cela permet de commander un grand nombre de ventilateurs sans régulation continue de chacun d’eux.

### Peut-on mettre en marche un groupe supplémentaire de ventilateurs au moyen d’un contacteur ?

Oui. La sortie à relais du contrôleur peut commander la bobine d’un contacteur correctement dimensionné.

Dans ce cas, le courant de charge des ventilateurs ne doit pas passer directement par le petit contact de commande.

### Que signifie le symbole du ventilateur ou le voyant jaune sur le contrôleur ?

Selon le modèle, les voyants indiquent l’état actuel des sorties et des fonctions.

Une signalisation jaune peut indiquer une fonction de travail active, par exemple le fonctionnement de la ventilation, du chauffage ou d’un groupe supplémentaire.

La signification exacte doit être vérifiée dans la notice du modèle concerné.

### Que signifie le symbole du mode manuel ?

Le mode manuel signifie que la valeur de commande a été imposée par l’utilisateur et n’est pas, à cet instant, calculée automatiquement à partir de la température.

À la fin des essais, il convient de s’assurer que le contrôleur a été rétabli dans le mode automatique approprié.


## Entrées d’air et actionneurs

### Le contrôleur peut-il commander les entrées d’air ?

Oui, certains contrôleurs permettent de fonctionner avec les motorisations des entrées d’air.

Le raccordement dépend du type d’actionneur et de son mode de commande.

### Quels types d’actionneurs peut-on utiliser pour les entrées d’air ?

Deux solutions ont été le plus fréquemment évoquées dans les conversations techniques :

- un actionneur commandé par un signal analogique 0–10 V ou 2–10 V,
- un actionneur réversible ouverture/fermeture avec un signal de retour, par exemple provenant d’un potentiomètre.

Avant l’achat, il convient de vérifier la compatibilité du modèle concerné avec le contrôleur utilisé.

### La tension d’alimentation de l’actionneur 24 V ou 230 V a-t-elle une incidence sur le signal 0–10 V ?

Le signal de commande et l’alimentation de l’actionneur sont des paramètres distincts.

L’actionneur peut être alimenté par une tension différente de celle du signal de commande. Les deux paramètres doivent être conformes à la documentation de l’actionneur et du contrôleur.

### Que signifie la commande 0–10 V ?

Le contrôleur envoie un signal analogique en tension représentant la position souhaitée ou le niveau de commande.

Dans une application courante, une valeur plus basse correspond à une ouverture plus faible, et une valeur plus élevée à une ouverture plus grande, mais la caractéristique réelle doit être vérifiée dans la documentation de l’actionneur.

### Quelle est la différence entre 0–10 V et 2–10 V ?

Dans les deux cas, la position est définie par un signal analogique.

Dans le standard 2–10 V, la partie inférieure de la plage est décalée et peut permettre à l’appareil de distinguer le signal de commande de son absence.

Le contrôleur et l’actionneur doivent prendre en charge une plage compatible.

### Comment choisir un actionneur en fonction du nombre d’entrées d’air ?

Il ne faut pas choisir l’actionneur uniquement en fonction du nombre de volets.

Il faut tenir compte :

- de la force ou du couple requis,
- de la longueur et du cheminement du mécanisme,
- de la résistance des volets,
- de la longueur de course,
- de la vitesse de fonctionnement,
- de la tension d’alimentation,
- du type de commande,
- du retour requis.

### Un seul actionneur peut-il commander plusieurs volets ?

Oui, si la mécanique de l’installation permet de relier les volets par un système commun et si le couple ou la force requis ne dépasse pas les capacités de l’actionneur.

En pratique, le choix dépend de la résistance de l’ensemble du mécanisme, et non du seul nombre de volets.

### Peut-on raccorder plusieurs actionneurs en parallèle et les commander par un seul signal ?

Cela est possible dans certains systèmes, mais il convient de vérifier la documentation des actionneurs et la charge admissible de la sortie de commande.

Dans le cas de motorisations réversibles sans retour indépendant, les positions des différents actionneurs peuvent également se décaler progressivement.

### Pourquoi plusieurs actionneurs peuvent-ils adopter des positions différentes avec le temps ?

Même des moteurs identiques peuvent fonctionner à des vitesses légèrement différentes en raison :

- de charges différentes,
- de résistances mécaniques,
- des tolérances des paramètres du moteur,
- de différences entre les réducteurs.

C’est pourquoi, lorsqu’une synchronisation précise est requise, un retour approprié ou un contrôle individuel de la position est nécessaire.

### Les entrées d’air peuvent-elles être commandées proportionnellement à la ventilation ?

Oui. Dans les systèmes correctement configurés, la position des entrées d’air peut être liée au niveau actuel de ventilation.

Ainsi, l’ouverture des entrées d’air augmente également lorsque le débit des ventilateurs augmente.

### L’actionneur 24 V nécessite-t-il une alimentation séparée ?

Si le contrôleur ne dispose pas d’une sortie d’alimentation appropriée offrant la puissance requise, une alimentation séparée est nécessaire.

Sa puissance doit être dimensionnée en fonction du courant consommé par l’actionneur et par les autres appareils alimentés à partir de la même source.

### Peut-on utiliser un actionneur d’une autre marque ?

Souvent oui, si ses caractéristiques électriques et son mode de commande sont compatibles avec les sorties du contrôleur.

Avant le raccordement, il convient de vérifier :

- la tension,
- le type de signal,
- le schéma de câblage,
- les sens de fonctionnement,
- le signal de position,
- la charge admissible.


## Capteurs de température et d’humidité

### Où raccorder le capteur de température ?

Le capteur doit être raccordé à l’entrée pour capteur prévue par le fabricant, à l’entrée pour capteur indiquée dans la documentation du modèle concerné.

Il ne faut pas supposer que les désignations des bornes sont identiques dans toutes les versions des appareils.

### Le capteur de température indique une valeur différente de celle du thermomètre de référence. Que faire ?

Si le contrôleur dispose d’une fonction d’étalonnage du capteur, l’indication peut être corrigée après comparaison avec un thermomètre de référence fiable.

Avant de modifier l’étalonnage, il est utile de s’assurer que :

- les deux capteurs se trouvent au même endroit,
- la mesure s’est stabilisée,
- le capteur n’est pas chauffé par le soleil ou par des appareils,
- il ne se trouve pas directement dans un flux d’air froid ou chaud.

### Le capteur d’humidité indique une valeur incorrecte. Peut-on l’étalonner ?

Cela dépend de la version du contrôleur, du capteur et du logiciel.

Dans certaines solutions, la correction peut nécessiter une fonction logicielle appropriée ou un type de capteur compatible. Si l’écart est important et répétable, il convient de vérifier la version de l’appareil et de contacter l’assistance technique.

### Une mesure incorrecte signifie-t-elle toujours que le capteur est défectueux ?

Non.

La cause peut également être :

- un emplacement inapproprié du capteur,
- le câble,
- le raccordement électrique,
- la configuration,
- un type de capteur inadapté,
- la nécessité d’un étalonnage,
- l’humidité ou la corrosion.


## Alarmes et notifications

### Peut-on raccorder directement une sirène à la sortie d’alarme du contrôleur ?

Il ne faut pas le supposer.

La sortie d’alarme du contrôleur est généralement une sortie de commande ou un contact de relais. La sirène peut nécessiter une alimentation séparée et une centrale d’alarme.

### Pourquoi utilise-t-on une centrale d’alarme ?

La centrale peut :

- recevoir les signaux d’alarme des contrôleurs,
- alimenter le dispositif de signalisation,
- maintenir le fonctionnement pendant une coupure d’alimentation,
- signaler une alarme par un signal sonore ou lumineux,
- envoyer des notifications GSM dans les versions disposant de cette fonction.

### La centrale peut-elle signaler une coupure d’alimentation du contrôleur ?

Oui, si le système a été correctement raccordé.

La solution peut détecter non seulement un dépassement de température, mais aussi la perte du signal du contrôleur causée par une coupure de son alimentation.

### Où règle-t-on les températures minimale et maximale d’alarme ?

Dans une configuration courante, les seuils d’alarme sont réglés dans le contrôleur qui gère la chambre ou le local concerné.

La centrale d’alarme reçoit ensuite l’information indiquant que le contrôleur a signalé une alarme.

### La centrale GSM nécessite-t-elle une carte SIM ?

Pour émettre des appels et envoyer des messages via le réseau mobile, une carte SIM active ou une autre solution de communication prévue dans le modèle concerné est nécessaire.

Sans connexion active au réseau mobile, les fonctions téléphoniques et SMS ne fonctionneront pas.

### Le système d’alarme peut-il indiquer de quel contrôleur provient l’événement ?

Oui, dans un système correctement configuré.

Les entrées de la centrale peuvent être attribuées à des locaux ou à des contrôleurs précis, ce qui permet au message d’identifier la source de l’alarme.

### Combien de contrôleurs peut-on raccorder à une seule centrale d’alarme ?

Cela dépend du modèle de la centrale.

Les transcriptions mentionnaient des centrales prenant en charge jusqu’à huit entrées ; toutefois, avant de réaliser l’installation, il convient de vérifier les spécifications actuelles de l’appareil concerné.

### Quel accumulateur est utilisé dans la centrale d’alarme ?

Certains appareils évoqués dans les conversations utilisaient un accumulateur 12 V 7 Ah.

Avant d’acheter un accumulateur de remplacement, il convient de vérifier le marquage de l’accumulateur existant et les spécifications de la centrale, car d’autres versions des appareils peuvent nécessiter un accumulateur différent.

### La centrale envoie des messages de tension faible. Que vérifier ?

Il convient de vérifier en premier lieu :

- l’état de l’accumulateur,
- son âge,
- les connexions de l’accumulateur,
- la présence de l’alimentation secteur,
- le fonctionnement du chargeur ou de l’alimentation de la centrale.

Un accumulateur usé peut provoquer des messages cycliques de tension faible.

### À quelle fréquence faut-il remplacer l’accumulateur de la centrale d’alarme ?

Il n’existe pas de périodicité unique adaptée à toutes les conditions.

L’accumulateur doit être testé périodiquement, en particulier dans les installations où l’alarme en cas de coupure d’alimentation est critique. Sa capacité réelle diminue avec l’âge.

### Une sirène seule suffit-elle comme protection ?

La sirène n’est efficace que si quelqu’un peut l’entendre.

Dans les bâtiments temporairement laissés sans surveillance, il est utile de prévoir également une notification à distance et une alimentation de secours par accumulateur.


## Variateurs de fréquence

### Comment choisir un variateur de fréquence pour les ventilateurs ?

Il faut connaître :

- la tension d’alimentation,
- le nombre de phases,
- la puissance et le courant de tous les moteurs,
- leur mode de raccordement,
- les conditions de fonctionnement,
- le mode de commande requis.

Le variateur de fréquence doit disposer d’une marge appropriée par rapport à la charge, en particulier lorsque plusieurs moteurs fonctionnent en parallèle.

### Le variateur de fréquence doit-il avoir exactement la même puissance que la somme des puissances des moteurs ?

Il ne faut pas dimensionner le variateur de fréquence uniquement à partir d’une simple addition des puissances, ni choisir un appareil fonctionnant exactement à la limite de ses caractéristiques.

Il convient de tenir compte des courants nominaux, de la nature de la charge et des recommandations du fabricant du variateur de fréquence.

### Le variateur de fréquence a arrêté les ventilateurs et affiché une erreur. Que faire ?

Le plus important est de noter le code d’erreur complet avant la réinitialisation.

:::tip Prenez une photo de l’écran

Si la situation le permet, prenez une photo de l’afficheur avant la réinitialisation. Le code d’erreur complet facilite considérablement le diagnostic.

:::

Le début du message ne suffit souvent pas à déterminer la cause. Le code complet permet notamment de distinguer :

- une surcharge,
- une surintensité,
- une surchauffe,
- une tension incorrecte,
- d’autres erreurs de l’entraînement.

### Peut-on simplement réinitialiser l’erreur du variateur de fréquence ?

La réinitialisation peut rétablir le fonctionnement, mais elle ne supprime pas la cause de l’alarme.

Après l’événement, il convient de vérifier le code d’erreur et d’en déterminer la cause avant de remettre l’installation en marche pour une durée prolongée.

### Le variateur de fréquence fonctionne dans un local poussiéreux. Faut-il le nettoyer ?

Oui.

La poussière et les dépôts sur le dissipateur thermique ou sur le ventilateur de refroidissement peuvent réduire la dissipation de chaleur et provoquer une surchauffe du variateur de fréquence.

Le nettoyage doit être effectué conformément à la notice du fabricant, après avoir déconnecté l’alimentation en toute sécurité.

### Quelles peuvent être les causes d’une surchauffe du variateur de fréquence ?

Les causes les plus fréquentes sont :

- des éléments de refroidissement encrassés,
- une circulation d’air obstruée,
- une température ambiante trop élevée,
- une surcharge,
- un ventilateur de refroidissement défectueux,
- un montage incorrect.

### Une tension secteur élevée peut-elle déclencher une alarme du variateur de fréquence ?

Oui. Les variateurs de fréquence surveillent la tension du circuit d’alimentation et peuvent signaler une erreur lorsque le niveau admissible est dépassé.

Si le problème se répète, il convient de contrôler l’installation et la qualité de l’alimentation.


## Pannes et diagnostic

### Le contrôleur fonctionne, mais l’afficheur n’affiche rien. Quelle peut en être la cause ?

Les causes possibles comprennent notamment :

- une défaillance de l’afficheur,
- un problème de réglage du contraste dans les solutions plus anciennes,
- une connexion endommagée,
- de la corrosion,
- une défaillance de la carte principale.

Si l’appareil n’a pas été utilisé pendant longtemps ou a fonctionné dans un environnement humide, il est également utile de vérifier l’état de la carte.

### Le contrôleur présente un problème d’affichage après plusieurs années sans utilisation. Pourquoi ?

Une période d’arrêt prolongée dans un environnement humide ou agressif peut entraîner :

- l’oxydation des connecteurs,
- de la corrosion,
- une dégradation des contacts,
- des dommages aux composants électroniques.

Dans ce cas, il est utile de procéder à une inspection complète plutôt que de remplacer des composants sans diagnostic préalable.

### Le contrôleur est noirci après une surtension. Cela signifie-t-il que la carte doit être remplacée ?

Pas toujours.

Un composant de protection peut être endommagé et laisser de nombreux dépôts, alors que le reste de la carte peut encore être réparé.

Toutefois, si le stratifié est carbonisé ou brûlé, ou si les pistes sont endommagées, la réparation peut ne pas être rentable ou durable.

### Qu’est-ce qui peut endommager plusieurs contrôleurs simultanément ?

Si plusieurs appareils tombent en panne en même temps, il convient de vérifier l’installation d’alimentation.

L’une des causes possibles est un problème du conducteur neutre qui, dans une installation triphasée, peut provoquer des tensions incorrectes aux bornes des récepteurs monophasés.

Des surtensions provenant du réseau ou du groupe électrogène sont également possibles.

### Que faire après une panne liée à une surtension ?

Avant de raccorder un contrôleur réparé ou neuf, il convient de déterminer la cause du problème.

:::danger Ne raccordez pas de nouveau l’appareil sans vérifier l’installation

Si la panne a été causée par une tension incorrecte, un conducteur neutre endommagé ou une surtension, le contrôleur réparé ou neuf peut être de nouveau endommagé.

:::

### Qu’est-ce qu’un composant de protection contre les surtensions sur la carte ?

Les appareils électroniques utilisent des composants limitant les surtensions, par exemple des varistances.

Leur rôle est d’absorber une partie de l’énergie de la surtension et de protéger les circuits en aval. Après un événement important, un tel composant peut subir des dommages permanents.

### Peut-on mettre l’appareil en marche après avoir retiré le composant de protection brûlé ?

Cela ne doit pas être considéré comme une réparation normale.

Après le retrait de la protection, l’appareil peut perdre sa protection contre une nouvelle surtension. De telles opérations ne peuvent être effectuées que dans le cadre d’une procédure de maintenance délibérée, par une personne possédant les qualifications appropriées et après élimination de la cause de la panne initiale.

### Le contrôleur a subi une infiltration d’eau ou une forte corrosion. Vaut-il la peine de le réparer ?

Cela dépend de l’étendue des dommages.

La corrosion superficielle et les dommages isolés peuvent souvent être éliminés. Si la corrosion a atteint les pistes, les connecteurs et de nombreux composants, la réparation peut être longue, incertaine et économiquement injustifiée.

### Le lavage sous pression de l’appareil peut-il endommager le contrôleur ?

Oui.

L’électronique ne doit pas être exposée directement à l’eau ou à un produit de nettoyage si le boîtier et le mode de montage ne sont pas prévus à cet effet.

L’humidité pénétrant à l’intérieur peut provoquer de la corrosion et des défauts ultérieurs difficiles à diagnostiquer.

### Pourquoi les défauts consécutifs à une infiltration d’eau peuvent-ils réapparaître après la réparation ?

La corrosion peut également progresser dans des endroits non visibles lors du premier contrôle.

Les vias, pistes et connexions endommagés peuvent fonctionner pendant l’essai, puis perdre de nouveau le contact.

C’est pourquoi, dans le cas d’une carte fortement corrodée, le service après-vente peut recommander un remplacement plutôt que de nouvelles réparations.

### L’appareil fonctionne de manière intermittente. Par quoi commencer ?

Avant de contacter le service après-vente, il est utile de réunir :

- le modèle exact,
- une description du symptôme,
- le moment de son apparition,
- les valeurs affichées à l’écran,
- le code d’alarme ou d’erreur,
- les informations sur les dernières modifications de l’installation,
- une photo de l’intérieur et des bornes, si elle peut être prise en toute sécurité.

Plus la description est précise, plus le diagnostic est facile.


## Service après-vente et réparations

### Que faut-il envoyer au service après-vente si le contrôleur est défectueux ?

Il est préférable d’envoyer un ensemble permettant de reproduire le problème.

Il convient de joindre à l’envoi une brève description indiquant :

- ce qui ne fonctionne pas,
- quand le problème apparaît,
- si la panne est permanente ou intermittente,
- si une surtension, une infiltration d’eau ou un autre événement a précédé la panne,
- les coordonnées nécessaires pour vous contacter et retourner l’appareil.

:::note Données pour la demande d’intervention

Transmettez directement au service après-vente les coordonnées de contact et d’expédition. Ne les publiez pas dans des demandes accessibles à tous ni dans des documents publics.

:::

### Faut-il envoyer le contrôleur complet ou uniquement la carte ?

Cela dépend du défaut.

En cas de problèmes d’affichage, de boutons, d’alimentation ou de comportement ambigu, il est préférable d’envoyer l’ensemble nécessaire pour reproduire le symptôme.

Dans le cadre d’une réparation préalablement convenue d’un module précis, le service après-vente peut demander uniquement la carte.

### ELETOR répare-t-il les contrôleurs plutôt que de les remplacer immédiatement ?

Les transcriptions indiquent que les appareils font d’abord l’objet d’un diagnostic.

Si la réparation est possible et pertinente, les composants ou modules défectueux sont remplacés. En cas de dommages importants, le service après-vente peut proposer le remplacement de la carte ou de l’appareil complet.

### Que se passe-t-il si la carte endommagée ne peut pas être réparée ?

Le module endommagé peut être remplacé par un neuf, à condition que la pièce appropriée soit disponible et compatible avec l’appareil.

Pour les appareils plus anciens, le service après-vente doit d’abord confirmer la compatibilité des versions.

### Vaut-il la peine d’acheter immédiatement une carte neuve après une surtension ?

Pas toujours.

Si les dommages concernent un composant de protection ou une petite partie du circuit, la réparation peut être justifiée. Il est utile de procéder d’abord à un diagnostic.

### Le service après-vente peut-il également vérifier l’afficheur et les boutons ?

Oui, si ces éléments sont fournis avec l’appareil ou le module.

Cela est particulièrement utile lorsqu’on ne sait pas si le problème se situe sur la carte principale ou dans le panneau utilisateur.

### Vaut-il toujours la peine de récupérer un contrôleur fortement corrodé ?

Non.

Si le coût du diagnostic et de la réparation augmente et que la fiabilité après réparation reste incertaine, le remplacement peut être plus judicieux.

Cela concerne particulièrement les appareils dont dépend la ventilation du bâtiment.

### Comment accélérer le diagnostic du service après-vente ?

Joignez une description précise du symptôme plutôt que la simple mention « ne fonctionne pas ».

Les éléments suivants sont également utiles :

- des photos,
- le code d’erreur,
- une description de l’installation,
- le type de récepteurs raccordés,
- une information sur une surtension ou une coupure d’alimentation,
- une information sur une infiltration d’eau ou un lavage de l’appareil.


## Installation et câblage

### Comment raccorder les appareils aux bornes de relais C et NO ?

C et NO sont des désignations courantes des contacts de relais :

- C — contact commun,
- NO — contact normalement ouvert.

Le mode d’utilisation dépend de l’appareil et du schéma de l’installation. Le contact peut être utilisé, par exemple, pour commander la bobine d’un contacteur, mais ses caractéristiques admissibles ne doivent pas être dépassées.

:::warning Travaux électriques

Les raccordements à la tension secteur doivent être effectués par une personne possédant les qualifications appropriées, conformément au schéma de l’appareil concerné.

:::

### Une sortie à relais peut-elle alimenter directement un gros ventilateur ?

Il ne s’agit généralement pas d’une utilisation appropriée d’une petite sortie de commande.

Pour les charges plus importantes, on utilise un contacteur, un relais de puissance ou un module de commande de puissance dédié.

### À quoi servent les bornes A1 et A2 du contacteur ?

Il s’agit des bornes de la bobine du contacteur.

Lorsque la tension appropriée est appliquée à la bobine, le contacteur change l’état de ses contacts de puissance.

La tension de la bobine doit être conforme à la conception de l’installation et à la documentation du contacteur.

### Peut-on installer des appareillages supplémentaires à l’intérieur du boîtier du contrôleur ?

Uniquement si la conception du boîtier concerné le permet et si cela ne dégrade pas :

- l’indice de protection,
- l’isolation,
- le refroidissement,
- la sécurité,
- l’accès pour la maintenance.

Toute nouvelle ouverture doit être réalisée de manière à préserver l’étanchéité requise.

### Des interrupteurs supplémentaires pour les ventilateurs sont-ils utiles ?

Ils peuvent faciliter la maintenance et permettre de déconnecter indépendamment chaque ventilateur.

La réalisation doit toutefois tenir compte des protections électriques et ne doit pas provoquer d’états dangereux du contrôleur.

### Peut-on acheminer les câbles de commande avec les câbles de puissance ?

Il convient d’éviter d’acheminer les câbles de signal sensibles parallèlement et très près des câbles de forte puissance, en particulier sur de longues distances.

Les exigences dépendent du type de signal et de l’environnement électromagnétique.

### Quel câble utiliser pour les connexions réseau et les appareils PoE ?

Dans les installations évoquées, un câble à paires torsadées de catégorie 5e était indiqué comme minimum.

Si le câble traverse un environnement présentant un niveau élevé de perturbations ou un risque de charges électrostatiques, l’utilisation d’un câble correctement blindé et d’un système de mise à la terre approprié peut être justifiée.

### Un câble croisé est-il nécessaire pour le PoE ?

Dans les installations courantes, on utilise une liaison droite standard.

Il convient toutefois de toujours vérifier les exigences de l’appareil réseau et de l’alimentation PoE utilisée.


## Exploitation et entretien

### Comment réduire le risque de panne des contrôleurs dans les bâtiments agricoles ?

Le plus important est de limiter l’influence :

- de l’humidité,
- de l’ammoniac et de l’environnement agressif,
- de la poussière,
- du lavage direct à l’eau,
- des surtensions,
- d’une alimentation incorrecte.

Il est également utile de contrôler périodiquement l’état des câbles, des connexions et des boîtiers.

### Les appareils électroniques doivent-ils être nettoyés régulièrement ?

Oui, en particulier les appareils équipés de dissipateurs thermiques, de ventilateurs et d’ouvertures de ventilation.

La poussière accumulée réduit l’efficacité du refroidissement.

Le nettoyage doit être effectué après déconnexion de l’alimentation et conformément à la notice de l’appareil.

### Vaut-il la peine de procéder à une inspection du contrôleur après plusieurs années de fonctionnement ?

Oui, en particulier dans des conditions environnementales difficiles.

L’inspection peut comprendre :

- l’évaluation de l’état des connecteurs,
- le contrôle des traces d’humidité et de corrosion,
- la vérification des éléments de refroidissement,
- la vérification du panneau et des boutons,
- le test des capteurs,
- le contrôle des accumulateurs des systèmes d’alarme.

### Que faut-il noter après une panne ?

Les éléments les plus utiles sont :

- le message complet,
- le code d’erreur,
- l’heure de l’événement,
- la température,
- l’état de la ventilation,
- une information sur une coupure d’alimentation,
- une information sur le fonctionnement du groupe électrogène,
- une photo de l’écran ou de l’appareil.

Il ne faut pas réinitialiser l’appareil avant d’avoir noté le code si la situation permet de le faire en toute sécurité.

### Vaut-il la peine de disposer d’une alarme indépendante du contrôleur de ventilation ?

Oui, en particulier lorsque la panne de ventilation peut rapidement entraîner des conditions dangereuses.

Une centrale indépendante dotée de son propre accumulateur et de notifications à distance apporte un niveau de protection supplémentaire.

### Quelles informations préparer avant de contacter l’assistance technique ?

Il est préférable de préparer :

1. le modèle exact de l’appareil,
2. une description de l’installation,
3. le nombre et les caractéristiques des appareils raccordés,
4. les réglages actuels liés au problème,
5. le symptôme précis,
6. le code d’erreur ou d’alarme complet,
7. des photos de l’appareil et des plaques signalétiques,
8. une information sur les dernières modifications de l’installation.

Cela permet de réduire considérablement le temps nécessaire au diagnostic.


## Remarque importante concernant les appareils plus anciens

Les noms, les désignations des bornes et les fonctions disponibles peuvent varier entre les versions d’appareils fabriquées au cours d’années différentes.

Si l’appareil a plusieurs années ou plus d’une dizaine d’années, il convient de confirmer les éléments suivants avant d’appliquer la notice d’un modèle plus récent :

- la désignation exacte de l’appareil,
- la version de la carte,
- le type d’afficheur,
- la version du logiciel,
- le schéma des bornes.

:::warning Versions plus anciennes des appareils

Ne supposez pas une compatibilité totale sur la seule base d’un aspect similaire du boîtier. Avant d’utiliser un schéma ou une notice, confirmez le modèle exact et la version de l’appareil.

:::


## Contact avec l’assistance technique

Si la FAQ ne résout pas le problème, préparez les éléments suivants avant de prendre contact :

- une photo du contrôleur,
- une photo de la plaque signalétique du récepteur,
- les caractéristiques des moteurs ou des actionneurs,
- le schéma de raccordement,
- une description précise du mode de fonctionnement souhaité.

Ainsi, le choix de l’appareil ou le diagnostic du problème peut être effectué sur la base des caractéristiques réelles de l’installation, et non de suppositions.
