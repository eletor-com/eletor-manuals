---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: A leggyakoribb kérdések az ELETOR készülékek kiválasztásával, konfigurálásával,
  diagnosztikájával és szervizelésével kapcsolatban.
keywords:
- ELETOR
- FAQ
- szellőzésvezérlők
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

A FAQ az ELETOR felhasználóival és ügyfeleivel folytatott valós beszélgetések anonimizált elemzése alapján készült. A válaszokat úgy általánosítottuk, hogy tipikus esetekben segítséget nyújtsanak, és ne tartalmazzanak konkrét személyekre vagy telepítésekre vonatkozó adatokat.

:::note A FAQ hatóköre

A válaszok tipikus esetekre vonatkoznak. A kapocsjelölések, a funkciók és a csatlakoztatás módja modellenként és készülékverziónként eltérhet. Kétség esetén az adott termékhez tartozó dokumentációt használja.

:::

:::warning Biztonság

Az elektromos berendezésen végzett munkákat a készülék dokumentációjának és a hatályos biztonsági előírásoknak megfelelően végezze. A hálózati feszültséggel kapcsolatos munkákat megfelelő képesítéssel rendelkező személy végezze.

:::

## A vezérlő és a teljesítmény kiválasztása

### Hogyan válasszon vezérlőt a ventilátorokhoz?

A kiválasztás alapja elsősorban a ventilátorok összesített árama, nem kizárólag a számuk.

:::tip Készítse elő az adatokat a kiválasztás előtt

Minél pontosabbak a motorokra és a berendezés működési módjára vonatkozó adatok, annál biztosabb a vezérlő kiválasztása.

:::

A kiválasztás előtt érdemes előkészíteni:

- a ventilátorok számát,
- a tápfeszültséget,
- az egyes ventilátorok teljesítményét vagy névleges áramát,
- az információt arról, hogy minden ventilátornak fokozatmentesen kell-e működnie,
- az információt arról, hogy a ventilátorok csoportokra oszthatók-e,
- az egyéb berendezésekre vonatkozó információkat, pl. fűtőegységek vagy légbeömlők.

A vezérlőt nem szabad pontosan „határértékre” méretezni. A maximális terheléshez képest megfelelő tartalékot kell hagyni.

### Elég a ventilátorok teljesítményét wattban összeadni?

Előzetes becsléshez a teljesítmény felhasználható, de a végleges kiválasztásnak a készülékek névleges áramán és a terhelés jellegén kell alapulnia.

A motor indításkor a normál üzemhez képest nagyobb áramot vehet fel. Emiatt két, hasonló névleges teljesítményű ventilátorkészlet nem mindig jelent azonos terhelést a vezérlő számára.

### Több kis ventilátorom van. Csatlakoztathatom őket párhuzamosan egy kimenetre?

Igen, ha:

- alkalmasak erre a vezérlési módra,
- együtt kell működniük,
- a terhelések összege nem haladja meg a kimenet megengedett áramát,
- a csatlakoztatás módja megfelel a vezérlő dokumentációjának.

Nagyobb számú ventilátor esetén érdemes megfontolni a csoportokra osztást vagy teljesítménybővítő modul alkalmazását.

### Mikor szükséges teljesítménybővítő modul?

Teljesítménybővítő modult akkor alkalmaznak, amikor a terhelés meghaladja a vezérlő kimenetének lehetőségeit, vagy amikor a berendezést több ventilátorral kell bővíteni.

Ilyenkor a vezérlő adja a vezérlőjelet, míg a tényleges terhelést egy kiegészítő modul kezeli.

### Bővíthető később a rendszer további ventilátorokkal?

Sok rendszerben igen. A leggyakrabban az alábbiakat alkalmazzák:

- kiegészítő teljesítménybővítő modult,
- kiegészítő szellőzési csoportot,
- a következő csoportot kapcsoló mágneskapcsolót,
- frekvenciaváltót háromfázisú motorok esetén.

A tervezett bővítést célszerű már a vezérlő első kiválasztásakor figyelembe venni.

### Minden ventilátornak fokozatmentesen kell működnie?

Nem. Két tipikus megoldás létezik:

1. minden ventilátor fokozatmentesen működik,
2. az első csoport fokozatmentesen működik, a további csoportok pedig fokozatosan kapcsolódnak be, pl. mágneskapcsolókon keresztül.

A második megoldás lehetővé teszi nagyobb rendszer kezelését anélkül, hogy minden ventilátor fokozatmentes szabályozást kapna.

### Van 10 ventilátorom. Nagyon nagy vezérlőre van szükségem?

Nem mindig. Többféle vezérlési mód alkalmazható:

- csoportokra osztás,
- teljesítménybővítő modulok,
- mágneskapcsolók,
- frekvenciaváltó.

A végleges kiválasztás a ventilátorok villamos paramétereitől, valamint attól függ, hogy mindegyiknek egyszerre kell-e fordulatszámot változtatnia.

### Az 6 A és az 12 A vezérlő csak a megengedett terhelésben különbözik?

Nem szabad feltételezni, hogy az egyetlen különbség az áramérték. Az egyes készülékverziók és generációk felszereltségben vagy kivitelben is eltérhetnek.

Készülékcsere esetén ellenőrizni kell a pontos modellt és az aktuális dokumentációt.


## Ventilátorok és a szellőzés vezérlése

### A vezérlő fokozatmentesen szabályozza a ventilátorokat?

A fokozatmentes szellőzésszabályozásra tervezett vezérlőkben a ventilátorok sebessége az igény függvényében változik, amely többek között a hőmérsékletből adódik.

Ellenőrizni kell azonban, hogy az adott motortípus alkalmas-e az alkalmazott szabályozási módra.

### Mit jelent a beállított hőmérséklet?

A beállított hőmérséklet az az érték, amelyhez a vezérlő az aktuális hőmérsékletmérést viszonyítja.

Ennek alapján a vezérlő növeli vagy csökkenti a szellőzés intenzitását a többi beállításnak megfelelően, pl. a szabályozási sáv, a minimális és maximális szint szerint.

### Mit jelent a minimális szellőzési szint?

Ez a ventilátorvezérlés minimális értéke automatikus üzemben.

A beállítás megakadályozza az olyan szint alatti működést, amelynél a ventilátor instabilan működhetne, vagy túl kicsi légcserét biztosítana.

### Mit jelent a maximális szellőzési szint?

Ez a szellőzésvezérlés értékének felső korlátja.

Például az 100% alatti érték beállítása korlátozhatja a ventilátor maximális fordulatszámát, ha azt a rendszer megköveteli.

### Mit jelent a szellőzési sáv?

A szellőzési sáv azt a hőmérséklet-tartományt határozza meg, amelyben a vezérlő a minimális szellőzési szintről a maximálisra áll át.

Minél kisebb a sáv, annál gyorsabban reagál a szabályozás a hőmérséklet változására a teljesítmény növelésével.

### A ventilátor indítás után először 100% értékre áll, és csak később lassul le. Miért?

Aktív lehet az indítási funkció, amelynek feladata a motor rövid idejű, nagyobb teljesítménnyel történő elindítása.

A vezérlő verziójától függően az alábbiakkal kapcsolatos beállításokat kell ellenőrizni:

- a Soft Start funkciót,
- a felfutási időt,
- az 100% melletti működési időt,
- a kifutási időt.

Ha a funkcióre az adott rendszerben nincs szükség, a megfelelő paraméterek a készülék útmutatójának megfelelően módosíthatók.

### Miért indulhat a ventilátor indításkor rövid időre teljes teljesítménnyel?

Ez az indítás segíthet a ventilátor megbízható beindításában, valamint olyan rendszerekben, ahol a mechanikai elemek induláskor nagyobb ellenállást fejthetnek ki.

Erre azonban nincs szükség minden rendszerben.

### Mit jelent a felfutási idő és a kifutási idő?

**A felfutási idő** azt határozza meg, hogyan növekszik a vezérlés a ventilátor indításakor.

**A kifutási idő** azt határozza meg, hogyan csökken a sebesség.

Mindkét paraméter lehetővé teszi a fordulatszám és a rendszer működésének hirtelen változásai korlátozását.

### Miért indíthat két azonos vezérlő eltérően ventilátorokat?

A leggyakoribb ok az eltérő beállítás.

Érdemes elsősorban az alábbiakat összehasonlítani:

- a beállított hőmérsékletet,
- a szellőzési sávot,
- a minimumot és a maximumot,
- a Soft Start beállításait,
- a felfutási és kifutási időket,
- a szellőzési csoportok konfigurációját.

### A vezérlő képes a szellőzést időszakosan, a hőmérséklettől függetlenül működtetni?

Modelltől függően időszakos átszellőztetési funkció áll rendelkezésre.

Ez meghatározott időre, megadott időközönként elindíthatja a szellőzést akkor is, ha a hőmérséklet-szabályozás nem igényli a szellőzés növelését.

### Mire szolgálnak a szellőzési csoportok?

A csoportok lehetővé teszik a rendszer teljesítményének fokozatos növelését.

Például:

- az 1 csoport fokozatmentesen működik,
- az 2 csoport további ventilátorokat indít,
- a következő csoport még nagyobb igény esetén indul.

Ez lehetővé teszi nagyszámú ventilátor vezérlését anélkül, hogy mindegyik külön fokozatmentes szabályozást kapna.

### Kapcsolható egy további ventilátorcsoport mágneskapcsolón keresztül?

Igen. A vezérlő relékimenete vezérelheti egy megfelelően kiválasztott mágneskapcsoló tekercsét.

A ventilátorok terhelését ilyenkor nem szabad közvetlenül a kis vezérlőérintkezőn keresztül vezetni.

### Mit jelent a ventilátor szimbólum vagy a sárga jelzőlámpa a vezérlőn?

Modelltől függően a jelzőfények az aktuális kimenet- és funkcióállapotokról tájékoztatnak.

A sárga jelzés aktív működési funkciót jelenthet, pl. a szellőzés, a fűtés vagy a következő csoport működését.

A pontos jelentést az adott modell útmutatójában kell ellenőrizni.

### Mit jelent a kézi üzemmód szimbóluma?

A kézi üzemmód azt jelenti, hogy a vezérlési értéket a felhasználó kényszerítette ki, és azt a rendszer az adott pillanatban nem automatikusan, a hőmérséklet alapján számítja.

A tesztek befejezése után meg kell győződni arról, hogy a vezérlő visszaállt a megfelelő automatikus üzemmódba.


## Légbeömlők és működtetők

### Képes a vezérlő a légbeömlők vezérlésére?

Igen, egyes vezérlők lehetővé teszik a légbeömlő-meghajtásokkal való együttműködést.

A csatlakoztatás módja a működtető típusától és vezérlési módjától függ.

### Milyen típusú működtetők használhatók a légbeömlőkhöz?

A műszaki egyeztetések során leggyakrabban két megoldás fordult elő:

- analóg 0–10 V vagy 2–10 V jellel vezérelt működtető,
- reverzáló nyit/zár működtető visszacsatoló jellel, pl. potenciométerről.

Vásárlás előtt ellenőrizni kell az adott modell kompatibilitását a meglévő vezérlővel.

### Számít a 24 V vagy 230 V működtető tápfeszültsége az 0–10 V jel szempontjából?

A vezérlőjel és a működtető tápellátása külön paraméterek.

A működtető tápfeszültsége eltérhet a vezérlőjel feszültségétől. Mindkét paraméternek meg kell felelnie a működtető és a vezérlő dokumentációjának.

### Mit jelent az 0–10 V vezérlés?

A vezérlő feszültségalapú analóg jelet küld, amely a kívánt pozíciót vagy vezérlési szintet reprezentálja.

Tipikus alkalmazásban az alacsonyabb érték kisebb nyitást, a magasabb nagyobbat jelent, de a tényleges karakterisztikát a működtető dokumentációjában kell ellenőrizni.

### Mi a különbség az 0–10 V és az 2–10 V között?

Mindkét esetben a pozíciót analóg jellel adják meg.

Az 2–10 V szabvány esetén a tartomány alsó része el van tolva, és lehetővé teheti a készülék számára a vezérlőjel és annak hiánya közötti különbségtételt.

A vezérlőnek és a működtetőnek azonos tartományt kell támogatnia.

### Hogyan kell a működtetőt a légbeömlők számához kiválasztani?

A működtetőt nem szabad kizárólag a zsalu(k) száma alapján kiválasztani.

Figyelembe kell venni:

- a szükséges erőt vagy nyomatékot,
- a mechanizmus hosszát és vezetésének módját,
- a zsalu(k) ellenállását,
- a löket hosszát,
- a működési sebességet,
- a tápfeszültséget,
- a vezérlés típusát,
- a szükséges visszacsatolást.

### Egy működtető képes több zsalu kiszolgálására?

Igen, ha a rendszer mechanikája lehetővé teszi a zsaluk közös mechanizmussal történő összekapcsolását, és a szükséges nyomaték vagy erő nem haladja meg a működtető képességeit.

A gyakorlatban a kiválasztást a teljes mechanizmus ellenállása határozza meg, nem pusztán a zsaluk száma.

### Több működtető köthető párhuzamosan, és vezérelhető egyetlen jellel?

Egyes rendszerekben ez lehetséges, de ellenőrizni kell a működtetők dokumentációját, valamint a vezérlőkimenet megengedett terhelését.

Független visszacsatolás nélküli reverzáló hajtások esetén az egyes működtetők pozíciói fokozatosan szét is csúszhatnak.

### Miért állhat be idővel több működtető eltérő pozícióba?

Még azonos motorok is működhetnek kissé eltérő sebességgel az alábbiak miatt:

- eltérő terhelés,
- mechanikai ellenállás,
- a motorparaméterek tűrése,
- az áttételek különbségei.

Ezért ha pontos szinkronizálás szükséges, megfelelő visszacsatolásra vagy egyedi pozíciószabályozásra van szükség.

### A légbeömlők arányosan vezérelhetők a szellőzéssel?

Igen. Megfelelően konfigurált rendszerekben a légbeömlők pozíciója összekapcsolható az aktuális szellőzési szinttel.

Ennek köszönhetően a ventilátorok teljesítményének növekedésével együtt a légbeömlők nyitása is növekszik.

### Az 24 V működtető külön tápegységet igényel?

Ha a vezérlő nem rendelkezik a szükséges teljesítményű megfelelő tápkimenettel, külön tápegység szükséges.

A tápegység teljesítményét a működtető áramfelvételéhez, valamint az ugyanabból a forrásból táplált egyéb berendezésekhez kell méretezni.

### Használható más gyártó működtetője?

Gyakran igen, ha a villamos paraméterei és a vezérlési módja kompatibilis a vezérlő kimeneteivel.

Csatlakoztatás előtt ellenőrizni kell:

- a feszültséget,
- a jeltípust,
- a vezetékezési rajzot,
- a működési irányokat,
- a helyzetjelet,
- a megengedett terhelést.


## Hőmérséklet- és páratartalom-érzékelők

### Hová kell csatlakoztatni a hőmérséklet-érzékelőt?

Az érzékelőt a gyártó által előírt érzékelőbemenetre, az adott modell dokumentációjában megjelölt érzékelőbemenetre kell csatlakoztatni.

Nem szabad feltételezni, hogy a kapocsjelölések minden készülékverzióban azonosak.

### A hőmérséklet-érzékelő más értéket mutat, mint a referencia-hőmérő. Mit kell tenni?

Ha a vezérlő rendelkezik érzékelőkalibrálási funkcióval, a kijelzés megbízható referencia-hőmérővel való összehasonlítás után korrigálható.

A kalibráció módosítása előtt érdemes meggyőződni arról, hogy:

- mindkét érzékelő ugyanazon a helyen van,
- a mérés stabilizálódott,
- az érzékelőt nem melegíti a nap vagy más berendezés,
- az érzékelő nincs közvetlenül hideg vagy meleg levegőáramban.

### A páratartalom-érzékelő hibás értéket mutat. Kalibrálható?

Ez a vezérlő, az érzékelő és a szoftver verziójától függ.

Egyes megoldásokban a korrekció megfelelő programfunkciót vagy kompatibilis érzékelőtípust igényelhet. Ha az eltérés nagy és ismétlődő, ellenőrizni kell a készülék verzióját, és kapcsolatba kell lépni a műszaki támogatással.

### Jelent-e a hibás mérés mindig meghibásodott érzékelőt?

Nem.

Az ok lehet még:

- az érzékelő helytelen elhelyezése,
- a vezeték,
- a villamos csatlakozás,
- a konfiguráció,
- nem megfelelő érzékelőtípus,
- kalibráció szükségessége,
- nedvesség vagy korrózió.


## Riasztások és értesítések

### Csatlakoztatható közvetlenül sziréna a vezérlő riasztáskimenetére?

Ezt nem szabad feltételezni.

A vezérlő riasztáskimenete általában vezérlőkimenet vagy reléérintkező. A sziréna külön tápellátást és riasztóközpontot igényelhet.

### Mire szolgál a riasztóközpont?

A központ képes:

- a vezérlőktől érkező riasztási jelek fogadására,
- a jelzőberendezés táplálására,
- működés fenntartására hálózati tápkimaradás esetén,
- a riasztás hang- vagy fényjelzéssel történő jelzésére,
- GSM értesítések küldésére az ezt a funkciót tartalmazó verziókban.

### Képes a központ a vezérlő tápellátásának megszűnéséről is riasztani?

Igen, ha a rendszer megfelelően van bekötve.

A megoldás nemcsak a hőmérséklet túllépését érzékelheti, hanem a vezérlő jelének elvesztését is, amelyet annak tápellátás-kimaradása okoz.

### Hol állítható be a riasztás minimális és maximális hőmérséklete?

Tipikus konfigurációban a riasztási küszöbértékeket az adott kamrát vagy helyiséget kezelő vezérlőben állítják be.

A riasztóközpont ezután azt az információt kapja, hogy a vezérlő riasztást jelzett.

### Szükséges SIM-kártya a GSM központhoz?

Hívások és üzenetek mobilhálózaton keresztüli küldéséhez aktív SIM-kártya vagy az adott modellben előirányzott egyéb kommunikációs megoldás szükséges.

Aktív mobilhálózati kapcsolat nélkül a telefonos és SMS funkciók nem működnek.

### Küldhet-e a riasztás információt arról, melyik vezérlőtől származik az esemény?

Megfelelően konfigurált rendszerben igen.

A központ bemenetei konkrét helyiségekhez vagy vezérlőkhöz rendelhetők, így az üzenet lehetővé teszi a riasztás forrásának meghatározását.

### Hány vezérlő csatlakoztatható egy riasztóközponthoz?

Ez a központ modelljétől függ.

Az átiratokban legfeljebb nyolc bemenetet kezelő központok szerepeltek, azonban a telepítés elvégzése előtt ellenőrizni kell az adott készülék aktuális specifikációját.

### Milyen akkumulátort használnak a riasztóközpontban?

A beszélgetésekben tárgyalt egyes készülékekben 12 V 7 Ah akkumulátort használtak.

Csereakkumulátor vásárlása előtt ellenőrizni kell a meglévő akkumulátor jelölését és a központ specifikációját, mert a készülék más verziói eltérő akkumulátort igényelhetnek.

### A központ alacsony feszültségről küld üzeneteket. Mit kell ellenőrizni?

Elsőként az alábbiakat kell ellenőrizni:

- az akkumulátor állapotát,
- annak korát,
- az akkumulátor csatlakozásait,
- a hálózati táp jelenlétét,
- a központ töltőjének vagy tápegységének működését.

Az elhasználódott akkumulátor ciklikus alacsony feszültségű üzeneteket okozhat.

### Milyen gyakran kell cserélni a riasztóközpont akkumulátorát?

Nincs egyetlen, minden körülményre megfelelő érték.

Az akkumulátort időszakosan tesztelni kell, különösen olyan rendszerekben, ahol a tápellátás kiesése alatti riasztás kritikus jelentőségű. Az életkor előrehaladtával a tényleges kapacitása csökken.

### Elegendő védelemként önmagában a sziréna?

A sziréna csak akkor hatékony, ha valaki hallhatja.

Időszakosan felügyelet nélkül maradó létesítményekben érdemes távértesítést és akkumulátoros tartalékellátást is alkalmazni.


## Frekvenciaváltók

### Hogyan válasszon frekvenciaváltót a ventilátorokhoz?

Ismerni kell:

- a tápfeszültséget,
- a fázisok számát,
- az összes motor teljesítményét és áramát,
- a csatlakoztatás módját,
- az üzemi feltételeket,
- a szükséges vezérlési módot.

A frekvenciaváltónak a terheléshez képest megfelelő tartalékkal kell rendelkeznie, különösen akkor, ha több motor párhuzamosan üzemel.

### A frekvenciaváltónak pontosan akkora teljesítményűnek kell lennie, mint a motorok teljesítményének összege?

A frekvenciaváltót nem szabad kizárólag a teljesítmények egyszerű összeadására alapozva kiválasztani, és olyan készüléket választani, amely pontosan a paraméterhatáron üzemel.

Figyelembe kell venni a névleges áramokat, a terhelés jellegét és a frekvenciaváltó gyártójának ajánlásait.

### A frekvenciaváltó leállította a ventilátorokat és hibát jelzett. Mit kell tenni?

A legfontosabb a teljes hibakód rögzítése a visszaállítás előtt.

:::tip Készítsen fényképet a kijelzőről

Ha a helyzet lehetővé teszi, a visszaállítás előtt készítsen fényképet a kijelzőről. A teljes hibakód jelentősen megkönnyíti a diagnosztikát.

:::

Az üzenet eleje gyakran nem elegendő az ok megállapításához. A teljes kód lehetővé teszi többek között az alábbiak megkülönböztetését:

- túlterhelés,
- áramtúllépés,
- túlmelegedés,
- nem megfelelő feszültség,
- egyéb hajtáshibák.

### Egyszerűen vissza lehet állítani a frekvenciaváltó hibáját?

A visszaállítás helyreállíthatja a működést, de a riasztás okát nem szünteti meg.

Az esemény után ellenőrizni kell a hibakódot, és a rendszer újbóli, tartós indítása előtt meg kell állapítani az okot.

### A frekvenciaváltó poros helyiségben működik. Kell tisztítani?

Igen.

A por és a lerakódások a hűtőbordán vagy a hűtőventilátoron ronthatják a hőelvezetést, és a frekvenciaváltó túlmelegedéséhez vezethetnek.

A tisztítást a gyártó útmutatójának megfelelően, a tápfeszültség biztonságos leválasztása után kell elvégezni.

### Mi okozhatja a frekvenciaváltó túlmelegedését?

A leggyakoribb okok:

- szennyezett hűtőelemek,
- akadályozott légáramlás,
- túl magas környezeti hőmérséklet,
- túlterhelés,
- a hűtőventilátor meghibásodása,
- helytelen szerelés.

### Okozhat-e emelkedett hálózati feszültség frekvenciaváltó-riasztást?

Igen. A frekvenciaváltók ellenőrzik a tápkör feszültségét, és a megengedett szint túllépése esetén hibát jelezhetnek.

Ha a probléma ismétlődik, ellenőrizni kell az elektromos rendszert és a tápellátás minőségét.


## Meghibásodások és diagnosztika

### A vezérlő működik, de a kijelző semmit sem mutat. Mi lehet az oka?

A lehetséges okok többek között:

- a kijelző meghibásodása,
- a kontrasztbeállítás problémája régebbi megoldásokban,
- csatlakozási hiba,
- korrózió,
- az alaplap meghibásodása.

Ha a készüléket hosszú ideig nem használták, vagy nedves környezetben működött, érdemes a panel állapotát is ellenőrizni.

### A vezérlő több év használaton kívüli állapot után kijelzőproblémát mutat. Miért?

A tartós leállás nedves vagy agresszív környezetben az alábbiakhoz vezethet:

- csatlakozók oxidációja,
- korrózió,
- érintkezések romlása,
- elektronikus alkatrészek károsodása.

Ilyen esetben érdemes teljes átvizsgálást végezni, és nem előzetes diagnózis nélkül alkatrészeket cserélni.

### A vezérlő túlfeszültség után kormos. Ez azt jelenti, hogy a panelt cserélni kell?

Nem mindig.

A védőelem megsérülhet, és sok lerakódást hagyhat maga után, miközben a panel többi része még javítható.

Ha azonban a laminátum elszenesedett, kiégett, vagy a vezetősávok sérültek, a javítás gazdaságtalan vagy nem tartós lehet.

### Mi károsíthat egyszerre több vezérlőt?

Ha több készülék hibásodik meg ugyanabban az időben, ellenőrizni kell a tápellátó rendszert.

Az egyik lehetséges ok a nullavezetővel kapcsolatos probléma, amely háromfázisú rendszerben helytelen feszültségek megjelenéséhez vezethet az egyfázisú fogyasztókon.

Lehetséges a hálózatból vagy aggregátorról származó túlfeszültség is.

### Mit kell tenni túlfeszültséggel kapcsolatos meghibásodás után?

A javított vagy új vezérlő csatlakoztatása előtt meg kell állapítani a probléma okát.

:::danger Ne csatlakoztassa újra a készüléket a rendszer ellenőrzése nélkül

Ha a meghibásodást helytelen feszültség, sérült nullavezető vagy túlfeszültség okozta, a javított vagy új vezérlő ismét károsodhat.

:::

### Mi a panelen található túlfeszültség-védelmi elem?

Az elektronikus készülékekben túlfeszültséget korlátozó elemeket, pl. varisztorokat alkalmaznak.

Feladatuk a túlfeszültség energiájának egy részét elnyelni és a további áramköröket védeni. Erős esemény után az ilyen elem maradandóan károsodhat.

### Üzembe helyezhető a készülék a kiégett védőelem eltávolítása után?

Ezt nem szabad normál javításnak tekinteni.

A védelem eltávolítása után a készülék elveszítheti a következő túlfeszültséggel szembeni védelmét. Ilyen műveletet kizárólag tudatos szervizeljárásként, megfelelő képesítéssel rendelkező személy végezhet, és csak az eredeti meghibásodás okának megszüntetése után.

### A vezérlőt eláztatta a víz vagy erősen korrodált. Érdemes javítani?

Ez a károsodás mértékétől függ.

A felületi korrózió és az egyedi sérülések gyakran megszüntethetők. Ha a korrózió a vezetősávokat, a csatlakozókat és sok alkatrészt érintett, a javítás időigényes, bizonytalan és gazdaságilag indokolatlan lehet.

### Károsíthatja a vezérlőt a készülék nyomás alatti mosása?

Igen.

Az elektronikát nem szabad közvetlen víz- vagy tisztítószerhatásnak kitenni, ha a ház és a szerelési mód erre nincs kialakítva.

A belsejébe jutó nedvesség korrózióhoz és későbbi, nehezen diagnosztizálható hibákhoz vezethet.

### Miért térhetnek vissza a meghibásodások az elázás utáni javítás után?

A korrózió az első ellenőrzéskor nem látható helyeken is továbbhaladhat.

A sérült átvezető furatok, vezetősávok és csatlakozások a teszt során működhetnek, később azonban ismét elveszíthetik az érintkezést.

Ezért erősen korrodált panel esetén a szerviz további javítás helyett cserét javasolhat.

### A készülék egyszer működik, máskor nem. Mivel érdemes kezdeni?

A szervizzel való kapcsolatfelvétel előtt érdemes összegyűjteni:

- a pontos modellt,
- a jelenség leírását,
- az előfordulás időpontját,
- a kijelzőn megjelenő értékeket,
- a riasztási vagy hibakódot,
- az utolsó változtatásokra vonatkozó információkat a rendszerben,
- fotót a belső térről és a kapcsokról, ha ez biztonságosan elkészíthető.

Minél pontosabb a leírás, annál könnyebb a diagnózis.


## Szerviz és javítások

### Mit kell a szerviznek elküldeni, ha a vezérlő hibás?

A legjobb a hiba reprodukálását lehetővé tevő teljes egységet elküldeni.

A csomaghoz rövid leírást kell mellékelni:

- mi nem működik,
- mikor jelentkezik a probléma,
- a hiba állandó vagy időszakos-e,
- történt-e a hiba előtt túlfeszültség, elázás vagy más esemény,
- a kapcsolattartáshoz és a készülék visszaküldéséhez szükséges adatok.

:::note A szervizbejelentéshez szükséges adatok

A kapcsolattartási és szállítási adatokat közvetlenül a szerviznek adja meg. Ne tegye közzé őket nyílt bejelentésekben vagy nyilvános anyagokban.

:::

### A teljes vezérlőt kell elküldeni, vagy csak a panelt?

Ez a hibától függ.

Kijelzővel, nyomógombokkal, tápellátással kapcsolatos problémák vagy nem egyértelmű működés esetén a legjobb a jelenség reprodukálásához szükséges teljes egységet elküldeni.

Egy előre egyeztetett, konkrét modul javítása esetén a szerviz kérheti csak a panelt.

### Az ELETOR javítja a vezérlőket ahelyett, hogy azonnal cserélné őket?

Az átiratok alapján a készülékeket először diagnosztizálják.

Ha a javítás lehetséges és indokolt, a sérült alkatrészeket vagy modulokat cserélik. Súlyos sérülés esetén a szerviz a panel vagy a teljes készülék cseréjét javasolhatja.

### Mi történik, ha a sérült panel nem javítható?

Lehetséges a sérült modul újra cserélése, amennyiben a megfelelő alkatrész rendelkezésre áll és kompatibilis a készülékkel.

Régebbi készülékeknél a szerviznek először meg kell erősítenie a verziókompatibilitást.

### Érdemes túlfeszültség után azonnal új panelt venni?

Nem mindig.

Ha a sérülés a védőelemet vagy az áramkör kis részét érinti, a javítás indokolt lehet. Először érdemes diagnózist végezni.

### A szerviz ellenőrizheti a kijelzőt és a gombokat is?

Igen, ha ezek az elemek a készülékkel vagy modullal együtt kerülnek beküldésre.

Ez különösen hasznos akkor, ha nem egyértelmű, hogy a probléma az alaplapon vagy a felhasználói panelen található.

### Egy erősen korrodált vezérlőt mindig érdemes megmenteni?

Nem.

Ha a diagnózis és a javítás költsége nő, miközben a javítás utáni megbízhatóság továbbra is bizonytalan, a csere ésszerűbb lehet.

Ez különösen azokra a készülékekre vonatkozik, amelyektől a létesítmény szellőzése függ.

### Hogyan gyorsítható fel a szervizdiagnosztika?

A puszta „nem működik” megállapítás helyett csatoljon pontos hibaleírást.

Hasznosak továbbá:

- fényképek,
- a hibakód,
- a rendszer leírása,
- a csatlakoztatott fogyasztók típusa,
- információ túlfeszültségről vagy tápkimaradásról,
- információ elázásról vagy a készülék mosásáról.


## Telepítés és kábelezés

### Hogyan kell készülékeket csatlakoztatni a C és NO relékapcsokhoz?

A C és NO a reléérintkezők tipikus jelölései:

- C — közös érintkező,
- NO — normál esetben nyitott érintkező.

A felhasználás módja a készüléktől és a telepítési rajztól függ. Az érintkező például mágneskapcsoló tekercsének vezérlésére használható, de a megengedett paramétereit nem szabad túllépni.

:::warning Elektromos munkák

A hálózati feszültséghez történő csatlakoztatásokat megfelelő képesítéssel rendelkező személynek kell elvégeznie, az adott készülék kapcsolási rajzának megfelelően.

:::

### Képes a relékimenet közvetlenül nagy ventilátort táplálni?

Ez általában nem megfelelő alkalmazása egy kis vezérlőkimenetnek.

Nagyobb terhelésekhez mágneskapcsolót, teljesítményrelét vagy külön végrehajtó modult alkalmaznak.

### Mire szolgálnak a mágneskapcsoló A1 és A2 kapcsai?

Ezek a mágneskapcsoló tekercsének kapcsai.

A megfelelő feszültség tekercsre adása után a mágneskapcsoló megváltoztatja teljesítményérintkezőinek állapotát.

A tekercsfeszültségnek összhangban kell lennie a rendszer tervével és a mágneskapcsoló dokumentációjával.

### Szerelhetők kiegészítő készülékek a vezérlőház belsejébe?

Csak akkor, ha az adott ház kialakítása ezt lehetővé teszi, és ez nem rontja:

- a védettségi fokozatot,
- a szigetelést,
- a hűtést,
- a biztonságot,
- a szervizhozzáférést.

Minden új nyílást úgy kell kialakítani, hogy a szükséges tömítettség megmaradjon.

### Hasznosak a ventilátorokhoz tartozó kiegészítő kapcsolók?

Megkönnyíthetik a szervizelést, és lehetővé tehetik az egyes ventilátorok független leválasztását.

A kialakításnak azonban figyelembe kell vennie a villamos védelmeket, és nem idézheti elő a vezérlő veszélyes állapotait.

### A vezérlőkábelek vezethetők együtt a teljesítménykábelekkel?

Kerülni kell az érzékeny jelkábelek nagy teljesítményű vezetékekkel párhuzamos, nagyon közeli vezetését, különösen hosszú szakaszokon.

A követelmények a jel típusától és az elektromágneses környezettől függenek.

### Milyen kábelt kell használni a hálózati csatlakozásokhoz és a PoE eszközökhöz?

A tárgyalt rendszerekben minimumként 5e kategóriájú sodrott érpár-kábelt jelöltek meg.

Ha a kábel fokozott zavarású vagy elektrosztatikus feltöltődés kockázatával járó környezetben fut, indokolt lehet megfelelően árnyékolt kábel és helyes földelési rendszer alkalmazása.

### PoE-hez szükséges keresztkötésű kábel?

Tipikus rendszerekben szabványos egyenes bekötést alkalmaznak.

Mindig ellenőrizni kell azonban a hálózati eszköz és az alkalmazott PoE tápegység követelményeit.


## Üzemeltetés és karbantartás

### Hogyan csökkenthető a vezérlők meghibásodásának kockázata mezőgazdasági épületekben?

A legfontosabb a következők hatásának korlátozása:

- nedvesség,
- ammónia és agresszív környezet,
- por,
- közvetlen vizes mosás,
- túlfeszültségek,
- nem megfelelő tápellátás.

Érdemes továbbá időszakosan ellenőrizni a vezetékek, csatlakozások és burkolatok állapotát.

### Kell rendszeresen tisztítani az elektronikus készülékeket?

Igen, különösen a hűtőbordákkal, ventilátorokkal és szellőzőnyílásokkal felszerelt berendezéseket.

A felgyülemlett por rontja a hűtést.

A tisztítást a tápellátás leválasztása után és a készülék útmutatójának megfelelően kell elvégezni.

### Erdemes néhány év üzem után átvizsgálást végezni a vezérlőn?

Igen, különösen nehéz környezeti feltételek mellett.

Az átvizsgálás kiterjedhet:

- a csatlakozók állapotának értékelésére,
- a nedvesség- és korróziónyomok ellenőrzésére,
- a hűtőelemek ellenőrzésére,
- a panel és a gombok ellenőrzésére,
- az érzékelők tesztelésére,
- az akkumulátorok ellenőrzésére riasztórendszerekben.

### Mit érdemes feljegyezni meghibásodás esetén?

A leghasznosabbak:

- a teljes üzenet,
- a hibakód,
- az esemény időpontja,
- a hőmérséklet,
- a szellőzés állapota,
- információ a tápkimaradásról,
- információ az aggregátor működéséről,
- fénykép a kijelzőről vagy a készülékről.

A készüléket nem szabad a kód rögzítése előtt visszaállítani, ha a helyzet ezt biztonságosan lehetővé teszi.

### Erdemes a szellőzésvezérlőtől független riasztást alkalmazni?

Igen, különösen ott, ahol a szellőzés meghibásodása gyorsan veszélyes körülményekhez vezethet.

A saját akkumulátorral és távértesítéssel rendelkező független központ további védelmi réteget biztosít.

### Milyen információkat kell előkészíteni a műszaki támogatással való kapcsolatfelvétel előtt?

A legjobb előkészíteni:

1. a készülék pontos modelljét,
2. a rendszer leírását,
3. a csatlakoztatott készülékek számát és paramétereit,
4. a problémával kapcsolatos aktuális beállításokat,
5. a pontos hibajelenséget,
6. a teljes hibakódot vagy riasztási kódot,
7. fényképeket a készülékről és az adattáblákról,
8. információt a rendszer legutóbbi módosításairól.

Ez jelentősen lerövidítheti a diagnózist.


## Fontos megjegyzés a régebbi készülékekről

A különböző években gyártott készülékverziók között eltérhetnek a megnevezések, a kapocsjelölések és az elérhető funkciók.

Ha a készülék több vagy akár több mint tíz éves, újabb modell útmutatójának alkalmazása előtt meg kell erősíteni:

- a készülék pontos jelölését,
- a panel verzióját,
- a kijelző típusát,
- a szoftver verzióját,
- a kapocskiosztási rajzot.

:::warning Régebbi készülékverziók

Ne feltételezzen teljes kompatibilitást pusztán a ház hasonló megjelenése alapján. A kapcsolási rajz vagy útmutató használata előtt erősítse meg a készülék pontos modelljét és verzióját.

:::


## Kapcsolatfelvétel a műszaki támogatással

Ha a FAQ nem oldja meg a problémát, kapcsolatfelvétel előtt készítse elő:

- a vezérlő fényképét,
- a fogyasztó adattáblájának fényképét,
- a motorok vagy működtetők paramétereit,
- a kapcsolási rajzot,
- a kívánt működési mód pontos leírását.

Ennek köszönhetően a készülék kiválasztása vagy a probléma diagnózisa a rendszer tényleges paraméterei alapján végezhető el, nem feltételezések alapján.
