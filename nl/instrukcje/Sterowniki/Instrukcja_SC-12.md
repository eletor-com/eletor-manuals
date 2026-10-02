---
sidebar_position: 3
title: Handleiding SC-12
description: Klimaatregelaar voor stallen met een toegestane uitgangsstroom tot 12A
keywords:
- eletor sc-12
- ventilatieregelaar
- klimaatregelaar
- ventilatieregelaar voor varkensstallen
- microklimaatregelaar
- regelaar voor varkensstallen
- ventilatie van varkensstallen
- regelaar voor opfokruimten
---

# Regelaar SC-12

Microprocessorgestuurde klimaatregelaar uit de serie SPEED CONTROL. De veelzijdigheid van het apparaat wordt gewaarborgd door het grote aantal in- en uitgangen en intuïtieve software in het Pools en Engels. Naast de basisinstellingen voor temperaturen, periodieke ventilatie, bijverwarming, minimale/maximale ventilatieniveaus en alarmen biedt het regelprogramma de mogelijkheid om de op de regelaar aangesloten actuatoren te testen en hun kalibratie op te slaan.

**Parameters en kenmerken:** 
- Ventilatie van groep I: 
  - max. stroom van de uitgang voor traploze regeling 12A,
  - thermische beveiliging van het systeem, 
  - geleidelijke aanloop van de ventilatie – softstart,
  - overbruggingsrelais bij volledige aansturing, 
  - kalibratie van het minimale toerental, 
  - energiebesparingsprogramma met een systeem van kleppen die vooraf worden geopend.
- Ventilatie van groep II, potentiaalvrij contact tot 6A.
- Bijverwarming, potentiaalvrij contact tot 6A
- Alarmuitgangen NO en NC: 
  - signalering van spanningsuitval,
  - signalering van overschrijding van de minimale of maximale temperatuurgrens,
  - ingebouwde akoestische signaalgever.
- Onafhankelijke 3 uitgangen 0..10V:
  - ondersteuning van uitbreidingsmodules,
  - aansturing van het kleppensysteem, 
  - regeling van verwarming met variabel vermogen.**
- Twee analoge ingangen voor temperatuurmeting.
- Digitale poort voor temperatuurmeting (tot 4 sensoren).
- Twee functionele relaisuitgangen (naar keuze):
  - ondersteuning van lineaire actuatoren, 
  - III en IV ventilatiegroep
- Twee analoge ingangen 0-10V.
- Voeding voor de potentiometer DC 10V.
- Aanvullende voeding DC 12V.
- Mogelijkheid tot samenwerking met een computer tot 1200m.
- Hermetische behuizing IP65.
- Voedingsspanning 230VAC 50Hz.
- Opgenomen vermogen van het systeem < 10V

# Installatie van de regelaar
:::danger 
 Tijdens de installatie van het apparaat moet de elektrische voeding beslist worden uitgeschakeld, omdat de spanning op bepaalde onderdelen gevaarlijk is voor leven en gezondheid. Het wordt aanbevolen de installatie door een gekwalificeerd persoon te laten uitvoeren.  Deze handeling is gevaarlijk
:::

## Keuze van de montageplaats
De montageplaats moet zorgvuldig worden gekozen, zodat het apparaat gemakkelijk toegankelijk is voor bevoegde personen en ontoegankelijk is voor dieren en kinderen. Ook moet rekening worden gehouden met de klimaatomstandigheden, dat wil zeggen dat het apparaat moet werken binnen een temperatuurbereik van -10°C tot 40 °C, op een plaats zonder directe zoninstraling. Rond het apparaat moet de lucht vrij kunnen circuleren. Het apparaat omvat een temperatuursensor.  

### Voor de montage van de temperatuursensor gelden enkele regels:
 - de sensor mag niet worden gemonteerd op een plaats zonder luchtcirculatie of met directe zoninstraling,
 - de sensor mag niet worden gemonteerd op een dragende (buiten)muur van het gebouw,
 - vermijd de nabijheid van warmte afgevende apparaten, zoals radiatoren en lampen,
 - plaats de sensor niet direct naast deuren en ventilatieopeningen,
 - plaats de sensor niet op plaatsen die toegankelijk zijn voor dieren,
 - het wordt aanbevolen de aansluitkabel van de sensor op afstand van voedingskabels te leggen.

# Montage
Het apparaat kan onder agressieve klimaatomstandigheden werken. Een correct gemonteerde regelaar en temperatuursensor zijn bestand tegen schadelijke omgevingsinvloeden.  

### Tijdens de montage moet op de volgende punten worden gelet:
 - controleer de afdichting van het deksel voordat het wordt vastgeschroefd,
 - het deksel moet met alle schroeven worden vastgezet,
 - de voor aansluiting van de regelaar gebruikte kabels moeten rond zijn,
 - draai na aansluiting van de kabel de kabelwartels vast, zodat de kabel wordt afgedicht en vastgezet; het gebruik van silicone wordt aanbevolen,
 - ongebruikte doorvoeren (kabelwartels) moeten worden afgedicht,
 - bevestig de regelaar (het onderste deel van de behuizing) met 4 pluggen aan een vlakke muur.

# Elektrische aansluiting
:::danger 
 Controleer vóór aansluiting van het systeem of de voeding is uitgeschakeld!
Deze handeling is gevaarlijk
:::

Voordat de regelaar wordt aangesloten, moet het deksel worden losgeschroefd en verwijderd. Voer de kabels door de rubberen kabelwartels; daarna kunnen ze worden aangesloten. De aansluitklemmen van de regelaar zijn weergegeven in de onderstaande afbeelding.

![Aansluiting ](./img/sc-12.png)

**De aansluiting AC 230V** wordt verbonden met de voeding (verdeelinrichting). Het gebruik van een installatieautomaat 1P-B6 en overspanningsbeveiligingen van het type T1 T2 is vereist. Bij aansluiting van meerdere apparaten is het een goede praktijk de regelaars over verschillende „fasen” (L1, L2, L3) te verdelen om de voedingslijn gelijkmatig te belasten.

**De aansluiting FAN** moet rechtstreeks op de ventilator worden aangesloten. Bij aansturing van meerdere ventilatoren mag de totale belasting niet hoger zijn dan 6A; elke ventilator moet afzonderlijk worden beveiligd. PE en N mogen niet vanuit de voeding (verdeelinrichting) worden betrokken; ze moeten beslist op de aansluitingen van de regelaar worden aangesloten.

**De aansluiting FAN 2** kan worden gebruikt voor aansluiting van ventilatoren van groep 2 of sproeisystemen. De uitgang is potentiaalvrij, de maximale contactstroom bedraagt 6A (een externe installatieautomaat van het type 1P-B6 is vereist bij rechtstreekse aansturing van de belasting); het contact sluit wanneer de gemeten temperatuur hoger is dan de som van de ingestelde temperatuur en de ventilatieband.

**De aansluiting HOT** kan worden gebruikt voor aansluiting van een luchtverwarmer. De uitgang is potentiaalvrij, de maximale contactstroom bedraagt 6A (een externe installatieautomaat 1P-B6 is vereist bij rechtstreekse aansturing van de belasting); het contact sluit wanneer de gemeten temperatuur onder de ingestelde waarde daalt.

**De aansluiting ALARM** heeft potentiaalvrije uitgangen NC, C en NO voor aansluiting op een alarmcentrale. Het alarm wordt in de volgende gevallen geactiveerd:
    - de temperatuur is te laag of te hoog,
    - de regelaar of de temperatuursensor is defect,
    - de voedingsspanning van de regelaar is uitgevallen,
    - de regelaar werkt niet correct (bijv. oververhitting van de regelaar)
De onderstaande afbeelding toont hoe de ventilator op de alarmcentrale wordt aangesloten.

![Alarmaansluiting](./img/alarmsc-s.png)

**De aansluiting FUNC1 en FUNC2** dient voor aansluiting van een lier voor het openen van luchtinlaten, gebaseerd op een motor met rechts-/linksloop. Relais FUNC1 schakelt de stroom voor de actuator in en FUNC2 schakelt de draairichting van de motor om. Voorbeeld van een aansluitschema voor de lier (een externe installatieautomaat 1P-B6 is vereist):
Bij deactivering van de lierfunctie werken de uitgangen FUNC1 en FUNC2 als contacten van respectievelijk ventilatiegroep 3 en 4.

![Aansluiting van de lier](./img/Sc-12fan.png)

**De aansluiting 12V** is bestemd voor de voeding van externe sensoren.

**De aansluiting V1 0-10V** dient voor aansluiting van vermogensuitbreidingsmodules. De spanning op deze klem is evenredig met het ventilatieniveau.

**De aansluiting V2 0-10V** dient voor aansluiting van de actuator die de luchtinlaatkleppen opent.

**De aansluiting V3 0-10V** dient voor aansluiting van een verwarmingssysteem met traploos regelbaar vermogen. De spanning op deze uitgang neemt evenredig toe met de temperatuurdaling vanaf de bijverwarmingstemperatuur.

**De aansluiting 10V** dient voor de voeding van de potentiometer van de lier of andere systemen van het type 0-10V.

**De aansluiting SENS1 (SENS2)** wordt verbonden met 1 temperatuursensor TS3 of TS5; de polariteit is niet van belang. Bij gelijktijdige aansluiting van 2 sensoren worden de gemeten temperaturen gemiddeld. Het is een goede praktijk de meetkabels op afstand van de voedingskabels te houden.

**De aansluiting 1-WIRE** kan worden gebruikt voor aansluiting van een groter aantal digitale temperatuursensoren, maximaal 4, die parallel worden aangesloten (de juiste polariteit moet in acht worden genomen). De maximale lengte van de aansluitkabel voor de sensoren bedraagt 150m (de lengte heeft geen invloed op de temperatuurmeting); het gebruik van een afgeschermde kabel wordt aanbevolen.

**De aansluiting RS-485** kan worden gebruikt voor de opbouw van ventilatiesystemen en voor communicatie met een pc.

**De aansluiting IN1 0-10** dient voor het invoeren van een terugkoppelingssignaal van het luchtinlaatsysteem – dit geeft de actuele stand van de inlaten aan.

**De aansluiting IN2 0-10** dient voor aansluiting van de regelaar op andere sensoren, bijv. voor luchtvochtigheid, CO2, of voor gebruik van de regelaar als vermogensuitbreiding.

# Werkingsprincipe
De belangrijkste taak van de regelaar is het handhaven van de temperatuur in de dierenverblijfsruimte op het door de veehouder ingestelde niveau. Houd er rekening mee dat de regelaar slechts een hulpmiddel is om optimale klimaatomstandigheden in de dierenverblijfsruimte te realiseren. De veehouder speelt echter de belangrijkste rol in dit proces: hij moet de instellingen van het apparaat aanpassen aan de veranderende klimaatomstandigheden buiten en vooral aan de behoeften van de dieren in de stal, en de werking van het apparaat via de alarmcentrale bewaken.

## Eerste ingebruikname van de regelaar
:::danger 
 Bij de eerste ingebruikname van de regelaar moet beslist het verboden werkingsgebied van de motor worden ingesteld.

:::
De regelaar werkt met ventilatoren met een eenfasige asynchrone motor met een maximale totale stroomopname van 12A. Na aansluiting van de gekozen ventilatoren moet de gebruiker deze afstemmen op de werking met de regelaar. Met andere woorden: het minimale werkingsniveau (toerental) van de ventilator moet worden ingesteld. Deze functie heet „Verboden band” en wordt door de gebruiker eenmalig ingesteld via „Geavanceerde instellingen”. Om deze handeling correct uit te voeren, wordt de hulp van een tweede persoon aanbevolen, die het gedrag van de ventilator voortdurend kan observeren terwijl de andere persoon de waarde van de „Verboden band” instelt (de fabriekswaarde bedraagt 0). Als de verboden band niet wordt ingesteld, kan het apparaat onjuist werken. De waarde van de „Verboden band” kan als correct worden beschouwd zodra de door de ventilator opgewekte druk de kleppen van de ventilatieschacht enigszins begint op te tillen. De „Verboden band” moet opnieuw worden ingesteld wanneer de op de regelaar aangesloten ventilator wordt vervangen.

## Periodieke ventilatie
Periodieke ventilatie is een door de regelaar uitgevoerde functie die wordt gestart wanneer de temperatuur in de ruimte onder de ingestelde temperatuur daalt. Deze functie voorziet de dieren cyclisch van verse lucht. In het menu Periodieke ventilatie zijn 3 parameters beschikbaar:
- **„Bedrijfstijd”** - bepaalt hoeveel minuten de ventilator moet worden ingeschakeld;
- **„Pauzetijd”** - bepaalt de stilstandtijd van de ventilator;
- **„Niveau periodieke ventilatie”** - bepaalt het ventilatievermogen tijdens de „Bedrijfstijd”.

Alle hierboven genoemde parameters worden door de gebruiker ingesteld. 

### Bij het instellen van de parameters voor periodieke ventilatie moet met enkele regels rekening worden gehouden:
- periodieke ventilatie wordt uitsluitend ingeschakeld wanneer de temperatuur in de varkensstal onder de ingestelde temperatuur daalt,
- de hoofdfunctie van periodieke ventilatie is de dieren cyclisch van verse lucht te voorzien, niet het handhaven van de ingestelde temperatuur in de ruimte,
- het wordt aanbevolen de ruimten kort maar vaak te ventileren,
- vermijd lange perioden van periodieke ventilatie, omdat deze tot te grote temperatuurschommelingen kunnen leiden,
- de ingestelde parameters moeten beslist worden aangepast aan het gedrag van de dieren en de omstandigheden zowel binnen als buiten de ruimte.

## Werking van het apparaat
De regelaar regelt de ventilatie traploos van **„Min.1” tot „Max.1”** binnen het bereik van de **„Ingestelde temperatuur”** tot de som van de **„Ingestelde temperatuur”** en de **„Ventilatieband 1gr.”**. Boven dit bereik wordt ventilatiegroep 2 ingeschakeld en verandert groep 1 het niveau naar **„Min.2”**; bij een verdere temperatuurstijging neemt de ventilatie toe tot **„Max.2”**, aan het einde van het bereik van de **„Ventilatieband 2 gr.”**. Wanneer de **„Ventilatieband 2 gr.”** op nul is ingesteld en de ventilatie op **„Max.1”** werkt, wordt ventilatiegroep 2 ingeschakeld en leidt een verdere temperatuurstijging niet meer tot veranderingen in de ventilatie (het gestippelde deel van de grafiek). Wanneer de temperatuur in de ruimte onder de **„Ingestelde temperatuur”** daalt, ventileert de regelaar de ruimte periodiek; bij een verdere daling wordt de bijverwarming ingeschakeld. Alles is afhankelijk van de door de gebruiker ingevoerde instellingen. Het regelprogramma houdt ook rekening met samenwerking met een alarmcentrale, die kan worden geactiveerd wanneer de temperatuur in de varkensstal afwijkt van de ingestelde parameters. 

![Ventilatie](./img/Sc-12wentyl.png)  

## Programmering van de regelaar
De regelaar beschikt over een reeks standaardinstellingen die in twee gevallen in het niet-vluchtige geheugen worden geschreven:
1. Eerste ingebruikname van het apparaat,
2. Fout in het gegevensgeheugen.
Bij ontbrekende voeding of spanningsuitval verliest de regelaar de eerder ingevoerde en opgeslagen gebruikersinstellingen niet.

## Voorpaneel – indicatoren, toetsen en display
![Paneel](./img/SC-12panel.png)  
    1. Rood controlelampje dat overschrijding van de maximaal toegestane temperatuur aangeeft.
    2. Rood controlelampje dat onderschrijding van de minimaal toegestane temperatuur aangeeft.
    3. Geel controlelampje dat bijverwarming aangeeft.
    4. Geel controlelampje dat ventilatie van groep 2 aangeeft.
    5. Groen controlelampje dat handmatige instelling van het ventilatieniveau aangeeft.
    6. Groen controlelampje dat actieve communicatie RS485 aangeeft.
    7. Menudisplay, toont de temperatuur tijdens normaal bedrijf.
    8. Balkindicator die het ventilatieniveau aangeeft.
    9. Toets om omhoog door het menu te navigeren of de parameterwaarde te wijzigen.
    10. Toets ESC - om het menu of de betreffende parameter te verlaten zonder de waarde op te slaan.
    11. Toets OK - om het menu te openen of de betreffende parameter te bevestigen (op te slaan).
    12. Toets om omlaag door het menu te navigeren of de parameterwaarde te wijzigen.

## Gebruik van het menu
De regelaar is uitgerust met een reeks functies waarmee hij aan de betreffende toepassing kan worden aangepast. Deze functies zijn gegroepeerd in een menu dat toegankelijk is door op een van de toetsen **(„+”, „-” of „OK”)** te drukken. De toetsen **„+”** en **„-”** dienen om functies te selecteren; bewerken, gegevens opslaan of een volgend submenu openen kan met de toets **„OK”**. Druk op de toets **„Esc”** om terug te keren naar het bovenliggende menu of om het opslaan van de betreffende parameter te annuleren.

## Functies van het basismenu

| MENU                          | Beschrijving       | 
|:-----------                   |:---------- |
| Temperatuur 20,8o C W16% A    | **Informatiemodus** - normaal bedrijf. Het display toont de actuele temperatuur en, wanneer de ventilator draait, de waarde van het ventilatieniveau. Betekenis van de aanvullende symbolen:A-betekent dat het alarm is ingeschakeld,D  - betekent dat de verwarming is ingeschakeld, W - betekent aanvullende ventilatie| 
|   Ingestelde temp.   20,0o C      |**„Ingestelde temperatuur”** – Bepaalt de temperatuur waarbij het proces van traploze ventilatie begint. Kies een geschikte waarde afhankelijk van de diersoort.| 
| Periodieke ventilatie     | **Periodieke ventilatie** – er worden twee tijdwaarden ingesteld.    1.**Bedrijfstijd** Bepaalt het aantal minuten dat de ventilatie werkt.    2.**Pauzetijd** Bepaalt het aantal minuten dat de ventilatie stilstaat tussen opeenvolgende bedrijfscycli.    3.**Niveau periodieke ventilatie** - Bepaalt de ventilatiesterkte tijdens de periodieke ventilatie.| 
| Alarm |  1.**Alarm actief Ja** - Activering/Deactivering van het alarmcontact; om te voorkomen dat de regelaar een alarmsignaal op de uitgang (naar de alarmcentrale) afgeeft, kiest u „NEE” in het menu.  2. **Temp. Min. 15,0o C** - Bepaalt de absolute minimumtemperatuur waarbij het alarm wordt ingeschakeld.  3.**Temp. Max. 25,0o C** - Bepaalt de absolute maximumtemperatuur waarbij het alarm wordt ingeschakeld.  4.**Alarmsignaal Ja** - Activering/Deactivering van het akoestische signaal in de regelaar. | 
|    Ventilatie        |  1.**Vent.band 1 5,0o C**   - Bepaalt de reactiesnelheid van de regelaar (verandering van het ventilatieniveau van minimum 1 tot maximum 1) op een stijgende temperatuur.  2.**Min. niveau 1 1 %** - Bepaalt het ventilatieniveau dat overeenkomt met de ingestelde temperatuur.  3.**Max. niveau 1 100 %**-Bepaalt het vaste ventilatieniveau voor een temperatuur boven het bereik van de traploze regeling wanneer „Vent.band 2gr.” = 0, en anders het maximale niveau van de geregelde ventilatie voor een temperatuur die gelijk is aan de som van de ingestelde temp. en de band van groep 1.  4.**Vent.band 2 0,0o C**-Bepaalt de reactiesnelheid van de regelaar (verandering van het ventilatieniveau van minimum 2 tot maximum 2) op een stijgende temperatuur voor groep 2. De functie is niet actief wanneer de band gelijk is aan nul.  5.**Min. niveau 2 1 %**-Bepaalt het minimale ventilatieniveau van groep 1 op het moment dat de contacten van groep 2 sluiten.  6.**Max. niveau 2 100 %**-Bepaalt het vaste ventilatieniveau voor een temperatuur boven het bereik van de traploze regeling wanneer groep 2 is ingeschakeld.  7.**Groep 3  5,0o C**-Bepaalt het vaste ventilatieniveau voor een temperatuur boven het bereik van de traploze regeling wanneer groep 2 is ingeschakeld.  8.**Groep 4 7,0o C**-Bepaalt de temperatuur ten opzichte van de ingestelde temperatuur waarbij ventilatiegroep 4 wordt ingeschakeld (de lierfunctie moet gedeactiveerd zijn).| 
|    Bijverwarming  |  1.**Bijverw.temp. 15,0o C**-Bepaalt de inschakeltemperatuur van de bijverwarming.  2.**Bijverw.band 5,0o C** -Bepaalt de verhouding van het vermogen van de bijverwarmingssystemen (op uitgang V3 0-10V) afhankelijk van de temperatuur. | 

## Functies van het geavanceerde menu
Het geavanceerde menu is voornamelijk bestemd voor installateurs en maakt het mogelijk de regelaar af te stemmen op de installatie en de ventilator, circuits te testen en de menutaal te selecteren. De geavanceerde instellingen worden geopend door twee menutoetsen gedurende ongeveer 10s ingedrukt te houden. 

| MENU                          | Beschrijving       | 
|:-----------                   |:---------- |
|Testen  |Deze functie dient om de afzonderlijke uitgangscircuits van de regelaar te controleren. Alle instellingen zijn tijdelijk en gelden alleen zolang het betreffende menuonderdeel geopend is; na het indrukken van „ESC” of „OK” keert de betreffende uitgang terug naar de toestand die uit de werking van de regelaar voortvloeit.  1.**Ventilatie 0 %**  Maakt handmatige invoer van het ventilatieniveau mogelijk om het ventilatiesysteem te controleren. Na bevestiging van de functie gaat het groene controlelampje (handje) branden.  2.**Alarm Nee** Activering schakelt 2 rode controlelampjes, het akoestische signaal en het alarmcircuit in.  3.**Bijverwarming Nee** Activering schakelt het gele controlelampje (vlammetje) en het bijverwarmingscircuit in.  4.**Vent. 2 trap Nee** Activering schakelt het gele controlelampje (ventilator) en het circuit van groep 2 in.  5.**Uitgang V1 0,0 V  Uitgang V2  0,0 V Uitgang V3  0,0 V**-Test van uitgangen 0-10V; met de toetsen „+” of „-” kan een gekozen spanning worden ingesteld voor achtereenvolgens: uitbreidingsmodules, luchtinlaatkleppen en traploze bijverwarming. De functie is bijzonder nuttig bij de kalibratie van Uitgang V2 voor de luchtinlaatkleppen.  6.**Lier 0** Maakt controle van het luchtinlaatkleppensysteem mogelijk: „+” - opent de inlaten, „-” - sluit de inlaten; het display toont de actuele stand van de actuator zoals afgelezen van de potentiometer.  7.**Groep 3 Nee**  Activering schakelt het circuit van ventilatiegroep 3 in. (de lierfunctie moet gedeactiveerd zijn)  8.**Groep 4 Nee**  Activering schakelt het circuit van ventilatiegroep 4 in. (de lierfunctie moet gedeactiveerd zijn)|
|Taal        | Selectie van de menutaal. Er kan worden gekozen tussen Pools en Engels. | 
|Ventilator         |  1.**Verboden band 0**- Kalibratie van het minimale toerental van de rechtstreeks op de regelaar aangesloten ventilatoren; deze parameter komt overeen met ventilatieniveau „1%”. Een positieve parameterwaarde verhoogt het toerental, een negatieve verlaagt het.  2.**Uitbr.module Min. 1,9 V** -Minimale spanning die aan de vermogensuitbreidingsmodule wordt geleverd (uitgang V1 0-10V).  3.**Uitbr.module Max. 10,0 V** -Maximale spanning die aan de vermogensuitbreidingsmodule wordt geleverd (uitgang V1 0-10V).  4.**Module uitschakelen Nee** - Uitschakeling van de vermogensuitbreidingsmodule; wanneer „JA” is geselecteerd, daalt de spanning op de uitgang voor aansturing van de uitbreidingsmodules (V1 0-10V) naar niveau 0V in plaats van de ingestelde minimumwaarde wanneer het ventilatieniveau 0% bedraagt.  5.**Inversie  Nee**-Activering keert de karakteristiek van uitgang V1 om. De spanning daalt naarmate het ventilatieniveau stijgt binnen het door min.-max. bepaalde bereik. Het signaal op uitgang V1 is van het type 10-0V.| 
| Luchtinlaatkleppen       |  1.**Vooropening 0,0o C**-Eerder openen van de luchtinlaatkleppen. De ingestelde parameter bepaalt hoeveel graden vóór het bereiken van de „Ingestelde temperatuur” de luchtinlaatkleppen moeten openen.  2.**Volledig sluiten  Nee**- Activering zorgt ervoor dat de spanning op de uitgang voor aansturing van de luchtinlaatkleppen (V2 0-10V) daalt naar niveau 0V in plaats van de ingestelde minimumwaarde. Dit geldt wanneer er geen ventilatie is (ventilatieniveau 0%).  3.**Kleppen min.  1,9 V**- Minimale spanning die aan de luchtinlaatkleppen wordt geleverd (uitgang V2 0-10V).  4.**Kleppen max.  10,0 V**- Maximale spanning die aan de luchtinlaatkleppen wordt geleverd (uitgang V2 0-10V).  5.**Inversie   Nee**-Activering keert de karakteristiek van uitgang V2 om. De spanning daalt naarmate het ventilatieniveau stijgt binnen het door min.-max. bepaalde bereik. Het signaal op uitgang V2 is van het type 10-0V. |  
| Temperatuurmeting  |  1.**Kalibratie S1 23,0o C -> 23,5o C**,**Kalibratie S2 23,0o C -> 23,2o C** - Kalibratie voor de analoge ingangen maakt herschaling van de van sensoren S1 en S2 afgelezen temperatuur mogelijk.  2.**Middelingstijd 60 s**- Deze parameter bepaalt de tijdsperiode waarover de actuele temperatuurmetingen worden gemiddeld. De gemiddelde temperatuurwaarde is de basisparameter voor de functies van de regelaar. Toestandsveranderingen van de uitgangen (ventilatie, bijverwarming, kleppen, volgende ventilatiegroepen, alarmen,...) zijn nauw verbonden met deze parameter en kunnen niet vaker optreden dan de hier bepaalde tijd. | 
| Lier      |  1.**Kalibratie Open 1024 -> 853**,**Kalibratie Gesloten 0 -> 324** -Kalibratie van de lier is noodzakelijk voor de correcte werking van het luchtinlaatsysteem. De toets „+” opent de inlaten, de toets „-” sluit de inlaten. Tijdens het openen van de inlaten moet de positieparameter toenemen en tijdens het sluiten afnemen; anders moet de aansluiting van de actuator (voeding en potentiometer) worden gecontroleerd. Bij de kalibratie van de open stand worden de inlaten volledig geopend en wordt de positie met de toets „OK” bevestigd. Bij de kalibratie van de gesloten stand worden de inlaten gesloten en wordt de positie met de toets „OK” bevestigd. Met de toets „ESC” wordt de functie verlaten zonder op te slaan. Het verschil tussen de open en gesloten stand moet minimaal 100 eenheden bedragen.  2.**Deactivering Nee**-Deactivering maakt de contacten FUNC1 en FUNC2 vrij van de aansturing van de lier; deze contacten dienen dan voor ventilatiegroep 3 en 4.| 
| Softstart               | De parameters in deze menugroep regelen de aanloop van de ventilatie. Het inschakelen van de ventilatie in de traploos geregelde groep wordt voorafgegaan door een geleidelijke aanloop tot 100%, een korte werking op 100%  en een daling naar het vereiste ventilatieniveau. Daardoor ontstaat bij het starten van de ventilatie een luchtstoot die het openen van de vlinderkleppen in de schachten vergemakkelijkt.   De waarden worden uitgedrukt in perioden van de voedingsspanning bij 1% ventilatie.  1.**Aanlooptijd 5**- Deze parameter bepaalt de snelheid waarmee het ventilatortoerental stijgt van nul tot maximaal – geleidelijk inschakelen van de ventilatoren. De waarde 0 schakelt de geleidelijke aanloop uit.  2.**Tijd 100%   100**- Deze parameter bepaalt de bedrijfstijd bij het starten op 100% van het ventilatieniveau. Door de aanlooptijd en 100% op 0 in te stellen, wordt de luchtstoot bij het starten van de ventilatie volledig uitgeschakeld.  3.**Uitlooptijd 5**-  Deze parameter bepaalt de snelheid waarmee het ventilatieniveau verandert. | 
|Bijverwarming              |  1.**Contactinversie Nee**-Activering keert de karakteristiek van uitgang HOT om. Het contact wordt  geopend naarmate de gemeten temperatuur daalt.  2.**Hysterese  0,5o C** - Bepaalt de temperatuurhysterese voor het bijverwarmingscontact.  3.**Relatieve werking Nee**- Activering maakt relatieve instelling van de bijverwarmingstemperatuur ten opzichte van de ingestelde temperatuur mogelijk. Het basismenu voor bijverwarming verandert; daarin wordt dan het verschil ten opzichte van de ingestelde temperatuur opgegeven.  4.**Bijverwarming min. 1,9 V** - Minimale spanning die wordt geleverd voor traploze aansturing van de verwarming – luchtverwarmer met variabele ventilatorcapaciteit (uitgang V3 0-10V).  5.**Bijverwarming max. 10,0 V** - Maximale spanning die wordt geleverd voor traploze aansturing van de verwarming – luchtverwarmer met variabele ventilatorcapaciteit (uitgang V3 0-10V).| 
| Programma 	|  **versie 2.4  apr 13 2018** - 	Aflezen van de softwareversie en compilatiedatum|

## Fout- en waarschuwingsmeldingen

Foutmeldingen informeren de gebruiker over onregelmatigheden in de werking van de regelaar. Hieronder staan de mogelijke foutmeldingen

|FOUT                            |	BESCHRIJVING      |
|:-----------                    |:---------- |
|Alarm     Overbelasting 	     |Overbelastingsalarm, geactiveerd bij 75°C. Het apparaat onderbreekt de werking totdat het is afgekoeld.|
|Alarm  Geen sensor|Geeft aan dat de sensor of de aansluitkabel ontbreekt of defect is.|

# Opmerkingen en waarschuwingen 
:::danger 
 Tijdens de installatie van het apparaat moet de elektrische voeding beslist worden uitgeschakeld, omdat de spanning op bepaalde onderdelen gevaarlijk is voor leven en gezondheid. Het wordt aanbevolen de installatie door een gekwalificeerd persoon te laten uitvoeren.

:::
- Om problemen bij het gebruik van het apparaat te voorkomen, moet de handleiding vóór installatie en gebruik worden gelezen.
- Het is niet toegestaan de constructie te wijzigen of zelfstandig reparaties uit te voeren. Dit geldt in het bijzonder voor wijzigingen aan elementen en onderdelen. 
- Onderhouds- en servicewerkzaamheden moeten worden uitgevoerd door bevoegd personeel (installateur of bedrijfsservicedienst). In stallen met geforceerde ventilatie is een alarmsysteem vereist. De fabrikant van het apparaat is niet aansprakelijk voor schade veroorzaakt door onjuiste installatie, onjuiste programmering van functies, gevolgen van onvoorziene gebeurtenissen en externe factoren. 
- De parameters van de ventilatieregelaar moeten worden ingesteld overeenkomstig de omstandigheden in de dierenverblijfsruimte. Deze instellingen zijn individueel en afhankelijk van de beslissing van de veehouder. De fabrikant van het apparaat behoudt zich het recht voor wijzigingen aan te brengen in de constructie van het apparaat en in de software.

:::caution
<div class="warning-container">
  <p>
    <strong></strong> Aan het einde van de gebruiksduur mag het product niet met ongesorteerd huishoudelijk afval worden weggegooid, maar moet het overeenkomstig de geldende voorschriften worden verwerkt (WEEE-richtlijnen van de Europese Unie 2012/19/EU).
Het product is vervaardigd overeenkomstig de RoHS-eisen (richtlijn van de Europese Unie 2011/65/EU).
  </p>
</div>
:::
:::tip

## Technische gegevens van de regelaar
|Parameter                        |	BESCHRIJVING      |
|:-----------                    |:---------- |
|Voedingsspanning|	230VAC 50Hz|
|Maximale stroom van de uitgang voor traploze regeling FAN|	12A|
|Regelbereik van de uitgangsspanning|	70V ÷ 230V|
|Maximale uitgangsstroom (contactstroom) FAN 2|	6A|
|Maximale uitgangsstroom (contactstroom) HOT|	6A|
|Maximale uitgangsstroom (contactstroom) ALARM|	4A|
|Maximale uitgangsstroom (contactstroom) FUNC1 en FUNC2|	4A|
|Bedrijfstemperatuurbereik|	-10 +40oC|
|Temperatuurmeetbereik|	0 +50oC|
|Resolutie van de temperatuurmeting|	0,1oC|
|Detectie van defecten aan de temperatuursensor|	JA|
|Maximaal aantal analoge sensoren|	2|
|Nauwkeurigheid van de temperatuurmeting – analoge ingang|	1oC|
|Afhankelijkheid van de meting van de kabelweerstand – analoge ingang|	15,8Ω/oC|
|Maximaal aantal digitale sensoren|	4|
|Nauwkeurigheid van de temperatuurmeting – digitale ingang|	0,5oC|
|Afhankelijkheid van de meting van de kabelweerstand – digitale ingang|	Geen|
|Maximale lengte van de verbindingslijn tussen digitale sensoren|	150m|
|Bestandheid tegen overspanning (max E)|	210J|
|Overbelastingsbeveiliging|	75oC|
|Afmetingen van het apparaat|	34x29x12 [cm]|
|Beschermingsgraad van de behuizing|	IP56|
:::

:::info
De regelaar SPEED CONTROL-12 v2  wordt geleverd met:
 - 1 temperatuursensor,
 - 4 pluggen,
 - 2 kabelwartels PG13,5.
 - 3 kabelwartels PG11,
 - 4 kabelwartels PG9.
:::















































































