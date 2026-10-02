---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Nejčastější otázky týkající se volby, konfigurace, diagnostiky a servisu
  zařízení ELETOR.
keywords:
- ELETOR
- FAQ
- řídicí jednotky ventilace
- regulátory
- ventilátory
- pohony
- alarmy
- frekvenční měniče
- servis
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Nejčastěji kladené otázky

FAQ vzniklo na základě anonymizované analýzy skutečných rozhovorů s uživateli a zákazníky ELETOR. Odpovědi byly zobecněny tak, aby pomáhaly v typických případech a neobsahovaly údaje o konkrétních osobách ani instalacích.

:::note Rozsah FAQ

Odpovědi se týkají typických případů. Označení svorek, funkce a způsob připojení se mohou lišit mezi modely a verzemi zařízení. V případě pochybností používejte dokumentaci příslušnou pro konkrétní výrobek.

:::

:::warning Bezpečnost

Práce na elektrické instalaci provádějte v souladu s dokumentací zařízení a platnými bezpečnostními předpisy. Práce na síťovém napětí by měla provádět osoba s odpovídající kvalifikací.

:::

## Volba řídicí jednotky a výkonu

### Jak zvolit řídicí jednotku pro ventilátory?

Základem volby je především celkový proud ventilátorů, nikoli pouze jejich počet.

:::tip Připravte údaje před volbou

Čím přesnější údaje o motorech a způsobu provozu instalace, tím jistější bude volba řídicí jednotky.

:::

Před volbou je vhodné připravit:

- počet ventilátorů,
- napájecí napětí,
- jmenovitý výkon nebo proud každého ventilátoru,
- informaci, zda mají všechny ventilátory pracovat plynule,
- informaci, zda lze ventilátory rozdělit do skupin,
- informace o dalších zařízeních, např. ohřívačích nebo přívodech vzduchu.

Řídicí jednotka by se neměla volit přesně „na hraně“. Je nutné zachovat odpovídající rezervu vůči maximálnímu zatížení.

### Stačí sečíst výkon ventilátorů ve wattech?

Pro předběžný odhad lze použít výkon, ale konečná volba by měla vycházet z jmenovitého proudu zařízení a charakteru zatížení.

Motor může při rozběhu odebírat více proudu než při běžném provozu. Z tohoto důvodu nejsou dvě sady ventilátorů s podobným jmenovitým výkonem vždy rovnocenným zatížením pro řídicí jednotku.

### Mám několik malých ventilátorů. Mohu je připojit paralelně k jednomu výstupu?

Ano, pokud:

- jsou určeny pro tento způsob řízení,
- mají pracovat společně,
- součet zatížení nepřekračuje dovolený proud výstupu,
- způsob zapojení je v souladu s dokumentací řídicí jednotky.

Při větším počtu ventilátorů je vhodné zvážit rozdělení do skupin nebo použití výkonového rozšíření.

### Kdy je potřeba výkonové rozšíření?

Výkonové rozšíření se používá tehdy, když zatížení překračuje možnosti výstupu řídicí jednotky nebo když má být instalace rozšířena o větší počet ventilátorů.

Řídicí jednotka pak předává řídicí signál, zatímco vlastní zatížení obsluhuje dodatečný modul.

### Lze instalaci později rozšířit o další ventilátory?

V mnoha instalacích ano. Nejčastěji se používá:

- dodatečné výkonové rozšíření,
- další ventilační skupina,
- stykač spínající další skupinu,
- frekvenční měnič v případě třífázových motorů.

Plánované rozšíření je nejlepší zohlednit již při prvním výběru řídicí jednotky.

### Musejí všechny ventilátory pracovat plynule?

Ne. Typická jsou dvě řešení:

1. všechny ventilátory pracují plynule,
2. první skupina pracuje plynule a další skupiny se připojují postupně, např. pomocí stykačů.

Druhé řešení umožňuje obsloužit větší instalaci bez plynulé regulace každého ventilátoru.

### Mám 10 ventilátorů. Potřebuji velmi velkou řídicí jednotku?

Ne vždy. Lze použít několik způsobů řízení:

- rozdělení do skupin,
- výkonová rozšíření,
- stykače,
- frekvenční měnič.

Konečná volba závisí na elektrických parametrech ventilátorů a na tom, zda mají všechny měnit otáčky současně.

### Liší se řídicí jednotka 6 A a 12 A pouze přípustným zatížením?

Nelze předpokládat, že jediným rozdílem je hodnota proudu. Jednotlivé verze a generace zařízení se mohou lišit výbavou nebo provedením.

Při výměně zařízení je nutné ověřit přesný model a aktuální dokumentaci.


## Ventilátory a řízení ventilace

### Reguluje řídicí jednotka ventilátory plynule?

U řídicích jednotek určených pro plynulou regulaci ventilace se rychlost ventilátorů mění podle potřeby vyplývající mimo jiné z teploty.

Je však nutné ověřit, zda je daný typ motoru vhodný pro použitý způsob regulace.

### Co znamená žádaná teplota?

Žádaná teplota je hodnota, ke které řídicí jednotka vztahuje aktuální měření teploty.

Na jejím základě řídicí jednotka zvyšuje nebo snižuje intenzitu ventilace podle ostatních nastavení, např. regulačního pásma, minimální a maximální úrovně.

### Co znamená minimální úroveň ventilace?

Je to minimální hodnota řízení ventilátoru při automatickém provozu.

Toto nastavení zabraňuje provozu pod úrovní, při které by ventilátor mohl pracovat nestabilně nebo zajišťovat příliš malou výměnu vzduchu.

### Co znamená maximální úroveň ventilace?

Je to horní omezení hodnoty řízení ventilace.

Například nastavení hodnoty pod 100% může omezit maximální otáčky ventilátoru, pokud to instalace vyžaduje.

### Co znamená ventilační pásmo?

Ventilační pásmo určuje rozsah teplot, ve kterém řídicí jednotka přechází od minimální k maximální úrovni ventilace.

Čím menší je pásmo, tím rychleji řízení reaguje zvýšením výkonu na změnu teploty.

### Ventilátor po spuštění nejprve přejde na 100%, a teprve poté zpomalí. Proč?

Může být aktivní rozběhová funkce, jejímž úkolem je krátkodobě spustit motor s vyšším výkonem.

Podle verze řídicí jednotky je třeba zkontrolovat nastavení související s:

- funkcí Soft Start,
- dobou rozběhu,
- dobou provozu při 100%,
- dobou doběhu.

Pokud funkce není v dané instalaci potřebná, lze příslušné parametry změnit podle návodu k zařízení.

### Proč může být ventilátor při startu krátkodobě spuštěn na plný výkon?

Takový rozběh může pomáhat spolehlivému spuštění ventilátoru a v instalacích, kde mohou mechanické prvky při startu klást větší odpor.

Není to však potřeba v každé instalaci.

### Co znamenají doba rozběhu a doba doběhu?

**Doba rozběhu** určuje způsob nárůstu řízení při spouštění ventilátoru.

**Doba doběhu** určuje způsob snižování rychlosti.

Oba parametry umožňují omezit prudké změny otáček a provozu instalace.

### Proč mohou dvě stejné řídicí jednotky spouštět ventilátory odlišně?

Nejčastější příčinou jsou rozdílná nastavení.

Vyplatí se porovnat především:

- žádanou teplotu,
- ventilační pásmo,
- minimum a maximum,
- nastavení Soft Start,
- doby rozběhu a doběhu,
- konfiguraci ventilačních skupin.

### Může řídicí jednotka periodicky spouštět ventilaci nezávisle na teplotě?

V závislosti na modelu je k dispozici funkce periodického provětrávání.

Ta může spouštět ventilaci na stanovenou dobu v nastavených intervalech, i když regulace podle teploty nevyžaduje zvýšení ventilace.

### K čemu slouží ventilační skupiny?

Skupiny umožňují postupné zvyšování výkonu instalace.

Například:

- skupina 1 pracuje plynule,
- skupina 2 spouští další ventilátory,
- další skupina se spouští při ještě vyšší potřebě.

To umožňuje řídit velký počet ventilátorů bez plynulé regulace každého z nich.

### Lze další skupinu ventilátorů spínat pomocí stykače?

Ano. Reléový výstup řídicí jednotky může ovládat cívku vhodně zvoleného stykače.

Zatížení ventilátorů by pak nemělo být vedeno přímo přes malý ovládací kontakt.

### Co znamená symbol ventilátoru nebo žlutá kontrolka na řídicí jednotce?

V závislosti na modelu kontrolky informují o aktuálním stavu výstupů a funkcí.

Žlutá signalizace může znamenat aktivní provozní funkci, např. chod ventilace, vytápění nebo další skupiny.

Přesný význam je nutné ověřit v návodu daného modelu.

### Co znamená symbol ručního režimu?

Ruční režim znamená, že hodnota řízení byla vynucena uživatelem a v daném okamžiku není automaticky vypočítávána na základě teploty.

Po dokončení testů je nutné se ujistit, že byla řídicí jednotka vrácena do správného automatického režimu.


## Přívody vzduchu a pohony

### Může řídicí jednotka ovládat přívody vzduchu?

Ano, vybrané řídicí jednotky umožňují spolupráci s pohony přívodů vzduchu.

Způsob připojení závisí na typu pohonu a způsobu jeho řízení.

### Jaké typy pohonů lze použít pro přívody?

V technických konzultacích se nejčastěji vyskytovala dvě řešení:

- pohon řízený analogovým signálem 0–10 V nebo 2–10 V,
- reverzní pohon otevřít/zavřít se signálem zpětné vazby, např. z potenciometru.

Před nákupem je nutné ověřit kompatibilitu konkrétního modelu se stávající řídicí jednotkou.

### Má napájecí napětí pohonu 24 V nebo 230 V význam pro signál 0–10 V?

Řídicí signál a napájení pohonu jsou samostatné parametry.

Pohon může být napájen jiným napětím než je napětí řídicího signálu. Oba parametry musí být v souladu s dokumentací pohonu a řídicí jednotky.

### Co znamená řízení 0–10 V?

Řídicí jednotka vysílá napěťový analogový signál reprezentující požadovanou polohu nebo úroveň řízení.

V typickém použití nižší hodnota znamená menší otevření a vyšší větší, skutečnou charakteristiku je však nutné ověřit v dokumentaci pohonu.

### Čím se liší 0–10 V od 2–10 V?

V obou případech je poloha zadávána analogovým signálem.

Ve standardu 2–10 V je dolní část rozsahu posunuta a může zařízení umožnit rozlišit řídicí signál od jeho absence.

Řídicí jednotka a pohon musí podporovat shodný rozsah.

### Jak volit pohon podle počtu přívodů?

Pohon by se neměl volit pouze podle počtu klap.

Je třeba zohlednit:

- požadovanou sílu nebo moment,
- délku a způsob vedení mechanismu,
- odpor klap,
- délku zdvihu,
- rychlost činnosti,
- napájecí napětí,
- typ řízení,
- požadovanou zpětnou vazbu.

### Může jeden pohon obsluhovat více klap?

Ano, pokud mechanika instalace umožňuje propojit klapky společným mechanismem a požadovaný moment nebo síla nepřekračuje možnosti pohonu.

V praxi o volbě rozhoduje odpor celého mechanismu, nikoli samotný počet klap.

### Lze několik pohonů spojit paralelně a řídit jedním signálem?

V některých systémech je to možné, je však nutné ověřit dokumentaci pohonů a přípustné zatížení řídicího výstupu.

U reverzních pohonů bez nezávislé zpětné vazby může také dojít k postupnému rozcházení poloh jednotlivých pohonů.

### Proč se může několik pohonů časem nastavovat do různých poloh?

I totožné motory mohou pracovat mírně odlišnou rychlostí z důvodu:

- různého zatížení,
- mechanických odporů,
- tolerance parametrů motoru,
- rozdílů v převodech.

Proto je při požadované přesné synchronizaci nutná správná zpětná vazba nebo individuální řízení polohy.

### Mohou být přívody řízeny proporcionálně k ventilaci?

Ano. Ve vhodně nakonfigurovaných systémech může být poloha přívodů propojena s aktuální úrovní ventilace.

Díky tomu se se zvyšováním výkonu ventilátorů zvětšuje také otevření přívodů.

### Vyžaduje pohon 24 V samostatný napájecí zdroj?

Pokud řídicí jednotka nemá vhodný napájecí výstup s požadovaným výkonem, je potřeba samostatný napájecí zdroj.

Jeho výkon je nutné zvolit podle odběru proudu pohonu a dalších zařízení napájených ze stejného zdroje.

### Lze použít pohon jiné značky?

Často ano, pokud jeho elektrické parametry a způsob řízení odpovídají výstupům řídicí jednotky.

Před připojením je nutné ověřit:

- napětí,
- typ signálu,
- schéma vodičů,
- směry chodu,
- signál polohy,
- přípustné zatížení.


## Snímače teploty a vlhkosti

### Kam připojit snímač teploty?

Snímač je nutné připojit ke snímačovému vstupu určenému výrobcem, ke snímačovému vstupu uvedenému v dokumentaci daného modelu.

Nelze předpokládat, že označení svorek jsou ve všech verzích zařízení totožná.

### Snímač teploty ukazuje jinou hodnotu než referenční teploměr. Co dělat?

Pokud má řídicí jednotka funkci kalibrace snímače, lze údaj korigovat po porovnání se spolehlivým referenčním teploměrem.

Před změnou kalibrace je vhodné se ujistit, že:

- oba snímače se nacházejí na stejném místě,
- měření se ustálilo,
- snímač není zahříván sluncem nebo zařízeními,
- nenachází se přímo v proudu studeného nebo horkého vzduchu.

### Snímač vlhkosti ukazuje nesprávnou hodnotu. Lze jej kalibrovat?

Závisí to na verzi řídicí jednotky, snímače a softwaru.

U některých řešení může korekce vyžadovat odpovídající softwarovou funkci nebo kompatibilní typ snímače. Pokud je rozdíl velký a opakovaný, je nutné ověřit verzi zařízení a kontaktovat technickou podporu.

### Znamená chybná hodnota měření vždy poškozený snímač?

Ne.

Příčinou může být také:

- nevhodné umístění snímače,
- vodič,
- elektrické připojení,
- konfigurace,
- nevhodný typ snímače,
- potřeba kalibrace,
- vlhkost nebo koroze.


## Alarmy a upozornění

### Lze k alarmovému výstupu řídicí jednotky připojit sirénu přímo?

Nelze to předpokládat.

Alarmový výstup řídicí jednotky je obvykle řídicí výstup nebo reléový kontakt. Siréna může vyžadovat samostatné napájení a také ústřednu alarmu.

### K čemu se používá ústředna alarmu?

Ústředna může:

- přijímat alarmové signály z řídicích jednotek,
- napájet signalizátor,
- udržet činnost při výpadku napájení,
- signalizovat alarm zvukem nebo světlem,
- odesílat GSM upozornění u verzí vybavených touto funkcí.

### Může ústředna alarmovat při výpadku napájení řídicí jednotky?

Ano, pokud byl systém správně připojen.

Řešení může detekovat nejen překročení teploty, ale také ztrátu signálu z řídicí jednotky způsobenou výpadkem jejího napájení.

### Kde se nastavuje minimální a maximální teplota alarmu?

V typické konfiguraci se alarmové prahy nastavují v řídicí jednotce obsluhující danou komoru nebo místnost.

Ústředna alarmu následně přijímá informaci, že řídicí jednotka vyhlásila alarm.

### Vyžaduje GSM ústředna SIM kartu?

Pro odesílání hovorů a zpráv přes mobilní síť je zapotřebí aktivní SIM karta nebo jiné komunikační řešení určené pro daný model.

Bez aktivního připojení k mobilní síti nebudou telefonní a SMS funkce fungovat.

### Může alarm odeslat informaci, ze které řídicí jednotky událost pochází?

Ve správně nakonfigurovaném systému ano.

Vstupy ústředny mohou být přiřazeny ke konkrétním místnostem nebo řídicím jednotkám, takže zpráva umožní určit zdroj alarmu.

### Kolik řídicích jednotek lze připojit k jedné ústředně alarmu?

Záleží na modelu ústředny.

V přepisech se vyskytovaly ústředny podporující až osm vstupů, před provedením instalace je však nutné ověřit aktuální specifikaci konkrétního zařízení.

### Jaký akumulátor se používá v ústředně alarmu?

U části zařízení probíraných v rozhovorech byl použit akumulátor 12 V 7 Ah.

Před nákupem náhrady je nutné ověřit označení na stávajícím akumulátoru a specifikaci ústředny, protože jiné verze zařízení mohou vyžadovat jiný akumulátor.

### Ústředna odesílá hlášení o nízkém napětí. Co zkontrolovat?

V první řadě je nutné zkontrolovat:

- stav akumulátoru,
- jeho stáří,
- připojení akumulátoru,
- přítomnost síťového napájení,
- činnost nabíječky nebo napájecího zdroje ústředny.

Opotřebovaný akumulátor může způsobovat opakovaná hlášení o nízkém napětí.

### Jak často měnit akumulátor v ústředně alarmu?

Neexistuje jedna hodnota vhodná pro všechny podmínky.

Akumulátor je nutné periodicky testovat, zejména v instalacích, kde je alarm při výpadku napájení kriticky důležitý. S věkem jeho skutečná kapacita klesá.

### Stačí samotná siréna jako zabezpečení?

Siréna funguje jen tehdy, když ji může někdo slyšet.

V objektech, které zůstávají po určitou dobu bez dozoru, je vhodné používat také vzdálené upozornění a akumulátorové zálohování.


## Frekvenční měniče

### Jak zvolit frekvenční měnič pro ventilátory?

Je nutné znát:

- napájecí napětí,
- počet fází,
- výkon a proud všech motorů,
- způsob jejich zapojení,
- provozní podmínky,
- požadovaný způsob řízení.

Frekvenční měnič by měl mít odpovídající rezervu vůči zatížení, zejména když několik motorů pracuje paralelně.

### Má mít frekvenční měnič přesně stejný výkon jako součet výkonů motorů?

Frekvenční měnič by se neměl volit pouze na základě prostého součtu výkonů a vybírat jako zařízení pracující přesně na hranici parametrů.

Je nutné zohlednit jmenovité proudy, charakter zatížení a doporučení výrobce frekvenčního měniče.

### Frekvenční měnič zastavil ventilátory a zobrazil chybu. Co dělat?

Nejdůležitější je zaznamenat celý chybový kód před resetem.

:::tip Vyfoťte obrazovku

Pokud to situace dovoluje, pořiďte před resetem fotografii displeje. Úplný chybový kód výrazně usnadňuje diagnostiku.

:::

Samotný začátek hlášení často k určení příčiny nestačí. Úplný kód umožňuje rozlišit mimo jiné:

- přetížení,
- překročení proudu,
- přehřátí,
- nesprávné napětí,
- jiné chyby pohonu.

### Lze jednoduše resetovat chybu frekvenčního měniče?

Reset může obnovit provoz, ale neodstraňuje příčinu alarmu.

Po události je nutné zkontrolovat chybový kód a určit příčinu před opětovným dlouhodobým spuštěním instalace.

### Frekvenční měnič pracuje v prašném prostoru. Je třeba jej čistit?

Ano.

Prach a usazeniny na chladiči nebo chladicím ventilátoru mohou zhoršovat odvod tepla a vést k přehřívání frekvenčního měniče.

Čištění je nutné provádět podle pokynů výrobce po bezpečném odpojení napájení.

### Co může způsobovat přehřívání frekvenčního měniče?

Nejčastější příčiny jsou:

- znečištěné chladicí prvky,
- omezené proudění vzduchu,
- příliš vysoká okolní teplota,
- přetížení,
- porucha chladicího ventilátoru,
- nesprávná montáž.

### Může zvýšené síťové napětí vyvolat alarm frekvenčního měniče?

Ano. Frekvenční měniče sledují napětí napájecího obvodu a při překročení přípustné úrovně mohou hlásit chybu.

Pokud se problém opakuje, je nutné zkontrolovat instalaci a kvalitu napájení.


## Poruchy a diagnostika

### Řídicí jednotka funguje, ale displej nic nezobrazuje. Co může být příčinou?

Mezi možné příčiny patří mimo jiné:

- poškození displeje,
- problém s nastavením kontrastu u starších řešení,
- poškození spojení,
- koroze,
- poškození hlavní desky.

Pokud zařízení nebylo delší dobu používáno nebo pracovalo ve vlhkém prostředí, je vhodné zkontrolovat také stav desky.

### Řídicí jednotka má po několika letech nepoužívání problém s displejem. Proč?

Dlouhodobá odstávka ve vlhkém nebo agresivním prostředí může vést k:

- oxidaci konektorů,
- korozi,
- zhoršení kontaktů,
- poškození elektronických součástí.

V takovém případě je vhodné provést kompletní kontrolu, a ne měnit prvky bez předchozí diagnostiky.

### Řídicí jednotka je po přepětí očazená. Znamená to, že je desku nutné vyměnit?

Ne vždy.

Ochranný prvek se může poškodit a zanechat mnoho usazenin, přestože zbytek desky lze opravit.

Pokud je však laminát zuhelnatělý, propálený nebo jsou poškozené vodivé cesty, může být oprava neekonomická nebo netrvalá.

### Co může poškodit několik řídicích jednotek současně?

Pokud dochází k poruše více zařízení ve stejnou dobu, je nutné zkontrolovat napájecí instalaci.

Jednou z možných příčin je problém s nulovým vodičem, který může v třífázové instalaci vést ke vzniku nesprávných napětí na jednofázových spotřebičích.

Možná jsou také přepětí pocházející ze sítě nebo agregátu.

### Co dělat po poruše související s přepětím?

Před připojením opravené nebo nové řídicí jednotky je nutné určit příčinu problému.

:::danger Nepřipojujte zařízení znovu bez kontroly instalace

Pokud byla příčinou poruchy nesprávná napětí, poškozený nulový vodič nebo přepětí, může se opravená nebo nová řídicí jednotka znovu poškodit.

:::

### Co je přepěťový ochranný prvek na desce?

V elektronických zařízeních se používají prvky omezující přepětí, např. varistory.

Jejich úkolem je převzít část energie přepětí a chránit další obvody. Po silné události se takový prvek může trvale poškodit.

### Lze zařízení spustit po odstranění spáleného ochranného prvku?

Nelze to považovat za běžnou opravu.

Po odstranění ochrany může zařízení ztratit ochranu proti dalšímu přepětí. Takové kroky smí být prováděny výhradně jako vědomý servisní postup osobou s odpovídající kvalifikací a po odstranění původní příčiny poruchy.

### Řídicí jednotka byla zatečena nebo silně zkorodovala. Má smysl ji opravovat?

Záleží na stupni poškození.

Povrchovou korozi a jednotlivá poškození lze často odstranit. Pokud koroze zasáhla vodivé cesty, konektory a mnoho součástí, může být oprava časově náročná, nejistá a ekonomicky neodůvodněná.

### Může tlakové mytí zařízení poškodit řídicí jednotku?

Ano.

Elektronika by neměla být vystavena přímému působení vody ani čisticího prostředku, pokud k tomu skříň a způsob montáže nejsou určeny.

Vlhkost pronikající dovnitř může vést ke korozi a pozdějším, obtížně diagnostikovatelným závadám.

### Proč se mohou závady po zatečení po opravě vracet?

Koroze může postupovat i v místech, která nejsou při první kontrole viditelná.

Poškozené prokovení, vodivé cesty a spoje mohou při testu fungovat a později znovu ztratit kontakt.

Proto může servis u silně zkorodované desky doporučit výměnu namísto dalších oprav.

### Zařízení někdy funguje a někdy ne. Čím začít?

Před kontaktováním servisu je vhodné shromáždit:

- přesný model,
- popis příznaku,
- okamžik výskytu,
- hodnoty zobrazené na obrazovce,
- kód alarmu nebo chyby,
- informace o posledních změnách v instalaci,
- fotografii vnitřku a svorek, pokud ji lze bezpečně pořídit.

Čím přesnější popis, tím snazší diagnostika.


## Servis a opravy

### Co zaslat do servisu, pokud je řídicí jednotka poškozená?

Nejlépe je zaslat komplet umožňující reprodukovat problém.

K zásilce je nutné přiložit stručný popis:

- co nefunguje,
- kdy se problém objevuje,
- zda je porucha trvalá nebo občasná,
- zda před poruchou došlo k přepětí, zatečení nebo jiné události,
- údaje potřebné pro kontakt a vrácení zařízení.

:::note Údaje pro servisní hlášení

Kontaktní a zasílací údaje předávejte přímo servisu. Nezveřejňujte je v otevřených hlášeních ani ve veřejných materiálech.

:::

### Je třeba poslat celou řídicí jednotku, nebo jen desku?

Záleží na závadě.

Při problémech s displejem, tlačítky, napájením nebo nejednoznačným chováním je nejlepší zaslat celou sestavu potřebnou k reprodukci příznaku.

Při předem dohodnuté opravě konkrétního modulu může servis požádat pouze o desku.

### Opravuje ELETOR řídicí jednotky místo jejich okamžité výměny?

Z přepisů vyplývá, že se zařízení nejprve diagnostikují.

Pokud je oprava možná a smysluplná, vyměňují se poškozené prvky nebo moduly. V případě vážného poškození může servis navrhnout výměnu desky nebo celého zařízení.

### Co se stane, pokud poškozenou desku nelze opravit?

Je možná výměna poškozeného modulu za nový, pokud je příslušný díl dostupný a kompatibilní se zařízením.

U starších zařízení by měl servis nejprve potvrdit kompatibilitu verze.

### Má smysl kupovat po přepětí hned novou desku?

Ne vždy.

Pokud se poškození týká ochranného prvku nebo malé části obvodu, může být oprava opodstatněná. Nejprve je vhodné provést diagnostiku.

### Může servis zkontrolovat také displej a tlačítka?

Ano, pokud budou prvky dodány spolu se zařízením nebo modulem.

To je zvláště užitečné tehdy, když není jasné, zda je problém na hlavní desce nebo v uživatelském panelu.

### Má vždy smysl zachraňovat silně zkorodovanou řídicí jednotku?

Ne.

Pokud náklady na diagnostiku a opravu rostou a spolehlivost po opravě zůstává nejistá, může být rozumnější výměna.

To se týká zejména zařízení, na nichž závisí ventilace objektu.

### Jak urychlit servisní diagnostiku?

Přiložte přesný popis příznaku místo pouhého konstatování „nefunguje“.

Užitečné jsou také:

- fotografie,
- chybový kód,
- popis instalace,
- typ připojených spotřebičů,
- informace o přepětí nebo výpadku napájení,
- informace o zatečení nebo mytí zařízení.


## Instalace a kabeláž

### Jak připojovat zařízení ke reléovým svorkám C a NO?

C a NO jsou typická označení reléového kontaktu:

- C — společný kontakt,
- NO — normálně otevřený kontakt.

Způsob použití závisí na zařízení a schématu instalace. Kontakt lze použít např. k ovládání cívky stykače, nesmí se však překročit jeho přípustné parametry.

:::warning Elektrické práce

Připojení k síťovému napětí by měla provádět osoba s odpovídající kvalifikací v souladu se schématem konkrétního zařízení.

:::

### Může reléový výstup napájet velký ventilátor přímo?

Obvykle to není vhodné použití malého řídicího výstupu.

Pro větší zatížení se používá stykač, výkonové relé nebo specializovaný výkonový modul.

### K čemu slouží svorky A1 a A2 stykače?

Jsou to svorky cívky stykače.

Po přivedení odpovídajícího napětí na cívku stykač změní stav svých výkonových kontaktů.

Napětí cívky musí odpovídat projektu instalace a dokumentaci stykače.

### Lze uvnitř skříně řídicí jednotky montovat další přístroje?

Pouze tehdy, pokud to konstrukce konkrétní skříně umožňuje a nezhorší to:

- stupeň krytí,
- izolaci,
- chlazení,
- bezpečnost,
- servisní přístup.

Veškeré nové otvory by měly být provedeny tak, aby byla zachována požadovaná těsnost.

### Jsou dodatečné vypínače ventilátorů užitečné?

Mohou usnadnit servis a umožnit nezávislé odpojení jednotlivých ventilátorů.

Způsob provedení však musí zohlednit elektrické ochrany a nesmí způsobovat nebezpečné stavy řídicí jednotky.

### Lze řídicí vodiče vést společně s výkonovými vodiči?

Je nutné se vyvarovat vedení citlivých signálových vodičů paralelně a velmi blízko vodičům velkých výkonů, zejména na dlouhých úsecích.

Požadavky závisí na druhu signálu a elektromagnetickém prostředí.

### Jaký kabel použít pro síťová připojení a zařízení PoE?

V probíraných instalacích byla jako minimum uváděna kroucená dvojlinka kategorie 5e.

Pokud kabel vede v prostředí se zvýšenou úrovní rušení nebo rizikem elektrostatických nábojů, může být vhodné použít odpovídajícím způsobem stíněný kabel a správný systém uzemnění.

### Je pro PoE potřeba křížený kabel?

V typických instalacích se používá standardní přímé zapojení.

Je však vždy nutné ověřit požadavky síťového zařízení a použitého PoE napáječe.


## Provoz a údržba

### Jak omezit riziko poruch řídicích jednotek v hospodářských budovách?

Nejdůležitější je omezit vliv:

- vlhkosti,
- amoniaku a agresivního prostředí,
- prachu,
- přímého mytí vodou,
- přepětí,
- nesprávného napájení.

Je také vhodné periodicky kontrolovat stav vodičů, spojů a skříní.

### Měla by se elektronická zařízení pravidelně čistit?

Ano, zejména zařízení vybavená chladiči, ventilátory a větracími otvory.

Nahromaděný prach zhoršuje chlazení.

Čištění je nutné provádět po odpojení napájení a v souladu s návodem k zařízení.

### Má smysl po několika letech provozu provést kontrolu řídicí jednotky?

Ano, zejména v náročných podmínkách prostředí.

Kontrola může zahrnovat:

- posouzení stavu konektorů,
- kontrolu stop vlhkosti a koroze,
- kontrolu chladicích prvků,
- kontrolu panelu a tlačítek,
- test snímačů,
- kontrolu akumulátorů v alarmových systémech.

### Co je vhodné zaznamenat po vzniku poruchy?

Nejužitečnější jsou:

- celé hlášení,
- chybový kód,
- čas události,
- teplota,
- stav ventilace,
- informace o výpadku napájení,
- informace o provozu agregátu,
- fotografie obrazovky nebo zařízení.

Zařízení by se nemělo resetovat před zaznamenáním kódu, pokud to situace umožňuje bezpečně provést.

### Má smysl mít alarm nezávislý na řídicí jednotce ventilace?

Ano, zejména tam, kde může porucha ventilace rychle vést k nebezpečným podmínkám.

Nezávislá ústředna s vlastním akumulátorem a vzdáleným upozorňováním poskytuje další vrstvu zabezpečení.

### Jaké informace připravit před kontaktováním technické podpory?

Nejlépe je připravit:

1. přesný model zařízení,
2. popis instalace,
3. počet a parametry připojených zařízení,
4. aktuální nastavení související s problémem,
5. přesný příznak,
6. úplný kód chyby nebo alarmu,
7. fotografie zařízení a typových štítků,
8. informaci o posledních změnách v instalaci.

To umožňuje výrazně zkrátit diagnostiku.


## Důležitá poznámka ke starším zařízením

Názvy, označení svorek a dostupné funkce se mohou lišit mezi verzemi zařízení vyráběnými v různých letech.

Pokud je zařízení několik nebo i více než deset let staré, je před použitím návodu z novějšího modelu nutné potvrdit:

- přesné označení zařízení,
- verzi desky,
- typ displeje,
- verzi softwaru,
- schéma svorek.

:::warning Starší verze zařízení

Nepředpokládejte úplnou shodu pouze na základě podobného vzhledu skříně. Před použitím schématu nebo návodu potvrďte přesný model a verzi zařízení.

:::


## Kontakt s technickou podporou

Pokud FAQ problém neřeší, připravte si před kontaktováním:

- fotografii řídicí jednotky,
- fotografii typového štítku spotřebiče,
- parametry motorů nebo pohonů,
- schéma zapojení,
- přesný popis požadovaného způsobu činnosti.

Díky tomu může být volba zařízení nebo diagnostika problému provedena na základě skutečných parametrů instalace, a ne domněnek.
