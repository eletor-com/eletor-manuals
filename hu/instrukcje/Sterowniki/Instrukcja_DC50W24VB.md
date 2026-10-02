---
sidebar_position: 4
title: DC50W24VB tápegység használati útmutatója
description: DC50W24VB  szünetmentes tápegység a légbevezető rendszerhez.
keywords:
- eletor IC-AC
- légbevezető-vezérlő
- klímavezérlő
- sertésistálló szellőzésvezérlője
- mikroklíma-vezérlő
- vezérlő sertésistállókhoz
- sertésistálló szellőztetése
- vezérlő nevelőistállókhoz
---


# Tápegység DC50W24VB

Szünetmentes tápegység a légbevezetők és légkivezetők automatikus és kézi nyitásának funkciójával. A haszonállatok biztonságának biztosítására szolgál áramkimaradás vagy a vezérlő meghibásodása esetén. Rendellenesség észlelésekor a készülék riasztást ad, és az emelőszerkezeteket a beállított szintig nyitja.

## Paraméterek és jellemzők: 
-  Üzemmódválasztó kapcsoló: 
    - MANUAL
    - AUTO.
-  A légbevezetők nyitási fokának forgatógombja.
-  Támogatott szabványok:
    - 0-10, 2-10, 10-0, 10-2.
-  A vezérlőjel invertálásának lehetősége.
-  Riasztási kimenetek NO és NC.
-  Áramkimaradás jelzése.
-  A vezérlőfeszültség felügyelete 2-10V.
-  A 24VDC kimenetek rövidzárlat-felügyelete.
-  A 0-10V kimenetek rövidzárlat-felügyelete.
-  2 bemenet 0-10V.
-  2 kimenetek 0-10V.
-  A bemenetek, kimenetek és a 24V vonal elektronikus védelme.
-  Akkumulátortelep 24V 4.0 Ah.
-  Hermetikus készülékház IP65.
-  Tápfeszültség 85~264VAC 47~63Hz.

# A vezérlő telepítése  
:::danger 
A készülék telepítése során az elektromos energiaellátást feltétlenül le kell kapcsolni, mivel egyes részegységeken a feszültség élet- és egészségveszélyes. A telepítést ajánlott szakképzett személyre bízni.
:::

## A szerelési hely kiválasztása  

A szerelési helyet körültekintően kell kiválasztani, figyelembe véve, hogy a készülék az arra jogosult személyek számára könnyen hozzáférhető, az állatok és gyermekek számára pedig hozzáférhetetlen legyen. Figyelembe kell venni a klimatikus körülményeket is, azaz a készüléknek -10°C és 40 °C közötti hőmérséklet-tartományban, közvetlen napsugárzástól védett helyen kell működnie. A készülék körül biztosítani kell a levegő szabad áramlását.

# Szerelés  

A készülék agresszív klimatikus körülmények között is működhet. A megfelelően felszerelt készülék ellenáll a környezet káros hatásainak.

### A szerelés során a következőkre kell figyelni: 
 - a fedél minden csavarját meg kell húzni,
 - a készülék bekötéséhez használt kábeleknek kör keresztmetszetűnek kell lenniük,
 - a kábel bekötése után a tömszelencéket úgy kell meghúzni, hogy biztosítsák a kábel tömítését és rögzítését, szilikon használata ajánlott,
 - a nem használt kábelkivezetéseket (tömszelencéket) le kell zárni,
 - a készülékház alsó részét sík falra kell rögzíteni 4 feszítődübellel.


# Elektromos bekötés  

:::danger 
Az áramkör csatlakoztatása előtt meg kell győződni arról, hogy a tápellátás ki van kapcsolva!
:::

A készülék csavarjainak kicsavarása után az előlapot le kell venni. Ehhez ki kell húzni a szalagkábelt a P1 jelölésű csatlakozóból. A kábeleket át kell vezetni a gumi tömszelencéken, ezután megkezdhető a bekötésük. A bekötést a leírás szerint kell elvégezni.

![Bekötés](./img/DC50W24VB.png)

**Tápellátás 230V AC:** csatlakoztatni kell a tápellátáshoz (elosztóhoz). Kötelező kismegszakító („S” típusú B6), valamint „C” osztályú túlfeszültség-korlátozók használata. A készülék széles, 85V és 264V közötti feszültségtartományban, valamint 47 és 63Hz közötti frekvenciatartományban táplálható, anélkül, hogy ez befolyásolná a készülék működését.  

**In1 és In2 csatlakozó** a vezérlőhöz kell csatlakoztatni, hogy az emelőszerkezetek rendszerei megkapják a vezérlőjelet. A készülék két vezérlőt vagy egyetlen, külön légbevezető és légkivezető szekcióval rendelkező vezérlőt képes kezelni (a I1 és I2 kapcsokat át kell hidalni).  

**ALARM csatlakozó** a riasztóközponthoz kell csatlakoztatni, a rendszertől függően – zárt (NO és C), nyitott (NC és C). A riasztás a következő esetekben kapcsol be:  •megszűnt a készülék tápfeszültsége,  •megszűnt a 2-10V vezérlőjel legalább az egyik bemeneten,  •a kimeneti jel rövidzárlata lépett fel, vagy annak értéke eltér a mért értéktől,  •rövidzárlat lépett fel az emelőszerkezeteket tápláló +24V sínen.  

**Ouput 1 és Ouput 2** csatlakozó a működtetőhöz (emelőszerkezethez) csatlakoztatandó az adott készülék által megkövetelt módon, a bekötés leírásának az adott működtető (emelőszerkezet) útmutatójában kell szerepelnie.  

**Üzemmódkapcsoló S1** az adott működtetőtől (emelőszerkezettől) függően ki kell választani a megfelelő üzemmódot. Alapértelmezés szerint a 1,2,3,4,5,6 kapcsolók off állásban vannak – 2-10V működés.
 
| Csatorna 1 | Csatorna 2| Funkció |
|------|------|----------|
| 1 – off | 4 – off | Működés a 2-10V jeltartományban, a 1,5V alatti vezérlőfeszültség riasztást vált ki.   |
| 1 – on| 4 – on  | Működés a 0-10V jeltartományban, a 1,5V alatti jelre nincs riasztási reakció.   |
| 2 – off | 5 – off  | Arányos üzemmód, a kimeneti jelek a 0-10V vagy 2-10V tartományban vannak.  |
| 2 – on | 5 – on  | Fordított üzemmód, a kimeneti jelek a 10-0V vagy 10-2V tartományban vannak.   |
| 3 – off | 6 – off  | Bemeneti invertálás kikapcsolva.  |
| 3 – on | 6 – on   | Bemeneti invertálás bekapcsolva.   |

# Működési elv  

A szünetmentes tápegység normál üzemmódban táplálja a 24V működtetőket (emelőszerkezeteket), és tölti vagy feltöltött állapotban tartja az akkumulátorokat, amelyek áramkimaradás esetén biztosítják a tápellátást.  A AUTO/MANUAL kapcsoló határozza meg a készülék üzemmódját.  

**A MANUAL** üzemmód lehetővé teszi a működtetők (emelőszerkezetek) közvetlen vezérlését a készülék paneljén található forgatógombbal.  

**A AUTO** üzemmód – az alapvető üzemmód, amely a vezérlőjelet a bemenetről a kimenetre továbbítja, a „S1” kapcsoló beállításainak megfelelő feldolgozást végezve, és felügyeli a bemeneti jel szintjét.  Ha az adott bemeneten rendellenességet észlel, a készülék az előlapon található forgatógomb jelét adja a kimenetére.  A riasztórelé a következő esetekben lép működésbe:  •túl alacsony bemeneti jel (Uin < 1,5V) – „S1” kapcsoló 1-off, 4-off,  •a kimeneti jel rövidzárlata a testhez vagy a 24V ponthoz,  •a tápfeszültség hiánya,  •a 24V feszültség rövidzárlata.

## Használat 

A felhasználó a kapcsolóval kiválasztja a MANUAL üzemmódot, a forgatógombbal pedig a légbevezetők igényeknek megfelelő nyitási fokát – a működtetők a forgatógomb beállításának megfelelően működnek. A légbevezetők beállításának befejezése után a kapcsolóval ki kell választani a AUTO üzemmódot, majd a készüléket ebben az állapotban kell hagyni – a légbevezetők a szellőzésvezérlő által megkövetelt szintre állnak. Vészhelyzetben a légbevezetők a forgatógomb beállításának megfelelően állnak be.  

## Előlap 

| MENÜ                       | Leírás | 
|:---:                       |:---|
|![Bekötés](./img/paneldcw50.png) |**Jelzőlámpa POWER** – jelzi a tápellátás meglétét és az akkumulátorok töltését.  1.**Jelzőlámpa CHECK** – automatikus üzemmódban folyamatosan világít, amikor a kimenetre a vezérlő jele kerül, villog, amikor a kimenetre a forgatógomb jele kerül.  2.**OUT 1** – a 1 csatorna rendellenességeiről tájékoztat.  3.**OUT 2** – a 2 csatorna rendellenességeiről tájékoztat.  4.**AUTO** – automatikus üzemmód.  5.**MANUAL** – kézi üzemmód.  6.**Forgatógomb 0%-100%** - a légbevezetők nyitási fokának kiválasztása.| 

# Hibaüzenetek és figyelmeztetések

A hibaüzenetek a készülék működésében fellépő rendellenességekről tájékoztatják a felhasználót. Az alábbiakban a lehetséges hibaüzenetek szerepelnek:
 -  Jelzőlámpa POWER – nem világít zölden – nincs hálózati tápellátás.
 -  Jelzőlámpa CHECK – sárgán villog – a kimenetekre a potenciométer jele került.
 -  Jelzőlámpa OUT 1 – pirosan világít - rendellenesség észlelése (vezérlőjel hiánya, rövidzárlat a kimeneten vagy rövidzárlat a 24VDC sínen) az első csatornán.
 -  Jelzőlámpa OUT 2 – pirosan világít - rendellenesség észlelése (vezérlőjel hiánya, rövidzárlat a kimeneten vagy rövidzárlat a 24VDC sínen) a második csatornán.

# Megjegyzések és figyelmeztetések  

:::danger 
A készülék telepítése során az elektromos energiaellátást feltétlenül le kell kapcsolni, mivel egyes részegységeken a feszültség élet- és egészségveszélyes. A telepítést ajánlott szakképzett személyre bízni.
:::

 - A készülék üzemeltetési problémáinak elkerülése érdekében a telepítés és a használat megkezdése előtt el kell olvasni az útmutatót. Tilos a készülék szerkezetébe beavatkozni vagy önálló javításokat végezni. Ez különösen az elemek és részegységek módosítására vonatkozik.
 - A karbantartási és szervizmunkákat arra jogosult személyzetnek (telepítőnek vagy a gyártó szervizének) kell elvégeznie. A kényszerszellőztetéssel rendelkező állattartó épületekben riasztórendszer használata kötelező. 
 - A készülék gyártója nem vállal felelősséget a helytelen telepítés, a funkciók helytelen programozása, véletlen események következményei és külső tényezők által okozott károkért. A készülék paramétereit az állattartó helyiségben uralkodó körülményeknek megfelelően kell beállítani.Ezek a beállítások egyediek, és az állattartó döntésétől függenek. 
 - A készülék gyártója fenntartja a jogot a készülék szerkezetének és szoftverének módosítására.
A készülék akkumulátortelepet tartalmaz, az akkumulátorok túlzott kisütését meg kell akadályozni, mert az a telep károsodását okozhatja. 
Az akkumulátortelep pólusainak rövidre zárása tüzet okozhat.  


:::caution
![alt](./img/trash.svg) A terméket használatának befejezése után nem szabad a válogatatlan települési hulladékkal együtt kidobni, hanem a hatályos előírásoknak megfelelően kell kezelni (az Európai Unió WEEE-irányelvei 2012/19/UE).  A termék a RoHS követelményeinek megfelelően készült (az Európai Unió 2011/65/UE irányelve).
:::

<!-- \newpage -->
# A vezérlő műszaki adatai  

|Paraméter                        |	LEÍRÁS      |
|:-----------                    |:---------- |
|Váltakozó tápfeszültség|	85~264VAC 47~63Hz|
|Egyen tápfeszültség|	120~370VDC|
|Kimeneti feszültség|	27,6VDC|
|Maximális kimeneti áram|	1,8A|
|Hatásfok|	85%|
|A 0-10V| vezérlőkimenetek maximális árama	30mA|
|Az ALARM kimenet (érintkező) maximális árama|	3A|
|A bemenetek és kimenetek túlfeszültség-védelme|	IGEN|
|Rövidzárlat elleni védelem|	Automatikus |
|Akkumulátortelep|	4Ah 24V|
|Üzemi hőmérséklet-tartomány|	-10 +40oC|
|A készülék méretei|	20x15x8 cm|
|A készülékház védettségi osztálya|	IP65|

:::info
A IC-AC vezérlő készletének tartalma:
 - feszítődübelek - 	4 db, 
 - akkumulátorok 12V 4Ah - 	2 db, 
 - tömszelence PG13,5 -	1 db,
 - tömszelence PG11 -	3 db, 
 - tömszelence PG9 -	3 db.
:::

