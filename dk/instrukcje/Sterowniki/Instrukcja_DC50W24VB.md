---
sidebar_position: 4
title: Vejledning Strømforsyning DC50W24VB
description: Nødstrømforsyning DC50W24VB  til luftindtagssystem.
keywords:
- eletor IC-AC
- styring af luftindtag
- klimastyring
- ventilationsstyring til svinestalde
- mikroklimastyring
- styring til svinestalde
- ventilation i svinestalde
- styring til opdrætsstalde
---


# Strømforsyning DC50W24VB

Nødstrømforsyning med funktion til automatisk og manuel åbning af luftindtag og luftudtag. Anvendes til at sikre husdyrenes sikkerhed i tilfælde af strømsvigt eller fejl i styringen. Når enheden registrerer en uregelmæssighed, afgiver den en alarm og åbner hejseanordningerne til det indstillede niveau.

## Parametre og egenskaber: 
-  Omskifter til valg af driftstilstand: 
    - MANUAL
    - AUTO.
-  Drejeknap til indstilling af luftindtagenes åbningsgrad.
-  Understøttede standarder:
    - 0-10, 2-10, 10-0, 10-2.
-  Mulighed for invertering af styresignalet.
-  Alarmudgange NO og NC.
-  Signalering af strømsvigt.
-  Overvågning af styrespænding 2-10V.
-  Kortslutningsovervågning af udgangene 24VDC.
-  Kortslutningsovervågning af udgangene 0-10V.
-  2 indgang 0-10V.
-  2 udgange 0-10V.
-  Elektronisk beskyttelse af indgange, udgange og 24V-linjen.
-  Akkumulatorbatteri 24V 4.0 Ah.
-  Tæt kapsling IP65.
-  Forsyningsspænding 85~264VAC 47~63Hz.

# Installation af styringen  
:::danger 
Under installation af enheden skal strømforsyningen ubetinget afbrydes, da spændingen på visse komponenter er farlig for liv og helbred. Det anbefales at overlade installationen til en kvalificeret person.
:::

## Valg af monteringssted  

Monteringsstedet skal vælges hensigtsmæssigt under hensyntagen til, at enheden skal være let tilgængelig for bemyndigede personer, men utilgængelig for dyr og børn. Der skal også tages hensyn til klimaforholdene, dvs. enheden skal arbejde i temperaturområdet fra -10°C til 40 °C på et sted uden direkte sollys. Der skal være fri luftcirkulation omkring enheden.

# Montering  

Enheden kan arbejde under aggressive klimaforhold. En korrekt monteret enhed er modstandsdygtig over for skadelige miljøpåvirkninger.

### Ved montering skal følgende iagttages: 
 - låget skal fastspændes med alle skruer,
 - kablerne, der anvendes til tilslutning af enheden, skal have et rundt tværsnit,
 - efter tilslutning af kablet skal kabelforskruningerne spændes, så kablet tætnes og fastholdes; det anbefales at anvende silikone,
 - ubrugte gennemføringer (kabelforskruninger) skal blændes af,
 - kapslingens underdel fastgøres til en plan væg med 4 ekspansionsdyvler.


# Elektrisk tilslutning  

:::danger 
Før systemet tilsluttes, skal det sikres, at strømforsyningen er afbrudt!
:::

Når enheden er skruet op, skal frontpanelet tages af. Dette gøres ved at trække fladkablet ud af stikket mærket P1. Kablerne føres gennem gummikabelforskruningerne, hvorefter de kan tilsluttes. Tilslutningen skal udføres i overensstemmelse med beskrivelsen.

![Tilslutning](./img/DC50W24VB.png)

**Forsyning 230V AC:** tilsluttes strømforsyningen (fordelingstavlen). Der skal anvendes en automatsikring (type ”S” B6) samt overspændingsafledere i klasse ”C”. Enheden kan forsynes over et bredt spændingsområde fra 85V til 264V og et frekvensområde fra 47 til 63Hz uden at påvirke enhedens drift.  

**Stikkene In1 og In2** skal tilsluttes styringen for at tilføre styresignalet til hejseanordningernes systemer. Enheden kan understøtte to styringer eller én styring med separate sektioner for luftindtag og luftudtag (klemmerne I1 og I2 skal forbindes med en bro).  

**Stikket ALARM** tilsluttes alarmcentralen afhængigt af systemet – sluttet (NO og C), åben (NC og C). Alarmen aktiveres i følgende tilfælde:  •enhedens forsyningsspænding er bortfaldet,  •styresignalet 2-10V er bortfaldet på mindst én af indgangene,  •udgangssignalet er kortsluttet, eller dets værdi afviger fra den målte,  •der er opstået kortslutning på +24V-skinnen, som forsyner hejseanordningerne.  

**Stikkene Ouput 1 og Ouput 2** tilsluttes aktuatoren (hejseanordningen) på den måde, som den pågældende enhed kræver; tilslutningsbeskrivelsen skal findes i vejledningen til den pågældende aktuator (hejseanordning).  

**Driftstilstandsomskifter S1** den relevante driftstilstand skal vælges afhængigt af den anvendte aktuator (hejseanordning). Som standard står omskifterne 1,2,3,4,5,6 i positionen off – drift 2-10V.
 
| Kanal 1 | Kanal 2| Funktion |
|------|------|----------|
| 1 – off | 4 – off | Driftstilstand med signalområde 2-10V, styrespænding under 1,5V udløser en alarm.   |
| 1 – on| 4 – on  | Driftstilstand med signalområde 0-10V, ingen alarmreaktion ved et signal under 1,5V.   |
| 2 – off | 5 – off  | Proportional driftstilstand, udgangssignaler i området 0-10V eller 2-10V.  |
| 2 – on | 5 – on  | Omvendt driftstilstand, udgangssignaler i området 10-0V eller 10-2V.   |
| 3 – off | 6 – off  | Invertering af indgangen deaktiveret.  |
| 3 – on | 6 – on   | Invertering af indgangen aktiveret.   |

# Funktionsprincip  

Nødstrømforsyningen forsyner under normal drift aktuatorerne (hejseanordningerne) 24V og oplader eller vedligeholdelsesoplader akkumulatorerne, som leverer strøm i tilfælde af strømsvigt.  Omskifteren AUTO/MANUAL bestemmer enhedens driftstilstand.  

**Tilstanden MANUAL** muliggør direkte styring af aktuatorerne (hejseanordningerne) via drejeknappen på enhedens panel.  

**Tilstanden AUTO** – den grundlæggende driftstilstand, overfører styresignalet fra indgangen til udgangen med passende behandling afhængigt af indstillingerne på omskifteren ”S1” og overvåger indgangssignalets niveau.  Hvis der registreres en uregelmæssighed på en given indgang, sender enheden signalet fra drejeknappen på frontpanelet til sin udgang.  Alarmrelæet aktiveres i følgende tilfælde:  •for lavt indgangssignal (Uin < 1,5V) – omskifter ”S1” 1-off, 4-off,  •kortslutning af udgangssignalet til stel eller 24V,  •manglende forsyningsspænding,  •kortslutning af spændingen 24V.

## Betjening 

Brugeren vælger tilstanden MANUAL med omskifteren og indstiller med drejeknappen luftindtagenes åbningsgrad efter behov – aktuatorerne arbejder i overensstemmelse med drejeknappens indstilling. Efter afsluttet indstilling af luftindtagene vælges tilstanden AUTO med omskifteren, og enheden efterlades – luftindtagene indstilles til det niveau, som ventilationsstyringen kræver. I en nødsituation indstilles luftindtagene i overensstemmelse med drejeknappens indstilling.  

## Frontpanel 

| MENU                       | Beskrivelse | 
|:---:                       |:---|
|![Tilslutning](./img/paneldcw50.png) |**Indikatorlampe POWER** – angiver, at forsyningsspænding er til stede, og at akkumulatorerne oplades.  1.**Indikatorlampe CHECK** – lyser konstant i automatisk tilstand, når signalet fra styringen overføres til udgangen, og blinker, når signalet fra drejeknappen sendes til udgangen.  2.**OUT 1** – angiver uregelmæssigheder i kanal 1.  3.**OUT 2** – angiver uregelmæssigheder i kanal 2.  4.**AUTO** – automatisk driftstilstand.  5.**MANUAL** – manuel driftstilstand.  6.**Drejeknap 0%-100%** - valg af luftindtagenes åbningsgrad.| 

# F ejl- og advarselsmeddelelser

Fejlmeddelelserne bruges til at informere brugeren om uregelmæssigheder i enhedens drift. Nedenfor er de mulige fejlmeddelelser angivet:
 -  Indikatorlampe POWER – lyser ikke grønt – ingen netforsyning.
 -  Indikatorlampe CHECK – blinker gult – signalet fra potentiometeret sendes til udgangene.
 -  Indikatorlampe OUT 1 – lyser rødt - registrering af en uregelmæssighed (manglende styresignal, kortslutning på udgangen eller kortslutning på 24VDC-skinnen) i den første kanal.
 -  Indikatorlampe OUT 2 – lyser rødt - registrering af en uregelmæssighed (manglende styresignal, kortslutning på udgangen eller kortslutning på 24VDC-skinnen) i den anden kanal.

# Bemærkninger og advarsler  

:::danger 
Under installation af enheden skal strømforsyningen ubetinget afbrydes, da spændingen på visse komponenter er farlig for liv og helbred. Det anbefales at overlade installationen til en kvalificeret person.
:::

 - For at undgå problemer med enhedens drift skal vejledningen læses, før installation og brug påbegyndes. Det er ikke tilladt at foretage indgreb i konstruktionen eller selv udføre reparationer. Dette gælder navnlig ændringer af elementer og komponenter.
 - Vedligeholdelse og service skal udføres af autoriseret personale (installatør eller producentens serviceafdeling). I staldbygninger med mekanisk ventilation kræves et alarmsystem. 
 - Producenten af enheden er ikke ansvarlig for skader forårsaget af forkert installation, forkert programmering af funktioner, følger af hændelige begivenheder samt eksterne faktorer. Enhedens parametre skal indstilles i overensstemmelse med forholdene i staldrummet.Disse indstillinger er individuelle og afhænger af husdyrholderens beslutning. 
 - Producenten af enheden forbeholder sig ret til at ændre enhedens konstruktion og software.
Enheden indeholder et akkumulatorbatteri; akkumulatorerne må ikke aflades for meget, da dette kan beskadige batteriet. 
Kortslutning af batteriets poler kan medføre brand.  


:::caution
![alternativ tekst](./img/trash.svg) Når produktet ikke længere anvendes, må det ikke bortskaffes sammen med usorteret husholdningsaffald, men skal bortskaffes i overensstemmelse med gældende bestemmelser (EU's WEEE-direktiver 2012/19/EU).  Produktet er fremstillet i overensstemmelse med RoHS-kravene (EU-direktiv 2011/65/EU).
:::

<!-- \newpage -->
# Tekniske data for styringen  

|Parameter                        |	BESKRIVELSE      |
|:-----------                    |:---------- |
|Forsyningsspænding, vekselspænding|	85~264VAC 47~63Hz|
|Forsyningsspænding, jævnspænding|	120~370VDC|
|Udgangsspænding|	27,6VDC|
|Maksimal udgangsstrøm|	1,8A|
|Virkningsgrad|	85%|
|Maksimal strøm på styreudgangene 0-10V|	30mA|
|Maksimal strøm på ALARM-udgangen (kontakten)|	3A|
|Overspændingsbeskyttelse af indgange og udgange|	JA|
|Kortslutningsbeskyttelse|	Automatisk |
|Akkumulatorbatteri|	4Ah 24V|
|Driftstemperaturområde|	-10 +40oC|
|Enhedens mål|	20x15x8 cm|
|Kapslingens tæthedsklasse|	IP65|

:::info
Styringen IC-AC leveres med:
 - ekspansionsdyvler - 	4 stk., 
 - akkumulatorer 12V 4Ah - 	2 stk., 
 - kabelforskruning PG13,5 -	1 stk.,
 - kabelforskruning PG11 -	3 stk., 
 - kabelforskruning PG9 -	3 stk.
:::

