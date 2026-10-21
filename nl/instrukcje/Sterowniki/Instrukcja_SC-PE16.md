---
id: sc-pe16
title: SC-PE16 — gebruiksaanwijzing
sidebar_label: SC-PE16
sidebar_position: 5
description: Handleiding voor de vermogensuitbreiding SC-PE16 — montage, aansluiting,
  inbedrijfstelling, menu en beveiligingen.
slug: /sc-pe16
toc_min_heading_level: 2
toc_max_heading_level: 3
---


De vermogensuitbreiding SC-PE16 dient voor de aansturing van ventilatoren wanneer de belasting de capaciteit van de hoofdregelaar overschrijdt. Het apparaat regelt de voedingsspanning van de ventilatoren op basis van een analoog signaal of een handmatige instelling. De maximale totale uitgangsstroom bedraagt 16 A.

![Vermogensuitbreiding ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Parameters en kenmerken

- modi AUTO en MANUAL en slaapstand van het apparaat;
- grafisch display en aanraaktoetsenbord;
- analoge aansturing 2–10 V of 4–20 mA;
- programmeerbare inschakeldrempel van ventilatiegroep 2;
- byPASS bij een constant niveau van 100%;
- thermische beveiliging van de vermogenstrap;
- safeRUN: instelbaar niveau voor noodbedrijf;
- kalibratie van het minimale ventilatieniveau;
- test van ventilatie, relais en alarm;
- toetsenbordvergrendeling en reinigingsvergrendeling;
- Pools, Engels of Oekraïens;
- voeding 230 V AC, 50 Hz; behuizing IP65.

:::info Softwareversie

De functiebeschrijving heeft betrekking op de meegeleverde software **versie 2.1**. De beschikbaarheid van functies moet worden beoordeeld op basis van de in het apparaat geïnstalleerde versie.

:::

## Installatie van de regelaar

:::danger Schakel de voeding uit

Tijdens de installatie van het apparaat moet de stroomtoevoer beslist worden onderbroken, omdat de spanning op sommige onderdelen gevaarlijk is voor leven en gezondheid. Het wordt aanbevolen de installatie door een gekwalificeerd persoon te laten uitvoeren.

:::

### Keuze van de montagelocatie

Het apparaat moet worden gemonteerd op een voor het bedieningspersoneel toegankelijke plaats, buiten het bereik van kinderen en dieren en zonder direct zonlicht. Het omgevingstemperatuurbereik bedraagt −10°C tot +40°C. Zorg voor een vrije luchtstroom rondom de behuizing en het koellichaam. Dek het koellichaam niet af en monteer het apparaat niet in de buurt van warmtebronnen.

### Montage

Bevestig het onderste deel van de behuizing met vier pluggen op een vlakke wand, via de montagegaten buiten het afgedichte compartiment. Monteer het deksel met het meegeleverde scharnier. Controleer vóór het sluiten de toestand en de positie van de afdichting.

Gebruik kabels met een ronde buitenomtrek die passen bij de kabelwartels. Draai de kabelwartels zodanig vast dat ze de kabel afdichten en vastzetten. Sluit ongebruikte doorvoeren af. Draai het deksel met alle schroeven vast. De dichtheid is afhankelijk van de correcte montage van de behuizing en de doorvoeren.

### Voorbereiding van de aansluitingen

Voer alle werkzaamheden binnen de behuizing uit nadat de voeding is uitgeschakeld en de spanningsloosheid is gecontroleerd. Als de lintkabel moet worden losgekoppeld om het paneel te verwijderen, koppel deze dan voorzichtig los en sluit deze weer goed aan voordat de behuizing wordt gesloten. Sluit de lintkabel niet aan en koppel deze niet los terwijl de voeding is ingeschakeld.

Leg de signaalkabels INPUT en ENABLE gescheiden van de voedings- en uitgangskabels. Volg de klemmarkeringen op het betreffende exemplaar van het apparaat. De massa van de signaalingangen en de beschermingsaardklem PE hebben verschillende functies en zijn niet onderling uitwisselbaar.

## Elektrische aansluiting

:::danger Schakel de voeding uit

Controleer vóór het aansluiten van het systeem of de voeding is uitgeschakeld!

:::

![Klemmen voor voeding, ventilatoren, GR 2, ENABLE, CAN en INPUT](./img/sc-pe16/zaciski.png)

| KLEM | FUNCTIE |
| --- | --- |
| L, N, PE — voeding | Voeding 230 V AC, 50 Hz: L — fase, N — nulleider, PE — beschermingsleiding. In de oorspronkelijke documentatie is een beveiliging B20 vermeld; bij de keuze van beveiligingen en kabels moet rekening worden gehouden met de installatie en de belasting. |
| U, N, PE — ventilatoren | U — geregelde fase-uitgang; N en PE — de bijbehorende gemeenschappelijke klemmen van het apparaat. De som van de ventilatorstromen mag 16 A niet overschrijden. Elke ventilator vereist een afzonderlijke beveiliging. Gebruik motoren die zijn goedgekeurd voor spanningsregeling. |
| GR 2: C, NO | Galvanisch gescheiden relaiscontact van groep 2. Schakelt in wanneer het ingestelde ventilatieniveau gelijk is aan of hoger is dan de drempel „Ventilatiegroep 2”. Maximale contactstroom volgens de meegeleverde handleiding: 6 A. Bij directe aansturing van een belasting vermeldt de documentatie een externe beveiliging B6. |
| INPUT: V, massa | Spanningsingang. Selecteer „Type aansturing → Ingang V”. In het geanalyseerde programma bedraagt het regelbereik 2–10 V. Sluit geen netspanning of geregelde voedingsuitgang van de ventilatoren op deze ingang aan. |
| INPUT: I, massa | Stroomingang 4–20 mA. Selecteer „Type aansturing → Ingang I”. Sluit het signaal aan volgens de markeringen van de bron en de ontvanger. |

Gebruik voor de aansturing de geselecteerde ingang V of I. SC-PE16 vereist een eigen netvoeding; de analoge ingang draagt uitsluitend de stuurwaarde over.

## ENABLE-ingang en communicatie

### ENABLE: E en massa

De ingang werkt met een potentiaalvrij contact. De klemmen E en massa mogen uitsluitend worden kortgesloten of onderbroken; leg geen externe spanning aan. Kortsluiting geeft vrijgave voor bedrijf, onderbreking stelt het niveau 0% in. Het stoppen is afhankelijk van de instelling „Uitlooptijd”.

De ENABLE-functie wordt afzonderlijk ingeschakeld voor AUTO en MANUAL in het menu „Geavanceerd → Ventilator”. Beide functies zijn af fabriek uitgeschakeld, zodat er in dat geval geen jumper nodig is. Het onderbreken van ENABLE is niet hetzelfde als de slaapstand: het paneel blijft actief. In AUTO slaat het programma bij een actieve ENABLE-blokkering het uitlezen van het stuursignaal over en wordt safeRUN niet geactiveerd.

### CAN en Wi-Fi

De opties „Ingang CAN” en „Ingang WiFi” zijn in het menu aanwezig, maar voeren in softwareversie 2.1 geen aansturing uit: beide functies leveren niveau 0%. Selecteer ingang V of I om het apparaat met dit programma in bedrijf te stellen. Configureer de installatie niet op basis van CAN of Wi-Fi zonder bevestiging dat de geïnstalleerde softwareversie deze ondersteunt.

## Werkingsprincipe

SC-PE16 is een vermogensregelaar die de opdrachten van de hoofdregelaar of de bediener uitvoert. Het apparaat meet de ruimtetemperatuur niet en heeft geen eigen instellingen voor temperatuur, doorspoelventilatie, bijverwarming of luchtinlaatkleppen. Het procentuele ventilatieniveau is een stuurwaarde en geen meting van het werkelijke motortoerental.

| NOMINAAL SIGNAAL | INGESTELD VENTILATIENIVEAU |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

Tussen de grenswaarden bepaalt het programma het niveau lineair en rondt dit af op hele procenten. Voor ingang V begint de stijging zodra de afgelezen waarde 2,04 V wordt overschreden, en voor ingang I bij 4,04 mA. De uiteindelijke toestand van de uitgang is ook afhankelijk van ENABLE, de aanloop en de thermische beveiliging.

## Noodbedrijf en beveiligingen

### safeRUN — uitval van het ingangssignaal

In modus AUTO verschijnt het alarm „Ingang” bij een afgelezen spanning onder 1,50 V of een stroom onder 2,00 mA, afhankelijk van de geselecteerde ingang. Het programma stelt dan het niveau „Noodbedrijf” in binnen het bereik 0–100%; fabrieksinstelling 30%. Zodra het signaal terugkeert naar de detectiedrempel of daarboven, verdwijnt het ingangsalarm en keert het apparaat terug naar analoge aansturing.

Het bereik 1,50–2,04 V en 2,00–4,04 mA resulteert in niveau 0% zonder ingangsalarm. Het signaal 0 V is in deze versie geen normale stopopdracht — het activeert noodbedrijf. Een hoofdregelaar met een uitgang 0–10 V moet worden geconfigureerd voor het bereik 2–10 V zonder afschakeling naar 0 V. In MANUAL stuurt het analoge signaal de ventilatie niet aan en wordt het ingangsalarm gewist.

### Thermische beveiliging

Het alarm „Oververhitting” wordt geactiveerd wanneer de afgelezen temperatuur van het koellichaam 87°C overschrijdt. Het wordt gewist zodra de temperatuur onder 80°C daalt. Tijdens het alarm wijzigt het programma het ingestelde niveau: voor waarden van ten minste 50% wordt 100% ingesteld, en voor waarden onder 50% wordt 0% ingesteld. De wijziging van de uitgang volgt het aanloop- en uitloopalgoritme. De beveiliging garandeert niet in alle gevallen een continue werking van de ventilatie.

De toestand van relais GR 2 wordt vóór de thermische correctie bepaald: deze is afhankelijk van het niveau vóór het geforceerd instellen van 0% of 100%. Het noodbedrijfsniveau is eveneens onderhevig aan thermische correctie. Controleer bij oververhitting de koelomstandigheden, vervuiling van het koellichaam en de belasting; laat werkzaamheden binnen de behuizing uitvoeren door een bevoegd persoon.

### byPASS en zachte aanloop

Bij een constant uitgangsniveau van 100% schakelt het programma het overbruggingsrelais van de faseaansnijdingsregeling in. De aanloop kan bestaan uit een stijging tot 100%, vasthouden op 100% en de overgang naar het ingestelde niveau. De parameters „Zachte aanloop” beïnvloeden ook de reactiesnelheid van de uitgang op een wijziging van de gewenste waarde.

## Eerste inbedrijfstelling van de regelaar

:::warning Kalibratie van de ventilatoren

Let op! Bij de eerste inbedrijfstelling van het apparaat moet het verboden werkingsbereik van de motor beslist worden ingesteld.

:::

1. Controleer bij uitgeschakelde voeding de aansluiting van de voeding, PE, ventilatoren en het analoge signaal. Controleer of de motoren zijn goedgekeurd voor spanningsregeling en of de totale stroom maximaal 16 A bedraagt.
2. Schakel de voeding in. Als een taalkeuze wordt aangeboden, druk dan op OK en selecteer de taal. Ontgrendel het toetsenbord met de toets met het hangslotsymbool.
3. Selecteer bij „Type aansturing” de optie „Ingang V” of „Ingang I”. Stel het niveau „Noodbedrijf” en de drempel „Ventilatiegroep 2” in. Activeer ENABLE indien nodig afzonderlijk voor de betreffende modus.
4. Ga naar „Geavanceerd → Ventilator → Verboden bereik”. In deze optie forceert het programma niveau 1% en heeft een wijziging van de parameter onmiddellijk invloed op de uitgang. Het bereik bedraagt −20 tot 200, fabrieksinstelling 0. Een positieve waarde verhoogt het minimale aansturingsniveau, een negatieve waarde verlaagt het.
5. Kies de waarde zodanig dat alle ventilatoren stabiel draaien, zonder stil te vallen of overmatig warm te worden. Observeer elke ventilator, bij voorkeur met hulp van een tweede persoon. Alleen het omhoogkomen van de klep vervangt niet de controle van de correcte motorwerking. Bevestig met OK; ESC herstelt de vorige instelling.
6. Controleer de uitgang op verschillende niveaus, waaronder 0%, een laag niveau en 100%. Herhaal de kalibratie na vervanging van ventilatoren of wijziging van hun configuratie.
7. Controleer in AUTO de reactie op het minimale en maximale signaal. Controleer vervolgens de signaalonderbreking en de overgang naar noodbedrijf, evenals de terugkeer nadat het signaal is hersteld. Als ENABLE actief is, controleer dan ook de werking ervan.
8. Controleer GR 2 en de alarmsignalering in het menu „Testen”. Verlaat deze optie na afloop van de tests en selecteer de beoogde bedrijfsmodus.

:::warning Werkelijke activering van de uitgangen

Testen en kalibratie sturen de werkelijke uitgangen aan. Ze kunnen de ventilatoren inschakelen en de ventilatietest forceert een niveau onafhankelijk van de normale aansturing. Zorg voor veilige testomstandigheden en permanent toezicht.

:::

## Programmering van de regelaar

### Voorpaneel — indicatoren en toetsen

| ELEMENT | BEDIENING |
| --- | --- |
| Voeding / slaapstand | De toets met het voedingssymbool toont een bevestiging voor de slaapstand; bevestig met OK. Door opnieuw te drukken wordt het apparaat uit de slaapstand gehaald. De slaapstand stelt de uitgangen in op de uitgeschakelde toestand; de netspanning wordt niet onderbroken. |
| Hangslot | Schakelt de toetsenbordvergrendeling in of uit. Na ontgrendeling brandt het controlelampje bij het hangslot. Op het hoofdscherm wordt de vergrendeling na ongeveer 30 s inactiviteit opnieuw geactiveerd. |
| A — AUTO | Selecteert aansturing via de analoge ingang na bevestiging met OK. Controlelampje A geeft de geselecteerde modus aan. |
| M — MANUAL | Selecteert handmatige aansturing na bevestiging met OK. Op het hoofdscherm wijzigen de toetsen + en − de instelling 0–100%. Controlelampje M geeft de geselecteerde modus aan. |
| +, −, OK, ESC | OK opent het menu, opent een optie en bevestigt een waarde. + en − selecteren een optie of wijzigen een waarde. ESC keert terug naar het vorige niveau of annuleert de bewerking. |
| Alarm en groep 2 | Het rode controlelampje geeft een alarm aan. Het controlelampje bij het ventilatorsymbool „2” geeft aan dat relais GR 2 is ingeschakeld. |
| Display | Toont in AUTO het ingestelde ventilatieniveau, de afgelezen waarde van de geselecteerde ingang, een staafdiagram en alarmen. Wanneer ENABLE actief is, wordt ook de toestand ervan weergegeven. In MANUAL geeft de hoofdwaarde de handmatige instelling aan; de beveiligingen kunnen de uitgang wijzigen. |

### Opslaan van instellingen

De menuparameters worden na bevestiging met OK opgeslagen in het niet-vluchtige geheugen. Wijzigingen van niveau MANUAL zijn onmiddellijk van kracht en worden na korte inactiviteit opgeslagen. Na een stroomuitval worden de opgeslagen instellingen hersteld, waaronder modus AUTO/MANUAL, het handmatige niveau en de slaapstand. Schakel de voeding niet onmiddellijk uit na wijziging van de handmatige instelling.

Bij een onjuiste controlesom of een waarde buiten het bereik herstelt het programma de fabriekswaarden. Controleer in dat geval alle instellingen opnieuw, met name de ventilatorkalibratie, de stuuringang en het noodbedrijf.

## Functies van het basismenu

| MENU | BEREIK / FABRIEKSINSTELLING | BESCHRIJVING |
| --- | --- | --- |
| Type aansturing | Ingang V | Keuze uit V, I, CAN of Wi-Fi. Gebruik voor de geanalyseerde versie V (2–10 V) of I (4–20 mA). CAN en Wi-Fi voeren geen aansturing uit. |
| Ventilatiegroep 2 | 1–100% / 100% | Inschakeldrempel van contact GR 2. Het contact is ingeschakeld bij een niveau gelijk aan of hoger dan de drempel en uitgeschakeld onder de drempel. Het programma definieert geen afzonderlijke hysterese. |
| Noodbedrijf | 0–100% / 30% | Niveau dat wordt ingesteld bij uitval van het geselecteerde analoge signaal in AUTO. De waarde 0% betekent stoppen bij signaalverlies. |
| Reinigingsvergrendeling | 60 s | Blokkeert de toetsbediening gedurende 60 seconden en toont een aftelling. De ventilatieregeling blijft werken. Deze functie dient voor het afvegen van het paneel, niet voor elektrische werkzaamheden of het reinigen van het binnenwerk. |
| Geavanceerd | Submenu | Toegang tot tests, taal, ventilatorkalibratie, ENABLE, Zachte aanloop, alarmgeluid, fabrieksinstellingen en programma-informatie. |

## Functies van het geavanceerde menu

| MENU / PARAMETER | BEREIK / FABRIEKSINSTELLING | BESCHRIJVING |
| --- | --- | --- |
| Testen → Ventilatie | 0–100% | Tijdelijk forceren van de geregelde uitgang. Wijzigingen zijn tijdens het bewerken van kracht. Na afsluiten met OK of ESC wordt de normale aansturing hervat. |
| Testen → Vent. trap 2 | Nee / Ja | Tijdelijk forceren van contact GR 2 en het bijbehorende controlelampje. |
| Testen → Alarm | Nee / Ja | Tijdelijke test van de alarmsignalering, inclusief geluid, onafhankelijk van de normale instelling „Alarmsignaal”. |
| Taal | Pools | Keuze uit Pools, Engels en Oekraïens. |
| Ventilator → Verboden bereik | −20–200 / 0 | Kalibratie van niveau 1%. Tijdens het bewerken wordt de werkelijke uitgang 1% geforceerd. De parameter wordt niet uitgedrukt in procenten of seconden. |
| Ventilator → Activering EN AUTO | Nee / Ja; Nee | Maakt modus AUTO afhankelijk van de ENABLE-ingang. |
| Ventilator → Activering EN MANUAL | Nee / Ja; Nee | Maakt modus MANUAL afhankelijk van de ENABLE-ingang. |
| Zachte aanloop → Aanlooptijd | 0–50 / 5 | Stijgsnelheid van het niveau tijdens de aanloop tot 100%. Een hogere waarde betekent een tragere wijziging. De waarde 0 slaat de stijgfase over. |
| Zachte aanloop → Tijd 100% | 0–250 / 100 | Vasthouden van niveau 100% tijdens de aanloop. De waarde 0 slaat de vasthoudfase over. Door zowel de aanloop als het vasthouden op 0 in te stellen, wordt het doorblazen tot 100% overgeslagen. |
| Zachte aanloop → Uitlooptijd | 0–50 / 5 | Snelheid waarmee het gewenste niveau wordt bereikt, ook bij wijziging ervan. De waarde 0 betekent een wijziging zonder geleidelijke overgang. |
| Alarmsignaal | Nee / Ja; Nee | Schakelt het akoestische alarmsignaal in. De instelling Nee verwijdert de melding op het scherm en de signalering met het controlelampje niet. |
| Fabrieksinstellingen | Nee / Ja | Na selectie van Ja worden de standaardwaarden hersteld en opgeslagen, waaronder kalibratie 0, ingang V, AUTO, noodbedrijf 30%, drempel GR 2 gelijk aan 100% en uitgeschakelde ENABLE. Configureer en controleer het apparaat daarna opnieuw. |
| Programma | versie 2.1 + compilatiedatum | Toont de versie en compilatiedatum van het programma. Deze beschrijving is opgesteld op basis van de meegeleverde bronbestanden SC_PX16_v02. |

De parameters van Zachte aanloop zijn dimensieloze instellingen van programmatellers en geen tijden in seconden. Bij 50 Hz komt één stap ongeveer overeen met (instelling + 1) × 20 ms: voor aanloop en uitloop is dit de tijd voor een wijziging met 1 procentpunt, voor „Tijd 100%” de vasthoudtijd. De waarde 0 heeft de in de tabel beschreven betekenis. De werkelijke tijden zijn afhankelijk van de fase van het algoritme.

## Foutmeldingen en waarschuwingen

| MELDING | BETEKENIS EN TE NEMEN MAATREGELEN |
| --- | --- |
| Ingang | Te lage afgelezen waarde van het geselecteerde signaal in AUTO. Het apparaat stelt noodbedrijf in. Controleer de signaalbron, kabels, gemeenschappelijke massa en de selectie V/I. |
| Oververhitting | Afgelezen temperatuur van het koellichaam &gt;87°C; wissen bij &lt;80°C. De ventilatie wordt ingesteld op 0% of 100%, volgens de beschrijving van de thermische beveiliging. Controleer de koeling en de belasting. |
| Voeding | Verstoring van de synchronisatie van de vermogenstrap met het net. Controleer de voeding en de installatie. Bij volledige stroomuitval werkt het display niet. |
| Geheugen CRC | Fout in de controlesom of het bereik van de opgeslagen instellingen. Het programma herstelt de standaardwaarden. Controleer de configuratie en herhaal de kalibratie; neem bij een herhaalde fout contact op met de servicedienst. |

## Opmerkingen en waarschuwingen

:::danger Schakel de voeding uit

Tijdens de installatie van het apparaat moet de stroomtoevoer beslist worden onderbroken, omdat de spanning op sommige onderdelen gevaarlijk is voor leven en gezondheid. Het wordt aanbevolen de installatie door een gekwalificeerd persoon te laten uitvoeren.

:::

Lees de handleiding vóór installatie en gebruik. Laat reparaties en werkzaamheden binnen het apparaat uitvoeren door bevoegd personeel. De slaapstand, toetsenbordvergrendeling, ENABLE en instelling 0% onderbreken de voeding niet en waarborgen geen veilige omstandigheden voor elektrische werkzaamheden.

Stem de instellingen voor ventilatie en noodbedrijf af op de behoeften van de dieren en de installatie. Controleer regelmatig de werkelijke werking van alle ventilatoren. Signalering SC-PE16 vervangt geen onafhankelijke bewaking van de omstandigheden in het gebouw en van stroomuitval. Op de afgebeelde klemmenstrook is geen afzonderlijk ALARM-contact voor een alarmcentrale aanwezig.

:::note Afvoer van het apparaat

Na beëindiging van het gebruik mag het product niet bij het ongesorteerde huishoudelijke afval worden weggegooid, maar moet het volgens de geldende voorschriften worden afgevoerd (WEEE-richtlijnen van de Europese Unie 2012/19/EU).

:::

Het product is vervaardigd in overeenstemming met de RoHS-vereisten (richtlijn van de Europese Unie 2011/65/EU).

## Technische gegevens van de regelaar

| PARAMETER | WAARDE |
| --- | --- |
| Voeding / eigen verbruik | 230 V AC, 50 Hz / &lt;10 W |
| Maximale totale stroom van uitgang U | 16 A |
| Maximale contactstroom GR 2 | 6 A; contact C–NO, galvanisch gescheiden |
| Ingang V / ingang I | 2–10 V / 4–20 mA, selecteerbaar in het menu |
| Drempel voor signaaluitval (door het programma afgelezen waarde) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Potentiaalvrij contact E–massa; afzonderlijke activering voor AUTO/MANUAL |
| Thermische beveiliging (afgelezen temperatuur van het koellichaam) | Alarm &gt;87°C; herstel &lt;80°C |
| Omgevingstemperatuur / behuizing | −10°C tot +40°C / IP65 |
| Afmetingen / overspanningsbestendigheid | 34 × 29 × 12 cm / 210 J |
| Menutalen | Pools, Engels, Oekraïens |

Inhoud van de set volgens de meegeleverde documentatie: 4 spreidpluggen, 2 kabelwartels PG13,5, 1 kabelwartel PG9 en 1 scharnier.

## Garantievoorwaarden

De inhoud van de garantievoorwaarden is overgenomen uit het meegeleverde document van de fabrikant.

1. De fabrikant ELETOR, gevestigd in Polen, adres: Pod Sosno 28, 87-305 Zbiczno (hierna de garantieverstrekker genoemd), verleent de Koper een kwaliteitsgarantie voor het product waarvoor dit garantiebewijs is afgegeven, op voorwaarde dat het wordt gebruikt overeenkomstig de bestemming en de voorschriften in de gebruiksaanwijzing die samen met dit product aan de Koper is verstrekt.
2. De garantieperiode bedraagt 24 maanden vanaf de verkoopdatum. Storingen of gebreken van het product die binnen deze periode aan het licht komen, worden kosteloos verholpen. Na afloop van de garantieperiode of bij verlies van de garantierechten worden storingen of gebreken tegen betaling verholpen.
3. De garantie dekt niet:

   - gebreken die zijn ontstaan door onjuist gebruik van het product (waaronder het uitvoeren van handelingen die niet in de gebruiksaanwijzing zijn beschreven, enz.);

   - defecten die zijn ontstaan als gevolg van reparaties, wijzigingen enz. uitgevoerd door een andere persoon dan de garantieverstrekker;

   - gebreken of schade als gevolg van transport of het laten vallen van het product, indien deze gebeurtenissen na aankoop van het product hebben plaatsgevonden, en mechanische schade als gevolg van onjuiste bediening door de gebruiker;

   - gebreken of schade als gevolg van brand, aardbevingen, overstromingen, blikseminslag of andere natuurrampen, milieuverontreiniging, de inwerking van externe ioniserende straling of een magnetisch veld en onregelmatige stroomtoevoer of stroom met parameters die niet aan de vereisten voldoen;

   - gebreken als gevolg van onjuiste opslag (bijv. opslag van het product buiten het in de specificatie vermelde temperatuur- of vochtigheidsbereik, in de buurt van chemicaliën), onjuist onderhoud of onjuiste reiniging enz.;

   - gebreken als gevolg van lege voedingsbatterijen enz.;

   - gebreken veroorzaakt door zand, modder, stof, water en andere vloeistoffen enz. die in de behuizing van het product zijn binnengedrongen;

   - schade als gevolg van natuurlijke, gedeeltelijke of volledige slijtage van het product overeenkomstig de eigenschappen of de bestemming van het product;

   - handelingen die in de gebruiksaanwijzing zijn vermeld en die de gebruiker zelf moet uitvoeren.

4. De Koper verliest de garantierechten als gevolg van:

   - het uitvoeren van reparaties of wijzigingen aan het product door een andere persoon dan de garantieverstrekker;

   - de vaststelling dat een van de verzegelingen is aangetast, beschadigd of verbroken;

   - de vaststelling dat serienummers of andere identificatiemarkeringen van het product zijn beschadigd, aangetast, afgedekt of verwijderd.

5. De reparatietermijn bedraagt maximaal 21 werkdagen vanaf de datum waarop het gebrek is gemeld en het complete product bij het servicepunt van de garantieverstrekker is afgeleverd. In bijzonder gerechtvaardigde gevallen, in verband met de noodzaak onderdelen of componenten uit het buitenland te betrekken of met bijzonder complexe of moeilijk te repareren of te diagnosticeren schade, kan de reparatietermijn worden verlengd met de periode die nodig is om aan de garantieverplichtingen te voldoen.
6. De Koper kan zijn garantierechten uitsluitend uitoefenen na overlegging van een geldig en op de aankoopdatum correct ingevuld garantiebewijs en een aankoopbewijs (factuur, kassabon enz.). Eigenmachtige wijzigingen van de vermeldingen op het garantiebewijs (waaronder doorhalingen, uitwissingen, toevoegingen enz.) leiden tot verlies van de garantierechten. Een garantiebewijs zonder productnaam, model, serienummer van het product, aankoopdatum en -plaats en een leesbare stempel en handtekening van de Verkoper is ongeldig en vormt geen grondslag voor een geldige garantieclaim.
7. De Koper is verplicht het product op eigen kosten aan te leveren in een voor de betreffende apparatuur geschikte verpakking die veilig en correct transport en opslag waarborgt, of de voorrijkosten van de garantieverstrekker te vergoeden. Indien wordt vastgesteld dat het ter reparatie aangeboden product technisch in orde en vrij van gebreken is, of dat de vastgestelde storing niet onder de garantie valt, worden de kosten van diensten en transport aan de Koper in rekening gebracht.
8. De Koper is verplicht het gerepareerde product binnen 90 dagen na de kennisgeving van de reparatie door de garantieverstrekker op te halen. Indien de koper het product niet binnen deze termijn ophaalt, draagt hij het risico van onopzettelijk verlies of beschadiging van het product.
9. De garantieperiode wordt verlengd met de duur van de reparatie, gerekend vanaf de datum van aflevering van het product tot de afgesproken ophaaldatum na de reparatie. De garantieverstrekker is verplicht een document af te geven waarin de periode en de omvang van de verholpen gebreken van het product worden vermeld.

10. De Koper dient claims in via de Verkoper van het product of rechtstreeks op het adres van de garantieverstrekker: ELETOR, Pod Sosno 28, 87-305 Zbiczno, Polen.

11. De garantieverstrekker is niet aansprakelijk:

    - voor gederfde inkomsten als gevolg van het aan het licht komen van een gebrek en de tijd die nodig is om dit te verhelpen;

    - voor verliezen als gevolg van het aan het licht komen van een gebrek en voor alle schade als gevolg van onjuiste installatie, onjuist gebruik of onjuiste programmering van de functies van het apparaat.
