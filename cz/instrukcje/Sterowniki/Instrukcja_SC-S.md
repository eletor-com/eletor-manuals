---
sidebar_position: 2
title: Návod SC-S
description: Regulátor klimatu pro stájové prostory s přípustným výstupním proudem
  do 5A
keywords:
- eletor sc-s
- regulátor ventilace
- regulátor klimatu
- regulátor ventilace vepřína
- regulátor mikroklimatu
- regulátor pro vepříny
- ventilace vepřína
- regulátor pro odchovny
---


# Regulátor SC-S

Mikroprocesorový regulátor klimatu patřící do řady SPEED CONTROL. Spolehlivý regulátor se snadnou montáží a obsluhou, se softwarem v polštině, angličtině, ruštině a němčině. Program regulátoru umožňuje intuitivní zadávání parametrů: teplot, provětrávání, přitápění, min./max. úrovní ventilace a alarmů.

**Parametry a vlastnosti:**  
- Ventilace I. skupiny:
  - max. proud výstupu plynulé regulace 6A,
  - tepelná ochrana obvodu,
  - pozvolný rozběh ventilace,
  - kalibrace minimálních otáček
- Ventilace II skupiny, oddělený kontakt do 3A (1 volitelně)
- Přitápění, oddělený kontakt do 3A (1 volitelně)
- Alarmové výstupy NO a NC:
  - signalizace výpadku napájení,
  - signalizace překročení min. nebo max. mezní teploty
- 1 analogový vstup pro měření teploty
- 2 výstupy 0-10V
- Příkon obvodu < 3W
- Hermetický kryt IP56
- Napájecí napětí 230VAC 50Hz

## Instalace regulátoru  
:::danger 
Během instalace zařízení je bezpodmínečně nutné odpojit přívod elektrické energie, protože napětí na některých součástech je nebezpečné pro život a zdraví.  
Doporučuje se svěřit instalaci kvalifikované osobě.
:::

### Volba místa montáže  

Místo montáže je nutné zvolit uvážlivě s ohledem na snadný přístup oprávněných osob k přístroji a nepřístupnost pro zvířata a děti. Je nutné zohlednit také klimatické podmínky, tzn. zařízení má pracovat v rozsahu teplot -10°C až 40°C, na místě nevystaveném slunečnímu záření. Kolem zařízení musí být zajištěno volné proudění vzduchu. Součástí zařízení je snímač teploty. Pro montáž snímače teploty platí několik zásad:  
- snímač nesmí být namontován na místě bez cirkulace vzduchu nebo vystaveném přímému slunečnímu záření
- snímač nesmí být namontován na nosné (vnější) stěně budovy,
- vyhněte se blízkosti zařízení vyzařujících teplo, jako jsou topná tělesa a svítidla,
- snímač nesmí být umístěn přímo u dveří a ventilačních otvorů,
- snímač nesmí být umístěn na místech přístupných zvířatům,
- doporučuje se vést kabel připojující snímač mimo napájecí kabely.

### Montáž  

Zařízení může pracovat v náročných klimatických podmínkách. Správně namontovaný regulátor a snímač teploty jsou odolné vůči působení prostředí.
Při montáži je nutné věnovat pozornost následujícím 사항ům:  
- před sešroubováním je nutné zkontrolovat těsnění víka,
- víko musí být dotaženo všemi šrouby,
- kabely použité k připojení regulátoru musí být kulaté,
- po připojení kabelu je nutné dotáhnout kabelové vývodky tak, aby byl kabel utěsněn a zajištěn proti pohybu, doporučuje se použití silikonu,
- nepoužité průchody (vývodky) je nutné zaslepit,
- regulátor (spodní část krytu) upevněte na rovnou stěnu pomocí 4 rozpěrných hmoždinek.

## Elektrické zapojení  

:::danger 
Před připojením obvodu se ujistěte, že je napájení vypnuté!
:::

Před zahájením připojování regulátoru je nutné odšroubovat a sejmout víko. Kabely protáhněte pryžovými vývodkami a poté je můžete připojit. Svorky regulátoru jsou znázorněny na následujícím obrázku.

![Zapojení](./img/Sc-s2.png)

**Svorkovnici AC 230V** připojte k napájení (rozváděči). Je vyžadováno použití nadproudového jističe 1P-B6 a svodičů přepětí typu T1 T2. Při připojování několika zařízení je vhodné rozdělit regulátory do skupin na různé „fáze“ (L1, L2, L3), aby bylo napájecí vedení zatíženo rovnoměrně.  
**Svorkovnici FAN** je nutné připojit přímo k ventilátoru, při řízení několika ventilátorů nesmí celkové zatížení překročit 6A, každý ventilátor musí být jištěn samostatně. PE a N nesmí být vedeny z napájení (rozváděče), musí být bezpodmínečně připojeny ke svorkám regulátoru.  
**Svorkovnice FUNCTION** je oddělený reléový výstup, maximální proud kontaktu je 6A (při přímém řízení zátěže je vyžadován externí nadproudový jistič 1P-B6),
lze jej využít jako:  
- **Přitápění** – kontakt sepne při poklesu měřené teploty pod nastavenou hodnotu.  
- **Ventilace 2 skupiny nebo skrápěcích systémů** – kontakt sepne, pokud je měřená teplota vyšší než součet požadované teploty a pásma ventilace.  kontakt sepne, pokud je měřená teplota vyšší než součet požadované teploty a pásma ventilace.  

Následující obrázek znázorňuje způsob připojení ventilátoru 2 skupiny nebo ohřívače.  

![Druhá skupina](./img/2grupa.png)

**Svorkovnice ALARM** má oddělené výstupy NC, C a NO sloužící k připojení k alarmové ústředně. Alarm se aktivuje v následujících případech:  
- teplota je příliš nízká nebo příliš vysoká,
- došlo k poškození regulátoru nebo snímače teploty,
- došlo k výpadku napájecího napětí regulátoru;
- došlo k nesprávné činnosti regulátoru (např. přehřátí regulátoru)  

![Alarm](./img/alarmsc-s.png)  

**Svorkovnice V1 0-10V** slouží k připojení modulů pro rozšíření výkonu nebo ventilátorů s vestavěným obvodem regulace otáček. Napětí na této svorce je úměrné úrovni ventilace.  
**Svorkovnice V2 0-10V** slouží k připojení servopohonu otevírajícího klapky přívodu vzduchu.  
**Svorkovnici SENSOR** připojte k 1 snímači teploty TS3 nebo TS5, na polaritě nezáleží.  Je vhodné vést měřicí kabely mimo napájecí kabely.  
**Svorkovnici RS-485** lze využít k vytváření ventilačních systémů a ke komunikaci s počítačem PC.  

## Princip činnosti  

Hlavním úkolem regulátoru je udržovat teplotu v chovném prostoru na úrovni stanovené chovatelem. Je nutné mít na paměti, že regulátor je pouze nástrojem, který má pomoci zajistit optimální klimatické podmínky v chovném prostoru. Hlavní úlohu v tomto procesu však plní chovatel, který musí přizpůsobovat nastavení zařízení měnícím se venkovním klimatickým podmínkám, a především požadavkům zvířat ve stáji, a sledovat provozní stav zařízení pomocí alarmové ústředny.  

### První spuštění regulátoru  

:::danger
Při prvním spuštění regulátoru je bezpodmínečně nutné nastavit zakázané pásmo provozu motoru.
:::

Regulátor spolupracuje s ventilátory s jednofázovým asynchronním motorem s maximálním celkovým odběrem proudu 5A. Po připojení zvolených ventilátorů je uživatel musí přizpůsobit pro spolupráci s regulátorem. Jinými slovy je nutné nastavit minimální provozní úroveň (otáčky) ventilátoru. Tato funkce se nazývá **„Zakázané pásmo”** a uživatel ji nastavuje jednorázově v **„Pokročilých nastaveních”**. Pro správné provedení tohoto úkonu se doporučuje pomoc druhé osoby, která může nepřetržitě sledovat chování ventilátoru, zatímco druhá osoba nastavuje hodnotu **„Zakázaného pásma”**. Nenastavení zakázaného pásma může vést k nesprávné činnosti zařízení. Hodnotu **„Zakázaného pásma”** lze považovat za správnou v okamžiku, kdy tlak vytvořený ventilátorem začne mírně nadzvedávat klapky ventilačního komína. Nastavení **„Zakázaného pásma”** je nutné provést znovu při výměně ventilátoru připojeného k regulátoru.  

### Periodické provětrávání  

Provětrávání je funkce prováděná regulátorem, která se spustí v okamžiku, kdy teplota v místnosti klesne pod požadovanou teplotu. Tato funkce zajišťuje zvířatům pravidelný přívod čerstvého vzduchu. Provětrávání definují 3 parametry:
- **„Doba chodu”** - určuje, na kolik sekund má být ventilátor zapnut,
- **„Doba přestávky”** - určuje dobu odstávky ventilátoru v sekundách,
- **„Úroveň provětrávání”** - určuje výkon ventilace během „Doby chodu”.  

Příklad nastavení **60s/120s** znamená, že ventilátor je zapínán na 60s s přestávkou mezi jednotlivými zapnutími 120s. 

Všechny výše uvedené parametry nastavuje uživatel. Při nastavování parametrů provětrávání je nutné mít na paměti několik zásad:
- provětrávání se zapíná výhradně v situaci, kdy teplota ve vepříně klesne pod požadovanou teplotu,
- základní funkcí provětrávání je zajistit zvířatům pravidelný přívod čerstvého vzduchu, nikoli udržovat požadovanou teplotu v místnosti,
- doporučuje se provětrávat prostory krátce, ale často,
- je nutné vyvarovat se dlouhých dob provětrávání, protože to může vést k příliš velkému kolísání teploty,
- nastavované parametry je bezpodmínečně nutné přizpůsobovat chování zvířat a podmínkám uvnitř i vně místnosti,
- funkci provětrávání lze vypnout; v této situaci je nutné jak v procentním, tak v časovém režimu nastavit nulové hodnoty na místě odpovídajícím hodnotě doby provětrávání, např.: 0/120s  

### Plynulá ventilace  

Regulátor plynule reguluje ventilaci od „Minimálních otáček” do **„Maximálních otáček”** v rozsahu od **„Požadované teploty”** do součtu **„Požadované teploty”** a **„Pásma ventilace”**. Nad tímto rozsahem se zapíná 2 skupina ventilace.  

![ventilace](./img/wentylacjia.png)  

Nad tímto rozsahem se zapíná 2 skupina ventilace, Pokud teplota v místnosti klesne pod **„Požadovanou teplotu”**, regulátor periodicky provětrává místnost, při dalším poklesu se zapne přitápění. Vše závisí na nastaveních zadaných uživatelem. Program regulátoru zohledňuje také spolupráci s alarmovou ústřednou, která může být aktivována v situaci, kdy se teplota ve vepříně odchyluje od zadaných parametrů.  

## Programování regulátoru  

Regulátor obsahuje sadu výchozích nastavení, která se zapisují do energeticky nezávislé paměti ve dvou případech:  
1. První spuštění zařízení,  
2. Chyba v paměti dat.  
Při nepřítomnosti nebo výpadku napájení regulátor neztrácí dříve zadaná a uložená uživatelská nastavení.  

### Používání menu  

Regulátor je vybaven řadou funkcí, které umožňují jeho přizpůsobení dané aplikaci. Tyto funkce jsou seskupeny v menu, do kterého lze vstoupit stisknutím jedné z kláves **(„ Šipka vpravo”, „Šipka vlevo”)**. Parametry se mění pomocí kláves **„+” a „-”**, upravovaný parametr se automaticky uloží do energeticky nezávislé paměti po uplynutí **30s** od posledního stisknutí tlačítka.  

### Funkce základního menu  

| MENU                       | Popis | 
|:---:                       |:---|
|Teplota  <br />20,8°C W16% A  |**„Informační režim”** - běžného provozu. Na displeji se zobrazuje aktuální teplota a při spuštěném ventilátoru hodnota úrovně ventilace. Význam dalších symbolů: A-označuje aktivovaný alarm, D  - označuje zapnuté vytápění, W - označuje přídavnou ventilaci| 
|Požad. teplota  <br />20,0°C        |**„Požadovaná teplota”** – hodnota teploty určující začátek procesu plynulé ventilace.   | 
|Provětrávání  <br />20s / 200s  |**„Provětrávání”** – nastavují se dvě časové hodnoty 1 „Doba chodu”, 2 „Doba přestávky” mezi jednotlivými cyklickými zapnutími ventilace.| 
|Úroveň provětr.  <br />20%        |**„Úroveň provětrávání”** - úroveň ventilace během chodu provětrávání   | 
|Alarm minimum  <br />12,0°C       |**„Alarm minimum”** - určuje absolutní minimální teplotu, při které se aktivuje alarm. 
|Alarm maximum  <br />28,0°C       |**"Alarm maximum"** - určuje absolutní maximální teplotu, při které se aktivuje alarm.  | 
|Přitápění  <br />12,0°C         |V závislosti na konfiguraci se provádějí funkce: **„Přitápění”** - kontakt sepne, pokud teplota klesne pod uvedenou hodnotu. | 
|Ventilace 2 stupně  <br />25,0  |**„Ventilace 2 stupně”** - kontakt sepne, pokud měřená teplota překročí součet požadované teploty a pásma ventilace. | 
|Pásmo ventilace  <br />5,0°C     |**„Pásmo ventilace”** - určuje rychlost reakce regulátoru (změny úrovně ventilace od minima 1 do maxima 1) na rostoucí teplotu. | 
|Minimální otáčky  <br />1%        |**„Minimální otáčky”** – jedná se o stav, ve kterém zařízení setrvává po neurčitou dobu a přivádí na výstup napětí o zadané hodnotě. Slouží ke kalibraci zařízení s motorem a mechanismem klapek.   | 
|Maximální otáčky  <br />100%      |**„Maximální otáčky”** – jedná se o stav, ve kterém zařízení setrvává po neurčitou dobu a přivádí na výstup napětí o zadané hodnotě. Slouží k omezení výkonu určeného pro ventilaci| 

### Pokročilé menu  

Pokročilé menu je určeno především pro instalační techniky, umožňuje přizpůsobit regulátor instalaci a ventilátoru. Do pokročilých nastavení se přechází stisknutím a podržením dvou kláves menu po dobu přibližně 10s.  

| MENU                                 | Popis| 
|:---:                                 |:--- |
|Chybí nastavení  <br />pokročilá   |Toto hlášení znamená, že regulátor nebyl zkalibrován s ventilací a jeho činnost může být nesprávná Je nutné vstoupit do pokročilého menu a provést nastavení „Zakázaného pásma”.|
|Nastavení <br />Pokročilá         |Signalizace vstupu do pokročilých nastavení. | 
|Software Ver:  <br />1907       |Informace o verzi softwaru.| 
|Zakázané pásmo  <br />1000 us       |Kalibrace minimálních otáček ventilátorů připojených přímo k regulátoru, tento parametr odpovídá úrovni ventilace „1%”|  
|Funkce kontaktů  <br />Přitápění     |Volba funkce kontaktů:  <br />• Přitápění (výchozí)<br />• 2 skupina ventilace | 
|Provětrávání  <br />Časové         |Volba druhu provětrávání: <br />• Časové (výchozí) <br />• Procentní| 
|Rozsah V1  <br />od 2,0 do 10,0       |Nastavení rozsahu změn napětí na výstupu V1 0÷10V. Nastavení se týkají minimální a maximální hodnoty napětí. Nastavení se používá k přizpůsobení regulátoru modulu pro rozšíření výkonu nebo frekvenčnímu měniči.| 
|Inverze V1  <br />Ne                |Aktivace způsobí obrácení charakteristiky výstupu V1. Napětí bude klesat s růstem úrovně ventilace v rozsahu zadaném min.-max. Signál na výstupu V1 bude typu 10-0V.| 
|Odpojení V1  <br />Ne                |Aktivace způsobí, že na výstup  V1 0-10V bude přiváděna úroveň 0V namísto nastavené minimální hodnoty, pokud úroveň ventilace bude 0%.| 
|Rozsah V2  <br />od 2,0 do 10,0       |Nastavení rozsahu změn napětí na výstupu V2 0÷10V. Nastavení se týkají minimální a maximální hodnoty napětí. Nastavení se používá ke kalibraci systému klapek.|
|Inverze V2  <br />Ne      	       |Aktivace způsobí obrácení charakteristiky výstupu V2. Napětí bude klesat s růstem úrovně ventilace v rozsahu zadaném min.-max. Signál na výstupu V2 bude typu 10-0V.|
|Kalibrace tepl  <br />21,0°C -> 22,0°C|Kalibrace snímače teploty umožňuje přepočítat odečtenou hodnotu.|
|Pozvolný rozběh  <br />50%      	           |Určení úrovně ventilace při každém spuštění ventilátoru, ventilátor se rozběhne na uvedenou hodnotu a poté přejde na požadovanou úroveň.| 
|Jazyk  <br />Polština    	           |Volba jazyka menu: polština, angličtina, němčina, ruština|
|Ukončení                               |Opuštění pokročilého menu pomocí klávesy „+”, provedené změny se uloží do energeticky nezávislé paměti.|

### Chybová a výstražná hlášení  

Chybová hlášení slouží k informování uživatele o nesprávné činnosti regulátoru. Níže jsou uvedena možná chybová hlášení.  

|CHYBA                                    | POPIS |
|:---:                                   |:--- |
|Alarm  <br />Přetížení 	         |Alarm přetížení, aktivovaný při 75°C. Zařízení přeruší provoz do vychladnutí.|
|SNÍMAČ ROZPOJEN!  <br />Zkontrolujte snímač|Rozpojený snímač, signalizuje poškození snímače nebo připojovacího kabelu.|
|SNÍMAČ ZKRATOVÁN!  <br />Zkontrolujte snímač  |Zkratovaný snímač, signalizuje poškození snímače nebo připojovacího kabelu.|
|Výpadek  <br />Napájení                  |Výpadek napájení, příliš nízká hodnota napájecího napětí, nesprávná frekvence nebo silně zkreslené napájecí napětí.| 

## Poznámky a výstrahy  

:::danger 
Během instalace zařízení je bezpodmínečně nutné odpojit přívod elektrické energie, protože napětí na některých součástech je nebezpečné pro život a zdraví. Doporučuje se svěřit instalaci kvalifikované osobě.
:::

- Aby se předešlo problémům při provozu zařízení, je nutné se před zahájením instalace a používání seznámit s návodem.  
- Není dovoleno zasahovat do konstrukce ani provádět vlastní opravy. To se týká zejména změn prvků a součástí.  
- Údržbu a servis smí provádět oprávněný personál (instalační technik nebo firemní servis). Ve stájích s nucenou ventilací je vyžadován alarmový systém. Výrobce zařízení neodpovídá za škody způsobené nesprávnou instalací, nesprávným naprogramováním funkcí, následky náhodných událostí a vnějšími faktory.  
- Regulátor ventilace vyžaduje nastavení parametrů podle podmínek v chovném prostoru. Tato nastavení jsou individuální záležitostí závislou na rozhodnutí chovatele. Výrobce zařízení si vyhrazuje právo na změny konstrukce zařízení a softwaru.  


:::caution
![alternativní text](./img/trash.svg) Po ukončení používání výrobku jej nevyhazujte spolu s netříděným komunálním odpadem, ale zlikvidujte jej v souladu s platnými předpisy (směrnice WEEE Evropské unie 2012/19/EU). <br />Výrobek byl vyroben v souladu s požadavky RoHS (směrnicí Evropské unie 2011/65/EU).
:::

<!-- \newpage -->
## Technické údaje regulátoru  

|Parametr                        |	POPIS      |
|:-----------                    |:---------- |
|Napájecí napětí|	230VAC 50Hz|
|Maximální proud výstupu plynulé regulace FAN|	6A|
|Rozsah regulace výstupního napětí|	70V ÷ (Uz-5)V|
|Maximální proud výstupu (kontaktu) ALARM|	3A|
|Maximální proud výstupu (kontaktu) FUNCTION|	3A|
|Rozsah provozních teplot|	-20 +40oC|
|Rozsah měření teploty|	0 +50°C|
|Rozlišení měření teploty|	0,1°C|
|Detekce poškození snímače teploty|	ANO|
|Maximální počet analogových snímačů|	1|
|Přesnost měření teploty – analogový vstup|	1°C|
|Závislost měření na odporu vodičů – analogový vstup|	15,8Ω/°C|
|Odolnost vůči přepětí (max E)|	210J|
|Ochrana proti přetížení|	75°C|
|Rozměry zařízení|	20x15x8 [cm]|
|Stupeň krytí|	IP56|
  


:::info
Regulátor SPEED CONTROL SERVOMOTOR obsahuje v sadě:
- 1 snímač teploty + příslušenství,
- 4 rozpěrné hmoždinky,
- 1 pojistku 10A.
:::

