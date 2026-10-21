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


De vermogensuitbreiding SC-PE16 dient voor het aansturen van ventilatoren wanneer de belasting de capaciteit van de bovenliggende regelaar overschrijdt. Het apparaat regelt de voedingsspanning van de ventilatoren op basis van een analoog signaal of een handmatige instelling. De maximale totale uitgangsstroom bedraagt 16 A.

![Vermogensuitbreiding ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Parameters en kenmerken

- modi AUTO en MANUAL en slaapstand van het apparaat;
- grafisch display en aanraaktoetsenbord;
- analoge aansturing 2–10 V of 4–20 mA;
- programmeerbare inschakeldrempel voor ventilatiegroep 2;
- byPASS bij een stabiel niveau van 100%;
- thermische beveiliging van de vermogensschakeling;
- safeRUN: instelbaar niveau voor noodbedrijf;
- kalibratie van het minimale ventilatieniveau;
- test van ventilatie, relais en alarm;
- toetsenbordvergrendeling en reinigingsvergrendeling;
- Poolse, Engelse of Oekraïense taal;
- voeding 230 V AC, 50 Hz; behuizing IP65.

:::info Softwareversie

De functiebeschrijving heeft betrekking op de meegeleverde software **versie 2.1**. De beschikbaarheid van functies moet worden beoordeeld aan de hand van de op het apparaat geïnstalleerde versie.

:::

## Installatie van de regelaar

:::danger Koppel de voeding los

Tijdens de installatie van het apparaat moet de elektrische voeding beslist worden losgekoppeld, omdat de spanning op sommige onderdelen gevaarlijk is voor leven en gezondheid. Het wordt aanbevolen de installatie door een gekwalificeerde persoon te laten uitvoeren.

:::

### Keuze van de montagelocatie

Monteer het apparaat op een voor het bedieningspersoneel toegankelijke plaats, buiten het bereik van kinderen en dieren en zonder direct zonlicht. Het omgevingstemperatuurbereik bedraagt −10°C tot +40°C. Zorg voor een vrije luchtstroom rondom de behuizing en het koellichaam. Dek het koellichaam niet af en monteer het apparaat niet bij warmtebronnen.

### Montage

Bevestig het onderste deel van de behuizing met vier pluggen aan een vlakke wand en gebruik daarbij de montagegaten buiten het afgedichte compartiment. Monteer het deksel met het meegeleverde scharnier. Controleer vóór het sluiten de toestand en de plaatsing van de afdichting.

Gebruik kabels met een ronde buitendoorsnede die geschikt zijn voor de kabelwartels. Draai de kabelwartels zodanig vast dat ze de kabel afdichten en vastzetten. Sluit ongebruikte doorvoeren af. Draai het deksel met alle schroeven vast. De afdichting is afhankelijk van een correcte montage van de behuizing en de doorvoeren.

### Voorbereiding van de aansluitingen

Voer alle werkzaamheden in de behuizing uit nadat de voeding is losgekoppeld en de spanningsloosheid is gecontroleerd. Als voor het verwijderen van het paneel de lintkabel moet worden losgekoppeld, koppel deze dan voorzichtig los en sluit deze weer goed aan voordat u de behuizing sluit. Sluit de lintkabel niet aan en koppel deze niet los terwijl de voeding is ingeschakeld.

Leg de signaalkabels INPUT en ENABLE gescheiden van de voedings- en uitgangskabels. Volg de klemmarkeringen op het betreffende exemplaar van het apparaat. De massa van de signaalingangen en de beschermingsaardklem PE hebben verschillende functies en zijn niet onderling uitwisselbaar.

## Elektrische aansluiting

:::danger Koppel de voeding los

Controleer vóór het aansluiten van de schakeling of de voeding is uitgeschakeld!

:::

![Klemmen voor voeding, ventilatoren, GR 2, ENABLE, CAN en INPUT](./img/sc-pe16/zaciski.png)

| KLEM | FUNCTIE |
| --- | --- |
| L, N, PE — voeding | Voeding 230 V AC, 50 Hz: L — fase, N — nulleider, PE — beschermingsleiding. In de oorspronkelijke documentatie is een beveiliging van B20 aangegeven; bij de keuze van beveiligingen en kabels moet rekening worden gehouden met de installatie en de belasting. |
| U, N, PE — ventilatoren | U — geregelde fase-uitgang; N en PE — overeenkomstige gemeenschappelijke klemmen van het apparaat. De som van de ventilatorstromen mag 16 A niet overschrijden. Elke ventilator vereist een afzonderlijke beveiliging. Gebruik motoren die zijn goedgekeurd voor spanningsregeling. |
| GR 2: C, NO | Geïsoleerd relaiscontact van groep 2. Schakelt in wanneer het ingestelde ventilatieniveau gelijk is aan of hoger is dan de drempel „Ventilatiegroep 2”. Maximale contactstroom volgens de meegeleverde handleiding: 6 A. Bij rechtstreekse aansturing van een belasting vermeldt de documentatie een externe beveiliging van B6. |
| INPUT: V, massa | Spanningsingang. Selecteer „Type aansturing → Ingang V”. In het geanalyseerde programma bedraagt het regelbereik 2–10 V. Sluit geen netspanning of geregelde voedingsuitgang voor ventilatoren op deze ingang aan. |
| INPUT: I, massa | Stroomingang 4–20 mA. Selecteer „Type aansturing → Ingang I”. Sluit het signaal aan volgens de markeringen van de bron en de ontvanger. |

Gebruik voor de aansturing de geselecteerde ingang V of I. SC-PE16 vereist een eigen netvoeding; de analoge ingang draagt alleen de stuurwaarde over.

## ENABLE-ingang en communicatie

### ENABLE: E en massa

De ingang werkt met een potentiaalvrij contact. De klemmen E en massa mogen uitsluitend worden kortgesloten of onderbroken; leg geen externe spanning aan. Kortsluiten geeft het bedrijf vrij, onderbreken stelt het niveau in op 0%. Het stoppen is afhankelijk van de instelling „Uitlooptijd”.

De ENABLE-functie wordt afzonderlijk voor AUTO en MANUAL ingeschakeld in het menu „Geavanceerd → Ventilator”. Beide functies zijn in de fabriek uitgeschakeld, zodat een draadbrug dan niet nodig is. Het onderbreken van ENABLE is niet hetzelfde als de slaapstand: het paneel blijft actief. In AUTO slaat het programma bij actieve ENABLE-blokkering het uitlezen van het stuursignaal over en activeert het safeRUN niet.

### CAN en Wi-Fi

De opties „Ingang CAN” en „Ingang WiFi” zijn in het menu aanwezig, maar voeren in softwareversie 2.1 geen aansturing uit: beide functies leveren het niveau 0%. Selecteer ingang V of I om het apparaat met dit programma in bedrijf te stellen. Configureer de installatie niet op basis van CAN of Wi-Fi zonder bevestiging dat de geïnstalleerde softwareversie deze ondersteunt.

## Werkingsprincipe

SC-PE16 is een vermogensregelaar die opdrachten van een bovenliggende regelaar of een operator uitvoert. Het apparaat meet de ruimtetemperatuur niet en heeft geen eigen instellingen voor temperatuur, luchten, bijverwarming of luchtinlaatkleppen. Het ventilatieniveau in procenten geeft de stuurwaarde aan en is geen meting van het werkelijke motortoerental.

| NOMINAAL SIGNAAL | INGESTELD VENTILATIENIVEAU |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

Tussen de grenswaarden bepaalt het programma het niveau lineair en rondt het af op hele procenten. Voor ingang V begint de stijging wanneer de uitgelezen waarde 2,04 V wordt overschreden, en voor ingang I bij 4,04 mA. De uiteindelijke toestand van de uitgang is ook afhankelijk van ENABLE, de aanloop en de thermische beveiliging.

## Noodbedrijf en beveiligingen

### safeRUN — wegvallen van het ingangssignaal

In de modus AUTO verschijnt het alarm „Ingang” bij een uitgelezen spanning lager dan 1,50 V of een stroom lager dan 2,00 mA, afhankelijk van de geselecteerde ingang. Het programma stelt dan het niveau „Noodbedrijf” in binnen het bereik 0–100%; fabrieksinstelling 30%. Zodra het signaal de detectiedrempel weer bereikt of overschrijdt, verdwijnt het ingangsalarm en keert het apparaat terug naar analoge aansturing.

Het bereik 1,50–2,04 V en 2,00–4,04 mA levert het niveau 0% zonder ingangsalarm. Het signaal 0 V is in deze versie geen normale stopopdracht — het activeert het noodbedrijf. Een bovenliggende regelaar met een uitgang van 0–10 V moet worden geconfigureerd voor het bereik 2–10 V zonder afschakeling naar 0 V. In MANUAL stuurt het analoge signaal de ventilatie niet aan en wordt het ingangsalarm gewist.

### Thermische beveiliging

Het alarm „Oververhitting” wordt geactiveerd wanneer de uitgelezen temperatuur van het koellichaam 87°C overschrijdt. Het wordt gewist nadat de temperatuur onder 80°C is gedaald. Tijdens het alarm wijzigt het programma het ingestelde niveau: bij een waarde van ten minste 50% stelt het 100% in, en bij een waarde lager dan 50% stelt het 0% in. De wijziging van de uitgang is onderworpen aan het aanloop- en uitloopalgoritme. De beveiliging garandeert niet in alle gevallen een ononderbroken werking van de ventilatie.

De toestand van relais GR 2 wordt vóór de thermische correctie bepaald: deze is afhankelijk van het niveau vóór het geforceerd instellen van 0% of 100%. Ook het niveau voor noodbedrijf is onderworpen aan thermische correctie. Controleer bij oververhitting de koelomstandigheden, de vervuiling van het koellichaam en de belasting; laat werkzaamheden in de behuizing door een bevoegde persoon uitvoeren.

### byPASS en zachte aanloop

Bij een stabiel uitgangsniveau van 100% schakelt het programma het overbruggingsrelais van de faseaansnijdingsregeling in. De aanloop kan bestaan uit een opbouw tot 100%, het aanhouden van 100% en de overgang naar het ingestelde niveau. De parameters voor „Zachte aanloop” beïnvloeden ook de reactiesnelheid van de uitgang op een wijziging van de gevraagde waarde.

## Eerste inbedrijfstelling van de regelaar

:::warning Kalibratie van de ventilatoren

Let op! Bij de eerste inbedrijfstelling van het apparaat moet het verboden bedrijfsbereik van de motor beslist worden ingesteld.

:::

1. Controleer bij losgekoppelde voeding de aansluiting van de voeding, PE, ventilatoren en het analoge signaal. Controleer of de motoren zijn goedgekeurd voor spanningsregeling en of de totale stroom maximaal 16 A bedraagt.
2. Schakel de voeding in. Als de taalkeuze wordt aangeboden, druk dan op OK en selecteer de taal. Ontgrendel het toetsenbord met de toets met het hangslotsymbool.
3. Selecteer bij „Type aansturing” de optie „Ingang V” of „Ingang I”. Stel het niveau „Noodbedrijf” en de drempel „Ventilatiegroep 2” in. Activeer ENABLE indien nodig afzonderlijk voor de betreffende modus.
4. Ga naar „Geavanceerd → Ventilator → Verboden bereik”. In deze menuoptie forceert het programma het niveau 1% en heeft een wijziging van de parameter onmiddellijk invloed op de uitgang. Het bereik loopt van −20 tot 200, met fabrieksinstelling 0. Een positieve waarde verhoogt het minimale aansturingsniveau, een negatieve waarde verlaagt het.
5. Kies de waarde zodanig dat alle ventilatoren stabiel draaien, zonder stil te vallen of overmatig op te warmen. Observeer elke ventilator, bij voorkeur met hulp van een tweede persoon. Alleen het omhoogkomen van de klep vervangt de controle van de correcte motorwerking niet. Bevestig met OK; ESC herstelt de vorige instelling.
6. Controleer de uitgang bij verschillende niveaus, waaronder 0%, een laag niveau en 100%. Herhaal de kalibratie na vervanging van de ventilatoren of wijziging van hun configuratie.
7. Controleer in AUTO de reactie op het minimale en maximale signaal. Controleer vervolgens het wegvallen van het signaal en de overgang naar noodbedrijf, evenals de terugkeer na herstel van het signaal. Controleer ook de werking van ENABLE als deze functie actief is.
8. Controleer GR 2 en de alarmsignalering in het menu „Testen”. Verlaat deze menuoptie na afloop van de tests en selecteer de beoogde bedrijfsmodus.

:::warning Werkelijke activering van de uitgangen

Testen en kalibreren sturen de werkelijke uitgangen aan. Ze kunnen de ventilatoren starten en de ventilatietest forceert een niveau onafhankelijk van de normale aansturing. Zorg voor veilige testomstandigheden en voortdurend toezicht.

:::

## Programmering van de regelaar

### Frontpaneel — indicatoren en toetsen

| ELEMENT | BEDIENING |
| --- | --- |
| Voeding / slaapstand | De toets met het voedingssymbool toont een bevestiging voor de slaapstand; bevestig met OK. Door opnieuw te drukken wordt het apparaat geactiveerd. De slaapstand stelt de uitgangen in op de uitgeschakelde toestand; de netspanning wordt niet losgekoppeld. |
| Hangslot | Schakelt de toetsenbordvergrendeling in of uit. Na ontgrendeling brandt het indicatielampje bij het hangslot. Op het hoofdscherm wordt de vergrendeling na ongeveer 30 s inactiviteit weer ingeschakeld. |
| A — AUTO | Selecteert aansturing via de analoge ingang na bevestiging met OK. Het indicatielampje A geeft de geselecteerde modus aan. |
| M — MANUAL | Selecteert handmatige aansturing na bevestiging met OK. Op het hoofdscherm wijzigen de toetsen + en − de instelling 0–100%. Het indicatielampje M geeft de geselecteerde modus aan. |
| +, −, OK, ESC | OK opent het menu, opent een menuoptie en bevestigt de waarde. + en − selecteren een menuoptie of wijzigen de waarde. ESC keert terug naar het vorige niveau of annuleert de bewerking. |
| Alarm en groep 2 | Het rode indicatielampje geeft een alarm aan. Het indicatielampje bij het ventilatorsymbool „2” geeft aan dat relais GR 2 is ingeschakeld. |
| Display | Toont in AUTO het ingestelde ventilatieniveau, de uitgelezen waarde van de geselecteerde ingang, een balkweergave en alarmen. Bij actieve ENABLE wordt ook de toestand daarvan weergegeven. In MANUAL geeft de hoofdwaarde de handmatige instelling aan; beveiligingen kunnen de uitgang wijzigen. |

### Opslaan van instellingen

De menuparameters worden na bevestiging met OK in het niet-vluchtige geheugen opgeslagen. Wijzigingen van het niveau MANUAL worden onmiddellijk van kracht en worden na een korte periode van inactiviteit opgeslagen. Na een stroomuitval worden de opgeslagen instellingen hersteld, waaronder modus AUTO/MANUAL, het handmatige niveau en de slaapstand. Schakel de voeding niet onmiddellijk uit na een wijziging van de handmatige instelling.

Bij een onjuiste controlesom of een waarde buiten het bereik herstelt het programma de fabrieksinstellingen. Controleer dan alle instellingen opnieuw, met name de kalibratie van de ventilatoren, de stuuringang en het noodbedrijf.

## Functies van het basismenu

| MENU | BEREIK / FABRIEKSINSTELLING | BESCHRIJVING |
| --- | --- | --- |
| Type aansturing | Ingang V | Keuze uit V, I, CAN of Wi-Fi. Gebruik voor de geanalyseerde versie V (2–10 V) of I (4–20 mA). CAN en Wi-Fi voeren geen aansturing uit. |
| Ventilatiegroep 2 | 1–100% / 100% | Inschakeldrempel van contact GR 2. Het contact is ingeschakeld bij een niveau dat gelijk is aan of hoger is dan de drempel en uitgeschakeld onder de drempel. Het programma definieert geen afzonderlijke hysterese. |
| Noodbedrijf | 0–100% / 30% | Niveau dat wordt ingesteld bij het wegvallen van het geselecteerde analoge signaal in AUTO. De waarde 0% betekent stoppen bij signaalverlies. |
| Reinigingsvergrendeling | 60 s | Blokkeert de toetsbediening gedurende 60 seconden en toont een aftelling. De ventilatieregeling blijft werken. De functie is bedoeld voor het afnemen van het paneel, niet voor elektrische werkzaamheden of het wassen van de binnenzijde. |
| Geavanceerd | Submenu | Toegang tot tests, taal, ventilatorkalibratie, ENABLE, Zachte aanloop, alarmgeluid, fabrieksinstellingen en programma-informatie. |

## Functies van het geavanceerde menu

| MENU / PARAMETER | BEREIK / FABRIEKSINSTELLING | BESCHRIJVING |
| --- | --- | --- |
| Testen → Ventilatie | 0–100% | Tijdelijk forceren van de geregelde uitgang. Wijzigingen worden tijdens het bewerken van kracht. Na afsluiten met OK of ESC wordt de normale aansturing hervat. |
| Testen → Vent. trap 2 | Nee / Ja | Tijdelijk forceren van contact GR 2 en het bijbehorende indicatielampje. |
| Testen → Alarm | Nee / Ja | Tijdelijke test van de alarmsignalering, inclusief het geluid, onafhankelijk van de normale instelling „Alarmsignaal”. |
| Taal | Pools | Keuze uit Pools, Engels en Oekraïens. |
| Ventilator → Verboden bereik | −20–200 / 0 | Kalibratie van het niveau 1%. Tijdens het bewerken wordt de werkelijke uitgang 1% geforceerd. De parameter wordt niet uitgedrukt in procenten of seconden. |
| Ventilator → Activering EN AUTO | Nee / Ja; Nee | Maakt modus AUTO afhankelijk van de ENABLE-ingang. |
| Ventilator → Activering EN MANUAL | Nee / Ja; Nee | Maakt modus MANUAL afhankelijk van de ENABLE-ingang. |
| Zachte aanloop → Aanlooptijd | 0–50 / 5 | Stijgsnelheid van het niveau tijdens de aanloop tot 100%. Een hogere waarde betekent een langzamere wijziging. Bij de waarde 0 wordt de opbouwfase overgeslagen. |
| Zachte aanloop → Tijd 100% | 0–250 / 100 | Aanhouden van niveau 100% tijdens de aanloop. Bij de waarde 0 wordt de aanhoudfase overgeslagen. Als zowel de aanloop als het aanhouden op 0 wordt ingesteld, wordt het doorblazen tot 100% overgeslagen. |
| Zachte aanloop → Uitlooptijd | 0–50 / 5 | Snelheid waarmee het gevraagde niveau wordt bereikt, ook bij wijziging daarvan. De waarde 0 betekent een wijziging zonder geleidelijke overgang. |
| Alarmsignaal | Nee / Ja; Nee | Schakelt het akoestische alarmsignaal in. De instelling Nee verwijdert niet de melding op het scherm of de signalering via het indicatielampje. |
| Fabrieksinstellingen | Nee / Ja | Na selectie van Ja worden de standaardwaarden hersteld en opgeslagen, waaronder kalibratie 0, ingang V, AUTO, noodbedrijf 30%, drempel GR 2 gelijk aan 100% en uitgeschakelde ENABLE. Configureer en controleer het apparaat na deze handeling opnieuw. |
| Programma | versie 2.1 + compilatiedatum | Toont de versie en compilatiedatum van het programma. Deze beschrijving is opgesteld op basis van de meegeleverde bronbestanden SC_PX16_v02. |

De parameters voor Zachte aanloop zijn dimensieloze instellingen van programmatellers en geen tijden in seconden. Bij 50 Hz komt één stap ongeveer overeen met (instelling + 1) × 20 ms: voor de aanloop en uitloop is dit de tijd voor een wijziging van 1 procentpunt, voor „Tijd 100%” de aanhoudtijd. De waarde 0 heeft de in de tabel beschreven betekenis. De werkelijke tijden zijn afhankelijk van de fase van het algoritme.

## Fout- en waarschuwingsmeldingen

| MELDING | BETEKENIS EN MAATREGELEN |
| --- | --- |
| Ingang | Te lage uitgelezen waarde van het geselecteerde signaal in AUTO. Het apparaat stelt noodbedrijf in. Controleer de signaalbron, de kabels, de gemeenschappelijke massa en de selectie van V/I. |
| Oververhitting | Uitgelezen temperatuur van het koellichaam &gt;87°C; wissen bij &lt;80°C. Het ventilatieniveau wordt ingesteld op 0% of 100%, overeenkomstig de beschrijving van de thermische beveiliging. Controleer de koeling en de belasting. |
| Voeding | Verstoring van de synchronisatie van de vermogensschakeling met het net. Controleer de voeding en de installatie. Bij volledige uitval van de voeding werkt het display niet. |
| Geheugen CRC | Fout in de controlesom of het bereik van de opgeslagen instellingen. Het programma herstelt de standaardwaarden. Controleer de configuratie en herhaal de kalibratie; neem bij herhaling van de fout contact op met de servicedienst. |

## Opmerkingen en waarschuwingen

:::danger Koppel de voeding los

Tijdens de installatie van het apparaat moet de elektrische voeding beslist worden losgekoppeld, omdat de spanning op sommige onderdelen gevaarlijk is voor leven en gezondheid. Het wordt aanbevolen de installatie door een gekwalificeerde persoon te laten uitvoeren.

:::

Lees vóór installatie en gebruik de handleiding. Laat reparaties en werkzaamheden in het apparaat door bevoegd personeel uitvoeren. De slaapstand, toetsenbordvergrendeling, ENABLE en de instelling 0% vormen geen loskoppeling van de voeding en waarborgen geen veilige omstandigheden voor elektrische werkzaamheden.

Stem de instellingen voor ventilatie en noodbedrijf af op de behoeften van de dieren en de installatie. Controleer regelmatig de werkelijke werking van alle ventilatoren. De signalering SC-PE16 vervangt geen onafhankelijke bewaking van de omstandigheden in het gebouw en van stroomuitval. Op de weergegeven klemmenstrook is geen afzonderlijk ALARM-contact voor een alarmcentrale aanwezig.

:::note Afvoer van het apparaat

Gooi het product aan het einde van zijn gebruiksduur niet weg bij het ongesorteerde huishoudelijke afval, maar voer het af overeenkomstig de geldende voorschriften (WEEE-richtlijnen van de Europese Unie 2012/19/EU).

:::

Het product is vervaardigd overeenkomstig de RoHS-eisen (richtlijn van de Europese Unie 2011/65/EU).

## Technische gegevens van de regelaar

| PARAMETER | WAARDE |
| --- | --- |
| Voeding / eigen verbruik | 230 V AC, 50 Hz / &lt;10 W |
| Maximale totale stroom van uitgang U | 16 A |
| Maximale stroom van contact GR 2 | 6 A; contact C–NO, geïsoleerd |
| Ingang V / ingang I | 2–10 V / 4–20 mA, selecteerbaar in het menu |
| Drempel voor signaalverlies (door het programma uitgelezen waarde) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Potentiaalvrij contact E–massa; afzonderlijke activering voor AUTO/MANUAL |
| Thermische beveiliging (uitgelezen temperatuur van het koellichaam) | Alarm &gt;87°C; herstel &lt;80°C |
| Omgevingstemperatuur / behuizing | −10°C tot +40°C / IP65 |
| Afmetingen / overspanningsbestendigheid | 34 × 29 × 12 cm / 210 J |
| Menutalen | Pools, Engels, Oekraïens |

Inhoud van de set volgens de meegeleverde documentatie: 4 pluggen, 2 kabelwartels PG13,5, 1 kabelwartel PG9 en 1 scharnier.

## Garantievoorwaarden

De inhoud van de garantievoorwaarden is overgenomen uit het meegeleverde document van de fabrikant.

1. De fabrikant ELETOR, gevestigd in Polen, adres: Pod Sosno 28, 87-305 Zbiczno (hierna de garantieverstrekker genoemd), verleent de Koper een kwaliteitsgarantie op het product waarvoor dit garantiebewijs is afgegeven, op voorwaarde dat het wordt gebruikt overeenkomstig de bestemming en de voorschriften in de gebruiksaanwijzing die samen met dit product aan de Koper is verstrekt.
2. De garantieperiode bedraagt 24 maanden vanaf de verkoopdatum. Storingen of gebreken van het product die binnen deze periode aan het licht komen, worden kosteloos verholpen. Na afloop van de garantieperiode of bij verlies van de garantierechten worden storingen of gebreken tegen betaling verholpen.
3. De garantie dekt niet:

   - enige gebreken die zijn ontstaan door onjuist gebruik van het product (waaronder het uitvoeren van handelingen die niet in de gebruiksaanwijzing zijn beschreven, enz.);

   - enige defecten die zijn ontstaan als gevolg van reparaties, wijzigingen enz. door een andere persoon dan de garantieverstrekker;

   - enige gebreken of beschadigingen die zijn ontstaan door transport of het vallen van het product, indien deze gebeurtenissen na aankoop van het product hebben plaatsgevonden, alsmede mechanische beschadigingen door onjuiste bediening door de gebruiker;

   - enige gebreken of beschadigingen die zijn ontstaan als gevolg van brand, aardbeving, overstroming, blikseminslag of andere natuurrampen, milieuverontreiniging, de inwerking van externe ioniserende straling of een magnetisch veld, alsmede onregelmatige stroomvoorziening of stroom met parameters die niet aan de vereisten voldoen;

   - enige gebreken die voortvloeien uit onjuiste opslag (bijv. opslag van het product buiten het in de specificatie aangegeven temperatuur- of vochtigheidsbereik, in de nabijheid van chemicaliën), onjuist onderhoud of onjuiste reiniging enz.;

   - enige gebreken die voortvloeien uit het leegraken van de voedingsbatterijen enz.;

   - enige gebreken veroorzaakt door zand, modder, stof, water en andere vloeistoffen enz. die in de behuizing van het product zijn binnengedrongen;

   - beschadigingen als gevolg van natuurlijke, gedeeltelijke of volledige slijtage van het product overeenkomstig de eigenschappen of bestemming van het product;

   - de in de gebruiksaanwijzing vermelde handelingen die de gebruiker zelf dient uit te voeren.

4. De Koper verliest zijn garantierechten als gevolg van:

   - het uitvoeren van enige reparatie of wijziging aan het product door een andere persoon dan de garantieverstrekker;

   - de vaststelling dat een van de verzegelingen is aangetast, beschadigd of verbroken;

   - de vaststelling dat serienummers of andere identificatiemarkeringen van het product zijn beschadigd, aangetast, afgedekt of verwijderd.

5. De reparatietermijn bedraagt maximaal 21 werkdagen vanaf de datum van melding van het gebrek en aflevering van het complete product bij het servicepunt van de garantieverstrekker. In bijzonder gerechtvaardigde gevallen, die verband houden met de noodzaak om onderdelen of componenten uit het buitenland te betrekken of met bijzonder complexe of moeilijk te repareren of te diagnosticeren schade, kan de reparatietermijn worden verlengd met de periode die nodig is om de garantieverplichtingen na te komen.
6. De garantierechten van de Koper kunnen uitsluitend worden uitgeoefend na overlegging van een geldig en op de aankoopdatum correct ingevuld garantiebewijs en een aankoopbewijs (factuur, kassabon enz.). Onbevoegde wijzigingen van de vermeldingen op het garantiebewijs (waaronder doorhalingen, uitwissingen, aanvullingen enz.) leiden tot verlies van de garantierechten. Een garantiebewijs zonder naam, model en serienummer van het product, datum en plaats van aankoop van het product en een leesbare stempel en handtekening van de Verkoper is ongeldig en vormt geen basis voor het rechtsgeldig indienen van een klacht.
7. De Koper is verplicht het product op eigen kosten aan te leveren in een voor de betreffende apparatuur geschikte verpakking die veilig en correct transport en opslag waarborgt, of de voorrijkosten van de garantieverstrekker te vergoeden. Indien wordt vastgesteld dat het ter reparatie aangeboden product technisch in orde en vrij van gebreken is, of indien de vastgestelde storing niet onder de garantie valt, worden de kosten van dienstverlening en transport aan de Koper in rekening gebracht.
8. De Koper is verplicht het gerepareerde product binnen 90 dagen op te halen vanaf de dag waarop de garantieverstrekker kennis heeft gegeven van de reparatie. Indien de koper het product niet binnen deze termijn ophaalt, draagt hij het risico van toevallig verlies of toevallige beschadiging van het product.
9. De garantieperiode wordt verlengd met de duur van de reparatie, gerekend vanaf de datum van aflevering van het product tot de overeengekomen afhaaldatum na reparatie. De garantieverstrekker is verplicht een document af te geven waarin de periode en de omvang van de verholpen productgebreken worden vermeld.

10. De Koper dient aanspraken in via de Verkoper van het product of rechtstreeks op het adres van de garantieverstrekker: ELETOR, Pod Sosno 28, 87-305 Zbiczno, Polen.

11. De garantieverstrekker is niet aansprakelijk:

    - voor gederfde inkomsten als gevolg van het aan het licht komen van een gebrek en de tijd die nodig is om dit te verhelpen;

    - voor verliezen als gevolg van het aan het licht komen van een gebrek en alle schade die voortvloeit uit onjuiste installatie, onjuist gebruik of onjuiste programmering van de functies van het apparaat.
