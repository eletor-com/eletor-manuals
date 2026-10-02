---
sidebar_position: 2
title: Útmutató SC-S
description: Klímavezérlő állattartó helyiségekhez, legfeljebb 5A megengedett kimeneti
  árammal
keywords:
- eletor sc-s
- szellőztetésvezérlő
- klímavezérlő
- sertésól-szellőztetésvezérlő
- mikroklíma-vezérlő
- vezérlő sertésólakhoz
- sertésól szellőztetése
- vezérlő nevelőhelyiségekhez
---


# Vezérlő SC-S

Az SPEED CONTROL családba tartozó mikroprocesszoros klímavezérlő. Megbízható, egyszerűen telepíthető és üzemeltethető vezérlő, lengyel, angol, orosz és német nyelvű szoftverrel. A vezérlő programja lehetővé teszi a következő paraméterek intuitív beállítását: hőmérsékletek, időszakos szellőztetés, kiegészítő fűtés, min./max. szellőztetési szintek és riasztások.

**Paraméterek és jellemzők:**  
- Az I. csoport szellőztetése:
  - a fokozatmentes szabályozás kimenetének max. árama 6A,
  - az áramkör hővédelme,
  - a szellőztetés lágyindítása,
  - a minimális fordulatszám kalibrálása
- Az II csoport szellőztetése, leválasztott érintkező legfeljebb 3A értékig (1 opcióként)
- Kiegészítő fűtés, leválasztott érintkező legfeljebb 3A értékig (1 opcióként)
- NO és NC riasztási kimenetek:
  - a tápellátás megszűnésének jelzése,
  - a min. vagy max. hőmérsékleti küszöb átlépésének jelzése
- 1 analóg bemenet a hőmérséklet méréséhez
- 2 0-10V kimenet
- Az áramkör teljesítményfelvétele < 3W
- Hermetikusan zárt ház IP56
- Tápfeszültség 230VAC 50Hz

## A vezérlő telepítése  
:::danger 
A készülék telepítése során az elektromos tápellátást feltétlenül meg kell szakítani, mivel egyes részegységeken az életre és az egészségre veszélyes feszültség van jelen.  
Javasolt a telepítést szakképzett személyre bízni.
:::

### A felszerelési hely kiválasztása  

A felszerelési helyet észszerűen kell kiválasztani, figyelembe véve, hogy a készülék az arra jogosult személyek számára könnyen hozzáférhető, az állatok és gyermekek számára viszont hozzáférhetetlen legyen. Figyelembe kell venni az éghajlati körülményeket is, azaz a készüléknek -10°C és 40°C közötti hőmérséklet-tartományban, közvetlen napfénytől védett helyen kell működnie. A készülék körül biztosítani kell a levegő szabad áramlását. A készülékhez hőmérséklet-érzékelő tartozik. A hőmérséklet-érzékelő felszerelésére néhány szabály vonatkozik:  
- az érzékelőt nem szabad légáramlás nélküli vagy közvetlen napsugárzásnak kitett helyre felszerelni
- az érzékelőt nem szabad az épület teherhordó (külső) falára felszerelni,
- kerülni kell a hőt kibocsátó készülékek, például fűtőtestek és lámpák közelségét,
- az érzékelőt nem szabad közvetlenül ajtók és szellőzőnyílások mellé elhelyezni,
- az érzékelőt nem szabad állatok számára hozzáférhető helyre elhelyezni,
- javasolt az érzékelő csatlakozóvezetékét a tápvezetékektől távol elvezetni.

### Felszerelés  

A készülék nehéz éghajlati körülmények között is működhet. A megfelelően felszerelt vezérlő és hőmérséklet-érzékelő ellenáll a környezeti hatásoknak.
A felszerelés során a következőkre kell ügyelni:  
- az összecsavarozás előtt ellenőrizni kell a fedél tömítését,
- a fedelet az összes csavarral meg kell húzni,
- a vezérlő csatlakoztatásához használt vezetékeknek kör keresztmetszetűnek kell lenniük,
- a vezeték csatlakoztatása után a tömszelencéket úgy kell meghúzni, hogy a vezeték tömített és rögzített legyen; szilikon használata javasolt,
- a nem használt kivezetéseket (tömszelencéket) le kell zárni,
- a vezérlőt (a ház alsó részét) sík falra rögzítjük 4 dübellel.

## Elektromos csatlakoztatás  

:::danger 
Az áramkör csatlakoztatása előtt győződjön meg arról, hogy a tápellátás ki van kapcsolva!
:::

A vezérlő csatlakoztatása előtt ki kell csavarni a csavarokat és le kell venni a fedelet. A vezetékeket átvezetjük a gumi tömszelencéken, majd megkezdhetjük a csatlakoztatásukat. A vezérlő kapcsait az alábbi ábra mutatja.

![Csatlakoztatás](./img/Sc-s2.png)

**Az AC 230V** csatlakozót a tápellátáshoz (elosztószekrényhez) csatlakoztatjuk. 1P-B6 kismegszakító és T1 T2 típusú túlfeszültség-korlátozók alkalmazása szükséges. Több készülék csatlakoztatásakor bevált gyakorlat a vezérlők különböző „fázisokra” (L1, L2, L3) történő csoportosítása a tápvezeték egyenletes terhelése érdekében.  
**A FAN csatlakozót** közvetlenül a ventilátorhoz kell csatlakoztatni; több ventilátor vezérlése esetén az összesített terhelés nem haladhatja meg az 6A értéket, és minden ventilátort külön védelemmel kell ellátni. A PE és N vezetékeket nem szabad a tápellátásból (elosztószekrényből) kivezetni, azokat feltétlenül a vezérlő kivezetéseihez kell csatlakoztatni.  
**A FUNCTION csatlakozó** leválasztott relékimenet, az érintkező maximális árama 6A (a terhelés közvetlen vezérlése esetén külső 1P-B6 kismegszakító szükséges),
a következőkre használható:  
- **Kiegészítő fűtés** – az érintkező zár, ha a mért hőmérséklet a beállított érték alá csökken.  
- **Az 2 csoport vagy a permetezőrendszerek szellőztetése** – az érintkező zár, ha a mért hőmérséklet meghaladja a beállított hőmérséklet és a szellőztetési sáv összegét.  az érintkező zár, ha a mért hőmérséklet meghaladja a beállított hőmérséklet és a szellőztetési sáv összegét.  

Az alábbi ábra az 2 csoport ventilátorának vagy a léghevítőnek a csatlakoztatási módját mutatja.  

![Második csoport](./img/2grupa.png)

**Az ALARM csatlakozó** leválasztott NC, C és NO kimenetekből áll, amelyek a riasztóközponthoz való csatlakoztatásra szolgálnak. A riasztás a következő esetekben aktiválódik:  
- a hőmérséklet túl alacsony vagy túl magas,
- a vezérlő vagy a hőmérséklet-érzékelő meghibásodott,
- megszűnt a vezérlő tápfeszültsége;
- a vezérlő rendellenesen működik (pl. a vezérlő túlmelegedett)  

![Riasztás](./img/alarmsc-s.png)  

**Az V1 0-10V** csatlakozó teljesítménybővítő modulok vagy beépített fordulatszám-szabályozóval rendelkező ventilátorok csatlakoztatására szolgál. Ezen a kapcson a feszültség arányos a szellőztetési szinttel.  
**Az V2 0-10V** csatlakozó a levegőbevezető csappantyúkat nyitó állítómű csatlakoztatására szolgál.  
**A SENSOR csatlakozót** az 1 TS3 vagy TS5 hőmérséklet-érzékelőhöz csatlakoztatjuk, a polaritásnak nincs jelentősége.  Bevált gyakorlat a mérővezetékek tápvezetékektől távol történő elvezetése.  
**Az RS-485** csatlakozó szellőztetőrendszerek kialakítására és PC-vel való kommunikációra használható.  

## Működési elv  

A vezérlő fő feladata az állattartó helyiség hőmérsékletének az állattartó által meghatározott szinten tartása. Figyelembe kell venni, hogy a vezérlő csupán eszköz, amely segít az optimális klimatikus körülmények biztosításában az állattartó helyiségben. Ebben a folyamatban azonban az állattartó szerepe az elsődleges, akinek a készülék beállításait a változó kültéri éghajlati körülményekhez, és mindenekelőtt az állattartó épületben lévő állatok igényeihez kell igazítania, továbbá riasztóközpont segítségével figyelemmel kell kísérnie a készülék üzemállapotát.  

### A vezérlő első üzembe helyezése  

:::danger
A vezérlő első üzembe helyezésekor feltétlenül be kell állítani a motor tiltott működési sávját.
:::

A vezérlő egyfázisú aszinkronmotorral működő ventilátorokkal használható, amelyek maximális összesített áramfelvétele 5A. A felhasználónak a kiválasztott ventilátorok csatlakoztatása után azokat a vezérlővel való együttműködéshez kell beállítania. Más szóval be kell állítani a ventilátor minimális működési szintjét (fordulatszámát). Ez a funkció a **„Tiltott sáv”** nevet viseli, és a felhasználó egyszer állítja be a **„Speciális beállítások”** menüben. A művelet megfelelő elvégzéséhez javasolt egy második személy segítsége, aki folyamatosan figyelheti a ventilátor viselkedését, miközben a másik személy a **„Tiltott sáv”** értékét állítja be. A tiltott sáv beállításának elmulasztása a készülék rendellenes működéséhez vezethet. A **„Tiltott sáv”** értéke akkor tekinthető megfelelőnek, amikor a ventilátor által létrehozott nyomás enyhén megemeli a szellőzőkürtő csappantyúit. A **„Tiltott sáv”** beállítását meg kell ismételni, ha a vezérlőhöz csatlakoztatott ventilátort kicserélik.  

### Időszakos szellőztetés  

Az időszakos szellőztetés a vezérlő által végrehajtott funkció, amely akkor aktiválódik, amikor a helyiség hőmérséklete a beállított hőmérséklet alá csökken. Ez a funkció ciklikusan friss levegőt biztosít az állatoknak. Az időszakos szellőztetést 3 paraméter határozza meg:
- **„Működési idő”** - meghatározza, hány másodpercre kapcsoljon be a ventilátor,
- **„Szünetidő”** - meghatározza a ventilátor állásidejét másodpercben,
- **„Időszakos szellőztetési szint”** - meghatározza a szellőztetés teljesítményét a „Működési idő” alatt.  

A példaként megadott **60s/120s** beállítás azt jelenti, hogy a ventilátor 60s időtartamra kapcsol be, az egymást követő bekapcsolások között 120s szünettel. 

A fent felsorolt összes paramétert a felhasználó állítja be. Az időszakos szellőztetés paramétereinek beállításakor néhány szabályt figyelembe kell venni:
- az időszakos szellőztetés kizárólag akkor kapcsol be, ha a sertésól hőmérséklete a beállított hőmérséklet alá csökken,
- az időszakos szellőztetés alapvető feladata az állatok ciklikus frisslevegő-ellátásának biztosítása, nem pedig a helyiség beállított hőmérsékletének fenntartása,
- javasolt a helyiségeket rövid ideig, de gyakran szellőztetni,
- kerülni kell a hosszú szellőztetési időszakokat, mert azok túl nagy hőmérséklet-ingadozásokhoz vezethetnek,
- a beállított paramétereket feltétlenül az állatok viselkedéséhez, valamint a helyiségen belüli és kívüli körülményekhez kell igazítani,
- az időszakos szellőztetési funkció kikapcsolható; ebben az esetben mind százalékos, mind időalapú üzemmódban nulla értéket kell beállítani a szellőztetési időnek megfelelő helyen, pl.: 0/120s  

### Fokozatmentes szellőztetés  

A vezérlő a szellőztetést fokozatmentesen szabályozza a „Minimális fordulatszám” és a **„Maximális fordulatszám”** között, a **„Beállított hőmérséklet”** és a **„Beállított hőmérséklet”** és a **„Szellőztetési sáv”** összege közötti tartományban. E tartomány felett bekapcsol az 2 szellőztetési csoport.  

![szellőztetés](./img/wentylacjia.png)  

E tartomány felett bekapcsol az 2 szellőztetési csoport. Ha a helyiség hőmérséklete a **„Beállított hőmérséklet”** alá csökken, a vezérlő időszakosan szellőzteti a helyiséget, további csökkenés esetén pedig bekapcsol a kiegészítő fűtés. Mindez a felhasználó által megadott beállításoktól függ. A vezérlő programja riasztóközponttal való együttműködést is lehetővé tesz, amely akkor aktiválható, ha a sertésól hőmérséklete eltér a beállított paraméterektől.  

## A vezérlő programozása  

A vezérlő alapértelmezett beállításokat tartalmaz, amelyek két esetben kerülnek a nem felejtő memóriába:  
1. A készülék első üzembe helyezésekor,  
2. Adatmemória-hiba esetén.  
A tápellátás hiánya vagy megszűnése esetén a vezérlő nem veszíti el a korábban megadott és elmentett felhasználói beállításokat.  

### A menü használata  

A vezérlő számos funkcióval rendelkezik, amelyek lehetővé teszik az adott alkalmazáshoz való igazítását. Ezek a funkciók menübe vannak rendezve, amely az egyik **(„ Jobbra nyíl”, „Balra nyíl”)** gomb megnyomásával érhető el. A paraméterek módosítása a **„+” és „-”** gombokkal történik, a szerkesztett paraméter az utolsó gombnyomástól számított **30s** elteltével automatikusan mentésre kerül a nem felejtő memóriába.  

### Az alapmenü funkciói  

| MENÜ                       | Leírás | 
|:---:                       |:---|
|Hőmérséklet  <br />20,8°C W16% A  |**„Információs üzemmód”** - normál működés. A kijelzőn az aktuális hőmérséklet, valamint működő ventilátor esetén a szellőztetési szint értéke látható. A további jelzések jelentése: A-bekapcsolt riasztás, D  - bekapcsolt fűtés, W - kiegészítő szellőztetés| 
|Beállított hőm.  <br />20,0°C        |**„Beállított hőmérséklet”** – a fokozatmentes szellőztetési folyamat kezdetét meghatározó hőmérsékleti érték.   | 
|Időszakos szellőztetés  <br />20s / 200s  |**„Időszakos szellőztetés”** – két időérték állítható be: 1 „Működési idő”, 2 „Szünetidő” a szellőztetés egymást követő ciklikus bekapcsolásai között.| 
|Idősz. szell. szint  <br />20%        |**„Időszakos szellőztetési szint”** - a szellőztetési szint az időszakos szellőztetés működése alatt   | 
|Minimumriasztás  <br />12,0°C       |**„Minimumriasztás”** - meghatározza azt az abszolút minimális hőmérsékletet, amelynél a riasztás bekapcsol. 
|Maximumriasztás  <br />28,0°C       |**"Maximumriasztás"** - meghatározza azt az abszolút maximális hőmérsékletet, amelynél a riasztás bekapcsol.  | 
|Kiegészítő fűtés  <br />12,0°C         |A konfigurációtól függően a következő funkciók valósulnak meg: **„Kiegészítő fűtés”** - az érintkező zár, ha a hőmérséklet a kijelzett érték alá csökken. | 
|2 fokozatú szellőztetés  <br />25,0  |**„2 fokozatú szellőztetés”** - az érintkező zár, ha a mért hőmérséklet meghaladja a beállított hőmérséklet és a szellőztetési sáv összegét. | 
|Szellőztetési sáv  <br />5,0°C     |**„Szellőztetési sáv”** - meghatározza a vezérlő reakciójának sebességét (a szellőztetési szint változását az 1 minimumtól az 1 maximumig) az emelkedő hőmérsékletre. | 
|Minimális fordulatszám  <br />1%        |**„Minimális fordulatszám”** – olyan állapot, amelyben a készülék határozatlan ideig marad, és a kimeneten a beállított értékű feszültséget adja. A készülék motorhoz és csappantyúmechanizmushoz történő kalibrálására szolgál.   | 
|Maximális fordulatszám  <br />100%      |**„Maximális fordulatszám”** – olyan állapot, amelyben a készülék határozatlan ideig marad, és a kimeneten a beállított értékű feszültséget adja. A szellőztetésre fordított teljesítmény korlátozására szolgál| 

### Speciális menü  

A speciális menü elsősorban a telepítők számára készült, és lehetővé teszi a vezérlő rendszerhez és ventilátorhoz való igazítását. A speciális beállítások a két menügomb egyidejű megnyomásával és körülbelül 10s ideig történő nyomva tartásával érhetők el.  

| MENÜ                                 | Leírás| 
|:---:                                 |:--- |
|Nincsenek beállítások  <br />speciális   |Ez az üzenet azt jelzi, hogy a vezérlő nincs a szellőztetéshez kalibrálva, és működése rendellenes lehet. Be kell lépni a speciális menübe, és el kell végezni a „Tiltott sáv” beállítását.|
|Beállítások <br />Speciális         |A speciális beállításokba való belépés jelzése. | 
|Szoftververzió:  <br />1907       |Tájékoztatás a szoftver verziójáról.| 
|Tiltott sáv  <br />1000 us       |A közvetlenül a vezérlőhöz csatlakoztatott ventilátorok minimális fordulatszámának kalibrálása; ez a paraméter a „1%” szellőztetési szintnek felel meg|  
|Érintkezők funkciója  <br />Kiegészítő fűtés     |Az érintkezők funkciójának kiválasztása:  <br />• Kiegészítő fűtés (alapértelmezett)<br />• 2 szellőztetési csoport | 
|Időszakos szellőztetés  <br />Időalapú         |Az időszakos szellőztetés típusának kiválasztása: <br />• Időalapú (alapértelmezett) <br />• Százalékos| 
|Tartomány V1  <br />2,0 és 10,0 között       |Az V1 kimenet feszültségváltozási tartományának beállítása 0÷10V. A beállítások a minimális és maximális feszültségértékre vonatkoznak. A szabályozás a vezérlő teljesítménybővítőhöz vagy frekvenciaváltóhoz történő igazítására szolgál.| 
|Invertálás V1  <br />Nem                |Aktiválása megfordítja az V1 kimenet karakterisztikáját. A feszültség a szellőztetési szint növekedésével csökken a min.-max. által meghatározott tartományban. Az V1 kimeneten a jel 10-0V típusú lesz.| 
|Lekapcsolás V1  <br />Nem                |Aktiválásakor az  V1 0-10V kimeneten 0V szint jelenik meg a beállított minimális érték helyett, ha a szellőztetési szint 0%.| 
|Tartomány V2  <br />2,0 és 10,0 között       |Az V2 kimenet feszültségváltozási tartományának beállítása 0÷10V. A beállítások a minimális és maximális feszültségértékre vonatkoznak. A szabályozás a csappantyúrendszer kalibrálására szolgál.|
|Invertálás V2  <br />Nem      	       |Aktiválása megfordítja az V2 kimenet karakterisztikáját. A feszültség a szellőztetési szint növekedésével csökken a min.-max. által meghatározott tartományban. Az V2 kimeneten a jel 10-0V típusú lesz.|
|Hőm. kalibrálása  <br />21,0°C -> 22,0°C|A hőmérséklet-érzékelő kalibrálása lehetővé teszi a leolvasott érték átskálázását.|
|Lágyindítás  <br />50%      	           |A szellőztetési szint meghatározása a ventilátor minden indításakor; a ventilátor a megadott értékre gyorsul fel, majd áttér a beállított szintre.| 
|Nyelv  <br />Lengyel    	           |A menü nyelvének kiválasztása: lengyel, angol, német, orosz|
|Kilépés                               |Kilépés a speciális menüből a „+” gombbal; a megadott módosítások mentésre kerülnek a nem felejtő memóriába.|

### Hibaüzenetek és figyelmeztetések  

A hibaüzenetek a vezérlő működési rendellenességeiről tájékoztatják a felhasználót. Az alábbiakban a lehetséges hibaüzenetek találhatók.  

|HIBA                                    | LEÍRÁS |
|:---:                                   |:--- |
|Riasztás  <br />Túlterhelési 	         |Túlterhelési riasztás, amely 75°C esetén aktiválódik. A készülék a lehűlésig felfüggeszti a működését.|
|ÉRZÉKELŐ SZAKADT!  <br />Ellenőrizze az érzékelőt|Szakadt érzékelő, az érzékelő vagy a csatlakozóvezeték meghibásodását jelzi.|
|ÉRZÉKELŐ ZÁRLATOS!  <br />Ellenőrizze az érzékelőt  |Zárlatos érzékelő, az érzékelő vagy a csatlakozóvezeték meghibásodását jelzi.|
|Kimaradás  <br />Tápellátás                  |Tápellátás-kimaradás, túl alacsony tápfeszültség, hibás frekvencia vagy erősen torzult tápfeszültség.| 

## Megjegyzések és figyelmeztetések  

:::danger 
A készülék telepítése során az elektromos tápellátást feltétlenül meg kell szakítani, mivel egyes részegységeken az életre és az egészségre veszélyes feszültség van jelen. Javasolt a telepítést szakképzett személyre bízni.
:::

- A készülék üzemeltetésével kapcsolatos problémák elkerülése érdekében a telepítés és a használat megkezdése előtt meg kell ismerni az útmutatót.  
- Tilos a készülék szerkezetébe beavatkozni vagy önálló javításokat végezni. Ez különösen az alkatrészek és részegységek módosítására vonatkozik.  
- A karbantartási és szervizmunkákat arra jogosult személyzetnek (telepítőnek vagy a gyártó szervizének) kell elvégeznie. Kényszerszellőztetésű állattartó épületekben riasztórendszer alkalmazása szükséges. A készülék gyártója nem vállal felelősséget a helytelen telepítés, a funkciók helytelen programozása, véletlenszerű események következményei és külső tényezők által okozott károkért.  
- A szellőztetésvezérlő paramétereit az állattartó helyiségben fennálló körülményeknek megfelelően kell beállítani. Ezek a beállítások egyediek, és az állattartó döntésétől függenek. A készülék gyártója fenntartja a készülék szerkezetének és szoftverének módosítására vonatkozó jogot.  


:::caution
![alternatív szöveg](./img/trash.svg) A terméket használatának befejezése után nem szabad a válogatatlan települési hulladékkal együtt kidobni, hanem a hatályos előírásoknak megfelelően kell ártalmatlanítani (az Európai Unió WEEE-irányelvei 2012/19/EU). <br />A termék a RoHS követelményeinek megfelelően készült (az Európai Unió 2011/65/EU irányelve).
:::

<!-- \newpage -->
## A vezérlő műszaki adatai  

|Paraméter                        |	LEÍRÁS      |
|:-----------                    |:---------- |
|Tápfeszültség|	230VAC 50Hz|
|A FAN fokozatmentes szabályozási kimenet maximális árama|	6A|
|A kimeneti feszültség szabályozási tartománya|	70V ÷ (Uz-5)V|
|Az ALARM kimenet (érintkező) maximális árama|	3A|
|A FUNCTION kimenet (érintkező) maximális árama|	3A|
|Üzemi hőmérséklet-tartomány|	-20 +40oC|
|Hőmérséklet-mérési tartomány|	0 +50°C|
|A hőmérsékletmérés felbontása|	0,1°C|
|A hőmérséklet-érzékelő hibáinak felismerése|	IGEN|
|Az analóg érzékelők maximális száma|	1|
|Hőmérséklet-mérési pontosság – analóg bemenet|	1°C|
|A mérés függése a vezetékek ellenállásától – analóg bemenet|	15,8Ω/°C|
|Túlfeszültség-állóság (max E)|	210J|
|Túlterhelés-védelem|	75°C|
|A készülék méretei|	20x15x8 [cm]|
|A ház védettségi fokozata|	IP56|
  


:::info
Az SPEED CONTROL SERVOMOTOR vezérlő készlete a következőket tartalmazza:
- 1 hőmérséklet-érzékelő + tartozékok,
- 4 dübel,
- 1 10A biztosíték.
:::

