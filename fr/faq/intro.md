---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Les questions les plus fréquentes concernant le choix, la configuration,
  le diagnostic et le service des appareils ELETOR.
keywords:
- ELETOR
- FAQ
- contrôleurs de ventilation
- régulateurs
- ventilateurs
- actionneurs
- alarmes
- variateurs de fréquence
- service
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Questions fréquemment posées

Cette FAQ a été élaborée à partir d’une analyse anonymisée de conversations réelles avec des utilisateurs et des clients de ELETOR. Les réponses ont été généralisées afin d’aider dans les cas typiques et ne contiennent pas de données concernant des personnes ou des installations spécifiques.

:::note Portée de la FAQ

Les réponses concernent des cas typiques. Les repères de bornes, les fonctions et le mode de raccordement peuvent différer selon les modèles et les versions des appareils. En cas de doute, utilisez la documentation appropriée au produit concerné.

:::

:::warning Sécurité

Effectuez les travaux sur l’installation électrique conformément à la documentation de l’appareil et aux règles de sécurité en vigueur. Les travaux sous tension secteur doivent être effectués par une personne disposant des qualifications appropriées.

:::

## Choix du contrôleur et de la puissance

### Comment choisir un contrôleur pour des ventilateurs ?

La base du choix est avant tout le courant total des ventilateurs, et non uniquement leur nombre.

:::tip Réunissez les données avant le choix

Plus les données sur les moteurs et le mode de fonctionnement de l’installation sont précises, plus le choix du contrôleur est fiable.

:::

Avant le choix, il est utile de préparer :

- le nombre de ventilateurs,
- la tension d’alimentation,
- la puissance ou le courant nominal de chaque ventilateur,
- l’information indiquant si tous les ventilateurs doivent fonctionner en variation continue,
- l’information indiquant si les ventilateurs peuvent être répartis en groupes,
- des informations sur les appareils supplémentaires, par ex. les aérothermes ou les entrées d’air.

Le contrôleur ne doit pas être choisi exactement « à la limite ». Il convient de conserver une marge appropriée par rapport à la charge maximale.

### Est-il suffisant d’additionner la puissance des ventilateurs en watts ?

Pour une estimation préliminaire, il est possible d’utiliser la puissance, mais le choix final doit être fondé sur le courant nominal des appareils ainsi que sur la nature de la charge.

Au démarrage, un moteur peut consommer plus de courant qu’en fonctionnement normal. C’est pourquoi deux ensembles de ventilateurs de puissance nominale similaire ne constituent pas toujours une charge équivalente pour le contrôleur.

### J’ai plusieurs petits ventilateurs. Puis-je les raccorder en parallèle sur une seule sortie ?

Oui, si :

- ils sont prévus pour ce mode de commande,
- ils doivent fonctionner ensemble,
- la somme des charges ne dépasse pas le courant admissible de la sortie,
- le mode de raccordement est conforme à la documentation du contrôleur.

Pour un plus grand nombre de ventilateurs, il convient d’envisager une répartition en groupes ou l’utilisation d’une extension de puissance.

### Quand une extension de puissance est-elle nécessaire ?

Une extension de puissance est utilisée lorsque la charge dépasse les capacités de la sortie du contrôleur ou lorsque l’installation doit être étendue à un plus grand nombre de ventilateurs.

Le contrôleur transmet alors le signal de commande, tandis que la charge proprement dite est prise en charge par un module supplémentaire.

### L’installation peut-elle être ultérieurement étendue avec des ventilateurs supplémentaires ?

Dans de nombreuses installations, oui. On utilise le plus souvent :

- une extension de puissance supplémentaire,
- un groupe de ventilation supplémentaire,
- un contacteur enclenchant le groupe suivant,
- un variateur de fréquence dans le cas de moteurs triphasés.

Il est préférable de prévoir l’extension envisagée dès le premier choix du contrôleur.

### Tous les ventilateurs doivent-ils fonctionner en variation continue ?

Non. Deux solutions sont typiques :

1. tous les ventilateurs fonctionnent en variation continue,
2. le premier groupe fonctionne en variation continue, et les groupes suivants sont ajoutés progressivement, par ex. au moyen de contacteurs.

La seconde solution permet de gérer une installation plus importante sans régulation continue de chaque ventilateur.

### J’ai 10 ventilateurs. Ai-je besoin d’un très grand contrôleur ?

Pas toujours. Plusieurs modes de commande peuvent être appliqués :

- répartition en groupes,
- extensions de puissance,
- contacteurs,
- variateur de fréquence.

Le choix final dépend des paramètres électriques des ventilateurs ainsi que du fait qu’ils doivent tous varier simultanément ou non.

### Les contrôleurs 6 A et 12 A diffèrent-ils uniquement par la charge admissible ?

Il ne faut pas supposer que la seule différence réside dans la valeur du courant. Les différentes versions et générations d’appareils peuvent différer par leur équipement ou leur mode de réalisation.

Lors du remplacement d’un appareil, il faut vérifier le modèle exact et la documentation actuelle.


## Ventilateurs et commande de la ventilation

### Le contrôleur régule-t-il les ventilateurs en continu ?

Dans les contrôleurs destinés à la régulation continue de la ventilation, la vitesse des ventilateurs est modifiée en fonction de la demande résultant notamment de la température.

Il faut toutefois vérifier si le type de moteur concerné convient au mode de régulation utilisé.

### Que signifie la température de consigne ?

La température de consigne est la valeur à laquelle le contrôleur compare la mesure actuelle de la température.

Sur cette base, le contrôleur augmente ou réduit l’intensité de la ventilation conformément aux autres réglages, par ex. la bande de régulation, le niveau minimal et le niveau maximal.

### Que signifie le niveau minimal de ventilation ?

Il s’agit de la valeur minimale de commande du ventilateur en fonctionnement automatique.

Ce réglage évite un fonctionnement en dessous du niveau auquel le ventilateur pourrait fonctionner de manière instable ou assurer un renouvellement d’air insuffisant.

### Que signifie le niveau maximal de ventilation ?

Il s’agit de la limite supérieure de la valeur de commande de la ventilation.

Par exemple, le réglage d’une valeur inférieure à 100% peut limiter la vitesse maximale du ventilateur, si l’installation l’exige.

### Que signifie la bande de ventilation ?

La bande de ventilation définit la plage de température dans laquelle le contrôleur passe du niveau minimal au niveau maximal de ventilation.

Plus la bande est étroite, plus la commande réagit rapidement à une variation de température par une augmentation du débit.

### Après la mise en marche, le ventilateur passe d’abord à 100%, puis ne ralentit qu’ensuite. Pourquoi ?

La fonction de démarrage peut être active, son rôle étant de lancer momentanément le moteur à une puissance plus élevée.

Selon la version du contrôleur, il convient de vérifier les réglages liés à :

- la fonction Soft Start,
- la durée d’accélération,
- la durée de fonctionnement à 100%,
- la durée de décélération.

Si la fonction n’est pas nécessaire dans l’installation concernée, les paramètres appropriés peuvent être modifiés conformément à la notice de l’appareil.

### Pourquoi le ventilateur peut-il être momentanément lancé à pleine puissance au démarrage ?

Un tel démarrage peut faciliter le démarrage fiable du ventilateur ainsi que dans les installations où les éléments mécaniques peuvent opposer une résistance plus importante au démarrage.

Cela n’est toutefois pas nécessaire dans toutes les installations.

### Que signifient la durée d’accélération et la durée de décélération ?

**La durée d’accélération** définit la manière dont la commande augmente lors du démarrage du ventilateur.

**La durée de décélération** définit la manière dont la vitesse diminue.

Ces deux paramètres permettent de limiter les changements brusques de vitesse de rotation et du fonctionnement de l’installation.

### Pourquoi deux contrôleurs identiques peuvent-ils démarrer les ventilateurs différemment ?

La cause la plus fréquente est la différence de réglages.

Il convient de comparer en particulier :

- la température de consigne,
- la bande de ventilation,
- le minimum et le maximum,
- les réglages Soft Start,
- les durées d’accélération et de décélération,
- la configuration des groupes de ventilation.

### Le contrôleur peut-il déclencher périodiquement la ventilation indépendamment de la température ?

Selon le modèle, une fonction d’aération périodique est disponible.

Elle peut déclencher la ventilation pendant une durée déterminée à des intervalles définis, même lorsque la régulation de température ne demande pas une augmentation de la ventilation.

### À quoi servent les groupes de ventilation ?

Les groupes permettent d’augmenter progressivement la capacité de l’installation.

Par exemple :

- le groupe 1 fonctionne en variation continue,
- le groupe 2 démarre les ventilateurs supplémentaires,
- le groupe suivant se déclenche lorsque la demande est encore plus élevée.

Cela permet de commander un grand nombre de ventilateurs sans régulation continue de chacun d’eux.

### Un groupe supplémentaire de ventilateurs peut-il être enclenché par contacteur ?

Oui. La sortie relais du contrôleur peut commander la bobine d’un contacteur correctement dimensionné.

La charge des ventilateurs ne doit alors pas être acheminée directement par un petit contact de commande.

### Que signifie le symbole du ventilateur ou le voyant jaune sur le contrôleur ?

Selon le modèle, les voyants indiquent l’état actuel des sorties et des fonctions.

La signalisation jaune peut indiquer une fonction de service active, par ex. le fonctionnement de la ventilation, du chauffage ou d’un groupe supplémentaire.

La signification exacte doit être vérifiée dans la notice du modèle concerné.

### Que signifie le symbole du mode manuel ?

Le mode manuel signifie que la valeur de commande a été imposée par l’utilisateur et n’est pas calculée automatiquement à ce moment-là sur la base de la température.

Après la fin des essais, il faut s’assurer que le contrôleur a été rétabli dans le mode automatique approprié.


## Entrées d’air et actionneurs

### Le contrôleur peut-il commander les entrées d’air ?

Oui, certains contrôleurs permettent de fonctionner avec des entraînements d’entrées d’air.

Le mode de raccordement dépend du type d’actionneur et de son mode de commande.

### Quels types d’actionneurs peuvent être utilisés pour les entrées d’air ?

Dans les échanges techniques, deux solutions étaient les plus fréquentes :

- un actionneur commandé par signal analogique 0–10 V ou 2–10 V,
- un actionneur réversible ouvrir/fermer avec signal de retour, par ex. à partir d’un potentiomètre.

Avant l’achat, il faut vérifier la compatibilité du modèle concerné avec le contrôleur utilisé.

### La tension d’alimentation de l’actionneur 24 V ou 230 V a-t-elle une importance pour le signal 0–10 V ?

Le signal de commande et l’alimentation de l’actionneur sont des paramètres distincts.

L’actionneur peut être alimenté par une tension différente de la tension du signal de commande. Les deux paramètres doivent être conformes à la documentation de l’actionneur et du contrôleur.

### Que signifie la commande 0–10 V ?

Le contrôleur envoie un signal analogique en tension représentant la position ou le niveau de commande demandé.

Dans une application typique, une valeur plus faible signifie une ouverture plus faible, et une valeur plus élevée une ouverture plus grande, mais la caractéristique réelle doit être vérifiée dans la documentation de l’actionneur.

### Quelle est la différence entre 0–10 V et 2–10 V ?

Dans les deux cas, la position est définie par un signal analogique.

Dans le standard 2–10 V, la partie basse de la plage est décalée et peut permettre à l’appareil de distinguer le signal de commande de son absence.

Le contrôleur et l’actionneur doivent prendre en charge une plage compatible.

### Comment choisir un actionneur en fonction du nombre d’entrées d’air ?

Il ne faut pas choisir un actionneur uniquement sur la base du nombre de volets.

Il faut tenir compte de :

- la force ou le couple requis,
- la longueur et le mode de guidage du mécanisme,
- les résistances des volets,
- la longueur de course,
- la vitesse de fonctionnement,
- la tension d’alimentation,
- le type de commande,
- le retour d’information requis.

### Un seul actionneur peut-il commander plusieurs volets ?

Oui, si la mécanique de l’installation permet de relier les volets par un système commun et si le couple ou la force requis ne dépassent pas les capacités de l’actionneur.

En pratique, le choix est déterminé par les résistances de l’ensemble du mécanisme, et non par le seul nombre de volets.

### Plusieurs actionneurs peuvent-ils être raccordés en parallèle et commandés par un seul signal ?

Dans certains systèmes, cela est possible, mais il faut vérifier la documentation des actionneurs ainsi que la charge admissible de la sortie de commande.

Dans le cas d’entraînements réversibles sans retour indépendant, il peut également se produire un décalage progressif de la position des différents actionneurs.

### Pourquoi plusieurs actionneurs peuvent-ils avec le temps se positionner différemment ?

Même des moteurs identiques peuvent fonctionner à une vitesse légèrement différente en raison de :

- charges différentes,
- résistances mécaniques,
- tolérance des paramètres du moteur,
- différences de transmission.

C’est pourquoi, lorsqu’une synchronisation précise est requise, un retour approprié ou un contrôle individuel de la position est nécessaire.

### Les entrées d’air peuvent-elles être commandées proportionnellement à la ventilation ?

Oui. Dans des systèmes correctement configurés, la position des entrées d’air peut être liée au niveau actuel de ventilation.

Ainsi, à mesure que la capacité des ventilateurs augmente, l’ouverture des entrées d’air augmente également.

### L’actionneur 24 V nécessite-t-il une alimentation séparée ?

Si le contrôleur ne dispose pas d’une sortie d’alimentation appropriée de la puissance requise, une alimentation séparée est nécessaire.

Sa puissance doit être choisie en fonction de la consommation de courant de l’actionneur ainsi que des autres appareils alimentés par la même source.

### Peut-on utiliser un actionneur d’une autre marque ?

Souvent oui, si ses paramètres électriques et son mode de commande sont compatibles avec les sorties du contrôleur.

Avant le raccordement, il faut vérifier :

- la tension,
- le type de signal,
- le schéma des conducteurs,
- les sens de fonctionnement,
- le signal de position,
- la charge admissible.


## Capteurs de température et d’humidité

### Où raccorder le capteur de température ?

Le capteur doit être raccordé à l’entrée capteur prévue par le fabricant, à l’entrée capteur indiquée dans la documentation du modèle concerné.

Il ne faut pas supposer que les repères de bornes sont identiques dans toutes les versions des appareils.

### Le capteur de température indique une valeur différente de celle d’un thermomètre de référence. Que faire ?

Si le contrôleur dispose d’une fonction d’étalonnage du capteur, l’indication peut être corrigée après comparaison avec un thermomètre de référence fiable.

Avant de modifier l’étalonnage, il est utile de s’assurer que :

- les deux capteurs se trouvent au même endroit,
- la mesure s’est stabilisée,
- le capteur n’est pas chauffé par le soleil ou par des appareils,
- il ne se trouve pas directement dans un flux d’air froid ou chaud.

### Le capteur d’humidité indique une valeur incorrecte. Peut-on l’étalonner ?

Cela dépend de la version du contrôleur, du capteur et du logiciel.

Dans certaines solutions, la correction peut nécessiter une fonction logicielle appropriée ou un type de capteur compatible. Si l’écart est important et répétitif, il faut vérifier la version de l’appareil et contacter le support technique.

### Une mesure erronée signifie-t-elle toujours que le capteur est endommagé ?

Non.

La cause peut également être :

- un emplacement incorrect du capteur,
- le conducteur,
- le raccordement électrique,
- la configuration,
- un type de capteur inadapté,
- la nécessité d’un étalonnage,
- l’humidité ou la corrosion.


## Alarmes et notifications

### Peut-on raccorder directement une sirène à la sortie d’alarme du contrôleur ?

Il ne faut pas le supposer.

La sortie d’alarme du contrôleur est généralement une sortie de commande ou un contact relais. La sirène peut nécessiter une alimentation séparée ainsi qu’une centrale d’alarme.

### À quoi sert une centrale d’alarme ?

La centrale peut :

- recevoir les signaux d’alarme des contrôleurs,
- alimenter le dispositif de signalisation,
- maintenir le fonctionnement en cas de coupure d’alimentation,
- signaler l’alarme par un son ou une lumière,
- envoyer des notifications GSM dans les versions disposant de cette fonction.

### La centrale peut-elle signaler une coupure d’alimentation du contrôleur ?

Oui, si le système a été correctement raccordé.

La solution peut détecter non seulement un dépassement de température, mais aussi une perte de signal du contrôleur provoquée par l’absence de son alimentation.

### Où règle-t-on les températures minimale et maximale d’alarme ?

Dans une configuration typique, les seuils d’alarme sont réglés dans le contrôleur qui gère la chambre ou le local concerné.

La centrale d’alarme reçoit ensuite l’information indiquant que le contrôleur a signalé une alarme.

### Une centrale GSM nécessite-t-elle une carte SIM ?

Pour l’envoi d’appels et de messages via le réseau mobile, une carte SIM active ou une autre solution de communication prévue dans le modèle concerné est nécessaire.

Sans connexion active au réseau mobile, les fonctions téléphoniques et SMS ne fonctionneront pas.

### L’alarme peut-elle envoyer l’information indiquant de quel contrôleur provient l’événement ?

Dans un système correctement configuré, oui.

Les entrées de la centrale peuvent être attribuées à des locaux ou à des contrôleurs spécifiques, ce qui permet au message d’identifier la source de l’alarme.

### Combien de contrôleurs peut-on raccorder à une seule centrale d’alarme ?

Cela dépend du modèle de la centrale.

Dans les transcriptions, il y avait des centrales prenant en charge jusqu’à huit entrées, mais avant de réaliser l’installation, il faut vérifier la spécification actuelle de l’appareil concerné.

### Quel accumulateur est utilisé dans la centrale d’alarme ?

Dans une partie des appareils évoqués dans les échanges, un accumulateur 12 V 7 Ah était utilisé.

Avant d’acheter un remplacement, il faut vérifier le marquage sur l’accumulateur existant ainsi que la spécification de la centrale, car d’autres versions d’appareils peuvent nécessiter un autre accumulateur.

### La centrale envoie des messages de basse tension. Que faut-il vérifier ?

En premier lieu, il faut vérifier :

- l’état de l’accumulateur,
- son âge,
- les raccordements de l’accumulateur,
- la présence de l’alimentation secteur,
- le fonctionnement du chargeur ou de l’alimentation de la centrale.

Un accumulateur usé peut provoquer des messages cycliques de basse tension.

### À quelle fréquence faut-il remplacer l’accumulateur dans une centrale d’alarme ?

Il n’existe pas de valeur unique adaptée à toutes les conditions.

L’accumulateur doit être testé périodiquement, en particulier dans les installations où l’alarme en cas de coupure d’alimentation a une importance critique. Avec l’âge, sa capacité réelle diminue.

### La sirène seule suffit-elle comme protection ?

La sirène n’agit que si quelqu’un peut l’entendre.

Dans les sites laissés temporairement sans surveillance, il est utile d’utiliser également une notification à distance ainsi qu’une alimentation secourue par accumulateur.


## Variateurs de fréquence

### Comment choisir un variateur de fréquence pour des ventilateurs ?

Il faut connaître :

- la tension d’alimentation,
- le nombre de phases,
- la puissance et le courant de tous les moteurs,
- leur mode de raccordement,
- les conditions de fonctionnement,
- le mode de commande requis.

Le variateur de fréquence doit disposer d’une marge appropriée par rapport à la charge, en particulier lorsque plusieurs moteurs fonctionnent en parallèle.

### Le variateur de fréquence doit-il avoir exactement la même puissance que la somme des puissances des moteurs ?

Il ne faut pas choisir le variateur de fréquence uniquement sur la base d’une simple addition des puissances ni sélectionner un appareil fonctionnant exactement à la limite de ses paramètres.

Il faut tenir compte des courants nominaux, de la nature de la charge et des recommandations du fabricant du variateur de fréquence.

### Le variateur de fréquence a arrêté les ventilateurs et a affiché une erreur. Que faire ?

Le plus important est de noter le code d’erreur complet avant la réinitialisation.

:::tip Prenez une photo de l’écran

Si la situation le permet, prenez une photo de l’afficheur avant la réinitialisation. Le code d’erreur complet facilite considérablement le diagnostic.

:::

Le début du message seul ne suffit souvent pas à déterminer la cause. Le code complet permet notamment de distinguer :

- une surcharge,
- un dépassement de courant,
- une surchauffe,
- une tension incorrecte,
- d’autres erreurs de l’entraînement.

### Peut-on simplement réinitialiser l’erreur du variateur de fréquence ?

La réinitialisation peut rétablir le fonctionnement, mais elle n’élimine pas la cause de l’alarme.

Après l’événement, il faut vérifier le code d’erreur et déterminer la cause avant de redémarrer l’installation pour un fonctionnement prolongé.

### Le variateur de fréquence fonctionne dans un local poussiéreux. Faut-il le nettoyer ?

Oui.

La poussière et les dépôts sur le radiateur ou le ventilateur de refroidissement peuvent dégrader l’évacuation de la chaleur et entraîner une surchauffe du variateur de fréquence.

Le nettoyage doit être effectué conformément aux instructions du fabricant, après une mise hors tension en toute sécurité.

### Qu’est-ce qui peut provoquer la surchauffe d’un variateur de fréquence ?

Les causes les plus fréquentes sont :

- des éléments de refroidissement encrassés,
- une circulation d’air obstruée,
- une température ambiante trop élevée,
- une surcharge,
- une défaillance du ventilateur de refroidissement,
- un montage incorrect.

### Une tension secteur élevée peut-elle déclencher une alarme du variateur de fréquence ?

Oui. Les variateurs de fréquence surveillent la tension du circuit d’alimentation et peuvent signaler une erreur en cas de dépassement du niveau admissible.

Si le problème se répète, il faut contrôler l’installation et la qualité de l’alimentation.


## Pannes et diagnostic

### Le contrôleur fonctionne, mais l’afficheur n’affiche rien. Quelle peut être la cause ?

Les causes possibles comprennent notamment :

- une défaillance de l’afficheur,
- un problème de réglage du contraste dans les solutions plus anciennes,
- une défaillance du raccordement,
- de la corrosion,
- une défaillance de la carte principale.

Si l’appareil n’a pas été utilisé pendant une longue période ou a fonctionné dans un environnement humide, il est également utile de vérifier l’état de la carte.

### Après plusieurs années sans utilisation, le contrôleur a un problème d’afficheur. Pourquoi ?

Un arrêt prolongé dans un environnement humide ou agressif peut entraîner :

- l’oxydation des connecteurs,
- de la corrosion,
- une dégradation des contacts,
- des dommages aux composants électroniques.

Dans ce cas, il est utile d’effectuer une inspection complète plutôt que de remplacer des éléments sans diagnostic préalable.

### Le contrôleur est noirci après une surtension. Cela signifie-t-il que la carte doit être remplacée ?

Pas toujours.

Un élément de protection peut être endommagé et laisser beaucoup de dépôts, alors même que le reste de la carte peut être réparable.

Toutefois, si le stratifié est carbonisé, brûlé ou si les pistes sont endommagées, la réparation peut être non rentable ou peu durable.

### Qu’est-ce qui peut endommager plusieurs contrôleurs en même temps ?

Si plusieurs appareils tombent en panne au même moment, il faut vérifier l’installation d’alimentation.

L’une des causes possibles est un problème de conducteur neutre qui, dans une installation triphasée, peut entraîner l’apparition de tensions incorrectes sur les récepteurs monophasés.

Des surtensions provenant du réseau ou d’un groupe électrogène sont également possibles.

### Que faire après une panne liée à une surtension ?

Avant de raccorder un contrôleur réparé ou neuf, il faut déterminer la cause du problème.

:::danger Ne reconnectez pas l’appareil sans avoir vérifié l’installation

Si la cause de la panne était une tension incorrecte, un conducteur neutre endommagé ou une surtension, le contrôleur réparé ou neuf peut être de nouveau endommagé.

:::

### Qu’est-ce qu’un élément de protection contre les surtensions sur la carte ?

Dans les appareils électroniques, on utilise des éléments limitant les surtensions, par ex. des varistances.

Leur rôle est d’absorber une partie de l’énergie de la surtension et de protéger les circuits situés en aval. Après un événement important, un tel élément peut subir une défaillance permanente.

### Peut-on mettre l’appareil en marche après avoir retiré l’élément de protection brûlé ?

Il ne faut pas considérer cela comme une réparation normale.

Après retrait de la protection, l’appareil peut perdre sa protection contre une nouvelle surtension. De telles actions ne peuvent être effectuées qu’en tant que procédure de service délibérée, par une personne disposant des qualifications appropriées et après élimination de la cause initiale de la panne.

### Le contrôleur a été inondé ou a fortement corrodé. Vaut-il la peine de le réparer ?

Cela dépend du degré des dommages.

La corrosion superficielle et les dommages isolés peuvent souvent être éliminés. Si la corrosion a touché les pistes, les connecteurs et de nombreux composants, la réparation peut être longue, incertaine et économiquement injustifiée.

### Le lavage sous pression de l’appareil peut-il endommager le contrôleur ?

Oui.

L’électronique ne doit pas être exposée directement à l’eau ni au produit de nettoyage si le boîtier et le mode de montage ne sont pas prévus à cet effet.

L’humidité pénétrant à l’intérieur peut provoquer de la corrosion et des pannes ultérieures difficiles à diagnostiquer.

### Pourquoi les défauts après inondation peuvent-ils réapparaître après réparation ?

La corrosion peut également progresser dans des endroits non visibles lors de la première inspection.

Les vias, pistes et raccordements endommagés peuvent fonctionner pendant l’essai, puis perdre à nouveau le contact par la suite.

C’est pourquoi, sur une carte fortement corrodée, le service peut recommander un remplacement plutôt que de nouvelles réparations.

### L’appareil fonctionne par moments, puis plus du tout. Par quoi commencer ?

Avant de contacter le service, il est utile de rassembler :

- le modèle exact,
- la description du symptôme,
- le moment d’apparition,
- les valeurs affichées à l’écran,
- le code d’alarme ou d’erreur,
- des informations sur les dernières modifications de l’installation,
- une photo de l’intérieur et des bornes, si elle peut être prise en toute sécurité.

Plus la description est précise, plus le diagnostic est facile.


## Service et réparations

### Que faut-il envoyer au service si le contrôleur est endommagé ?

Il est préférable d’envoyer un ensemble complet permettant de reproduire le problème.

Le colis doit être accompagné d’une brève description :

- de ce qui ne fonctionne pas,
- du moment où le problème apparaît,
- du caractère permanent ou intermittent de la panne,
- de la survenue ou non, avant la panne, d’une surtension, d’une inondation ou d’un autre événement,
- des données nécessaires pour le contact et le retour de l’appareil.

:::note Données pour la demande de service

Transmettez les coordonnées de contact et d’expédition directement au service. Ne les publiez pas dans des demandes ouvertes ni dans des documents publics.

:::

### Faut-il envoyer le contrôleur complet ou seulement la carte ?

Cela dépend de la panne.

En cas de problèmes d’afficheur, de boutons, d’alimentation ou de comportement ambigu, il est préférable d’envoyer l’ensemble complet nécessaire pour reproduire le symptôme.

Dans le cas d’une réparation préalablement convenue d’un module spécifique, le service peut ne demander que la carte.

### Est-ce que ELETOR répare les contrôleurs au lieu de les remplacer immédiatement ?

Il ressort des transcriptions que les appareils sont d’abord diagnostiqués.

Si la réparation est possible et pertinente, les composants ou modules endommagés sont remplacés. En cas de dommage grave, le service peut proposer le remplacement de la carte ou de l’appareil complet.

### Que se passe-t-il si la carte endommagée ne peut pas être réparée ?

Il est possible de remplacer le module endommagé par un neuf, à condition que la pièce appropriée soit disponible et compatible avec l’appareil.

Pour les appareils plus anciens, le service doit d’abord confirmer la compatibilité des versions.

### Vaut-il la peine d’acheter immédiatement une nouvelle carte après une surtension ?

Pas toujours.

Si le dommage concerne un élément de protection ou une petite partie du circuit, une réparation peut être justifiée. Il est préférable d’effectuer d’abord un diagnostic.

### Le service peut-il également vérifier l’afficheur et les boutons ?

Oui, si ces éléments sont fournis avec l’appareil ou le module.

Cela est particulièrement utile lorsqu’on ne sait pas si le problème se situe sur la carte principale ou sur le panneau utilisateur.

### Faut-il toujours essayer de sauver un contrôleur fortement corrodé ?

Non.

Si le coût du diagnostic et de la réparation augmente alors que la fiabilité après réparation reste incertaine, un remplacement peut être plus raisonnable.

Cela concerne en particulier les appareils dont dépend la ventilation du site.

### Comment accélérer le diagnostic de service ?

Joignez une description précise du symptôme au lieu de la simple indication « ne fonctionne pas ».

Sont également utiles :

- des photos,
- le code d’erreur,
- une description de l’installation,
- le type des récepteurs raccordés,
- une information sur une surtension ou une coupure d’alimentation,
- une information sur une inondation ou le lavage de l’appareil.


## Installation et câblage

### Comment raccorder des appareils aux bornes relais C et NO ?

C et NO sont des désignations typiques d’un contact de relais :

- C — contact commun,
- NO — contact normalement ouvert.

Le mode d’utilisation dépend de l’appareil et du schéma de l’installation. Le contact peut être utilisé, par ex., pour commander la bobine d’un contacteur, mais ses paramètres admissibles ne doivent pas être dépassés.

:::warning Travaux électriques

Les raccordements à la tension secteur doivent être effectués par une personne disposant des qualifications appropriées, conformément au schéma de l’appareil concerné.

:::

### La sortie relais peut-elle alimenter directement un grand ventilateur ?

En règle générale, ce n’est pas une utilisation appropriée d’une petite sortie de commande.

Pour des charges plus importantes, on utilise un contacteur, un relais de puissance ou un module de sortie dédié.

### À quoi servent les bornes A1 et A2 d’un contacteur ?

Ce sont les bornes de la bobine du contacteur.

Lorsque la tension appropriée est appliquée à la bobine, le contacteur change l’état de ses contacts de puissance.

La tension de la bobine doit être conforme au projet de l’installation et à la documentation du contacteur.

### Peut-on monter des appareils supplémentaires à l’intérieur du boîtier du contrôleur ?

Uniquement si la conception du boîtier concerné le permet et si cela ne dégrade pas :

- le degré de protection,
- l’isolation,
- le refroidissement,
- la sécurité,
- l’accès pour le service.

Toute nouvelle ouverture doit être réalisée de manière à préserver l’étanchéité requise.

### Des interrupteurs supplémentaires pour les ventilateurs sont-ils utiles ?

Ils peuvent faciliter le service et permettre la coupure indépendante de certains ventilateurs.

Le mode de réalisation doit toutefois tenir compte des protections électriques et ne doit pas provoquer d’états dangereux du contrôleur.

### Les conducteurs de commande peuvent-ils être posés avec les conducteurs de puissance ?

Il faut éviter de poser des conducteurs de signal sensibles en parallèle et très près de conducteurs de forte puissance, surtout sur de longues distances.

Les exigences dépendent du type de signal et de l’environnement électromagnétique.

### Quel câble utiliser pour les liaisons réseau et les appareils PoE ?

Dans les installations évoquées, on indiquait comme minimum une paire torsadée de catégorie 5e.

Si le câble passe dans un environnement à niveau élevé de perturbations ou à risque de charges électrostatiques, l’utilisation d’un câble correctement blindé et d’un système de mise à la terre approprié peut être justifiée.

### Un câble croisé est-il nécessaire pour le PoE ?

Dans les installations typiques, on utilise une liaison droite standard.

Il faut toutefois toujours vérifier les exigences de l’appareil réseau et de l’alimentation PoE utilisée.


## Exploitation et maintenance

### Comment limiter le risque de panne des contrôleurs dans les bâtiments d’élevage ?

Le plus important est de limiter l’influence de :

- l’humidité,
- l’ammoniac et de l’environnement agressif,
- la poussière,
- le lavage direct à l’eau,
- les surtensions,
- une alimentation incorrecte.

Il est également utile de contrôler périodiquement l’état des conducteurs, des raccordements et des boîtiers.

### Les appareils électroniques doivent-ils être nettoyés régulièrement ?

Oui, en particulier les appareils équipés de radiateurs, de ventilateurs et d’ouvertures de ventilation.

La poussière accumulée dégrade le refroidissement.

Le nettoyage doit être effectué après coupure de l’alimentation et conformément à la notice de l’appareil.

### Après quelques années de fonctionnement, vaut-il la peine d’effectuer une inspection du contrôleur ?

Oui, en particulier dans des conditions environnementales difficiles.

L’inspection peut inclure :

- l’évaluation de l’état des connecteurs,
- le contrôle des traces d’humidité et de corrosion,
- la vérification des éléments de refroidissement,
- la vérification du panneau et des boutons,
- le test des capteurs,
- le contrôle des accumulateurs dans les systèmes d’alarme.

### Que vaut-il la peine de noter après la survenue d’une panne ?

Les éléments les plus utiles sont :

- le message complet,
- le code d’erreur,
- l’heure de l’événement,
- la température,
- l’état de la ventilation,
- l’information relative à une coupure d’alimentation,
- l’information sur le fonctionnement du groupe électrogène,
- une photo de l’écran ou de l’appareil.

Il ne faut pas réinitialiser l’appareil avant d’avoir noté le code, si la situation permet de le faire en toute sécurité.

### Vaut-il la peine d’avoir une alarme indépendante du contrôleur de ventilation ?

Oui, en particulier là où une défaillance de la ventilation peut rapidement conduire à des conditions dangereuses.

Une centrale indépendante avec son propre accumulateur et une notification à distance offre une couche de protection supplémentaire.

### Quelles informations préparer avant de contacter le support technique ?

Il est préférable de préparer :

1. le modèle exact de l’appareil,
2. une description de l’installation,
3. le nombre et les paramètres des appareils raccordés,
4. les réglages actuels liés au problème,
5. le symptôme exact,
6. le code complet d’erreur ou d’alarme,
7. des photos de l’appareil et des plaques signalétiques,
8. une information sur les dernières modifications de l’installation.

Cela permet de raccourcir considérablement le diagnostic.


## Remarque importante concernant les appareils plus anciens

Les noms, les repères de bornes et les fonctions disponibles peuvent différer selon les versions des appareils fabriquées au cours d’années différentes.

Si l’appareil a plusieurs années ou une dizaine d’années, avant d’utiliser la notice d’un modèle plus récent, il faut confirmer :

- la désignation exacte de l’appareil,
- la version de la carte,
- le type d’afficheur,
- la version du logiciel,
- le schéma des bornes.

:::warning Anciennes versions des appareils

Ne supposez pas une compatibilité totale uniquement sur la base d’un aspect similaire du boîtier. Avant d’utiliser un schéma ou une notice, confirmez le modèle exact et la version de l’appareil.

:::


## Contact avec le support technique

Si la FAQ ne résout pas le problème, préparez avant le contact :

- une photo du contrôleur,
- une photo de la plaque signalétique du récepteur,
- les paramètres des moteurs ou des actionneurs,
- le schéma de raccordement,
- une description précise du mode de fonctionnement attendu.

Cela permet de choisir l’appareil ou de diagnostiquer le problème sur la base des paramètres réels de l’installation, et non d’hypothèses.
