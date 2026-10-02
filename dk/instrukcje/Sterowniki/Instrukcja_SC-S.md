---
sidebar_position: 2
title: Vejledning SC-S
description: Klimastyreenhed til staldbygninger med en tilladt udgangsstrøm på op
  til 5A
keywords:
- eletor sc-s
- ventilationsstyreenhed
- klimastyreenhed
- styreenhed til svinestaldsventilation
- mikroklimastyreenhed
- styreenhed til svinestalde
- svinestaldsventilation
- styreenhed til opdrætsstalde
---


# Styreenhed SC-S

Mikroprocessorbaseret klimastyreenhed fra familien SPEED CONTROL. En pålidelig styreenhed, der er nem at montere og betjene, med software på polsk, engelsk, russisk og tysk. Styreenhedens program muliggør intuitiv indstilling af parametre: temperaturer, udluftning, supplerende opvarmning, min./maks. ventilationsniveauer og alarmer.

**Parametre og egenskaber:**  
- Ventilation i gruppe I:
  - maks. strøm for udgangen med trinløs regulering 6A,
  - termisk beskyttelse af kredsløbet,
  - blød start af ventilationen,
  - kalibrering af minimumsomdrejningstal
- Ventilation i gruppe II, potentialfri kontakt op til 3A (1 som tilvalg)
- Supplerende opvarmning, potentialfri kontakt op til 3A (1 som tilvalg)
- Alarmudgange NO og NC:
  - signalering af strømsvigt,
  - signalering af overskridelse af min.- eller maks. temperaturgrænse
- 1 analog indgang til temperaturmåling
- 2 udgange 0-10V
- Kredsløbets effektforbrug < 3W
- Tæt kapsling IP56
- Forsyningsspænding 230VAC 50Hz

## Installation af styreenheden  
:::danger 
Under installation af enheden skal strømforsyningen ubetinget afbrydes, da spændingen på visse komponenter er farlig for liv og helbred.  
Det anbefales at lade installationen udføre af en kvalificeret person.
:::

### Valg af monteringssted  

Monteringsstedet skal vælges hensigtsmæssigt under hensyntagen til, at enheden skal være let tilgængelig for autoriserede personer, men utilgængelig for dyr og børn. Der skal også tages hensyn til klimaforholdene, dvs. enheden skal fungere i temperaturområdet -10°C til 40°C på et sted uden direkte sollys. Der skal være fri luftcirkulation omkring enheden. Enheden omfatter en temperatursensor. Følgende regler gælder for montering af temperatursensoren:  
- sensoren bør ikke monteres på et sted uden luftcirkulation eller med direkte sollys
- sensoren bør ikke monteres på bygningens bærende væg (ydervæg),
- undgå nærhed til varmeafgivende enheder såsom radiatorer og lamper,
- sensoren må ikke placeres direkte ved døre og ventilationsåbninger,
- sensoren må ikke placeres på steder, der er tilgængelige for dyr,
- det anbefales at føre sensorens forbindelsesledning væk fra forsyningsledningerne.

### Montering  

Enheden kan fungere under vanskelige klimaforhold. En korrekt monteret styreenhed og temperatursensor er modstandsdygtige over for miljøpåvirkninger.
Under monteringen skal der tages hensyn til følgende:  
- kontrollér dækslets pakning, før skruerne spændes,
- dækslet skal spændes fast med alle skruer,
- de kabler, der anvendes til tilslutning af styreenheden, skal være runde,
- efter tilslutning af kablet skal kabelforskruningerne spændes, så kablet tætnes og fastholdes; det anbefales at anvende silikone,
- ubrugte gennemføringer (kabelforskruninger) skal blændes af,
- styreenheden (kapslingens nederste del) fastgøres til en plan væg med 4 ekspansionsdyvler.

## Elektrisk tilslutning  

:::danger 
Kontrollér, at strømforsyningen er afbrudt, før kredsløbet tilsluttes!
:::

Før styreenheden tilsluttes, skal dækslet skrues løs og fjernes. Før kablerne gennem gummiforskruningerne, hvorefter de kan tilsluttes. Styreenhedens klemmer er vist på nedenstående figur.

![Tilslutning](./img/Sc-s2.png)

**AC-stikket 230V** tilsluttes strømforsyningen (fordelingstavlen). Der skal anvendes en automatsikring 1P-B6 samt overspændingsbeskyttelse af type T1 T2. Ved tilslutning af flere enheder er det god praksis at fordele styreenhederne på forskellige ”faser” (L1, L2, L3) for at belaste forsyningsledningen jævnt.  
**FAN-stikket** skal tilsluttes direkte til ventilatoren. Ved styring af flere ventilatorer må den samlede belastning ikke overstige 6A, og hver ventilator skal sikres separat. PE og N må ikke føres fra strømforsyningen (fordelingstavlen); de skal tilsluttes styreenhedens tilslutninger.  
**FUNCTION-stikket** er en potentialfri relæudgang med en maksimal kontaktstrøm på 6A (en ekstern automatsikring 1P-B6 er påkrævet ved direkte styring af belastningen),
og kan anvendes som:  
- **Supplerende opvarmning** – kontakten sluttes, når den målte temperatur falder under den indstillede værdi.  
- **Ventilation i gruppe 2 eller overrislingsanlæg** – kontakten sluttes, når den målte temperatur er højere end summen af den indstillede temperatur og ventilationsbåndet.  kontakten sluttes, når den målte temperatur er højere end summen af den indstillede temperatur og ventilationsbåndet.  

Nedenstående figur viser tilslutningen af en ventilator i gruppe 2 eller en varmeenhed.  

![Anden gruppe](./img/2grupa.png)

**ALARM-stikket** består af potentialfri udgange NC, C og NO til tilslutning til en alarmcentral. Alarmen aktiveres i følgende tilfælde:  
- temperaturen er for lav eller for høj,
- styreenheden eller temperatursensoren er beskadiget,
- styreenhedens forsyningsspænding er bortfaldet;
- der er opstået en driftsfejl i styreenheden (f.eks. overophedning af styreenheden)  

![Alarm](./img/alarmsc-s.png)  

**Stikket V1 0-10V** bruges til tilslutning af effektudvidelsesmoduler eller ventilatorer med indbygget hastighedsregulering. Spændingen på denne klemme er proportional med ventilationsniveauet.  
**Stikket V2 0-10V** bruges til tilslutning af en aktuator, der åbner luftindtagsspjældene.  
**SENSOR-stikket** tilsluttes 1 temperatursensor TS3 eller TS5; polariteten er uden betydning.  Det er god praksis at holde måleledningerne adskilt fra forsyningsledningerne.  
**Stikket RS-485** kan anvendes til opbygning af ventilationssystemer samt kommunikation med en PC.  

## Funktionsprincip  

Styreenhedens hovedopgave er at holde temperaturen i husdyrrummet på det niveau, som husdyrproducenten har fastsat. Det skal bemærkes, at styreenheden kun er et værktøj, der skal hjælpe med at sikre optimale klimaforhold i husdyrrummet. Den overordnede rolle i denne proces varetages dog af husdyrproducenten, som skal tilpasse enhedens indstillinger til de skiftende klimaforhold udendørs og især til dyrenes behov i staldbygningen samt overvåge enhedens driftstilstand ved hjælp af en alarmcentral.  

### Første idriftsættelse af styreenheden  

:::danger
Ved første idriftsættelse af styreenheden skal motorens forbudte driftsområde ubetinget indstilles.
:::

Styreenheden fungerer sammen med ventilatorer med enfaset asynkronmotor med et maksimalt samlet strømforbrug på 5A. Efter tilslutning af de valgte ventilatorer skal brugeren tilpasse dem til drift med styreenheden. Det er med andre ord nødvendigt at indstille ventilatorens minimale driftsniveau (omdrejningstal). Denne funktion kaldes **”Forbudt område”** og indstilles én gang af brugeren via **”Avancerede indstillinger”**. For at udføre dette korrekt anbefales det at få hjælp fra en anden person, som løbende kan observere ventilatorens adfærd, mens den første person indstiller værdien for **”Forbudt område”**. Manglende indstilling af det forbudte område kan medføre, at enheden fungerer forkert. Værdien for **”Forbudt område”** kan anses for korrekt, når trykket fra ventilatoren begynder at løfte ventilationsskorstenens spjæld en smule. Indstillingen af **”Forbudt område”** skal gentages, hvis den ventilator, der er tilsluttet styreenheden, udskiftes.  

### Periodisk udluftning  

Udluftning er en funktion, som udføres af styreenheden og aktiveres, når temperaturen i rummet falder under den indstillede temperatur. Denne funktion sikrer dyrene en cyklisk tilførsel af frisk luft. Udluftning defineres af 3 parametre:
- **”Driftstid”** - angiver, hvor mange sekunder ventilatoren skal være tændt,
- **”Pausetid”** - angiver i sekunder, hvor længe ventilatoren skal stå stille,
- **”Udluftningsniveau”** - angiver ventilationseffekten under ”Driftstid”.  

Et eksempel på indstillingen **60s/120s** betyder, at ventilatoren tændes i 60s med en pause på 120s mellem de efterfølgende aktiveringer. 

Alle ovennævnte parametre indstilles af brugeren. Følgende regler skal overholdes ved indstilling af udluftningsparametrene:
- udluftning aktiveres udelukkende, når temperaturen i svinestalden falder under den indstillede temperatur,
- udluftningens primære funktion er at sikre dyrene en cyklisk tilførsel af frisk luft, ikke at opretholde den indstillede temperatur i rummet,
- det anbefales at udlufte rummene kortvarigt, men hyppigt,
- lange udluftningsperioder skal undgås, da de kan medføre for store temperaturudsving,
- de indstillede parametre skal ubetinget tilpasses dyrenes adfærd og forholdene både inde i og uden for rummet,
- udluftningsfunktionen kan deaktiveres; i så fald skal der både i procenttilstand og tidstilstand indstilles nulværdier i feltet for udluftningstiden, f.eks.: 0/120s  

### Trinløs ventilation  

Styreenheden regulerer ventilationen trinløst fra ”Minimumsomdrejningstal” til **”Maksimumsomdrejningstal”** i området fra **”Indstillet temperatur”** til summen af **”Indstillet temperatur”** og **”Ventilationsbånd”**. Over dette interval aktiveres ventilationsgruppe 2.  

![ventilation](./img/wentylacjia.png)  

Over dette interval aktiveres ventilationsgruppe 2. Hvis temperaturen i rummet falder under **”Indstillet temperatur”**, udlufter styreenheden rummet periodisk; ved yderligere temperaturfald aktiveres supplerende opvarmning. Alt afhænger af de indstillinger, brugeren har indtastet. Styreenhedens program omfatter også samspil med en alarmcentral, som kan aktiveres, hvis temperaturen i svinestalden afviger fra de indstillede parametre.  

## Programmering af styreenheden  

Styreenheden har et sæt standardindstillinger, som skrives til den ikke-flygtige hukommelse i to tilfælde:  
1. Første idriftsættelse af enheden,  
2. F ejl i datahukommelsen.  
Ved manglende strømforsyning eller strømsvigt mister styreenheden ikke tidligere indtastede og gemte brugerindstillinger.  

### Brug af menuen  

Styreenheden er udstyret med en række funktioner, som gør det muligt at tilpasse den til den pågældende anvendelse. Funktionerne er samlet i en menu, som åbnes ved at trykke på en af tasterne **(” Pil højre”, ”Pil venstre”)**. Parametrene ændres med tasterne **”+” og ”-”**. Den redigerede parameter gemmes automatisk i den ikke-flygtige hukommelse **30s** efter det seneste tastetryk.  

### Funktioner i grundmenuen  

| MENU                       | Beskrivelse | 
|:---:                       |:---|
|Temperatur  <br />20,8°C W16% A  |**”Informationstilstand”** - normal drift. Displayet viser den aktuelle temperatur og, når ventilatoren er aktiveret, ventilationsniveauet. Betydning af yderligere symboler: A-angiver aktiveret alarm, D  - angiver aktiveret opvarmning, W - angiver ekstra ventilation| 
|Indstillet temp.  <br />20,0°C        |**”Indstillet temperatur”** – temperaturværdi, der angiver begyndelsen af den trinløse ventilationsproces.   | 
|Udluftning  <br />20s / 200s  |**”Udluftning”** – der indstilles to tidsværdier 1 ”Driftstid”, 2 ”Pausetid” mellem efterfølgende cykliske aktiveringer af ventilationen.| 
|Udluftningsniv.  <br />20%        |**”Udluftningsniveau”** - ventilationsniveauet under udluftningens driftstid   | 
|Minimumsalarm  <br />12,0°C       |**”Minimumsalarm”** - angiver den absolutte minimumstemperatur, ved hvilken alarmen aktiveres. 
|Maksimumsalarm  <br />28,0°C       |**"Maksimumsalarm"** - angiver den absolutte maksimumstemperatur, ved hvilken alarmen aktiveres.  | 
|Supplerende opvarmning  <br />12,0°C         |Afhængigt af konfigurationen udføres følgende funktioner: **”Supplerende opvarmning”** - kontakten sluttes, hvis temperaturen falder under den viste værdi. | 
|Ventilationstrin 2  <br />25,0  |**”Ventilationstrin 2”** - kontakten sluttes, når den målte temperatur overstiger summen af den indstillede temperatur og ventilationsbåndet. | 
|Ventilationsbånd  <br />5,0°C     |**”Ventilationsbånd”** - angiver styreenhedens reaktionshastighed (ændring af ventilationsniveauet fra minimum 1 til maksimum 1) ved stigende temperatur. | 
|Minimumsomdrejningstal  <br />1%        |**”Minimumsomdrejningstal”** – en tilstand, hvor enheden forbliver i ubestemt tid og leverer en spænding med den indstillede værdi til udgangen. Bruges til kalibrering af enheden med motoren og spjældmekanismen.   | 
|Maksimumsomdrejningstal  <br />100%      |**”Maksimumsomdrejningstal”** – en tilstand, hvor enheden forbliver i ubestemt tid og leverer en spænding med den indstillede værdi til udgangen. Bruges til at begrænse den effekt, der anvendes til ventilation| 

### Avanceret menu  

Den avancerede menu er primært beregnet til installatører og gør det muligt at tilpasse styreenheden til installationen og ventilatoren. De avancerede indstillinger åbnes ved at trykke på og holde de to menutaster nede i cirka 10s.  

| MENU                                 | Beskrivelse| 
|:---:                                 |:--- |
|Ingen indstillinger  <br />avancerede   |Denne meddelelse angiver, at styreenheden ikke er kalibreret med ventilationen, og at den kan fungere forkert. Det er nødvendigt at åbne den avancerede menu og indstille ”Forbudt område”.|
|Indstillinger <br />Avancerede         |Angivelse af adgang til avancerede indstillinger. | 
|Softwareversion:  <br />1907       |Oplysning om softwareversion.| 
|Forbudt område  <br />1000 us       |Kalibrering af minimumsomdrejningstallet for ventilatorer, der er tilsluttet direkte til styreenheden; denne parameter svarer til ventilationsniveauet ”1%”|  
|Kontaktfunktion  <br />Supplerende opvarmning     |Valg af kontaktfunktion:  <br />• Supplerende opvarmning (standard)<br />• ventilationsgruppe 2 | 
|Udluftning  <br />Tidsstyret         |Valg af udluftningstype: <br />• Tidsstyret (standard) <br />• Procentbaseret| 
|Område V1  <br />fra 2,0 til 10,0       |Regulering af spændingsområdet på udgangen V1 0÷10V. Indstillingerne vedrører spændingens minimums- og maksimumsværdi. Reguleringen bruges til at tilpasse styreenheden til effektudvidelsen eller frekvensomformeren.| 
|Invertering V1  <br />Nej                |Aktivering medfører, at udgangskarakteristikken for V1 vendes. Spændingen falder, når ventilationsniveauet stiger inden for det område, der er fastsat af min.-maks. Signalet på udgangen V1 bliver af typen 10-0V.| 
|Afbrydelse V1  <br />Nej                |Aktivering medfører, at udgangen  V1 0-10V leverer niveauet 0V i stedet for den indstillede minimumsværdi, når ventilationsniveauet er 0%.| 
|Område V2  <br />fra 2,0 til 10,0       |Regulering af spændingsområdet på udgangen V2 0÷10V. Indstillingerne vedrører spændingens minimums- og maksimumsværdi. Reguleringen bruges til kalibrering af spjældsystemet.|
|Invertering V2  <br />Nej      	       |Aktivering medfører, at udgangskarakteristikken for V2 vendes. Spændingen falder, når ventilationsniveauet stiger inden for det område, der er fastsat af min.-maks. Signalet på udgangen V2 bliver af typen 10-0V.|
|Temp.kalibrering  <br />21,0°C -> 22,0°C|Kalibrering af temperatursensoren gør det muligt at omskalere den aflæste værdi.|
|Blød start  <br />50%      	           |Fastsættelse af ventilationsniveauet ved hver start af ventilatoren; ventilatoren accelereres til den angivne værdi og går derefter over til det indstillede niveau.| 
|Sprog  <br />Polsk    	           |Valg af menusprog: polsk, engelsk, tysk, russisk|
|Afslut                               |Afslut den avancerede menu med tasten ”+”; de foretagne ændringer gemmes i den ikke-flygtige hukommelse.|

### F ejl- og advarselsmeddelelser  

Fejlmeddelelser informerer brugeren om uregelmæssigheder i styreenhedens drift. Nedenfor er de mulige fejlmeddelelser angivet.  

|FEJL                                    | BESKRIVELSE |
|:---:                                   |:--- |
|Alarm  <br />Overbelastning 	         |Overbelastningsalarm, aktiveres ved 75°C. Enheden standser driften, indtil den er kølet af.|
|SENSOR AFBRUDT!  <br />Kontrollér sensor|Afbrudt sensor angiver beskadigelse af sensoren eller forbindelsesledningen.|
|SENSOR KORTSLUTTET!  <br />Kontrollér sensor  |Kortsluttet sensor angiver beskadigelse af sensoren eller forbindelsesledningen.|
|Svigt  <br />Strømforsyning                  |Strømsvigt, for lav forsyningsspænding, forkert frekvens eller kraftigt forvrænget forsyningsspænding.| 

## Bemærkninger og advarsler  

:::danger 
Under installation af enheden skal strømforsyningen ubetinget afbrydes, da spændingen på visse komponenter er farlig for liv og helbred. Det anbefales at lade installationen udføre af en kvalificeret person.
:::

- For at undgå problemer med enhedens drift skal vejledningen læses, før installation og brug påbegyndes.  
- Det er ikke tilladt at foretage indgreb i konstruktionen eller udføre reparationer på egen hånd. Dette gælder især ændringer af dele og komponenter.  
- Vedligeholdelse og service skal udføres af autoriseret personale (installatør eller producentens serviceafdeling). I staldbygninger med mekanisk ventilation kræves et alarmsystem. Enhedens producent er ikke ansvarlig for skader forårsaget af forkert installation, forkert programmering af funktioner, følger af hændelige begivenheder samt eksterne faktorer.  
- Ventilationsstyreenhedens parametre skal indstilles i overensstemmelse med forholdene i husdyrrummet. Disse indstillinger er individuelle og afhænger af husdyrproducentens beslutning. Enhedens producent forbeholder sig retten til at ændre enhedens konstruktion og software.  


:::caution
![alternativ tekst](./img/trash.svg) Når produktet ikke længere skal bruges, må det ikke bortskaffes sammen med usorteret kommunalt affald, men skal bortskaffes i overensstemmelse med gældende bestemmelser (Den Europæiske Unions WEEE-direktiver 2012/19/EU). <br />Produktet er fremstillet i overensstemmelse med RoHS-kravene (Den Europæiske Unions direktiv 2011/65/EU).
:::

<!-- \newpage -->
## Styreenhedens tekniske data  

|Parameter                        |	BESKRIVELSE      |
|:-----------                    |:---------- |
|Forsyningsspænding|	230VAC 50Hz|
|Maksimal strøm for udgangen med trinløs regulering FAN|	6A|
|Reguleringsområde for udgangsspænding|	70V ÷ (Uz-5)V|
|Maksimal strøm for udgangen (kontakten) ALARM|	3A|
|Maksimal strøm for udgangen (kontakten) FUNCTION|	3A|
|Driftstemperaturområde|	-20 +40oC|
|Temperaturmåleområde|	0 +50°C|
|Temperaturmålingens opløsning|	0,1°C|
|Registrering af fejl i temperatursensoren|	JA|
|Maksimalt antal analoge sensorer|	1|
|Temperaturmålingens nøjagtighed – analog indgang|	1°C|
|Målingens afhængighed af ledningsmodstanden – analog indgang|	15,8Ω/°C|
|Overspændingsmodstandsevne (maks. E)|	210J|
|Overbelastningsbeskyttelse|	75°C|
|Enhedens dimensioner|	20x15x8 [cm]|
|Kapslingens tæthedsklasse|	IP56|
  


:::info
Styreenheden SPEED CONTROL SERVOMOTOR leveres med:
- 1 temperatursensor + tilbehør,
- 4 ekspansionsdyvler,
- 1 sikring 10A.
:::

