---
id: sc-pe16
title: SC-PE16 — használati útmutató
sidebar_label: SC-PE16
sidebar_position: 5
description: Az SC-PE16 teljesítménybővítő útmutatója — felszerelés, csatlakoztatás,
  üzembe helyezés, menü és védelmek.
slug: /sc-pe16
toc_min_heading_level: 2
toc_max_heading_level: 3
---


Az SC-PE16 teljesítménybővítő ventilátorok vezérlésére szolgál, ha a terhelés meghaladja a fölérendelt vezérlő terhelhetőségét. A készülék analóg jel vagy kézi beállítás alapján szabályozza a ventilátorok tápfeszültségét. A kimenet maximális összesített árama 16 A.

![Teljesítménybővítő ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Paraméterek és jellemzők

- AUTO és MANUAL üzemmód, valamint a készülék alvó állapota;
- grafikus kijelző és érintőbillentyűzet;
- analóg vezérlés 2–10 V vagy 4–20 mA;
- a szellőztetés 2. csoportjának programozható bekapcsolási küszöbértéke;
- byPASS állandósult 100% szintnél;
- a teljesítményáramkör hővédelme;
- safeRUN: beállítható vészüzemi szint;
- a minimális szellőztetési szint kalibrálása;
- a szellőztetés, a relé és a riasztás tesztelése;
- billentyűzár és tisztítási zárolás;
- lengyel, angol vagy ukrán nyelv;
- tápellátás 230 V AC, 50 Hz; készülékház IP65.

:::info Szoftververzió

A funkciók leírása a mellékelt **szoftver 2.1** verziójára vonatkozik. A funkciók elérhetőségét a készülékre telepített verzió alapján kell megítélni.

:::

## A vezérlő telepítése

:::danger Válassza le a tápellátást

A készülék telepítése során az elektromos tápellátást feltétlenül le kell választani, mert egyes alkatrészeken az életre és az egészségre veszélyes feszültség van jelen. Javasolt a telepítést szakképzett személyre bízni.

:::

### A felszerelési hely kiválasztása

A készüléket a kezelő számára hozzáférhető, gyermekek és állatok által el nem érhető, közvetlen napsugárzástól védett helyre kell felszerelni. A környezeti hőmérséklet tartománya −10°C és +40°C között van. A készülékház és a hűtőborda körül biztosítani kell a levegő szabad áramlását. A hűtőbordát tilos letakarni, és a készüléket tilos hőforrások közelébe szerelni.

### Felszerelés

A készülékház alsó részét négy dübellel rögzítse sík falra, a tömített rekeszen kívüli szerelőfuratok felhasználásával. A fedelet a készlethez mellékelt zsanérral szerelje fel. Lezárás előtt ellenőrizze a tömítés állapotát és elhelyezkedését.

A tömszelencékhez illeszkedő, kör keresztmetszetű külső köpennyel rendelkező kábeleket használjon. A tömszelencéket úgy húzza meg, hogy tömítsék és rögzítsék a kábelt. A nem használt kábelátvezetéseket zárja le. A fedelet az összes csavarral rögzítse. A tömítettség a készülékház és a kábelátvezetések megfelelő felszerelésétől függ.

### A csatlakoztatások előkészítése

A készülékházon belül minden munkát a tápellátás leválasztása és a feszültségmentesség ellenőrzése után végezzen. Ha a panel eltávolításához a szalagkábel leválasztása szükséges, óvatosan válassza le, majd a készülékház lezárása előtt csatlakoztassa újra megfelelően. Bekapcsolt tápellátás mellett ne csatlakoztassa és ne válassza le a szalagkábelt.

Az INPUT és ENABLE jelvezetékeket a táp- és kimeneti vezetékektől elkülönítve vezesse. Az adott készülékpéldányon feltüntetett kapocsjelöléseket vegye figyelembe. A jelbemenetek testpontja és a PE védővezető-kapocs eltérő funkciót lát el, és nem helyettesíthetők egymással.

## Elektromos csatlakoztatás

:::danger Válassza le a tápellátást

Az áramkör csatlakoztatása előtt győződjön meg arról, hogy a tápellátás ki van kapcsolva!

:::

![Tápellátás, ventilátorok, GR 2, ENABLE, CAN és INPUT kapcsai](./img/sc-pe16/zaciski.png)

| KAPOCS | RENDELTETÉS |
| --- | --- |
| L, N, PE — tápellátás | Tápellátás 230 V AC, 50 Hz: L — fázisvezető, N — nullavezető, PE — védővezető. Az eredeti dokumentáció B20 védelmet ír elő; a védelmek és a vezetékek kiválasztásakor figyelembe kell venni a villamos hálózatot és a terhelést. |
| U, N, PE — ventilátorok | U — szabályozott fáziskimenet; N és PE — a készülék megfelelő közös kapcsai. A ventilátorok összesített árama nem haladhatja meg az 16 A értéket. Minden ventilátorhoz külön védelem szükséges. Feszültségszabályozásra engedélyezett motorokat használjon. |
| GR 2: C, NO | A 2. csoport galvanikusan leválasztott reléérintkezője. Bekapcsol, ha a szellőztetés alapjele eléri vagy meghaladja a „Szellőztetés 2. csoportja” küszöbértékét. Az érintkező maximális árama a mellékelt útmutató szerint: 6 A. A terhelés közvetlen vezérlése esetén a dokumentáció B6 külső védelmet ír elő. |
| INPUT: V, test | Feszültségbemenet. Válassza a „Vezérlés típusa → V bemenet” lehetőséget. A vizsgált programban a szabályozási tartomány 2–10 V. Erre a bemenetre tilos hálózati feszültséget vagy a ventilátorok szabályozott tápkimenetét csatlakoztatni. |
| INPUT: I, test | 4–20 mA árambemenet. Válassza a „Vezérlés típusa → I bemenet” lehetőséget. A jelet a forrás és a fogadó jelöléseinek megfelelően csatlakoztassa. |

A vezérléshez a kiválasztott V vagy I bemenetet használja. Az SC-PE16 saját hálózati tápellátást igényel; az analóg bemenet csak a vezérlési értéket továbbítja.

## ENABLE bemenet és kommunikáció

### ENABLE: E és test

A bemenet potenciálmentes érintkezővel működik együtt. Az E kapcsot és a testpontot kizárólag összezárni vagy szétválasztani szabad; külső feszültséget tilos rájuk kapcsolni. A zárt állapot engedélyezi a működést, a nyitott állapot 0% szintet ad meg. A leállás a „Kifutási idő” beállításnak megfelelően történik.

Az ENABLE kezelése az AUTO és az MANUAL esetében külön kapcsolható be a „Speciális → Ventilátor” menüben. Gyárilag mindkét funkció ki van kapcsolva, ezért ilyenkor nincs szükség átkötésre. Az ENABLE nyitott állapota nem azonos az alvó állapottal: a panel aktív marad. AUTO esetén, aktív ENABLE tiltás mellett a program kihagyja a vezérlőjel beolvasását, és nem indítja el a safeRUN funkciót.

### CAN és Wi-Fi

A „CAN bemenet” és a „WiFi bemenet” menüpontok szerepelnek a menüben, de az 2.1 szoftververzióban nem valósítanak meg vezérlést: mindkét funkció 0% szintet ad vissza. A készülék ezzel a programmal történő üzembe helyezéséhez válassza a V vagy I bemenetet. Ne konfigurálja a rendszert CAN vagy Wi-Fi alapú működésre anélkül, hogy megerősítést kapna a telepített szoftververzió támogatásáról.

## Működési elv

Az SC-PE16 a fölérendelt vezérlő vagy a kezelő utasításait végrehajtó teljesítményszabályozó. Nem méri a helyiség hőmérsékletét, és nem rendelkezik saját hőmérséklet-, átszellőztetés-, ráfűtés- vagy légbeeresztőcsappantyú-beállításokkal. A százalékos szellőztetési szint vezérlési értéket jelent, nem a motor tényleges fordulatszámának mérését.

| NÉVLEGES JEL | SZELLŐZTETÉSI ALAPJEL |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

A határértékek között a program lineárisan határozza meg a szintet, és egész százalékra kerekíti. A V bemenetnél a növekedés az 2,04 V, az I bemenetnél pedig az 4,04 mA beolvasott érték túllépése után kezdődik. A kimenet végleges állapota az ENABLE bemenettől, az indítástól és a hővédelemtől is függ.

## Vészüzem és védelmek

### safeRUN — a bemeneti jel megszűnése

AUTO üzemmódban a „Bemenet” riasztás akkor jelenik meg, ha a beolvasott feszültség 1,50 V alá vagy az áram 2,00 mA alá csökken, a kiválasztott bemenettől függően. A program ekkor a „Vészüzem” szintjét adja meg az 0–100% tartományban; a gyári érték 30%. Miután a jel visszatér az érzékelési küszöbértékre vagy afölé, a bemeneti riasztás megszűnik, és a készülék visszatér az analóg vezérléshez.

Az 1,50–2,04 V és az 2,00–4,04 mA tartomány 0% szintet eredményez bemeneti riasztás nélkül. Az 0 V jel ebben a verzióban nem egyszerű leállítási parancs — vészüzemet indít el. Az 0–10 V kimenettel rendelkező fölérendelt vezérlőt az 2–10 V tartományra kell konfigurálni, az 0 V értékre történő lekapcsolás nélkül. MANUAL esetén az analóg jel nem vezérli a szellőztetést, és a bemeneti riasztás törlődik.

### Hővédelem

A „Túlmelegedés” riasztás akkor aktiválódik, ha a hűtőborda beolvasott hőmérséklete meghaladja az 87°C értéket. A riasztás az 80°C alá csökkenés után törlődik. A riasztás alatt a program módosítja az alapjelet: legalább 50% érték esetén 100%, 50% alatti érték esetén pedig 0% szintet ad meg. A kimenet módosítása az indítási és kifutási algoritmus szerint történik. A védelem nem garantálja minden esetben a szellőztetés folyamatos működését.

A GR 2 relé állapotának meghatározása a hőmérsékleti korrekció előtt történik: állapota az 0% vagy 100% szint kényszerítése előtti szinttől függ. A vészüzemi szintre is érvényes a hőmérsékleti korrekció. Túlmelegedés esetén ellenőrizze a hűtés körülményeit, a hűtőborda szennyezettségét és a terhelést; a készülékházon belüli munkákat megfelelő jogosultsággal rendelkező személyre bízza.

### byPASS és lágyindítás

Állandósult 100% kimeneti szintnél a program bekapcsolja a fázishasításos szabályozóáramkört áthidaló relét. Az indítás magában foglalhatja az 100% szintig történő felfutást, az 100% szinten tartást és az alapjelre történő átmenetet. A „Lágyindítás” paraméterei a kimenetnek az igény változására adott reakciósebességét is befolyásolják.

## A vezérlő első üzembe helyezése

:::warning A ventilátorok kalibrálása

Figyelem! A készülék első üzembe helyezésekor feltétlenül be kell állítani a motor tiltott működési tartományát.

:::

1. Leválasztott tápellátás mellett ellenőrizze a tápellátás, a PE, a ventilátorok és az analóg jel csatlakoztatását. Ellenőrizze, hogy a motorok engedélyezettek-e feszültségszabályozásra, és az összesített áram legfeljebb 16 A-e.
2. Kapcsolja be a tápellátást. Ha megjelenik a nyelvválasztási lehetőség, nyomja meg az OK gombot, és válassza ki a nyelvet. Oldja fel a billentyűzárat a lakat szimbólummal jelölt gombbal.
3. A „Vezérlés típusa” menüpontban válassza a „V bemenet” vagy az „I bemenet” lehetőséget. Állítsa be a „Vészüzem” szintjét és a „Szellőztetés 2. csoportja” küszöbértékét. Szükség esetén külön aktiválja az ENABLE funkciót a megfelelő üzemmódhoz.
4. Lépjen be a „Speciális → Ventilátor → Tiltott tartomány” menüpontba. Ebben a menüpontban a program 1% szintet kényszerít ki, és a paraméter módosítása azonnal hat a kimenetre. A tartomány −20 és 200 között van, a gyári érték 0. A pozitív érték növeli, a negatív csökkenti a minimális vezérlési szintet.
5. Úgy válassza meg az értéket, hogy minden ventilátor stabilan, leállás és túlzott melegedés nélkül forogjon. Figyeljen meg minden ventilátort, lehetőleg egy másik személy segítségével. A csappantyú puszta megemelkedése nem helyettesíti a motor megfelelő működésének ellenőrzését. Az OK gombbal hagyja jóvá; az ESC visszaállítja az előző beállítást.
6. Ellenőrizze a kimenetet több szinten, beleértve az 0% szintet, egy alacsony szintet és az 100% szintet. A ventilátorok cseréje vagy konfigurációjuk módosítása után ismételje meg a kalibrálást.
7. AUTO esetén ellenőrizze a minimális és maximális jelre adott reakciót. Ezután ellenőrizze a jel megszakadását és a vészüzemre váltást, valamint a jel helyreállítása utáni visszatérést. Ha az ENABLE aktív, annak működését is ellenőrizze.
8. Ellenőrizze a GR 2 relét és a riasztásjelzést a „Tesztelés” menüben. A tesztek befejezése után lépjen ki ebből a menüpontból, és válassza ki a végleges üzemmódot.

:::warning A kimenetek tényleges működtetése

A tesztelés és a kalibrálás a tényleges kimeneteket vezérli. Elindíthatják a ventilátorokat, a szellőztetési teszt pedig a normál vezérléstől függetlenül kényszeríti ki a szintet. Biztosítsa a teszt biztonságos körülményeit és a folyamatos felügyeletet.

:::

## A vezérlő programozása

### Előlap — jelzőfények és gombok

| ELEM | KEZELÉS |
| --- | --- |
| Tápellátás / alvó állapot | A tápellátás szimbólumával jelölt gomb megjeleníti az alvó állapot megerősítését; hagyja jóvá az OK gombbal. Az ismételt megnyomás felébreszti a készüléket. Az alvó állapot kikapcsolt állapotot ad meg a kimeneteknek; nem választja le a hálózati feszültséget. |
| Lakat | Bekapcsolja vagy kikapcsolja a billentyűzárat. Feloldás után a lakat melletti jelzőfény világít. A főképernyőn a zárolás körülbelül 30 s inaktivitás után visszakapcsol. |
| A — AUTO | Az OK gombbal történő jóváhagyás után kiválasztja az analóg bemenetről történő vezérlést. Az A jelzőfény a kiválasztott üzemmódot jelzi. |
| M — MANUAL | Az OK gombbal történő jóváhagyás után kiválasztja a kézi vezérlést. A főképernyőn a + és − gombok az 0–100% tartományban módosítják a beállítást. Az M jelzőfény a kiválasztott üzemmódot jelzi. |
| +, −, OK, ESC | Az OK megnyitja a menüt, belép a menüpontba és jóváhagyja az értéket. A + és − kiválasztja a menüpontot vagy módosítja az értéket. Az ESC visszatér az előző szintre vagy megszakítja a szerkesztést. |
| Riasztás és csoport 2 | A piros jelzőfény riasztást jelez. Az „2” ventilátorszimbólum melletti jelzőfény a GR 2 relé bekapcsolását jelzi. |
| Kijelző | AUTO esetén megjeleníti a szellőztetési alapjelet, a kiválasztott bemenet beolvasott értékét, az oszlopdiagramot és a riasztásokat. Aktív ENABLE esetén annak állapotát is megjeleníti. MANUAL esetén a fő érték a kézi beállítást jelenti; a védelmek módosíthatják a kimenetet. |

### A beállítások mentése

A menüparaméterek az OK gombbal történő jóváhagyás után nem felejtő memóriába mentődnek. Az MANUAL szint módosításai azonnal érvénybe lépnek, a mentés pedig rövid inaktivitás után történik. A tápellátás megszűnése után a mentett beállítások állnak vissza, beleértve az AUTO/MANUAL üzemmódot, a kézi szintet és az alvó állapotot. Ne kapcsolja ki a tápellátást közvetlenül a kézi beállítás módosítása után.

Hibás ellenőrzőösszeg vagy tartományon kívüli érték esetén a program visszaállítja a gyári értékeket. Ilyenkor minden beállítást újra ellenőrizni kell, különösen a ventilátorok kalibrálását, a vezérlőbemenetet és a vészüzemet.

## Az alapmenü funkciói

| MENÜ | TARTOMÁNY / GYÁRI ÉRTÉK | LEÍRÁS |
| --- | --- | --- |
| Vezérlés típusa | V bemenet | V, I, CAN vagy Wi-Fi kiválasztása. A vizsgált verzióhoz a V (2–10 V) vagy I (4–20 mA) bemenetet használja. A CAN és a Wi-Fi nem valósít meg vezérlést. |
| Szellőztetés 2. csoportja | 1–100% / 100% | A GR 2 érintkező bekapcsolási küszöbértéke. Az érintkező a küszöbértékkel azonos vagy annál magasabb szintnél bekapcsolt, a küszöbérték alatt kikapcsolt állapotban van. A program nem határoz meg külön hiszterézist. |
| Vészüzem | 0–100% / 30% | A kiválasztott analóg jel megszűnésekor megadott szint AUTO esetén. Az 0% érték a jel elvesztése esetén leállást jelent. |
| Tisztítási zárolás | 60 s | 60 másodpercre letiltja a gombok kezelését, és visszaszámlálást jelenít meg. A szellőztetés szabályozása tovább működik. A funkció a panel letörlésére szolgál, nem elektromos munkákra vagy a belső tér mosására. |
| Speciális | Almenü | Hozzáférés a tesztekhez, a nyelvhez, a ventilátor kalibrálásához, az ENABLE funkcióhoz, a lágyindításhoz, a riasztási hanghoz, a gyári beállításokhoz és a programinformációkhoz. |

## A speciális menü funkciói

| MENÜ / PARAMÉTER | TARTOMÁNY / GYÁRI ÉRTÉK | LEÍRÁS |
| --- | --- | --- |
| Tesztelés → Szellőztetés | 0–100% | A szabályozott kimenet ideiglenes kényszerítése. A módosítások a szerkesztés közben érvényesülnek. Az OK vagy ESC gombbal történő kilépés után visszaáll a normál vezérlés. |
| Tesztelés → Szellőztetés 2. fokozat | Nem / Igen | A GR 2 érintkező és jelzőfénye ideiglenes kényszerítése. |
| Tesztelés → Riasztás | Nem / Igen | A riasztásjelzés ideiglenes tesztje, a hangjelzést is beleértve, a „Riasztásjelzés” normál beállításától függetlenül. |
| Nyelv | Lengyel | Lengyel, angol és ukrán választható. |
| Ventilátor → Tiltott tartomány | −20–200 / 0 | Az 1% szint kalibrálása. Szerkesztés közben a tényleges kimenet 1% szintre kényszerül. A paraméter nem százalékban és nem másodpercben van megadva. |
| Ventilátor → EN aktiválása AUTO | Nem / Igen; Nem | Bekapcsolja az AUTO üzemmód függését az ENABLE bemenettől. |
| Ventilátor → EN aktiválása MANUAL | Nem / Igen; Nem | Bekapcsolja az MANUAL üzemmód függését az ENABLE bemenettől. |
| Lágyindítás → Felfutási idő | 0–50 / 5 | A szint növekedésének sebessége indításkor az 100% szintig. A nagyobb érték lassabb változást jelent. Az 0 érték kihagyja a felfutási szakaszt. |
| Lágyindítás → 100% idő | 0–250 / 100 | Az 100% szint fenntartása indítás közben. Az 0 érték kihagyja a szinten tartási szakaszt. A felfutás és a szinten tartás együttes 0 értékre állítása kihagyja az 100% szintig történő átfúvatást. |
| Lágyindítás → Kifutási idő | 0–50 / 5 | A kívánt szint elérésének sebessége, annak módosításakor is. Az 0 érték fokozatos átmenet nélküli változást jelent. |
| Riasztásjelzés | Nem / Igen; Nem | Bekapcsolja a riasztást jelző hangot. A Nem beállítás nem szünteti meg a képernyőn megjelenő üzenetet és a jelzőfény jelzését. |
| Gyári beállítások | Nem / Igen | Az Igen kiválasztása után visszaállítja és menti az alapértelmezett értékeket, beleértve az 0 kalibrálást, a V bemenetet, az AUTO értéket, az 30% vészüzemi szintet, az 2 GR küszöbértéket, amely 100%, valamint a kikapcsolt ENABLE funkciót. A művelet után konfigurálja újra és ellenőrizze a készüléket. |
| Program | verzió 2.1 + fordítás dátuma | Megjeleníti a program verzióját és fordításának dátumát. Ez a leírás a rendelkezésre bocsátott SC_PX16_v02 források alapján készült. |

A lágyindítás paraméterei a program számlálóinak dimenzió nélküli beállításai, nem másodpercben megadott idők. 50 Hz esetén egy lépés megközelítőleg (beállítás + 1) × 20 ms időnek felel meg: felfutás és kifutás esetén ez 1 százalékpontnyi változás ideje, az „100% idő” esetén pedig a szinten tartás ideje. Az 0 érték jelentését a táblázat ismerteti. A tényleges idők az algoritmus fázisától függenek.

## Hiba- és figyelmeztető üzenetek

| ÜZENET | JELENTÉS ÉS TEENDŐ |
| --- | --- |
| Bemenet | A kiválasztott jel beolvasott értéke túl alacsony AUTO esetén. A készülék vészüzemet ad meg. Ellenőrizze a jelforrást, a vezetékeket, a közös testpontot és az V/I kiválasztását. |
| Túlmelegedés | A hűtőborda beolvasott értéke &gt;87°C; törlés &lt;80°C esetén. A szellőztetési alapjel 0% vagy 100%, a hővédelem leírásának megfelelően. Ellenőrizze a hűtést és a terhelést. |
| Tápellátás | Zavar a teljesítményáramkör hálózattal történő szinkronizálásában. Ellenőrizze a tápellátást és a villamos hálózatot. A tápellátás teljes megszűnésekor a kijelző nem működik. |
| Memória CRC | A mentett beállítások ellenőrzőösszeg- vagy tartományhibája. A program visszaállítja az alapértelmezett értékeket. Ellenőrizze a konfigurációt, és ismételje meg a kalibrálást; ismételt hiba esetén forduljon a szervizhez. |

## Megjegyzések és figyelmeztetések

:::danger Válassza le a tápellátást

A készülék telepítése során az elektromos tápellátást feltétlenül le kell választani, mert egyes alkatrészeken az életre és az egészségre veszélyes feszültség van jelen. Javasolt a telepítést szakképzett személyre bízni.

:::

Telepítés és használat előtt olvassa el az útmutatót. A javításokat és a készüléken belüli munkákat megfelelő jogosultsággal rendelkező személyzetre bízza. Az alvó állapot, a billentyűzár, az ENABLE és az 0% beállítás nem jelenti a tápellátás leválasztását, és nem biztosít biztonságos körülményeket az elektromos munkákhoz.

A szellőztetés és a vészüzem beállításait az állatok és a rendszer igényeihez igazítsa. Rendszeresen ellenőrizze minden ventilátor tényleges működését. Az SC-PE16 jelzése nem helyettesíti a létesítmény körülményeinek és a tápellátás megszűnésének független felügyeletét. A bemutatott kapocslécen nincs külön ALARM érintkező a központ számára.

:::note A készülék ártalmatlanítása

A terméket használatának befejezése után nem szabad a válogatatlan települési hulladékkal együtt kidobni, hanem a hatályos előírásoknak megfelelően kell ártalmatlanítani (az Európai Unió 2012/19/EU WEEE irányelvei).

:::

A termék a RoHS követelményeinek megfelelően készült (az Európai Unió 2011/65/EU irányelve).

## A vezérlő műszaki adatai

| PARAMÉTER | ÉRTÉK |
| --- | --- |
| Tápellátás / saját fogyasztás | 230 V AC, 50 Hz / &lt;10 W |
| Az U kimenet maximális összesített árama | 16 A |
| A GR érintkező maximális árama 2 | 6 A; C–NO érintkező, galvanikusan leválasztott |
| V bemenet / I bemenet | 2–10 V / 4–20 mA, menüben választható |
| A jel megszűnésének küszöbértéke (a program által beolvasott érték) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Potenciálmentes E–test érintkező; külön aktiválás az AUTO/MANUAL | esetében
| Hővédelem (a hűtőborda beolvasott értéke) | Riasztás &gt;87°C; visszaállás &lt;80°C |
| Környezeti hőmérséklet / készülékház | −10°C és +40°C között / IP65 |
| Méretek / túlfeszültség-állóság | 34 × 29 × 12 cm / 210 J |
| Menünyelvek | Lengyel, angol, ukrán |

A készlet tartalma a mellékelt dokumentáció szerint: 4 dübel, 2 tömszelence PG13,5, 1 tömszelence PG9 és 1 zsanér.

## Jótállási feltételek

A jótállási feltételek tartalma a gyártó rendelkezésre bocsátott dokumentumának megfelelően maradt meg.

1. A lengyelországi székhelyű ELETOR gyártó, címe: Pod Sosno 28, 87-305 Zbiczno (a továbbiakban: jótálló), minőségi jótállást nyújt a Vásárlónak arra a termékre, amelyre ezt a jótállási jegyet kiállították, feltéve, hogy azt rendeltetésszerűen és a Vásárlónak a termékkel együtt átadott használati útmutatóban meghatározott szabályok szerint használják.
2. A jótállási idő az értékesítés napjától számított 24 hónap. Az ezen időszak alatt feltárt meghibásodások vagy termékhibák elhárítása díjmentesen történik. A jótállási idő lejárta vagy a jótállási jogosultság elvesztése esetén a meghibásodások vagy hibák elhárítása díjköteles.
3. A jótállás nem terjed ki az alábbiakra:

   - a termék nem megfelelő kezeléséből eredő bármilyen hiba (ideértve a használati útmutatóban nem ismertetett műveletek végrehajtását stb.);

   - a jótállótól eltérő személy által végzett javítás, módosítás stb. következtében keletkezett bármilyen hiba;

   - a termék szállításából vagy leejtéséből eredő bármilyen hiba vagy sérülés, ha ezek az események a termék megvásárlása után történtek, valamint a felhasználó nem megfelelő kezeléséből eredő mechanikai sérülések;

   - tűz, földrengés, árvíz, villámcsapás vagy más természeti katasztrófa, környezetszennyezés, külső ionizáló sugárzás vagy mágneses tér hatása, továbbá rendszertelen áramellátás vagy az előírtaktól eltérő paraméterű áramellátás következtében keletkezett bármilyen hiba vagy sérülés;

   - nem megfelelő tárolásból (pl. a terméknek a műszaki adatokban megadott hőmérséklet- vagy páratartalom-tartományon kívüli, vegyszerek közelében történő tárolásából), nem megfelelő karbantartásból vagy tisztításból stb. eredő bármilyen hiba;

   - a tápellátást biztosító elemek lemerüléséből stb. eredő bármilyen hiba;

   - a termék készülékházába jutott homok, sár, por, víz és más folyadékok stb. által okozott bármilyen hiba;

   - a termék tulajdonságainak vagy rendeltetésének megfelelő természetes, részleges vagy teljes elhasználódásból eredő sérülések;

   - a használati útmutatóban megjelölt műveletek, amelyeket a felhasználó saját maga köteles elvégezni.

4. A Vásárló elveszíti jótállási jogosultságát az alábbiak következtében:

   - a termék bármilyen javítása vagy módosítása a jótállótól eltérő személy által;

   - bármely plomba megbontásának, sérülésének vagy leszakításának megállapítása;

   - a sorozatszámok vagy a termék azonosítására szolgáló egyéb jelölések sérülésének, megváltoztatásának, eltakarásának vagy eltávolításának megállapítása.

5. A javítás határideje a hiba bejelentésétől és a teljes terméknek a jótálló szervizpontjára történő eljuttatásától számított legfeljebb 21 munkanap. Különösen indokolt esetekben, amikor alkatrészek vagy részegységek külföldről történő beszerzése szükséges, illetve különösen összetett, nehezen javítható vagy diagnosztizálható meghibásodás esetén a javítás határideje a jótállási kötelezettségek teljesítéséhez szükséges idővel meghosszabbodhat.
6. A Vásárló jótállási jogai kizárólag az érvényes, a vásárlás napján szabályosan kitöltött jótállási jegy és a vásárlást igazoló bizonylat (számla, nyugta stb.) bemutatásával érvényesíthetők. A jótállási jegy bejegyzéseinek önkényes módosítása (ideértve az áthúzást, törlést, hozzáírást stb.) a jótállási jogosultság elvesztését eredményezi. A termék megnevezése, modellje, sorozatszáma, a vásárlás dátuma és helye, valamint az Eladó olvasható bélyegzője és aláírása nélküli jótállási jegy érvénytelen, és nem képezi érvényes reklamáció alapját.
7. A Vásárló köteles a terméket saját költségén, az adott berendezésnek megfelelő, biztonságos és szabályos szállítást és tárolást biztosító csomagolásban eljuttatni, vagy a jótálló kiszállási költségét fedezni. Ha megállapítást nyer, hogy a javításra átadott termék műszakilag működőképes és hibamentes, vagy a megállapított hibára nem terjed ki a jótállás, a szolgáltatások és a szállítás költségei a Vásárlót terhelik.
8. A Vásárló köteles a megjavított terméket a jótálló javításról szóló értesítésének napjától számított 90 napon belül átvenni. Ha a vásárló e határidőn belül nem veszi át a terméket, viseli a termék véletlen elvesztésének vagy sérülésének kockázatát.
9. A jótállási idő meghosszabbodik a javítás időtartamával, a termék átadásának napjától a javítás utáni átvétel megállapított határidejéig számítva. A jótálló köteles a javítás időtartamát és a termék elhárított hibáinak körét igazoló dokumentumot kiadni.

10. A Vásárló igényeit a termék Eladóján keresztül vagy közvetlenül a jótálló címére jelenti be: ELETOR, Pod Sosno 28, 87-305 Zbiczno, Lengyelország.

11. A jótálló nem vállal felelősséget:

    - a hiba jelentkezéséből és elhárításának időtartamából eredő elmaradt bevételért;

    - a hiba jelentkezéséből eredő veszteségekért, valamint a készülék nem megfelelő telepítéséből, használatából vagy funkcióinak helytelen programozásából eredő bármilyen kárért.
