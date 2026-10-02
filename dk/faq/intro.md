---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: De hyppigste spørgsmål om valg, konfiguration, diagnosticering og service
  af enheder fra ELETOR.
keywords:
- ELETOR
- FAQ
- ventilationsstyreenheder
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

FAQ'en er udarbejdet på grundlag af en anonymiseret analyse af faktiske samtaler med brugere og kunder hos ELETOR. Svarene er generaliseret, så de hjælper i typiske situationer og ikke indeholder oplysninger om konkrete personer eller installationer.

:::note FAQ'ens omfang

Svarene vedrører typiske situationer. Klemmebetegnelser, funktioner og tilslutningsmetoder kan variere mellem modeller og versioner af enhederne. Ved tvivl skal dokumentationen for det konkrete produkt anvendes.

:::

:::warning Sikkerhed

Arbejde på den elektriske installation skal udføres i overensstemmelse med enhedens dokumentation og gældende sikkerhedsregler. Arbejde med netspænding bør udføres af en person med de nødvendige kvalifikationer.

:::

## Valg af styreenhed og effekt

### Hvordan vælges en styreenhed til ventilatorer?

Valget baseres først og fremmest på ventilatorernes samlede strøm og ikke udelukkende på deres antal.

:::tip Indsaml oplysninger før valget

Jo mere præcise oplysningerne om motorerne og installationens driftsmåde er, desto sikrere bliver valget af styreenhed.

:::

Før valget bør følgende oplysninger indsamles:

- antal ventilatorer,
- forsyningsspænding,
- mærkeeffekt eller mærkestrøm for hver ventilator,
- oplysning om, hvorvidt alle ventilatorer skal reguleres trinløst,
- oplysning om, hvorvidt ventilatorerne kan opdeles i grupper,
- oplysninger om yderligere enheder, f.eks. varmeapparater eller luftindtag.

Styreenheden bør ikke dimensioneres præcis til grænsen. Der skal sikres en passende margin i forhold til den maksimale belastning.

### Er det tilstrækkeligt at lægge ventilatorernes effekt i watt sammen?

Effekten kan anvendes til et indledende skøn, men det endelige valg bør baseres på enhedernes mærkestrøm og belastningens karakter.

En motor kan under opstart trække mere strøm end under normal drift. Derfor udgør to sæt ventilatorer med tilsvarende mærkeeffekt ikke altid en tilsvarende belastning for styreenheden.

### Jeg har flere små ventilatorer. Kan de tilsluttes parallelt til én udgang?

Ja, hvis:

- de er beregnet til denne styringsmetode,
- de skal køre sammen,
- summen af belastningerne ikke overstiger udgangens tilladte strøm,
- tilslutningsmetoden er i overensstemmelse med styreenhedens dokumentation.

Ved et større antal ventilatorer bør det overvejes at opdele dem i grupper eller anvende en effektudvidelse.

### Hvornår er en effektudvidelse nødvendig?

En effektudvidelse anvendes, når belastningen overstiger kapaciteten for styreenhedens udgang, eller når installationen skal udvides med flere ventilatorer.

Styreenheden sender da styresignalet, mens den egentlige belastning håndteres af et ekstra modul.

### Kan installationen senere udvides med yderligere ventilatorer?

I mange installationer er det muligt. Oftest anvendes:

- en ekstra effektudvidelse,
- en ekstra ventilationsgruppe,
- en kontaktor, der indkobler den næste gruppe,
- en frekvensomformer ved trefasede motorer.

Det er bedst at tage højde for den planlagte udvidelse allerede ved det første valg af styreenhed.

### Skal alle ventilatorer reguleres trinløst?

Nej. Der er to typiske løsninger:

1. alle ventilatorer reguleres trinløst,
2. den første gruppe reguleres trinløst, og de efterfølgende grupper indkobles trinvist, f.eks. via kontaktorer.

Den anden løsning gør det muligt at styre en større installation uden trinløs regulering af hver enkelt ventilator.

### Jeg har 10 ventilatorer. Har jeg brug for en meget stor styreenhed?

Ikke altid. Der kan anvendes flere styringsmetoder:

- opdeling i grupper,
- effektudvidelser,
- kontaktorer,
- en frekvensomformer.

Det endelige valg afhænger af ventilatorernes elektriske parametre, og af om de alle skal ændre omdrejningstal samtidigt.

### Er den tilladte belastning den eneste forskel mellem styreenhederne 6 A og 12 A?

Det bør ikke antages, at strømværdien er den eneste forskel. De enkelte versioner og generationer af enhederne kan have forskelligt udstyr eller forskellig udførelse.

Ved udskiftning af en enhed skal den præcise model og den aktuelle dokumentation kontrolleres.


## Ventilatorer og ventilationsstyring

### Regulerer styreenheden ventilatorerne trinløst?

I styreenheder beregnet til trinløs ventilationsregulering ændres ventilatorernes hastighed afhængigt af behovet, som blandt andet bestemmes af temperaturen.

Det skal dog kontrolleres, om den pågældende motortype er egnet til den anvendte reguleringsmetode.

### Hvad betyder temperaturens setpunkt?

Temperaturens setpunkt er den værdi, som styreenheden sammenholder den aktuelle temperaturmåling med.

På dette grundlag øger eller reducerer styreenheden ventilationens intensitet i overensstemmelse med de øvrige indstillinger, f.eks. reguleringsbåndet samt minimums- og maksimumsniveauet.

### Hvad betyder minimumsniveauet for ventilation?

Det er den mindste styreværdi for ventilatoren under automatisk drift.

Indstillingen forhindrer drift under det niveau, hvor ventilatoren kan køre ustabilt eller give et for lavt luftskifte.

### Hvad betyder maksimumsniveauet for ventilation?

Det er den øvre grænse for ventilationens styreværdi.

Eksempelvis kan indstilling af en værdi under 100% begrænse ventilatorens maksimale omdrejningstal, hvis installationen kræver det.

### Hvad betyder ventilationsbåndet?

Ventilationsbåndet angiver det temperaturområde, hvor styreenheden går fra minimums- til maksimumsniveauet for ventilation.

Jo smallere båndet er, desto hurtigere reagerer styringen på en temperaturændring ved at øge kapaciteten.

### Efter opstart går ventilatoren først op på 100% og sænker først hastigheden senere. Hvorfor?

En opstartsfunktion kan være aktiv, hvis formål er kortvarigt at starte motoren med højere effekt.

Afhængigt af styreenhedens version skal indstillingerne for følgende kontrolleres:

- Soft Start-funktionen,
- opstartstiden,
- driftstiden ved 100%,
- nedløbstiden.

Hvis funktionen ikke er nødvendig i den pågældende installation, kan de relevante parametre ændres i overensstemmelse med enhedens vejledning.

### Hvorfor kan ventilatoren ved opstart kortvarigt blive startet med fuld effekt?

En sådan opstart kan hjælpe med at sikre en pålidelig start af ventilatoren og være nyttig i installationer, hvor mekaniske dele kan yde større modstand under opstart.

Det er dog ikke nødvendigt i alle installationer.

### Hvad betyder opstartstid og nedløbstid?

**Opstartstiden** angiver, hvordan styreværdien øges under opstart af ventilatoren.

**Nedløbstiden** angiver, hvordan hastigheden reduceres.

Begge parametre gør det muligt at begrænse pludselige ændringer i omdrejningstal og installationens drift.

### Hvorfor kan to identiske styreenheder starte ventilatorerne forskelligt?

Den hyppigste årsag er forskellige indstillinger.

Følgende bør især sammenlignes:

- temperaturens setpunkt,
- ventilationsbåndet,
- minimum og maksimum,
- Soft Start-indstillingerne,
- opstarts- og nedløbstiderne,
- konfigurationen af ventilationsgrupperne.

### Kan styreenheden starte ventilationen periodisk uafhængigt af temperaturen?

Afhængigt af modellen er der en funktion til periodisk udluftning.

Den kan starte ventilationen i et bestemt tidsrum med fastlagte intervaller, selv når temperaturreguleringen ikke kræver øget ventilation.

### Hvad bruges ventilationsgrupper til?

Grupperne gør det muligt at øge installationens kapacitet trinvist.

Eksempelvis:

- gruppe 1 reguleres trinløst,
- gruppe 2 starter yderligere ventilatorer,
- den næste gruppe starter ved et endnu større behov.

Det gør det muligt at styre et stort antal ventilatorer uden trinløs regulering af hver enkelt.

### Kan en ekstra ventilatorgruppe indkobles via en kontaktor?

Ja. Styreenhedens relæudgang kan styre spolen i en korrekt dimensioneret kontaktor.

Ventilatorernes belastningsstrøm bør da ikke føres direkte gennem den lille styrekontakt.

### Hvad betyder ventilatorsymbolet eller den gule kontrollampe på styreenheden?

Afhængigt af modellen angiver kontrollamperne den aktuelle tilstand for udgange og funktioner.

En gul indikation kan betyde, at en driftsfunktion er aktiv, f.eks. ventilation, opvarmning eller en yderligere gruppe.

Den præcise betydning skal kontrolleres i vejledningen til den pågældende model.

### Hvad betyder symbolet for manuel tilstand?

Manuel tilstand betyder, at styreværdien er tvangsstyret af brugeren og på det pågældende tidspunkt ikke beregnes automatisk ud fra temperaturen.

Efter afslutning af testene skal det sikres, at styreenheden er sat tilbage i den korrekte automatiske tilstand.


## Luftindtag og aktuatorer

### Kan styreenheden styre luftindtag?

Ja, udvalgte styreenheder kan arbejde sammen med drev til luftindtag.

Tilslutningsmetoden afhænger af aktuatortypen og dens styringsmetode.

### Hvilke typer aktuatorer kan anvendes til luftindtag?

I de tekniske samtaler forekom oftest to løsninger:

- en aktuator styret af et analogt signal 0–10 V eller 2–10 V,
- en reversibel aktuator med åbn/luk-styring og et tilbagekoblingssignal, f.eks. fra et potentiometer.

Før køb skal den konkrete models kompatibilitet med den eksisterende styreenhed kontrolleres.

### Har aktuatorens forsyningsspænding 24 V eller 230 V betydning for signalet 0–10 V?

Styresignalet og aktuatorens strømforsyning er separate parametre.

Aktuatoren kan forsynes med en anden spænding end styresignalets spænding. Begge parametre skal være i overensstemmelse med aktuatorens og styreenhedens dokumentation.

### Hvad betyder styring med 0–10 V?

Styreenheden sender et analogt spændingssignal, der repræsenterer den ønskede position eller det ønskede styringsniveau.

Ved typisk anvendelse betyder en lavere værdi en mindre åbning og en højere værdi en større åbning, men den faktiske karakteristik skal kontrolleres i aktuatorens dokumentation.

### Hvad er forskellen mellem 0–10 V og 2–10 V?

I begge tilfælde angives positionen med et analogt signal.

I standarden 2–10 V er den nedre del af området forskudt, hvilket kan gøre det muligt for enheden at skelne mellem et styresignal og fraværet af dette.

Styreenheden og aktuatoren skal understøtte et kompatibelt område.

### Hvordan vælges en aktuator ud fra antallet af luftindtag?

Aktuatoren bør ikke vælges udelukkende ud fra antallet af spjæld.

Der skal tages højde for:

- den nødvendige kraft eller det nødvendige drejningsmoment,
- mekanismens længde og føring,
- spjældenes modstand,
- slaglængden,
- bevægelseshastigheden,
- forsyningsspændingen,
- styringstypen,
- den nødvendige tilbagekobling.

### Kan én aktuator betjene mange spjæld?

Ja, hvis installationens mekanik gør det muligt at forbinde spjældene med et fælles system, og det nødvendige drejningsmoment eller den nødvendige kraft ikke overstiger aktuatorens kapacitet.

I praksis bestemmes valget af modstanden i hele mekanismen og ikke alene af antallet af spjæld.

### Kan flere aktuatorer parallelforbindes og styres med ét signal?

I nogle systemer er det muligt, men aktuatorernes dokumentation og styreudgangens tilladte belastning skal kontrolleres.

Ved reversible drev uden uafhængig tilbagekobling kan de enkelte aktuatorers positioner desuden gradvist afvige fra hinanden.

### Hvorfor kan flere aktuatorer med tiden indstille sig i forskellige positioner?

Selv identiske motorer kan køre med lidt forskellig hastighed på grund af:

- forskellig belastning,
- mekanisk modstand,
- tolerancer i motorparametrene,
- forskelle i gearene.

Hvis der kræves præcis synkronisering, er passende tilbagekobling eller individuel positionskontrol derfor nødvendig.

### Kan luftindtagene styres proportionalt med ventilationen?

Ja. I korrekt konfigurerede systemer kan luftindtagenes position være knyttet til det aktuelle ventilationsniveau.

Dermed øges luftindtagenes åbning også, når ventilatorernes kapacitet øges.

### Kræver aktuatoren 24 V en separat strømforsyning?

Hvis styreenheden ikke har en passende forsyningsudgang med den nødvendige effekt, kræves en separat strømforsyning.

Dens effekt skal dimensioneres efter strømforbruget for aktuatoren og de øvrige enheder, der forsynes fra samme kilde.

### Kan der anvendes en aktuator fra en anden producent?

Ofte ja, hvis dens elektriske parametre og styringsmetode er kompatible med styreenhedens udgange.

Før tilslutning skal følgende kontrolleres:

- spænding,
- signaltype,
- ledningsdiagram,
- bevægelsesretninger,
- positionssignal,
- tilladt belastning.


## Temperatur- og fugtighedssensorer

### Hvor skal temperatursensoren tilsluttes?

Sensoren skal tilsluttes den sensorindgang, som producenten har beregnet til formålet, den sensorindgang, der er angivet i dokumentationen for den pågældende model.

Det bør ikke antages, at klemmebetegnelserne er identiske i alle versioner af enhederne.

### Temperatursensoren viser en anden værdi end referencetermometeret. Hvad skal der gøres?

Hvis styreenheden har en funktion til sensorkalibrering, kan visningen korrigeres efter sammenligning med et pålideligt referencetermometer.

Før kalibreringen ændres, bør det sikres, at:

- begge sensorer befinder sig samme sted,
- målingen er stabiliseret,
- sensoren ikke opvarmes af solen eller enheder,
- den ikke befinder sig direkte i en strøm af kold eller varm luft.

### Fugtighedssensoren viser en forkert værdi. Kan den kalibreres?

Det afhænger af styreenhedens, sensorens og softwarens version.

I nogle løsninger kan korrektion kræve en passende softwarefunktion eller en kompatibel sensortype. Hvis forskellen er stor og gentager sig, skal enhedens version kontrolleres, og teknisk support kontaktes.

### Betyder en forkert måling altid, at sensoren er defekt?

Nej.

Årsagen kan også være:

- forkert placering af sensoren,
- kablet,
- den elektriske forbindelse,
- konfigurationen,
- en forkert sensortype,
- behov for kalibrering,
- fugt eller korrosion.


## Alarmer og meddelelser

### Kan en sirene tilsluttes direkte til styreenhedens alarmudgang?

Det bør ikke antages.

Styreenhedens alarmudgang er normalt en styreudgang eller en relækontakt. Sirenen kan kræve separat strømforsyning og en alarmcentral.

### Hvorfor anvendes en alarmcentral?

Centralen kan:

- modtage alarmsignaler fra styreenheder,
- forsyne en alarmgiver med strøm,
- opretholde driften ved strømsvigt,
- signalere en alarm med lyd eller lys,
- sende GSM-meddelelser i versioner, der har denne funktion.

### Kan centralen udløse en alarm ved strømsvigt i styreenheden?

Ja, hvis systemet er korrekt tilsluttet.

Løsningen kan ikke blot registrere overskridelse af temperaturen, men også tab af signal fra styreenheden som følge af strømsvigt i denne.

### Hvor indstilles den minimale og maksimale alarmtemperatur?

I en typisk konfiguration indstilles alarmgrænserne i den styreenhed, der betjener det pågældende kammer eller rum.

Alarmcentralen modtager derefter information om, at styreenheden har udløst en alarm.

### Kræver GSM-centralen et SIM-kort?

For at foretage opkald og sende meddelelser via mobilnettet kræves et aktivt SIM-kort eller en anden kommunikationsløsning, som den pågældende model understøtter.

Uden en aktiv forbindelse til mobilnettet fungerer telefon- og SMS-funktionerne ikke.

### Kan alarmen sende information om, hvilken styreenhed hændelsen stammer fra?

Ja, i et korrekt konfigureret system.

Centralens indgange kan tildeles bestemte rum eller styreenheder, så meddelelsen gør det muligt at identificere alarmens kilde.

### Hvor mange styreenheder kan tilsluttes én alarmcentral?

Det afhænger af centralens model.

I transskriptionerne forekom centraler, der understøtter op til otte indgange, men før installationen udføres, skal den aktuelle specifikation for den konkrete enhed kontrolleres.

### Hvilket batteri anvendes i alarmcentralen?

I nogle af de enheder, der blev omtalt i samtalerne, blev der anvendt et batteri på 12 V 7 Ah.

Før køb af et erstatningsbatteri skal mærkningen på det eksisterende batteri og centralens specifikation kontrolleres, da andre versioner af enhederne kan kræve et andet batteri.

### Centralen sender meddelelser om lav spænding. Hvad skal kontrolleres?

Først skal følgende kontrolleres:

- batteriets tilstand,
- dets alder,
- batteriets forbindelser,
- om netforsyningen er til stede,
- funktionen af centralens oplader eller strømforsyning.

Et slidt batteri kan medføre tilbagevendende meddelelser om lav spænding.

### Hvor ofte skal batteriet i alarmcentralen udskiftes?

Der findes ikke ét interval, der passer til alle forhold.

Batteriet skal testes regelmæssigt, især i installationer, hvor alarmen ved strømsvigt er kritisk. Dets faktiske kapacitet falder med alderen.

### Er en sirene alene tilstrækkelig som sikring?

En sirene har kun effekt, når nogen kan høre den.

I bygninger, der i perioder er uden opsyn, bør der også anvendes fjernmeddelelser og batteribackup.


## Frekvensomformere

### Hvordan vælges en frekvensomformer til ventilatorer?

Følgende skal være kendt:

- forsyningsspændingen,
- antallet af faser,
- effekt og strøm for alle motorer,
- deres tilslutningsmetode,
- driftsforholdene,
- den krævede styringsmetode.

Frekvensomformeren bør have en passende margin i forhold til belastningen, især når flere motorer kører parallelt.

### Skal frekvensomformeren have præcis samme effekt som summen af motorernes effekt?

Frekvensomformeren bør ikke vælges udelukkende ved simpel sammenlægning af effekten, og der bør ikke vælges en enhed, der arbejder præcis ved grænsen for sine parametre.

Der skal tages højde for mærkestrømmene, belastningens karakter og frekvensomformerproducentens anbefalinger.

### Frekvensomformeren har stoppet ventilatorerne og viser en fejl. Hvad skal der gøres?

Det vigtigste er at notere hele fejlkoden før nulstilling.

:::tip Tag et billede af skærmen

Hvis situationen tillader det, skal der tages et billede af displayet før nulstilling. Den fulde fejlkode gør diagnosticeringen væsentligt lettere.

:::

Begyndelsen af meddelelsen alene er ofte ikke tilstrækkelig til at fastslå årsagen. Den fulde kode gør det muligt at skelne mellem blandt andet:

- overbelastning,
- overstrøm,
- overophedning,
- forkert spænding,
- andre fejl i drevet.

### Kan frekvensomformerens fejl blot nulstilles?

En nulstilling kan genoprette driften, men fjerner ikke årsagen til alarmen.

Efter hændelsen skal fejlkoden kontrolleres og årsagen fastslås, før installationen igen sættes i langvarig drift.

### Frekvensomformeren arbejder i et støvet rum. Skal den rengøres?

Ja.

Støv og aflejringer på køleprofilen eller køleventilatoren kan forringe varmeafledningen og medføre overophedning af frekvensomformeren.

Rengøring skal udføres i overensstemmelse med producentens vejledning, efter at strømforsyningen er afbrudt på sikker vis.

### Hvad kan medføre overophedning af frekvensomformeren?

De hyppigste årsager er:

- tilsmudsede kølekomponenter,
- blokeret luftgennemstrømning,
- for høj omgivelsestemperatur,
- overbelastning,
- en defekt køleventilator,
- forkert montering.

### Kan forhøjet netspænding udløse en alarm i frekvensomformeren?

Ja. Frekvensomformere overvåger spændingen i forsyningskredsløbet og kan melde en fejl, hvis det tilladte niveau overskrides.

Hvis problemet gentager sig, skal installationen og strømforsyningens kvalitet kontrolleres.


## Fejl og diagnosticering

### Styreenheden fungerer, men displayet viser intet. Hvad kan årsagen være?

Mulige årsager omfatter blandt andet:

- et defekt display,
- et problem med kontrastindstillingen i ældre løsninger,
- en beskadiget forbindelse,
- korrosion,
- et defekt hovedprintkort.

Hvis enheden ikke har været anvendt i lang tid eller har arbejdet i et fugtigt miljø, bør printkortets tilstand også kontrolleres.

### Efter flere år uden brug har styreenheden problemer med displayet. Hvorfor?

Langvarig stilstand i et fugtigt eller aggressivt miljø kan medføre:

- oxidation af stikforbindelser,
- korrosion,
- forringelse af kontakter,
- skader på elektroniske komponenter.

I så fald bør der udføres et fuldt eftersyn frem for at udskifte komponenter uden forudgående diagnosticering.

### Styreenheden er tilsodet efter en overspænding. Betyder det, at printkortet skal udskiftes?

Ikke altid.

En beskyttelseskomponent kan blive beskadiget og efterlade store mængder aflejringer, selv om resten af printkortet kan repareres.

Hvis laminatet derimod er forkullet eller brændt igennem, eller printbanerne er beskadiget, kan reparationen være urentabel eller ikke holdbar.

### Hvad kan beskadige flere styreenheder samtidigt?

Hvis mange enheder svigter på samme tidspunkt, skal forsyningsinstallationen kontrolleres.

En mulig årsag er et problem med nullederen, som i en trefaset installation kan medføre forkerte spændinger på enfasede forbrugere.

Overspændinger fra elnettet eller generatoren er også mulige.

### Hvad skal der gøres efter en fejl forårsaget af overspænding?

Før en repareret eller ny styreenhed tilsluttes, skal årsagen til problemet fastslås.

:::danger Tilslut ikke enheden igen uden at kontrollere installationen

Hvis fejlen skyldtes forkert spænding, en beskadiget nulleder eller overspænding, kan den reparerede eller nye styreenhed blive beskadiget igen.

:::

### Hvad er en overspændingsbeskyttelseskomponent på printkortet?

I elektroniske enheder anvendes komponenter, der begrænser overspændinger, f.eks. varistorer.

Deres opgave er at optage en del af overspændingens energi og beskytte de efterfølgende kredsløb. Efter en kraftig hændelse kan en sådan komponent blive permanent beskadiget.

### Kan enheden startes efter fjernelse af en afbrændt beskyttelseskomponent?

Dette bør ikke betragtes som en normal reparation.

Efter fjernelse af beskyttelsen kan enheden miste sin beskyttelse mod en ny overspænding. Sådanne indgreb må kun udføres som en bevidst serviceprocedure af en person med de nødvendige kvalifikationer, og efter at årsagen til den oprindelige fejl er fjernet.

### Styreenheden har været udsat for vandindtrængning eller er kraftigt korroderet. Kan det betale sig at reparere den?

Det afhænger af skadernes omfang.

Overfladisk korrosion og enkelte skader kan ofte afhjælpes. Hvis korrosionen har angrebet printbaner, stikforbindelser og mange komponenter, kan reparationen være tidskrævende, usikker og økonomisk ubegrundet.

### Kan højtryksrensning af enheden beskadige styreenheden?

Ja.

Elektronikken bør ikke udsættes direkte for vand eller rengøringsmiddel, hvis kapslingen og monteringsmåden ikke er beregnet til det.

Fugt, der trænger ind, kan medføre korrosion og senere fejl, som er vanskelige at diagnosticere.

### Hvorfor kan fejl efter vandindtrængning vende tilbage efter reparation?

Korrosion kan også udvikle sig på steder, som ikke er synlige ved den første kontrol.

Beskadigede gennempletteringer, printbaner og forbindelser kan fungere under testen og senere igen miste kontakten.

Ved et kraftigt korroderet printkort kan serviceafdelingen derfor anbefale udskiftning frem for yderligere reparationer.

### Enheden fungerer nogle gange og andre gange ikke. Hvor skal man begynde?

Før kontakt til serviceafdelingen bør følgende indsamles:

- den præcise model,
- en beskrivelse af symptomet,
- tidspunktet for, hvornår det opstår,
- værdierne, der vises på skærmen,
- alarm- eller fejlkoden,
- oplysninger om de seneste ændringer i installationen,
- et billede af indvendige dele og klemmer, hvis det kan tages sikkert.

Jo mere præcis beskrivelsen er, desto lettere bliver diagnosticeringen.


## Service og reparationer

### Hvad skal sendes til serviceafdelingen, hvis styreenheden er defekt?

Det er bedst at sende et komplet sæt, som gør det muligt at genskabe problemet.

Forsendelsen skal ledsages af en kort beskrivelse af:

- hvad der ikke fungerer,
- hvornår problemet opstår,
- om fejlen er konstant eller periodisk,
- om der før fejlen forekom overspænding, vandindtrængning eller en anden hændelse,
- de oplysninger, der er nødvendige for kontakt og returnering af enheden.

:::note Oplysninger til serviceanmodningen

Kontakt- og forsendelsesoplysninger skal sendes direkte til serviceafdelingen. De må ikke offentliggøres i åbne henvendelser eller offentligt materiale.

:::

### Skal hele styreenheden sendes eller kun printkortet?

Det afhænger af fejlen.

Ved problemer med display, knapper, strømforsyning eller uklar adfærd er det bedst at sende hele det sæt, der er nødvendigt for at genskabe symptomet.

Ved en på forhånd aftalt reparation af et bestemt modul kan serviceafdelingen bede om kun at få printkortet.

### Reparerer ELETOR styreenheder frem for straks at udskifte dem?

Det fremgår af transskriptionerne, at enhederne først diagnosticeres.

Hvis en reparation er mulig og hensigtsmæssig, udskiftes de beskadigede komponenter eller moduler. Ved alvorlige skader kan serviceafdelingen foreslå udskiftning af printkortet eller hele enheden.

### Hvad sker der, hvis det beskadigede printkort ikke kan repareres?

Det beskadigede modul kan udskiftes med et nyt, hvis den relevante del er tilgængelig og kompatibel med enheden.

Ved ældre enheder bør serviceafdelingen først bekræfte, at versionerne er kompatible.

### Kan det betale sig straks at købe et nyt printkort efter en overspænding?

Ikke altid.

Hvis skaden vedrører en beskyttelseskomponent eller en mindre del af kredsløbet, kan en reparation være hensigtsmæssig. Der bør først udføres diagnosticering.

### Kan serviceafdelingen også kontrollere displayet og knapperne?

Ja, hvis delene indsendes sammen med enheden eller modulet.

Det er især nyttigt, når det ikke vides, om problemet ligger på hovedprintkortet eller i betjeningspanelet.

### Kan det altid betale sig at redde en kraftigt korroderet styreenhed?

Nej.

Hvis omkostningerne til diagnosticering og reparation stiger, og driftssikkerheden efter reparation fortsat er usikker, kan udskiftning være mere fornuftig.

Det gælder især enheder, som bygningens ventilation afhænger af.

### Hvordan kan servicediagnosticeringen fremskyndes?

Vedlæg en præcis beskrivelse af symptomet frem for blot angivelsen »fungerer ikke«.

Følgende er også nyttigt:

- billeder,
- fejlkoden,
- en beskrivelse af installationen,
- typen af tilsluttede forbrugere,
- oplysning om overspænding eller strømsvigt,
- oplysning om vandindtrængning eller vask af enheden.


## Installation og kabelføring

### Hvordan tilsluttes enheder til relæklemmerne C og NO?

C og NO er typiske betegnelser for en relækontakt:

- C — fælles kontakt,
- NO — normalt åben kontakt.

Anvendelsen afhænger af enheden og installationsdiagrammet. Kontakten kan f.eks. anvendes til at styre en kontaktorspole, men dens tilladte parametre må ikke overskrides.

:::warning Elarbejde

Tilslutninger til netspænding bør udføres af en person med de nødvendige kvalifikationer i overensstemmelse med diagrammet for den konkrete enhed.

:::

### Kan en relæudgang forsyne en stor ventilator direkte?

Det er normalt ikke en korrekt anvendelse af en lille styreudgang.

Til større belastninger anvendes en kontaktor, et effektrelæ eller et dedikeret udgangsmodul.

### Hvad bruges kontaktorens klemmer A1 og A2 til?

Det er klemmerne til kontaktorens spole.

Når den korrekte spænding påtrykkes spolen, ændrer kontaktoren tilstanden for sine hovedkontakter.

Spolespændingen skal være i overensstemmelse med installationsprojektet og kontaktorens dokumentation.

### Kan der monteres yderligere apparater inde i styreenhedens kapsling?

Kun hvis den konkrete kapslings konstruktion tillader det, og det ikke forringer:

- kapslingsklassen,
- isoleringen,
- kølingen,
- sikkerheden,
- serviceadgangen.

Alle nye huller bør udføres, så den nødvendige tæthed bevares.

### Er ekstra afbrydere til ventilatorerne nyttige?

De kan lette servicearbejdet og gøre det muligt at afbryde de enkelte ventilatorer uafhængigt.

Udførelsen skal dog tage højde for elektriske beskyttelsesforanstaltninger og må ikke medføre farlige tilstande i styreenheden.

### Kan styrekabler føres sammen med effektkabler?

Følsomme signalkabler bør ikke føres parallelt med og meget tæt på kabler til høj effekt, især ikke over lange strækninger.

Kravene afhænger af signaltypen og det elektromagnetiske miljø.

### Hvilket kabel skal anvendes til netværksforbindelser og PoE-enheder?

I de omtalte installationer blev parsnoet kabel i kategori 5e angivet som minimum.

Hvis kablet føres i et miljø med et forhøjet støjniveau eller risiko for elektrostatiske ladninger, kan det være hensigtsmæssigt at anvende et passende skærmet kabel og et korrekt jordingssystem.

### Kræves der et krydset kabel til PoE?

I typiske installationer anvendes en standardforbindelse med lige gennemkobling.

Kravene til netværksenheden og den anvendte PoE-strømforsyning skal dog altid kontrolleres.


## Drift og vedligeholdelse

### Hvordan begrænses risikoen for fejl i styreenheder i driftsbygninger?

Det vigtigste er at begrænse påvirkningen fra:

- fugt,
- ammoniak og aggressive miljøer,
- støv,
- direkte vask med vand,
- overspændinger,
- forkert strømforsyning.

Tilstanden af kabler, forbindelser og kapslinger bør også kontrolleres regelmæssigt.

### Bør elektroniske enheder rengøres regelmæssigt?

Ja, især enheder med køleprofiler, ventilatorer og ventilationsåbninger.

Ophobet støv forringer kølingen.

Rengøring skal udføres efter afbrydelse af strømforsyningen og i overensstemmelse med enhedens vejledning.

### Bør styreenheden efterses efter flere års drift?

Ja, især under krævende miljøforhold.

Eftersynet kan omfatte:

- vurdering af stikforbindelsernes tilstand,
- kontrol for spor af fugt og korrosion,
- kontrol af kølekomponenter,
- kontrol af panel og knapper,
- test af sensorer,
- kontrol af batterier i alarmsystemer.

### Hvad bør noteres efter en fejl?

Det mest nyttige er:

- den fulde meddelelse,
- fejlkoden,
- tidspunktet for hændelsen,
- temperaturen,
- ventilationens tilstand,
- oplysning om strømsvigt,
- oplysning om generatorens drift,
- et billede af skærmen eller enheden.

Enheden bør ikke nulstilles, før koden er noteret, hvis situationen tillader, at dette gøres sikkert.

### Er det hensigtsmæssigt at have en alarm, som er uafhængig af ventilationsstyreenheden?

Ja, især hvor ventilationssvigt hurtigt kan medføre farlige forhold.

En uafhængig central med eget batteri og fjernmeddelelser giver et ekstra sikkerhedslag.

### Hvilke oplysninger skal forberedes før kontakt til teknisk support?

Følgende bør forberedes:

1. enhedens præcise model,
2. en beskrivelse af installationen,
3. antal og parametre for de tilsluttede enheder,
4. de aktuelle indstillinger, der vedrører problemet,
5. det præcise symptom,
6. den fulde fejl- eller alarmkode,
7. billeder af enheden og typeskiltene,
8. oplysning om de seneste ændringer i installationen.

Det kan forkorte diagnosticeringen betydeligt.


## Vigtig bemærkning om ældre enheder

Navne, klemmebetegnelser og tilgængelige funktioner kan variere mellem versioner af enheder, der er produceret i forskellige år.

Hvis enheden er flere år eller over ti år gammel, skal følgende bekræftes, før vejledningen til en nyere model anvendes:

- enhedens præcise betegnelse,
- printkortets version,
- displaytypen,
- softwareversionen,
- klemmediagrammet.

:::warning Ældre versioner af enheder

Fuld kompatibilitet må ikke antages alene på grundlag af et lignende udseende af kapslingen. Før et diagram eller en vejledning anvendes, skal enhedens præcise model og version bekræftes.

:::


## Kontakt til teknisk support

Hvis FAQ'en ikke løser problemet, skal følgende forberedes før kontakt:

- et billede af styreenheden,
- et billede af forbrugerens typeskilt,
- motorernes eller aktuatorernes parametre,
- et tilslutningsdiagram,
- en præcis beskrivelse af den ønskede funktionsmåde.

Dermed kan valg af enhed eller diagnosticering af problemet udføres på grundlag af installationens faktiske parametre frem for antagelser.
