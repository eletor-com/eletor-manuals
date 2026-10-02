---
sidebar_position: 2
title: Handleiding SC-S
description: Klimaatregelaar voor stalruimten met een toegestane uitgangsstroom tot
  5A
keywords:
- eletor sc-s
- ventilatieregelaar
- klimaatregelaar
- ventilatieregelaar voor varkensstallen
- microklimaatregelaar
- regelaar voor varkensstallen
- ventilatie van varkensstallen
- regelaar voor opfokruimten
---


# Regelaar SC-S

Microprocessorgestuurde klimaatregelaar uit de SPEED CONTROL-familie. Een betrouwbare regelaar die eenvoudig te installeren en te bedienen is, met software in het Pools, Engels, Russisch en Duits. Het programma van de regelaar maakt het mogelijk om de parameters intuïtief in te stellen: temperaturen, periodieke ventilatie, bijverwarming, min./max. ventilatieniveaus en alarmen.

**Parameters en kenmerken:**  
- Ventilatie van groep I:
  - max. stroom van de uitgang voor traploze regeling 6A,
  - thermische beveiliging van het systeem,
  - zachte aanloop van de ventilatie,
  - kalibratie van het minimale toerental
- Ventilatie van groep II, potentiaalvrij contact tot 3A (1 als optie)
- Bijverwarming, potentiaalvrij contact tot 3A (1 als optie)
- Alarmuitgangen NO en NC:
  - signalering van spanningsuitval,
  - signalering van overschrijding van de min. of max. temperatuurdrempel
- 1 analoge ingang voor temperatuurmeting
- 2 uitgangen 0-10V
- Opgenomen vermogen van het systeem < 3W
- Hermetische behuizing IP56
- Voedingsspanning 230VAC 50Hz

## Installatie van de regelaar  
:::danger 
Tijdens de installatie van het apparaat moet de stroomtoevoer absoluut worden uitgeschakeld, aangezien de spanning op sommige componenten gevaarlijk is voor leven en gezondheid.  
Het wordt aanbevolen de installatie door een gekwalificeerd persoon te laten uitvoeren.
:::

### Keuze van de montageplaats  

De montageplaats moet zorgvuldig worden gekozen, zodat het apparaat gemakkelijk toegankelijk is voor bevoegde personen, maar niet toegankelijk is voor dieren en kinderen. Er moet ook rekening worden gehouden met de klimatologische omstandigheden, dat wil zeggen dat het apparaat moet werken binnen een temperatuurbereik van -10°C tot 40°C, op een plaats zonder direct zonlicht. Rondom het apparaat moet de lucht vrij kunnen circuleren. Het apparaat omvat een temperatuursensor. Voor de montage van de temperatuursensor gelden enkele regels:  
- de sensor mag niet worden gemonteerd op een plaats zonder luchtcirculatie of met direct zonlicht
- de sensor mag niet op een dragende (buiten)muur van het gebouw worden gemonteerd,
- vermijd de nabijheid van warmteafgevende apparaten, zoals radiatoren en lampen,
- plaats de sensor niet direct bij deuren en ventilatieopeningen,
- plaats de sensor niet op voor dieren toegankelijke plaatsen,
- het wordt aanbevolen de aansluitkabel van de sensor op afstand van voedingskabels te leggen.

### Montage  

Het apparaat kan onder zware klimatologische omstandigheden werken. Een correct gemonteerde regelaar en temperatuursensor zijn bestand tegen omgevingsinvloeden.
Tijdens de montage moet op het volgende worden gelet:  
- controleer de afdichting van het deksel vóór het vastschroeven,
- het deksel moet met alle schroeven worden vastgezet,
- de voor de aansluiting van de regelaar gebruikte kabels moeten rond zijn,
- draai na het aansluiten van de kabel de kabelwartels vast, zodat de kabel wordt afgedicht en vastgezet; het gebruik van silicone wordt aanbevolen,
- ongebruikte doorvoeren (kabelwartels) moeten worden afgedicht,
- bevestig de regelaar (het onderste deel van de behuizing) aan een vlakke wand met 4 pluggen.

## Elektrische aansluiting  

:::danger 
Controleer vóór het aansluiten van het systeem of de voeding is uitgeschakeld!
:::

Schroef het deksel los en verwijder het voordat u de regelaar aansluit. Voer de kabels door de rubberen kabelwartels; daarna kunnen ze worden aangesloten. De aansluitklemmen van de regelaar zijn weergegeven in de onderstaande afbeelding.

![Aansluiting](./img/Sc-s2.png)

**De AC-aansluiting 230V** wordt aangesloten op de voeding (verdeelkast). Het gebruik van een installatieautomaat 1P-B6 en overspanningsbeveiligingen van het type T1 T2 is vereist. Bij het aansluiten van meerdere apparaten is het een goede werkwijze om de regelaars over verschillende „fasen” (L1, L2, L3) te verdelen, om de voedingsleiding gelijkmatig te belasten.  
**De FAN-aansluiting** moet rechtstreeks op de ventilator worden aangesloten; bij het aansturen van meerdere ventilatoren mag de totale belasting niet hoger zijn dan 6A en moet elke ventilator afzonderlijk worden beveiligd. PE en N mogen niet vanuit de voeding (verdeelkast) worden aangevoerd; ze moeten beslist op de aansluitingen van de regelaar worden aangesloten.  
**De FUNCTION-aansluiting** is een potentiaalvrije relaisuitgang; de maximale contactstroom bedraagt 6A (bij rechtstreekse aansturing van een belasting is een externe installatieautomaat 1P-B6 vereist),
deze kan worden gebruikt als:  
- **Bijverwarming** – het contact sluit wanneer de gemeten temperatuur onder de ingestelde waarde daalt.  
- **Ventilatie van groep 2 of sproeisystemen** – het contact sluit wanneer de gemeten temperatuur hoger is dan de som van de ingestelde temperatuur en de ventilatieband.  het contact sluit wanneer de gemeten temperatuur hoger is dan de som van de ingestelde temperatuur en de ventilatieband.  

De onderstaande afbeelding toont de aansluiting van de ventilator van groep 2 of van het verwarmingstoestel.  

![Tweede groep](./img/2grupa.png)

**De ALARM-aansluiting** omvat potentiaalvrije uitgangen NC, C en NO voor aansluiting op de alarmcentrale. Het alarm wordt in de volgende gevallen geactiveerd:  
- de temperatuur is te laag of te hoog,
- de regelaar of temperatuursensor is defect,
- de voedingsspanning van de regelaar is uitgevallen;
- de regelaar werkt niet correct (bijv. oververhitting van de regelaar)  

![Alarm](./img/alarmsc-s.png)  

**De aansluiting V1 0-10V** dient voor het aansluiten van vermogensuitbreidingsmodules of ventilatoren met een ingebouwde toerentalregeling. De spanning op deze klem is evenredig met het ventilatieniveau.  
**De aansluiting V2 0-10V** dient voor het aansluiten van de actuator die de luchtinlaatkleppen opent.  
**De SENSOR-aansluiting** wordt aangesloten op de 1 temperatuursensor TS3 of TS5; de polariteit is niet van belang.  Het is een goede werkwijze om meetkabels op afstand van voedingskabels te houden.  
**De aansluiting RS-485** kan worden gebruikt voor het opbouwen van ventilatiesystemen en voor communicatie met een pc.  

## Werkingsprincipe  

De belangrijkste taak van de regelaar is om de temperatuur in de veehouderijruimte op het door de veehouder ingestelde niveau te houden. Houd er rekening mee dat de regelaar slechts een hulpmiddel is om optimale klimatologische omstandigheden in de veehouderijruimte te waarborgen. De veehouder speelt echter de belangrijkste rol in dit proces en moet de instellingen van het apparaat aanpassen aan de veranderende klimatologische omstandigheden buiten, en vooral aan de behoeften van de dieren in het stalgebouw, en de werking van het apparaat bewaken via de alarmcentrale.  

### Eerste ingebruikname van de regelaar  

:::danger
Bij de eerste ingebruikname van de regelaar moet beslist de verboden bedrijfsband van de motor worden ingesteld.
:::

De regelaar werkt samen met ventilatoren met een eenfasige asynchrone motor met een maximale totale stroomopname van 5A. Na het aansluiten van de gekozen ventilatoren moet de gebruiker deze afstemmen op de samenwerking met de regelaar. Met andere woorden: het minimale bedrijfsniveau (toerental) van de ventilator moet worden ingesteld. Deze functie heet **„Verboden band”** en wordt door de gebruiker eenmalig ingesteld via **„Geavanceerde instellingen”**. Om deze handeling correct uit te voeren, wordt de hulp van een tweede persoon aanbevolen, die het gedrag van de ventilator voortdurend kan observeren terwijl de andere persoon de waarde van de **„Verboden band”** instelt. Als de verboden band niet wordt ingesteld, kan het apparaat onjuist werken. De waarde van de **„Verboden band”** kan als correct worden beschouwd wanneer de door de ventilator opgewekte druk de kleppen van de ventilatiekoker net begint op te tillen. De instelling van de **„Verboden band”** moet opnieuw worden uitgevoerd wanneer de op de regelaar aangesloten ventilator wordt vervangen.  

### Periodieke ventilatie  

Periodieke ventilatie is een functie van de regelaar die wordt geactiveerd wanneer de temperatuur in de ruimte onder de ingestelde temperatuur daalt. Deze functie voorziet de dieren cyclisch van verse lucht. Periodieke ventilatie wordt bepaald door 3 parameters:
- **„Bedrijfstijd”** - bepaalt hoeveel seconden de ventilator wordt ingeschakeld,
- **„Pauzetijd”** - bepaalt de stilstandtijd van de ventilator in seconden,
- **„Periodiek ventilatieniveau”** - bepaalt het ventilatievermogen tijdens de „Bedrijfstijd”.  

De voorbeeldinstelling **60s/120s** betekent dat de ventilator gedurende 60s wordt ingeschakeld met een pauze van 120s tussen opeenvolgende inschakelingen. 

Alle hierboven genoemde parameters worden door de gebruiker ingesteld. Bij het instellen van de parameters voor periodieke ventilatie moet rekening worden gehouden met enkele regels:
- periodieke ventilatie wordt uitsluitend ingeschakeld wanneer de temperatuur in de varkensstal onder de ingestelde temperatuur daalt,
- de basisfunctie van periodieke ventilatie is om de dieren cyclisch van verse lucht te voorzien, niet om de ingestelde temperatuur in de ruimte te handhaven,
- het wordt aanbevolen de ruimten kort, maar vaak te ventileren,
- vermijd lange perioden van periodieke ventilatie, omdat dit tot te grote temperatuurschommelingen kan leiden,
- de ingestelde parameters moeten beslist worden aangepast aan het gedrag van de dieren en de omstandigheden zowel binnen als buiten de ruimte,
- de functie voor periodieke ventilatie kan worden uitgeschakeld; in dat geval moeten zowel in de procentuele als in de tijdgestuurde modus nulwaarden worden ingesteld op de plaats die overeenkomt met de ventilatieduur, bijv.: 0/120s  

### Traploze ventilatie  

De regelaar regelt de ventilatie traploos van „Minimaal toerental” tot **„Maximaal toerental”** binnen het bereik van de **„Ingestelde temperatuur”** tot de som van de **„Ingestelde temperatuur”** en de **„Ventilatieband”**. Boven dit bereik wordt ventilatiegroep 2 ingeschakeld.  

![ventilatie](./img/wentylacjia.png)  

Boven dit bereik wordt ventilatiegroep 2 ingeschakeld, Wanneer de temperatuur in de ruimte onder de **„Ingestelde temperatuur”** daalt, ventileert de regelaar de ruimte periodiek; bij een verdere daling wordt de bijverwarming ingeschakeld. Dit is volledig afhankelijk van de door de gebruiker ingevoerde instellingen. Het programma van de regelaar voorziet ook in samenwerking met een alarmcentrale, die kan worden geactiveerd wanneer de temperatuur in de varkensstal afwijkt van de ingestelde parameters.  

## Programmering van de regelaar  

De regelaar beschikt over een reeks standaardinstellingen die in twee gevallen in het niet-vluchtige geheugen worden opgeslagen:  
1. Eerste ingebruikname van het apparaat,  
2. Fout in het gegevensgeheugen.  
Bij het ontbreken of uitvallen van de voeding gaan de eerder ingevoerde en opgeslagen gebruikersinstellingen niet verloren.  

### Gebruik van het menu  

De regelaar beschikt over een reeks functies waarmee hij aan de betreffende toepassing kan worden aangepast. Deze functies zijn gegroepeerd in een menu dat toegankelijk is door op een van de toetsen **(„ Pijl rechts”, „Pijl links”)** te drukken. Parameters worden gewijzigd met de toetsen **„+” en „-”**; de bewerkte parameter wordt automatisch in het niet-vluchtige geheugen opgeslagen na **30s** sinds de laatste toetsdruk.  

### Functies van het basismenu  

| MENU                       | Beschrijving | 
|:---:                       |:---|
|Temperatuur  <br />20,8°C W16% A  |**„Informatiemodus”** - normale werking. Het display toont de actuele temperatuur en, wanneer de ventilator draait, het ventilatieniveau. Betekenis van de aanvullende symbolen: A-betekent dat het alarm is geactiveerd, D  - betekent dat de verwarming is ingeschakeld, W - betekent aanvullende ventilatie| 
|Ingestelde temp.  <br />20,0°C        |**„Ingestelde temperatuur”** – temperatuurwaarde die het begin van het traploze ventilatieproces bepaalt.   | 
|Periodieke ventilatie  <br />20s / 200s  |**„Periodieke ventilatie”** – er worden twee tijdwaarden ingesteld: 1 „Bedrijfstijd”, 2 „Pauzetijd” tussen opeenvolgende cyclische inschakelingen van de ventilatie.| 
|Periodiek vent.niveau  <br />20%        |**„Periodiek ventilatieniveau”** - ventilatieniveau tijdens de bedrijfstijd van de periodieke ventilatie   | 
|Minimumalarm  <br />12,0°C       |**„Minimumalarm”** - bepaalt de absolute minimumtemperatuur waarbij het alarm wordt geactiveerd. 
|Maximumalarm  <br />28,0°C       |**"Maximumalarm"** - bepaalt de absolute maximumtemperatuur waarbij het alarm wordt geactiveerd.  | 
|Bijverwarming  <br />12,0°C         |Afhankelijk van de configuratie worden de volgende functies uitgevoerd: **„Bijverwarming”** - het contact sluit wanneer de temperatuur onder de aangegeven waarde daalt. | 
|Ventilatie 2 trap  <br />25,0  |**„Ventilatie 2 trap”** - het contact sluit wanneer de gemeten temperatuur de som van de ingestelde temperatuur en de ventilatieband overschrijdt. | 
|Ventilatieband  <br />5,0°C     |**„Ventilatieband”** - bepaalt de reactiesnelheid van de regelaar (wijziging van het ventilatieniveau van minimum 1 tot maximum 1) bij een stijgende temperatuur. | 
|Minimaal toerental  <br />1%        |**„Minimaal toerental”** – dit is een toestand waarin het apparaat voor onbepaalde tijd blijft en een spanning met de ingestelde waarde op de uitgang levert. Dient voor de kalibratie van het apparaat met de motor en het kleppenmechanisme.   | 
|Maximaal toerental  <br />100%      |**„Maximaal toerental”** – dit is een toestand waarin het apparaat voor onbepaalde tijd blijft en een spanning met de ingestelde waarde op de uitgang levert. Dient om het voor ventilatie gebruikte vermogen te beperken| 

### Geavanceerd menu  

Het geavanceerde menu is voornamelijk bedoeld voor installateurs en maakt het mogelijk de regelaar aan de installatie en de ventilator aan te passen. U gaat naar de geavanceerde instellingen door de twee menutoetsen ongeveer 10s ingedrukt te houden.  

| MENU                                 | Beschrijving| 
|:---:                                 |:--- |
|Geen instellingen  <br />geavanceerd   |Deze melding geeft aan dat de regelaar niet op de ventilatie is gekalibreerd en mogelijk niet correct werkt. Het geavanceerde menu moet worden geopend om de „Verboden band” in te stellen.|
|Instellingen <br />Geavanceerd         |Signalering dat de geavanceerde instellingen zijn geopend. | 
|Softwareversie:  <br />1907       |Informatie over de softwareversie.| 
|Verboden band  <br />1000 us       |Kalibratie van het minimale toerental van de rechtstreeks op de regelaar aangesloten ventilatoren; deze parameter komt overeen met ventilatieniveau „1%”|  
|Contactfunctie  <br />Bijverwarming     |Keuze van de contactfunctie:  <br />• Bijverwarming (standaard)<br />• 2 ventilatiegroep | 
|Periodieke ventilatie  <br />Tijdgestuurd         |Keuze van het type periodieke ventilatie: <br />• Tijdgestuurd (standaard) <br />• Procentueel| 
|Bereik V1  <br />van 2,0 tot 10,0       |Instelling van het spanningsbereik op uitgang V1 0÷10V. De instellingen betreffen de minimale en maximale spanningswaarde. Deze instelling wordt gebruikt om de regelaar af te stemmen op de vermogensuitbreiding of de frequentieregelaar.| 
|Inversie V1  <br />Nee                |Activering keert de karakteristiek van uitgang V1 om. De spanning daalt bij een stijgend ventilatieniveau binnen het door min.-max. ingestelde bereik. Het signaal op uitgang V1 is van het type 10-0V.| 
|Uitschakeling V1  <br />Nee                |Bij activering wordt op uitgang  V1 0-10V niveau 0V geleverd in plaats van de ingestelde minimumwaarde, wanneer het ventilatieniveau 0% bedraagt.| 
|Bereik V2  <br />van 2,0 tot 10,0       |Instelling van het spanningsbereik op uitgang V2 0÷10V. De instellingen betreffen de minimale en maximale spanningswaarde. Deze instelling wordt gebruikt om het kleppensysteem te kalibreren.|
|Inversie V2  <br />Nee      	       |Activering keert de karakteristiek van uitgang V2 om. De spanning daalt bij een stijgend ventilatieniveau binnen het door min.-max. ingestelde bereik. Het signaal op uitgang V2 is van het type 10-0V.|
|Temp.kalibratie  <br />21,0°C -> 22,0°C|Kalibratie van de temperatuursensor maakt het mogelijk de afgelezen waarde opnieuw te schalen.|
|Zachte aanloop  <br />50%      	           |Bepaalt het ventilatieniveau bij elke start van de ventilator; de ventilator wordt tot de aangegeven waarde versneld en gaat vervolgens over naar het ingestelde niveau.| 
|Taal  <br />Pools    	           |Keuze van de menutaal: Pools, Engels, Duits, Russisch|
|Afsluiten                               |Afsluiten van het geavanceerde menu met de toets „+”; de ingevoerde wijzigingen worden opgeslagen in het niet-vluchtige geheugen.|

### Fout- en waarschuwingsmeldingen  

Foutmeldingen informeren de gebruiker over onregelmatigheden in de werking van de regelaar. Hieronder staan de mogelijke foutmeldingen.  

|FOUT                                    | BESCHRIJVING |
|:---:                                   |:--- |
|Alarm  <br />Overbelasting 	         |Overbelastingsalarm, geactiveerd bij 75°C. Het apparaat onderbreekt de werking totdat het is afgekoeld.|
|SENSOR ONDERBROKEN!  <br />Controleer sensor|Onderbroken sensor, signaleert een defect aan de sensor of de aansluitkabel.|
|SENSOR KORTGESLOTEN!  <br />Controleer sensor  |Kortgesloten sensor, signaleert een defect aan de sensor of de aansluitkabel.|
|Uitval  <br />Voeding                  |Spanningsuitval, te lage voedingsspanning, onjuiste frequentie of sterk vervormde voedingsspanning.| 

## Opmerkingen en waarschuwingen  

:::danger 
Tijdens de installatie van het apparaat moet de stroomtoevoer absoluut worden uitgeschakeld, aangezien de spanning op sommige componenten gevaarlijk is voor leven en gezondheid. Het wordt aanbevolen de installatie door een gekwalificeerd persoon te laten uitvoeren.
:::

- Om problemen bij het gebruik van het apparaat te voorkomen, moet de handleiding worden gelezen voordat met de installatie en het gebruik wordt begonnen.  
- Het is niet toegestaan de constructie te wijzigen of zelfstandig reparaties uit te voeren. Dit geldt met name voor wijzigingen aan onderdelen en componenten.  
- Onderhouds- en servicewerkzaamheden moeten worden uitgevoerd door bevoegd personeel (installateur of servicedienst van de fabrikant). In stalgebouwen met geforceerde ventilatie is een alarmsysteem vereist. De fabrikant van het apparaat is niet aansprakelijk voor schade veroorzaakt door onjuiste installatie, onjuiste programmering van functies, gevolgen van onvoorziene gebeurtenissen en externe factoren.  
- De parameters van de ventilatieregelaar moeten worden ingesteld in overeenstemming met de omstandigheden in de veehouderijruimte. Deze instellingen zijn individueel en afhankelijk van de beslissing van de veehouder. De fabrikant van het apparaat behoudt zich het recht voor wijzigingen aan te brengen in de constructie van het apparaat en de software.  


:::caution
![alternatieve tekst](./img/trash.svg) Na afloop van het gebruik mag het product niet samen met ongesorteerd huishoudelijk afval worden weggegooid, maar moet het worden verwerkt overeenkomstig de geldende voorschriften (WEEE-richtlijnen van de Europese Unie 2012/19/EU). <br />Het product is vervaardigd overeenkomstig de RoHS-vereisten (richtlijn van de Europese Unie 2011/65/EU).
:::

<!-- \newpage -->
## Technische gegevens van de regelaar  

|Parameter                        |	BESCHRIJVING      |
|:-----------                    |:---------- |
|Voedingsspanning|	230VAC 50Hz|
|Maximale stroom van de uitgang voor traploze regeling FAN|	6A|
|Regelbereik van de uitgangsspanning|	70V ÷ (Uz-5)V|
|Maximale stroom van de uitgang (het contact) ALARM|	3A|
|Maximale stroom van de uitgang (het contact) FUNCTION|	3A|
|Bedrijfstemperatuurbereik|	-20 +40oC|
|Temperatuurmeetbereik|	0 +50°C|
|Resolutie van de temperatuurmeting|	0,1°C|
|Detectie van defecten aan de temperatuursensor|	JA|
|Maximaal aantal analoge sensoren|	1|
|Nauwkeurigheid van de temperatuurmeting – analoge ingang|	1°C|
|Afhankelijkheid van de meting van de kabelweerstand – analoge ingang|	15,8Ω/°C|
|Bestendigheid tegen overspanning (max E)|	210J|
|Overbelastingsbeveiliging|	75°C|
|Afmetingen van het apparaat|	20x15x8 [cm]|
|Beschermingsgraad van de behuizing|	IP56|
  


:::info
De regelaar SPEED CONTROL SERVOMOTOR wordt geleverd met:
- 1 temperatuursensor + accessoires,
- 4 pluggen,
- 1 zekering 10A.
:::

