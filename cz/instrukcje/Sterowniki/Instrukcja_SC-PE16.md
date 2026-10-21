---
id: sc-pe16
title: SC-PE16 — návod k obsluze
sidebar_label: SC-PE16
sidebar_position: 5
description: Návod k výkonovému rozšiřujícímu modulu SC-PE16 — montáž, připojení,
  uvedení do provozu, nabídka a ochrany.
slug: /sc-pe16
toc_min_heading_level: 2
toc_max_heading_level: 3
---


Výkonový rozšiřující modul SC-PE16 slouží k řízení ventilátorů, pokud zatížení překračuje možnosti nadřazeného regulátoru. Zařízení reguluje napájecí napětí ventilátorů na základě analogového signálu nebo ručního nastavení. Maximální celkový výstupní proud je 16 A.

![Výkonový rozšiřující modul ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Parametry a vlastnosti

- režimy AUTO a MANUAL a uspání zařízení;
- grafický displej a dotyková klávesnice;
- analogové řízení 2–10 V nebo 4–20 mA;
- programovatelný práh sepnutí 2. skupiny ventilace;
- byPASS při ustálené úrovni 100%;
- tepelná ochrana výkonového obvodu;
- safeRUN: nastavitelná úroveň nouzového provozu;
- kalibrace minimální úrovně ventilace;
- test ventilace, relé a alarmu;
- zámek klávesnice a zámek pro čištění;
- polský, anglický nebo ukrajinský jazyk;
- napájení 230 V AC, 50 Hz; kryt IP65.

:::info Verze softwaru

Popis funkcí se vztahuje na dodaný software **ver. 2.1**. Dostupnost funkcí je nutné posuzovat podle verze nainstalované v zařízení.

:::

## Instalace regulátoru

:::danger Odpojte napájení

Během instalace zařízení je bezpodmínečně nutné odpojit přívod elektrické energie, protože napětí na některých součástech je životu a zdraví nebezpečné. Doporučuje se svěřit instalaci kvalifikované osobě.

:::

### Výběr místa montáže

Zařízení je nutné namontovat na místo přístupné obsluze, mimo dosah dětí a zvířat, bez přímého slunečního záření. Rozsah okolní teploty je od −10°C do +40°C. Kolem krytu a chladiče je nutné zajistit volné proudění vzduchu. Nezakrývejte chladič ani nemontujte zařízení v blízkosti zdrojů tepla.

### Montáž

Spodní část krytu připevněte na rovnou stěnu čtyřmi hmoždinkami s využitím montážních otvorů mimo utěsněnou komoru. Víko namontujte pomocí závěsu dodaného v sadě. Před uzavřením zkontrolujte stav a uložení těsnění.

Používejte kabely s kruhovým vnějším průřezem, odpovídající kabelovým vývodkám. Kabelové vývodky utáhněte tak, aby kabel utěsnily a zajistily proti pohybu. Nepoužité průchodky zaslepte. Víko dotáhněte všemi šrouby. Těsnost závisí na správné montáži krytu a průchodek.

### Příprava připojení

Veškeré práce uvnitř krytu provádějte po odpojení napájení a ověření beznapěťového stavu. Pokud sejmutí panelu vyžaduje odpojení plochého kabelu, opatrně jej odpojte a před uzavřením krytu znovu zapojte. Nepřipojujte ani neodpojujte plochý kabel při zapnutém napájení.

Signálové kabely INPUT a ENABLE veďte odděleně od napájecích a výstupních kabelů. Řiďte se označením svorek na konkrétním kusu zařízení. Signálová zem vstupů a ochranná svorka PE plní různé funkce a nejsou zaměnitelné.

## Elektrické připojení

:::danger Odpojte napájení

Před připojením obvodu se ujistěte, že je napájení vypnuté!

:::

![Svorky napájení, ventilátorů, GR 2, ENABLE, CAN a INPUT](./img/sc-pe16/zaciski.png)

| SVORKA | ÚČEL |
| --- | --- |
| L, N, PE — napájení | Napájení 230 V AC, 50 Hz: L — fáze, N — střední vodič, PE — ochranný vodič. V původní dokumentaci je uvedeno jištění B20; výběr jištění a vodičů musí zohledňovat instalaci a zatížení. |
| U, N, PE — ventilátory | U — regulovaný fázový výstup; N a PE — příslušné společné svorky zařízení. Součet proudů ventilátorů nesmí překročit 16 A. Každý ventilátor vyžaduje samostatné jištění. Používejte motory schválené pro napěťovou regulaci. |
| GR 2: C, NO | Oddělený kontakt relé 2. skupiny. Sepne, když je požadovaná úroveň ventilace rovna prahu „Skupina 2 ventilace“ nebo vyšší. Maximální proud kontaktu podle dodaného návodu: 6 A. Při přímém řízení zátěže dokumentace uvádí externí jištění B6. |
| INPUT: V, zem | Napěťový vstup. Vyberte „Typ řízení → Vstup V“. V posuzovaném programu je rozsah regulace 2–10 V. Nepřipojujte k tomuto vstupu síťové napětí ani regulovaný napájecí výstup ventilátorů. |
| INPUT: I, zem | Proudový vstup 4–20 mA. Vyberte „Typ řízení → Vstup I“. Signál připojujte podle označení zdroje a přijímače. |

Pro řízení používejte vybraný vstup V nebo I. SC-PE16 vyžaduje vlastní síťové napájení; analogový vstup přenáší pouze řídicí hodnotu.

## Vstup ENABLE a komunikace

### ENABLE: E a zem

Vstup spolupracuje s bezpotenciálovým kontaktem. Svorky E a zem je dovoleno pouze spojovat nebo rozpojovat; nepřivádějte externí napětí. Spojení povoluje provoz, rozpojení zadává úroveň 0%. Zastavení se řídí nastavením „Doba doběhu“.

Obsluha ENABLE se zapíná samostatně pro AUTO a MANUAL v nabídce „Pokročilé → Ventilátor“. Obě funkce jsou z výroby vypnuté, takže propojka tehdy není nutná. Rozpojení ENABLE není totéž co uspání: panel zůstává aktivní. V AUTO při aktivním blokování ENABLE program přeskakuje čtení řídicího signálu a nespouští safeRUN.

### CAN a Wi-Fi

Položky „Vstup CAN“ a „Vstup WiFi“ jsou v nabídce přítomny, ale v softwaru ver. 2.1 nezajišťují řízení: obě funkce vracejí úroveň 0%. Pro uvedení zařízení s tímto programem do provozu vyberte vstup V nebo I. Nekonfigurujte instalaci na základě CAN nebo Wi-Fi bez potvrzení podpory v nainstalované verzi softwaru.

## Princip činnosti

SC-PE16 je regulátor výkonu vykonávající povely nadřazeného regulátoru nebo obsluhy. Neměří teplotu v místnosti a nemá vlastní nastavení teploty, provětrávání, přitápění ani přívodních klapek. Procentní úroveň ventilace znamená řídicí hodnotu, nikoli měření skutečných otáček motoru.

| JMENOVITÝ SIGNÁL | POŽADOVANÁ ÚROVEŇ VENTILACE |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

Mezi mezními hodnotami program určuje úroveň lineárně a zaokrouhluje na celá procenta. Pro vstup V začíná nárůst po překročení odečtené hodnoty 2,04 V a pro vstup I — 4,04 mA. Konečný stav výstupu závisí také na ENABLE, rozběhu a tepelné ochraně.

## Nouzový provoz a ochrany

### safeRUN — ztráta vstupního signálu

V režimu AUTO se alarm „Vstup“ objeví při odečtené hodnotě napětí pod 1,50 V nebo proudu pod 2,00 mA, podle vybraného vstupu. Program pak zadává úroveň „Nouzový provoz“ v rozsahu 0–100%; z výroby 30%. Po návratu signálu na práh detekce nebo nad něj alarm vstupu zanikne a zařízení se vrátí k analogovému řízení.

Rozsah 1,50–2,04 V a 2,00–4,04 mA poskytuje úroveň 0% bez alarmu vstupu. Signál 0 V není v této verzi běžným povelem k zastavení — spouští nouzový provoz. Nadřazený regulátor s výstupem 0–10 V je nutné nakonfigurovat na rozsah 2–10 V bez snížení na 0 V. V MANUAL analogový signál neřídí ventilaci a alarm vstupu se ruší.

### Tepelná ochrana

Alarm „Přehřátí“ se aktivuje, když odečtená teplota chladiče překročí 87°C. Zruší se po poklesu pod 80°C. Během alarmu program mění požadovanou úroveň: pro hodnoty alespoň 50% zadává 100% a pro hodnoty pod 50% zadává 0%. Změna výstupu podléhá algoritmu rozběhu a doběhu. Ochrana nezaručuje nepřetržitý provoz ventilace ve všech případech.

Stav relé GR 2 se určuje před tepelnou korekcí: závisí na úrovni před vynucením 0% nebo 100%. Úroveň nouzového provozu rovněž podléhá tepelné korekci. Při přehřátí zkontrolujte podmínky chlazení, znečištění chladiče a zatížení; práce uvnitř krytu svěřte oprávněné osobě.

### byPASS a plynulý rozběh

Při ustálené výstupní úrovni 100% program sepne relé přemostění obvodu fázové regulace. Rozběh může zahrnovat nárůst na 100%, udržování na 100% a přechod na požadovanou úroveň. Parametry „Plynulý rozběh“ ovlivňují také rychlost reakce výstupu na změnu požadavku.

## První uvedení regulátoru do provozu

:::warning Kalibrace ventilátorů

Pozor! Při prvním uvedení zařízení do provozu je bezpodmínečně nutné nastavit zakázané pásmo provozu motoru.

:::

1. Při odpojeném napájení zkontrolujte připojení napájení, PE, ventilátorů a analogového signálu. Ověřte schválení motorů pro napěťovou regulaci a celkový proud do 16 A.
2. Zapněte napájení. Pokud se zobrazí nabídka výběru jazyka, stiskněte OK a vyberte jazyk. Odemkněte klávesnici tlačítkem se symbolem zámku.
3. V položce „Typ řízení“ vyberte „Vstup V“ nebo „Vstup I“. Nastavte úroveň „Nouzový provoz“ a práh „Skupina 2 ventilace“. V případě potřeby aktivujte ENABLE samostatně pro příslušný režim.
4. Přejděte do „Pokročilé → Ventilátor → Zakázané pásmo“. V této položce program vynucuje úroveň 1% a změna parametru se okamžitě projeví na výstupu. Rozsah je od −20 do 200, z výroby 0. Kladná hodnota zvyšuje minimální úroveň řízení, záporná ji snižuje.
5. Zvolte hodnotu tak, aby se všechny ventilátory otáčely stabilně, bez zastavování a nadměrného zahřívání. Sledujte každý ventilátor, nejlépe s pomocí druhé osoby. Samotné nadzvednutí klapky nenahrazuje kontrolu správného chodu motoru. Potvrďte OK; ESC obnoví předchozí nastavení.
6. Zkontrolujte výstup při několika úrovních, včetně 0%, nízké úrovně a 100%. Po výměně ventilátorů nebo změně jejich konfigurace kalibraci zopakujte.
7. V AUTO zkontrolujte reakci na minimální a maximální signál. Poté zkontrolujte přerušení signálu a přechod na nouzový provoz i návrat po obnovení signálu. Pokud je ENABLE aktivní, zkontrolujte také jeho funkci.
8. Zkontrolujte GR 2 a signalizaci alarmu v nabídce „Testování“. Po dokončení testů tuto položku opusťte a vyberte cílový provozní režim.

:::warning Skutečná aktivace výstupů

Testování a kalibrace ovládají skutečné výstupy. Mohou spustit ventilátory a test ventilace vynucuje úroveň nezávisle na běžném řízení. Zajistěte bezpečné podmínky zkoušky a trvalý dohled.

:::

## Programování regulátoru

### Přední panel — indikátory a tlačítka

| PRVEK | OBSLUHA |
| --- | --- |
| Napájení / uspání | Tlačítko se symbolem napájení zobrazí potvrzení uspání; potvrďte OK. Opětovným stisknutím zařízení probudíte. Uspání zadává výstupům vypnutý stav; neodpojuje síťové napětí. |
| Zámek | Zapíná nebo vypíná zámek klávesnice. Po odemknutí kontrolka u zámku svítí. Na hlavní obrazovce se zámek znovu aktivuje přibližně po 30 s nečinnosti. |
| A — AUTO | Po potvrzení OK vybere řízení z analogového vstupu. Kontrolka A indikuje vybraný režim. |
| M — MANUAL | Po potvrzení OK vybere ruční řízení. Na hlavní obrazovce tlačítka + a − mění nastavení 0–100%. Kontrolka M indikuje vybraný režim. |
| +, −, OK, ESC | OK otevírá nabídku, vstupuje do položky a potvrzuje hodnotu. + a − vybírají položku nebo mění hodnotu. ESC se vrací na předchozí úroveň nebo ruší úpravu. |
| Alarm a skupina 2 | Červená kontrolka signalizuje alarm. Kontrolka u symbolu ventilátoru „2“ signalizuje sepnutí relé GR 2. |
| Displej | V AUTO zobrazuje požadovanou úroveň ventilace, odečtenou hodnotu vybraného vstupu, sloupcový indikátor a alarmy. Při aktivním ENABLE zobrazuje také jeho stav. V MANUAL hlavní hodnota znamená ruční nastavení; ochrany mohou změnit výstup. |

### Ukládání nastavení

Parametry nabídky se ukládají do energeticky nezávislé paměti po potvrzení OK. Změny úrovně MANUAL se projeví okamžitě a k uložení dojde po krátké nečinnosti. Po výpadku napájení se obnoví uložená nastavení, včetně režimu AUTO/MANUAL, ruční úrovně a stavu uspání. Nevypínejte napájení bezprostředně po změně ručního nastavení.

V případě chybného kontrolního součtu nebo hodnoty mimo rozsah program obnoví tovární hodnoty. Poté je nutné znovu zkontrolovat všechna nastavení, zejména kalibraci ventilátorů, řídicí vstup a nouzový provoz.

## Funkce základní nabídky

| NABÍDKA | ROZSAH / Z VÝROBY | POPIS |
| --- | --- | --- |
| Typ řízení | Vstup V | Výběr V, I, CAN nebo Wi-Fi. Pro posuzovanou verzi používejte V (2–10 V) nebo I (4–20 mA). CAN a Wi-Fi nezajišťují řízení. |
| Skupina 2 ventilace | 1–100% / 100% | Práh sepnutí kontaktu GR 2. Kontakt je sepnutý při úrovni rovné prahu nebo vyšší, rozepnutý pod prahem. Program nedefinuje samostatnou hysterezi. |
| Nouzový provoz | 0–100% / 30% | Úroveň zadávaná při ztrátě vybraného analogového signálu v AUTO. Hodnota 0% znamená zastavení při ztrátě signálu. |
| Zámek pro čištění | 60 s | Na 60 sekund zablokuje ovládání tlačítek a zobrazí odpočítávání. Regulace ventilace funguje dále. Funkce slouží k otření panelu, nikoli k elektrickým pracím nebo mytí vnitřku. |
| Pokročilé | Podnabídka | Přístup k testům, jazyku, kalibraci ventilátoru, ENABLE, plynulému rozběhu, zvuku alarmu, továrnímu nastavení a informacím o programu. |

## Funkce pokročilé nabídky

| NABÍDKA / PARAMETR | ROZSAH / Z VÝROBY | POPIS |
| --- | --- | --- |
| Testování → Ventilace | 0–100% | Dočasné vynucení regulovaného výstupu. Změny se projevují během úprav. Po opuštění pomocí OK nebo ESC se obnoví běžné řízení. |
| Testování → Vent. 2 stupně | Ne / Ano | Dočasné vynucení kontaktu GR 2 a jeho kontrolky. |
| Testování → Alarm | Ne / Ano | Dočasný test alarmové signalizace, včetně zvuku, nezávisle na běžném nastavení „Signál alarmu“. |
| Jazyk | Polština | Na výběr polština, angličtina a ukrajinština. |
| Ventilátor → Zakázané pásmo | −20–200 / 0 | Kalibrace úrovně 1%. Během úprav je vynucován skutečný výstup 1%. Parametr není vyjádřen v procentech ani v sekundách. |
| Ventilátor → Aktivace EN AUTO | Ne / Ano; Ne | Zapíná závislost režimu AUTO na vstupu ENABLE. |
| Ventilátor → Aktivace EN MANUAL | Ne / Ano; Ne | Zapíná závislost režimu MANUAL na vstupu ENABLE. |
| Plynulý rozběh → Doba rozběhu | 0–50 / 5 | Rychlost nárůstu úrovně při rozběhu na 100%. Vyšší hodnota znamená pomalejší změnu. Hodnota 0 vynechává fázi nárůstu. |
| Plynulý rozběh → Doba 100% | 0–250 / 100 | Udržování úrovně 100% během rozběhu. Hodnota 0 vynechává fázi udržování. Současné nastavení rozběhu a udržování na 0 vynechává profouknutí na 100%. |
| Plynulý rozběh → Doba doběhu | 0–50 / 5 | Rychlost dosažení požadované úrovně, také při její změně. Hodnota 0 znamená změnu bez postupného přechodu. |
| Signál alarmu | Ne / Ano; Ne | Zapíná zvuk signalizující alarm. Nastavení Ne neodstraňuje hlášení na obrazovce ani signalizaci kontrolkou. |
| Tovární nastavení | Ne / Ano | Po výběru Ano obnoví a uloží výchozí hodnoty, včetně kalibrace 0, vstupu V, AUTO, nouzového provozu 30%, prahu GR 2 rovného 100% a vypnutého ENABLE. Po provedení operace zařízení znovu nakonfigurujte a zkontrolujte. |
| Program | ver. 2.1 + datum kompilace | Zobrazuje verzi a datum kompilace programu. Tento popis byl vypracován na základě dodaných zdrojů SC_PX16_v02. |

Parametry plynulého rozběhu jsou bezrozměrná nastavení čítačů programu, nikoli časy uvedené v sekundách. Při 50 Hz odpovídá jeden krok přibližně (nastavení + 1) × 20 ms: pro rozběh a doběh jde o dobu změny o 1 procentní bod, pro „Doba 100%“ — dobu udržování. Hodnota 0 má význam popsaný v tabulce. Skutečné časy závisí na fázi algoritmu.

## Chybová a výstražná hlášení

| HLÁŠENÍ | VÝZNAM A POSTUP |
| --- | --- |
| Vstup | Příliš nízká odečtená hodnota vybraného signálu v AUTO. Zařízení zadává nouzový provoz. Zkontrolujte zdroj signálu, kabely, společnou zem a výběr V/I. |
| Přehřátí | Odečtená hodnota chladiče &gt;87°C; zrušení &lt;80°C. Ventilace je zadávána jako 0% nebo 100% podle popisu tepelné ochrany. Zkontrolujte chlazení a zatížení. |
| Napájení | Porucha synchronizace výkonového obvodu se sítí. Zkontrolujte napájení a instalaci. Při úplném výpadku napájení displej nefunguje. |
| Paměť CRC | Chyba kontrolního součtu nebo rozsahu uložených nastavení. Program obnoví výchozí hodnoty. Zkontrolujte konfiguraci a zopakujte kalibraci; při opakované chybě kontaktujte servis. |

## Poznámky a varování

:::danger Odpojte napájení

Během instalace zařízení je bezpodmínečně nutné odpojit přívod elektrické energie, protože napětí na některých součástech je životu a zdraví nebezpečné. Doporučuje se svěřit instalaci kvalifikované osobě.

:::

Před instalací a používáním se seznamte s návodem. Opravy a práce uvnitř zařízení svěřujte oprávněnému personálu. Uspání, zámek klávesnice, ENABLE ani nastavení 0% nepředstavují odpojení napájení a nezajišťují bezpečné podmínky pro elektrické práce.

Nastavení ventilace a nouzového provozu volte podle potřeb zvířat a instalace. Pravidelně kontrolujte skutečný chod všech ventilátorů. Signalizace SC-PE16 nenahrazuje nezávislé sledování podmínek v objektu a výpadku napájení. Na zobrazené svorkovnici není samostatný kontakt ALARM pro ústřednu.

:::note Likvidace zařízení

Po ukončení používání výrobku jej nevyhazujte společně s netříděným komunálním odpadem, ale zlikvidujte jej v souladu s platnými předpisy (směrnice WEEE Evropské unie 2012/19/EU).

:::

Výrobek byl vyroben v souladu s požadavky RoHS (směrnice Evropské unie 2011/65/EU).

## Technické údaje regulátoru

| PARAMETR | HODNOTA |
| --- | --- |
| Napájení / vlastní příkon | 230 V AC, 50 Hz / &lt;10 W |
| Maximální celkový proud výstupu U | 16 A |
| Maximální proud kontaktu GR 2 | 6 A; kontakt C–NO, oddělený |
| Vstup V / vstup I | 2–10 V / 4–20 mA, volitelné v nabídce |
| Práh ztráty signálu (hodnota odečtená programem) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Bezpotenciálový kontakt E–zem; aktivace samostatně pro AUTO/MANUAL |
| Tepelná ochrana (odečtená hodnota chladiče) | Alarm &gt;87°C; návrat &lt;80°C |
| Okolní teplota / kryt | −10°C do +40°C / IP65 |
| Rozměry / přepěťová odolnost | 34 × 29 × 12 cm / 210 J |
| Jazyky nabídky | Polština, angličtina, ukrajinština |

Obsah sady podle dodané dokumentace: 4 hmoždinky, 2 kabelové vývodky PG13,5, 1 kabelová vývodka PG9 a 1 závěs.

## Záruční podmínky

Znění záručních podmínek bylo zachováno z dodaného dokumentu výrobce.

1. Výrobce ELETOR se sídlem v Polsku, adresa: Pod Sosno 28, 87-305 Zbiczno (dále jen poskytovatel záruky), poskytuje Kupujícímu záruku na jakost zboží, pro které byl vystaven tento záruční list, za podmínky používání v souladu s jeho určením a zásadami stanovenými v návodu k obsluze předaném Kupujícímu spolu s tímto zbožím.
2. Záruční doba činí 24 měsíce od data prodeje. Poruchy nebo vady zboží zjištěné v této době budou odstraněny bezplatně. Po uplynutí záruční doby nebo při ztrátě záručních práv budou poruchy nebo vady odstraňovány za úplatu.
3. Záruka se nevztahuje na:

   - jakékoli vady, které vznikly v důsledku nesprávného zacházení se zbožím (zahrnuje to provádění úkonů, které nejsou popsány v návodu k obsluze, apod.);

   - jakékoli závady vzniklé v důsledku opravy, úpravy apod. provedené jinou osobou než poskytovatelem záruky;

   - jakékoli vady nebo poškození, které vznikly v důsledku přepravy nebo pádu zboží, pokud k těmto událostem došlo až po zakoupení zboží, a mechanická poškození vzniklá v důsledku nesprávné obsluhy uživatelem;

   - jakékoli vady nebo poškození, které vznikly v důsledku požáru, zemětřesení, povodně, úderu blesku nebo jiných živelních pohrom, znečištění životního prostředí, působení vnějšího ionizujícího záření nebo magnetického pole a nepravidelných dodávek elektrického proudu nebo proudu s parametry neodpovídajícími požadavkům;

   - jakékoli vady vyplývající z nesprávného skladování (např. skladování zboží mimo rozsah teplot nebo vlhkosti uvedený ve specifikaci, v blízkosti chemických látek), nesprávné údržby nebo čištění apod.;

   - jakékoli vady vyplývající z vybití napájecích baterií apod.;

   - jakékoli vady způsobené pískem, blátem, prachem, vodou a jinými kapalinami apod., které pronikly dovnitř krytu zboží;

   - poškození vzniklá v důsledku přirozeného, částečného nebo úplného opotřebení zboží v souladu s vlastnostmi nebo určením zboží;

   - úkony uvedené v návodu k obsluze, které je uživatel povinen provádět sám.

4. Kupující ztrácí záruční práva v důsledku:

   - provedení jakékoli opravy či úpravy zboží jinou osobou než poskytovatelem záruky;

   - zjištění porušení, poškození nebo stržení kterékoli z plomb;

   - zjištění poškození, porušení, zakrytí nebo odstranění sériových čísel či jiných označení identifikujících zboží.

5. Lhůta opravy činí až 21 pracovních dnů od data nahlášení vady a dodání kompletního zboží do servisního místa poskytovatele záruky. Ve zvlášť odůvodněných případech souvisejících s nutností dovozu prvků nebo součástí ze zahraničí nebo se zvlášť složitým či obtížně opravitelným nebo diagnostikovatelným poškozením může být lhůta opravy prodloužena o dobu nezbytnou ke splnění záručních povinností.
6. Práva Kupujícího ze záruky lze uplatnit pouze po předložení platného záručního listu řádně vyplněného v den nákupu a dokladu o koupi (faktura, účtenka apod.). Svévolné změny zápisů v záručním listu (včetně přeškrtnutí, vymazání, doplnění apod.) způsobují ztrátu práv ze záruky. Záruční list bez názvu, modelu, sériového čísla zboží, data a místa nákupu zboží a čitelného razítka a podpisu Prodávajícího je neplatný a není podkladem pro účinné uplatnění reklamace.
7. Kupující je povinen dodat zboží na vlastní náklady v obalu vhodném pro dané zařízení, který zajišťuje bezpečnou a správnou přepravu a skladování, nebo uhradit náklady na výjezd poskytovatele záruky. Pokud se zjistí, že zboží předané k opravě je technicky funkční a bez vad nebo že se na zjištěnou poruchu záruka nevztahuje, budou Kupujícímu účtovány náklady na služby a přepravu.
8. Kupující je povinen vyzvednout opravené zboží do 90 dnů ode dne oznámení opravy poskytovatelem záruky. Pokud kupující zboží v této lhůtě nevyzvedne, nese riziko náhodné ztráty nebo poškození zboží.
9. Záruční doba se prodlužuje o dobu trvání opravy počítanou od data dodání zboží do stanoveného termínu vyzvednutí po opravě. Poskytovatel záruky je povinen vydat doklad potvrzující dobu a rozsah odstraněných vad zboží.

10. Kupující uplatňuje nároky prostřednictvím Prodávajícího zboží nebo přímo na adrese poskytovatele záruky: ELETOR, Pod Sosno 28, 87-305 Zbiczno, Polsko.

11. Poskytovatel záruky nenese odpovědnost:

    - za ušlé příjmy v důsledku projevení vady a doby jejího odstranění;

    - za ztráty vzniklé v důsledku projevení vady a veškeré škody vyplývající z nesprávné instalace, používání nebo naprogramování funkcí zařízení.
