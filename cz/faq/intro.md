---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Nejčastější dotazy týkající se výběru, konfigurace, diagnostiky a servisu
  zařízení ELETOR.
keywords:
- ELETOR
- FAQ
- řídicí jednotky větrání
- regulátory
- ventilátory
- servopohony
- alarmy
- frekvenční měniče
- servis
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Nejčastější dotazy

FAQ vzniklo na základě anonymizované analýzy skutečných rozhovorů s uživateli a zákazníky ELETOR. Odpovědi byly zobecněny tak, aby pomáhaly v běžných případech a neobsahovaly údaje o konkrétních osobách ani instalacích.

:::note Rozsah FAQ

Odpovědi se týkají běžných případů. Označení svorek, funkce a způsob zapojení se mohou mezi modely a verzemi zařízení lišit. V případě pochybností používejte dokumentaci příslušného konkrétního produktu.

:::

:::warning B bezpečnost

Práce na elektrické instalaci provádějte v souladu s dokumentací zařízení a platnými bezpečnostními pravidly. Práce se síťovým napětím by měla provádět osoba s odpovídající kvalifikací.

:::

## Výběr řídicí jednotky a výkonu

### Jak vybrat řídicí jednotku pro ventilátory?

Základem výběru je především celkový proud ventilátorů, nikoli pouze jejich počet.

:::tip Připravte si údaje před výběrem

Čím přesnější jsou údaje o motorech a způsobu provozu instalace, tím spolehlivější je výběr řídicí jednotky.

:::

Před výběrem je vhodné připravit:

- počet ventilátorů,
- napájecí napětí,
- výkon nebo jmenovitý proud každého ventilátoru,
- informaci, zda mají být všechny ventilátory plynule regulovány,
- informaci, zda lze ventilátory rozdělit do skupin,
- informace o dalších zařízeních, např. ohřívačích nebo přívodních otvorech vzduchu.

Řídicí jednotku není vhodné vybírat přesně „na hranici“. Je nutné zachovat odpovídající rezervu vzhledem k maximálnímu zatížení.

### Stačí sečíst výkon ventilátorů ve wattech?

Pro předběžný odhad lze použít výkon, ale konečný výběr by měl vycházet ze jmenovitého proudu zařízení a charakteru zátěže.

Motor může během rozběhu odebírat více proudu než za běžného provozu. Z tohoto důvodu nemusí dvě sestavy ventilátorů s podobným jmenovitým výkonem vždy představovat rovnocennou zátěž pro řídicí jednotku.

### Mám několik malých ventilátorů. Mohu je připojit paralelně k jednomu výstupu?

Ano, pokud:

- jsou určeny pro tento způsob řízení,
- mají pracovat společně,
- součet zatížení nepřekračuje přípustný proud výstupu,
- způsob zapojení odpovídá dokumentaci řídicí jednotky.

Při větším počtu ventilátorů je vhodné zvážit rozdělení do skupin nebo použití výkonového rozšíření.

### Kdy je potřeba výkonové rozšíření?

Výkonové rozšíření se používá tehdy, když zátěž překračuje možnosti výstupu řídicí jednotky nebo když má být instalace rozšířena o větší počet ventilátorů.

Řídicí jednotka pak předává řídicí signál, zatímco vlastní zátěž je obsluhována přídavným modulem.

### Lze instalaci později rozšířit o další ventilátory?

U mnoha instalací ano. Nejčastěji se používá:

- další výkonové rozšíření,
- další skupina větrání,
- stykač spínající další skupinu,
- frekvenční měnič v případě třífázových motorů.

Plánované rozšíření je nejlepší zohlednit již při prvním výběru řídicí jednotky.

### Musí být všechny ventilátory plynule regulovány?

Ne. Běžná jsou dvě řešení:

1. všechny ventilátory jsou plynule regulovány,
2. první skupina je plynule regulována a další skupiny se připojují postupně, např. pomocí stykačů.

Druhé řešení umožňuje obsluhovat větší instalaci bez plynulé regulace každého ventilátoru.

### Mám 10 ventilátorů. Potřebuji velmi velkou řídicí jednotku?

Ne vždy. Lze použít několik způsobů řízení:

- rozdělení do skupin,
- výkonová rozšíření,
- stykače,
- frekvenční měnič.

Konečný výběr závisí na elektrických parametrech ventilátorů a na tom, zda mají všechny měnit otáčky současně.

### Liší se řídicí jednotky 6 A a 12 A pouze přípustným zatížením?

Nelze předpokládat, že jediným rozdílem je hodnota proudu. Jednotlivé verze a generace zařízení se mohou lišit vybavením nebo provedením.

Při výměně zařízení je nutné ověřit přesný model a aktuální dokumentaci.


## Ventilátory a řízení větrání

### Reguluje řídicí jednotka ventilátory plynule?

U řídicích jednotek určených k plynulé regulaci větrání se rychlost ventilátorů mění v závislosti na požadavcích vyplývajících mimo jiné z teploty.

Je však nutné ověřit, zda je daný typ motoru vhodný pro použitý způsob regulace.

### Co znamená požadovaná teplota?

Požadovaná teplota je hodnota, se kterou řídicí jednotka porovnává aktuálně naměřenou teplotu.

Na jejím základě řídicí jednotka zvyšuje nebo snižuje intenzitu větrání podle ostatních nastavení, např. regulačního pásma, minimální a maximální úrovně.

### Co znamená minimální úroveň větrání?

Jedná se o minimální hodnotu řízení ventilátoru během automatického provozu.

Toto nastavení zabraňuje provozu pod úrovní, při které by ventilátor mohl pracovat nestabilně nebo zajišťovat příliš malou výměnu vzduchu.

### Co znamená maximální úroveň větrání?

Jedná se o horní omezení hodnoty řízení větrání.

Například nastavení hodnoty pod 100% může omezit maximální otáčky ventilátoru, pokud to instalace vyžaduje.

### Co znamená pásmo větrání?

Pásmo větrání určuje rozsah teplot, ve kterém řídicí jednotka přechází z minimální na maximální úroveň větrání.

Čím užší je pásmo, tím rychleji řízení reaguje zvýšením výkonu na změnu teploty.

### Ventilátor po spuštění nejprve dosáhne 100% a teprve poté zpomalí. Proč?

Může být aktivní funkce rozběhu, jejímž úkolem je krátkodobé spuštění motoru s vyšším výkonem.

V závislosti na verzi řídicí jednotky je nutné zkontrolovat nastavení související s:

- funkcí Soft Start,
- dobou rozběhu,
- dobou provozu při 100%,
- dobou doběhu.

Pokud funkce není v dané instalaci potřebná, lze příslušné parametry změnit podle návodu zařízení.

### Proč může být ventilátor při spuštění krátkodobě uveden do chodu s plným výkonem?

Takový rozběh může pomoci zajistit spolehlivé spuštění ventilátoru i v instalacích, ve kterých mohou mechanické prvky při spuštění klást větší odpor.

Není to však potřebné v každé instalaci.

### Co znamenají doba rozběhu a doba doběhu?

**Doba rozběhu** určuje způsob nárůstu řídicí hodnoty během spouštění ventilátoru.

**Doba doběhu** určuje způsob snižování rychlosti.

Oba parametry umožňují omezit prudké změny otáček a provozu instalace.

### Proč mohou dvě stejné řídicí jednotky spouštět ventilátory odlišně?

Nejčastější příčinou jsou odlišná nastavení.

Je vhodné porovnat především:

- požadovanou teplotu,
- pásmo větrání,
- minimum a maximum,
- nastavení Soft Start,
- doby rozběhu a doběhu,
- konfiguraci skupin větrání.

### Může řídicí jednotka pravidelně spouštět větrání nezávisle na teplotě?

V závislosti na modelu je dostupná funkce periodického provětrávání.

Může spouštět větrání na stanovenou dobu v nastavených intervalech, i když teplotní regulace nevyžaduje zvýšení větrání.

### K čemu slouží skupiny větrání?

Skupiny umožňují postupné zvyšování výkonu instalace.

Například:

- skupina 1 je plynule regulována,
- skupina 2 spouští další ventilátory,
- další skupina se spouští při ještě vyšších požadavcích.

To umožňuje řídit velký počet ventilátorů bez plynulé regulace každého z nich.

### Lze další skupinu ventilátorů spínat pomocí stykače?

Ano. Reléový výstup řídicí jednotky může ovládat cívku vhodně zvoleného stykače.

Zátěž ventilátorů by pak neměla být vedena přímo přes malý řídicí kontakt.

### Co znamená symbol ventilátoru nebo žlutá kontrolka na řídicí jednotce?

V závislosti na modelu kontrolky informují o aktuálním stavu výstupů a funkcí.

Žlutá signalizace může znamenat aktivní provozní funkci, např. chod větrání, vytápění nebo další skupiny.

Přesný význam je nutné ověřit v návodu daného modelu.

### Co znamená symbol ručního režimu?

Ruční režim znamená, že hodnotu řízení vynutil uživatel a v daném okamžiku se nevypočítává automaticky na základě teploty.

Po ukončení zkoušek je nutné se ujistit, že řídicí jednotka byla vrácena do správného automatického režimu.


## Přívodní otvory vzduchu a servopohony

### Může řídicí jednotka ovládat přívodní otvory vzduchu?

Ano, vybrané řídicí jednotky umožňují spolupráci s pohony přívodních otvorů vzduchu.

Způsob zapojení závisí na typu servopohonu a způsobu jeho řízení.

### Jaké typy servopohonů lze použít pro přívodní otvory?

V technických rozhovorech se nejčastěji objevovala dvě řešení:

- servopohon řízený analogovým signálem 0–10 V nebo 2–10 V,
- reverzní servopohon otevřít/zavřít se signálem zpětné vazby, např. z potenciometru.

Před nákupem je nutné ověřit kompatibilitu konkrétního modelu s používanou řídicí jednotkou.

### Má napájecí napětí servopohonu 24 V nebo 230 V význam pro signál 0–10 V?

Řídicí signál a napájení servopohonu jsou samostatné parametry.

Servopohon může být napájen jiným napětím, než je napětí řídicího signálu. Oba parametry musí odpovídat dokumentaci servopohonu a řídicí jednotky.

### Co znamená řízení 0–10 V?

Řídicí jednotka vysílá napěťový analogový signál představující požadovanou polohu nebo úroveň řízení.

Při běžném použití znamená nižší hodnota menší otevření a vyšší hodnota větší otevření, skutečnou charakteristiku je však nutné ověřit v dokumentaci servopohonu.

### Čím se liší 0–10 V od 2–10 V?

V obou případech se poloha zadává analogovým signálem.

Ve standardu 2–10 V je dolní část rozsahu posunuta a může zařízení umožňovat rozlišit řídicí signál od jeho nepřítomnosti.

Řídicí jednotka a servopohon musí podporovat shodný rozsah.

### Jak vybrat servopohon podle počtu přívodních otvorů?

Servopohon není vhodné vybírat pouze na základě počtu klapek.

Je nutné zohlednit:

- požadovanou sílu nebo moment,
- délku a způsob vedení mechanismu,
- odpory klapek,
- délku zdvihu,
- rychlost činnosti,
- napájecí napětí,
- typ řízení,
- požadovanou zpětnou vazbu.

### Může jeden servopohon ovládat více klapek?

Ano, pokud mechanické uspořádání instalace umožňuje spojit klapky společným mechanismem a požadovaný moment nebo síla nepřekračuje možnosti servopohonu.

V praxi o výběru rozhodují odpory celého mechanismu, nikoli samotný počet klapek.

### Lze několik servopohonů zapojit paralelně a řídit jedním signálem?

V některých systémech je to možné, je však nutné ověřit dokumentaci servopohonů a přípustné zatížení řídicího výstupu.

U reverzních pohonů bez nezávislé zpětné vazby může rovněž docházet k postupnému rozcházení poloh jednotlivých servopohonů.

### Proč se může několik servopohonů časem nastavovat do různých poloh?

I stejné motory mohou pracovat s mírně odlišnou rychlostí kvůli:

- rozdílnému zatížení,
- mechanickým odporům,
- tolerancím parametrů motoru,
- rozdílům v převodovkách.

Proto je při požadavku na přesnou synchronizaci nutná vhodná zpětná vazba nebo individuální kontrola polohy.

### Lze přívodní otvory řídit proporcionálně k větrání?

Ano. V odpovídajícím způsobem nakonfigurovaných systémech může být poloha přívodních otvorů provázána s aktuální úrovní větrání.

Díky tomu se se zvyšováním výkonu ventilátorů zvětšuje také otevření přívodních otvorů.

### Vyžaduje servopohon 24 V samostatný napájecí zdroj?

Pokud řídicí jednotka nemá vhodný napájecí výstup s požadovaným výkonem, je zapotřebí samostatný napájecí zdroj.

Jeho výkon je nutné zvolit podle proudového odběru servopohonu a dalších zařízení napájených ze stejného zdroje.

### Lze použít servopohon jiného výrobce?

Často ano, pokud jeho elektrické parametry a způsob řízení odpovídají výstupům řídicí jednotky.

Před připojením je nutné ověřit:

- napětí,
- typ signálu,
- schéma vodičů,
- směry pohybu,
- signál polohy,
- přípustné zatížení.


## Snímače teploty a vlhkosti

### Kam připojit snímač teploty?

Snímač je nutné připojit ke vstupu pro snímač určenému výrobcem, ke vstupu pro snímač uvedenému v dokumentaci daného modelu.

Nelze předpokládat, že označení svorek je stejné u všech verzí zařízení.

### Snímač teploty ukazuje jinou hodnotu než referenční teploměr. Co dělat?

Pokud řídicí jednotka disponuje funkcí kalibrace snímače, lze údaj upravit po porovnání se spolehlivým referenčním teploměrem.

Před změnou kalibrace je vhodné se ujistit, že:

- oba snímače jsou na stejném místě,
- měření se ustálilo,
- snímač není zahříván sluncem nebo zařízeními,
- nenachází se přímo v proudu studeného nebo horkého vzduchu.

### Snímač vlhkosti ukazuje nesprávnou hodnotu. Lze jej kalibrovat?

Závisí to na verzi řídicí jednotky, snímače a softwaru.

U některých řešení může korekce vyžadovat odpovídající softwarovou funkci nebo kompatibilní typ snímače. Pokud je rozdíl velký a opakovaný, je nutné ověřit verzi zařízení a kontaktovat technickou podporu.

### Znamená chybné měření vždy poškozený snímač?

Ne.

Příčinou může být také:

- nesprávné umístění snímače,
- kabel,
- elektrické připojení,
- konfigurace,
- nesprávný typ snímače,
- potřeba kalibrace,
- vlhkost nebo koroze.


## Alarmy a upozornění

### Lze k alarmovému výstupu řídicí jednotky připojit přímo sirénu?

Nelze to předpokládat.

Alarmový výstup řídicí jednotky je obvykle řídicí výstup nebo reléový kontakt. Siréna může vyžadovat samostatné napájení a alarmovou ústřednu.

### Proč se používá alarmová ústředna?

Ústředna může:

- přijímat alarmové signály z řídicích jednotek,
- napájet signalizátor,
- udržovat provoz při výpadku napájení,
- signalizovat alarm zvukem nebo světlem,
- odesílat upozornění GSM ve verzích vybavených touto funkcí.

### Může ústředna hlásit výpadek napájení řídicí jednotky?

Ano, pokud byl systém správně zapojen.

Řešení může detekovat nejen překročení teploty, ale také ztrátu signálu z řídicí jednotky způsobenou výpadkem jejího napájení.

### Kde se nastavuje minimální a maximální teplota alarmu?

V běžné konfiguraci se prahové hodnoty alarmu nastavují v řídicí jednotce obsluhující danou komoru nebo místnost.

Alarmová ústředna následně přijímá informaci, že řídicí jednotka vyhlásila alarm.

### Vyžaduje ústředna GSM SIM kartu?

Pro uskutečňování hovorů a odesílání zpráv prostřednictvím mobilní sítě je zapotřebí aktivní SIM karta nebo jiné komunikační řešení určené pro daný model.

Bez aktivního připojení k mobilní síti nebudou telefonní funkce a SMS fungovat.

### Může alarm odeslat informaci, ze které řídicí jednotky událost pochází?

V odpovídajícím způsobem nakonfigurovaném systému ano.

Vstupy ústředny lze přiřadit ke konkrétním místnostem nebo řídicím jednotkám, takže zpráva umožňuje určit zdroj alarmu.

### Kolik řídicích jednotek lze připojit k jedné alarmové ústředně?

Závisí to na modelu ústředny.

V přepisech se objevovaly ústředny podporující až osm vstupů, před provedením instalace je však nutné ověřit aktuální specifikaci konkrétního zařízení.

### Jaký akumulátor se používá v alarmové ústředně?

V některých zařízeních probíraných v rozhovorech byl používán akumulátor 12 V 7 Ah.

Před nákupem náhrady je nutné ověřit označení na stávajícím akumulátoru a specifikaci ústředny, protože jiné verze zařízení mohou vyžadovat jiný akumulátor.

### Ústředna odesílá zprávy o nízkém napětí. Co zkontrolovat?

Nejprve je nutné zkontrolovat:

- stav akumulátoru,
- jeho stáří,
- připojení akumulátoru,
- přítomnost síťového napájení,
- funkci nabíječky nebo napájecího zdroje ústředny.

Opotřebovaný akumulátor může způsobovat opakované zprávy o nízkém napětí.

### Jak často měnit akumulátor v alarmové ústředně?

Neexistuje jedna hodnota vhodná pro všechny podmínky.

Akumulátor je nutné pravidelně testovat, zejména v instalacích, ve kterých má alarm při výpadku napájení zásadní význam. S přibývajícím stářím jeho skutečná kapacita klesá.

### Stačí jako zabezpečení samotná siréna?

Siréna plní svou funkci pouze tehdy, když ji někdo může slyšet.

V objektech, které zůstávají dočasně bez dozoru, je vhodné používat také vzdálené upozornění a zálohování akumulátorem.


## Frekvenční měniče

### Jak vybrat frekvenční měnič pro ventilátory?

Je nutné znát:

- napájecí napětí,
- počet fází,
- výkon a proud všech motorů,
- způsob jejich zapojení,
- provozní podmínky,
- požadovaný způsob řízení.

Frekvenční měnič by měl mít odpovídající rezervu vzhledem k zátěži, zejména pokud několik motorů pracuje paralelně.

### Měl by mít frekvenční měnič přesně stejný výkon jako součet výkonů motorů?

Frekvenční měnič by se neměl vybírat pouze na základě prostého součtu výkonů a nemělo by se volit zařízení pracující přesně na hranici svých parametrů.

Je nutné zohlednit jmenovité proudy, charakter zátěže a doporučení výrobce frekvenčního měniče.

### Frekvenční měnič zastavil ventilátory a zobrazil chybu. Co dělat?

Nejdůležitější je zaznamenat úplný kód chyby před resetováním.

:::tip Vyfotografujte obrazovku

Pokud to situace umožňuje, před resetováním vyfotografujte displej. Úplný kód chyby výrazně usnadňuje diagnostiku.

:::

Samotný začátek hlášení často nestačí k určení příčiny. Úplný kód umožňuje rozlišit mimo jiné:

- přetížení,
- překročení proudu,
- přehřátí,
- nesprávné napětí,
- jiné chyby pohonu.

### Lze chybu frekvenčního měniče jednoduše resetovat?

Reset může obnovit provoz, ale neodstraňuje příčinu alarmu.

Po události je nutné zkontrolovat kód chyby a určit příčinu před opětovným dlouhodobým spuštěním instalace.

### Frekvenční měnič pracuje v prašné místnosti. Je nutné jej čistit?

Ano.

Prach a usazeniny na chladiči nebo chladicím ventilátoru mohou zhoršovat odvod tepla a vést k přehřívání frekvenčního měniče.

Čištění je nutné provádět podle návodu výrobce po bezpečném odpojení napájení.

### Co může způsobovat přehřívání frekvenčního měniče?

Nejčastějšími příčinami jsou:

- znečištěné chladicí prvky,
- omezené proudění vzduchu,
- příliš vysoká okolní teplota,
- přetížení,
- poškození chladicího ventilátoru,
- nesprávná montáž.

### Může zvýšené síťové napětí vyvolat alarm frekvenčního měniče?

Ano. Frekvenční měniče sledují napětí napájecího obvodu a mohou hlásit chybu při překročení přípustné úrovně.

Pokud se problém opakuje, je nutné zkontrolovat instalaci a kvalitu napájení.


## Poruchy a diagnostika

### Řídicí jednotka funguje, ale displej nic nezobrazuje. Co může být příčinou?

Možné příčiny zahrnují mimo jiné:

- poškození displeje,
- problém s nastavením kontrastu u starších řešení,
- poškození propojení,
- korozi,
- poškození hlavní desky.

Pokud zařízení nebylo dlouhou dobu používáno nebo pracovalo ve vlhkém prostředí, je vhodné zkontrolovat také stav desky.

### Řídicí jednotka má po několika letech nepoužívání problém s displejem. Proč?

Dlouhodobá odstávka ve vlhkém nebo agresivním prostředí může vést k:

- oxidaci konektorů,
- korozi,
- zhoršení kontaktů,
- poškození elektronických součástek.

V takovém případě je vhodné provést úplnou prohlídku, nikoli vyměňovat součástky bez předchozí diagnostiky.

### Řídicí jednotka je po přepětí očazená. Znamená to, že je nutné vyměnit desku?

Ne vždy.

Ochranný prvek se může poškodit a zanechat velké množství usazenin, přestože zbývající část desky lze opravit.

Pokud je však laminát zuhelnatělý, vypálený nebo jsou poškozené vodivé spoje, oprava může být neekonomická nebo nemusí mít dlouhodobou životnost.

### Co může poškodit několik řídicích jednotek současně?

Pokud se více zařízení porouchá ve stejnou dobu, je nutné zkontrolovat napájecí instalaci.

Jednou z možných příčin je problém s nulovým vodičem, který může v třífázové instalaci způsobit výskyt nesprávných napětí na jednofázových spotřebičích.

Možná jsou také přepětí pocházející ze sítě nebo elektrocentrály.

### Co dělat po poruše související s přepětím?

Před připojením opravené nebo nové řídicí jednotky je nutné určit příčinu problému.

:::danger Nepřipojujte zařízení znovu bez kontroly instalace

Pokud příčinou poruchy bylo nesprávné napětí, poškozený nulový vodič nebo přepětí, může být opravená nebo nová řídicí jednotka znovu poškozena.

:::

### Co je přepěťový ochranný prvek na desce?

V elektronických zařízeních se používají prvky omezující přepětí, např. varistory.

Jejich úkolem je pohltit část energie přepětí a chránit navazující obvody. Po silné události může být takový prvek trvale poškozen.

### Lze zařízení spustit po odstranění spáleného ochranného prvku?

Nelze to považovat za běžnou opravu.

Po odstranění ochrany může zařízení ztratit ochranu proti dalšímu přepětí. Takové úkony lze provádět výhradně jako vědomý servisní postup osobou s odpovídající kvalifikací a po odstranění příčiny původní poruchy.

### Řídicí jednotka byla zaplavena nebo silně zkorodovala. Vyplatí se ji opravovat?

Závisí to na rozsahu poškození.

Povrchovou korozi a jednotlivá poškození lze často odstranit. Pokud koroze zasáhla vodivé spoje, konektory a mnoho součástek, může být oprava časově náročná, nejistá a ekonomicky neopodstatněná.

### Může tlakové mytí zařízení poškodit řídicí jednotku?

Ano.

Elektronika by neměla být vystavena přímému působení vody ani čisticího prostředku, pokud k tomu kryt a způsob montáže nejsou určeny.

Vlhkost pronikající dovnitř může vést ke korozi a pozdějším obtížně diagnostikovatelným poruchám.

### Proč se mohou poruchy po zaplavení vracet i po opravě?

Koroze může postupovat také na místech, která nebyla při první kontrole viditelná.

Poškozené prokovy, vodivé spoje a propojení mohou během zkoušky fungovat a později znovu ztratit kontakt.

Proto může servis u silně zkorodované desky doporučit výměnu místo dalších oprav.

### Zařízení někdy funguje a někdy ne. Kde začít?

Před kontaktováním servisu je vhodné shromáždit:

- přesný model,
- popis příznaku,
- okamžik výskytu,
- hodnoty zobrazované na obrazovce,
- kód alarmu nebo chyby,
- informace o posledních změnách v instalaci,
- fotografii vnitřku a svorek, pokud ji lze bezpečně pořídit.

Čím přesnější je popis, tím snazší je diagnostika.


## Servis a opravy

### Co poslat do servisu, pokud je řídicí jednotka poškozená?

Nejlepší je poslat kompletní sestavu umožňující reprodukovat problém.

K zásilce je nutné přiložit stručný popis:

- co nefunguje,
- kdy se problém objevuje,
- zda je porucha trvalá nebo občasná,
- zda před poruchou došlo k přepětí, zaplavení nebo jiné události,
- údaje potřebné pro kontakt a vrácení zařízení.

:::note Údaje pro servisní hlášení

Kontaktní a doručovací údaje předávejte přímo servisu. Nezveřejňujte je ve veřejně přístupných hlášeních ani ve veřejných materiálech.

:::

### Je nutné poslat celou řídicí jednotku, nebo pouze desku?

Závisí to na závadě.

Při problémech s displejem, tlačítky, napájením nebo nejednoznačným chováním je nejlepší poslat celou sestavu potřebnou k reprodukci příznaku.

Při předem dohodnuté opravě konkrétního modulu může servis požádat pouze o desku.

### Opravuje ELETOR řídicí jednotky místo jejich okamžité výměny?

Z přepisů vyplývá, že zařízení nejprve procházejí diagnostikou.

Pokud je oprava možná a smysluplná, vyměňují se poškozené součástky nebo moduly. V případě závažného poškození může servis navrhnout výměnu desky nebo celého zařízení.

### Co se stane, pokud poškozenou desku nelze opravit?

Poškozený modul lze vyměnit za nový, pokud je příslušný díl dostupný a kompatibilní se zařízením.

U starších zařízení by měl servis nejprve potvrdit kompatibilitu verzí.

### Vyplatí se po přepětí rovnou koupit novou desku?

Ne vždy.

Pokud poškození postihuje ochranný prvek nebo malou část obvodu, může být oprava opodstatněná. Nejprve je vhodné provést diagnostiku.

### Může servis zkontrolovat také displej a tlačítka?

Ano, pokud jsou tyto prvky dodány spolu se zařízením nebo modulem.

To je zvláště užitečné tehdy, když není jasné, zda se problém nachází na hlavní desce nebo v uživatelském panelu.

### Vyplatí se silně zkorodovanou řídicí jednotku vždy zachraňovat?

Ne.

Pokud náklady na diagnostiku a opravu rostou a spolehlivost po opravě zůstává nejistá, může být výměna rozumnější.

To se týká zejména zařízení, na kterých závisí větrání objektu.

### Jak urychlit servisní diagnostiku?

Přiložte přesný popis příznaku místo pouhého konstatování „nefunguje“.

Užitečné jsou také:

- fotografie,
- kód chyby,
- popis instalace,
- typ připojených spotřebičů,
- informace o přepětí nebo výpadku napájení,
- informace o zaplavení nebo mytí zařízení.


## Instalace a kabeláž

### Jak připojovat zařízení k reléovým svorkám C a NO?

C a NO jsou běžná označení reléového kontaktu:

- C — společný kontakt,
- NO — spínací kontakt, v klidovém stavu rozepnutý.

Způsob použití závisí na zařízení a schématu instalace. Kontakt lze použít např. k ovládání cívky stykače, nesmí však být překročeny jeho přípustné parametry.

:::warning Elektroinstalační práce

Připojení k síťovému napětí by měla provádět osoba s odpovídající kvalifikací podle schématu konkrétního zařízení.

:::

### Může reléový výstup přímo napájet velký ventilátor?

Obvykle se nejedná o vhodné použití malého řídicího výstupu.

Pro větší zátěže se používá stykač, výkonové relé nebo vyhrazený akční modul.

### K čemu slouží svorky A1 a A2 stykače?

Jedná se o svorky cívky stykače.

Po přivedení odpovídajícího napětí na cívku stykač změní stav svých výkonových kontaktů.

Napětí cívky musí odpovídat projektu instalace a dokumentaci stykače.

### Lze uvnitř krytu řídicí jednotky montovat další přístroje?

Pouze tehdy, pokud to konstrukce konkrétního krytu umožňuje a nezhorší se tím:

- stupeň krytí,
- izolace,
- chlazení,
- bezpečnost,
- servisní přístup.

Veškeré nové otvory by měly být provedeny tak, aby byla zachována požadovaná těsnost.

### Jsou přídavné vypínače ventilátorů užitečné?

Mohou usnadnit servis a umožnit nezávislé odpojení jednotlivých ventilátorů.

Způsob provedení však musí zohledňovat elektrické ochrany a nesmí způsobovat nebezpečné stavy řídicí jednotky.

### Lze řídicí kabely vést společně se silovými kabely?

Je nutné vyhýbat se souběžnému vedení citlivých signálových kabelů ve velmi malé vzdálenosti od kabelů přenášejících velký výkon, zejména na dlouhých úsecích.

Požadavky závisí na typu signálu a elektromagnetickém prostředí.

### Jaký kabel použít pro síťová připojení a zařízení PoE?

V probíraných instalacích byla jako minimum uváděna kroucená dvojlinka kategorie 5e.

Pokud kabel vede prostředím se zvýšenou úrovní rušení nebo rizikem elektrostatických nábojů, může být vhodné použít odpovídajícím způsobem stíněný kabel a správný systém uzemnění.

### Je pro PoE potřeba křížený kabel?

V běžných instalacích se používá standardní přímé zapojení.

Vždy je však nutné ověřit požadavky síťového zařízení a použitého napájecího zdroje PoE.


## Provoz a údržba

### Jak snížit riziko poruch řídicích jednotek v hospodářských budovách?

Nejdůležitější je omezit vliv:

- vlhkosti,
- amoniaku a agresivního prostředí,
- prachu,
- přímého mytí vodou,
- přepětí,
- nesprávného napájení.

Je také vhodné pravidelně kontrolovat stav kabelů, připojení a krytů.

### Měla by se elektronická zařízení pravidelně čistit?

Ano, zejména zařízení vybavená chladiči, ventilátory a větracími otvory.

Nahromaděný prach zhoršuje chlazení.

Čištění je nutné provádět po odpojení napájení a podle návodu zařízení.

### Je vhodné po několika letech provozu provést prohlídku řídicí jednotky?

Ano, zejména v náročných podmínkách prostředí.

Prohlídka může zahrnovat:

- posouzení stavu konektorů,
- kontrolu stop vlhkosti a koroze,
- kontrolu chladicích prvků,
- kontrolu panelu a tlačítek,
- zkoušku snímačů,
- kontrolu akumulátorů v alarmových systémech.

### Co je vhodné zaznamenat po výskytu poruchy?

Nejužitečnější jsou:

- úplné hlášení,
- kód chyby,
- čas události,
- teplota,
- stav větrání,
- informace o výpadku napájení,
- informace o provozu elektrocentrály,
- fotografie obrazovky nebo zařízení.

Zařízení není vhodné resetovat před zaznamenáním kódu, pokud situace umožňuje učinit tak bezpečně.

### Je vhodné mít alarm nezávislý na řídicí jednotce větrání?

Ano, zejména tam, kde porucha větrání může rychle vést k nebezpečným podmínkám.

Nezávislá ústředna s vlastním akumulátorem a vzdáleným upozorňováním poskytuje další vrstvu zabezpečení.

### Jaké informace připravit před kontaktováním technické podpory?

Nejlepší je připravit:

1. přesný model zařízení,
2. popis instalace,
3. počet a parametry připojených zařízení,
4. aktuální nastavení související s problémem,
5. přesný příznak,
6. úplný kód chyby nebo alarmu,
7. fotografie zařízení a typových štítků,
8. informaci o posledních změnách v instalaci.

To umožňuje výrazně zkrátit diagnostiku.


## Důležité upozornění týkající se starších zařízení

Názvy, označení svorek a dostupné funkce se mohou lišit mezi verzemi zařízení vyráběnými v různých letech.

Pokud je zařízení staré několik nebo více než deset let, je před použitím návodu novějšího modelu nutné ověřit:

- přesné označení zařízení,
- verzi desky,
- typ displeje,
- verzi softwaru,
- schéma svorek.

:::warning Starší verze zařízení

Nepředpokládejte úplnou kompatibilitu pouze na základě podobného vzhledu krytu. Před použitím schématu nebo návodu ověřte přesný model a verzi zařízení.

:::


## Kontakt s technickou podporou

Pokud FAQ problém neřeší, připravte si před kontaktováním:

- fotografii řídicí jednotky,
- fotografii typového štítku spotřebiče,
- parametry motorů nebo servopohonů,
- schéma zapojení,
- přesný popis požadovaného způsobu činnosti.

Díky tomu lze výběr zařízení nebo diagnostiku problému provést na základě skutečných parametrů instalace, nikoli domněnek.
