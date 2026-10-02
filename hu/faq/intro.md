---
id: faq
title: GYIK
sidebar_label: FAQ
slug: /faq
description: Az ELETOR készülékek kiválasztásával, konfigurálásával, diagnosztikájával
  és szervizelésével kapcsolatos leggyakoribb kérdések.
keywords:
- ELETOR
- GYIK
- szellőztetésvezérlők
- szabályozók
- ventilátorok
- működtetők
- riasztások
- frekvenciaváltók
- szerviz
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Gyakran ismételt kérdések

A GYIK az ELETOR felhasználóival és ügyfeleivel folytatott valós beszélgetések anonimizált elemzése alapján készült. A válaszokat általánosítottuk, hogy a tipikus esetekben segítséget nyújtsanak, és ne tartalmazzanak konkrét személyekre vagy rendszerekre vonatkozó adatokat.

:::note A GYIK hatóköre

A válaszok tipikus esetekre vonatkoznak. A kapocsjelölések, a funkciók és a bekötés módja az egyes készülékmodellek és -változatok között eltérhet. Kétség esetén az adott termékhez tartozó dokumentációt használja.

:::

:::warning Biztonság

A villamos berendezésen végzett munkákat a készülék dokumentációjának és a hatályos biztonsági előírásoknak megfelelően végezze. A hálózati feszültséggel kapcsolatos munkákat megfelelő képesítéssel rendelkező személynek kell végeznie.

:::

## A vezérlő és a teljesítmény kiválasztása

### Hogyan kell kiválasztani a vezérlőt a ventilátorokhoz?

A kiválasztás alapja elsősorban a ventilátorok összesített áramfelvétele, nem pedig kizárólag a darabszámuk.

:::tip Készítse elő az adatokat a kiválasztás előtt

Minél pontosabbak a motorokra és a rendszer működési módjára vonatkozó adatok, annál megbízhatóbban választható ki a vezérlő.

:::

A kiválasztás előtt érdemes előkészíteni:

- a ventilátorok számát,
- a tápfeszültséget,
- az egyes ventilátorok teljesítményét vagy névleges áramát,
- az információt arról, hogy minden ventilátornak fokozatmentes szabályozással kell-e működnie,
- az információt arról, hogy a ventilátorok csoportokra oszthatók-e,
- a kiegészítő készülékekre, például légfűtőkre vagy légbeeresztőkre vonatkozó információkat.

A vezérlőt nem szabad pontosan a terhelési határra méretezni. A maximális terheléshez képest megfelelő tartalékot kell biztosítani.

### Elegendő a ventilátorok wattban megadott teljesítményét összeadni?

Az előzetes becsléshez felhasználható a teljesítmény, de a végleges kiválasztásnak a készülékek névleges áramán és a terhelés jellegén kell alapulnia.

A motor indításkor nagyobb áramot vehet fel, mint normál üzemben. Emiatt két, hasonló névleges teljesítményű ventilátorcsoport nem mindig jelent azonos terhelést a vezérlő számára.

### Több kis ventilátorom van. Csatlakoztathatom őket párhuzamosan egy kimenetre?

Igen, ha:

- alkalmasak erre a vezérlési módra,
- együtt kell működniük,
- az összesített terhelés nem haladja meg a kimenet megengedett áramát,
- a bekötés módja megfelel a vezérlő dokumentációjának.

Nagyobb számú ventilátor esetén érdemes megfontolni a csoportokra osztást vagy teljesítménybővítő alkalmazását.

### Mikor van szükség teljesítménybővítőre?

Teljesítménybővítőt akkor alkalmaznak, ha a terhelés meghaladja a vezérlő kimenetének terhelhetőségét, vagy ha a rendszert nagyobb számú ventilátorral kívánják bővíteni.

A vezérlő ilyenkor a vezérlőjelet adja, míg a tényleges terhelést egy kiegészítő modul kezeli.

### Bővíthető később a rendszer további ventilátorokkal?

Sok rendszerben igen. Leggyakrabban a következőket alkalmazzák:

- kiegészítő teljesítménybővítő,
- további szellőztetési csoport,
- a következő csoportot bekapcsoló mágneskapcsoló,
- frekvenciaváltó háromfázisú motorok esetén.

A tervezett bővítést célszerű már a vezérlő első kiválasztásakor figyelembe venni.

### Minden ventilátornak fokozatmentes szabályozással kell működnie?

Nem. Két tipikus megoldás létezik:

1. minden ventilátor fokozatmentes szabályozással működik,
2. az első csoport fokozatmentes szabályozással működik, a további csoportokat pedig lépcsőzetesen kapcsolják be, például mágneskapcsolókkal.

A második megoldás lehetővé teszi egy nagyobb rendszer kezelését az egyes ventilátorok fokozatmentes szabályozása nélkül.

### 10 ventilátorom van. Szükségem van nagyon nagy vezérlőre?

Nem feltétlenül. Többféle vezérlési megoldás alkalmazható:

- csoportokra osztás,
- teljesítménybővítők,
- mágneskapcsolók,
- frekvenciaváltó.

A végleges kiválasztás a ventilátorok villamos paramétereitől és attól függ, hogy mindegyiknek egyidejűleg kell-e változtatnia a fordulatszámát.

### Az 6 A és az 12 A vezérlő csak a megengedett terhelésben különbözik?

Nem szabad feltételezni, hogy az egyetlen különbség az áramérték. A készülékek egyes változatai és generációi felszereltségükben vagy kialakításukban is eltérhetnek.

A készülék cseréjekor ellenőrizni kell a pontos modellt és az aktuális dokumentációt.


## Ventilátorok és szellőztetésvezérlés

### A vezérlő fokozatmentesen szabályozza a ventilátorokat?

A szellőztetés fokozatmentes szabályozására szolgáló vezérlőkben a ventilátorok fordulatszáma többek között a hőmérsékletből adódó igénynek megfelelően változik.

Ellenőrizni kell azonban, hogy az adott motortípus alkalmas-e az alkalmazott szabályozási módra.

### Mit jelent a beállított hőmérséklet?

A beállított hőmérséklet az az érték, amelyhez a vezérlő az aktuális hőmérsékletmérést viszonyítja.

Ennek alapján a vezérlő növeli vagy csökkenti a szellőztetés intenzitását a többi beállításnak, például a szabályozási sávnak, a minimális és maximális szintnek megfelelően.

### Mit jelent a minimális szellőztetési szint?

Ez a ventilátor vezérlésének minimális értéke automatikus működés közben.

A beállítás megakadályozza az olyan szint alatti működést, amelynél a ventilátor instabilan működhetne vagy túl kis légcserét biztosíthatna.

### Mit jelent a maximális szellőztetési szint?

Ez a szellőztetés vezérlési értékének felső korlátja.

Például az 100% alatti érték beállítása korlátozhatja a ventilátor maximális fordulatszámát, ha ezt a rendszer megköveteli.

### Mit jelent a szellőztetési sáv?

A szellőztetési sáv azt a hőmérséklet-tartományt határozza meg, amelyben a vezérlő a minimális szellőztetési szintről a maximálisra vált.

Minél kisebb a sáv, annál gyorsabban reagál a vezérlés a hőmérséklet változására a szellőztetési teljesítmény növelésével.

### A ventilátor indítás után először 100% értékre gyorsul, és csak ezután lassul le. Miért?

Aktív lehet az indítási funkció, amelynek feladata a motor rövid ideig tartó, nagyobb teljesítményű indítása.

A vezérlő változatától függően ellenőrizni kell a következőkhöz kapcsolódó beállításokat:

- a Soft Start funkció,
- a felfutási idő,
- az 100% értéken történő működés ideje,
- a lefutási idő.

Ha a funkcióra az adott rendszerben nincs szükség, a megfelelő paraméterek a készülék útmutatójának megfelelően módosíthatók.

### Miért indulhat a ventilátor rövid időre teljes teljesítménnyel?

Az ilyen indítás segítheti a ventilátor megbízható elindulását, valamint hasznos lehet olyan rendszerekben, amelyekben a mechanikus elemek indításkor nagyobb ellenállást fejthetnek ki.

Erre azonban nem minden rendszerben van szükség.

### Mit jelent a felfutási és a lefutási idő?

**A felfutási idő** a vezérlési érték növekedésének módját határozza meg a ventilátor indításakor.

**A lefutási idő** a fordulatszám csökkentésének módját határozza meg.

Mindkét paraméter lehetővé teszi a fordulatszám és a rendszer működésének hirtelen változásainak korlátozását.

### Miért indíthatja eltérően a ventilátorokat két azonos vezérlő?

A leggyakoribb ok az eltérő beállításokban rejlik.

Elsősorban a következőket érdemes összehasonlítani:

- a beállított hőmérsékletet,
- a szellőztetési sávot,
- a minimumot és a maximumot,
- a Soft Start beállításait,
- a felfutási és lefutási időket,
- a szellőztetési csoportok konfigurációját.

### A vezérlő a hőmérséklettől függetlenül is elindíthatja időszakosan a szellőztetést?

A modelltől függően időszakos átszellőztetési funkció is rendelkezésre áll.

Ez a megadott időközönként meghatározott időre elindíthatja a szellőztetést akkor is, ha a hőmérséklet-szabályozás nem igényli a szellőztetés növelését.

### Mire szolgálnak a szellőztetési csoportok?

A csoportok lehetővé teszik a rendszer szellőztetési teljesítményének lépcsőzetes növelését.

Például:

- az 1 csoport fokozatmentes szabályozással működik,
- az 2 csoport további ventilátorokat indít el,
- a következő csoport még nagyobb igény esetén indul el.

Ez lehetővé teszi nagy számú ventilátor vezérlését az egyes ventilátorok fokozatmentes szabályozása nélkül.

### Bekapcsolható egy további ventilátorcsoport mágneskapcsolóval?

Igen. A vezérlő relékimenete egy megfelelően kiválasztott mágneskapcsoló tekercsét vezérelheti.

A ventilátorok terhelőáramát ilyenkor nem szabad közvetlenül a kis vezérlőérintkezőn átvezetni.

### Mit jelent a ventilátor szimbóluma vagy a sárga jelzőfény a vezérlőn?

A modelltől függően a jelzőfények a kimenetek és funkciók aktuális állapotáról tájékoztatnak.

A sárga jelzés aktív üzemi funkciót jelezhet, például a szellőztetés, a fűtés vagy egy további csoport működését.

A pontos jelentést az adott modell útmutatójában kell ellenőrizni.

### Mit jelent a kézi üzemmód szimbóluma?

A kézi üzemmód azt jelenti, hogy a vezérlési értéket a felhasználó kényszerítette ki, és azt a vezérlő az adott pillanatban nem automatikusan, a hőmérséklet alapján számítja ki.

A tesztek befejezése után meg kell győződni arról, hogy a vezérlőt visszaállították a megfelelő automatikus üzemmódba.


## Légbeeresztők és működtetők

### A vezérlő vezérelhet légbeeresztőket?

Igen, egyes vezérlők lehetővé teszik a légbeeresztők hajtásaival való együttműködést.

A bekötés módja a működtető típusától és vezérlési módjától függ.

### Milyen típusú működtetők alkalmazhatók a légbeeresztőkhöz?

A műszaki beszélgetésekben leggyakrabban két megoldás fordult elő:

- 0–10 V vagy 2–10 V analóg jellel vezérelt működtető,
- nyitás/zárás vezérlésű irányváltó működtető visszacsatolási jellel, például potenciométerről.

Vásárlás előtt ellenőrizni kell az adott modell kompatibilitását a meglévő vezérlővel.

### Van jelentősége a működtető 24 V vagy 230 V tápfeszültségének az 0–10 V jel szempontjából?

A vezérlőjel és a működtető tápellátása különálló paraméterek.

A működtető tápfeszültsége eltérhet a vezérlőjel feszültségétől. Mindkét paraméternek meg kell felelnie a működtető és a vezérlő dokumentációjának.

### Mit jelent az 0–10 V vezérlés?

A vezérlő analóg feszültségjelet küld, amely a kívánt pozíciót vagy vezérlési szintet képviseli.

Tipikus alkalmazásban az alacsonyabb érték kisebb, a magasabb érték nagyobb nyitást jelent, de a tényleges karakterisztikát a működtető dokumentációjában kell ellenőrizni.

### Miben különbözik az 0–10 V az 2–10 V jeltől?

Mindkét esetben analóg jel határozza meg a pozíciót.

Az 2–10 V szabványban a tartomány alsó része el van tolva, ami lehetővé teheti a készülék számára a vezérlőjel és a jel hiányának megkülönböztetését.

A vezérlőnek és a működtetőnek egymással kompatibilis tartományt kell támogatnia.

### Hogyan kell kiválasztani a működtetőt a légbeeresztők számához?

A működtetőt nem szabad kizárólag a csappantyúk száma alapján kiválasztani.

Figyelembe kell venni:

- a szükséges erőt vagy nyomatékot,
- a mechanizmus hosszát és vezetési módját,
- a csappantyúk ellenállását,
- a lökethosszt,
- a működési sebességet,
- a tápfeszültséget,
- a vezérlés típusát,
- a szükséges visszacsatolást.

### Egy működtető több csappantyút is működtethet?

Igen, ha a rendszer mechanikája lehetővé teszi a csappantyúk közös mechanizmussal történő összekapcsolását, és a szükséges nyomaték vagy erő nem haladja meg a működtető képességeit.

A gyakorlatban a kiválasztást a teljes mechanizmus ellenállása határozza meg, nem csupán a csappantyúk száma.

### Több működtető párhuzamosan összekapcsolható és egyetlen jellel vezérelhető?

Egyes rendszerekben ez lehetséges, de ellenőrizni kell a működtetők dokumentációját és a vezérlőkimenet megengedett terhelését.

Független visszacsatolás nélküli irányváltó hajtások esetén az egyes működtetők pozíciói fokozatosan el is térhetnek egymástól.

### Miért állhatnak be idővel eltérő pozíciókba az egyes működtetők?

Még azonos motorok is kissé eltérő sebességgel működhetnek a következők miatt:

- eltérő terhelés,
- mechanikai ellenállások,
- a motorparaméterek tűrése,
- a hajtóművek eltérései.

Ezért, ha pontos szinkronizálás szükséges, megfelelő visszacsatolásra vagy egyedi pozícióvezérlésre van szükség.

### A légbeeresztők a szellőztetéssel arányosan vezérelhetők?

Igen. Megfelelően konfigurált rendszerekben a légbeeresztők pozíciója az aktuális szellőztetési szinthez kapcsolható.

Ennek köszönhetően a ventilátorok szellőztetési teljesítményének növekedésével a légbeeresztők nyitása is növekszik.

### Az 24 V működtető külön tápegységet igényel?

Ha a vezérlő nem rendelkezik megfelelő, a szükséges teljesítményt biztosító tápkimenettel, külön tápegységre van szükség.

Teljesítményét a működtető és az ugyanarról a forrásról táplált további készülékek áramfelvételéhez kell méretezni.

### Alkalmazható más gyártó működtetője?

Gyakran igen, ha villamos paraméterei és vezérlési módja megfelelnek a vezérlő kimeneteinek.

Csatlakoztatás előtt ellenőrizni kell:

- a feszültséget,
- a jel típusát,
- a vezetékek bekötési rajzát,
- a működési irányokat,
- a pozíciójelet,
- a megengedett terhelést.


## Hőmérséklet- és páratartalom-érzékelők

### Hová kell csatlakoztatni a hőmérséklet-érzékelőt?

Az érzékelőt a gyártó által erre a célra kijelölt érzékelőbemenethez, az adott modell dokumentációjában megjelölt érzékelőbemenethez kell csatlakoztatni.

Nem szabad feltételezni, hogy a kapocsjelölések minden készülékváltozatban azonosak.

### A hőmérséklet-érzékelő a referencia-hőmérőtől eltérő értéket mutat. Mi a teendő?

Ha a vezérlő rendelkezik érzékelőkalibrálási funkcióval, a kijelzett érték egy megbízható referencia-hőmérővel való összehasonlítás után korrigálható.

A kalibrálás módosítása előtt érdemes meggyőződni arról, hogy:

- mindkét érzékelő ugyanazon a helyen van,
- a mérés stabilizálódott,
- az érzékelőt nem melegíti a nap vagy valamely készülék,
- az érzékelő nincs közvetlenül hideg vagy meleg légáramban.

### A páratartalom-érzékelő hibás értéket mutat. Kalibrálható?

Ez a vezérlő, az érzékelő és a szoftver változatától függ.

Egyes megoldásoknál a korrekció megfelelő szoftverfunkciót vagy kompatibilis érzékelőtípust igényelhet. Ha az eltérés nagy és ismétlődő, ellenőrizni kell a készülék változatát, és fel kell venni a kapcsolatot a műszaki támogatással.

### A hibás mérés mindig az érzékelő meghibásodását jelenti?

Nem.

Az ok lehet továbbá:

- az érzékelő nem megfelelő elhelyezése,
- a vezeték,
- a villamos csatlakozás,
- a konfiguráció,
- a nem megfelelő érzékelőtípus,
- a kalibrálás szükségessége,
- nedvesség vagy korrózió.


## Riasztások és értesítések

### Csatlakoztatható sziréna közvetlenül a vezérlő riasztókimenetére?

Ezt nem szabad feltételezni.

A vezérlő riasztókimenete általában vezérlőkimenet vagy reléérintkező. A sziréna külön tápellátást és riasztóközpontot igényelhet.

### Miért alkalmaznak riasztóközpontot?

A központ képes lehet:

- riasztási jelek fogadására a vezérlőktől,
- a jelzőkészülék tápellátására,
- a működés fenntartására tápellátás-kimaradás esetén,
- a riasztás hanggal vagy fénnyel történő jelzésére,
- GSM-értesítések küldésére az ilyen funkcióval rendelkező változatokban.

### A központ jelezheti a vezérlő tápellátásának kimaradását?

Igen, ha a rendszert megfelelően bekötötték.

A megoldás nemcsak a hőmérséklet túllépését, hanem a vezérlő tápellátásának kimaradása miatt bekövetkező jelvesztést is észlelheti.

### Hol állítható be a minimális és maximális riasztási hőmérséklet?

Tipikus konfigurációban a riasztási küszöbértékeket az adott kamrát vagy helyiséget kezelő vezérlőben állítják be.

A riasztóközpont ezután azt az információt fogadja, hogy a vezérlő riasztást jelzett.

### A GSM-központ SIM-kártyát igényel?

A mobilhálózaton keresztüli hívásokhoz és üzenetküldéshez aktív SIM-kártyára vagy az adott modellben alkalmazott más kommunikációs megoldásra van szükség.

Aktív mobilhálózati kapcsolat nélkül a telefonos és SMS-funkciók nem működnek.

### A riasztás elküldheti, hogy melyik vezérlőtől származik az esemény?

Megfelelően konfigurált rendszerben igen.

A központ bemenetei meghatározott helyiségekhez vagy vezérlőkhöz rendelhetők, így az üzenet alapján meghatározható a riasztás forrása.

### Hány vezérlő csatlakoztatható egy riasztóközponthoz?

Ez a központ modelljétől függ.

Az átiratokban legfeljebb nyolc bemenetet kezelő központok szerepeltek, de a rendszer kiépítése előtt ellenőrizni kell az adott készülék aktuális specifikációját.

### Milyen akkumulátort alkalmaznak a riasztóközpontban?

A beszélgetésekben tárgyalt készülékek egy részében 12 V 7 Ah akkumulátort alkalmaztak.

Csereakkumulátor vásárlása előtt ellenőrizni kell a meglévő akkumulátor jelölését és a központ specifikációját, mivel más készülékváltozatok más akkumulátort igényelhetnek.

### A központ alacsony feszültségről küld üzeneteket. Mit kell ellenőrizni?

Elsőként a következőket kell ellenőrizni:

- az akkumulátor állapotát,
- az akkumulátor korát,
- az akkumulátor csatlakozásait,
- a hálózati tápellátás meglétét,
- a töltő vagy a központ tápegységének működését.

Az elhasználódott akkumulátor ismétlődő alacsonyfeszültség-üzeneteket okozhat.

### Milyen gyakran kell cserélni a riasztóközpont akkumulátorát?

Nincs minden körülményre megfelelő egyetlen érték.

Az akkumulátort rendszeresen tesztelni kell, különösen olyan rendszerekben, ahol a tápellátás-kimaradás alatti riasztás kritikus jelentőségű. Az életkor előrehaladtával a tényleges kapacitása csökken.

### Elegendő önmagában a sziréna a védelemhez?

A sziréna csak akkor hatásos, ha valaki meghallhatja.

Az időszakosan felügyelet nélkül maradó létesítményekben érdemes távoli értesítést és akkumulátoros tartalék tápellátást is alkalmazni.


## Frekvenciaváltók

### Hogyan kell kiválasztani a frekvenciaváltót a ventilátorokhoz?

Ismerni kell:

- a tápfeszültséget,
- a fázisok számát,
- az összes motor teljesítményét és áramát,
- a motorok bekötési módját,
- az üzemi körülményeket,
- a szükséges vezérlési módot.

A frekvenciaváltónak megfelelő tartalékkal kell rendelkeznie a terheléshez képest, különösen akkor, ha több motor párhuzamosan működik.

### A frekvenciaváltó teljesítményének pontosan meg kell egyeznie a motorok összteljesítményével?

A frekvenciaváltót nem szabad kizárólag a teljesítmények egyszerű összeadása alapján kiválasztani, és olyan készüléket választani, amely pontosan a paraméterhatárain működik.

Figyelembe kell venni a névleges áramokat, a terhelés jellegét és a frekvenciaváltó gyártójának ajánlásait.

### A frekvenciaváltó leállította a ventilátorokat, és hibát jelzett. Mi a teendő?

A legfontosabb a teljes hibakód rögzítése a visszaállítás előtt.

:::tip Készítsen fényképet a kijelzőről

Ha a helyzet lehetővé teszi, a visszaállítás előtt készítsen fényképet a kijelzőről. A teljes hibakód jelentősen megkönnyíti a diagnosztikát.

:::

Az üzenet eleje önmagában gyakran nem elegendő az ok meghatározásához. A teljes kód lehetővé teszi többek között a következők megkülönböztetését:

- túlterhelés,
- áramtúllépés,
- túlmelegedés,
- nem megfelelő feszültség,
- a hajtás egyéb hibái.

### Egyszerűen visszaállítható a frekvenciaváltó hibája?

A visszaállítás helyreállíthatja a működést, de nem szünteti meg a riasztás okát.

Az esemény után ellenőrizni kell a hibakódot, és meg kell határozni az okot a rendszer ismételt, tartós üzembe helyezése előtt.

### A frekvenciaváltó poros helyiségben működik. Szükséges tisztítani?

Igen.

A hűtőbordán vagy a hűtőventilátoron lévő por és lerakódások ronthatják a hőelvezetést, és a frekvenciaváltó túlmelegedéséhez vezethetnek.

A tisztítást a gyártó útmutatója szerint, a tápellátás biztonságos leválasztása után kell végezni.

### Mi okozhatja a frekvenciaváltó túlmelegedését?

A leggyakoribb okok:

- elszennyeződött hűtőelemek,
- akadályozott légáramlás,
- túl magas környezeti hőmérséklet,
- túlterhelés,
- a hűtőventilátor meghibásodása,
- helytelen felszerelés.

### A megemelkedett hálózati feszültség kiválthatja a frekvenciaváltó riasztását?

Igen. A frekvenciaváltók ellenőrzik a tápáramkör feszültségét, és a megengedett szint túllépésekor hibát jelezhetnek.

Ha a probléma ismétlődik, ellenőrizni kell a villamos berendezést és a tápellátás minőségét.


## Meghibásodások és diagnosztika

### A vezérlő működik, de a kijelző nem mutat semmit. Mi lehet az oka?

A lehetséges okok többek között:

- a kijelző meghibásodása,
- kontrasztbeállítási probléma a régebbi megoldásoknál,
- a csatlakozás sérülése,
- korrózió,
- az alaplap meghibásodása.

Ha a készüléket hosszú ideig nem használták, vagy nedves környezetben működött, érdemes a nyomtatott áramköri lap állapotát is ellenőrizni.

### A vezérlő kijelzője több évnyi használaton kívüli állapot után problémás. Miért?

A nedves vagy agresszív környezetben történő hosszú idejű állás a következőkhöz vezethet:

- a csatlakozók oxidációja,
- korrózió,
- az érintkezések romlása,
- az elektronikus alkatrészek károsodása.

Ilyen esetben érdemes teljes átvizsgálást végezni, és nem előzetes diagnosztika nélkül cserélni az alkatrészeket.

### A vezérlő túlfeszültség után kormos. Ez azt jelenti, hogy a nyomtatott áramköri lapot cserélni kell?

Nem feltétlenül.

A védelmi alkatrész meghibásodhat, és jelentős lerakódást hagyhat maga után, miközben a nyomtatott áramköri lap többi része javítható marad.

Ha azonban a laminátum elszenesedett, kiégett, vagy a vezetősávok sérültek, a javítás gazdaságtalan vagy nem tartós lehet.

### Mi károsíthat egyszerre több vezérlőt?

Ha több készülék egyidejűleg meghibásodik, ellenőrizni kell a tápellátást biztosító villamos berendezést.

Az egyik lehetséges ok a nullavezető problémája, amely háromfázisú rendszerben nem megfelelő feszültségek megjelenéséhez vezethet az egyfázisú fogyasztókon.

A hálózatból vagy az áramfejlesztőből származó túlfeszültségek is lehetségesek.

### Mi a teendő túlfeszültséghez kapcsolódó meghibásodás után?

A javított vagy új vezérlő csatlakoztatása előtt meg kell határozni a probléma okát.

:::danger Ne csatlakoztassa újra a készüléket a villamos berendezés ellenőrzése nélkül

Ha a meghibásodást nem megfelelő feszültség, sérült nullavezető vagy túlfeszültség okozta, a javított vagy új vezérlő ismét károsodhat.

:::

### Mi a nyomtatott áramköri lapon található túlfeszültség-védelmi alkatrész?

Az elektronikus készülékekben túlfeszültséget korlátozó alkatrészeket, például varisztorokat alkalmaznak.

Feladatuk a túlfeszültség energiájának egy részét elnyelni és a további áramköröket védeni. Egy erős esemény után az ilyen alkatrész maradandóan károsodhat.

### Elindítható a készülék a kiégett védelmi alkatrész eltávolítása után?

Ezt nem szabad szokásos javításnak tekinteni.

A védelem eltávolítása után a készülék elveszítheti a következő túlfeszültség elleni védelmét. Az ilyen beavatkozás kizárólag tudatos szervizeljárásként, megfelelő képesítéssel rendelkező személy által és az eredeti meghibásodás okának megszüntetése után végezhető.

### A vezérlőt folyadék érte, vagy erősen korrodálódott. Érdemes javítani?

Ez a károsodás mértékétől függ.

A felületi korrózió és az egyedi meghibásodások gyakran megszüntethetők. Ha a korrózió a vezetősávokat, a csatlakozókat és számos alkatrészt érint, a javítás időigényes, bizonytalan és gazdaságilag indokolatlan lehet.

### A nagynyomású mosás károsíthatja a vezérlőt?

Igen.

Az elektronikát nem szabad közvetlen víz- vagy tisztítószerhatásnak kitenni, ha a burkolat és a felszerelés módja nem erre van kialakítva.

A belsejébe jutó nedvesség korrózióhoz és később nehezen diagnosztizálható hibákhoz vezethet.

### Miért térhetnek vissza javítás után a folyadék bejutását követő hibák?

A korrózió olyan helyeken is továbbterjedhet, amelyek az első ellenőrzés során nem láthatók.

A sérült furatgalvanizálások, vezetősávok és csatlakozások a teszt során működhetnek, később azonban ismét elveszíthetik az érintkezést.

Ezért erősen korrodált nyomtatott áramköri lap esetén a szerviz további javítások helyett cserét javasolhat.

### A készülék hol működik, hol nem. Mivel érdemes kezdeni?

A szervizzel való kapcsolatfelvétel előtt érdemes összegyűjteni:

- a pontos modellt,
- a tünet leírását,
- a jelentkezés időpontját,
- a kijelzőn látható értékeket,
- a riasztási vagy hibakódot,
- a rendszerben végzett legutóbbi változtatásokra vonatkozó információkat,
- a belső részről és a kapcsokról készült fényképet, ha az biztonságosan elkészíthető.

Minél pontosabb a leírás, annál könnyebb a diagnosztika.


## Szerviz és javítások

### Mit kell elküldeni a szervizbe, ha a vezérlő meghibásodott?

Célszerű a probléma reprodukálását lehetővé tevő teljes egységet elküldeni.

A küldeményhez rövid leírást kell mellékelni a következőkről:

- mi nem működik,
- mikor jelentkezik a probléma,
- a hiba állandó vagy időszakos-e,
- a meghibásodás előtt történt-e túlfeszültség, folyadékbejutás vagy más esemény,
- a kapcsolattartáshoz és a készülék visszaküldéséhez szükséges adatok.

:::note Adatok a szervizbejelentéshez

A kapcsolattartási és szállítási adatokat közvetlenül a szerviznek adja meg. Ne tegye közzé ezeket nyilvános bejelentésekben vagy nyilvános anyagokban.

:::

### A teljes vezérlőt kell elküldeni, vagy csak a nyomtatott áramköri lapot?

Ez a hibától függ.

A kijelzővel, a gombokkal, a tápellátással kapcsolatos problémák vagy nem egyértelmű működés esetén célszerű a tünet reprodukálásához szükséges teljes egységet elküldeni.

Egy adott modul előzetesen egyeztetett javítása esetén a szerviz csak a nyomtatott áramköri lapot is kérheti.

### Az ELETOR javítja a vezérlőket ahelyett, hogy azonnal cserélné őket?

Az átiratok alapján a készülékeket először diagnosztizálják.

Ha a javítás lehetséges és észszerű, a hibás alkatrészeket vagy modulokat kicserélik. Súlyos károsodás esetén a szerviz a nyomtatott áramköri lap vagy a teljes készülék cseréjét javasolhatja.

### Mi történik, ha a sérült nyomtatott áramköri lap nem javítható?

A hibás modul újra cserélhető, ha a megfelelő alkatrész rendelkezésre áll és kompatibilis a készülékkel.

Régebbi készülékeknél a szerviznek először meg kell erősítenie a változatok kompatibilitását.

### Érdemes túlfeszültség után azonnal új nyomtatott áramköri lapot vásárolni?

Nem feltétlenül.

Ha a károsodás egy védelmi alkatrészt vagy az áramkör kis részét érinti, a javítás indokolt lehet. Először érdemes diagnosztikát végezni.

### A szerviz a kijelzőt és a gombokat is ellenőrizheti?

Igen, ha ezeket az elemeket a készülékkel vagy a modullal együtt eljuttatják a szervizbe.

Ez különösen hasznos akkor, ha nem ismert, hogy a probléma az alaplapon vagy a kezelőpanelen van-e.

### Mindig érdemes megmenteni az erősen korrodált vezérlőt?

Nem.

Ha a diagnosztika és a javítás költsége növekszik, miközben a javítás utáni megbízhatóság bizonytalan marad, a csere észszerűbb lehet.

Ez különösen azokra a készülékekre vonatkozik, amelyektől a létesítmény szellőztetése függ.

### Hogyan gyorsítható fel a szervizdiagnosztika?

A puszta „nem működik” megállapítás helyett mellékelje a tünet pontos leírását.

Hasznosak továbbá:

- a fényképek,
- a hibakód,
- a rendszer leírása,
- a csatlakoztatott fogyasztók típusa,
- a túlfeszültségre vagy tápellátás-kimaradásra vonatkozó információ,
- a folyadékbejutásra vagy a készülék mosására vonatkozó információ.


## Telepítés és kábelezés

### Hogyan kell a készülékeket a C és NO relékapcsokhoz csatlakoztatni?

A C és az NO a reléérintkezők szokásos jelölései:

- C — közös érintkező,
- NO — alaphelyzetben nyitott érintkező.

A felhasználás módja a készüléktől és a rendszer kapcsolási rajzától függ. Az érintkező például mágneskapcsoló tekercsének vezérlésére használható, de megengedett paramétereit nem szabad túllépni.

:::warning Villamos munkák

A hálózati feszültségre történő bekötést megfelelő képesítéssel rendelkező személynek kell elvégeznie, az adott készülék kapcsolási rajzának megfelelően.

:::

### A relékimenet közvetlenül táplálhat nagy ventilátort?

Ez általában nem megfelelő alkalmazása egy kis vezérlőkimenetnek.

Nagyobb terhelésekhez mágneskapcsolót, teljesítményrelét vagy erre szolgáló végrehajtó modult alkalmaznak.

### Mire szolgálnak a mágneskapcsoló A1 és A2 kapcsai?

Ezek a mágneskapcsoló tekercsének kapcsai.

Ha a tekercsre megfelelő feszültséget kapcsolnak, a mágneskapcsoló megváltoztatja a teljesítményérintkezőinek állapotát.

A tekercsfeszültségnek meg kell felelnie a rendszer tervének és a mágneskapcsoló dokumentációjának.

### Beszerelhetők további villamos készülékek a vezérlő burkolatába?

Csak akkor, ha az adott burkolat kialakítása ezt lehetővé teszi, és ez nem rontja:

- a védettségi fokozatot,
- a szigetelést,
- a hűtést,
- a biztonságot,
- a szervizelési hozzáférést.

Minden új nyílást úgy kell kialakítani, hogy a szükséges tömítettség megmaradjon.

### Hasznosak a ventilátorok kiegészítő leválasztó kapcsolói?

Megkönnyíthetik a szervizelést, és lehetővé tehetik az egyes ventilátorok független leválasztását.

A kialakításnak azonban figyelembe kell vennie a villamos védelmeket, és nem idézhet elő veszélyes állapotokat a vezérlőben.

### A vezérlővezetékek az erősáramú vezetékekkel együtt vezethetők?

Kerülni kell az érzékeny jelvezetékek párhuzamos, az erősáramú vezetékekhez nagyon közeli vezetését, különösen hosszú szakaszokon.

A követelmények a jel típusától és az elektromágneses környezettől függnek.

### Milyen kábelt kell alkalmazni hálózati kapcsolatokhoz és PoE-készülékekhez?

A tárgyalt rendszerekben minimumként 5e kategóriájú sodrott érpárú kábelt jelöltek meg.

Ha a kábel fokozott zavarszintű vagy elektrosztatikus feltöltődés veszélyének kitett környezetben halad, indokolt lehet megfelelően árnyékolt kábel és helyes földelési rendszer alkalmazása.

### Szükséges keresztkábel a PoE-hez?

Tipikus rendszerekben szabványos egyenes bekötést alkalmaznak.

Mindig ellenőrizni kell azonban a hálózati készülék és az alkalmazott PoE-tápegység követelményeit.


## Üzemeltetés és karbantartás

### Hogyan csökkenthető a vezérlők meghibásodásának kockázata gazdasági épületekben?

A legfontosabb a következők hatásának korlátozása:

- nedvesség,
- ammónia és agresszív környezet,
- por,
- közvetlen vizes mosás,
- túlfeszültségek,
- nem megfelelő tápellátás.

Érdemes a vezetékek, csatlakozások és burkolatok állapotát is rendszeresen ellenőrizni.

### Rendszeresen tisztítani kell az elektronikus készülékeket?

Igen, különösen a hűtőbordákkal, ventilátorokkal és szellőzőnyílásokkal ellátott készülékeket.

A felgyülemlett por rontja a hűtést.

A tisztítást a tápellátás leválasztása után, a készülék útmutatójának megfelelően kell végezni.

### Érdemes több év működés után átvizsgálni a vezérlőt?

Igen, különösen nehéz környezeti körülmények között.

Az átvizsgálás kiterjedhet:

- a csatlakozók állapotának felmérésére,
- a nedvesség és korrózió nyomainak ellenőrzésére,
- a hűtőelemek ellenőrzésére,
- a panel és a gombok ellenőrzésére,
- az érzékelők tesztelésére,
- a riasztórendszerek akkumulátorainak ellenőrzésére.

### Mit érdemes feljegyezni meghibásodás után?

A leghasznosabbak:

- a teljes üzenet,
- a hibakód,
- az esemény időpontja,
- a hőmérséklet,
- a szellőztetés állapota,
- a tápellátás-kimaradásra vonatkozó információ,
- az áramfejlesztő működésére vonatkozó információ,
- a kijelzőről vagy a készülékről készült fénykép.

Nem szabad visszaállítani a készüléket a kód rögzítése előtt, ha a helyzet lehetővé teszi annak biztonságos elvégzését.

### Érdemes a szellőztetésvezérlőtől független riasztórendszert használni?

Igen, különösen ott, ahol a szellőztetés meghibásodása gyorsan veszélyes körülményekhez vezethet.

A saját akkumulátorral és távoli értesítéssel rendelkező független központ további védelmi szintet biztosít.

### Milyen információkat kell előkészíteni a műszaki támogatással való kapcsolatfelvétel előtt?

Célszerű előkészíteni:

1. a készülék pontos modelljét,
2. a rendszer leírását,
3. a csatlakoztatott készülékek számát és paramétereit,
4. a problémához kapcsolódó aktuális beállításokat,
5. a pontos tünetet,
6. a teljes hiba- vagy riasztási kódot,
7. a készülékről és az adattáblákról készült fényképeket,
8. a rendszerben végzett legutóbbi változtatásokra vonatkozó információt.

Ez lehetővé teszi a diagnosztikai idő jelentős lerövidítését.


## Fontos megjegyzés a régebbi készülékekről

A megnevezések, a kapocsjelölések és a rendelkezésre álló funkciók eltérhetnek a különböző években gyártott készülékváltozatok között.

Ha a készülék néhány vagy tízegynéhány éves, egy újabb modell útmutatójának alkalmazása előtt meg kell erősíteni:

- a készülék pontos típusjelölését,
- a nyomtatott áramköri lap változatát,
- a kijelző típusát,
- a szoftververziót,
- a kapocskiosztási rajzot.

:::warning Régebbi készülékváltozatok

Ne feltételezzen teljes kompatibilitást pusztán a burkolat hasonló megjelenése alapján. A kapcsolási rajz vagy az útmutató használata előtt erősítse meg a készülék pontos modelljét és változatát.

:::


## Kapcsolatfelvétel a műszaki támogatással

Ha a GYIK nem oldja meg a problémát, a kapcsolatfelvétel előtt készítse elő:

- a vezérlőről készült fényképet,
- a fogyasztó adattáblájáról készült fényképet,
- a motorok vagy működtetők paramétereit,
- a bekötési rajzot,
- az elvárt működési mód pontos leírását.

Ennek köszönhetően a készülék kiválasztása vagy a probléma diagnosztizálása a rendszer tényleges paraméterei, nem pedig feltételezések alapján végezhető el.
