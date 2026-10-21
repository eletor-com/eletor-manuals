---
id: sc-pe16
title: SC-PE16 — brugsanvisning
sidebar_label: SC-PE16
sidebar_position: 5
description: Vejledning til effektudvidelsen SC-PE16 — montering, tilslutning, idriftsættelse,
  menu og beskyttelsesfunktioner.
slug: /sc-pe16
toc_min_heading_level: 2
toc_max_heading_level: 3
---


Effektudvidelsen SC-PE16 anvendes til styring af ventilatorer, når belastningen overstiger den overordnede styreenheds kapacitet. Enheden regulerer ventilatorernes forsyningsspænding ud fra et analogt signal eller en manuel indstilling. Den maksimale samlede udgangsstrøm er 16 A.

![Effektudvidelse ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Parametre og egenskaber

- driftstilstandene AUTO og MANUAL samt enhedens dvaletilstand;
- grafisk display og berøringstastatur;
- analog styring 2–10 V eller 4–20 mA;
- programmerbar indkoblingstærskel for ventilationsgruppe 2;
- byPASS ved et stabilt niveau på 100%;
- termisk beskyttelse af effektkredsløbet;
- safeRUN: indstilleligt nøddriftsniveau;
- kalibrering af det minimale ventilationsniveau;
- test af ventilation, relæ og alarm;
- tastaturlås og rengøringslås;
- polsk, engelsk eller ukrainsk sprog;
- forsyning 230 V AC, 50 Hz; kabinet IP65.

:::info Softwareversion

Funktionsbeskrivelsen gælder den leverede software **version 2.1**. Funktionernes tilgængelighed skal vurderes i forhold til den version, der er installeret i enheden.

:::

## Installation af styreenheden

:::danger Afbryd strømforsyningen

Under installation af enheden skal strømforsyningen ubetinget afbrydes, da spændingen på visse komponenter er farlig for liv og helbred. Det anbefales at lade en kvalificeret person udføre installationen.

:::

### Valg af monteringssted

Enheden skal monteres på et sted, der er tilgængeligt for betjeningspersonalet, uden for børns og dyrs rækkevidde og uden direkte sollys. Omgivelsestemperaturområdet er fra −10°C til +40°C. Der skal sikres fri luftcirkulation omkring kabinettet og køleprofilen. Køleprofilen må ikke tildækkes, og enheden må ikke monteres ved varmekilder.

### Montering

Fastgør kabinettets underdel til en plan væg med fire dyvler ved hjælp af monteringshullerne uden for det tætnede rum. Monter dækslet med det medfølgende hængsel. Kontroller pakningens tilstand og placering før lukning.

Anvend kabler med et rundt udvendigt tværsnit, der passer til kabelforskruningerne. Spænd kabelforskruningerne, så de tætner og fastholder kablet. Luk ubenyttede gennemføringer med blindpropper. Spænd dækslet med alle skruer. Tætheden afhænger af korrekt montering af kabinettet og gennemføringerne.

### Forberedelse af forbindelser

Alt arbejde inde i kabinettet skal udføres efter afbrydelse af strømforsyningen og kontrol af spændingsløs tilstand. Hvis afmontering af panelet kræver frakobling af fladkablet, skal det frakobles forsigtigt og sættes korrekt på plads igen, før kabinettet lukkes. Fladkablet må ikke tilsluttes eller frakobles, mens strømforsyningen er tilsluttet.

Signalkablerne INPUT og ENABLE skal føres adskilt fra forsynings- og udgangskablerne. Følg klemmenummereringen på det konkrete eksemplar af enheden. Signalindgangenes stel og beskyttelsesklemmen PE har forskellige funktioner og kan ikke erstatte hinanden.

## Elektrisk tilslutning

:::danger Afbryd strømforsyningen

Kontroller, at strømforsyningen er afbrudt, før kredsløbet tilsluttes!

:::

![Klemmer til forsyning, ventilatorer, GR 2, ENABLE, CAN og INPUT](./img/sc-pe16/zaciski.png)

| KLEMME | FUNKTION |
| --- | --- |
| L, N, PE — forsyning | Forsyning 230 V AC, 50 Hz: L — fase, N — nulleder, PE — beskyttelsesleder. Den oprindelige dokumentation angiver beskyttelse B20; valg af beskyttelsesudstyr og kabler skal tage hensyn til installationen og belastningen. |
| U, N, PE — ventilatorer | U — reguleret faseudgang; N og PE — enhedens tilsvarende fælles klemmer. Summen af ventilatorernes strømme må ikke overstige 16 A. Hver ventilator kræver separat beskyttelse. Anvend motorer, der er godkendt til spændingsregulering. |
| GR 2: C, NO | Galvanisk adskilt relækontakt til gruppe 2. Den sluttes, når det ønskede ventilationsniveau er lig med eller højere end tærsklen »Ventilationsgruppe 2«. Maksimal kontaktstrøm ifølge den leverede vejledning: 6 A. Ved direkte styring af en belastning angiver dokumentationen ekstern beskyttelse B6. |
| INPUT: V, stel | Spændingsindgang. Vælg »Styringstype → Indgang V«. I det analyserede program er reguleringsområdet 2–10 V. Tilslut hverken netspænding eller den regulerede forsyningsudgang til ventilatorerne til denne indgang. |
| INPUT: I, stel | Strømindgang 4–20 mA. Vælg »Styringstype → Indgang I«. Tilslut signalet i overensstemmelse med mærkningerne på kilde og modtager. |

Anvend den valgte indgang V eller I til styring. SC-PE16 kræver sin egen netforsyning; den analoge indgang overfører kun styreværdien.

## ENABLE-indgang og kommunikation

### ENABLE: E og stel

Indgangen fungerer sammen med en potentialfri kontakt. Klemmerne E og stel må kun kortsluttes eller adskilles; der må ikke tilføres ekstern spænding. En sluttet forbindelse tillader drift, mens en brudt forbindelse angiver niveauet 0%. Standsning følger indstillingen »Udløbstid«.

ENABLE-funktionen aktiveres separat for AUTO og MANUAL i menuen »Avanceret → Ventilator«. Begge funktioner er deaktiveret fra fabrikken, så en forbindelsesbøjle er da ikke nødvendig. Åbning af ENABLE er ikke det samme som dvaletilstand: panelet forbliver aktivt. I AUTO springer programmet aflæsningen af styresignalet over og starter ikke safeRUN, når ENABLE-spærringen er aktiv.

### CAN og Wi-Fi

Menupunkterne »Indgang CAN« og »Indgang WiFi« findes i menuen, men udfører ikke styring i softwareversion 2.1: begge funktioner returnerer niveauet 0%. Vælg indgang V eller I for at sætte enheden i drift med dette program. Konfigurer ikke installationen ud fra CAN eller Wi-Fi uden at have fået bekræftet understøttelsen i den installerede softwareversion.

## Funktionsprincip

SC-PE16 er en effektregulator, der udfører kommandoer fra den overordnede styreenhed eller operatøren. Den måler ikke rumtemperaturen og har ikke egne indstillinger for temperatur, udluftning, supplerende opvarmning eller luftindtagsspjæld. Ventilationsniveauet i procent angiver en styreværdi og er ikke en måling af motorens faktiske omdrejningstal.

| NOMINELT SIGNAL | ØNSKET VENTILATIONSNIVEAU |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

Mellem grænseværdierne beregner programmet niveauet lineært og afrunder til hele procent. For indgang V begynder stigningen, når den aflæste værdi overstiger 2,04 V, og for indgang I — 4,04 mA. Udgangens endelige tilstand afhænger også af ENABLE, opstart og termisk beskyttelse.

## Nøddrift og beskyttelsesfunktioner

### safeRUN — bortfald af indgangssignal

I tilstanden AUTO vises alarmen »Indgang«, når den aflæste spænding er under 1,50 V, eller strømmen er under 2,00 mA, afhængigt af den valgte indgang. Programmet angiver da niveauet »Nøddrift« i området 0–100%; fabriksindstillingen er 30%. Når signalet vender tilbage til detektionstærsklen eller derover, ophører indgangsalarmen, og enheden vender tilbage til analog styring.

Områderne 1,50–2,04 V og 2,00–4,04 mA giver niveauet 0% uden indgangsalarm. Signalet 0 V er i denne version ikke en almindelig stopkommando — det aktiverer nøddrift. En overordnet styreenhed med udgang 0–10 V skal konfigureres til området 2–10 V uden afbrydelse til 0 V. I MANUAL styrer det analoge signal ikke ventilationen, og indgangsalarmen nulstilles.

### Termisk beskyttelse

Alarmen »Overophedning« aktiveres, når den aflæste temperatur på køleprofilen overstiger 87°C. Den nulstilles, når temperaturen falder til under 80°C. Under alarmen ændrer programmet det ønskede niveau: for værdier på mindst 50% angiver det 100%, og for værdier under 50% angiver det 0%. Ændringen af udgangen følger opstarts- og udløbsalgoritmen. Beskyttelsen garanterer ikke kontinuerlig ventilationsdrift i alle tilfælde.

Tilstanden for relæ GR 2 bestemmes før den termiske korrektion: dets tilstand afhænger af niveauet før tvangsstyringen til 0% eller 100%. Nøddriftsniveauet er også underlagt termisk korrektion. Ved overophedning skal køleforholdene, tilsmudsning af køleprofilen og belastningen kontrolleres; arbejde inde i kabinettet skal overlades til en autoriseret person.

### byPASS og blød opstart

Ved et stabilt udgangsniveau på 100% aktiverer programmet relæet til omgåelse af fasereguleringskredsløbet. Opstarten kan omfatte optrapning til 100%, fastholdelse på 100% og overgang til det ønskede niveau. Parametrene for »Blød opstart« påvirker også udgangens reaktionshastighed ved ændringer i den ønskede værdi.

## Første idriftsættelse af styreenheden

:::warning Kalibrering af ventilatorer

Advarsel! Ved første idriftsættelse af enheden skal det forbudte driftsområde for motoren ubetinget indstilles.

:::

1. Kontroller tilslutningen af forsyning, PE, ventilatorer og analogt signal, mens strømforsyningen er afbrudt. Bekræft, at motorerne er godkendt til spændingsregulering, og at den samlede strøm er højst 16 A.
2. Tilslut strømforsyningen. Hvis der vises en opfordring til at vælge sprog, skal du trykke på OK og vælge sprog. Lås tastaturet op med knappen med hængelåssymbolet.
3. Vælg »Indgang V« eller »Indgang I« under »Styringstype«. Indstil niveauet »Nøddrift« og tærsklen »Ventilationsgruppe 2«. Aktiver om nødvendigt ENABLE separat for den relevante tilstand.
4. Åbn »Avanceret → Ventilator → Forbudt område«. I dette menupunkt tvinger programmet niveauet til 1%, og ændring af parameteren påvirker straks udgangen. Området er fra −20 til 200, fabriksindstillingen er 0. En positiv værdi øger det minimale styreniveau, mens en negativ værdi reducerer det.
5. Vælg værdien, så alle ventilatorer roterer stabilt uden at standse eller blive overophedede. Observer hver ventilator, helst med hjælp fra en anden person. At spjældet blot løftes, erstatter ikke kontrollen af, at motoren fungerer korrekt. Bekræft med OK; ESC gendanner den tidligere indstilling.
6. Kontroller udgangen ved flere niveauer, herunder 0%, et lavt niveau og 100%. Gentag kalibreringen efter udskiftning af ventilatorerne eller ændring af deres konfiguration.
7. Kontroller i AUTO reaktionen på det minimale og maksimale signal. Kontroller derefter signalafbrydelse og overgang til nøddrift samt tilbagevenden efter genetablering af signalet. Hvis ENABLE er aktivt, skal dets funktion også kontrolleres.
8. Kontroller GR 2 samt alarmsignaleringen i menuen »Test«. Afslut dette menupunkt efter testene, og vælg den ønskede driftstilstand.

:::warning Faktisk aktivering af udgangene

Test og kalibrering styrer de faktiske udgange. De kan starte ventilatorerne, og ventilationstesten tvinger niveauet uafhængigt af den normale styring. Sørg for sikre testforhold og konstant opsyn.

:::

## Programmering af styreenheden

### Frontpanel — indikatorer og knapper

| ELEMENT | BETJENING |
| --- | --- |
| Strøm / dvaletilstand | Knappen med strømsymbolet viser en bekræftelse af dvaletilstand; bekræft med OK. Et nyt tryk vækker enheden. Dvaletilstand sætter udgangene i slukket tilstand; den afbryder ikke netspændingen. |
| Hængelås | Aktiverer eller deaktiverer tastaturlåsen. Efter oplåsning lyser kontrollampen ved hængelåsen. På hovedskærmen aktiveres låsen igen efter cirka 30 s uden aktivitet. |
| A — AUTO | Vælger styring fra den analoge indgang efter bekræftelse med OK. Kontrollampen A angiver den valgte tilstand. |
| M — MANUAL | Vælger manuel styring efter bekræftelse med OK. På hovedskærmen ændrer tasterne + og − indstillingen 0–100%. Kontrollampen M angiver den valgte tilstand. |
| +, −, OK, ESC | OK åbner menuen, åbner et menupunkt og bekræfter værdien. + og − vælger et menupunkt eller ændrer værdien. ESC vender tilbage til det forrige niveau eller annullerer redigeringen. |
| Alarm og gruppe 2 | Den røde kontrollampe angiver en alarm. Kontrollampen ved ventilatorsymbolet »2« angiver aktivering af relæ GR 2. |
| Display | I AUTO viser det det ønskede ventilationsniveau, den aflæste værdi fra den valgte indgang, en søjleindikator samt alarmer. Når ENABLE er aktivt, vises dets tilstand også. I MANUAL angiver hovedværdien den manuelle indstilling; beskyttelsesfunktionerne kan ændre udgangen. |

### Lagring af indstillinger

Menuparametrene gemmes i den ikke-flygtige hukommelse efter bekræftelse med OK. Ændringer af niveauet MANUAL træder straks i kraft og gemmes efter kort tids inaktivitet. Efter strømsvigt gendannes de gemte indstillinger, herunder tilstanden AUTO/MANUAL, det manuelle niveau og dvaletilstanden. Afbryd ikke strømforsyningen umiddelbart efter ændring af den manuelle indstilling.

Ved en forkert kontrolsum eller en værdi uden for området gendanner programmet fabriksindstillingerne. Alle indstillinger skal da kontrolleres igen, især ventilatorkalibrering, styreindgang og nøddrift.

## Funktioner i grundmenuen

| MENU | OMRÅDE / FABRIKSINDSTILLING | BESKRIVELSE |
| --- | --- | --- |
| Styringstype | Indgang V | Valg af V, I, CAN eller Wi-Fi. Anvend V (2–10 V) eller I (4–20 mA) i den analyserede version. CAN og Wi-Fi udfører ikke styring. |
| Ventilationsgruppe 2 | 1–100% / 100% | Indkoblingstærskel for kontakt GR 2. Kontakten er sluttet ved et niveau, der er lig med eller højere end tærsklen, og åben under tærsklen. Programmet definerer ikke en separat hysterese. |
| Nøddrift | 0–100% / 30% | Niveau, der angives ved bortfald af det valgte analoge signal i AUTO. Værdien 0% betyder standsning ved signaltab. |
| Rengøringslås | 60 s | Spærrer tastbetjeningen i 60 sekunder og viser en nedtælling. Ventilationsreguleringen fortsætter. Funktionen er beregnet til aftørring af panelet, ikke til elektrisk arbejde eller vask af enhedens indre. |
| Avanceret | Undermenu | Adgang til test, sprog, ventilatorkalibrering, ENABLE, blød opstart, alarmlyd, fabriksindstillinger og programoplysninger. |

## Funktioner i den avancerede menu

| MENU / PARAMETER | OMRÅDE / FABRIKSINDSTILLING | BESKRIVELSE |
| --- | --- | --- |
| Test → Ventilation | 0–100% | Midlertidig tvangsstyring af den regulerede udgang. Ændringer træder i kraft under redigeringen. Når menupunktet afsluttes med OK eller ESC, genoptages normal styring. |
| Test → Vent. trin 2 | Nej / Ja | Midlertidig tvangsstyring af kontakt GR 2 og dens kontrollampe. |
| Test → Alarm | Nej / Ja | Midlertidig test af alarmsignaleringen, herunder lyden, uafhængigt af den normale indstilling »Alarmsignal«. |
| Sprog | Polsk | Der kan vælges mellem polsk, engelsk og ukrainsk. |
| Ventilator → Forbudt område | −20–200 / 0 | Kalibrering af niveauet 1%. Under redigeringen tvangsstyres den faktiske udgang til 1%. Parameteren er hverken angivet i procent eller sekunder. |
| Ventilator → Aktivering EN AUTO | Nej / Ja; Nej | Gør tilstanden AUTO afhængig af ENABLE-indgangen. |
| Ventilator → Aktivering EN MANUAL | Nej / Ja; Nej | Gør tilstanden MANUAL afhængig af ENABLE-indgangen. |
| Blød opstart → Optrapningstid | 0–50 / 5 | Hastigheden for niveauets stigning under opstart til 100%. En større værdi betyder en langsommere ændring. Værdien 0 springer optrapningsfasen over. |
| Blød opstart → Tid 100% | 0–250 / 100 | Fastholdelse af niveauet 100% under opstart. Værdien 0 springer fastholdelsesfasen over. Hvis både optrapning og fastholdelse indstilles til 0, springes gennemblæsningen til 100% over. |
| Blød opstart → Udløbstid | 0–50 / 5 | Hastigheden for tilpasning til det ønskede niveau, også når det ændres. Værdien 0 betyder en ændring uden gradvis tilpasning. |
| Alarmsignal | Nej / Ja; Nej | Aktiverer den akustiske alarmsignalering. Indstillingen Nej fjerner ikke meddelelsen på skærmen eller signaleringen med kontrollampen. |
| Fabriksindstillinger | Nej / Ja | Ved valg af Ja gendannes og gemmes standardværdierne, herunder kalibrering 0, indgang V, AUTO, nøddrift 30%, tærskel for GR 2 lig med 100% og deaktiveret ENABLE. Konfigurer og kontroller enheden igen efter handlingen. |
| Program | version 2.1 + kompileringsdato | Viser programmets version og kompileringsdato. Denne beskrivelse er udarbejdet på grundlag af de leverede kildefiler SC_PX16_v02. |

Parametrene for blød opstart er enhedsløse indstillinger af programmets tællere og ikke tider angivet i sekunder. Ved 50 Hz svarer et enkelt trin omtrent til (indstilling + 1) × 20 ms: for optrapning og udløb er dette tiden for en ændring på 1 procentpoint, og for »Tid 100%« — fastholdelsestiden. Værdien 0 har den betydning, der er beskrevet i tabellen. De faktiske tider afhænger af algoritmens fase.

## F ejl- og advarselsmeddelelser

| MEDDELELSE | BETYDNING OG FREMGANGSMÅDE |
| --- | --- |
| Indgang | For lav aflæst værdi af det valgte signal i AUTO. Enheden angiver nøddrift. Kontroller signalkilden, kablerne, fælles stel og valget af V/I. |
| Overophedning | Aflæst temperatur på køleprofilen &gt;87°C; nulstilling &lt;80°C. Ventilationen angives som 0% eller 100% i overensstemmelse med beskrivelsen af den termiske beskyttelse. Kontroller køling og belastning. |
| Forsyning | Forstyrrelse af effektkredsløbets synkronisering med elnettet. Kontroller forsyningen og installationen. Ved fuldstændigt strømsvigt fungerer displayet ikke. |
| Hukommelse CRC | Fejl i kontrolsummen eller området for de gemte indstillinger. Programmet gendanner standardværdierne. Kontroller konfigurationen og gentag kalibreringen; kontakt service, hvis fejlen opstår igen. |

## Bemærkninger og advarsler

:::danger Afbryd strømforsyningen

Under installation af enheden skal strømforsyningen ubetinget afbrydes, da spændingen på visse komponenter er farlig for liv og helbred. Det anbefales at lade en kvalificeret person udføre installationen.

:::

Læs vejledningen før installation og brug. Reparationer og arbejde inde i enheden skal overlades til autoriseret personale. Dvaletilstand, tastaturlås, ENABLE og indstillingen 0% udgør ikke en afbrydelse af strømforsyningen og sikrer ikke forsvarlige betingelser for elektrisk arbejde.

Vælg indstillingerne for ventilation og nøddrift efter dyrenes og installationens behov. Kontroller regelmæssigt alle ventilatorers faktiske drift. Signaleringen SC-PE16 erstatter ikke uafhængig overvågning af forholdene i bygningen og strømsvigt. Den viste klemrække har ikke en separat ALARM-kontakt til en alarmcentral.

:::note Bortskaffelse af enheden

Når produktets levetid er udløbet, må det ikke bortskaffes sammen med usorteret husholdningsaffald, men skal bortskaffes i overensstemmelse med gældende lovgivning (Den Europæiske Unions WEEE-direktiver 2012/19/EU).

:::

Produktet er fremstillet i overensstemmelse med RoHS-kravene (Den Europæiske Unions direktiv 2011/65/EU).

## Tekniske data for styreenheden

| PARAMETER | VÆRDI |
| --- | --- |
| Forsyning / egetforbrug | 230 V AC, 50 Hz / &lt;10 W |
| Maksimal samlet strøm på udgang U | 16 A |
| Maksimal strøm for kontakt GR 2 | 6 A; kontakt C–NO, galvanisk adskilt |
| Indgang V / indgang I | 2–10 V / 4–20 mA, vælges i menuen |
| Tærskel for signalbortfald (programmets aflæsning) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Potentialfri kontakt E–stel; aktivering separat for AUTO/MANUAL |
| Termisk beskyttelse (aflæsning af køleprofil) | Alarm &gt;87°C; tilbagevenden &lt;80°C |
| Omgivelsestemperatur / kabinet | −10°C til +40°C / IP65 |
| Mål / overspændingsholdfasthed | 34 × 29 × 12 cm / 210 J |
| Menusprog | Polsk, engelsk, ukrainsk |

Pakkens indhold ifølge den leverede dokumentation: 4 ekspansionsdyvler, 2 kabelforskruninger PG13,5, 1 kabelforskruning PG9 og 1 hængsel.

## Garantibetingelser

Garantibetingelsernes indhold er bevaret fra det leverede producentdokument.

1. Producenten ELETOR med hjemsted i Polen, adresse: Pod Sosno 28, 87-305 Zbiczno (herefter benævnt garantigiveren), yder køberen en kvalitetsgaranti for den vare, som dette garantibevis er udstedt for, forudsat at varen anvendes efter sit formål og i overensstemmelse med de regler, der er fastsat i den brugsanvisning, som køberen har modtaget sammen med varen.
2. Garantiperioden er 24 måneder fra salgsdatoen. Fejl eller mangler ved varen, der viser sig i denne periode, afhjælpes gratis. Efter garantiperiodens udløb eller ved bortfald af garantirettighederne afhjælpes fejl eller mangler mod betaling.
3. Garantien omfatter ikke:

   - enhver mangel, der er opstået som følge af forkert håndtering af varen (herunder udførelse af handlinger, der ikke er beskrevet i brugsanvisningen, osv.);

   - enhver defekt, der er opstået som følge af reparation, ændring osv. udført af andre end garantigiveren;

   - enhver mangel eller skade, der er opstået som følge af transport eller tab af varen, hvis disse hændelser fandt sted efter købet af varen, samt mekaniske skader opstået som følge af brugerens ukorrekte betjening;

   - enhver mangel eller skade, der er opstået som følge af brand, jordskælv, oversvømmelse, lynnedslag eller andre naturkatastrofer, miljøforurening, påvirkning fra ekstern ioniserende stråling eller magnetfelter samt uregelmæssig strømforsyning eller strøm med parametre, der ikke svarer til kravene;

   - enhver mangel, der skyldes ukorrekt opbevaring (f.eks. opbevaring af varen uden for det temperatur- eller fugtighedsområde, der er angivet i specifikationen, eller i nærheden af kemikalier), forkert vedligeholdelse eller rengøring osv.;

   - enhver mangel, der skyldes opbrugte forsyningsbatterier osv.;

   - enhver mangel forårsaget af sand, mudder, støv, vand og andre væsker osv., der er trængt ind i varens kabinet;

   - skader opstået som følge af naturligt, delvist eller fuldstændigt slid på varen i overensstemmelse med dens egenskaber eller formål;

   - handlinger angivet i brugsanvisningen, som brugeren selv er forpligtet til at udføre.

4. Køberen mister garantirettighederne som følge af:

   - enhver reparation eller ændring af varen udført af andre end garantigiveren;

   - konstatering af indgreb i, beskadigelse af eller brud på en hvilken som helst plombering;

   - konstatering af beskadigelse, ændring, tildækning eller fjernelse af serienumre eller andre mærkninger, der identificerer varen.

5. Reparationstiden er op til 21 arbejdsdage fra datoen for anmeldelse af manglen og levering af den komplette vare til garantigiverens servicepunkt. I særligt begrundede tilfælde, hvor det er nødvendigt at indhente dele eller komponenter fra udlandet, eller hvor skaden er særlig kompliceret eller vanskelig at reparere eller diagnosticere, kan reparationstiden forlænges med den periode, der er nødvendig for at opfylde garantiforpligtelserne.
6. Køberens rettigheder i henhold til garantien kan kun gøres gældende ved fremlæggelse af et gyldigt garantibevis, der er korrekt udfyldt på købsdatoen, samt købsbevis (faktura, kvittering osv.). Uautoriserede ændringer af oplysningerne på garantibeviset (herunder overstregninger, udviskninger, tilføjelser osv.) medfører bortfald af garantirettighederne. Et garantibevis uden varens navn, model og serienummer, dato og sted for købet samt sælgerens læselige stempel og underskrift er ugyldigt og kan ikke danne grundlag for en gyldig reklamation.
7. Køberen er forpligtet til for egen regning at levere varen i en emballage, der er egnet til det pågældende udstyr og sikrer sikker og korrekt transport og opbevaring, eller at dække garantigiverens kørselsomkostninger. Hvis det konstateres, at den vare, der er indleveret til reparation, er teknisk funktionsdygtig og uden mangler, eller hvis den konstaterede fejl ikke er omfattet af garantien, pålægges køberen omkostningerne til serviceydelser og transport.
8. Køberen er forpligtet til at afhente den reparerede vare inden for 90 dage fra den dag, hvor garantigiveren har meddelt, at reparationen er udført. Hvis køberen ikke afhenter varen inden for denne frist, bærer køberen risikoen for hændeligt tab eller beskadigelse af varen.
9. Garantiperioden forlænges med reparationens varighed regnet fra datoen for levering af varen til den fastsatte afhentningsdato efter reparationen. Garantigiveren er forpligtet til at udstede et dokument, der angiver perioden og omfanget af de afhjulpne mangler ved varen.

10. Køberen anmelder krav via varens sælger eller direkte til garantigiverens adresse: ELETOR, Pod Sosno 28, 87-305 Zbiczno, Polen.

11. Garantigiveren er ikke ansvarlig:

    - for tabt indkomst som følge af, at en mangel viser sig, og den tid, det tager at afhjælpe den;

    - for tab opstået som følge af, at en mangel viser sig, samt enhver skade, der skyldes forkert installation, brug eller programmering af enhedens funktioner.
