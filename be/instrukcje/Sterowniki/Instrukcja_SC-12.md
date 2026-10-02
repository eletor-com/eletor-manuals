---
sidebar_position: 3
title: Handleiding SC-12
description: Klimaatregelaar voor stalruimten met een toegestane uitgangsstroom tot
  12A
keywords:
- eletor sc-12
- ventilatieregelaar
- klimaatregelaar
- ventilatieregelaar voor varkensstallen
- microklimaatregelaar
- regelaar voor varkensstallen
- ventilatie van varkensstallen
- regelaar voor opfokstallen
---

# Regelaar SC-12

Microprocessorgestuurde klimaatregelaar uit de serie SPEED CONTROL. De veelzijdigheid van het apparaat wordt gewaarborgd door het grote aantal ingangen/uitgangen en de intuïtieve software in het Pools en Engels. Naast de basisinstellingen voor temperaturen, periodieke ventilatie, bijverwarming, min./max. ventilatieniveaus en alarmen maakt het programma van de regelaar het mogelijk om de aangesloten actuatoren te testen en hun kalibratie op te slaan.

**Parameters en kenmerken:** 
- Ventilatie van groep I: 
  - max. stroom van de traploos geregelde uitgang 12A,
  - thermische beveiliging van het systeem, 
  - zachte aanloop van de ventilatie – softstart,
  - overbruggingsrelais bij volledige aansturing, 
  - kalibratie van het minimumtoerental, 
  - energiebesparingsprogramma met een systeem van vooraf geopende kleppen.
- Ventilatie van groep II, potentiaalvrij contact tot 6A.
- Bijverwarming, potentiaalvrij contact tot 6A
- Alarmuitgangen NO en NC: 
  - signalering van voedingsuitval,
  - signalering van overschrijding van de min. of max. temperatuurdrempel,
  - ingebouwde akoestische signaalgever.
- Onafhankelijke 3 uitgangen 0..10V:
  - samenwerking met uitbreidingsmodules,
  - aansturing van het kleppensysteem, 
  - regeling van verwarming met variabele capaciteit.**
- Twee analoge ingangen voor temperatuurmeting.
- Digitale poort voor temperatuurmeting (tot 4 sensoren).
- Twee functionele relaisuitgangen (naar keuze):
  - samenwerking met lineaire actuatoren, 
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
 Tijdens de installatie van het apparaat moet de elektriciteitstoevoer beslist worden uitgeschakeld, omdat de spanning op bepaalde onderdelen levensgevaarlijk is en een gevaar voor de gezondheid vormt. Het wordt aanbevolen de installatie aan een gekwalificeerd persoon toe te vertrouwen.  Deze handeling is gevaarlijk
:::

## Keuze van de montageplaats
De montageplaats moet weloverwogen worden gekozen, zodat het apparaat gemakkelijk toegankelijk is voor bevoegde personen en ontoegankelijk is voor dieren en kinderen. Ook moet rekening worden gehouden met de klimaatomstandigheden, d.w.z. het apparaat moet werken binnen het temperatuurbereik van -10°C tot 40 °C, op een plaats die niet aan zonlicht is blootgesteld. Rondom het apparaat moet de lucht vrij kunnen stromen. Het apparaat omvat een temperatuursensor.  

### Voor de montage van de temperatuursensor gelden enkele regels:
 - de sensor mag niet worden gemonteerd op een plaats zonder luchtcirculatie of met direct zonlicht,
 - de sensor mag niet op een dragende (buiten)muur van het gebouw worden gemonteerd,
 - vermijd de nabijheid van apparaten die warmte afgeven, zoals radiatoren en lampen,
 - de sensor mag niet direct bij deuren en ventilatieopeningen worden geplaatst,
 - de sensor mag niet op voor dieren toegankelijke plaatsen worden geplaatst,
 - het wordt aanbevolen de verbindingskabel van de sensor op afstand van voedingskabels te leggen.

# Montage
Het apparaat kan onder agressieve klimaatomstandigheden werken. Een correct gemonteerde regelaar en temperatuursensor zijn bestand tegen schadelijke omgevingsinvloeden.  

### Tijdens de montage moet op het volgende worden gelet:
 - controleer de afdichting van het deksel voordat het wordt vastgeschroefd,
 - het deksel moet met alle schroeven worden vastgezet,
 - de kabels voor het aansluiten van de regelaar moeten rond zijn,
 - na het aansluiten van de kabel moeten de kabelwartels worden aangedraaid zodat de kabel wordt afgedicht en vastgezet; het gebruik van siliconen wordt aanbevolen,
 - ongebruikte doorvoeren (kabelwartels) moeten worden afgedopt,
 - de regelaar (het onderste deel van de behuizing) wordt met 4 expansiepluggen aan een vlakke wand bevestigd.

# Elektrische aansluiting
:::danger 
 Controleer vóór het aansluiten van het systeem of de voeding is uitgeschakeld!
Deze handeling is gevaarlijk
:::

Voordat de regelaar wordt aangesloten, moet het deksel worden losgeschroefd en verwijderd. Voer de kabels door de rubberen kabelwartels; daarna kunnen ze worden aangesloten. De aansluitklemmen van de regelaar zijn weergegeven in de onderstaande afbeelding.

![Aansluiting ](./img/sc-12.png)

**De AC-aansluiting 230V** wordt aangesloten op de voeding (verdeelkast). Het gebruik van een installatieautomaat 1P-B6 en overspanningsbeveiligingen van het type T1 T2 is vereist. Bij het aansluiten van meerdere apparaten is het een goede werkwijze om de regelaars over verschillende „fasen” (L1, L2, L3) te verdelen, zodat de voedingsleiding gelijkmatig wordt belast.

**De FAN-aansluiting** moet rechtstreeks op de ventilator worden aangesloten; bij aansturing van meerdere ventilatoren mag de totale belasting niet hoger zijn dan 6A, en elke ventilator moet afzonderlijk worden beveiligd. PE en N mogen niet vanaf de voeding (verdeelkast) worden doorgevoerd; ze moeten beslist op de aansluitingen van de regelaar worden aangesloten.

**De FAN-aansluiting 2** kan worden gebruikt om ventilatoren van groep 2 of sproeisystemen aan te sluiten. De uitgang is potentiaalvrij, de maximale contactstroom bedraagt 6A (bij rechtstreekse aansturing van de belasting is een externe installatieautomaat van het type 1P-B6 vereist); het contact sluit wanneer de gemeten temperatuur hoger is dan de som van de ingestelde temperatuur en de ventilatieband.

**De HOT-aansluiting** kan worden gebruikt om een luchtverwarmer aan te sluiten. De uitgang is potentiaalvrij, de maximale contactstroom bedraagt 6A (bij rechtstreekse aansturing van de belasting is een externe installatieautomaat 1P-B6 vereist); het contact sluit wanneer de gemeten temperatuur onder de ingestelde waarde daalt.

**De ALARM-aansluiting** heeft potentiaalvrije uitgangen NC, C en NO voor aansluiting op een alarmcentrale. Het alarm wordt in de volgende gevallen ingeschakeld:
    - de temperatuur is te laag of te hoog,
    - de regelaar of de temperatuursensor is defect,
    - de voedingsspanning van de regelaar is uitgevallen,
    - de regelaar werkt niet correct (bijv. oververhitting van de regelaar)
De onderstaande afbeelding toont hoe de ventilator op de alarmcentrale wordt aangesloten.

![Alarmaansluiting](./img/alarmsc-s.png)

**De aansluitingen FUNC1 en FUNC2** dienen voor het aansluiten van een lier voor het openen van de luchtinlaten, aangedreven door een motor met rechts-/linksdraaiende werking. Relais FUNC1 schakelt de stroom voor de actuator in en FUNC2 schakelt de draairichting van de motor om. Voorbeeld van een aansluitschema voor de lier (een externe installatieautomaat 1P-B6 is vereist):
Wanneer de lierfunctie wordt gedeactiveerd, werken de uitgangen FUNC1 en FUNC2 als contacten voor respectievelijk ventilatiegroep 3 en 4.

![Aansluiting van de lier](./img/Sc-12fan.png)

**De aansluiting 12V** is bestemd voor de voeding van externe sensoren.

**De aansluiting V1 0-10V** dient voor het aansluiten van vermogensuitbreidingsmodules. De spanning op deze klem is evenredig met het ventilatieniveau.

**De aansluiting V2 0-10V** dient voor het aansluiten van de actuator die de luchtinlaatkleppen opent.

**De aansluiting V3 0-10V** dient voor het aansluiten van een verwarmingssysteem met traploos regelbare capaciteit. De spanning op deze uitgang stijgt evenredig met de temperatuurdaling, vanaf de bijverwarmingstemperatuur.

**De aansluiting 10V** dient voor de voeding van de potentiometer van de lier of andere systemen van het type 0-10V.

**De aansluiting SENS1 (SENS2)** wordt verbonden met 1 temperatuursensor TS3 of TS5; de polariteit is niet van belang. Bij gelijktijdige aansluiting van 2 sensoren worden de gemeten temperaturen gemiddeld. Het is een goede werkwijze om de meetkabels op afstand van de voedingskabels te houden.

**De aansluiting 1-WIRE** kan worden gebruikt om een groter aantal digitale temperatuursensoren aan te sluiten, maximaal 4, die parallel worden aangesloten (de juiste polariteit moet worden aangehouden). De maximale lengte van de kabel die de sensoren verbindt bedraagt 150m (de lengte heeft geen invloed op de temperatuurmeting); het gebruik van een afgeschermde kabel wordt aanbevolen.

**De aansluiting RS-485** kan worden gebruikt voor het opbouwen van ventilatiesystemen en voor communicatie met een pc.

**De aansluiting IN1 0-10** dient voor het invoeren van een terugkoppelingssignaal van het luchtinlaatsysteem – dit geeft de actuele positie van de inlaten aan.

**De aansluiting IN2 0-10** dient voor het aansluiten van de regelaar op andere sensoren, bijvoorbeeld voor luchtvochtigheid, CO2 of voor het gebruik van de regelaar als vermogensuitbreiding.

# Werkingsprincipe
De hoofdtaak van de regelaar is het handhaven van de temperatuur in de stalruimte op het door de veehouder ingestelde niveau. Houd er rekening mee dat de regelaar slechts een hulpmiddel is om optimale klimaatomstandigheden in de stalruimte te waarborgen. De veehouder speelt echter de belangrijkste rol in dit proces en moet de instellingen van het apparaat aanpassen aan de veranderende klimaatomstandigheden buiten en vooral aan de behoeften van de dieren in het stalgebouw, en de werking van het apparaat via de alarmcentrale bewaken.

## Eerste inbedrijfstelling van de regelaar
:::danger 
 Bij de eerste inbedrijfstelling van de regelaar moet beslist de verboden bedrijfsband van de motor worden ingesteld.

:::
De regelaar werkt samen met ventilatoren met een eenfasige asynchrone motor met een maximale totale stroomopname van 12A. Na het aansluiten van de gekozen ventilatoren moet de gebruiker deze afstemmen op de samenwerking met de regelaar. Met andere woorden: het minimale bedrijfsniveau (toerental) van de ventilator moet worden ingesteld. Deze functie heet „Verboden band” en wordt door de gebruiker eenmalig ingesteld via „Geavanceerde instellingen”. Om deze handeling correct uit te voeren, is de hulp van een tweede persoon aanbevolen, die het gedrag van de ventilator voortdurend kan observeren terwijl de andere persoon de waarde van de „Verboden band” instelt (de fabriekswaarde bedraagt 0). Als de verboden band niet wordt ingesteld, kan het apparaat onjuist werken. De waarde van de „Verboden band” kan als correct worden beschouwd zodra de door de ventilator opgewekte druk de kleppen van de ventilatiekoker licht begint op te tillen. De „Verboden band” moet opnieuw worden ingesteld wanneer de op de regelaar aangesloten ventilator wordt vervangen.

## Periodieke ventilatie
Periodieke ventilatie is een functie van de regelaar die wordt geactiveerd wanneer de temperatuur in de ruimte onder de ingestelde temperatuur daalt. Deze functie zorgt voor een cyclische toevoer van verse lucht voor de dieren. In het menu Periodieke ventilatie zijn 3 parameters beschikbaar:
- **„Bedrijfstijd”** - bepaalt hoeveel minuten de ventilator moet worden ingeschakeld;
- **„Pauzetijd”** - bepaalt de stilstandtijd van de ventilator;
- **„Niveau periodieke ventilatie”** - bepaalt het ventilatievermogen tijdens de „Bedrijfstijd”.

Alle hierboven genoemde parameters worden door de gebruiker ingesteld. 

### Bij het instellen van de parameters voor periodieke ventilatie moeten enkele regels in acht worden genomen:
- periodieke ventilatie wordt uitsluitend ingeschakeld wanneer de temperatuur in de varkensstal onder de ingestelde temperatuur daalt,
- de hoofdfunctie van periodieke ventilatie is het waarborgen van een cyclische toevoer van verse lucht voor de dieren, niet het handhaven van de ingestelde temperatuur in de ruimte,
- het wordt aanbevolen de ruimten kort maar vaak te ventileren,
- lange perioden van periodieke ventilatie moeten worden vermeden, omdat deze tot te grote temperatuurschommelingen kunnen leiden,
- de ingestelde parameters moeten beslist worden afgestemd op het gedrag van de dieren en de omstandigheden binnen en buiten de ruimte.

## Werking van het apparaat
De regelaar regelt de ventilatie traploos van **„Min.1” tot „Max.1”** binnen het bereik van de **„Ingestelde temperatuur”** tot de som van de **„Ingestelde temperatuur”** en de **„Ventilatieband 1gr.”**. Boven dit bereik wordt ventilatiegroep 2 ingeschakeld en verandert groep 1 het niveau naar **„Min.2”**; bij een verdere temperatuurstijging neemt de ventilatie toe tot **„Max.2”**, aan het einde van het bereik van de **„Ventilatieband 2 gr.”**. Wanneer de **„Ventilatieband 2 gr.”** op nul is ingesteld en de ventilatie op **„Max.1”** werkt, wordt ventilatiegroep 2 ingeschakeld en leidt een verdere temperatuurstijging niet meer tot wijzigingen in de ventilatie (het gestippelde deel van de grafiek). Wanneer de temperatuur in de ruimte onder de **„Ingestelde temperatuur”** daalt, ventileert de regelaar de ruimte periodiek; bij een verdere daling wordt de bijverwarming ingeschakeld. Alles is afhankelijk van de door de gebruiker ingevoerde instellingen. Het programma van de regelaar voorziet ook in samenwerking met een alarmcentrale, die kan worden geactiveerd wanneer de temperatuur in de varkensstal afwijkt van de ingestelde parameters. 

![Ventilatie](./img/Sc-12wentyl.png)  

## Programmering van de regelaar
De regelaar beschikt over een reeks standaardinstellingen die in twee gevallen in het niet-vluchtige geheugen worden geschreven:
1. Eerste inbedrijfstelling van het apparaat,
2. Fout in het gegevensgeheugen.
Bij het ontbreken of uitvallen van de voeding behoudt de regelaar de eerder ingevoerde en opgeslagen gebruikersinstellingen.

## Frontpaneel – indicatoren, toetsen en display
![Paneel](./img/SC-12panel.png)  
    1. Rood controlelampje dat overschrijding van de maximaal toegestane temperatuur aangeeft.
    2. Rood controlelampje dat onderschrijding van de minimaal toegestane temperatuur aangeeft.
    3. Geel controlelampje dat bijverwarming aangeeft.
    4. Geel controlelampje dat ventilatie van groep 2 aangeeft.
    5. Groen controlelampje dat handmatige instelling van het ventilatieniveau aangeeft.
    6. Groen controlelampje dat de werking van de communicatie RS485 aangeeft.
    7. Menudisplay, geeft bij normale werking de temperatuur weer.
    8. Balkindicator die het ventilatieniveau aangeeft.
    9. Toets om omhoog te navigeren in het menu of de parameterwaarde te wijzigen.
    10. ESC-toets - om het menu of de betreffende parameter te verlaten zonder de waarde op te slaan.
    11. OK-toets - om het menu te openen of de betreffende parameter te bevestigen (op te slaan).
    12. Toets om omlaag te navigeren in het menu of de parameterwaarde te wijzigen.

## Gebruik van het menu
De regelaar is uitgerust met een reeks functies waarmee hij aan een specifieke toepassing kan worden aangepast. Deze functies zijn gegroepeerd in een menu dat wordt geopend door op een van de toetsen **(„+”, „-” of „OK”)** te drukken. De toetsen **„+”** en **„-”** dienen om een functie te selecteren; bewerken, gegevens opslaan of een volgend submenu openen kan met de toets **„OK”**. Druk op de toets **„Esc”** om terug te keren naar het bovenliggende menu of het opslaan van de betreffende parameter te annuleren.

## Functies van het basismenu

| MENU                          | Beschrijving       | 
|:-----------                   |:---------- |
| Temperatuur 20,8o C W16% A    | **Informatiemodus** - normale werking. Het display toont de actuele temperatuur en, wanneer de ventilator is ingeschakeld, de waarde van het ventilatieniveau. Betekenis van de aanvullende symbolen:A-betekent alarm ingeschakeld,D  - betekent verwarming ingeschakeld, W - betekent extra ventilatie| 
|   Ingestelde temp.   20,0o C      |**„Ingestelde temperatuur”** – Bepaalt de temperatuur vanaf welke het proces van traploze ventilatie begint. Selecteer een geschikte waarde afhankelijk van het soort vee.| 
| Periodieke ventilatie     | **Periodieke ventilatie** – er worden twee tijdwaarden ingesteld.    1.**Bedrijfstijd** Bepaalt het aantal minuten dat de ventilatie werkt.    2.**Pauzetijd** Bepaalt het aantal minuten dat de ventilatie stilstaat tussen opeenvolgende bedrijfscycli.    3.**Niveau periodieke ventilatie** - Bepaalt de ventilatie-intensiteit tijdens de werking van de periodieke ventilatie.| 
| Alarm |  1.**Alarm actief Ja** - Activering/Deactivering van het alarmcontact; selecteer „NEE” in het menu om te voorkomen dat de regelaar een alarmsignaal op de uitgang (naar de alarmcentrale) afgeeft.  2. **Temp. Min. 15,0o C** - Bepaalt de absolute minimumtemperatuur waarbij het alarm wordt ingeschakeld.  3.**Temp. Max. 25,0o C** - Bepaalt de absolute maximumtemperatuur waarbij het alarm wordt ingeschakeld.  4.**Alarmsignaal Ja** - Activering/Deactivering van het akoestische signaal in de regelaar. | 
|    Ventilatie        |  1.**Ventilatieband 1 5,0o C**   - Bepaalt de reactiesnelheid van de regelaar (wijziging van het ventilatieniveau van minimum 1 tot maximum 1) op een stijgende temperatuur.  2.**Min. niveau 1 1 %** - Bepaalt het ventilatieniveau dat overeenkomt met de ingestelde temperatuur.  3.**Max. niveau 1 100 %**-Bepaalt het constante ventilatieniveau bij een temperatuur boven het bereik van de traploze regeling wanneer „Ventilatieband 2gr.” = 0, anders het maximale niveau van de geregelde ventilatie bij een temperatuur gelijk aan de som van de ingestelde temp. en de band van groep 1.  4.**Ventilatieband 2 0,0o C**-Bepaalt de reactiesnelheid van de regelaar (wijziging van het ventilatieniveau van minimum 2 tot maximum 2) op een stijgende temperatuur voor groep 2. De functie is niet actief wanneer de band gelijk is aan nul.  5.**Min. niveau 2 1 %**-Bepaalt het minimale ventilatieniveau van groep 1 op het moment dat de contacten van groep 2 sluiten.  6.**Max. niveau 2 100 %**-Bepaalt het constante ventilatieniveau bij een temperatuur boven het bereik van de traploze regeling wanneer groep 2 is ingeschakeld.  7.**Groep 3  5,0o C**-Bepaalt het constante ventilatieniveau bij een temperatuur boven het bereik van de traploze regeling wanneer groep 2 is ingeschakeld.  8.**Groep 4 7,0o C**-Bepaalt de temperatuur ten opzichte van de ingestelde temperatuur waarbij ventilatiegroep 4 wordt ingeschakeld (de lierfunctie moet gedeactiveerd zijn).| 
|    Bijverwarming  |  1.**Bijverwarmingstemp. 15,0o C**-Bepaalt de inschakeltemperatuur van de bijverwarming.  2.**Bijverwarmingsband 5,0o C** -Bepaalt de vermogensverhouding van de bijverwarmingssystemen (op uitgang V3 0-10V) afhankelijk van de temperatuur. | 

## Functies van het geavanceerde menu
Het geavanceerde menu is voornamelijk bedoeld voor installateurs en maakt het mogelijk de regelaar op de installatie en ventilator af te stemmen, circuits te testen en de menutaal te kiezen. De geavanceerde instellingen worden geopend door twee menutoetsen gedurende ongeveer 10s ingedrukt te houden. 

| MENU                          | Beschrijving       | 
|:-----------                   |:---------- |
|Testen  |Deze functie dient voor het controleren van de afzonderlijke actuatorcircuits van de regelaar; alle instellingen zijn tijdelijk en gelden zolang de betreffende menuoptie geopend blijft. Na het indrukken van „ESC” of „OK” keert de betreffende uitgang terug naar de toestand die uit de werking van de regelaar volgt.  1.**Ventilatie 0 %**  Maakt handmatige invoer van het ventilatieniveau mogelijk om het ventilatiesysteem te controleren. Na bevestiging van de functie gaat het groene controlelampje (handje) branden.  2.**Alarm Nee** Activering schakelt 2 rode controlelampjes, het geluidssignaal en het alarmcircuit in.  3.**Bijverwarming Nee** Activering schakelt het gele controlelampje (vlammetje) en het bijverwarmingscircuit in.  4.**Vent. 2 trap Nee** Activering schakelt het gele controlelampje (ventilator) en het circuit van groep 2 in.  5.**Uitgang V1 0,0 V  Uitgang V2  0,0 V Uitgang V3  0,0 V**-Test van de uitgangen 0-10V; met de toetsen „+” of „-” kan de gewenste spanning worden ingesteld voor achtereenvolgens: uitbreidingsmodules, luchtinlaatkleppen, traploze bijverwarming. De functie is bijzonder nuttig bij de kalibratie van Uitgang V2 voor de luchtinlaatkleppen.  6.**Lier 0** Maakt controle van het luchtinlaatkleppensysteem mogelijk: „+” - opent de inlaten, „-” - sluit de inlaten; het display toont de actuele positie van de actuator, afgelezen van de potentiometer.  7.**Groep 3 Nee**  Activering schakelt het circuit van ventilatiegroep 3 in. (de lierfunctie moet gedeactiveerd zijn)  8.**Groep 4 Nee**  Activering schakelt het circuit van ventilatiegroep 4 in. (de lierfunctie moet gedeactiveerd zijn)|
|Taal        | Keuze van de menutaal. Er kan worden gekozen tussen Pools en Engels. | 
|Ventilator         |  1.**Verboden band 0**- Kalibratie van het minimumtoerental van de rechtstreeks op de regelaar aangesloten ventilatoren; deze parameter komt overeen met ventilatieniveau „1%”. Een positieve parameterwaarde verhoogt het toerental, een negatieve verlaagt het.  2.**Uitbr. module Min. 1,9 V** -Minimale spanning die aan de vermogensuitbreidingsmodule wordt geleverd (uitgang V1 0-10V).  3.**Uitbr. module Max. 10,0 V** -Maximale spanning die aan de vermogensuitbreidingsmodule wordt geleverd (uitgang V1 0-10V).  4.**Module uitschakelen Nee** - Uitschakeling van de vermogensuitbreidingsmodule; wanneer „JA” is geselecteerd, daalt de spanning op de uitgang voor het aansturen van de uitbreidingsmodules (V1 0-10V) tot niveau 0V in plaats van tot de ingestelde minimumwaarde wanneer het ventilatieniveau 0% bedraagt.  5.**Inversie  Nee**-Activering keert de karakteristiek van uitgang V1 om. De spanning daalt naarmate het ventilatieniveau stijgt binnen het door min.-max. ingestelde bereik. Het signaal op uitgang V1 is van het type 10-0V.| 
| Luchtinlaatkleppen       |  1.**Voorloop 0,0o C**-Eerder openen van de luchtinlaatkleppen. De ingestelde parameter bepaalt hoeveel temperatuurverschil vóór het bereiken van de „Ingestelde temperatuur” de luchtinlaatkleppen moeten openen.  2.**Volledig sluiten  Nee**- Activering zorgt ervoor dat de spanning op de uitgang voor het aansturen van de luchtinlaatkleppen (V2 0-10V) tot niveau 0V daalt in plaats van tot de ingestelde minimumwaarde. Dit geldt wanneer er geen ventilatie is (ventilatieniveau 0%).  3.**Kleppen min.  1,9 V**- Minimale spanning die aan de luchtinlaatkleppen wordt geleverd (uitgang V2 0-10V).  4.**Kleppen max.  10,0 V**- Maximale spanning die aan de luchtinlaatkleppen wordt geleverd (uitgang V2 0-10V).  5.**Inversie   Nee**-Activering keert de karakteristiek van uitgang V2 om. De spanning daalt naarmate het ventilatieniveau stijgt binnen het door min.-max. ingestelde bereik. Het signaal op uitgang V2 is van het type 10-0V. |  
| Temperatuurmeting  |  1.**Kalibratie S1 23,0o C -> 23,5o C**,**Kalibratie S2 23,0o C -> 23,2o C** - Kalibratie voor de analoge ingangen maakt het mogelijk de van de sensoren S1 en S2 afgelezen temperatuur opnieuw te schalen.  2.**Middelingstijd 60 s**- Deze parameter bepaalt de periode waarover de actuele temperatuurmetingen worden gemiddeld. De gemiddelde temperatuurwaarde is een basisparameter voor de functies van de regelaar. Wijzigingen in de toestand van de uitgangen (ventilatie, bijverwarming, kleppen, volgende ventilatiegroepen, alarmen,...) zijn nauw verbonden met deze parameter en kunnen niet vaker plaatsvinden dan de hier ingestelde tijd. | 
| Lier      |  1.**Kalibratie Open 1024 -> 853**,**Kalibratie Dicht 0 -> 324** -Kalibratie van de lier is noodzakelijk voor de correcte werking van het luchtinlaatsysteem. De toets „+” opent de inlaten, de toets „-” sluit de inlaten. Tijdens het openen van de inlaten moet de positieparameter toenemen en tijdens het sluiten afnemen; zo niet, dan moet de aansluiting van de actuator worden gecontroleerd (voeding en potentiometer). Bij de kalibratie van de openstand worden de inlaten maximaal geopend en wordt de positie bevestigd met de toets „OK”. Bij de kalibratie van de gesloten stand worden de inlaten gesloten en wordt de positie bevestigd met de toets „OK”. De toets „ESC” verlaat de functie zonder op te slaan. Het verschil tussen de open en gesloten positie moet min. 100 eenheden bedragen.  2.**Deactivering Nee**-Deactivering maakt de contacten FUNC1 en FUNC2 vrij van de lierbesturing; deze contacten functioneren dan voor ventilatiegroep 3 en 4.| 
| Softstart               | De parameters in deze menugroep regelen de aanloop van de ventilatie. Het inschakelen van de ventilatie in de traploos geregelde groep wordt voorafgegaan door een geleidelijke aanloop tot 100%, een korte werking op 100%  en een daling tot het vereiste ventilatieniveau. Hierdoor ontstaat bij het starten van de ventilatie een luchtstoot die het openen van de vlinderkleppen in de ventilatiekokers vergemakkelijkt.   De waarden worden uitgedrukt in perioden van de voedingsspanning bij 1% ventilatie.  1.**Aanlooptijd 5**- De parameter bepaalt de snelheid waarmee het ventilatietoerental toeneemt van nul tot maximaal – zacht inschakelen van de ventilatoren. De waarde 0 schakelt de zachte aanloop uit.  2.**Tijd 100%   100**- De parameter bepaalt de bedrijfstijd bij het starten op 100% van het ventilatieniveau. Door de aanlooptijd en 100% op 0 in te stellen, wordt de luchtstoot bij het starten van de ventilatie volledig uitgeschakeld.  3.**Uitlooptijd 5**-  De parameter bepaalt de snelheid van de wijzigingen van het ventilatieniveau. | 
|Bijverwarming              |  1.**Contactinversie Nee**-Activering keert de karakteristiek van de HOT-uitgang om. Het contact wordt  geopend naarmate de gemeten temperatuur daalt.  2.**Hysterese  0,5o C** - Bepaalt de temperatuurhysterese voor het bijverwarmingscontact.  3.**Relatieve werking Nee**-Activering maakt relatieve instelling van de bijverwarmingstemperatuur ten opzichte van de ingestelde temperatuur mogelijk. Het basismenu voor bijverwarming verandert; daarin wordt dan het verschil ten opzichte van de ingestelde temperatuur ingevoerd.  4.**Bijverwarming min. 1,9 V** - Minimale spanning voor de traploze aansturing van de verwarming – luchtverwarmer met variabele ventilatorcapaciteit (uitgang V3 0-10V).  5.**Bijverwarming max. 10,0 V** - Maximale spanning voor de traploze aansturing van de verwarming – luchtverwarmer met variabele ventilatorcapaciteit (uitgang V3 0-10V).| 
| Programma 	|  **versie 2.4  apr 13 2018** - 	Uitlezen van de softwareversie en compilatiedatum|

## Fout- en waarschuwingsmeldingen

Foutmeldingen informeren de gebruiker over onregelmatigheden in de werking van de regelaar. Hieronder staan de mogelijke foutmeldingen

|FOUT                            |	BESCHRIJVING      |
|:-----------                    |:---------- |
|Alarm     Overbelasting 	     |Overbelastingsalarm, geactiveerd bij 75°C. Het apparaat onderbreekt de werking totdat het is afgekoeld.|
|Alarm  Geen sensor|Geeft aan dat de sensor of de verbindingskabel ontbreekt of defect is.|

# Opmerkingen en waarschuwingen 
:::danger 
 Tijdens de installatie van het apparaat moet de elektriciteitstoevoer beslist worden uitgeschakeld, omdat de spanning op bepaalde onderdelen levensgevaarlijk is en een gevaar voor de gezondheid vormt. Het wordt aanbevolen de installatie aan een gekwalificeerd persoon toe te vertrouwen.

:::
- Om problemen bij het gebruik van het apparaat te voorkomen, moet de handleiding vóór installatie en gebruik worden gelezen.
- Het is niet toegestaan de constructie te wijzigen of zelfstandig reparaties uit te voeren. Dit geldt met name voor wijzigingen aan elementen en onderdelen. 
- Onderhouds- en servicewerkzaamheden moeten door bevoegd personeel worden uitgevoerd (installateur of servicedienst van de fabrikant). In stalgebouwen met geforceerde ventilatie is een alarmsysteem vereist. De fabrikant van het apparaat is niet aansprakelijk voor schade veroorzaakt door onjuiste installatie, onjuiste programmering van functies, gevolgen van onvoorziene gebeurtenissen en externe factoren. 
- De parameters van de ventilatieregelaar moeten worden ingesteld overeenkomstig de omstandigheden in de stalruimte. Deze instellingen zijn individueel en afhankelijk van de beslissing van de veehouder. De fabrikant van het apparaat behoudt zich het recht voor wijzigingen aan te brengen in de constructie van het apparaat en de software.

:::caution
<div class="warning-container">
  <p>
    <strong></strong> Na afloop van de gebruiksduur mag het product niet samen met ongesorteerd huishoudelijk afval worden weggegooid, maar moet het worden afgevoerd overeenkomstig de geldende voorschriften (WEEE-richtlijnen van de Europese Unie 2012/19/EU).
Het product is vervaardigd overeenkomstig de RoHS-eisen (richtlijn van de Europese Unie 2011/65/EU).
  </p>
</div>
:::
:::tip

## Technische gegevens van de regelaar
|Parameter                        |	BESCHRIJVING      |
|:-----------                    |:---------- |
|Voedingsspanning|	230VAC 50Hz|
|Maximale stroom van de traploos geregelde uitgang FAN|	12A|
|Regelbereik van de uitgangsspanning|	70V ÷ 230V|
|Maximale stroom van uitgang (contact) FAN 2|	6A|
|Maximale stroom van uitgang (contact) HOT|	6A|
|Maximale stroom van uitgang (contact) ALARM|	4A|
|Maximale stroom van uitgang (contact) FUNC1 en FUNC2|	4A|
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
|Maximale lengte van de verbindingsleiding van de digitale sensoren|	150m|
|Bestandheid tegen overspanning (max E)|	210J|
|Overbelastingsbeveiliging|	75oC|
|Afmetingen van het apparaat|	34x29x12 [cm]|
|Beschermingsgraad van de behuizing|	IP56|
:::

:::info
De regelaar SPEED CONTROL-12 v2  wordt geleverd met:
 - 1 temperatuursensor,
 - 4 expansiepluggen,
 - 2 kabelwartels PG13,5.
 - 3 kabelwartels PG11,
 - 4 kabelwartels PG9.
:::















































































