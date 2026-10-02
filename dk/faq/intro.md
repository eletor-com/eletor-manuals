---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: De mest almindelige spørgsmål om valg, konfiguration, diagnostik og service
  af enheder ELETOR.
keywords:
- ELETOR
- FAQ
- ventilationsstyringer
- regulatorer
- ventilatorer
- aktuatorer
- alarmer
- frekvensomformere
- service
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Ofte stillede spørgsmål

FAQ'en er udarbejdet på grundlag af en anonymiseret analyse af faktiske samtaler med brugere og kunder ELETOR. Svarene er generaliseret, så de hjælper i typiske tilfælde og ikke indeholder data om konkrete personer eller installationer.

:::note FAQ'ens omfang

Svarene vedrører typiske tilfælde. Klemmernes betegnelser, funktioner og tilslutningsmåde kan variere mellem modeller og enhedsversioner. Ved tvivl skal dokumentationen for det konkrete produkt anvendes.

:::

:::warning Sikkerhed

Arbejde på den elektriske installation skal udføres i overensstemmelse med enhedens dokumentation og gældende sikkerhedsregler. Arbejde på netspænding bør udføres af en person med de nødvendige kvalifikationer.

:::

## Valg af styring og effekt

### Hvordan vælges en styring til ventilatorer?

Grundlaget for valget er først og fremmest ventilatorernes samlede strøm og ikke kun deres antal.

:::tip Forbered data før valg

Jo mere præcise data om motorerne og anlæggets driftsmåde, desto mere sikkert er valget af styring.

:::

Før valg er det en god idé at forberede:

- antallet af ventilatorer,
- forsyningsspændingen,
- den nominelle effekt eller strøm for hver ventilator,
- oplysning om, hvorvidt alle ventilatorer skal reguleres trinløst,
- oplysning om, hvorvidt ventilatorerne kan opdeles i grupper,
- oplysninger om ekstra enheder, f.eks. varmeflader eller luftindtag.

Styringen bør ikke vælges helt “på grænsen”. Der skal være en passende reserve i forhold til den maksimale belastning.

### Er det nok at summere ventilatorernes effekt i watt?

Effekten kan bruges til et foreløbigt skøn, men det endelige valg bør baseres på enhedernes nominelle strøm og belastningens karakter.

Motoren kan under opstart trække mere strøm end under normal drift. Derfor er to sæt ventilatorer med lignende nominel effekt ikke altid en tilsvarende belastning for styringen.

### Jeg har flere små ventilatorer. Kan jeg tilslutte dem parallelt til én udgang?

Ja, hvis:

- de er beregnet til denne styringsmåde,
- de skal arbejde sammen,
- den samlede belastning ikke overskrider udgangens tilladte strøm,
- tilslutningsmåden er i overensstemmelse med styringens dokumentation.

Ved et større antal ventilatorer bør det overvejes at opdele dem i grupper eller anvende en effektudvidelse.

### Hvornår er en effektudvidelse nødvendig?

En effektudvidelse anvendes, når belastningen overstiger styringens udgangskapacitet, eller når anlægget skal udbygges med et større antal ventilatorer.

Styringen sender da styresignalet, mens den egentlige belastning håndteres af et ekstra modul.

### Kan anlægget senere udbygges med ekstra ventilatorer?

I mange anlæg ja. Oftest anvendes:

- ekstra effektudvidelse,
- ekstra ventilationsgruppe,
- kontaktor til indkobling af den næste gruppe,
- frekvensomformer ved trefasede motorer.

Det er bedst at tage højde for den planlagte udbygning allerede ved det første valg af styring.

### Skal alle ventilatorer reguleres trinløst?

Nej. To typiske løsninger er:

1. alle ventilatorer reguleres trinløst,
2. den første gruppe reguleres trinløst, og de næste grupper tilkobles gradvist, f.eks. via kontaktorer.

Den anden løsning gør det muligt at håndtere et større anlæg uden trinløs regulering af hver enkelt ventilator.

### Jeg har 10 ventilatorer. Har jeg brug for en meget stor styring?

Ikke altid. Der kan anvendes flere styringsmåder:

- opdeling i grupper,
- effektudvidelser,
- kontaktorer,
- frekvensomformer.

Det endelige valg afhænger af ventilatorernes elektriske parametre og af, om alle skal ændre omdrejningstal samtidig.

### Adskiller styring 6 A og 12 A sig kun ved den tilladte belastning?

Man bør ikke antage, at den eneste forskel er strømværdien. De enkelte versioner og generationer af enheder kan variere med hensyn til udstyr eller udførelse.

Ved udskiftning af enheden skal den præcise model og den aktuelle dokumentation kontrolleres.


## Ventilatorer og ventilationsstyring

### Regulerer styringen ventilatorerne trinløst?

I styringer beregnet til trinløs regulering af ventilation ændres ventilatorernes hastighed afhængigt af behovet, som bl.a. bestemmes af temperaturen.

Det skal dog kontrolleres, om den pågældende motortype er egnet til den anvendte reguleringsmetode.

### Hvad betyder setpunktstemperatur?

Setpunktstemperaturen er den værdi, som styringen sammenholder den aktuelle temperaturmåling med.

På dette grundlag øger eller reducerer styringen ventilationsintensiteten i overensstemmelse med de øvrige indstillinger, f.eks. reguleringsbånd, minimums- og maksimumsniveau.

### Hvad betyder minimumsventilationsniveau?

Det er den minimale styreværdi for ventilatoren under automatisk drift.

Indstillingen forhindrer drift under et niveau, hvor ventilatoren kunne arbejde ustabilt eller sikre for lille luftudskiftning.

### Hvad betyder maksimumsventilationsniveau?

Det er den øvre begrænsning af ventilationsstyringens værdi.

For eksempel kan en indstilling under 100% begrænse ventilatorens maksimale omdrejningstal, hvis installationen kræver det.

### Hvad betyder ventilationsbånd?

Ventilationsbåndet angiver det temperaturområde, hvor styringen går fra minimums- til maksimumsventilationsniveau.

Jo smallere båndet er, desto hurtigere reagerer styringen med øget ydelse på en temperaturændring.

### Ventilatoren går efter opstart først op på 100% og sænker først derefter hastigheden. Hvorfor?

Startfunktionen kan være aktiv, og dens opgave er at starte motoren kortvarigt med højere effekt.

Afhængigt af styringsversionen skal indstillingerne relateret til følgende kontrolleres:

- Soft Start-funktionen,
- oprampningstid,
- driftstid ved 100%,
- nedrampningstid.

Hvis funktionen ikke er nødvendig i det pågældende anlæg, kan de relevante parametre ændres i overensstemmelse med enhedens vejledning.

### Hvorfor kan ventilatoren ved start kortvarigt blive kørt med fuld effekt?

En sådan opstart kan hjælpe med sikker igangsætning af ventilatoren samt i anlæg, hvor mekaniske dele kan yde større modstand ved start.

Det er dog ikke nødvendigt i alle anlæg.

### Hvad betyder oprampningstid og nedrampningstid?

**Oprampningstid** angiver, hvordan styringen øges under opstart af ventilatoren.

**Nedrampningstid** angiver, hvordan hastigheden reduceres.

Begge parametre gør det muligt at begrænse pludselige ændringer i omdrejningstal og anlæggets drift.

### Hvorfor kan to identiske styringer starte ventilatorerne forskelligt?

Den hyppigste årsag er forskellige indstillinger.

Det er især værd at sammenligne:

- setpunktstemperaturen,
- ventilationsbåndet,
- minimum og maksimum,
- Soft Start-indstillinger,
- oprampnings- og nedrampningstider,
- konfigurationen af ventilationsgrupper.

### Kan styringen periodisk starte ventilationen uafhængigt af temperaturen?

Afhængigt af modellen findes der en funktion til periodisk udluftning.

Den kan starte ventilationen i et bestemt tidsrum med fastsatte intervaller, selv når temperaturreguleringen ikke kræver øget ventilation.

### Hvad bruges ventilationsgrupper til?

Grupper gør det muligt gradvist at øge anlæggets kapacitet.

For eksempel:

- gruppe 1 reguleres trinløst,
- gruppe 2 starter yderligere ventilatorer,
- næste gruppe starter ved endnu større behov.

Det gør det muligt at styre et stort antal ventilatorer uden trinløs regulering af hver enkelt.

### Kan en ekstra ventilatorgruppe kobles ind via en kontaktor?

Ja. Styringens relæudgang kan styre spolen på en korrekt dimensioneret kontaktor.

Ventilatorbelastningen bør da ikke føres direkte gennem den lille styrekontakt.

### Hvad betyder ventilatorsymbolet eller den gule kontrollampe på styringen?

Afhængigt af modellen viser indikatorerne udgangenes og funktionernes aktuelle tilstand.

Gul indikering kan betyde en aktiv driftsfunktion, f.eks. ventilation, opvarmning eller næste gruppe.

Den præcise betydning skal kontrolleres i vejledningen for den pågældende model.

### Hvad betyder symbolet for manuel tilstand?

Manuel tilstand betyder, at styreværdien er manuelt fastsat af brugeren og ikke i øjeblikket beregnes automatisk på grundlag af temperaturen.

Når testene er afsluttet, skal det sikres, at styringen er sat tilbage i korrekt automatisk tilstand.


## Luftindtag og aktuatorer

### Kan styringen styre luftindtag?

Ja, udvalgte styringer kan samarbejde med drev til luftindtag.

Tilslutningsmåden afhænger af aktuatorens type og dens styremåde.

### Hvilke typer aktuatorer kan anvendes til luftindtag?

I tekniske samtaler forekom oftest to løsninger:

- aktuator styret med analogt signal 0–10 V eller 2–10 V,
- reverserende åbn/luk-aktuator med tilbagemeldingssignal, f.eks. fra et potentiometer.

Før køb skal kompatibiliteten mellem den konkrete model og den eksisterende styring kontrolleres.

### Har aktuatorens forsyningsspænding 24 V eller 230 V betydning for signalet 0–10 V?

Styresignalet og aktuatorens forsyning er separate parametre.

Aktuatoren kan forsynes med en anden spænding end styresignalets spænding. Begge parametre skal være i overensstemmelse med dokumentationen for aktuatoren og styringen.

### Hvad betyder styring 0–10 V?

Styringen sender et analogt spændingssignal, der repræsenterer den ønskede position eller styreniveauet.

I typisk anvendelse betyder en lavere værdi mindre åbning og en højere værdi større åbning, men den faktiske karakteristik skal kontrolleres i aktuatorens dokumentation.

### Hvad er forskellen mellem 0–10 V og 2–10 V?

I begge tilfælde angives positionen med et analogt signal.

I standarden 2–10 V er den nedre del af området forskudt og kan gøre det muligt for enheden at skelne styresignalet fra manglende signal.

Styring og aktuator skal understøtte samme område.

### Hvordan vælges en aktuator i forhold til antallet af luftindtag?

En aktuator bør ikke vælges udelukkende på grundlag af antallet af spjæld.

Der skal tages højde for:

- den krævede kraft eller det krævede moment,
- mekanismens længde og føringsmåde,
- spjældenes modstand,
- slaglængde,
- arbejdshastighed,
- forsyningsspænding,
- styretype,
- krævet feedback.

### Kan én aktuator betjene flere spjæld?

Ja, hvis anlæggets mekanik gør det muligt at forbinde spjældene i en fælles mekanisme, og det krævede moment eller den krævede kraft ikke overstiger aktuatorens kapacitet.

I praksis bestemmes valget af hele mekanismens modstand og ikke kun af antallet af spjæld.

### Kan flere aktuatorer forbindes parallelt og styres med ét signal?

I nogle systemer er det muligt, men dokumentationen for aktuatorerne og den tilladte belastning af styreudgangen skal verificeres.

Ved reverserende drev uden uafhængig feedback kan der også opstå en gradvis positionsafvigelse mellem de enkelte aktuatorer.

### Hvorfor kan flere aktuatorer med tiden indstille sig i forskellige positioner?

Selv identiske motorer kan arbejde med lidt forskellig hastighed på grund af:

- forskellig belastning,
- mekanisk modstand,
- tolerance i motorparametre,
- forskelle i gear.

Derfor er korrekt feedback eller individuel positionskontrol nødvendig, når der kræves præcis synkronisering.

### Kan luftindtag styres proportionalt med ventilationen?

Ja. I korrekt konfigurerede systemer kan luftindtagenes position være knyttet til det aktuelle ventilationsniveau.

På den måde øges åbningen af luftindtagene også, når ventilatorernes kapacitet stiger.

### Kræver aktuator 24 V en separat strømforsyning?

Hvis styringen ikke har en passende forsyningsudgang med den krævede effekt, er der brug for en separat strømforsyning.

Dens effekt skal vælges i forhold til aktuatorens strømforbrug og andre enheder, der forsynes fra samme kilde.

### Kan der anvendes en aktuator fra en anden producent?

Ofte ja, hvis dens elektriske parametre og styremåde er kompatible med styringens udgange.

Før tilslutning skal følgende kontrolleres:

- spænding,
- signaltype,
- ledningsdiagram,
- arbejdsretninger,
- positionssignal,
- tilladt belastning.


## Temperatur- og fugtsensorer

### Hvor tilsluttes temperatursensoren?

Sensoren skal tilsluttes den sensorindgang, som producenten har forudset, den sensorindgang som er angivet i dokumentationen for den pågældende model.

Man bør ikke antage, at klemmernes betegnelser er identiske i alle enhedsversioner.

### Temperatursensoren viser en anden værdi end referencetermometeret. Hvad skal man gøre?

Hvis styringen har en funktion til sensorkalibrering, kan visningen korrigeres efter sammenligning med et pålideligt referencetermometer.

Før kalibreringen ændres, er det en god idé at sikre sig, at:

- begge sensorer befinder sig samme sted,
- målingen har stabiliseret sig,
- sensoren ikke opvarmes af solen eller enheder,
- den ikke befinder sig direkte i strømmen af kold eller varm luft.

### Fugtsensoren viser en forkert værdi. Kan den kalibreres?

Det afhænger af styringsversionen, sensoren og softwaren.

I nogle løsninger kan korrektionen kræve en passende softwarefunktion eller en kompatibel sensortype. Hvis forskellen er stor og gentager sig, skal enhedsversionen kontrolleres, og teknisk support kontaktes.

### Betyder en forkert måling altid, at sensoren er defekt?

Nej.

Årsagen kan også være:

- Forkert placering af sensoren,
- kablet,
- den elektriske forbindelse,
- konfigurationen,
- forkert sensortype,
- behov for kalibrering,
- fugt eller korrosion.


## Alarmer og notifikationer

### Kan en sirene tilsluttes direkte til styringens alarmudgang?

Det bør man ikke antage.

Styringens alarmudgang er normalt en styreudgang eller en relækontakt. Sirenen kan kræve separat strømforsyning samt en alarmcentral.

### Hvorfor anvendes en alarmcentral?

Centralen kan:

- modtage alarmsignaler fra styringer,
- forsyne signalgiveren,
- opretholde driften ved strømsvigt,
- signalere alarm med lyd eller lys,
- sende GSM-notifikationer i versioner, der har denne funktion.

### Kan centralen alarmere om bortfald af styringens forsyning?

Ja, hvis systemet er tilsluttet korrekt.

Løsningen kan registrere ikke kun overskridelse af temperaturen, men også tab af signal fra styringen som følge af bortfald af dens forsyning.

### Hvor indstilles alarmens minimums- og maksimumstemperatur?

I en typisk konfiguration indstilles alarmgrænserne i den styring, der betjener det pågældende kammer eller rum.

Alarmcentralen modtager derefter information om, at styringen har meldt alarm.

### Kræver en GSM-central et SIM-kort?

For at sende opkald og beskeder via mobilnettet kræves et aktivt SIM-kort eller en anden kommunikationsløsning, som er forudset i den pågældende model.

Uden en aktiv forbindelse til mobilnettet vil telefon- og SMS-funktionerne ikke fungere.

### Kan alarmen sende information om, hvilken styring hændelsen kommer fra?

I et korrekt konfigureret system ja.

Centralens indgange kan knyttes til bestemte rum eller styringer, så meddelelsen gør det muligt at identificere alarmens kilde.

### Hvor mange styringer kan tilsluttes én alarmcentral?

Det afhænger af centralens model.

I transskriptionerne forekom centraler med understøttelse af op til otte indgange, men før installationen udføres, skal den aktuelle specifikation for den konkrete enhed kontrolleres.

### Hvilken akkumulator anvendes i alarmcentralen?

I en del af de enheder, der blev omtalt i samtalerne, blev der anvendt en 12 V 7 Ah akkumulator.

Før køb af en erstatning skal mærkningen på den eksisterende akkumulator og centralens specifikation kontrolleres, da andre enhedsversioner kan kræve en anden akkumulator.

### Centralen sender meddelelser om lav spænding. Hvad skal kontrolleres?

Først og fremmest skal følgende kontrolleres:

- akkumulatorens tilstand,
- dens alder,
- akkumulatorforbindelserne,
- tilstedeværelsen af netforsyning,
- funktionen af centralens oplader eller strømforsyning.

En slidt akkumulator kan medføre tilbagevendende meddelelser om lav spænding.

### Hvor ofte skal akkumulatoren i alarmcentralen udskiftes?

Der findes ikke én værdi, der passer til alle forhold.

Akkumulatoren skal testes periodisk, især i installationer hvor alarm under strømsvigt er kritisk. Med alderen falder dens faktiske kapacitet.

### Er sirenen alene tilstrækkelig som sikring?

Sirenen virker kun, hvis nogen kan høre den.

I anlæg, der i perioder er uden opsyn, bør der også anvendes fjernnotifikation og batteribackup.


## Frekvensomformere

### Hvordan vælges en frekvensomformer til ventilatorer?

Det er nødvendigt at kende:

- forsyningsspændingen,
- antal faser,
- effekt og strøm for alle motorer,
- deres tilslutningsmåde,
- driftsforholdene,
- den krævede styremåde.

Frekvensomformeren bør have en passende reserve i forhold til belastningen, især når flere motorer arbejder parallelt.

### Skal frekvensomformeren have nøjagtig samme effekt som summen af motorernes effekt?

En frekvensomformer bør ikke vælges udelukkende på grundlag af en simpel summering af effekten, og man bør ikke vælge en enhed, der arbejder præcis på grænsen af sine parametre.

Der skal tages højde for de nominelle strømme, belastningens karakter og anbefalingerne fra frekvensomformerens producent.

### Frekvensomformeren stoppede ventilatorerne og viste en fejl. Hvad skal man gøre?

Det vigtigste er at notere den fulde fejlkode før reset.

:::tip Tag et billede af displayet

Hvis situationen tillader det, skal der tages et billede af displayet før reset. Den fulde fejlkode gør diagnosen væsentligt lettere.

:::

Kun begyndelsen af meddelelsen er ofte ikke nok til at fastslå årsagen. Den fulde kode gør det muligt bl.a. at skelne mellem:

- overbelastning,
- overstrøm,
- overophedning,
- forkert spænding,
- andre drevfejl.

### Kan man bare nulstille frekvensomformerens fejl?

Reset kan genoprette driften, men fjerner ikke årsagen til alarmen.

Efter hændelsen skal fejlkoden kontrolleres, og årsagen fastlægges, før anlægget sættes i længerevarende drift igen.

### Frekvensomformeren arbejder i et støvet rum. Skal den rengøres?

Ja.

Støv og aflejringer på kølepladen eller køleventilatoren kan forringe varmeafledningen og føre til overophedning af frekvensomformeren.

Rengøring skal udføres i overensstemmelse med producentens vejledning efter sikker frakobling af forsyningen.

### Hvad kan forårsage overophedning af frekvensomformeren?

De hyppigste årsager er:

- tilsmudsede køledele,
- blokeret luftgennemstrømning,
- for høj omgivelsestemperatur,
- overbelastning,
- defekt køleventilator,
- forkert montering.

### Kan forhøjet netspænding udløse alarm på frekvensomformeren?

Ja. Frekvensomformere overvåger forsyningskredsens spænding og kan melde fejl, når det tilladte niveau overskrides.

Hvis problemet gentager sig, skal installationen og forsyningskvaliteten kontrolleres.


## Fejl og diagnostik

### Styringen virker, men displayet viser ingenting. Hvad kan årsagen være?

Mulige årsager omfatter bl.a.:

- defekt display,
- problem med kontrastindstilling i ældre løsninger,
- defekt forbindelse,
- korrosion,
- defekt hovedkort.

Hvis enheden ikke har været anvendt i lang tid eller har arbejdet i et fugtigt miljø, er det også værd at kontrollere kortets tilstand.

### Styringen har efter flere års manglende brug problemer med displayet. Hvorfor?

Længere tids stilstand i et fugtigt eller aggressivt miljø kan føre til:

- oxidation af stikforbindelser,
- korrosion,
- forringede kontakter,
- skader på elektroniske komponenter.

I så fald er det værd at udføre et fuldt eftersyn frem for at udskifte dele uden forudgående diagnose.

### Styringen er sodet efter en overspænding. Betyder det, at kortet skal udskiftes?

Ikke altid.

En beskyttelseskomponent kan blive beskadiget og efterlade meget aflejring, selv om resten af kortet kan repareres.

Hvis laminatet derimod er forkullet, brændt, eller banerne er beskadiget, kan reparationen være urentabel eller ikke holdbar.

### Hvad kan beskadige flere styringer på én gang?

Hvis mange enheder svigter samtidig, skal forsyningsinstallationen kontrolleres.

En af de mulige årsager er et problem med nullederen, som i en trefaset installation kan føre til, at der opstår forkerte spændinger på enfasede belastninger.

Der kan også forekomme overspændinger fra nettet eller en generator.

### Hvad skal man gøre efter en fejl relateret til overspænding?

Før en repareret eller ny styring tilsluttes, skal årsagen til problemet fastlægges.

:::danger Tilslut ikke enheden igen uden at kontrollere installationen

Hvis årsagen til fejlen var forkert spænding, beskadiget nulleder eller overspænding, kan den reparerede eller nye styring blive beskadiget igen.

:::

### Hvad er et overspændingsbeskyttelseselement på kortet?

I elektroniske enheder anvendes komponenter, der begrænser overspænding, f.eks. varistorer.

Deres opgave er at optage en del af overspændingens energi og beskytte de efterfølgende kredsløb. Efter en kraftig hændelse kan en sådan komponent blive permanent beskadiget.

### Kan enheden startes efter fjernelse af den brændte beskyttelseskomponent?

Dette bør ikke betragtes som en normal reparation.

Efter fjernelse af beskyttelsen kan enheden miste beskyttelsen mod en ny overspænding. Sådanne handlinger må kun udføres som en bevidst serviceprocedure af en person med de nødvendige kvalifikationer og efter fjernelse af den oprindelige fejls årsag.

### Er det værd at reparere en styring, der har været oversvømmet eller er stærkt korroderet?

Det afhænger af skadernes omfang.

Overfladisk korrosion og enkelte skader kan ofte udbedres. Hvis korrosionen har angrebet baner, stikforbindelser og mange komponenter, kan reparationen være tidskrævende, usikker og økonomisk ubegrundet.

### Kan højtryksvask af enheden beskadige styringen?

Ja.

Elektronik bør ikke udsættes for direkte påvirkning af vand eller rengøringsmiddel, hvis kapslingen og monteringsmåden ikke er beregnet til det.

Fugt, der trænger ind, kan føre til korrosion og senere fejl, som er vanskelige at diagnosticere.

### Hvorfor kan fejl efter vandindtrængning vende tilbage efter reparation?

Korrosion kan også udvikle sig på steder, der ikke er synlige ved den første kontrol.

Beskadigede vias, baner og forbindelser kan virke under testen og senere igen miste kontakt.

Derfor kan service anbefale udskiftning i stedet for yderligere reparationer ved et stærkt korroderet kort.

### Enheden virker nogle gange og andre gange ikke. Hvor skal man begynde?

Det er værd at samle følgende før kontakt med service:

- den præcise model,
- beskrivelse af symptomet,
- tidspunktet for forekomsten,
- værdierne vist på displayet,
- alarm- eller fejlkoden,
- oplysninger om de seneste ændringer i installationen,
- et foto af indersiden og klemmerne, hvis det kan gøres sikkert.

Jo mere præcis beskrivelsen er, desto lettere er diagnosen.


## Service og reparationer

### Hvad skal sendes til service, hvis styringen er defekt?

Det er bedst at sende et komplet sæt, som gør det muligt at genskabe problemet.

Forsendelsen skal vedlægges en kort beskrivelse af:

- hvad der ikke virker,
- hvornår problemet opstår,
- om fejlen er permanent eller periodisk,
- om der før fejlen var overspænding, vandindtrængning eller en anden hændelse,
- de oplysninger, der er nødvendige for kontakt og returnering af enheden.

:::note Oplysninger til serviceanmodning

Kontakt- og forsendelsesoplysninger skal gives direkte til service. Offentliggør dem ikke i åbne henvendelser eller offentlige materialer.

:::

### Skal hele styringen sendes eller kun kortet?

Det afhænger af fejlen.

Ved problemer med display, knapper, forsyning eller tvetydig adfærd er det bedst at sende hele sættet, der er nødvendigt for at genskabe symptomet.

Ved en på forhånd aftalt reparation af et konkret modul kan service kun bede om kortet.

### Reparerer ELETOR styringer i stedet for straks at udskifte dem?

Transskriptionerne viser, at enhederne først diagnosticeres.

Hvis reparation er mulig og giver mening, udskiftes beskadigede komponenter eller moduler. Ved alvorlig skade kan service foreslå udskiftning af kortet eller hele enheden.

### Hvad sker der, hvis et beskadiget kort ikke kan repareres?

Det er muligt at udskifte det beskadigede modul med et nyt, hvis den passende del er tilgængelig og kompatibel med enheden.

Ved ældre enheder bør service først bekræfte versionskompatibiliteten.

### Kan det betale sig straks at købe et nyt kort efter en overspænding?

Ikke altid.

Hvis skaden vedrører et beskyttelseselement eller en mindre del af kredsløbet, kan reparation være berettiget. Det er værd først at udføre en diagnose.

### Kan service også kontrollere displayet og knapperne?

Ja, hvis elementerne leveres sammen med enheden eller modulet.

Det er især nyttigt, når det ikke vides, om problemet sidder på hovedkortet eller i brugerpanelet.

### Er det altid værd at forsøge at redde en stærkt korroderet styring?

Nej.

Hvis udgifterne til diagnose og reparation stiger, og driftssikkerheden efter reparation fortsat er usikker, kan udskiftning være mere fornuftig.

Det gælder især enheder, som anlæggets ventilation afhænger af.

### Hvordan kan servicediagnosen fremskyndes?

Vedlæg en præcis beskrivelse af symptomet i stedet for blot konstateringen “virker ikke”.

Følgende er også nyttige:

- fotos,
- fejlkode,
- beskrivelse af installationen,
- typen af tilsluttede belastninger,
- oplysning om overspænding eller strømsvigt,
- oplysning om vandindtrængning eller vask af enheden.


## Installation og kabelføring

### Hvordan tilsluttes enheder til relæklemmerne C og NO?

C og NO er typiske betegnelser for en relækontakt:

- C — fælles kontakt,
- NO — normalt åben kontakt.

Anvendelsesmåden afhænger af enheden og installationsdiagrammet. Kontakten kan f.eks. bruges til at styre kontaktorens spole, men dens tilladte parametre må ikke overskrides.

:::warning Elektrisk arbejde

Tilslutninger til netspænding bør udføres af en person med de nødvendige kvalifikationer i overensstemmelse med diagrammet for den konkrete enhed.

:::

### Kan relæudgangen direkte forsyne en stor ventilator?

Normalt er dette ikke korrekt anvendelse af en lille styreudgang.

Til større belastninger anvendes en kontaktor, et effektrelæ eller et dedikeret effektmodul.

### Hvad bruges kontaktorens klemmer A1 og A2 til?

Det er klemmerne til kontaktorens spole.

Når den korrekte spænding tilføres spolen, skifter kontaktoren tilstand på sine effektkontakter.

Spolespændingen skal være i overensstemmelse med installationsprojektet og kontaktorens dokumentation.

### Kan der monteres ekstra apparater inde i styringens kapsling?

Kun hvis konstruktionen af den konkrete kapsling tillader det, og det ikke forringer:

- beskyttelsesgraden,
- isoleringen,
- kølingen,
- sikkerheden,
- serviceadgangen.

Alle nye åbninger bør udføres på en måde, der bevarer den krævede tæthed.

### Er ekstra afbrydere til ventilatorer nyttige?

De kan lette service og muliggøre uafhængig frakobling af de enkelte ventilatorer.

Udførelsen skal dog tage højde for elektriske beskyttelser og må ikke skabe farlige tilstande for styringen.

### Kan styreledninger føres sammen med effektledninger?

Det bør undgås at føre følsomme signalledninger parallelt og meget tæt på højstrømsledninger, især over lange strækninger.

Kravene afhænger af signaltypen og det elektromagnetiske miljø.

### Hvilket kabel skal anvendes til netværksforbindelser og PoE-enheder?

I de omtalte installationer blev parsnoet kabel i kategori 5e angivet som minimum.

Hvis kablet føres i et miljø med forhøjet niveau af forstyrrelser eller risiko for elektrostatiske ladninger, kan det være berettiget at anvende et passende afskærmet kabel og et korrekt jordingssystem.

### Kræver PoE et krydset kabel?

I typiske installationer anvendes en standard lige forbindelse.

Kravene for netværksenheden og den anvendte PoE-strømforsyning skal dog altid kontrolleres.


## Drift og vedligeholdelse

### Hvordan begrænses risikoen for fejl på styringer i landbrugsbygninger?

Det vigtigste er at begrænse påvirkningen fra:

- fugt,
- ammoniak og aggressivt miljø,
- støv,
- direkte vask med vand,
- overspændinger,
- forkert forsyning.

Det er også værd periodisk at kontrollere tilstanden af kabler, forbindelser og kapslinger.

### Bør elektroniske enheder rengøres regelmæssigt?

Ja, især enheder udstyret med køleplader, ventilatorer og ventilationsåbninger.

Akkumuleret støv forringer kølingen.

Rengøring skal udføres efter frakobling af forsyningen og i overensstemmelse med enhedens vejledning.

### Kan det betale sig at udføre et eftersyn af styringen efter nogle års drift?

Ja, især under vanskelige miljøforhold.

Eftersynet kan omfatte:

- vurdering af stikforbindelsernes tilstand,
- kontrol for spor af fugt og korrosion,
- kontrol af kølekomponenter,
- kontrol af panel og knapper,
- test af sensorer,
- kontrol af akkumulatorer i alarmsystemer.

### Hvad er værd at notere efter en fejl er opstået?

Det mest nyttige er:

- den fulde meddelelse,
- fejlkoden,
- tidspunktet for hændelsen,
- temperaturen,
- ventilationsstatus,
- oplysning om strømsvigt,
- oplysning om generatorens drift,
- et foto af displayet eller enheden.

Enheden bør ikke nulstilles, før koden er noteret, hvis situationen gør det muligt at gøre det sikkert.

### Er det værd at have en alarm uafhængig af ventilationsstyringen?

Ja, især hvor ventilationssvigt hurtigt kan føre til farlige forhold.

En uafhængig central med egen akkumulator og fjernnotifikation giver et ekstra lag af beskyttelse.

### Hvilke oplysninger bør forberedes før kontakt med teknisk support?

Det er bedst at forberede:

1. den præcise enhedsmodel,
2. beskrivelse af installationen,
3. antal og parametre for tilsluttede enheder,
4. de aktuelle indstillinger relateret til problemet,
5. det præcise symptom,
6. den fulde fejl- eller alarmkode,
7. fotos af enheden og typeskiltene,
8. oplysning om de seneste ændringer i installationen.

Det gør det muligt at forkorte diagnosen betydeligt.


## Vigtig bemærkning om ældre enheder

Navne, klemmebetegnelser og tilgængelige funktioner kan variere mellem enhedsversioner produceret i forskellige år.

Hvis enheden er flere eller mange år gammel, skal følgende bekræftes, før instruktioner fra en nyere model anvendes:

- den præcise enhedsbetegnelse,
- kortversionen,
- typen af display,
- softwareversionen,
- klemmediagrammet.

:::warning Ældre enhedsversioner

Antag ikke fuld kompatibilitet alene på grundlag af kapslingens lignende udseende. Bekræft den præcise model og enhedsversion, før et diagram eller en vejledning bruges.

:::


## Kontakt med teknisk support

Hvis FAQ'en ikke løser problemet, skal følgende forberedes før kontakt:

- et foto af styringen,
- et foto af forbrugerens typeskilt,
- motorernes eller aktuatorernes parametre,
- tilslutningsdiagrammet,
- en præcis beskrivelse af den ønskede driftsmåde.

Takket være dette kan valg af enhed eller diagnose af problemet udføres på grundlag af installationens faktiske parametre og ikke antagelser.
