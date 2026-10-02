---
sidebar_position: 4
title: Návod Napájecí zdroj DC50W24VB
description: Záložní napájecí zdroj DC50W24VB  pro systém přívodů vzduchu.
keywords:
- eletor IC-AC
- řídicí jednotka přívodů vzduchu
- řídicí jednotka klimatu
- řídicí jednotka ventilace vepřína
- řídicí jednotka mikroklimatu
- řídicí jednotka pro vepříny
- ventilace vepřína
- řídicí jednotka pro odchovny
---


# Napájecí zdroj DC50W24VB

Záložní napájecí zdroj s funkcí automatického a ručního otevírání přívodů a odvodů vzduchu. Používá se k zajištění bezpečnosti hospodářských zvířat v případě výpadku napájení nebo poruchy řídicí jednotky. Zařízení po zjištění nesrovnalostí vyhlásí alarm a otevře navijáky na nastavenou úroveň.

## Parametry a vlastnosti: 
-  Přepínač volby provozního režimu: 
    - MANUAL
    - AUTO.
-  Otočný ovladač stupně otevření přívodů vzduchu.
-  Podporované standardy:
    - 0-10, 2-10, 10-0, 10-2.
-  Možnost inverze řídicího signálu.
-  Alarmové výstupy NO a NC.
-  Signalizace výpadku napájení.
-  Kontrola řídicího napětí 2-10V.
-  Kontrola zkratu na výstupech 24VDC.
-  Kontrola zkratu na výstupech 0-10V.
-  2 vstup 0-10V.
-  2 výstupy 0-10V.
-  Elektronické ochrany vstupů, výstupů a vedení 24V.
-  Baterie akumulátorů 24V 4.0 Ah.
-  Hermetický kryt IP65.
-  Napájecí napětí 85~264VAC 47~63Hz.

# Instalace řídicí jednotky  
:::danger 
Při instalaci zařízení je bezpodmínečně nutné odpojit přívod elektrické energie, protože napětí na některých součástech je nebezpečné pro život a zdraví. Doporučuje se svěřit instalaci kvalifikované osobě.
:::

## Výběr místa montáže  

Místo montáže je třeba volit uvážlivě s ohledem na snadný přístup k zařízení pro oprávněné osoby a nepřístupnost pro zvířata a děti. Je třeba zohlednit také klimatické podmínky, tj. zařízení musí pracovat v rozsahu teplot -10°C až 40 °C, na místě nevystaveném slunečnímu záření. Kolem zařízení musí být zajištěno volné proudění vzduchu.

# Montáž  

Zařízení může pracovat v agresivních klimatických podmínkách. Správně namontované zařízení je odolné vůči škodlivému působení prostředí.

### Při montáži je třeba věnovat pozornost následujícím bodům: 
 - víko musí být utaženo všemi šrouby,
 - kabely použité k připojení zařízení musí mít kruhový průřez,
 - po připojení kabelu je třeba utáhnout kabelové vývodky tak, aby byl kabel utěsněn a zajištěn proti pohybu, doporučuje se použít silikon,
 - nepoužité vývody (kabelové vývodky) je třeba zaslepit,
 - spodní část krytu připevněte k rovné stěně 4 rozpěrnými hmoždinkami.


# Elektrické připojení  

:::danger 
Před připojením systému se ujistěte, že je napájení vypnuté!
:::

Po odšroubování zařízení je třeba sejmout přední panel. Za tímto účelem vytáhněte plochý kabel z konektoru označeného jako P1. Protáhněte kabely pryžovými kabelovými vývodkami a můžete přistoupit k jejich připojení. Připojení je třeba provést podle popisu.

![Připojení](./img/DC50W24VB.png)

**Napájení 230V AC:** připojte k napájení (rozvaděči). Je nutné použít nadproudový jistič (typu „S“ B6) a svodiče přepětí třídy „C“. Zařízení může být napájeno v širokém rozsahu napětí od 85V do 264V a frekvencí od 47 do 63Hz, aniž by to ovlivnilo provoz zařízení.  

**Konektor In1 a In2** je třeba připojit k řídicí jednotce za účelem přivedení řídicího signálu do systémů navijáků. Zařízení může obsluhovat dvě řídicí jednotky nebo jednu s oddělenou sekcí přívodů a odvodů vzduchu (svorky I1 a I2 je třeba propojit můstkem).  

**Konektor ALARM** připojte k alarmové ústředně podle systému – sepnutý (NO a C), rozepnutý (NC a C). Alarm se aktivuje v následujících případech:  •došlo k výpadku napájecího napětí zařízení,  •došlo ke ztrátě řídicího signálu 2-10V alespoň na jednom ze vstupů,  •došlo ke zkratu výstupního signálu nebo se jeho hodnota liší od měřené hodnoty,  •došlo ke zkratu na sběrnici +24V napájející navijáky.  

**Konektor Ouput 1 a Ouput 2** připojte k pohonu (navijáku) způsobem požadovaným pro dané zařízení, popis připojení by měl být uveden v návodu příslušného pohonu (navijáku).  

**Přepínač provozního režimu S1** podle použitého pohonu (navijáku) je třeba zvolit odpovídající provozní režim. Ve výchozím nastavení jsou přepínače 1,2,3,4,5,6 v poloze off – provoz 2-10V.
 
| Kanál 1 | Kanál 2| Funkce |
|------|------|----------|
| 1 – off | 4 – off | Provozní režim v rozsahu signálů 2-10V, řídicí napětí pod 1,5V vyvolá alarm.   |
| 1 – on| 4 – on  | Provozní režim v rozsahu signálů 0-10V, bez alarmové reakce na signál pod 1,5V.   |
| 2 – off | 5 – off  | Proporcionální provozní režim, signály na výstupu v rozsahu 0-10V nebo 2-10V.  |
| 2 – on | 5 – on  | Obrácený provozní režim, signály na výstupu v rozsahu 10-0V nebo 10-2V.   |
| 3 – off | 6 – off  | Inverze vstupu vypnuta.  |
| 3 – on | 6 – on   | Inverze vstupu zapnuta.   |

# Princip činnosti  

Záložní napájecí zdroj v režimu běžného provozu napájí pohony (navijáky) 24V a nabíjí akumulátory nebo udržuje jejich nabití; akumulátory zajistí napájení v případě výpadku napájení.  Přepínač AUTO/MANUAL určuje provozní režim zařízení.  

**Režim MANUAL** umožňuje přímé ovládání pohonů (navijáků) otočným ovladačem na panelu zařízení.  

**Režim AUTO** – základní provozní režim, předává řídicí signál ze vstupu na výstup, provádí jeho odpovídající zpracování podle nastavení přepínače „S1“ a kontroluje úroveň vstupního signálu.  V případě zjištění nesrovnalostí na daném vstupu zařízení přivede na svůj výstup signál z otočného ovladače na předním panelu.  Alarmové relé se aktivuje v případě:  •příliš nízkého vstupního signálu (Uin < 1,5V) – přepínač „S1“ 1-off, 4-off,  •zkratu výstupního signálu na zem nebo 24V,  •výpadku napájecího napětí,  •zkratu napětí 24V.

## Používání 

Uživatel přepínačem zvolí režim MANUAL a otočným ovladačem stupeň otevření přívodů vzduchu odpovídající požadavkům – pohony pracují podle polohy otočného ovladače. Po dokončení nastavení přívodů vzduchu zvolte přepínačem režim AUTO a ponechte zařízení v provozu – přívody vzduchu se nastaví na úroveň požadovanou řídicí jednotkou ventilace. V nouzové situaci se přívody vzduchu nastaví podle polohy otočného ovladače.  

## Přední panel 

| MENU                       | Popis | 
|:---:                       |:---|
|![Připojení](./img/paneldcw50.png) |**Kontrolka POWER** – signalizuje přítomnost napájení a nabíjení akumulátorů.  1.**Kontrolka CHECK** – svítí trvale v automatickém režimu, když je na výstup předáván signál z řídicí jednotky, bliká při přivádění signálu z otočného ovladače na výstup.  2.**OUT 1** – informuje o nesrovnalostech v kanálu 1.  3.**OUT 2** – informuje o nesrovnalostech v kanálu 2.  4.**AUTO** – automatický provozní režim.  5.**MANUAL** – ruční provozní režim.  6.**Otočný ovladač 0%-100%** - volba stupně otevření přívodů vzduchu.| 

# Chybová a výstražná hlášení

Chybová hlášení slouží k informování uživatele o nesrovnalostech v provozu zařízení. Níže jsou uvedena možná chybová hlášení:
 -  Kontrolka POWER – nesvítí zeleně – chybí síťové napájení.
 -  Kontrolka CHECK – bliká žlutě – na výstupy je přiveden signál z potenciometru.
 -  Kontrolka OUT 1 – svítí červeně - zjištění nesrovnalostí (chybí řídicí signál, zkrat na výstupu nebo zkrat na sběrnici 24VDC) v prvním kanálu.
 -  Kontrolka OUT 2 – svítí červeně - zjištění nesrovnalostí (chybí řídicí signál, zkrat na výstupu nebo zkrat na sběrnici 24VDC) ve druhém kanálu.

# Poznámky a upozornění  

:::danger 
Při instalaci zařízení je bezpodmínečně nutné odpojit přívod elektrické energie, protože napětí na některých součástech je nebezpečné pro život a zdraví. Doporučuje se svěřit instalaci kvalifikované osobě.
:::

 - Aby se předešlo problémům s provozem zařízení, je nutné se před zahájením instalace a používání seznámit s návodem. Není dovoleno zasahovat do konstrukce ani provádět vlastní opravy. To se týká zejména změn prvků a součástí.
 - Údržbu nebo servisní činnosti musí provádět oprávněný personál (instalační technik nebo firemní servis). V objektech pro chov hospodářských zvířat s nucenou ventilací je vyžadován alarmový systém. 
 - Výrobce zařízení neodpovídá za škody způsobené nesprávnou instalací, nesprávným naprogramováním funkcí, následky nahodilých událostí a vnějšími faktory. Zařízení vyžaduje nastavení parametrů podle podmínek panujících v chovném prostoru.Tato nastavení jsou individuální záležitostí závislou na rozhodnutí chovatele. 
 - Výrobce zařízení si vyhrazuje právo na změny konstrukce zařízení a softwaru.
Součástí zařízení je baterie akumulátorů, nesmí dojít k jejich nadměrnému vybití, které může způsobit poškození baterie. 
Zkrat pólů baterie může způsobit požár.  


:::caution
![alternativní text](./img/trash.svg) Po ukončení používání výrobku jej nevyhazujte spolu s netříděným komunálním odpadem, ale zlikvidujte jej v souladu s platnými předpisy (směrnice WEEE Evropské unie 2012/19/EU).  Výrobek byl vyroben v souladu s požadavky RoHS (směrnice Evropské unie 2011/65/EU).
:::

<!-- \newpage -->
# Technické údaje řídicí jednotky  

|Parametr                        |	POPIS      |
|:-----------                    |:---------- |
|Střídavé napájecí napětí|	85~264VAC 47~63Hz|
|Stejnosměrné napájecí napětí|	120~370VDC|
|Výstupní napětí|	27,6VDC|
|Maximální výstupní proud|	1,8A|
|Účinnost|	85%|
|Maximální proud řídicích výstupů 0-10V|	30mA|
|Maximální proud výstupu (kontaktu) ALARM|	3A|
|Přepěťová ochrana vstupů a výstupů|	ANO|
|Ochrana proti zkratu|	Automatická |
|Baterie akumulátorů|	4Ah 24V|
|Rozsah provozních teplot|	-10 +40oC|
|Rozměry zařízení|	20x15x8 cm|
|Stupeň krytí krytu|	IP65|

:::info
Řídicí jednotka IC-AC obsahuje v sadě:
 - rozpěrné hmoždinky - 	4 ks, 
 - akumulátory 12V 4Ah - 	2 ks, 
 - kabelovou vývodku PG13,5 -	1 ks,
 - kabelovou vývodku PG11 -	3 ks, 
 - kabelovou vývodku PG9 -	3 ks.
:::

