---
sidebar_position: 4
title: Handleiding Voeding DC50W24VB
description: Noodvoeding DC50W24VB  voor het luchtinlaatsysteem.
keywords:
- eletor IC-AC
- luchtinlaatregelaar
- klimaatregelaar
- ventilatieregelaar voor varkensstallen
- microklimaatregelaar
- regelaar voor varkensstallen
- ventilatie van varkensstallen
- regelaar voor opfokstallen
---


# Voeding DC50W24VB

Noodvoeding met een functie voor het automatisch en handmatig openen van luchtinlaten en luchtuitlaten. Wordt gebruikt om de veiligheid van landbouwhuisdieren te waarborgen bij stroomuitval of een storing van de regelaar. Wanneer het apparaat een afwijking detecteert, geeft het een alarm en opent het de hefmechanismen tot het ingestelde niveau.

## Parameters en kenmerken: 
-  Keuzeschakelaar voor de bedrijfsmodus: 
    - MANUAL
    - AUTO.
-  Draaiknop voor de openingsgraad van de luchtinlaten.
-  Ondersteunde standaarden:
    - 0-10, 2-10, 10-0, 10-2.
-  Mogelijkheid tot inversie van het stuursignaal.
-  Alarmuitgangen NO en NC.
-  Signalering van stroomuitval.
-  Bewaking van de stuurspanning 2-10V.
-  Kortsluitbewaking van de uitgangen 24VDC.
-  Kortsluitbewaking van de uitgangen 0-10V.
-  2 ingang 0-10V.
-  2 uitgangen 0-10V.
-  Elektronische beveiligingen van ingangen, uitgangen en de lijn 24V.
-  Accubatterij 24V 4.0 Ah.
-  Hermetisch gesloten behuizing IP65.
-  Voedingsspanning 85~264VAC 47~63Hz.

# Installatie van de regelaar  
:::danger 
Tijdens de installatie van het apparaat moet de elektrische voeding beslist worden uitgeschakeld, omdat de spanning op sommige onderdelen gevaarlijk is voor leven en gezondheid. Het wordt aanbevolen de installatie aan een gekwalificeerde persoon toe te vertrouwen.
:::

## Keuze van de montagelocatie  

De montagelocatie moet zorgvuldig worden gekozen, zodat het apparaat gemakkelijk toegankelijk is voor bevoegde personen, maar niet toegankelijk voor dieren en kinderen. Er moet ook rekening worden gehouden met de klimatologische omstandigheden, dat wil zeggen dat het apparaat moet werken binnen het temperatuurbereik van -10°C tot 40 °C, op een plaats zonder direct zonlicht. Rondom het apparaat moet de lucht vrij kunnen circuleren.

# Montage  

Het apparaat kan onder agressieve klimatologische omstandigheden werken. Een correct gemonteerd apparaat is bestand tegen schadelijke omgevingsinvloeden.

### Tijdens de montage moet op het volgende worden gelet: 
 - het deksel moet met alle schroeven worden vastgeschroefd,
 - de kabels die voor de aansluiting van het apparaat worden gebruikt, moeten een ronde doorsnede hebben,
 - na het aansluiten van de kabel moeten de kabelwartels worden aangedraaid, zodat de kabel wordt afgedicht en vastgezet; het gebruik van siliconen wordt aanbevolen,
 - ongebruikte doorvoeren (kabelwartels) moeten worden afgedicht,
 - het onderste deel van de behuizing wordt met 4 pluggen aan een vlakke wand bevestigd.


# Elektrische aansluiting  

:::danger 
Controleer vóór het aansluiten van het systeem of de voeding is uitgeschakeld!
:::

Na het losschroeven van het apparaat moet het voorpaneel worden verwijderd. Trek hiervoor de lintkabel uit de connector met de aanduiding P1. Voer de kabels door de rubberen kabelwartels en sluit ze vervolgens aan. De aansluiting moet volgens de beschrijving worden uitgevoerd.

![Aansluiting](./img/DC50W24VB.png)

**Voeding 230V AC:** wordt aangesloten op de voeding (verdeelkast). Het gebruik van een installatieautomaat (type „S” B6) en overspanningsbeveiligingen van klasse „C” is vereist. Het apparaat kan worden gevoed met spanningen binnen een breed bereik van 85V tot 264V en frequenties van 47 tot 63Hz, zonder invloed op de werking van het apparaat.  

**Connector In1 en In2** moet op de regelaar worden aangesloten om het stuursignaal aan de hefsystemen door te geven. Het apparaat kan twee regelaars ondersteunen of één regelaar met afzonderlijke secties voor luchtinlaten en luchtuitlaten (de klemmen I1 en I2 moeten worden overbrugd).  

**Connector ALARM** wordt aangesloten op de alarmcentrale, afhankelijk van het systeem – gesloten (NO en C), open (NC en C). Het alarm wordt in de volgende gevallen geactiveerd:  •de voedingsspanning van het apparaat is uitgevallen,  •het stuursignaal 2-10V is op ten minste één van de ingangen weggevallen,  •er is kortsluiting in het uitgangssignaal opgetreden of de waarde ervan wijkt af van de gemeten waarde,  •er is kortsluiting opgetreden op de voedingsrail +24V van de hefmechanismen.  

**Connector Ouput 1 en Ouput 2** worden aangesloten op de actuator (het hefmechanisme) op de voor het betreffende apparaat vereiste wijze; de aansluitbeschrijving moet in de handleiding van de betreffende actuator (het hefmechanisme) staan.  

**Bedrijfsmodusschakelaar S1** afhankelijk van de gebruikte actuator (het hefmechanisme) moet de juiste bedrijfsmodus worden gekozen. Standaard staan de schakelaars 1,2,3,4,5,6 in de stand off – werking 2-10V.
 
| Kanaal 1 | Kanaal 2| Functie |
|------|------|----------|
| 1 – off | 4 – off | Bedrijfsmodus binnen het signaalbereik 2-10V, een stuurspanning onder 1,5V genereert een alarm.   |
| 1 – on| 4 – on  | Bedrijfsmodus binnen het signaalbereik 0-10V, geen alarmreactie op een signaal onder 1,5V.   |
| 2 – off | 5 – off  | Proportionele bedrijfsmodus, uitgangssignalen binnen het bereik 0-10V of 2-10V.  |
| 2 – on | 5 – on  | Omgekeerde bedrijfsmodus, uitgangssignalen binnen het bereik 10-0V of 10-2V.   |
| 3 – off | 6 – off  | Ingangsinversie uitgeschakeld.  |
| 3 – on | 6 – on   | Ingangsinversie ingeschakeld.   |

# Werkingsprincipe  

Tijdens normaal bedrijf voedt de noodvoeding de actuatoren (hefmechanismen) 24V en laadt deze de accu's op of houdt deze de accu's opgeladen; de accu's leveren de voeding bij stroomuitval.  De schakelaar AUTO/MANUAL bepaalt de bedrijfsmodus van het apparaat.  

**Modus MANUAL** maakt rechtstreekse bediening van de actuatoren (hefmechanismen) mogelijk met de draaiknop op het paneel van het apparaat.  

**Modus AUTO** – de standaardbedrijfsmodus, geeft het stuursignaal van de ingang door naar de uitgang, waarbij het passend wordt verwerkt afhankelijk van de instellingen van de schakelaar „S1”, en bewaakt het niveau van het ingangssignaal.  Wanneer een afwijking op een bepaalde ingang wordt gedetecteerd, geeft het apparaat het signaal van de draaiknop op het voorpaneel aan zijn uitgang door.  Het alarmrelais schakelt in de volgende gevallen:  •een te laag ingangssignaal (Uin < 1,5V) – schakelaar „S1” 1-off, 4-off,  •kortsluiting van het uitgangssignaal naar massa of 24V,  •ontbreken van de voedingsspanning,  •kortsluiting van de spanning 24V.

## Gebruik 

De gebruiker kiest met de schakelaar de modus MANUAL en stelt met de draaiknop de gewenste openingsgraad van de luchtinlaten in – de actuatoren werken volgens de stand van de draaiknop. Na het instellen van de luchtinlaten wordt met de schakelaar de modus AUTO gekozen en wordt het apparaat in die stand gelaten – de luchtinlaten stellen zich in op het door de ventilatieregelaar vereiste niveau. In een noodsituatie stellen de luchtinlaten zich in volgens de stand van de draaiknop.  

## Voorpaneel 

| MENU                       | Beschrijving | 
|:---:                       |:---|
|![Aansluiting](./img/paneldcw50.png) |**Controlelampje POWER** – geeft de aanwezigheid van voeding en het opladen van de accu's aan.  1.**Controlelampje CHECK** – brandt continu in de automatische modus wanneer het signaal van de regelaar naar de uitgang wordt doorgegeven, en knippert wanneer het signaal van de draaiknop naar de uitgang wordt doorgegeven.  2.**OUT 1** – geeft afwijkingen in kanaal 1 aan.  3.**OUT 2** – geeft afwijkingen in kanaal 2 aan.  4.**AUTO** – automatische bedrijfsmodus.  5.**MANUAL** – handmatige bedrijfsmodus.  6.**Draaiknop 0%-100%** - keuze van de openingsgraad van de luchtinlaten.| 

# Foutmeldingen en waarschuwingen

Foutmeldingen dienen om de gebruiker te informeren over afwijkingen in de werking van het apparaat. Hieronder staan de mogelijke foutmeldingen:
 -  Controlelampje POWER – brandt niet groen – geen netvoeding.
 -  Controlelampje CHECK – knippert geel – het signaal van de potentiometer wordt aan de uitgangen doorgegeven.
 -  Controlelampje OUT 1 – brandt rood - detectie van een afwijking (ontbreken van het stuursignaal, kortsluiting op de uitgang of kortsluiting op de rail 24VDC) in het eerste kanaal.
 -  Controlelampje OUT 2 – brandt rood - detectie van een afwijking (ontbreken van het stuursignaal, kortsluiting op de uitgang of kortsluiting op de rail 24VDC) in het tweede kanaal.

# Opmerkingen en waarschuwingen  

:::danger 
Tijdens de installatie van het apparaat moet de elektrische voeding beslist worden uitgeschakeld, omdat de spanning op sommige onderdelen gevaarlijk is voor leven en gezondheid. Het wordt aanbevolen de installatie aan een gekwalificeerde persoon toe te vertrouwen.
:::

 - Om problemen bij het gebruik van het apparaat te voorkomen, moet de handleiding vóór installatie en gebruik worden gelezen. Het is niet toegestaan de constructie te wijzigen of zelfstandig reparaties uit te voeren. Dit geldt in het bijzonder voor het wijzigen van elementen en onderdelen.
 - Onderhouds- of servicewerkzaamheden moeten door bevoegd personeel worden uitgevoerd (installateur of servicedienst van de fabrikant). In veestallen met mechanische ventilatie is een alarmsysteem vereist. 
 - De fabrikant van het apparaat is niet aansprakelijk voor schade veroorzaakt door onjuiste installatie, onjuiste programmering van functies, de gevolgen van onvoorziene gebeurtenissen en externe factoren. De parameters van het apparaat moeten worden ingesteld overeenkomstig de omstandigheden in de veestal.Deze instellingen zijn individueel en afhankelijk van de beslissing van de veehouder. 
 - De fabrikant van het apparaat behoudt zich het recht voor om wijzigingen aan te brengen in de constructie van het apparaat en in de software.
Het apparaat bevat een accubatterij; overmatige ontlading van de accu's moet worden voorkomen, omdat dit de batterij kan beschadigen. 
Kortsluiting van de batterijpolen kan brand veroorzaken.  


:::caution
![alternatieve tekst](./img/trash.svg) Na het einde van de gebruiksduur mag het product niet samen met ongesorteerd huishoudelijk afval worden weggegooid, maar moet het worden afgevoerd overeenkomstig de geldende voorschriften (WEEE-richtlijnen van de Europese Unie 2012/19/EU).  Het product is vervaardigd overeenkomstig de RoHS-eisen (richtlijn van de Europese Unie 2011/65/EU).
:::

<!-- \newpage -->
# Technische gegevens van de regelaar  

|Parameter                        |	BESCHRIJVING      |
|:-----------                    |:---------- |
|Wisselspanningsvoeding|	85~264VAC 47~63Hz|
|Gelijkspanningsvoeding|	120~370VDC|
|Uitgangsspanning|	27,6VDC|
|Maximale uitgangsstroom|	1,8A|
|Rendement|	85%|
|Maximale stroom van de stuuruitgangen 0-10V|	30mA|
|Maximale stroom van de uitgang (het contact) ALARM|	3A|
|Overspanningsbeveiliging van ingangen en uitgangen|	JA|
|Kortsluitbeveiliging|	Automatisch |
|Accubatterij|	4Ah 24V|
|Bedrijfstemperatuurbereik|	-10 +40oC|
|Afmetingen van het apparaat|	20x15x8 cm|
|Beschermingsklasse van de behuizing|	IP65|

:::info
De regelaar IC-AC wordt geleverd met:
 - pluggen - 	4 st., 
 - accu's 12V 4Ah - 	2 st., 
 - kabelwartel PG13,5 -	1 st.,
 - kabelwartel PG11 -	3 st., 
 - kabelwartel PG9 -	3 st.
:::

