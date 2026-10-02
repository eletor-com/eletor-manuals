---
sidebar_position: 2
title: Handleiding SC-S
description: Klimaatregelaar voor stallen met een toegestane uitgangsstroom tot 5A
keywords:
- eletor sc-s
- ventilatieregelaar
- klimaatregelaar
- ventilatieregelaar voor varkensstallen
- microklimaatregelaar
- regelaar voor varkensstallen
- ventilatie van varkensstallen
- regelaar voor opfokstallen
---


# Regelaar SC-S

Microprocessorgestuurde klimaatregelaar uit de familie SPEED CONTROL. Betrouwbare regelaar, eenvoudig te installeren en te bedienen, met software in het Pools, Engels, Russisch en Duits. Het regelprogramma maakt een intuïtieve instelling mogelijk van de parameters: temperaturen, periodieke ventilatie, bijverwarming, min./max. ventilatieniveaus en alarmen.

**Parameters en kenmerken:**  
- Ventilatie van groep I:
  - max. stroom van de traploos geregelde uitgang 6A,
  - thermische beveiliging van het systeem,
  - softstart van de ventilatie,
  - kalibratie van het minimumtoerental
- Ventilatie van groep II, potentiaalvrij contact tot 3A (1 optioneel)
- Bijverwarming, potentiaalvrij contact tot 3A (1 optioneel)
- Alarmuitgangen NO en NC:
  - signalering van voedingsuitval,
  - signalering van overschrijding van de min. of max. temperatuurgrens
- 1 analoge ingang voor temperatuurmeting
- 2 uitgangen 0-10V
- Opgenomen vermogen van het systeem < 3W
- Hermetische behuizing IP56
- Voedingsspanning 230VAC 50Hz

## Installatie van de regelaar  
:::danger 
Tijdens de installatie van het apparaat moet de stroomtoevoer absoluut worden onderbroken, omdat de spanning op sommige onderdelen gevaarlijk is voor leven en gezondheid.  
Het wordt aanbevolen de installatie door een gekwalificeerd persoon te laten uitvoeren.
:::

### Keuze van de montageplaats  

De montageplaats moet weloverwogen worden gekozen, waarbij het apparaat gemakkelijk toegankelijk moet zijn voor bevoegde personen en ontoegankelijk voor dieren en kinderen. Er moet ook rekening worden gehouden met de klimatologische omstandigheden, d.w.z. het apparaat moet werken binnen het temperatuurbereik van -10°C tot 40°C, op een plaats zonder direct zonlicht. Rondom het apparaat moet de lucht vrij kunnen stromen. Het apparaat omvat een temperatuursensor. Voor de montage van de temperatuursensor gelden enkele regels:  
- de sensor mag niet worden gemonteerd op een plaats zonder luchtcirculatie of in direct zonlicht
- de sensor mag niet op een dragende (buiten)muur van het gebouw worden gemonteerd,
- vermijd de nabijheid van warmteafgevende apparaten, zoals radiatoren en lampen,
- de sensor mag niet direct bij deuren en ventilatieopeningen worden geplaatst,
- de sensor mag niet op voor dieren toegankelijke plaatsen worden geplaatst,
- het wordt aanbevolen de aansluitkabel van de sensor uit de buurt van voedingskabels te leggen.

### Montage  

Het apparaat kan onder zware klimatologische omstandigheden werken. Een correct gemonteerde regelaar en temperatuursensor zijn bestand tegen omgevingsinvloeden.
Tijdens de montage moet op de volgende zaken worden gelet:  
- controleer de afdichting van het deksel voordat u het vastschroeft,
- het deksel moet met alle schroeven worden vastgezet,
- de kabels die voor het aansluiten van de regelaar worden gebruikt, moeten rond zijn,
- draai na het aansluiten van de kabel de kabelwartels aan, zodat de kabel wordt afgedicht en vastgezet; het gebruik van siliconen wordt aanbevolen,
- ongebruikte doorvoeren (kabelwartels) moeten worden afgedicht,
- bevestig de regelaar (het onderste deel van de behuizing) aan een vlakke wand met 4 pluggen.

## Elektrische aansluiting  

:::danger 
Controleer voordat u het systeem aansluit of de voeding is uitgeschakeld!
:::

Voordat u de regelaar aansluit, moet u het deksel losschroeven en verwijderen. Voer de kabels door de rubberen kabelwartels; daarna kunt u ze aansluiten. De aansluitklemmen van de regelaar zijn weergegeven in de onderstaande afbeelding.

![Aansluiting](./img/Sc-s2.png)

**Aansluiting AC 230V** wordt verbonden met de voeding (verdeelkast). Het gebruik van een installatieautomaat 1P-B6 en overspanningsbeveiligingen van het type T1 T2 is vereist. Bij het aansluiten van meerdere apparaten is het een goede praktijk om de regelaars over verschillende „fasen” (L1, L2, L3) te verdelen, om de voedingsleiding gelijkmatig te belasten.  
**Aansluiting FAN** moet rechtstreeks op de ventilator worden aangesloten; bij het aansturen van meerdere ventilatoren mag de totale belasting niet hoger zijn dan 6A, en elke ventilator moet afzonderlijk worden beveiligd. PE en N mogen niet vanuit de voeding (verdeelkast) worden afgetakt; ze moeten beslist op de aansluitingen van de regelaar worden aangesloten.  
**Aansluiting FUNCTION** is een potentiaalvrije relaisuitgang; de maximale contactstroom bedraagt 6A (een externe installatieautomaat 1P-B6 is vereist bij rechtstreekse aansturing van de belasting),
en kan worden gebruikt als:  
- **Bijverwarming** – het contact sluit wanneer de gemeten temperatuur onder de ingestelde waarde daalt.  
- **Ventilatie van groep 2 of sproeisystemen** – het contact sluit wanneer de gemeten temperatuur hoger is dan de som van de ingestelde temperatuur en de ventilatieband.  het contact sluit wanneer de gemeten temperatuur hoger is dan de som van de ingestelde temperatuur en de ventilatieband.  

De onderstaande afbeelding toont de aansluitwijze van een ventilator van groep 2 of een luchtverwarmer.  

![Tweede groep](./img/2grupa.png)

**Aansluiting ALARM** bestaat uit de potentiaalvrije uitgangen NC, C en NO voor aansluiting op een alarmcentrale. Het alarm wordt in de volgende gevallen geactiveerd:  
- de temperatuur is te laag of te hoog,
- de regelaar of de temperatuursensor is beschadigd,
- de voedingsspanning van de regelaar is uitgevallen;
- de regelaar werkt niet correct (bijv. oververhitting van de regelaar)  

![Alarm](./img/alarmsc-s.png)  

**Aansluiting V1 0-10V** dient voor het aansluiten van vermogensuitbreidingsmodules of ventilatoren met een ingebouwde toerentalregeling. De spanning op deze klem is evenredig met het ventilatieniveau.  
**Aansluiting V2 0-10V** dient voor het aansluiten van de actuator die de luchtinlaatkleppen opent.  
**Aansluiting SENSOR** wordt verbonden met 1 temperatuursensor TS3 of TS5; de polariteit is niet van belang.  Het is een goede praktijk om meetkabels uit de buurt van voedingskabels te houden.  
**Aansluiting RS-485** kan worden gebruikt voor de opbouw van ventilatiesystemen en voor communicatie met een pc.  

## Werkingsprincipe  

De hoofdtaak van de regelaar is het handhaven van de temperatuur in de veehouderijruimte op het door de veehouder vastgestelde niveau. Houd er rekening mee dat de regelaar slechts een hulpmiddel is om optimale klimatologische omstandigheden in de veehouderijruimte te waarborgen. De veehouder vervult echter de belangrijkste rol in dit proces en moet de instellingen van het apparaat aanpassen aan de veranderende klimatologische omstandigheden buiten en vooral aan de behoeften van de dieren in de stal, en de bedrijfstoestand van het apparaat bewaken via de alarmcentrale.  

### Eerste inbedrijfstelling van de regelaar  

:::danger
Bij de eerste inbedrijfstelling van de regelaar moet het verboden bedrijfsbereik van de motor beslist worden ingesteld.
:::

De regelaar werkt met ventilatoren met een eenfasige asynchrone motor met een maximale totale stroomopname van 5A. Na het aansluiten van de gekozen ventilatoren moet de gebruiker deze afstemmen op de samenwerking met de regelaar. Met andere woorden: het minimale bedrijfsniveau (toerental) van de ventilator moet worden ingesteld. Deze functie heet **„Verboden bereik”** en wordt door de gebruiker eenmalig ingesteld via de **„Geavanceerde instellingen”**. Om deze handeling correct uit te voeren, wordt de hulp aanbevolen van een tweede persoon die het gedrag van de ventilator voortdurend kan observeren terwijl de andere persoon de waarde van het **„Verboden bereik”** instelt. Als het verboden bereik niet wordt ingesteld, kan het apparaat niet correct werken. De waarde van het **„Verboden bereik”** kan als correct worden beschouwd wanneer de door de ventilator opgewekte druk de kleppen van de ventilatieschacht minimaal begint op te tillen. Het **„Verboden bereik”** moet opnieuw worden ingesteld wanneer de op de regelaar aangesloten ventilator wordt vervangen.  

### Periodieke ventilatie  

Periodieke ventilatie is een door de regelaar uitgevoerde functie die wordt geactiveerd wanneer de temperatuur in de ruimte onder de ingestelde temperatuur daalt. Deze functie zorgt voor een cyclische toevoer van verse lucht voor de dieren. De periodieke ventilatie wordt bepaald door 3 parameters:
- **„Bedrijfstijd”** - bepaalt hoeveel seconden de ventilator moet worden ingeschakeld,
- **„Pauzetijd”** - bepaalt de stilstandtijd van de ventilator in seconden,
- **„Niveau periodieke ventilatie”** - bepaalt het ventilatievermogen tijdens de „Bedrijfstijd”.  

Een voorbeeldinstelling **60s/120s** betekent dat de ventilator gedurende 60s wordt ingeschakeld, met een pauze van 120s tussen opeenvolgende inschakelingen. 

Alle hierboven genoemde parameters worden door de gebruiker ingesteld. Bij het instellen van de parameters voor periodieke ventilatie moet rekening worden gehouden met enkele regels:
- periodieke ventilatie wordt uitsluitend ingeschakeld wanneer de temperatuur in de varkensstal onder de ingestelde temperatuur daalt,
- de basisfunctie van periodieke ventilatie is het waarborgen van een cyclische toevoer van verse lucht voor de dieren, niet het handhaven van de ingestelde temperatuur in de ruimte,
- het wordt aanbevolen de ruimten kort maar vaak te ventileren,
- lange perioden van periodieke ventilatie moeten worden vermeden, omdat deze tot te grote temperatuurschommelingen kunnen leiden,
- de ingestelde parameters moeten beslist worden aangepast aan het gedrag van de dieren en aan de omstandigheden zowel binnen als buiten de ruimte,
- de functie voor periodieke ventilatie kan worden uitgeschakeld; in dat geval moeten zowel in de procentuele als in de tijdgestuurde modus nulwaarden worden ingesteld op de plaats die overeenkomt met de tijdswaarde voor periodieke ventilatie, bijv.: 0/120s  

### Traploze ventilatie  

De regelaar regelt de ventilatie traploos van „Minimumtoerental” tot **„Maximumtoerental”** binnen het bereik van de **„Ingestelde temperatuur”** tot de som van de **„Ingestelde temperatuur”** en de **„Ventilatieband”**. Boven dit bereik wordt ventilatiegroep 2 ingeschakeld.  

![ventilatie](./img/wentylacjia.png)  

Boven dit bereik wordt ventilatiegroep 2 ingeschakeld. Wanneer de temperatuur in de ruimte onder de **„Ingestelde temperatuur”** daalt, ventileert de regelaar de ruimte periodiek; bij een verdere daling wordt de bijverwarming ingeschakeld. Alles is afhankelijk van de door de gebruiker ingevoerde instellingen. Het regelprogramma voorziet ook in samenwerking met een alarmcentrale, die kan worden geactiveerd wanneer de temperatuur in de varkensstal afwijkt van de ingestelde parameters.  

## Programmering van de regelaar  

De regelaar beschikt over een reeks standaardinstellingen die in twee gevallen in het niet-vluchtige geheugen worden geschreven:  
1. Eerste inbedrijfstelling van het apparaat,  
2. Fout in het gegevensgeheugen.  
Bij afwezigheid of uitval van de voeding verliest de regelaar de eerder ingevoerde en opgeslagen gebruikersinstellingen niet.  

### Gebruik van het menu  

De regelaar is uitgerust met een aantal functies waarmee hij aan de betreffende toepassing kan worden aangepast. Deze functies zijn gegroepeerd in een menu dat toegankelijk is door op een van de toetsen **(„ Pijl rechts”, „Pijl links”)** te drukken. Parameters worden gewijzigd met de toetsen **„+” en „-”**; de bewerkte parameter wordt automatisch in het niet-vluchtige geheugen opgeslagen nadat **30s** is verstreken sinds de laatste toetsdruk.  

### Functies van het basismenu  

| MENU                       | Beschrijving | 
|:---:                       |:---|
|Temperatuur  <br />20,8°C W16% A  |**„Informatiemodus”** - normaal bedrijf. Het display toont de huidige temperatuur en, wanneer de ventilator is ingeschakeld, het ventilatieniveau. Betekenis van de aanvullende symbolen: A-betekent dat het alarm is geactiveerd, D  - betekent dat de verwarming is ingeschakeld, W - betekent aanvullende ventilatie| 
|Ingestelde temp.  <br />20,0°C        |**„Ingestelde temperatuur”** – temperatuurwaarde die het begin van het traploze ventilatieproces bepaalt.   | 
|Periodieke ventilatie  <br />20s / 200s  |**„Periodieke ventilatie”** – er worden twee tijdswaarden ingesteld: 1 „Bedrijfstijd”, 2 „Pauzetijd” tussen opeenvolgende cyclische inschakelingen van de ventilatie.| 
|Niveau period. vent.  <br />20%        |**„Niveau periodieke ventilatie”** - ventilatieniveau tijdens de bedrijfstijd van de periodieke ventilatie   | 
|Minimumalarm  <br />12,0°C       |**„Minimumalarm”** - bepaalt de absolute minimumtemperatuur waarbij het alarm wordt geactiveerd. 
|Maximumalarm  <br />28,0°C       |**"Maximumalarm"** - bepaalt de absolute maximumtemperatuur waarbij het alarm wordt geactiveerd.  | 
|Bijverwarming  <br />12,0°C         |Afhankelijk van de configuratie worden de volgende functies uitgevoerd: **„Bijverwarming”** - het contact sluit wanneer de temperatuur onder de aangegeven waarde daalt. | 
|Ventilatie van trap 2  <br />25,0  |**„Ventilatie van trap 2”** - het contact sluit wanneer de gemeten temperatuur de som van de ingestelde temperatuur en de ventilatieband overschrijdt. | 
|Ventilatieband  <br />5,0°C     |**„Ventilatieband”** - bepaalt de reactiesnelheid van de regelaar (verandering van het ventilatieniveau van minimum 1 tot maximum 1) op een stijgende temperatuur. | 
|Minimumtoerental  <br />1%        |**„Minimumtoerental”** – dit is een toestand waarin het apparaat voor onbepaalde tijd blijft en een spanning met de ingestelde waarde aan de uitgang levert. Dit dient voor de kalibratie van het apparaat met de motor en het kleppenmechanisme.   | 
|Maximumtoerental  <br />100%      |**„Maximumtoerental”** – dit is een toestand waarin het apparaat voor onbepaalde tijd blijft en een spanning met de ingestelde waarde aan de uitgang levert. Dit dient voor het beperken van het voor ventilatie gebruikte vermogen| 

### Geavanceerd menu  

Het geavanceerde menu is voornamelijk bedoeld voor installateurs en maakt het mogelijk de regelaar op de installatie en de ventilator af te stemmen. U opent de geavanceerde instellingen door de twee menutoetsen ongeveer 10s ingedrukt te houden.  

| MENU                                 | Beschrijving| 
|:---:                                 |:--- |
|Geen geavanceerde  <br />instellingen   |Deze melding geeft aan dat de regelaar niet met de ventilatie is gekalibreerd en mogelijk niet correct werkt. Het geavanceerde menu moet worden geopend en het „Verboden bereik” moet worden ingesteld.|
|Instellingen <br />Geavanceerd         |Aanduiding dat de geavanceerde instellingen zijn geopend. | 
|Softwareversie:  <br />1907       |Informatie over de softwareversie.| 
|Verboden bereik  <br />1000 us       |Kalibratie van het minimumtoerental van de rechtstreeks op de regelaar aangesloten ventilatoren; deze parameter komt overeen met ventilatieniveau „1%”|  
|Contactfunctie  <br />Bijverwarming     |Keuze van de contactfunctie:  <br />• Bijverwarming (standaard)<br />• Ventilatiegroep 2 | 
|Periodieke ventilatie  <br />Tijdgestuurd         |Keuze van het type periodieke ventilatie: <br />• Tijdgestuurd (standaard) <br />• Procentueel| 
|Bereik V1  <br />van 2,0 tot 10,0       |Instelling van het spanningsbereik op uitgang V1 0÷10V. De instellingen betreffen de minimale en maximale spanningswaarde. De regeling wordt gebruikt om de regelaar af te stemmen op een vermogensuitbreiding of frequentieregelaar.| 
|Inversie V1  <br />Nee                |Bij activering wordt de karakteristiek van uitgang V1 omgekeerd. De spanning daalt naarmate het ventilatieniveau stijgt, binnen het door min.-max. ingestelde bereik. Het signaal op uitgang V1 is van het type 10-0V.| 
|Afschakeling V1  <br />Nee                |Bij activering wordt op uitgang  V1 0-10V niveau 0V geleverd in plaats van de ingestelde minimumwaarde wanneer het ventilatieniveau 0% bedraagt.| 
|Bereik V2  <br />van 2,0 tot 10,0       |Instelling van het spanningsbereik op uitgang V2 0÷10V. De instellingen betreffen de minimale en maximale spanningswaarde. De regeling wordt gebruikt voor de kalibratie van het kleppensysteem.|
|Inversie V2  <br />Nee      	       |Bij activering wordt de karakteristiek van uitgang V2 omgekeerd. De spanning daalt naarmate het ventilatieniveau stijgt, binnen het door min.-max. ingestelde bereik. Het signaal op uitgang V2 is van het type 10-0V.|
|Temp.kalibratie  <br />21,0°C -> 22,0°C|Kalibratie van de temperatuursensor maakt het mogelijk de afgelezen waarde opnieuw te schalen.|
|Softstart  <br />50%      	           |Bepaling van het ventilatieniveau bij elke start van de ventilator; de ventilator wordt versneld tot de aangegeven waarde en gaat daarna over naar het ingestelde niveau.| 
|Taal  <br />Pools    	           |Keuze van de menutaal: Pools, Engels, Duits, Russisch|
|Afsluiten                               |Afsluiten van het geavanceerde menu met de toets „+”; de ingevoerde wijzigingen worden in het niet-vluchtige geheugen opgeslagen.|

### Fout- en waarschuwingsmeldingen  

Foutmeldingen dienen om de gebruiker te informeren over onregelmatigheden in de werking van de regelaar. Hieronder staan de mogelijke foutmeldingen.  

|FOUT                                    | BESCHRIJVING |
|:---:                                   |:--- |
|Alarm  <br />Overbelasting 	         |Overbelastingsalarm, geactiveerd bij 75°C. Het apparaat onderbreekt de werking totdat het is afgekoeld.|
|SENSOR ONDERBROKEN!  <br />Controleer sensor|Onderbroken sensor; geeft een beschadiging van de sensor of de aansluitkabel aan.|
|SENSOR KORTGESLOTEN!  <br />Controleer sensor  |Kortgesloten sensor; geeft een beschadiging van de sensor of de aansluitkabel aan.|
|Uitval  <br />Voeding                  |Voedingsuitval, te lage voedingsspanning, onjuiste frequentie of sterk vervormde voedingsspanning.| 

## Opmerkingen en waarschuwingen  

:::danger 
Tijdens de installatie van het apparaat moet de stroomtoevoer absoluut worden onderbroken, omdat de spanning op sommige onderdelen gevaarlijk is voor leven en gezondheid. Het wordt aanbevolen de installatie door een gekwalificeerd persoon te laten uitvoeren.
:::

- Om problemen bij het gebruik van het apparaat te voorkomen, moet de handleiding vóór installatie en gebruik worden gelezen.  
- Het is verboden de constructie te wijzigen of zelf reparaties uit te voeren. Dit geldt met name voor wijzigingen aan elementen en onderdelen.  
- Onderhouds- of servicewerkzaamheden moeten worden uitgevoerd door bevoegd personeel (installateur of servicedienst van de fabrikant). In stallen met geforceerde ventilatie is een alarmsysteem vereist. De fabrikant van het apparaat is niet aansprakelijk voor schade als gevolg van onjuiste installatie, onjuiste programmering van functies, de gevolgen van onvoorziene gebeurtenissen en externe factoren.  
- De parameters van de ventilatieregelaar moeten worden ingesteld overeenkomstig de omstandigheden in de veehouderijruimte. Deze instellingen zijn individueel en afhankelijk van de beslissing van de veehouder. De fabrikant van het apparaat behoudt zich het recht voor om de constructie van het apparaat en de software te wijzigen.  


:::caution
![alternatieve tekst](./img/trash.svg) Na beëindiging van het gebruik mag het product niet samen met ongesorteerd huishoudelijk afval worden weggegooid, maar moet het worden afgevoerd overeenkomstig de geldende voorschriften (WEEE-richtlijnen van de Europese Unie 2012/19/EU). <br />Het product is vervaardigd overeenkomstig de RoHS-vereisten (richtlijn van de Europese Unie 2011/65/EU).
:::

<!-- \newpage -->
## Technische gegevens van de regelaar  

|Parameter                        |	BESCHRIJVING      |
|:-----------                    |:---------- |
|Voedingsspanning|	230VAC 50Hz|
|Maximale stroom van de traploos geregelde uitgang FAN|	6A|
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
|Bestandheid tegen overspanning (max E)|	210J|
|Overbelastingsbeveiliging|	75°C|
|Afmetingen van het apparaat|	20x15x8 [cm]|
|Beschermingsgraad van de behuizing|	IP56|
  


:::info
De regelaar SPEED CONTROL SERVOMOTOR wordt geleverd met:
- 1 temperatuursensor + accessoires,
- 4 pluggen,
- 1 zekering 10A.
:::

