---
sidebar_position: 4
title: Útmutató IC-AC
description: IC-AC vezérlő állattartó helyiségek légbeejtőihez, legfeljebb 2A megengedett
  kimeneti árammal
keywords:
- eletor IC-AC
- légbeejtő-vezérlő
- klímavezérlő
- sertésistálló szellőzésvezérlője
- mikroklíma-vezérlő
- vezérlő sertésistállókhoz
- sertésistálló szellőztetése
- vezérlő nevelőépületekhez
---


# Vezérlő IC-AC

  A légbeejtők mozgatószerkezeteinek és emelőinek vezérlője, amelyek jobbra/balra forgó AC motorokkal és az aktuális helyzet leolvasására szolgáló potenciométerrel rendelkeznek. A vezérlő az 0-10V jelet a légbeejtők nyitási szintjére alakítja át, emellett kézi vezérlést is lehetővé tesz.

## Paraméterek és jellemzők:  
- Üzemmódok:
  - MANUAL – kézi vezérlés a „+”, „-” gombokkal;
  - AUTO – automatikus működés a kalibrált tartományban, az 0-10V jellel arányosan;
  - VÉSZÜZEM – a vezérlőjel megszűnése esetén a légbeejtők a százalékban megadott szintre nyílnak; 
- Relékimenet (jobbra/balra) 2A;
- Vezérlőjel: 0-10V;
- A vezérlőjel invertálásának lehetősége;
- Helyzetmérés 1-100kΩ potenciométerrel;
- Programozható hiszterézis és leolvasási átlagolási idő; 
- Hermetikus burkolat IP56;
- Tápfeszültség 230VAC 50Hz;
- Menünyelvek: 
  - lengyel
  - angol
  - ukrán
  - orosz

# A vezérlő telepítése  
:::danger 
A készülék telepítése során feltétlenül le kell választani az elektromos tápellátást, mivel egyes részegységeken az életre és az egészségre veszélyes feszültség van jelen. Javasolt a telepítést szakképzett személyre bízni.
:::

## A felszerelési hely kiválasztása  

  A felszerelési helyet észszerűen kell megválasztani, figyelembe véve, hogy a készülék az arra jogosult személyek számára könnyen hozzáférhető, állatok és gyermekek számára pedig hozzáférhetetlen legyen. Figyelembe kell venni a környezeti feltételeket is, azaz a készüléknek -10°C és 40 °C közötti hőmérséklet-tartományban, napsugárzástól védett helyen kell működnie.

# Felszerelés

A készülék agresszív környezeti feltételek között is működhet. A megfelelően felszerelt készülék ellenáll a környezet káros hatásainak. 

  A felszerelés során a következőkre kell figyelni: 
- a fedél összes csavarját meg kell húzni,
- a készülék csatlakoztatásához használt kábeleknek kör keresztmetszetűnek kell lenniük,
- a kábel csatlakoztatása után a tömszelencéket meg kell húzni úgy, hogy a kábel tömítve és rögzítve legyen, szilikon használata javasolt,
- a nem használt kivezetéseket (tömszelencéket) le kell zárni,
- a burkolat alsó részét sík falra rögzítjük 4 dübellel.


# Elektromos bekötés  

:::danger 
A rendszer csatlakoztatása előtt meg kell győződni arról, hogy a tápellátás ki van kapcsolva!
:::

  A készülék csavarjainak kicsavarása után az előlapot le kell venni. Ehhez kihúzzuk a szalagkábelt az P1 jelölésű csatlakozóból. A kábeleket átvezetjük a gumi tömszelencéken, és megkezdhetjük a bekötésüket. A bekötést a leírásnak megfelelően kell elvégezni. A vezérlő kapcsait az alábbi ábra mutatja.

![Bekötés](./img/ic-acpołącz.png)

## Az elosztószekrényből érkező 230V AC tápellátást a következő kapcsokhoz csatlakoztatjuk:  
 - **L csatlakozó** fáziskapocs. Kismegszakító („S” típusú B3) és túlfeszültség-korlátozók használata kötelező.  
 - **N csatlakozó** nullavezető-kapocs.  
 - **PE csatlakozó** védővezető-kapocs.

## Kimenet a mozgatószerkezethez: 
 - **L csatlakozó** vezetékkel összekötjük a C csatlakozóval, hogy a relék feszültséget kapjanak.  
 - **N csatlakozó** a mozgatószerkezet nullavezető-kapcsa.  
 - **PE csatlakozó** a mozgatószerkezet védővezető-kapcsa – burkolat.  
 - **Csatlakozó NO** a mozgatószerkezet kapcsa a légbeejtők nyitási irányához.  
 - **Csatlakozó NC** a mozgatószerkezet kapcsa a légbeejtők zárási irányához.
 - **Potenciométer-csatlakozó** – a mozgatószerkezet kapcsolási rajzán szereplő jelölés szerint kell bekötni. A potenciométer tápellátásának polaritását úgy kell megválasztani, hogy a helyzetegységek a légbeejtők nyitásakor növekedjenek, zárásakor pedig csökkenjenek. Ha ez nem így van, fel kell cserélni a potenciométer tápvezetékeit.  
 - **In csatlakozó** – a vezérlőhöz kell csatlakoztatni az emelőrendszerek vezérlőjelének biztosításához.  


# Működési elv  

  A vezérlő automatikus üzemmódban az 0-10V tartományba eső vezérlőjelet a légbeejtők mozgatószerkezetének megfelelő  helyzetére alakítja át. A mozgatószerkezetet a légbeejtők maximálisan nyitott és zárt helyzetében kalibrálni kell. A kalibrálás során ügyelni kell arra, hogy a légbeejtőkhöz vezető kötelek  folyamatosan feszesek maradjanak. Kalibrálás közben a „+” gombnak nyitnia, a „-” gombnak pedig zárnia kell a légbeejtőket. Ha ez nem így van, fel kell cserélni a vezetékeket az NO és NC kapcsokon.
  A potenciométerről leolvasott nyitási és zárási helyzetértékeknek több mint 100 egységgel kell eltérniük egymástól. A potenciométerről leolvasott helyzetegységeknek a légbeejtők nyitásakor növekedniük, zárásakor pedig csökkenniük kell. Ha ez nem így van, fel kell cserélni a potenciométer tápvezetékeit.
  A megfelelő kalibrálás után a vezérlő készen áll az automatikus működésre, és szabályozni fogja a mozgatószerkezet helyzetét. Az 1,5V alatti szintű vezérlőjel hatására a légbeejtők a vészhelyzeti helyzetbe állnak. 

## Használat 

  A légbeejtők vezérlője két üzemmód egyikében működhet: kézi vagy automatikus üzemmódban. A kiválasztott üzemmód tárolódik, és a tápellátás megszűnésétől függetlenül megmarad – a tápellátás bekapcsolása után a vezérlő visszatér ahhoz az üzemmódhoz, amelyben legutóbb működött. Az aktuálisan kiválasztott üzemmód a kijelzőn látható:  
   - **MANUAL** - a "+" vagy "-" gomb hosszan történő nyomva tartása bekapcsolja a kézi üzemmódot. Ebben az üzemmódban a légbeejtők kézzel vezérelhetők a gombokkal: „+” - nyitás, „-” - zárás.           
   - **AUTO**   - az "Esc" gomb hosszan történő nyomva tartása bekapcsolja az automatikus üzemmódot. Ebben az üzemmódban a légbeejtők automatikusan működnek, az In csatlakozóról érkező 0-10V jel vezérli őket.

## Az alapmenü funkciói  

| MENÜ                       | Leírás | 
|:---:                       |:---|
|MANUAL  LEÁLLÍTÁS    POT 539  |  **„Információs mód”** – kézi működés esetén. Megjelenített információk:  - **LEÁLLÍTÁS** – a mozgatószerkezet áll;  - **NYITÁS** – a légbeejtők nyitása a „+” gomb megnyomása után;  - **ZÁRÁS** – a légbeejtők zárása a „-” gomb megnyomása után;  - **POT 539** – a mozgatószerkezet aktuális helyzetének a potenciométer által meghatározott paramétere.  •Átváltás automatikus üzemmódra az „Esc” gomb nyomva tartásával| 
|AUTO  20 % = In 3,70 POT 511       |  **„Információs mód”**  automatikus működés esetén. Megjelenített információk:    **20 %**  A légbeejtők beállított nyitási helyzetének értéke    **"="**   a légbeejtők a beállított helyzetben vannak    **"–"**    a légbeejtők zárása a meghatározott helyzetig    **"+"**    a légbeejtők nyitása a meghatározott helyzetig    **In 3,70**  a vezérlőfeszültség mérése az In kapcsokon     **POT 511**  a mozgatószerkezet aktuális helyzetének a potenciométer által meghatározott paramétere.  Átváltás kézi üzemmódra a „+” vagy „-” gomb nyomva tartásával | 
|Csappantyúk vészhelyzetben 30 %  |**„Csappantyúk vészhelyzetben”** – a csappantyúk (légbeejtők) vészhelyzeti nyitási értékének beállítása a vezérlőjel megszűnése esetére. A légbeejtők a beállított szintre nyílnak a vezérlő vagy a jelkábel meghibásodása esetén.| 
|Nyitás kalibrálása 671 -> 311        |**„Nyitás kalibrálása”** – a légbeejtők nyitásának kalibrálása a légbeejtők maximális nyitásának (véghelyzetének) beállításával történik a „+” és „-” gombok segítségével. Az első megjelenített érték a legutóbb mentett beállítást, a második érték a mozgatószerkezet aktuális helyzetét jelzi. Az „Ok” gomb a memóriába menti a megadott beállításokat, az „Esc” mentés nélkül kilép a kalibrálási módból.   | 
|Zárás kalibrálása 281 -> 311      |**„Zárás kalibrálása”** – a légbeejtők zárásának kalibrálása a légbeejtők minimális helyzetének beállításával történik a „+” és „-” gombok segítségével. Az első megjelenített érték a legutóbb mentett beállítást, a második érték a mozgatószerkezet aktuális helyzetét jelzi. Az „Ok” gomb a memóriába menti a megadott beállításokat, az „Esc” mentés nélkül kilép a kalibrálási módból.|  
|Átlagolási idő 5 s       |**„Átlagolási idő”** – az In csatlakozóról érkező vezérlőjel átlagolási ideje, védelmet nyújt a vezérlőbemenet ingadozásaival szemben.  | 
|Invertálás   Nem |**„Invertálás”** – e funkció bekapcsolása a vezérlőt az 10-0V vezérlőjelhez igazítja  | 
|Nyelv   Lengyel |**„Nyelv”** – a menü nyelvének kiválasztása  | 
|Pot hiszterézis  5   | **„Potenciométer-hiszterézis”** – a mozgatószerkezet helyzetparaméterének a beállított értéknél kisebb változását a pozicionálás nem veszi figyelembe. A paraméter célja a mozgatószerkezet nagyon kis mozgásainak és a potenciométerből származó zavaroknak a kiküszöbölése. | 
 

# Megjegyzések és figyelmeztetések  

:::danger 
A készülék telepítése során feltétlenül le kell választani az elektromos tápellátást, mivel egyes részegységeken az életre és az egészségre veszélyes feszültség van jelen. Javasolt a telepítést szakképzett személyre bízni.
:::

- A készülék üzemeltetésével kapcsolatos problémák elkerülése érdekében a telepítés és a használat megkezdése előtt el kell olvasni az útmutatót. Tilos a készülék szerkezetébe beavatkozni vagy önálló javításokat végezni. Ez különösen az alkatrészek és részegységek módosítására vonatkozik.
- A karbantartási és szervizelési munkákat jogosult személyzetnek (telepítőnek vagy a gyártó szervizének) kell végeznie. A kényszerszellőztetésű állattartó épületekben riasztórendszer szükséges. 
- A készülék gyártója nem vállal felelősséget a helytelen telepítés, a funkciók helytelen programozása, a véletlen események következményei és a külső tényezők által okozott károkért.
- A készülék paramétereit az állattartó helyiségben uralkodó körülményeknek megfelelően kell beállítani. Ezek a beállítások egyediek, és az állattartó döntésétől függenek. A készülék gyártója fenntartja a jogot a készülék szerkezetének és szoftverének módosítására.  


:::caution
![alt](./img/trash.svg) A termék használatának befejezése után azt nem szabad a nem szelektíven gyűjtött települési hulladékkal együtt kidobni, hanem a hatályos előírásoknak megfelelően kell ártalmatlanítani (az Európai Unió 2012/19/EU WEEE irányelvei).  A termék az RoHS követelményeinek megfelelően készült (az Európai Unió 2011/65/EU irányelve).
:::

<!-- \newpage -->
# A vezérlő műszaki adatai  

|Paraméter                        |	LEÍRÁS      |
|:-----------                    |:---------- |
|Váltakozó tápfeszültség|	230VAC 50Hz|
|Maximális kimeneti áram|	2A|
|Kimeneti zavarszűrő|	RC|
|Bemeneti impedancia|	100kΩ|
|A bemenetek és kimenetek túlfeszültség-védelme|	IGEN|
|A potenciométer tápellátása|	10VDC|
|A potenciométer kimeneteinek maximális árama|	30mA|
|Üzemi hőmérséklet-tartomány|	-10 +40oC|
|A készülék méretei|	20x15x8 cm |
|A burkolat védettségi fokozata|	IP65|

:::info
Az IC-AC vezérlő csomagja a következőket tartalmazza:
- 4 dübel,
- 2 PG11 tömszelence,
- 2 PG9 tömszelence.
:::

