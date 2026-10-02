---
sidebar_position: 3
title: Vejledning SC-12
description: Klimastyring til staldbygninger med en tilladt udgangsstrøm op til 12A
keywords:
- eletor sc-12
- ventilationsstyring
- klimastyring
- ventilationsstyring til svinestald
- mikroklimastyring
- styring til svinestalde
- ventilation i svinestald
- styring til opdrætsstalde
---

# Styring SC-12

Mikroprocessorbaseret klimastyring fra serien SPEED CONTROL. Enhedens alsidighed sikres af systemets mange indgange/udgange samt intuitiv software på polsk og engelsk. Ud over grundlæggende indstillinger for temperaturer, udluftning, supplerende opvarmning, min./maks. ventilationsniveauer og alarmer muliggør styringens program test og lagring af kalibreringen af aktuatorer, der samarbejder med styringen.

**Parametre og egenskaber:** 
- Ventilation i gruppe I: 
  - maks. strøm for udgangen med trinløs regulering 12A,
  - termisk beskyttelse af systemet, 
  - blød opstart af ventilationen – blødstart,
  - bypassrelæ ved fuld udstyring, 
  - kalibrering af minimumsomdrejningstal, 
  - energispareprogram med et system af spjæld, der åbnes på forhånd.
- Ventilation i gruppe II, isoleret kontakt op til 6A.
- Supplerende opvarmning, isoleret kontakt op til 6A
- Alarmudgange NO og NC: 
  - signalering af strømsvigt,
  - signalering af overskridelse af min.- eller maks.-temperaturgrænsen,
  - indbygget akustisk signalgiver.
- Uafhængige 3 udgange 0..10V:
  - samarbejde med udvidelsesmoduler,
  - styring af spjældsystemet, 
  - regulering af opvarmning med variabel ydelse.**
- To analoge indgange til temperaturmåling.
- Digital port til temperaturmåling (op til 4 sensorer).
- To funktionsrelæudgange (valgfrit):
  - samarbejde med lineære aktuatorer, 
  - III og IV ventilationsgruppe
- To analoge indgange 0-10V.
- Forsyning til potentiometer DC 10V.
- Ekstra forsyning DC 12V.
- Mulighed for samarbejde med en computer op til 1200m.
- Tæt kabinet IP65.
- Forsyningsspænding 230VAC 50Hz.
- Systemets effektforbrug < 10V

# Installation af styringen
:::danger 
 Under installation af enheden skal strømforsyningen ubetinget afbrydes, da spændingen på visse komponenter er farlig for liv og helbred. Det anbefales at lade en kvalificeret person udføre installationen.  Denne handling er farlig
:::

## Valg af monteringssted
Monteringsstedet skal vælges hensigtsmæssigt under hensyntagen til, at autoriserede personer skal have let adgang til enheden, mens den skal være utilgængelig for dyr og børn. Der skal også tages hensyn til klimaforholdene, dvs. enheden skal fungere i temperaturområdet -10°C til 40 °C på et sted uden direkte sollys. Der skal være fri luftcirkulation omkring enheden. Enheden omfatter en temperatursensor.  

### Følgende regler gælder for montering af temperatursensoren:
 - sensoren bør ikke monteres på et sted uden luftcirkulation eller i direkte sollys,
 - sensoren bør ikke monteres på bygningens bærende væg (ydervæg),
 - undgå nærhed til varmeafgivende enheder såsom radiatorer og lamper,
 - sensoren må ikke placeres direkte ved døre og ventilationsåbninger,
 - sensoren må ikke placeres på steder, der er tilgængelige for dyr,
 - det anbefales at føre sensorens tilslutningskabel væk fra forsyningskabler.

# Montering
Enheden kan fungere under aggressive klimaforhold. En korrekt monteret styring og temperatursensor er modstandsdygtig over for skadelige miljøpåvirkninger.  

### Ved montering skal der tages hensyn til følgende:
 - før sammenskruning skal dækslets pakning kontrolleres,
 - dækslet skal fastspændes med alle skruer,
 - de kabler, der anvendes til tilslutning af styringen, skal være runde,
 - efter tilslutning af kablet skal kabelforskruningerne spændes, så kablet tætnes og fastholdes; det anbefales at anvende silikone,
 - ubrugte gennemføringer (kabelforskruninger) skal lukkes med blindpropper,
 - styringen (kabinettets nederste del) fastgøres til en plan væg med 4 ekspansionsdyvler.

# Elektrisk tilslutning
:::danger 
 Før systemet tilsluttes, skal det sikres, at strømforsyningen er afbrudt!
Denne handling er farlig
:::

Før styringen tilsluttes, skal dækslet skrues løs og fjernes. Kablerne føres gennem gummikabelforskruningerne, hvorefter de kan tilsluttes. Styringens klemmer er vist på nedenstående figur.

![Tilslutning ](./img/sc-12.png)

**AC-tilslutningen 230V** forbindes til strømforsyningen (fordelingstavlen). Der skal anvendes en automatsikring 1P-B6 samt overspændingsafledere af typen T1 T2. Ved tilslutning af flere enheder er det god praksis at fordele styringerne på forskellige »faser« (L1, L2, L3) for at opnå en jævn belastning af forsyningsledningen.

**FAN-tilslutningen** skal forbindes direkte til ventilatoren; ved styring af flere ventilatorer må den samlede belastning ikke overstige 6A, og hver ventilator skal sikres separat. PE og N må ikke føres fra strømforsyningen (fordelingstavlen); de skal ubetinget forbindes til styringens tilslutninger.

**FAN-tilslutningen 2** kan anvendes til tilslutning af ventilatorer i gruppe 2 eller overrislingssystemer. Udgangen er isoleret, og kontaktens maksimale strøm er 6A (en ekstern automatsikring af typen 1P-B6 er påkrævet ved direkte styring af belastningen); kontakten sluttes, når den målte temperatur er højere end summen af den indstillede temperatur og ventilationsbåndet.

**HOT-tilslutningen** kan anvendes til tilslutning af en varmeblæser. Udgangen er isoleret, og kontaktens maksimale strøm er 6A (en ekstern automatsikring 1P-B6 er påkrævet ved direkte styring af belastningen); kontakten sluttes, når den målte temperatur falder under indstillingen.

**ALARM-tilslutningen** har isolerede udgange NC, C og NO til tilslutning til en alarmcentral. Alarmen aktiveres i følgende tilfælde:
    - temperaturen er for lav eller for høj,
    - styringen eller temperatursensoren er beskadiget,
    - styringens forsyningsspænding er bortfaldet,
    - styringen fungerer ikke korrekt (f.eks. overophedning af styringen)
Nedenstående figur viser, hvordan ventilatoren forbindes til alarmcentralen.

![Alarmtilslutning](./img/alarmsc-s.png)

**Tilslutningerne FUNC1 og FUNC2** anvendes til tilslutning af en hejseanordning til åbning af luftindtag, baseret på en motor med højre-/venstreløb. Relæet FUNC1 tilkobler strømmen til aktuatoren, og FUNC2 omskifter motorens omdrejningsretning. Eksempel på et tilslutningsdiagram for hejseanordningen (en ekstern automatsikring 1P-B6 er påkrævet):
Når hejsefunktionen deaktiveres, fungerer udgangene FUNC1 og FUNC2 som kontakter for henholdsvis ventilationsgruppe 3 og 4.

![Tilslutning af hejseanordningen](./img/Sc-12fan.png)

**Tilslutningen 12V** er beregnet til forsyning af eksterne sensorer.

**Tilslutningen V1 0-10V** anvendes til tilslutning af effektudvidelsesmoduler. Spændingen på denne klemme er proportional med ventilationsniveauet.

**Tilslutningen V2 0-10V** anvendes til tilslutning af en aktuator, der åbner luftindtagsspjældene.

**Tilslutningen V3 0-10V** anvendes til tilslutning af et varmesystem med trinløst regulerbar ydelse. Spændingen på denne udgang stiger proportionalt med temperaturfaldet fra og med temperaturen for supplerende opvarmning.

**Tilslutningen 10V** anvendes til forsyning af hejseanordningens potentiometer eller andre systemer af typen 0-10V.

**Tilslutningen SENS1 (SENS2)** forbindes til 1 temperatursensor TS3 eller TS5; polariteten er uden betydning. Ved samtidig tilslutning af 2 sensorer beregnes gennemsnittet af de målte temperaturer. Det er god praksis at holde målekablerne på afstand af forsyningskablerne.

**Tilslutningen 1-WIRE** kan anvendes til tilslutning af et større antal digitale temperatursensorer, maksimalt 4, der forbindes parallelt (korrekt polaritet skal overholdes). Den maksimale længde af kablet, der forbinder sensorerne, er 150m (længden påvirker ikke temperaturmålingen); det anbefales at anvende et skærmet kabel.

**Tilslutningen RS-485** kan anvendes til opbygning af ventilationssystemer samt kommunikation med en PC.

**Tilslutningen IN1 0-10** anvendes til indføring af et tilbagemeldingssignal fra luftindtagssystemet – det angiver luftindtagenes aktuelle position.

**Tilslutningen IN2 0-10** anvendes til at forbinde styringen med andre sensorer, f.eks. fugtighedssensorer, CO2 eller til drift af styringen som effektudvidelse.

# Funktionsprincip
Styringens hovedopgave er at opretholde temperaturen i staldrummet på det niveau, som husdyrholderen har fastlagt. Det skal huskes, at styringen kun er et værktøj, der skal hjælpe med at sikre optimale klimaforhold i staldrummet. Den overordnede rolle i denne proces varetages dog af husdyrholderen, som skal tilpasse enhedens indstillinger til de skiftende klimaforhold udendørs og frem for alt til dyrenes behov i staldbygningen samt overvåge enhedens driftstilstand ved hjælp af alarmcentralen.

## Første opstart af styringen
:::danger 
 Ved første opstart af styringen skal motorens forbudte driftsbånd ubetinget indstilles.

:::
Styringen samarbejder med ventilatorer baseret på en enfaset asynkronmotor med et maksimalt samlet strømforbrug på 12A. Efter tilslutning af de valgte ventilatorer skal brugeren tilpasse dem til samarbejdet med styringen. Med andre ord er det nødvendigt at indstille ventilatorens minimale driftsniveau (omdrejningstal). Denne funktion kaldes »Forbudt bånd« og indstilles én gang af brugeren under »Avancerede indstillinger«. For at udføre denne handling korrekt anbefales hjælp fra en anden person, som løbende kan observere ventilatorens adfærd, mens den første person indstiller værdien for »Forbudt bånd« (fabriksindstillingen for denne værdi er 0). Hvis det forbudte bånd ikke indstilles, kan det medføre forkert drift af enheden. Værdien for »Forbudt bånd« kan betragtes som korrekt, når det tryk, ventilatoren skaber, begynder at løfte ventilationsskorstenens spjæld en smule. Indstillingen af »Forbudt bånd« skal udføres igen, når den ventilator, der er tilsluttet styringen, udskiftes.

## Periodisk udluftning
Udluftning er en funktion, som udføres af styringen, og som aktiveres, når temperaturen i rummet falder under den indstillede temperatur. Denne funktion sikrer dyrene en cyklisk tilførsel af frisk luft. I menuen Udluftning findes 3 parametre:
- **»Driftstid«** - angiver, hvor mange minutter ventilatoren skal være tilkoblet;
- **»Pausetid«** - angiver ventilatorens stilstandstid;
- **»Udluftningsniveau«** - angiver ventilationsydelsen i »Driftstid«.

Alle ovennævnte parametre indstilles af brugeren. 

### Ved indstilling af udluftningsparametrene skal følgende regler huskes:
- udluftning aktiveres udelukkende, når temperaturen i svinestalden falder under den indstillede temperatur,
- udluftningens grundlæggende funktion er at sikre dyrene en cyklisk tilførsel af frisk luft, ikke at opretholde den indstillede temperatur i rummet,
- det anbefales at udlufte rummene kortvarigt, men ofte,
- lange udluftningsperioder bør undgås, da de kan føre til for store temperaturudsving,
- de indstillede parametre skal ubetinget tilpasses dyrenes adfærd og forholdene både i og uden for rummet.

## Enhedens funktion
Styringen regulerer ventilationen trinløst fra **»Min.1« til »Maks.1«** i området fra **»Indstillet temperatur«** til summen af **»Indstillet temperatur«** og **»Ventilationsbånd 1gr.«**. Over dette område tilkobles ventilationsgruppe 2, og gruppe 1 ændrer niveauet til **»Min.2«**; ved yderligere temperaturstigning øges ventilationen til **»Maks.2«** ved slutningen af området for **»Ventilationsbånd 2 gr.«**. Hvis **»Ventilationsbånd 2 gr.«** er indstillet til nul, og ventilationen kører på **»Maks.1«**, tilkobles ventilationsgruppe 2, og yderligere temperaturstigning medfører ikke flere ændringer af ventilationen (den stiplede del af diagrammet). Hvis temperaturen i rummet falder under **»Indstillet temperatur«**, udlufter styringen rummet periodisk; ved yderligere fald tilkobles supplerende opvarmning. Alt afhænger af de indstillinger, som brugeren har indtastet. Styringens program omfatter også samarbejde med en alarmcentral, som kan aktiveres, hvis temperaturen i svinestalden afviger fra de indstillede parametre. 

![Ventilation](./img/Sc-12wentyl.png)  

## Programmering af styringen
Styringen har et sæt standardindstillinger, som skrives til den ikke-flygtige hukommelse i to tilfælde:
1. Første opstart af enheden,
2. F ejl i datahukommelsen.
Ved manglende strømforsyning eller strømsvigt mister styringen ikke de tidligere indtastede og gemte brugerindstillinger.

## Frontpanel – indikatorer, knapper og display
![Panel](./img/SC-12panel.png)  
    1. Rød kontrollampe, der angiver overskridelse af den maksimalt tilladte temperatur.
    2. Rød kontrollampe, der angiver underskridelse af den minimalt tilladte temperatur.
    3. Gul kontrollampe, der angiver supplerende opvarmning.
    4. Gul kontrollampe, der angiver ventilation i gruppe 2.
    5. Grøn kontrollampe, der angiver manuel indstilling af ventilationsniveauet.
    6. Grøn kontrollampe, der angiver aktiv kommunikation RS485.
    7. Menudisplay; viser temperaturen under normal drift.
    8. Søjleindikator, der angiver ventilationsniveauet.
    9. Tast til at bevæge sig opad i menuen eller ændre en parameterværdi.
    10. ESC-tast - forlader menuen eller den pågældende parameter uden at gemme værdien.
    11. OK-tast - åbner menuen eller bekræfter (gemmer) den pågældende parameter.
    12. Tast til at bevæge sig nedad i menuen eller ændre en parameterværdi.

## Brug af menuen
Styringen er udstyret med en række funktioner, der gør det muligt at tilpasse den til den pågældende anvendelse. Funktionerne er grupperet i en menu, som åbnes ved at trykke på en af tasterne **(»+«, »-« eller »OK«)**. Tasterne **»+«** og **»-«** anvendes til at vælge funktioner, og redigering, lagring af data eller adgang til et yderligere menuniveau kan udføres med tasten **»OK«**. Tryk på tasten **»Esc«** for at vende tilbage til den overordnede menu eller undlade at gemme den pågældende parameter.

## Funktioner i grundmenuen

| MENU                          | Beskrivelse       | 
|:-----------                   |:---------- |
| Temperatur 20,8o C W16% A    | **Informationstilstand** - normal drift. Displayet viser den aktuelle temperatur og, når ventilatoren er i drift, værdien for ventilationsniveauet. Betydning af yderligere symboler:A-angiver aktiveret alarm,D  - angiver tilkoblet opvarmning, W - angiver ekstra ventilation| 
|   Indstillet temp.   20,0o C      |**»Indstillet temperatur«** – Angiver den temperatur, hvor den trinløse ventilationsproces begynder. Der skal vælges en passende værdi afhængigt af husdyrarten.| 
| Udluftning     | **Udluftning** – der indstilles to tidsværdier.    1.**Driftstid** Angiver antallet af minutter med ventilation i drift.    2.**Pausetid** Angiver antallet af minutters stilstand for ventilationen mellem på hinanden følgende driftscyklusser.    3.**Udluftningsniveau** - Angiver ventilationsstyrken under udluftning.| 
| Alarm |  1.**Alarm aktiv Ja** - Aktivering/deaktivering af alarmkontakten; for at styringen ikke skal udsende et alarmsignal på udgangen (til alarmcentralen), vælges »NEJ« i menuen.  2. **Temp. Min. 15,0o C** - Angiver den absolutte minimumstemperatur, hvor alarmen aktiveres.  3.**Temp. Maks. 25,0o C** - Angiver den absolutte maksimumstemperatur, hvor alarmen aktiveres.  4.**Alarmsignal Ja** - Aktivering/deaktivering af det akustiske signal i styringen. | 
|    Ventilation        |  1.**Vent.bånd 1 5,0o C**   - Angiver styringens reaktionshastighed (ændring af ventilationsniveauet fra minimum 1 til maksimum 1) ved stigende temperatur.  2.**Min. niveau 1 1 %** - Angiver ventilationsniveauet svarende til den indstillede temperatur.  3.**Maks. niveau 1 100 %**-Angiver det faste ventilationsniveau for en temperatur, der overstiger området for trinløs regulering, når »Vent.bånd 2gr.« = 0, ellers det maksimale niveau for reguleret ventilation ved en temperatur, der er summen af den indstillede temperatur og båndet for gruppe 1.  4.**Vent.bånd 2 0,0o C**-Angiver styringens reaktionshastighed (ændring af ventilationsniveauet fra minimum 2 til maksimum 2) ved stigende temperatur for gruppe 2. Funktionen er inaktiv, når båndet er lig med nul.  5.**Min. niveau 2 1 %**-Angiver det minimale ventilationsniveau for gruppe 1 ved det punkt, hvor kontakterne for gruppe 2 sluttes.  6.**Maks. niveau 2 100 %**-Angiver det faste ventilationsniveau for en temperatur, der overstiger området for trinløs regulering, når gruppe 2 er tilkoblet.  7.**Gruppe 3  5,0o C**-Angiver det faste ventilationsniveau for en temperatur, der overstiger området for trinløs regulering, når gruppe 2 er tilkoblet.  8.**Gruppe 4 7,0o C**-Angiver temperaturen i forhold til den indstillede temperatur, hvor ventilationsgruppe 4 tilkobles (hejsefunktionen skal være deaktiveret).| 
|    Supplerende opvarmning  |  1.**Temp. suppl. opv. 15,0o C**-Angiver temperaturen for tilkobling af supplerende opvarmning.  2.**Bånd suppl. opv. 5,0o C** -Angiver effektforholdet for systemerne til supplerende opvarmning (på udgangen V3 0-10V) afhængigt af temperaturen. | 

## Funktioner i den avancerede menu
Den avancerede menu er primært beregnet til installatører og gør det muligt at tilpasse styringen til installationen og ventilatoren, teste kredsløb og vælge menusprog. Der skiftes til de avancerede indstillinger ved at trykke på og holde to menutaster nede i cirka 10s. 

| MENU                          | Beskrivelse       | 
|:-----------                   |:---------- |
|Test  |Denne funktion anvendes til at kontrollere styringens enkelte udgangskredsløb; alle indstillinger er midlertidige og gælder kun, mens det pågældende menupunkt er åbent. Efter tryk på »ESC« eller »OK« vender den pågældende udgang tilbage til den tilstand, der følger af styringens drift.  1.**Ventilation 0 %**  Muliggør manuel indstilling af ventilationsniveauet for at kontrollere ventilationssystemet. Når funktionen bekræftes, tændes den grønne kontrollampe (hånd).  2.**Alarm Nej** Aktivering medfører tænding af 2 røde kontrollamper samt aktivering af lydsignalet og alarmkredsløbet.  3.**Supplerende opvarmning Nej** Aktivering medfører tænding af den gule kontrollampe (flamme) samt tilkobling af kredsløbet for supplerende opvarmning.  4.**Vent. 2 trin Nej** Aktivering medfører tænding af den gule kontrollampe (ventilator) samt tilkobling af kredsløbet for gruppe 2.  5.**Udgang V1 0,0 V  Udgang V2  0,0 V Udgang V3  0,0 V**-Test af udgangene 0-10V; med tasterne »+« eller »-« kan der indstilles en valgt spænding til systemerne for henholdsvis: udvidelsesmoduler, luftindtagsspjæld og trinløs supplerende opvarmning. Funktionen er særligt nyttig ved kalibrering af Udgang V2 for luftindtagsspjældene.  6.**Hejseanordning 0** Muliggør kontrol af luftindtagsspjældsystemet; »+« - åbner indtagene, »-« - lukker indtagene. Displayet viser aktuatorens aktuelle position aflæst fra potentiometeret.  7.**Gruppe 3 Nej**  Aktivering medfører tilkobling af kredsløbet for ventilationsgruppe 3. (hejsefunktionen skal være deaktiveret)  8.**Gruppe 4 Nej**  Aktivering medfører tilkobling af kredsløbet for ventilationsgruppe 4. (hejsefunktionen skal være deaktiveret)|
|Sprog        | Valg af menusprog. Der kan vælges polsk eller engelsk. | 
|Ventilator         |  1.**Forbudt bånd 0**- Kalibrering af minimumsomdrejningstallet for ventilatorer, der er tilsluttet direkte til styringen; denne parameter svarer til ventilationsniveauet »1%«. En positiv parameterværdi øger omdrejningstallet, en negativ reducerer det.  2.**Udv.modul Min. 1,9 V** -Minimumsspænding, der tilføres effektudvidelsesmodulet (udgang V1 0-10V).  3.**Udv.modul Maks. 10,0 V** -Maksimumsspænding, der tilføres effektudvidelsesmodulet (udgang V1 0-10V).  4.**Modul frakobling Nej** - Frakobling af effektudvidelsesmodulet; når »JA« vælges, falder spændingen på udgangen, der styrer udvidelsesmodulerne (V1 0-10V), til niveauet 0V og ikke til den indstillede minimumsværdi, når ventilationsniveauet er 0%.  5.**Invertering  Nej**-Aktivering medfører invertering af udgangens karakteristik V1. Spændingen falder ved stigende ventilationsniveau inden for det område, der er fastlagt af min.-maks. Signalet på udgangen V1 bliver af typen 10-0V.| 
| Luftindtagsspjæld       |  1.**Forskud 0,0o C**-Tidligere åbning af luftindtagsspjældene. Den indstillede parameter angiver, hvor mange temperaturgrader før »Indstillet temperatur« luftindtagsspjældene skal åbnes.  2.**Fuld lukning  Nej**- Aktivering medfører, at spændingen på udgangen, der styrer luftindtagsspjældene (V2 0-10V), falder til niveauet 0V og ikke til den indstillede minimumsværdi. Ved manglende ventilation (ventilationsniveau 0%).  3.**Spjæld min.  1,9 V**- Minimumsspænding, der tilføres luftindtagsspjældene (udgang V2 0-10V).  4.**Spjæld maks.  10,0 V**- Maksimumsspænding, der tilføres luftindtagsspjældene (udgang V2 0-10V).  5.**Invertering   Nej**-Aktivering medfører invertering af udgangens karakteristik V2. Spændingen falder ved stigende ventilationsniveau inden for det område, der er fastlagt af min.-maks. Signalet på udgangen V2 bliver af typen 10-0V. |  
| Temperaturmåling  |  1.**Kalibrering S1 23,0o C -> 23,5o C**,**Kalibrering S2 23,0o C -> 23,2o C** - Kalibrering af de analoge indgange muliggør omskalering af temperaturen aflæst fra sensorerne S1 og S2.  2.**Midlingsperiode 60 s**- Denne parameter angiver det tidsrum, hvor de aktuelle temperaturaflæsninger midles. Den gennemsnitlige temperaturværdi er den grundlæggende parameter for styringens funktioner. Ændringer af udgangenes tilstand (ventilation, supplerende opvarmning, spjæld, yderligere ventilationsgrupper, alarmer,...) er tæt knyttet til denne parameter og kan ikke forekomme hyppigere end det tidsrum, der er angivet her. | 
| Hejseanordning      |  1.**Kalibrering Åbning 1024 -> 853**,**Kalibrering Lukning 0 -> 324** -Kalibrering af hejseanordningen er nødvendig for korrekt drift af luftindtagssystemet. Tasten »+« åbner indtagene, og tasten »-« lukker indtagene. Ved åbning af indtagene skal positionsparameteren stige, og ved lukning skal den falde; ellers skal aktuatorens tilslutning kontrolleres (forsyning og potentiometer). Ved kalibrering af åbning åbnes indtagene maksimalt, og positionen bekræftes med tasten »OK«. Ved kalibrering af lukning lukkes indtagene, og positionen bekræftes med tasten »OK«. Tasten »ESC« forlader funktionen uden at gemme. Forskellen mellem åben og lukket position skal være mindst 100 enheder.  2.**Deaktivering Nej**-Deaktivering frigør kontakterne FUNC1 og FUNC2 fra betjening af hejseanordningen; disse kontakter fungerer da som ventilation for gruppe 3 og 4.| 
| Blødstart               | Parametrene i denne menugruppe styrer opstart af ventilationen. Tilkobling af ventilationen i den trinløse gruppe indledes med en gradvis opstart til 100%, et kortvarigt driftsinterval på 100%  og et fald til det krævede ventilationsniveau. Dette skaber ved ventilationsstart et luftstød, som letter åbning af butterflyventilerne i skorstenene.   Værdierne er udtrykt i perioder af forsyningsspændingen ved 1% ventilation.  1.**Opstartstid 5**- Parameteren angiver, hvor hurtigt ventilationens omdrejningstal stiger fra nul til maksimum – blød tilkobling af ventilatorerne. Værdien 0 deaktiverer blød opstart.  2.**Tid 100%   100**- Parameteren angiver driftstiden ved opstart på 100% af ventilationsniveauet. Indstilling af opstartstiden og 100% til 0 deaktiverer fuldstændigt luftstødet ved ventilationsstart.  3.**Nedløbstid 5**-  Parameteren angiver hastigheden for ændringer af ventilationsniveauet. | 
|Supplerende opvarmning              |  1.**Kontaktinvertering Nej**-Aktivering medfører invertering af HOT-udgangens karakteristik. Kontakten åbnes  ved faldende målt temperatur.  2.**Hysterese  0,5o C** - Angiver temperaturhysteresen for kontakten til supplerende opvarmning.  3.**Relativ drift Nej**-Aktivering medfører relativ indstilling af temperaturen for supplerende opvarmning i forhold til den indstillede temperatur. Grundmenuen for supplerende opvarmning ændres, så forskellen fra den indstillede temperatur angives her.  4.**Supplerende opvarmning min. 1,9 V** - Minimumsspænding, der tilføres den trinløse varmestyring – varmeblæser med variabel ventilatorydelse (udgang V3 0-10V).  5.**Supplerende opvarmning maks. 10,0 V** - Maksimumsspænding, der tilføres den trinløse varmestyring – varmeblæser med variabel ventilatorydelse (udgang V3 0-10V).| 
| Program 	|  **ver. 2.4  apr. 13 2018** - 	Aflæsning af softwareversion og kompileringsdato|

## F ejlmeddelelser og advarsler

Fejlmeddelelserne informerer brugeren om uregelmæssigheder i styringens drift. Mulige fejlmeddelelser er angivet nedenfor

|FEJL                            |	BESKRIVELSE      |
|:-----------                    |:---------- |
|Alarm     Overbelastning 	     |Overbelastningsalarm, aktiveres ved 75°C. Enheden standser driften, indtil den er afkølet.|
|Alarm  Sensor mangler|Angiver en manglende eller beskadiget sensor eller et beskadiget tilslutningskabel.|

# Bemærkninger og advarsler 
:::danger 
 Under installation af enheden skal strømforsyningen ubetinget afbrydes, da spændingen på visse komponenter er farlig for liv og helbred. Det anbefales at lade en kvalificeret person udføre installationen.

:::
- For at undgå problemer med enhedens drift skal vejledningen læses før installation og brug.
- Det er ikke tilladt at ændre konstruktionen eller selv udføre reparationer. Dette gælder især ændringer af dele og komponenter. 
- Vedligeholdelse og service skal udføres af autoriseret personale (installatør eller producentens serviceafdeling). I staldbygninger med mekanisk ventilation er et alarmsystem påkrævet. Enhedens producent er ikke ansvarlig for skader forårsaget af forkert installation, forkert programmering af funktioner, følger af hændelige begivenheder samt eksterne faktorer. 
- Ventilationsstyringens parametre skal indstilles i overensstemmelse med forholdene i staldrummet. Disse indstillinger er individuelle og afhænger af husdyrholderens beslutning. Enhedens producent forbeholder sig retten til at ændre enhedens konstruktion og software.

:::caution
<div class="warning-container">
  <p>
    <strong></strong> Når produktet ikke længere anvendes, må det ikke bortskaffes sammen med usorteret husholdningsaffald, men skal bortskaffes i overensstemmelse med gældende bestemmelser (EU's WEEE-direktiv 2012/19/EU).
Produktet er fremstillet i overensstemmelse med RoHS-kravene (EU-direktiv 2011/65/EU).
  </p>
</div>
:::
:::tip

## Styringens tekniske data
|Parameter                        |	BESKRIVELSE      |
|:-----------                    |:---------- |
|Forsyningsspænding|	230VAC 50Hz|
|Maksimal strøm for udgangen med trinløs regulering FAN|	12A|
|Reguleringsområde for udgangsspændingen|	70V ÷ 230V|
|Maksimal strøm for udgangen (kontakten) FAN 2|	6A|
|Maksimal strøm for udgangen (kontakten) HOT|	6A|
|Maksimal strøm for udgangen (kontakten) ALARM|	4A|
|Maksimal strøm for udgangen (kontakten) FUNC1 og FUNC2|	4A|
|Driftstemperaturområde|	-10 +40oC|
|Temperaturmåleområde|	0 +50oC|
|Temperaturmålingens opløsning|	0,1oC|
|Registrering af fejl på temperatursensoren|	JA|
|Maksimalt antal analoge sensorer|	2|
|Temperaturmålingens nøjagtighed – analog indgang|	1oC|
|Målingens afhængighed af ledningsmodstand – analog indgang|	15,8Ω/oC|
|Maksimalt antal digitale sensorer|	4|
|Temperaturmålingens nøjagtighed – digital indgang|	0,5oC|
|Målingens afhængighed af ledningsmodstand – digital indgang|	Ingen|
|Maksimal længde af ledningen, der forbinder digitale sensorer|	150m|
|Overspændingsbestandighed (maks. E)|	210J|
|Overbelastningsbeskyttelse|	75oC|
|Enhedens mål|	34x29x12 [cm]|
|Kabinettets kapslingsklasse|	IP56|
:::

:::info
Styringen SPEED CONTROL-12 v2  leveres med:
 - 1 temperatursensor,
 - 4 ekspansionsdyvler,
 - 2 kabelforskruninger PG13,5.
 - 3 kabelforskruninger PG11,
 - 4 kabelforskruninger PG9.
:::















































































