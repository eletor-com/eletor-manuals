---
sidebar_position: 3
title: Návod SC-12
description: Regulátor klimatu pro stájové prostory s přípustným výstupním proudem
  až 12A
keywords:
- eletor sc-12
- regulátor ventilace
- regulátor klimatu
- regulátor ventilace prasečího chléva
- regulátor mikroklimatu
- regulátor pro prasečí chlévy
- ventilace prasečího chléva
- regulátor pro odchovny
---

# Regulátor SC-12

Mikroprocesorový regulátor klimatu patřící do řady SPEED CONTROL. Všestrannost zařízení zajišťuje velký počet vstupů/výstupů systému a intuitivní software v polském a anglickém jazyce. Program regulátoru kromě základního nastavení teplot, provětrávání, přitápění, min./max. úrovní ventilace a alarmů umožňuje testování a uložení kalibrace akčních členů spolupracujících s regulátorem.

**Parametry a vlastnosti:** 
- Ventilace I. skupiny: 
  - max. proud výstupu plynulé regulace 12A,
  - tepelná ochrana systému, 
  - pozvolný rozběh ventilace – měkký rozběh,
  - přemosťovací relé při plném vybuzení, 
  - kalibrace minimálních otáček, 
  - program úspory energie se systémem klapek otevíraných s předstihem.
- Ventilace II skupiny, oddělený kontakt do 6A.
- Přitápění, oddělený kontakt do 6A
- Alarmové výstupy NO a NC: 
  - signalizace výpadku napájení,
  - signalizace překročení min. nebo max. prahové teploty,
  - vestavěný akustický signalizátor.
- Nezávislé 3 výstupy 0..10V:
  - spolupráce s rozšiřujícími moduly,
  - ovládání systému klapek, 
  - regulace vytápění s proměnným výkonem.**
- Dva analogové vstupy pro měření teploty.
- Digitální port pro měření teploty (až 4 snímačů).
- Dva funkční reléové výstupy (volitelné):
  - spolupráce s lineárními pohony, 
  - III a IV skupina ventilace
- Dva analogové vstupy 0-10V.
- Napájení potenciometru DC 10V.
- Pomocné napájení DC 12V.
- Možnost spolupráce s počítačem až 1200m.
- Hermetický kryt IP65.
- Napájecí napětí 230VAC 50Hz.
- Příkon systému < 10V

# Instalace regulátoru
:::danger 
 Při instalaci zařízení je bezpodmínečně nutné odpojit přívod elektrické energie, protože napětí na některých součástech je nebezpečné pro život a zdraví. Doporučuje se svěřit instalaci kvalifikované osobě.  Tento úkon je nebezpečný
:::

## Výběr místa montáže
Místo montáže je nutné zvolit uvážlivě s ohledem na snadný přístup pověřených osob k přístroji a nepřístupnost pro zvířata a děti. Je nutné zohlednit také klimatické podmínky, tzn. zařízení má pracovat v rozsahu teplot -10°C až 40 °C, na místě nevystaveném slunečnímu záření. Kolem zařízení musí být zajištěno volné proudění vzduchu. Součástí zařízení je snímač teploty.  

### Pro montáž snímače teploty platí několik zásad:
 - snímač se nesmí montovat na místě bez cirkulace vzduchu nebo na místě vystaveném přímému slunečnímu záření,
 - snímač se nesmí montovat na nosnou (vnější) stěnu budovy,
 - vyhněte se blízkosti zařízení vyzařujících teplo, například topných těles a svítidel,
 - snímač se nesmí umísťovat přímo u dveří a větracích otvorů,
 - snímač se nesmí umísťovat na místa přístupná zvířatům,
 - doporučuje se vést kabel připojující snímač v dostatečné vzdálenosti od napájecích kabelů.

# Montáž
Zařízení může pracovat v agresivních klimatických podmínkách. Správně namontovaný regulátor a snímač teploty jsou odolné vůči škodlivým vlivům prostředí.  

### Při montáži je třeba věnovat pozornost následujícím bodům:
 - před sešroubováním je nutné zkontrolovat těsnění víka,
 - víko musí být dotaženo všemi šrouby,
 - kabely použité k připojení regulátoru musí mít kruhový průřez,
 - po připojení kabelu je nutné dotáhnout kabelové vývodky tak, aby byl kabel utěsněn a zajištěn proti pohybu, doporučuje se použití silikonu,
 - nepoužité průchody (vývodky) je nutné zaslepit,
 - regulátor (spodní část krytu) se připevňuje na rovnou stěnu 4 hmoždinkami.

# Elektrické připojení
:::danger 
 Před připojením systému se ujistěte, že je napájení vypnuté!
Tento úkon je nebezpečný
:::

Před připojením regulátoru je nutné odšroubovat a sejmout víko. Kabely se protáhnou gumovými vývodkami a lze přistoupit k jejich připojení. Svorky regulátoru jsou znázorněny na následujícím obrázku.

![Připojení ](./img/sc-12.png)

**Konektor AC 230V** se připojuje k napájení (rozváděči). Je nutné použít nadproudový jistič 1P-B6 a svodiče přepětí typu T1 T2. Při připojování více zařízení je vhodné rozdělit regulátory na různé „fáze“ (L1, L2, L3), aby bylo napájecí vedení rovnoměrně zatíženo.

**Konektor FAN** je nutné připojit přímo k ventilátoru, při řízení několika ventilátorů nesmí celkové zatížení překročit 6A, každý ventilátor musí být samostatně jištěn. PE a N se nesmí vyvádět z napájení (rozváděče), je nezbytné je připojit k vývodům regulátoru.

**Konektor FAN 2** lze použít pro připojení ventilátorů 2 skupiny nebo skrápěcích systémů. Výstup je oddělený, maximální proud kontaktu je 6A (při přímém řízení zátěže je vyžadován externí nadproudový jistič typu 1P-B6), kontakt sepne, když je měřená teplota vyšší než součet požadované teploty a pásma ventilace.

**Konektor HOT** lze použít k připojení ohřívače. Výstup je oddělený, maximální proud kontaktu je 6A (při přímém řízení zátěže je vyžadován externí nadproudový jistič 1P-B6), kontakt sepne při poklesu měřené teploty pod nastavenou hodnotu.

**Konektor ALARM** má oddělené výstupy NC, C a NO určené k připojení k alarmové ústředně. Alarm se aktivuje v následujících případech:
    - teplota je příliš nízká nebo příliš vysoká,
    - došlo k poruše regulátoru nebo snímače teploty,
    - došlo k výpadku napájecího napětí regulátoru,
    - došlo k nesprávné činnosti regulátoru (např. přehřátí regulátoru)
Následující obrázek znázorňuje způsob připojení ventilátoru k alarmové ústředně.

![Alarmové připojení](./img/alarmsc-s.png)

**Konektor FUNC1 a FUNC2** slouží k připojení zdvihacího mechanismu pro otevírání přívodů vzduchu s motorem s chodem vpravo/vlevo. Relé FUNC1 zapíná proud pro pohon a FUNC2 přepíná směr otáčení motoru. Příklad schématu připojení zdvihacího mechanismu (je vyžadován externí nadproudový jistič 1P-B6):
Po deaktivaci funkce zdvihacího mechanismu pracují výstupy FUNC1 a FUNC2 jako kontakty 3 a 4 skupiny ventilace v uvedeném pořadí.

![Připojení zdvihacího mechanismu](./img/Sc-12fan.png)

**Konektor 12V** je určen k napájení externích snímačů.

**Konektor V1 0-10V** slouží k připojení modulů pro rozšíření výkonu. Napětí na této svorce je úměrné úrovni ventilace.

**Konektor V2 0-10V** slouží k připojení pohonu otevírajícího klapky přívodu vzduchu.

**Konektor V3 0-10V** slouží k připojení topného systému s plynule regulovaným výkonem. Napětí na tomto výstupu roste úměrně poklesu teploty počínaje teplotou přitápění.

**Konektor 10V** slouží k napájení potenciometru zdvihacího mechanismu nebo jiných systémů typu 0-10V.

**Konektor SENS1 (SENS2)** se připojuje k 1 snímači teploty TS3 nebo TS5, na polaritě nezáleží. Při současném připojení 2 snímačů se měřené teploty průměrují. Je vhodné vést měřicí kabely v dostatečné vzdálenosti od napájecích kabelů.

**Konektor 1-WIRE** lze použít k připojení většího počtu digitálních snímačů teploty, maximálně 4, zapojených paralelně (je nutné dodržet správnou polaritu). Maximální délka kabelu připojujícího snímače je 150m (délka nemá vliv na měření teploty), doporučuje se použití stíněného kabelu.

**Konektor RS-485** lze použít pro vytváření ventilačních systémů a komunikaci s počítačem PC.

**Konektor IN1 0-10** slouží k přivedení signálu zpětné vazby ze systému přívodů vzduchu – určuje aktuální polohu přívodů.

**Konektor IN2 0-10** slouží k připojení regulátoru k jiným snímačům, např. vlhkosti, CO2 nebo k provozu regulátoru jako rozšíření výkonu.

# Princip činnosti
Hlavním úkolem regulátoru je udržovat teplotu v chovném prostoru na úrovni stanovené chovatelem. Je třeba mít na paměti, že regulátor je pouze nástrojem, který má pomoci zajistit optimální klimatické podmínky v chovném prostoru. Rozhodující úlohu v tomto procesu však má chovatel, který musí přizpůsobovat nastavení zařízení měnícím se venkovním klimatickým podmínkám a především požadavkům zvířat ve stáji a sledovat provozní stav zařízení prostřednictvím alarmové ústředny.

## První uvedení regulátoru do provozu
:::danger 
 Při prvním uvedení regulátoru do provozu je bezpodmínečně nutné nastavit zakázané pásmo provozu motoru.

:::
Regulátor spolupracuje s ventilátory s jednofázovým asynchronním motorem s maximálním celkovým odběrem proudu 12A. Uživatel musí po připojení vybraných ventilátorů přizpůsobit jejich provoz spolupráci s regulátorem. Jinými slovy je nutné nastavit minimální provozní úroveň (otáčky) ventilátoru. Tato funkce se nazývá „Zakázané pásmo“ a uživatel ji jednorázově nastavuje v „Pokročilých nastaveních“. Pro správné provedení tohoto úkonu je vhodná pomoc druhé osoby, která může nepřetržitě sledovat chování ventilátoru, zatímco druhá osoba nastavuje hodnotu „Zakázaného pásma“ (tovární hodnota je 0). Nenastavení zakázaného pásma může vést k nesprávné činnosti zařízení. Hodnotu „Zakázaného pásma“ lze považovat za správnou v okamžiku, kdy tlak vytvářený ventilátorem začne mírně nadzvedávat klapky ventilačního komína. Nastavení „Zakázaného pásma“ je nutné zopakovat při výměně ventilátoru připojeného k regulátoru.

## Periodické provětrávání
Provětrávání je funkce prováděná regulátorem, která se spouští v okamžiku, kdy teplota v prostoru klesne pod požadovanou teplotu. Tato funkce zajišťuje zvířatům cyklický přívod čerstvého vzduchu. V menu Provětrávání jsou k dispozici 3 parametry:
- **„Doba provozu“** - určuje, na kolik minut se má ventilátor zapnout;
- **„Doba přestávky“** - určuje dobu zastavení ventilátoru;
- **„Úroveň provětrávání“** - určuje výkon ventilace během „Doby provozu“.

Všechny výše uvedené parametry nastavuje uživatel. 

### Při nastavování parametrů provětrávání je třeba pamatovat na několik zásad:
- provětrávání se zapíná výhradně tehdy, když teplota v prasečím chlévě klesne pod požadovanou teplotu,
- základní funkcí provětrávání je zajistit zvířatům cyklický přívod čerstvého vzduchu, nikoli udržovat požadovanou teplotu v prostoru,
- doporučuje se provětrávat prostory krátce, ale často,
- je nutné vyvarovat se dlouhých intervalů provětrávání, protože mohou vést k příliš velkým výkyvům teploty,
- nastavované parametry je bezpodmínečně nutné přizpůsobovat chování zvířat a podmínkám uvnitř i vně prostoru.

## Způsob činnosti zařízení
Regulátor plynule reguluje ventilaci od **„Min.1“ do „Max.1“** v rozsahu od **„Požadované teploty“** do součtu **„Požadované teploty“** a **„Pásma ventilace 1sk.“**. Nad tímto rozsahem se zapne 2 skupina ventilace a 1 skupina změní úroveň na **„Min.2“**, při dalším růstu teploty bude ventilace růst až na **„Max.2“**, na konci rozsahu **„Pásma ventilace 2 sk.“**. Pokud je **„Pásmo ventilace 2 sk.“** nastaveno na nulu a ventilace pracuje na **„Max.1“**, zapne se 2 skupina ventilace a další růst teploty již nezpůsobí žádné změny ventilace (tečkovaná část grafu). Pokud teplota v prostoru klesne pod **„Požadovanou teplotu“**, regulátor prostor periodicky provětrává, při dalším poklesu se zapne přitápění. Vše závisí na nastavení provedeném uživatelem. Program regulátoru rovněž zahrnuje spolupráci s alarmovou ústřednou, která může být aktivována, pokud se teplota v prasečím chlévě odchyluje od nastavených parametrů. 

![Ventilace](./img/Sc-12wentyl.png)  

## Programování regulátoru
Regulátor obsahuje soubor výchozích nastavení, která se zapisují do energeticky nezávislé paměti ve dvou případech:
1. První uvedení zařízení do provozu,
2. Chyba v datové paměti.
Při absenci nebo výpadku napájení regulátor neztrácí dříve zadaná a uložená uživatelská nastavení.

## Přední panel – indikátory, tlačítka a displej
![Panel](./img/SC-12panel.png)  
    1. Červená kontrolka signalizující překročení maximální přípustné teploty.
    2. Červená kontrolka signalizující překročení minimální přípustné teploty.
    3. Žlutá kontrolka signalizující přitápění.
    4. Žlutá kontrolka signalizující ventilaci 2 skupiny.
    5. Zelená kontrolka signalizující ruční zadávání úrovně ventilace.
    6. Zelená kontrolka signalizující činnost komunikace RS485.
    7. Displej menu, v běžném provozním stavu zobrazuje teplotu.
    8. Sloupcový indikátor signalizující úroveň ventilace.
    9. Tlačítko pro pohyb nahoru v menu nebo změnu hodnoty parametru.
    10. Tlačítko ESC - opuštění menu nebo daného parametru bez uložení hodnoty.
    11. Tlačítko OK - vstup do menu nebo potvrzení (uložení) daného parametru.
    12. Tlačítko pro pohyb dolů v menu nebo změnu hodnoty parametru.

## Používání menu
Regulátor je vybaven řadou funkcí, které umožňují jeho přizpůsobení dané aplikaci. Tyto funkce jsou seskupeny v menu, do kterého se vstupuje stisknutím jednoho z tlačítek **(„+“, „-“ nebo „OK“)**. Tlačítka **„+“** a **„-“** slouží k výběru funkce, úpravu, uložení dat nebo přechod na další úroveň lze provést tlačítkem **„OK“**. Pro návrat do nadřazeného menu nebo zrušení uložení daného parametru stiskněte tlačítko **„Esc“**.

## Funkce základního menu

| MENU                          | Popis       | 
|:-----------                   |:---------- |
| Teplota 20,8o C W16% A    | **Informační režim** - běžného provozu. Displej zobrazuje aktuální teplotu a při zapnutém ventilátoru také hodnotu úrovně ventilace. Význam doplňkových symbolů:A-označuje aktivovaný alarm,D  - označuje zapnuté vytápění, W - označuje doplňkovou ventilaci| 
|   Požad. teplota   20,0o C      |**„Požadovaná teplota“** – Určuje teplotu, od které začíná proces plynulé ventilace. Je nutné zvolit vhodnou hodnotu podle druhu hospodářských zvířat.| 
| Provětrávání     | **Provětrávání** – nastavují se dvě časové hodnoty.    1.**Doba provozu** Určuje počet minut provozu ventilace.    2.**Doba přestávky** Určuje počet minut přestávky ventilace mezi jednotlivými provozními cykly.    3.**Úroveň provětrávání** - Určuje intenzitu ventilace během provětrávání.| 
| Alarm |  1.**Alarm aktivní Ano** - Aktivace/Deaktivace alarmového kontaktu, aby regulátor nevydával alarmový signál na výstupu (do alarmové ústředny), zvolte v menu „NE“.  2. **Tepl. Min. 15,0o C** - Určuje absolutní minimální teplotu, při které se aktivuje alarm.  3.**Tepl. Max. 25,0o C** - Určuje absolutní maximální teplotu, při které se aktivuje alarm.  4.**Signál alarmu Ano** - Aktivace/Deaktivace akustického signálu uvnitř regulátoru. | 
|    Ventilace        |  1.**Pásmo vent. 1 5,0o C**   - Určuje rychlost reakce regulátoru (změny úrovně ventilace od minima 1 do maxima 1) na rostoucí teplotu.  2.**Úroveň min. 1 1 %** - Určuje úroveň ventilace odpovídající požadované teplotě.  3.**Úroveň max. 1 100 %**-Určuje stálou úroveň ventilace pro teplotu překračující rozsah plynulé regulace, pokud „Pásmo vent. 2sk.“ = 0, jinak maximální úroveň regulované ventilace pro teplotu rovnou součtu požadované teploty a pásma 1 skupiny.  4.**Pásmo vent. 2 0,0o C**-Určuje rychlost reakce regulátoru (změny úrovně ventilace od minima 2 do maxima 2) na rostoucí teplotu pro 2 skupinu. Funkce je neaktivní, pokud je pásmo rovno nule.  5.**Úroveň min. 2 1 %**-Určuje minimální úroveň ventilace 1 skupiny v bodě sepnutí kontaktů 2 skupiny.  6.**Úroveň max. 2 100 %**-Určuje stálou úroveň ventilace pro teplotu překračující rozsah plynulé regulace, když je 2 skupina zapnutá.  7.**Skupina 3  5,0o C**-Určuje stálou úroveň ventilace pro teplotu překračující rozsah plynulé regulace, když je 2 skupina zapnutá.  8.**Skupina 4 7,0o C**-Určuje teplotu vzhledem k požadované teplotě, při které se zapíná 4 skupina ventilace (funkce zdvihacího mechanismu musí být deaktivována).| 
|    Přitápění  |  1.**Tepl. přitáp. 15,0o C**-Určuje teplotu zapnutí přitápění.  2.**Pásmo přitáp. 5,0o C** -Určuje poměr výkonu přitápěcích systémů (na výstupu V3 0-10V) v závislosti na teplotě. | 

## Funkce pokročilého menu
Pokročilé menu je určeno především pro instalační techniky, umožňuje přizpůsobit regulátor instalaci a ventilátoru, testovat obvody a zvolit jazyk menu. Do pokročilých nastavení se vstupuje stisknutím a podržením dvou tlačítek menu po dobu přibližně 10s. 

| MENU                          | Popis       | 
|:-----------                   |:---------- |
|Testování  |Tato funkce slouží ke kontrole jednotlivých výstupních obvodů regulátoru, všechna nastavení jsou dočasná a platí pouze po dobu setrvání v dané položce menu, po stisknutí „ESC“ nebo „OK“ se daný výstup vrátí do stavu vyplývajícího z činnosti regulátoru.  1.**Ventilace 0 %**  Umožňuje ručně zadat úroveň ventilace za účelem kontroly ventilačního systému. Po potvrzení funkce se rozsvítí zelená kontrolka (ručička).  2.**Alarm Ne** Aktivace způsobí rozsvícení 2 červených kontrolek, zapnutí zvukového signálu a alarmového obvodu.  3.**Přitápění Ne** Aktivace způsobí rozsvícení žluté kontrolky (plamínku) a zapnutí obvodu přitápění.  4.**Vent. 2 stupně Ne** Aktivace způsobí rozsvícení žluté kontrolky (ventilátoru) a zapnutí obvodu 2 skupiny.  5.**Výstup V1 0,0 V  Výstup V2  0,0 V Výstup V3  0,0 V**-Test výstupů 0-10V, tlačítky „+“ nebo „-“ lze zadat zvolené napětí pro systém v uvedeném pořadí: rozšiřujících modulů, přívodních klapek, plynulého přitápění. Funkce je zvláště užitečná při kalibraci Výstupu V2 přívodních klapek.  6.**Zdvihací mechanismus 0** Umožňuje kontrolu systému přívodních klapek, „+“ - otevírá přívody, „-“ - zavírá přívody, na displeji se zobrazuje aktuální poloha pohonu odečtená z potenciometru.  7.**Skupina 3 Ne**  Aktivace způsobí zapnutí obvodu 3 skupiny ventilace. (funkce zdvihacího mechanismu musí být deaktivována)  8.**Skupina 4 Ne**  Aktivace způsobí zapnutí obvodu 4 skupiny ventilace. (funkce zdvihacího mechanismu musí být deaktivována)|
|Jazyk        | Výběr jazyka menu. Lze zvolit polštinu nebo angličtinu. | 
|Ventilátor         |  1.**Zakázané pásmo 0**- Kalibrace minimálních otáček ventilátorů připojených přímo k regulátoru, tento parametr odpovídá úrovni ventilace „1%“. Kladná hodnota parametru otáčky zvyšuje, záporná je snižuje.  2.**Rozš. modul Min. 1,9 V** -Minimální napětí přiváděné na modul pro rozšíření výkonu (výstup V1 0-10V).  3.**Rozš. modul Max. 10,0 V** -Maximální napětí přiváděné na modul pro rozšíření výkonu (výstup V1 0-10V).  4.**Odpojení modulu Ne** - Odpojení modulu pro rozšíření výkonu, pokud je zvoleno „ANO“, napětí na výstupu řídícím rozšiřující moduly (V1 0-10V) klesne na úroveň 0V, nikoli na nastavenou minimální hodnotu, když úroveň ventilace dosáhne 0%.  5.**Inverze  Ne**-Aktivace způsobí obrácení charakteristiky výstupu V1. Napětí bude klesat s růstem úrovně ventilace v rozsahu stanoveném hodnotami min.-max. Signál na výstupu V1 bude typu 10-0V.| 
| Přívodní klapky       |  1.**Předstih 0,0o C**-Dřívější otevření přívodních klapek. Zadávaný parametr určuje, o jakou teplotu dříve oproti „Požadované teplotě“ se mají přívodní klapky otevřít.  2.**Dovření  Ne**- Aktivace způsobí, že napětí na výstupu řídícím přívodní klapky (V2 0-10V) klesne na úroveň 0V, nikoli na nastavenou minimální hodnotu. Při nečinnosti ventilace (úroveň ventilace 0%).  3.**Klapky min.  1,9 V**- Minimální napětí přiváděné na přívodní klapky (výstup V2 0-10V).  4.**Klapky max.  10,0 V**- Maximální napětí přiváděné na přívodní klapky (výstup V2 0-10V).  5.**Inverze   Ne**-Aktivace způsobí obrácení charakteristiky výstupu V2. Napětí bude klesat s růstem úrovně ventilace v rozsahu stanoveném hodnotami min.-max. Signál na výstupu V2 bude typu 10-0V. |  
| Měření teploty  |  1.**Kalibrace S1 23,0o C -> 23,5o C**,**Kalibrace S2 23,0o C -> 23,2o C** - Kalibrace analogových vstupů umožňuje změnit měřítko teploty odečtené ze snímačů S1 a S2.  2.**Doba průměrování 60 s**- Tento parametr stanovuje časový interval, během kterého se průměrují aktuální odečty teploty. Hodnota průměrné teploty je základním parametrem funkcí regulátoru. Změny stavu výstupů (ventilace, přitápění, klapek, dalších skupin ventilace, alarmů,...) jsou úzce spjaty s tímto parametrem a nemohou nastávat častěji, než určuje zde stanovená doba. | 
| Zdvihací mechanismus      |  1.**Kalibrace otevř. 1024 -> 853**,**Kalibrace zavř. 0 -> 324** -Kalibrace zdvihacího mechanismu je nezbytná pro správnou činnost systému přívodů vzduchu. Tlačítko „+“ otevírá přívody, tlačítko „-“ zavírá přívody. Při otevírání přívodů musí parametr polohy růst, při zavírání klesat, v opačném případě je nutné ověřit připojení pohonu (napájení a potenciometr). Při kalibraci otevření otevřete přívody na maximum a potvrďte polohu tlačítkem „OK“. Při kalibraci zavření zavřete přívody a potvrďte polohu tlačítkem „OK“. Tlačítko „ESC“ opustí funkci bez uložení. Rozdíl mezi polohou otevření a zavření musí činit min. 100 jednotek.  2.**Deaktivace Ne**-Deaktivace uvolní kontakty FUNC1 a FUNC2 z ovládání zdvihacího mechanismu, tyto kontakty pak plní funkci ventilace skupiny 3 a 4.| 
| Měkký rozběh               | Parametry v této skupině menu určují rozběh ventilace. Zapnutí ventilace ve skupině s plynulou regulací předchází postupný rozběh na 100%, krátký provoz na 100%  a pokles na požadovanou úroveň ventilace. Při spuštění ventilace tak vzniká profouknutí usnadňující otevření motýlkových klapek v komínech.   Hodnoty jsou vyjádřeny v periodách napájecího napětí při 1% ventilace.  1.**Doba rozběhu 5**- Parametr určuje rychlost nárůstu otáček ventilace z nulové na maximální úroveň – pozvolné zapnutí ventilátorů. Hodnota 0 vypíná pozvolný rozběh.  2.**Doba 100%   100**- Parametr určuje dobu provozu při spuštění na 100% úrovně ventilace. Nastavení doby rozběhu a 100% na 0 zcela vypíná profouknutí při spuštění ventilace.  3.**Doba doběhu 5**-  Parametr určuje rychlost změn úrovně ventilace. | 
|Přitápění              |  1.**Inverze kontaktu Ne**-Aktivace způsobí obrácení charakteristiky výstupu HOT. Kontakt se bude  rozepínat při poklesu měřené teploty.  2.**Hystereze  0,5o C** - Určuje úroveň teplotní hystereze pro kontakt přitápění.  3.**Relativní provoz Ne**-Aktivace způsobí relativní zadávání teploty přitápění vzhledem k požadované teplotě. Změní se základní menu přitápění, ve kterém se pak zadává rozdíl oproti požadované teplotě.  4.**Přitápění min. 1,9 V** - Minimální napětí přiváděné pro plynulé řízení vytápění – ohřívač s proměnným výkonem ventilátoru (výstup V3 0-10V).  5.**Přitápění max. 10,0 V** - Maximální napětí přiváděné pro plynulé řízení vytápění – ohřívač s proměnným výkonem ventilátoru (výstup V3 0-10V).| 
| Program 	|  **ver. 2.4  dub 13 2018** - 	Zobrazení verze softwaru a data kompilace|

## Chybová a výstražná hlášení

Chybová hlášení slouží k informování uživatele o nesprávné činnosti regulátoru. Níže jsou uvedena možná chybová hlášení

|CHYBA                            |	POPIS      |
|:-----------                    |:---------- |
|Alarm     Přetížení 	     |Alarm přetížení, aktivovaný při 75°C. Zařízení přeruší provoz až do vychladnutí.|
|Alarm  Chybí snímač|Signalizuje absenci nebo poruchu snímače či připojovacího kabelu.|

# Poznámky a upozornění 
:::danger 
 Při instalaci zařízení je bezpodmínečně nutné odpojit přívod elektrické energie, protože napětí na některých součástech je nebezpečné pro život a zdraví. Doporučuje se svěřit instalaci kvalifikované osobě.

:::
- Aby se předešlo problémům při provozu zařízení, je nutné se před zahájením instalace a používání seznámit s návodem.
- Není dovoleno zasahovat do konstrukce ani provádět vlastní opravy. To se týká zejména provádění změn prvků a součástí. 
- Údržbu a servis musí provádět oprávněný personál (instalační technik nebo firemní servis). Ve stájových budovách s nucenou ventilací je vyžadován alarmový systém. Výrobce zařízení neodpovídá za škody způsobené nesprávnou instalací, nesprávným naprogramováním funkcí, následky nahodilých událostí a vnějšími vlivy. 
- Regulátor ventilace vyžaduje nastavení parametrů podle podmínek v chovném prostoru. Tato nastavení jsou individuální záležitostí závislou na rozhodnutí chovatele. Výrobce zařízení si vyhrazuje právo na změny konstrukce zařízení a softwaru.

:::caution
<div class="warning-container">
  <p>
    <strong></strong> Po skončení používání výrobku se výrobek nesmí vyhazovat spolu s netříděným komunálním odpadem, ale musí být zlikvidován v souladu s platnými předpisy (směrnice WEEE Evropské unie 2012/19/EU).
Výrobek byl vyroben v souladu s požadavky RoHS (směrnice Evropské unie 2011/65/EU).
  </p>
</div>
:::
:::tip

## Technické údaje regulátoru
|Parametr                        |	POPIS      |
|:-----------                    |:---------- |
|Napájecí napětí|	230VAC 50Hz|
|Maximální proud výstupu plynulé regulace FAN|	12A|
|Rozsah regulace výstupního napětí|	70V ÷ 230V|
|Maximální proud výstupu (kontaktu) FAN 2|	6A|
|Maximální proud výstupu (kontaktu) HOT|	6A|
|Maximální proud výstupu (kontaktu) ALARM|	4A|
|Maximální proud výstupu (kontaktu) FUNC1 a FUNC2|	4A|
|Rozsah provozní teploty|	-10 +40oC|
|Rozsah měření teploty|	0 +50oC|
|Rozlišení měření teploty|	0,1oC|
|Detekce poruch snímače teploty|	ANO|
|Maximální počet analogových snímačů|	2|
|Přesnost měření teploty – analogový vstup|	1oC|
|Závislost měření na odporu kabelů – analogový vstup|	15,8Ω/oC|
|Maximální počet digitálních snímačů|	4|
|Přesnost měření teploty – digitální vstup|	0,5oC|
|Závislost měření na odporu kabelů – digitální vstup|	Žádná|
|Maximální délka vedení připojujícího digitální snímače|	150m|
|Odolnost vůči přepětí (max E)|	210J|
|Ochrana proti přetížení|	75oC|
|Rozměry zařízení|	34x29x12 [cm]|
|Stupeň krytí|	IP56|
:::

:::info
Regulátor SPEED CONTROL-12 v2  obsahuje v sadě:
 - 1 snímač teploty,
 - 4 hmoždinky,
 - 2 kabelové vývodky PG13,5.
 - 3 kabelové vývodky PG11,
 - 4 kabelové vývodky PG9.
:::















































































