---
sidebar_position: 4
title: Vejledning IC-AC
description: Styreenhed IC-AC til luftindtag i staldbygninger med en tilladt udgangsstrøm
  på op til 2A
keywords:
- eletor IC-AC
- styreenhed til luftindtag
- klimastyreenhed
- styreenhed til ventilation i svinestalde
- mikroklimastyreenhed
- styreenhed til svinestalde
- ventilation i svinestalde
- styreenhed til opdrætsstalde
---


# Styreenhed IC-AC

  Styreenhed til aktuatorer og hejsesystemer til luftindtag baseret på AC-motorer med højre-/venstreløb og potentiometer til aflæsning af den aktuelle position. Styreenheden fungerer som konverter af signalet 0-10V til luftindtagenes åbningsgrad og muliggør desuden manuel styring.

## Parametre og egenskaber:  
- Driftstilstande:
  - MANUAL – manuel styring med knapperne „+”, „-”;
  - AUTO – automatisk drift i det kalibrerede område proportionalt med signalet 0-10V;
  - NØDDRIFT – ved bortfald af styresignalet åbnes luftindtagene til det angivne niveau i procent; 
- Relæudgang (højre/venstre) 2A;
- Styresignal: 0-10V;
- Mulighed for invertering af styresignalet;
- Positionsmåling med potentiometer 1-100kΩ;
- Programmerbar hysterese og midlingstid for aflæsninger; 
- Hermetisk kapsling IP56;
- Forsyningsspænding 230VAC 50Hz;
- Menusprog: 
  - polsk
  - engelsk
  - ukrainsk
  - russisk

# Installation af styreenheden  
:::danger 
Under installation af enheden skal strømforsyningen ubetinget afbrydes, da spændingen på visse komponenter udgør en fare for liv og helbred. Det anbefales at lade en kvalificeret person udføre installationen.
:::

## Valg af monteringssted  

  Monteringsstedet skal vælges hensigtsmæssigt under hensyntagen til, at autoriserede personer skal have nem adgang til enheden, mens den skal være utilgængelig for dyr og børn. Der skal også tages hensyn til de klimatiske forhold, dvs. enheden skal anvendes i temperaturområdet -10°C til 40 °C på et sted uden direkte sollys.

# Montering

Enheden kan anvendes under aggressive klimatiske forhold. En korrekt monteret enhed er modstandsdygtig over for skadelige miljøpåvirkninger. 

  Under monteringen skal der tages hensyn til følgende: 
- låget skal spændes fast med alle skruer,
- kablerne til tilslutning af enheden skal have et rundt tværsnit,
- efter tilslutning af kablet skal kabelforskruningerne spændes, så kablet tætnes og fastholdes, brug af silikone anbefales,
- ubrugte gennemføringer (kabelforskruninger) skal lukkes med blindpropper,
- kapslingens underdel fastgøres på en plan væg med 4 ekspansionsdyvler.


# Elektrisk tilslutning  

:::danger 
Inden systemet tilsluttes, skal det sikres, at strømforsyningen er afbrudt!
:::

  Når enheden er skruet op, skal frontpanelet fjernes. Dette gøres ved at trække fladkablet ud af stikket mærket P1. Kablerne føres gennem gummikabelforskruningerne, hvorefter de kan tilsluttes. Tilslutningen skal udføres i henhold til beskrivelsen. Styreenhedens klemmer er vist på nedenstående figur.

![Tilslutning](./img/ic-acpołącz.png)

## Forsyningen 230V AC fra eltavlen tilsluttes klemmerne:  
 - **Tilslutning L** faseklemme. Der skal anvendes en automatsikring (type „S” B3) samt overspændingsafledere.  
 - **Tilslutning N** nulklemme.  
 - **Tilslutning PE** beskyttelsesjordklemme.

## Udgang til aktuator: 
 - **Tilslutning L** forbindes med en ledning til tilslutning C for at tilføre spænding til relæerne.  
 - **Tilslutning N** aktuatorens nulklemme.  
 - **Tilslutning PE** aktuatorens beskyttelsesjordklemme – kapsling.  
 - **Tilslutning NO** aktuatorens klemme for åbning af luftindtagene.  
 - **Tilslutning NC** aktuatorens klemme for lukning af luftindtagene.
 - **Potentiometertilslutning** – skal forbindes i henhold til mærkningen på aktuatorens diagram. Polariteten af potentiometerets forsyning skal vælges, så positionsværdien stiger, når luftindtagene åbnes, og falder, når de lukkes. Hvis dette ikke er tilfældet, skal ledningerne til potentiometerets forsyning byttes om.  
 - **Tilslutning In** – skal forbindes til styreenheden for at tilføre styresignalet til hejsesystemerne.  


# Funktionsprincip  

  I automatisk tilstand konverterer styreenheden styresignalet i området 0-10V til den tilsvarende position for luftindtagenes aktuator. Aktuatoren skal kalibreres i positionerne for maksimal åbning og lukning af luftindtagene. Under kalibreringen skal det sikres, at wirerne til luftindtagene hele tiden er spændte. Under kalibreringen skal knappen „+” åbne luftindtagene, og knappen „-” skal lukke luftindtagene. Hvis dette ikke er tilfældet, skal ledningerne på klemmerne NO og NC byttes om.
  De positioner, der aflæses fra potentiometeret for åbning og lukning, skal afvige med mere end 100 enheder. Positionsværdierne, der aflæses fra potentiometeret, skal stige, når luftindtagene åbnes, og falde, når de lukkes. Hvis dette ikke er tilfældet, skal ledningerne til potentiometerets forsyning byttes om.
  Efter korrekt kalibrering er styreenheden klar til automatisk drift og vil regulere aktuatorens position. Et styresignal på et niveau under 1,5V medfører, at luftindtagene indstilles til nødpositionen. 

## Betjening 

  Styreenheden til luftindtag kan anvendes i en af to tilstande: manuel eller automatisk. Den valgte driftstilstand gemmes uafhængigt af strømsvigt – når strømforsyningen tilsluttes igen, vender styreenheden tilbage til den senest anvendte tilstand. Den aktuelt valgte driftstilstand vises på displayet:  
   - **MANUAL** - ved at holde "+" eller "-" inde i længere tid aktiveres manuel tilstand. I denne tilstand styres luftindtagene manuelt med knapperne: „+” - åbning, „-” - lukning.           
   - **AUTO**   - ved at holde "Esc" inde i længere tid aktiveres automatisk tilstand. I denne tilstand fungerer luftindtagene automatisk, styret af signalet 0-10V fra tilslutning In.

## Funktioner i hovedmenuen  

| MENU                       | Beskrivelse | 
|:---:                       |:---|
|MANUAL  STOP    POT 539  |  **„Informationstilstand”** – ved manuel drift. Viste oplysninger:  - **STOP** – aktuatoren står stille;  - **ÅBN** – åbning af luftindtagene ved tryk på knappen „+”;  - **LUK** – lukning af luftindtagene ved tryk på knappen „-”;  - **POT 539** – parameter for aktuatorens aktuelle position bestemt af potentiometeret.  •Skift til automatisk driftstilstand ved at holde tasten „Esc” inde| 
|AUTO  20 % = In 3,70 POT 511       |  **„Informationstilstand”**  ved automatisk drift. Viste oplysninger:    **20 %**  Værdi for den indstillede åbningsposition for luftindtagene    **"="**   luftindtagene er i den fastlagte position    **"–"**    lukning af luftindtagene til den angivne position    **"+"**    åbning af luftindtagene til den angivne position    **In 3,70**  måling af styrespændingen på klemmerne In     **POT 511**  parameter for aktuatorens aktuelle position bestemt af potentiometeret.  Skift til manuel driftstilstand ved at holde tasten „+” eller „-” inde | 
|Spjæld nødposition 30 %  |**„Spjæld nødposition”** – indstilling af værdien for spjældenes (luftindtagenes) nødåbning ved bortfald af styresignalet. Luftindtagene åbnes til det indstillede niveau ved fejl i styreenheden eller signalkablet.| 
|Kalibrering Åbn 671 -> 311        |**„Kalibrering af åbning”** – kalibrering af luftindtagenes åbning udføres ved at indstille luftindtagene til maksimal åbning (yderposition) med knapperne „+” og „-”. Den første viste værdi repræsenterer den senest gemte indstilling, og den anden værdi aktuatorens aktuelle position. Tasten „Ok” gemmer de indtastede indstillinger i hukommelsen, mens „Esc” forlader kalibreringstilstanden uden at gemme.   | 
|Kalibrering Luk 281 -> 311      |**„Kalibrering af lukning”** – kalibrering af luftindtagenes lukning udføres ved at indstille luftindtagene til minimumspositionen med knapperne „+” og „-”. Den første viste værdi repræsenterer den senest gemte indstilling, og den anden værdi aktuatorens aktuelle position. Tasten „Ok” gemmer de indtastede indstillinger i hukommelsen, mens „Esc” forlader kalibreringstilstanden uden at gemme.|  
|Midlingstid 5 s       |**„Midlingstid”** – midlingstiden for styresignalet fra tilslutning In beskytter mod svingninger på styreindgangen.  | 
|Invertering   Nej |**„Invertering”** – aktivering af denne funktion tilpasser styreenheden til styresignalet 10-0V  | 
|Sprog   Polsk |**„Sprog”** – valg af menusprog  | 
|Hysterese Pot  5   | **„Potentiometerhysterese”** – ændringer i aktuatorens positionsparameter under den indstillede værdi tages ikke i betragtning ved positioneringen. Parameteren har til formål at eliminere meget små bevægelser af aktuatoren samt forstyrrelser fra potentiometeret. | 
 

# Bemærkninger og advarsler  

:::danger 
Under installation af enheden skal strømforsyningen ubetinget afbrydes, da spændingen på visse komponenter udgør en fare for liv og helbred. Det anbefales at lade en kvalificeret person udføre installationen.
:::

- For at undgå problemer med driften af enheden skal vejledningen læses før installation og brug. Det er ikke tilladt at ændre konstruktionen eller selv udføre reparationer. Dette gælder især ændringer af elementer og komponenter.
- Vedligeholdelses- og servicearbejde skal udføres af autoriseret personale (installatør eller producentens serviceafdeling). I staldbygninger med mekanisk ventilation er et alarmsystem påkrævet. 
- Producenten af enheden er ikke ansvarlig for skader forårsaget af forkert installation, forkert programmering af funktioner, følger af hændelige begivenheder samt eksterne faktorer.
- Enhedens parametre skal indstilles i overensstemmelse med forholdene i husdyrholdets lokaler. Disse indstillinger er individuelle og afhænger af husdyrholderens beslutning. Producenten af enheden forbeholder sig retten til at foretage ændringer i enhedens konstruktion og software.  


:::caution
![alt](./img/trash.svg) Når produktet er udtjent, må det ikke bortskaffes sammen med usorteret kommunalt affald, men skal bortskaffes i overensstemmelse med gældende bestemmelser (EU's WEEE-direktiver 2012/19/EU).  Produktet er fremstillet i overensstemmelse med RoHS-kravene (EU-direktiv 2011/65/EU).
:::

<!-- \newpage -->
# Styreenhedens tekniske data  

|Parameter                        |	BESKRIVELSE      |
|:-----------                    |:---------- |
|AC-forsyningsspænding|	230VAC 50Hz|
|Maksimal udgangsstrøm|	2A|
|Støjfilter på udgangen|	RC|
|Indgangsimpedans|	100kΩ|
|Overspændingsbeskyttelse af indgange og udgange|	JA|
|Forsyning til potentiometer|	10VDC|
|Maksimal strøm på potentiometerudgangene|	30mA|
|Driftstemperaturområde|	-10 +40oC|
|Enhedens mål|	20x15x8 cm |
|Kapslingens beskyttelsesgrad|	IP65|

:::info
Styreenheden IC-AC leveres med:
- 4 ekspansionsdyvler,
- 2 kabelforskruning PG11,
- 2 kabelforskruning PG9.
:::

