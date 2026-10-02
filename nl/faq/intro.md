---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: De meest gestelde vragen over selectie, configuratie, diagnose en service
  van ELETOR-apparaten.
keywords:
- ELETOR
- FAQ
- ventilatieregelaars
- regelaars
- ventilatoren
- actuators
- alarmen
- frequentieregelaars
- service
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Veelgestelde vragen

FAQ is opgesteld op basis van een geanonimiseerde analyse van daadwerkelijke gesprekken met gebruikers en klanten van ELETOR. De antwoorden zijn veralgemeend zodat ze helpen in typische gevallen en geen gegevens van specifieke personen of installaties bevatten.

:::note Reikwijdte van de FAQ

De antwoorden hebben betrekking op typische gevallen. Klemmaanduidingen, functies en aansluitwijze kunnen verschillen tussen modellen en uitvoeringen van apparaten. Raadpleeg bij twijfel de documentatie die hoort bij het specifieke product.

:::

:::warning Veiligheid

Werkzaamheden aan de elektrische installatie moeten worden uitgevoerd overeenkomstig de documentatie van het apparaat en de geldende veiligheidsvoorschriften. Werkzaamheden onder netspanning moeten worden uitgevoerd door een persoon met de juiste kwalificaties.

:::

## Selectie van regelaar en vermogen

### Hoe selecteer ik een regelaar voor ventilatoren?

Voor de selectie is vooral de totale stroom van de ventilatoren bepalend, en niet uitsluitend hun aantal.

:::tip Verzamel gegevens vóór de selectie

Hoe nauwkeuriger de gegevens over de motoren en de bedrijfswijze van de installatie, hoe zekerder de selectie van de regelaar.

:::

Voor de selectie is het raadzaam het volgende voor te bereiden:

- aantal ventilatoren,
- voedingsspanning,
- nominaal vermogen of nominale stroom van elke ventilator,
- informatie of alle ventilatoren traploos moeten werken,
- informatie of de ventilatoren in groepen kunnen worden verdeeld,
- informatie over extra apparaten, zoals heaters of luchtinlaten.

De regelaar mag niet exact 'op de grens' worden geselecteerd. Er moet een passende reserve ten opzichte van de maximale belasting worden aangehouden.

### is het voldoende om het vermogen van de ventilatoren in watt op te tellen?

Voor een voorlopige schatting kan het vermogen worden gebruikt, maar de definitieve selectie moet zijn gebaseerd op de nominale stroom van de apparaten en de aard van de belasting.

Een motor kan tijdens het opstarten meer stroom opnemen dan tijdens normale werking. Daarom zijn twee sets ventilatoren met een vergelijkbaar nominaal vermogen niet altijd een gelijkwaardige belasting voor de regelaar.

### Ik heb meerdere kleine ventilatoren. Kan ik ze parallel op één uitgang aansluiten?

Ja, indien:

- zij voor deze regelwijze bedoeld zijn,
- zij samen moeten werken,
- de som van de belastingen de toegestane uitgangsstroom niet overschrijdt,
- de aansluitwijze in overeenstemming is met de documentatie van de regelaar.

Bij een groter aantal ventilatoren is het zinvol om groepsindeling of een vermogensuitbreiding te overwegen.

### Wanneer is een vermogensuitbreiding nodig?

Een vermogensuitbreiding wordt toegepast wanneer de belasting de mogelijkheden van de uitgang van de regelaar overschrijdt, of wanneer de installatie wordt uitgebreid met een groter aantal ventilatoren.

De regelaar geeft dan het stuursignaal door, terwijl de feitelijke belasting door een extra module wordt verwerkt.

### Kan de installatie later worden uitgebreid met extra ventilatoren?

In veel installaties wel. Meestal worden toegepast:

- een extra vermogensuitbreiding,
- een extra ventilatiegroep,
- een contactor die een volgende groep inschakelt,
- een frequentieregelaar bij driefasenmotoren.

Geplande uitbreiding kan het best al bij de eerste selectie van de regelaar worden meegenomen.

### Moeten alle ventilatoren traploos werken?

Nee. Twee oplossingen zijn gebruikelijk:

1. alle ventilatoren werken traploos,
2. de eerste groep werkt traploos en de volgende groepen worden stapsgewijs bijgeschakeld, bijvoorbeeld via contactoren.

De tweede oplossing maakt het mogelijk een grotere installatie te bedienen zonder traploze regeling van elke ventilator.

### Ik heb 10 ventilatoren. Heb ik een zeer grote regelaar nodig?

Niet altijd. Er kunnen verschillende regelwijzen worden toegepast:

- indeling in groepen,
- vermogensuitbreidingen,
- contactoren,
- frequentieregelaar.

De definitieve selectie hangt af van de elektrische parameters van de ventilatoren en van de vraag of ze allemaal gelijktijdig van toerental moeten veranderen.

### Verschillen regelaar 6 A en 12 A alleen in toegestane belasting?

Er mag niet van worden uitgegaan dat de stroomwaarde het enige verschil is. Verschillende uitvoeringen en generaties van apparaten kunnen verschillen in uitrusting of uitvoering.

Bij vervanging van een apparaat moeten het exacte model en de actuele documentatie worden gecontroleerd.


## Ventilatoren en ventilatieregeling

### Regelt de regelaar de ventilatoren traploos?

Bij regelaars die bedoeld zijn voor traploze ventilatieregeling wordt de ventilatorsnelheid aangepast aan de vraag, die onder meer uit de temperatuur voortvloeit.

Er moet echter worden gecontroleerd of het betreffende motortype geschikt is voor de toegepaste regelwijze.

### Wat betekent de ingestelde temperatuur?

De ingestelde temperatuur is de waarde waarmee de regelaar de actuele temperatuurmeting vergelijkt.

Op basis hiervan verhoogt of verlaagt de regelaar de ventilatie-intensiteit overeenkomstig de overige instellingen, zoals de regelband en het minimale en maximale niveau.

### Wat betekent het minimale ventilatieniveau?

Dit is de minimale aanstuurwaarde van de ventilator tijdens automatische werking.

Deze instelling voorkomt werking onder een niveau waarbij de ventilator instabiel zou kunnen werken of te weinig luchtverversing zou leveren.

### Wat betekent het maximale ventilatieniveau?

Dit is de bovengrens van de aanstuurwaarde voor de ventilatie.

Het instellen van een waarde onder 100% kan bijvoorbeeld het maximale toerental van de ventilator beperken, als de installatie dit vereist.

### Wat betekent de ventilatieband?

De ventilatieband bepaalt het temperatuurbereik waarin de regelaar overgaat van het minimale naar het maximale ventilatieniveau.

Hoe kleiner de band, hoe sneller de regeling met een capaciteitsverhoging reageert op een temperatuurverandering.

### Na het starten gaat de ventilator eerst naar 100% en vertraagt pas daarna. Waarom?

Er kan een opstartfunctie actief zijn waarvan de taak is de motor kortstondig met hoger vermogen te starten.

Afhankelijk van de uitvoering van de regelaar moeten de instellingen worden gecontroleerd die verband houden met:

- de functie Soft Start,
- de oplooptijd,
- de werktijd bij 100%,
- de aflooptijd.

Als de functie in de betreffende installatie niet nodig is, kunnen de betreffende parameters volgens de instructie van het apparaat worden gewijzigd.

### Waarom kan de ventilator bij het starten kortstondig op vol vermogen worden ingeschakeld?

Zo'n opstart kan helpen om de ventilator betrouwbaar te laten starten en is nuttig in installaties waarin mechanische onderdelen bij de start meer weerstand kunnen bieden.

Dit is echter niet in elke installatie nodig.

### Wat betekenen oplooptijd en aflooptijd?

**Oplooptijd** bepaalt hoe de aansturing toeneemt tijdens het starten van de ventilator.

**Aflooptijd** bepaalt hoe de snelheid wordt verlaagd.

Beide parameters maken het mogelijk abrupte veranderingen in toerental en werking van de installatie te beperken.

### Waarom kunnen twee identieke regelaars ventilatoren verschillend opstarten?

De meest voorkomende oorzaak zijn verschillende instellingen.

Het is vooral zinvol om het volgende te vergelijken:

- de ingestelde temperatuur,
- de ventilatieband,
- minimum en maximum,
- de instellingen van Soft Start,
- de oploop- en aflooptijden,
- de configuratie van de ventilatiegroepen.

### Kan de regelaar de ventilatie periodiek inschakelen, onafhankelijk van de temperatuur?

Afhankelijk van het model is een functie voor periodieke ventilatie beschikbaar.

Deze functie kan de ventilatie gedurende een bepaalde tijd op ingestelde intervallen inschakelen, ook wanneer de temperatuurregeling geen verhoging van de ventilatie vereist.

### Waarvoor dienen ventilatiegroepen?

Groepen maken een stapsgewijze verhoging van de installatiecapaciteit mogelijk.

Bijvoorbeeld:

- groep 1 werkt traploos,
- groep 2 schakelt extra ventilatoren in,
- de volgende groep schakelt in bij nog grotere vraag.

Zo kan een groot aantal ventilatoren worden geregeld zonder traploze regeling van elk afzonderlijk exemplaar.

### Kan een extra groep ventilatoren via een contactor worden ingeschakeld?

Ja. De relaisuitgang van de regelaar kan de spoel van een passend geselecteerde contactor aansturen.

De belasting van de ventilatoren mag dan niet rechtstreeks via het kleine stuurcontact worden gevoerd.

### Wat betekent het ventilatorsymbool of het gele indicatielampje op de regelaar?

Afhankelijk van het model geven de indicatielampjes de actuele status van uitgangen en functies weer.

Een gele indicatie kan een actieve werkfunctie aanduiden, bijvoorbeeld de werking van ventilatie, verwarming of een volgende groep.

De exacte betekenis moet in de handleiding van het betreffende model worden gecontroleerd.

### Wat betekent het symbool voor de handmatige modus?

De handmatige modus betekent dat de aanstuurwaarde door de gebruiker is geforceerd en op dat moment niet automatisch op basis van de temperatuur wordt berekend.

Na afloop van de tests moet worden gecontroleerd of de regelaar is teruggezet naar de juiste automatische modus.


## Luchtinlaten en actuators

### Kan de regelaar luchtinlaten aansturen?

Ja, geselecteerde regelaars ondersteunen samenwerking met aandrijvingen van luchtinlaten.

De aansluitwijze hangt af van het type actuator en de manier waarop deze wordt aangestuurd.

### Welke typen actuators kunnen voor inlaten worden gebruikt?

In technische gesprekken kwamen het vaakst twee oplossingen voor:

- een actuator aangestuurd met een analoog signaal 0–10 V of 2–10 V,
- een omkeerbare open/dicht-actuator met terugkoppelsignaal, bijvoorbeeld van een potentiometer.

Voor aankoop moet de compatibiliteit van het specifieke model met de aanwezige regelaar worden gecontroleerd.

### Is de voedingsspanning van de actuator 24 V of 230 V van belang voor het signaal 0–10 V?

Het stuursignaal en de voeding van de actuator zijn afzonderlijke parameters.

De actuator kan met een andere spanning worden gevoed dan de spanning van het stuursignaal. Beide parameters moeten overeenkomen met de documentatie van de actuator en de regelaar.

### Wat betekent aansturing 0–10 V?

De regelaar stuurt een analoog spanningssignaal uit dat de gewenste positie of het gewenste aanstuurniveau weergeeft.

In een typische toepassing betekent een lagere waarde een kleinere opening en een hogere waarde een grotere, maar de werkelijke karakteristiek moet in de documentatie van de actuator worden gecontroleerd.

### Wat is het verschil tussen 0–10 V en 2–10 V?

In beide gevallen wordt de positie via een analoog signaal ingesteld.

Bij de standaard 2–10 V is het onderste deel van het bereik verschoven en kan het apparaat daardoor het stuursignaal onderscheiden van het ontbreken daarvan.

Regelaar en actuator moeten een compatibel bereik ondersteunen.

### Hoe moet een actuator worden geselecteerd in verhouding tot het aantal inlaten?

Een actuator mag niet uitsluitend op basis van het aantal kleppen worden geselecteerd.

Er moet rekening worden gehouden met:

- de vereiste kracht of het vereiste koppel,
- de lengte en de manier van geleiding van het mechanisme,
- de weerstand van de kleppen,
- de slaglengte,
- de werkingssnelheid,
- de voedingsspanning,
- het type aansturing,
- de vereiste terugkoppeling.

### Kan één actuator meerdere kleppen bedienen?

Ja, als de mechanica van de installatie het toelaat om de kleppen via een gemeenschappelijk mechanisme te koppelen en het vereiste koppel of de vereiste kracht de mogelijkheden van de actuator niet overschrijdt.

In de praktijk wordt de selectie bepaald door de weerstand van het volledige mechanisme en niet door alleen het aantal kleppen.

### Kunnen meerdere actuators parallel worden aangesloten en met één signaal worden aangestuurd?

In sommige systemen is dit mogelijk, maar de documentatie van de actuators en de toegestane belasting van de stuuruitgang moeten worden gecontroleerd.

Bij omkeerbare aandrijvingen zonder onafhankelijke terugkoppeling kunnen de posities van afzonderlijke actuators bovendien geleidelijk uit synchronisatie raken.

### Waarom kunnen meerdere actuators na verloop van tijd in verschillende posities komen te staan?

Zelfs identieke motoren kunnen met een enigszins verschillende snelheid werken door:

- verschillende belasting,
- mechanische weerstand,
- tolerantie van motorparameters,
- verschillen in overbrengingen.

Daarom is bij vereiste nauwkeurige synchronisatie een juiste terugkoppeling of individuele positieregeling nodig.

### Kunnen inlaten proportioneel ten opzichte van de ventilatie worden aangestuurd?

Ja. In correct geconfigureerde systemen kan de positie van de inlaten worden gekoppeld aan het actuele ventilatieniveau.

Daardoor wordt bij een toename van de ventilatorcapaciteit ook de opening van de inlaten vergroot.

### Heeft actuator 24 V een afzonderlijke voeding nodig?

Als de regelaar niet beschikt over een geschikte voedingsuitgang met het vereiste vermogen, is een afzonderlijke voeding nodig.

Het vermogen daarvan moet worden afgestemd op het stroomverbruik van de actuator en van andere apparaten die uit dezelfde bron worden gevoed.

### Kan een actuator van een andere fabrikant worden toegepast?

Vaak wel, als de elektrische parameters en de regelwijze overeenkomen met de uitgangen van de regelaar.

Vóór aansluiting moet het volgende worden gecontroleerd:

- spanning,
- signaaltype,
- aansluitschema,
- bewegingsrichtingen,
- positiesignaal,
- toegestane belasting.


## Temperatuur- en vochtigheidssensoren

### Waar moet de temperatuursensor worden aangesloten?

De sensor moet worden aangesloten op de door de fabrikant voorziene sensoringang, de sensoringang die in de documentatie van het betreffende model is aangegeven.

Er mag niet van worden uitgegaan dat de klemmaanduidingen in alle uitvoeringen van de apparaten identiek zijn.

### De temperatuursensor geeft een andere waarde aan dan de referentiethermometer. Wat moet worden gedaan?

Als de regelaar een sensorcalibratiefunctie heeft, kan de weergave worden gecorrigeerd na vergelijking met een betrouwbare referentiethermometer.

Vóór wijziging van de calibratie is het raadzaam te controleren of:

- beide sensoren zich op dezelfde plaats bevinden,
- de meting is gestabiliseerd,
- de sensor niet wordt verwarmd door zonlicht of apparatuur,
- de sensor zich niet rechtstreeks in een stroom koude of warme lucht bevindt.

### De vochtigheidssensor geeft een onjuiste waarde aan. Kan deze worden gekalibreerd?

Dit hangt af van de uitvoering van de regelaar, de sensor en de software.

Bij sommige oplossingen kan correctie een geschikte softwarefunctie of een compatibel sensortype vereisen. Als het verschil groot en reproduceerbaar is, moet de versie van het apparaat worden gecontroleerd en contact worden opgenomen met de technische ondersteuning.

### Betekent een foutieve meting altijd dat de sensor defect is?

Nee.

De oorzaak kan ook zijn:

- een onjuiste plaats van de sensor,
- de kabel,
- de elektrische verbinding,
- de configuratie,
- een onjuist sensortype,
- de noodzaak van calibratie,
- vocht of corrosie.


## Alarmen en meldingen

### Kan rechtstreeks een sirene op de alarmuitgang van de regelaar worden aangesloten?

Daar mag niet van worden uitgegaan.

De alarmuitgang van de regelaar is gewoonlijk een stuuruitgang of een relaiscontact. Een sirene kan een afzonderlijke voeding en een alarmcentrale vereisen.

### Waarom wordt een alarmcentrale toegepast?

De centrale kan:

- alarmsignalen van regelaars ontvangen,
- de signaalgever voeden,
- de werking tijdens een spanningsuitval in stand houden,
- alarm met geluid of licht signaleren,
- GSM-meldingen verzenden in uitvoeringen die over deze functie beschikken.

### Kan de centrale alarm geven bij uitval van de voeding van de regelaar?

Ja, als het systeem correct is aangesloten.

De oplossing kan niet alleen een temperatuuroverschrijding detecteren, maar ook het wegvallen van het signaal van de regelaar als gevolg van uitval van zijn voeding.

### Waar worden de minimale en maximale alarmtemperatuur ingesteld?

In een typische configuratie worden de alarmdrempels ingesteld in de regelaar die de betreffende kamer of ruimte bedient.

De alarmcentrale ontvangt vervolgens de melding dat de regelaar alarm heeft gegeven.

### Vereist een GSM-centrale een simkaart?

Voor het verzenden van oproepen en berichten via het mobiele netwerk is een actieve simkaart of een andere communicatieve oplossing vereist die in het betreffende model is voorzien.

Zonder een actieve verbinding met het mobiele netwerk zullen telefonie- en sms-functies niet werken.

### Kan het alarm informatie versturen van welke regelaar de gebeurtenis afkomstig is?

In een correct geconfigureerd systeem wel.

Ingangen van de centrale kunnen aan specifieke ruimten of regelaars worden toegewezen, zodat in het bericht de bron van het alarm kan worden bepaald.

### Hoeveel regelaars kunnen op één alarmcentrale worden aangesloten?

Dit hangt af van het model van de centrale.

In de transcripties kwamen centrales voor die tot acht ingangen ondersteunden, maar vóór uitvoering van de installatie moet de actuele specificatie van het betreffende apparaat worden gecontroleerd.

### Welke accu wordt in de alarmcentrale toegepast?

In een deel van de in de gesprekken besproken apparaten werd een accu 12 V 7 Ah toegepast.

Vóór aanschaf van een vervanger moeten de aanduiding op de bestaande accu en de specificatie van de centrale worden gecontroleerd, omdat andere uitvoeringen van apparaten een andere accu kunnen vereisen.

### De centrale verstuurt meldingen over lage spanning. Wat moet worden gecontroleerd?

Controleer eerst:

- de toestand van de accu,
- de leeftijd ervan,
- de aansluitingen van de accu,
- de aanwezigheid van netvoeding,
- de werking van de lader of voeding van de centrale.

Een versleten accu kan periodieke meldingen over lage spanning veroorzaken.

### Hoe vaak moet de accu in de alarmcentrale worden vervangen?

Er is geen eenduidige waarde die voor alle omstandigheden geschikt is.

De accu moet periodiek worden getest, vooral in installaties waarin alarm tijdens spanningsuitval van kritisch belang is. Met de leeftijd neemt de werkelijke capaciteit af.

### Is alleen een sirene voldoende als beveiliging?

Een sirene is alleen effectief als iemand deze kan horen.

In objecten die tijdelijk onbeheerd blijven, is het raadzaam ook meldingen op afstand en accuback-up toe te passen.


## Frequentieregelaars

### Hoe selecteer ik een frequentieregelaar voor ventilatoren?

Bekend moeten zijn:

- de voedingsspanning,
- het aantal fasen,
- het vermogen en de stroom van alle motoren,
- hun aansluitwijze,
- de bedrijfsomstandigheden,
- de vereiste regelwijze.

De frequentieregelaar moet een passende reserve ten opzichte van de belasting hebben, vooral wanneer meerdere motoren parallel werken.

### Moet de frequentieregelaar precies hetzelfde vermogen hebben als de som van het vermogen van de motoren?

Een frequentieregelaar mag niet uitsluitend worden geselecteerd op basis van een eenvoudige optelsom van het vermogen, noch mag een apparaat worden gekozen dat exact op de grens van zijn parameters werkt.

Er moet rekening worden gehouden met de nominale stromen, de aard van de belasting en de aanbevelingen van de fabrikant van de frequentieregelaar.

### De frequentieregelaar heeft de ventilatoren gestopt en een fout weergegeven. Wat moet worden gedaan?

Het belangrijkste is de volledige foutcode te noteren vóór de reset.

:::tip Maak een foto van het scherm

Als de situatie het toelaat, maak dan vóór de reset een foto van het display. De volledige foutcode vergemakkelijkt de diagnose aanzienlijk.

:::

Alleen het begin van de melding is vaak niet voldoende om de oorzaak vast te stellen. De volledige code maakt onder meer onderscheid tussen:

- overbelasting,
- overstroom,
- oververhitting,
- onjuiste spanning,
- andere aandrijffouten.

### Kan een fout van de frequentieregelaar gewoon worden gereset?

Een reset kan de werking herstellen, maar neemt de oorzaak van het alarm niet weg.

Na de gebeurtenis moet de foutcode worden gecontroleerd en de oorzaak worden vastgesteld voordat de installatie opnieuw langdurig in bedrijf wordt genomen.

### De frequentieregelaar werkt in een stoffige ruimte. Moet deze worden gereinigd?

Ja.

Stof en afzettingen op de koelribben of de koelventilator kunnen de warmteafvoer verslechteren en tot oververhitting van de frequentieregelaar leiden.

Reiniging moet volgens de instructies van de fabrikant worden uitgevoerd, nadat de voeding veilig is losgekoppeld.

### Waardoor kan een frequentieregelaar oververhit raken?

De meest voorkomende oorzaken zijn:

- vervuilde koelelementen,
- belemmerde luchtstroom,
- te hoge omgevingstemperatuur,
- overbelasting,
- defect van de koelventilator,
- onjuiste montage.

### Kan verhoogde netspanning een alarm van de frequentieregelaar veroorzaken?

Ja. Frequentieregelaars bewaken de spanning van het voedingscircuit en kunnen een fout melden wanneer het toegestane niveau wordt overschreden.

Als het probleem zich herhaalt, moeten de installatie en de kwaliteit van de voeding worden gecontroleerd.


## Storingen en diagnose

### De regelaar werkt, maar het display toont niets. Wat kan de oorzaak zijn?

Mogelijke oorzaken zijn onder meer:

- defect van het display,
- een probleem met de contrastregeling in oudere oplossingen,
- een defecte verbinding,
- corrosie,
- defect van de hoofdprintplaat.

Als het apparaat lange tijd niet is gebruikt of in een vochtige omgeving heeft gewerkt, is het ook raadzaam de toestand van de printplaat te controleren.

### De regelaar heeft na enkele jaren van niet-gebruik een probleem met het display. Waarom?

Langdurige stilstand in een vochtige of agressieve omgeving kan leiden tot:

- oxidatie van connectoren,
- corrosie,
- verslechtering van contacten,
- beschadiging van elektronische componenten.

In dat geval is het raadzaam een volledige inspectie uit te voeren en niet zonder voorafgaande diagnose onderdelen te vervangen.

### De regelaar is zwartgeblakerd na overspanning. Betekent dit dat de printplaat moet worden vervangen?

Niet altijd.

Een beveiligingselement kan beschadigd raken en veel aanslag achterlaten, terwijl de rest van de printplaat nog repareerbaar is.

Als het laminaat echter verkoold of doorgebrand is, of als de printbanen beschadigd zijn, kan reparatie economisch onrendabel of niet duurzaam zijn.

### Waardoor kunnen meerdere regelaars tegelijk beschadigd raken?

Als meerdere apparaten tegelijk defect raken, moet de voedingsinstallatie worden gecontroleerd.

Een van de mogelijke oorzaken is een probleem met de nulleider, dat in een driefaseninstallatie kan leiden tot onjuiste spanningen op eenfasige verbruikers.

Ook overspanningen afkomstig van het net of een aggregaat zijn mogelijk.

### Wat moet worden gedaan na een storing als gevolg van overspanning?

Vóór aansluiting van een gerepareerde of nieuwe regelaar moet de oorzaak van het probleem worden vastgesteld.

:::danger Sluit het apparaat niet opnieuw aan zonder de installatie te controleren

Als de oorzaak van de storing onjuiste spanning, een defecte nulleider of overspanning was, kan de gerepareerde of nieuwe regelaar opnieuw beschadigd raken.

:::

### Wat is een overspanningsbeveiligingselement op de printplaat?

In elektronische apparaten worden elementen toegepast die overspanningen begrenzen, bijvoorbeeld varistoren.

Hun taak is een deel van de energie van de overspanning op te nemen en de verdere circuits te beschermen. Na een zware gebeurtenis kan zo'n element blijvend beschadigd raken.

### Kan het apparaat worden ingeschakeld nadat het verbrande beveiligingselement is verwijderd?

Dit mag niet als een normale reparatie worden beschouwd.

Na verwijdering van de beveiliging kan het apparaat zijn bescherming tegen een volgende overspanning verliezen. Dergelijke handelingen mogen uitsluitend als bewuste serviceprocedure worden uitgevoerd door een persoon met de juiste kwalificaties en nadat de oorspronkelijke oorzaak van de storing is verholpen.

### De regelaar is nat geworden of sterk gecorrodeerd. Is het zinvol deze te repareren?

Dat hangt af van de mate van beschadiging.

Oppervlakkige corrosie en afzonderlijke beschadigingen kunnen vaak worden verholpen. Als de corrosie printbanen, connectoren en veel componenten heeft aangetast, kan reparatie tijdrovend, onzeker en economisch onredelijk zijn.

### Kan het onder druk reinigen van het apparaat de regelaar beschadigen?

Ja.

Elektronica mag niet worden blootgesteld aan directe inwerking van water of reinigingsmiddel als de behuizing en de montagwijze daarvoor niet zijn ontworpen.

Vocht dat binnendringt kan leiden tot corrosie en latere storingen die moeilijk te diagnosticeren zijn.

### Waarom kunnen storingen na waterschade na reparatie terugkeren?

Corrosie kan ook doorgaan op plaatsen die bij de eerste inspectie niet zichtbaar zijn.

Beschadigde doorverbindingen, printbanen en verbindingen kunnen tijdens de test functioneren en later opnieuw contact verliezen.

Daarom kan de servicedienst bij een sterk gecorrodeerde printplaat vervanging aanbevelen in plaats van verdere reparaties.

### Het apparaat werkt de ene keer wel en de andere keer niet. Waar te beginnen?

Verzamel vóór contact met de servicedienst bij voorkeur:

- het exacte model,
- een beschrijving van het symptoom,
- het moment waarop het optreedt,
- de waarden die op het scherm worden weergegeven,
- de alarm- of foutcode,
- informatie over recente wijzigingen in de installatie,
- een foto van de binnenzijde en de klemmen, als deze veilig kan worden gemaakt.

Hoe nauwkeuriger de beschrijving, hoe eenvoudiger de diagnose.


## Service en reparaties

### Wat moet naar de servicedienst worden gestuurd als de regelaar defect is?

Het beste is een volledige set op te sturen waarmee het probleem kan worden gereproduceerd.

Voeg een korte beschrijving bij de zending:

- wat niet werkt,
- wanneer het probleem optreedt,
- of de storing permanent of periodiek is,
- of vóór de storing overspanning, waterschade of een andere gebeurtenis is opgetreden,
- de gegevens die nodig zijn voor contact en retourzending van het apparaat.

:::note Gegevens voor de servicemelding

Geef contact- en verzendgegevens rechtstreeks aan de servicedienst door. Publiceer deze niet in open meldingen of openbare materialen.

:::

### Moet de volledige regelaar worden opgestuurd of alleen de printplaat?

Dat hangt af van de storing.

Bij problemen met het display, de toetsen, de voeding of niet-eenduidig gedrag is het het beste de volledige set op te sturen die nodig is om het symptoom te reproduceren.

Bij een vooraf overeengekomen reparatie van een specifieke module kan de servicedienst alleen om de printplaat vragen.

### Repareert ELETOR regelaars in plaats van ze meteen te vervangen?

Uit de transcripties blijkt dat de apparaten eerst worden gediagnosticeerd.

Als reparatie mogelijk en zinvol is, worden defecte componenten of modules vervangen. Bij ernstige schade kan de servicedienst vervanging van de printplaat of het volledige apparaat voorstellen.

### Wat gebeurt er als een defecte printplaat niet kan worden gerepareerd?

Vervanging van de defecte module door een nieuwe is mogelijk, mits het juiste onderdeel beschikbaar en compatibel met het apparaat is.

Bij oudere apparaten moet de servicedienst eerst de compatibiliteit van de versie bevestigen.

### Is het zinvol om direct een nieuwe printplaat te kopen na overspanning?

Niet altijd.

Als de schade een beveiligingselement of een klein deel van het circuit betreft, kan reparatie gerechtvaardigd zijn. Het is raadzaam eerst een diagnose uit te voeren.

### Kan de servicedienst ook het display en de toetsen controleren?

Ja, als deze onderdelen samen met het apparaat of de module worden aangeleverd.

Dit is vooral nuttig wanneer niet bekend is of het probleem zich op de hoofdprintplaat of in het gebruikerspaneel bevindt.

### Is het altijd de moeite waard een sterk gecorrodeerde regelaar te redden?

Nee.

Als de kosten van diagnose en reparatie stijgen en de betrouwbaarheid na reparatie onzeker blijft, kan vervanging verstandiger zijn.

Dit geldt in het bijzonder voor apparaten waarvan de ventilatie van het object afhankelijk is.

### Hoe kan de servicediagnose worden versneld?

Voeg een nauwkeurige beschrijving van het symptoom toe in plaats van alleen de opmerking 'werkt niet'.

Ook nuttig zijn:

- foto's,
- de foutcode,
- een beschrijving van de installatie,
- het type aangesloten verbruikers,
- informatie over overspanning of spanningsuitval,
- informatie over waterschade of reiniging van het apparaat.


## Installatie en bekabeling

### Hoe worden apparaten aangesloten op relaisklemmen C en NO?

C en NO zijn gebruikelijke aanduidingen van een relaiscontact:

- C — gemeenschappelijk contact,
- NO — normaal open contact.

De wijze van gebruik hangt af van het apparaat en het installatieschema. Het contact kan bijvoorbeeld worden gebruikt om de spoel van een contactor aan te sturen, maar de toegestane parameters mogen niet worden overschreden.

:::warning Elektrische werkzaamheden

Aansluitingen op netspanning moeten worden uitgevoerd door een persoon met de juiste kwalificaties, overeenkomstig het schema van het betreffende apparaat.

:::

### Kan een relaisuitgang rechtstreeks een grote ventilator voeden?

Dit is gewoonlijk geen juiste toepassing van een kleine stuuruitgang.

Voor grotere belastingen worden een contactor, vermogensrelais of een speciale uitvoermodule toegepast.

### Waarvoor dienen klemmen A1 en A2 van de contactor?

Dit zijn de klemmen van de spoel van de contactor.

Wanneer de juiste spanning op de spoel wordt gezet, verandert de contactor de toestand van zijn vermogenscontacten.

De spoelspanning moet overeenkomen met het ontwerp van de installatie en de documentatie van de contactor.

### Kunnen extra apparaten binnen in de behuizing van de regelaar worden gemonteerd?

Alleen als de constructie van de betreffende behuizing dit toelaat en dit geen verslechtering veroorzaakt van:

- de beschermingsgraad,
- de isolatie,
- de koeling,
- de veiligheid,
- de servicetoegang.

Alle nieuwe openingen moeten zo worden uitgevoerd dat de vereiste afdichting behouden blijft.

### Zijn extra schakelaars voor ventilatoren nuttig?

Ze kunnen service vergemakkelijken en een onafhankelijke uitschakeling van afzonderlijke ventilatoren mogelijk maken.

De uitvoering moet echter rekening houden met de elektrische beveiligingen en mag geen gevaarlijke toestanden van de regelaar veroorzaken.

### Kunnen stuurkabels samen met vermogenskabels worden gelegd?

Het moet worden vermeden om gevoelige signaalkabels parallel en zeer dicht langs kabels met groot vermogen te leggen, vooral over lange trajecten.

De eisen hangen af van het soort signaal en de elektromagnetische omgeving.

### Welke kabel moet worden gebruikt voor netwerkverbindingen en PoE-apparaten?

In de besproken installaties werd minimaal twisted pair van categorie 5e aanbevolen.

Als de kabel wordt gelegd in een omgeving met een verhoogd niveau van storingen of risico op elektrostatische ladingen, kan het zinvol zijn een passend afgeschermde kabel en een correct aardingssysteem toe te passen.

### Is voor PoE een cross-overkabel nodig?

In typische installaties wordt een standaard rechte verbinding toegepast.

De eisen van het netwerkapparaat en de toegepaste PoE-voeding moeten echter altijd worden gecontroleerd.


## Gebruik en onderhoud

### Hoe kan het risico op storingen van regelaars in agrarische gebouwen worden beperkt?

Het belangrijkste is de invloed te beperken van:

- vocht,
- ammoniak en een agressieve omgeving,
- stof,
- directe reiniging met water,
- overspanningen,
- onjuiste voeding.

Het is ook raadzaam periodiek de toestand van kabels, verbindingen en behuizingen te controleren.

### Moeten elektronische apparaten regelmatig worden gereinigd?

Ja, vooral apparaten die zijn uitgerust met koelribben, ventilatoren en ventilatieopeningen.

Opgehoopt stof verslechtert de koeling.

Reiniging moet worden uitgevoerd nadat de voeding is losgekoppeld en overeenkomstig de instructie van het apparaat.

### Is het zinvol om na enkele jaren bedrijf een inspectie van de regelaar uit te voeren?

Ja, vooral onder zware omgevingsomstandigheden.

De inspectie kan omvatten:

- beoordeling van de toestand van connectoren,
- controle op sporen van vocht en corrosie,
- controle van koelelementen,
- controle van het paneel en de toetsen,
- test van de sensoren,
- controle van accu's in alarmsystemen.

### Wat moet na het optreden van een storing worden genoteerd?

Het meest nuttig zijn:

- de volledige melding,
- de foutcode,
- het tijdstip van de gebeurtenis,
- de temperatuur,
- de status van de ventilatie,
- informatie over spanningsuitval,
- informatie over werking van het aggregaat,
- een foto van het scherm of het apparaat.

Het apparaat mag niet worden gereset voordat de code is genoteerd, als de situatie dit op veilige wijze toelaat.

### Is het zinvol om een alarm te hebben dat onafhankelijk is van de ventilatieregelaar?

Ja, vooral waar een uitval van de ventilatie snel tot gevaarlijke omstandigheden kan leiden.

Een onafhankelijke centrale met eigen accu en meldingen op afstand biedt een extra beveiligingslaag.

### Welke informatie moet vóór contact met de technische ondersteuning worden voorbereid?

Het is het beste om het volgende voor te bereiden:

1. het exacte model van het apparaat,
2. een beschrijving van de installatie,
3. het aantal en de parameters van de aangesloten apparaten,
4. de actuele instellingen die met het probleem verband houden,
5. het exacte symptoom,
6. de volledige fout- of alarmcode,
7. foto's van het apparaat en de typeplaatjes,
8. informatie over recente wijzigingen in de installatie.

Dit kan de diagnose aanzienlijk verkorten.


## Belangrijke opmerking over oudere apparaten

Namen, klemmaanduidingen en beschikbare functies kunnen verschillen tussen uitvoeringen van apparaten die in verschillende jaren zijn geproduceerd.

Als het apparaat enkele of meer dan tien jaar oud is, moet vóór gebruik van de instructie van een nieuwer model worden bevestigd:

- de exacte apparaataanduiding,
- de versie van de printplaat,
- het type display,
- de softwareversie,
- het klemmenschema.

:::warning Oudere uitvoeringen van apparaten

Ga niet uit van volledige compatibiliteit alleen op basis van een vergelijkbaar uiterlijk van de behuizing. Bevestig vóór gebruik van het schema of de instructie het exacte model en de uitvoering van het apparaat.

:::


## Contact met de technische ondersteuning

Als de FAQ het probleem niet oplost, bereid dan vóór contact het volgende voor:

- een foto van de regelaar,
- een foto van het typeplaatje van de verbruiker,
- de parameters van de motoren of actuators,
- het aansluitschema,
- een nauwkeurige beschrijving van de gewenste werking.

Hierdoor kan de selectie van het apparaat of de diagnose van het probleem worden uitgevoerd op basis van de werkelijke parameters van de installatie en niet op basis van aannames.
