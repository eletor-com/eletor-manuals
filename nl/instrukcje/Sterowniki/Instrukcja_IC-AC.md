---
sidebar_position: 4
title: Handleiding IC-AC
description: Regelaar IC-AC voor luchtinlaten in stallen met een toegestane uitgangsstroom
  tot 2A
keywords:
- eletor IC-AC
- regelaar voor luchtinlaten
- klimaatregelaar
- ventilatieregelaar voor varkensstallen
- microklimaatregelaar
- regelaar voor varkensstallen
- ventilatie van varkensstallen
- regelaar voor opfokstallen
---


# Regelaar IC-AC

  Regelaar voor actuatoren en hefsystemen van luchtinlaten met AC-motoren met rechts-/linksloop en een potentiometer voor het uitlezen van de actuele positie. De regelaar zet het signaal 0-10V om in de openingsgraad van de luchtinlaten en maakt tevens handmatige bediening mogelijk.

## Parameters en kenmerken:  
- Bedrijfsmodi:
  - MANUAL – handmatige bediening met de toetsen „+”, „-”;
  - AUTO – automatische werking binnen het gekalibreerde bereik, evenredig met het signaal 0-10V;
  - NOODMODUS – bij uitval van het stuursignaal openen de luchtinlaten tot het in procenten ingestelde niveau; 
- Relaisuitgang (rechts-/linksloop) 2A;
- Stuursignaal: 0-10V;
- Mogelijkheid tot inversie van het stuursignaal;
- Positiemeting met een potentiometer 1-100kΩ;
- Programmeerbare hysterese en middelingstijd van de meetwaarden; 
- Hermetische behuizing IP56;
- Voedingsspanning 230VAC 50Hz;
- Menutalen: 
  - Pools
  - Engels
  - Oekraïens
  - Russisch

# Installatie van de regelaar  
:::danger 
Tijdens de installatie van het apparaat moet de elektrische voeding beslist worden uitgeschakeld, omdat de spanning op sommige onderdelen gevaarlijk is voor leven en gezondheid. Het wordt aanbevolen de installatie door een gekwalificeerd persoon te laten uitvoeren.
:::

## Keuze van de montageplaats  

  De montageplaats moet zorgvuldig worden gekozen, zodat bevoegde personen gemakkelijk toegang tot het apparaat hebben en het onbereikbaar is voor dieren en kinderen. Ook moet rekening worden gehouden met de klimaatomstandigheden: het apparaat moet werken binnen het temperatuurbereik van -10°C tot 40 °C, op een plaats zonder direct zonlicht.

# Montage

Het apparaat kan onder agressieve klimaatomstandigheden werken. Een correct gemonteerd apparaat is bestand tegen schadelijke omgevingsinvloeden. 

  Tijdens de montage moet op het volgende worden gelet: 
- het deksel moet met alle schroeven worden vastgedraaid,
- de kabels die voor de aansluiting van het apparaat worden gebruikt, moeten een ronde doorsnede hebben,
- na het aansluiten van de kabel moeten de kabelwartels worden vastgedraaid, zodat de kabel wordt afgedicht en vastgezet; het gebruik van siliconen wordt aanbevolen,
- ongebruikte doorvoeren (kabelwartels) moeten worden afgedicht,
- het onderste deel van de behuizing wordt met 4 pluggen aan een vlakke wand bevestigd.


# Elektrische aansluiting  

:::danger 
Controleer vóór het aansluiten van het systeem of de voeding is uitgeschakeld!
:::

  Na het losschroeven van het apparaat moet het voorpaneel worden verwijderd. Trek hiervoor de lintkabel uit de connector met de aanduiding P1. Voer de kabels door de rubberen kabelwartels; vervolgens kunnen ze worden aangesloten. De aansluiting moet overeenkomstig de beschrijving worden uitgevoerd. De aansluitklemmen van de regelaar zijn in de onderstaande afbeelding weergegeven.

![Aansluiting](./img/ic-acpołącz.png)

## Sluit de 230V AC-voeding vanuit de verdeelkast aan op de klemmen:  
 - **Aansluiting L** faseklem. Het gebruik van een installatieautomaat (type „S” B3) en overspanningsbeveiligingen is vereist.  
 - **Aansluiting N** nulklem.  
 - **Aansluiting PE** aardklem.

## Uitgang naar de actuator: 
 - **Aansluiting L** wordt met een draad verbonden met aansluiting C om de relais van spanning te voorzien.  
 - **Aansluiting N** nulklem van de actuator.  
 - **Aansluiting PE** aardklem van de actuator – behuizing.  
 - **Aansluiting NO** klem van de actuator voor het openen van de luchtinlaten.  
 - **Aansluiting NC** klem van de actuator voor het sluiten van de luchtinlaten.
 - **Aansluiting van de potentiometer** – moet worden aangesloten overeenkomstig de aanduidingen op het schema van de actuator. De polariteit van de voeding van de potentiometer moet zodanig worden gekozen dat de positie-eenheden toenemen bij het openen van de luchtinlaten en afnemen bij het sluiten. Als dit niet het geval is, moeten de voedingsdraden van de potentiometer worden verwisseld.  
 - **Aansluiting In** – moet op de regelaar worden aangesloten om het stuursignaal naar de hefsystemen te voeren.  


# Werkingsprincipe  

  In de automatische modus zet de regelaar het stuursignaal in het bereik 0-10V om in de overeenkomstige  positie van de actuator van de luchtinlaten. De actuator moet worden gekalibreerd in de posities voor maximale opening en sluiting van de luchtinlaten. Tijdens de kalibratie moet erop worden gelet dat de kabels  naar de luchtinlaten voortdurend onder spanning blijven. Tijdens de kalibratie moet de toets „+” de luchtinlaten openen en de toets „-” de luchtinlaten sluiten. Als dit niet het geval is, moeten de draden op de klemmen NO en NC worden verwisseld.
  De door de potentiometer uitgelezen posities voor opening en sluiting moeten meer dan 100 eenheden van elkaar verschillen. De door de potentiometer uitgelezen positie-eenheden moeten toenemen bij het openen van de luchtinlaten en afnemen bij het sluiten. Als dit niet het geval is, moeten de voedingsdraden van de potentiometer worden verwisseld.
  Na een correcte kalibratie is de regelaar gereed voor automatische werking en zal deze de positie van de actuator regelen. Een stuursignaal met een niveau onder 1,5V leidt ertoe dat de luchtinlaten in de noodpositie worden gezet. 

## Gebruik 

  De regelaar voor luchtinlaten kan in een van twee modi werken: handmatig of automatisch. De gekozen bedrijfsmodus wordt opgeslagen en blijft behouden bij uitval van de voeding – na het inschakelen van de voeding keert de regelaar terug naar de modus waarin deze het laatst werkte. De momenteel gekozen bedrijfsmodus wordt op het display aangegeven:  
   - **MANUAL** - door "+" of "-" lang ingedrukt te houden, wordt de handmatige modus ingeschakeld. In deze modus worden de luchtinlaten handmatig bediend met de toetsen: „+” - openen, „-” - sluiten.           
   - **AUTO**   - door "Esc" lang ingedrukt te houden, wordt de automatische modus ingeschakeld. In deze modus werken de luchtinlaten automatisch, aangestuurd door het signaal 0-10V van aansluiting In.

## Functies van het basismenu  

| MENU                       | Beschrijving | 
|:---:                       |:---|
|MANUAL  STOP    POT 539  |  **„Informatiemodus”** – bij handmatige werking. Weergegeven informatie:  - **STOP** – actuator stilgezet;  - **OPEN** – openen van de luchtinlaten na het indrukken van de toets „+”;  - **CLOSE** – sluiten van de luchtinlaten na het indrukken van de toets „-”;  - **POT 539** – parameter voor de actuele positie van de actuator, bepaald door de potentiometer.  •Omschakeling naar de automatische bedrijfsmodus door de toets „Esc” ingedrukt te houden| 
|AUTO  20 % = In 3,70 POT 511       |  **„Informatiemodus”**  bij automatische werking. Weergegeven informatie:    **20 %**  Ingestelde waarde van de openingspositie van de luchtinlaten    **"="**   luchtinlaten in de ingestelde positie    **"–"**    sluiten van de luchtinlaten tot de opgegeven positie    **"+"**    openen van de luchtinlaten tot de opgegeven positie    **In 3,70**  meting van de stuurspanning op de klemmen In     **POT 511**  parameter voor de actuele positie van de actuator, bepaald door de potentiometer.  Omschakeling naar de handmatige bedrijfsmodus door de toets „+” of „-” ingedrukt te houden | 
|Kleppen noodpositie 30 %  |**„Kleppen noodpositie”** – instelling van de openingswaarde van de kleppen (luchtinlaten) bij uitval van het stuursignaal. De luchtinlaten openen tot het ingestelde niveau bij een storing van de regelaar of de signaalkabel.| 
|Kalibratie openen 671 -> 311        |**„Kalibratie van de opening”** – de opening van de luchtinlaten wordt gekalibreerd door de maximale opening (eindpositie) van de luchtinlaten in te stellen met de toetsen „+” en „-”. De eerste weergegeven waarde is de laatst opgeslagen instelling, de tweede waarde is de actuele positie van de actuator. De toets „Ok” slaat de ingevoerde instellingen op in het geheugen; „Esc” verlaat de kalibratiemodus zonder op te slaan.   | 
|Kalibratie sluiten 281 -> 311      |**„Kalibratie van de sluiting”** – de sluiting van de luchtinlaten wordt gekalibreerd door de minimale positie van de luchtinlaten in te stellen met de toetsen „+” en „-”. De eerste weergegeven waarde is de laatst opgeslagen instelling, de tweede waarde is de actuele positie van de actuator. De toets „Ok” slaat de ingevoerde instellingen op in het geheugen; „Esc” verlaat de kalibratiemodus zonder op te slaan.|  
|Middelingstijd 5 s       |**„Middelingstijd”** – tijd waarover het stuursignaal van aansluiting In wordt gemiddeld; beschermt tegen oscillaties op de stuuringang.  | 
|Inversie   Nee |**„Inversie”** – het inschakelen van deze functie past de regelaar aan het stuursignaal 10-0V aan  | 
|Taal   Pools |**„Taal”** – keuze van de menutaal  | 
|Hysterese Pot  5   | **„Hysterese van de potentiometer”** – een verandering van de positieparameter van de actuator die kleiner is dan de ingestelde waarde wordt bij het positioneren niet in aanmerking genomen. Deze parameter dient om zeer kleine bewegingen van de actuator en storingen van de potentiometer te elimineren. | 
 

# Opmerkingen en waarschuwingen  

:::danger 
Tijdens de installatie van het apparaat moet de elektrische voeding beslist worden uitgeschakeld, omdat de spanning op sommige onderdelen gevaarlijk is voor leven en gezondheid. Het wordt aanbevolen de installatie door een gekwalificeerd persoon te laten uitvoeren.
:::

- Om problemen bij het gebruik van het apparaat te voorkomen, moet de handleiding vóór de installatie en het gebruik worden gelezen. De constructie mag niet worden gewijzigd en reparaties mogen niet zelfstandig worden uitgevoerd. Dit geldt in het bijzonder voor wijzigingen aan elementen en onderdelen.
- Onderhouds- en servicewerkzaamheden moeten door bevoegd personeel worden uitgevoerd (installateur of servicedienst van de fabrikant). In stallen met mechanische ventilatie is een alarmsysteem vereist. 
- De fabrikant van het apparaat is niet aansprakelijk voor schade veroorzaakt door onjuiste installatie, onjuiste programmering van functies, de gevolgen van onvoorziene gebeurtenissen en externe factoren.
- De parameters van het apparaat moeten worden ingesteld overeenkomstig de omstandigheden in de stalruimte. Deze instellingen zijn individueel en afhankelijk van de beslissing van de veehouder. De fabrikant van het apparaat behoudt zich het recht voor om wijzigingen aan te brengen in de constructie van het apparaat en de software.  


:::caution
![alt](./img/trash.svg) Na afloop van de gebruiksduur mag het product niet samen met ongesorteerd huishoudelijk afval worden weggegooid, maar moet het worden afgevoerd overeenkomstig de geldende voorschriften (WEEE-richtlijnen van de Europese Unie 2012/19/EU).  Het product is vervaardigd overeenkomstig de RoHS-vereisten (richtlijn van de Europese Unie 2011/65/EU).
:::

<!-- \newpage -->
# Technische gegevens van de regelaar  

|Parameter                        |	BESCHRIJVING      |
|:-----------                    |:---------- |
|Voedingsspanning wisselstroom|	230VAC 50Hz|
|Maximale uitgangsstroom|	2A|
|Ontstoringsfilter op de uitgang|	RC|
|Ingangsimpedantie|	100kΩ|
|Overspanningsbeveiliging van ingangen en uitgangen|	JA|
|Voeding van de potentiometer|	10VDC|
|Maximale stroom van de potentiometeruitgangen|	30mA|
|Bedrijfstemperatuurbereik|	-10 +40oC|
|Afmetingen van het apparaat|	20x15x8 cm |
|Beschermingsgraad van de behuizing|	IP65|

:::info
De regelaar IC-AC wordt geleverd met:
- 4 pluggen,
- 2 kabelwartel PG11,
- 2 kabelwartel PG9.
:::

