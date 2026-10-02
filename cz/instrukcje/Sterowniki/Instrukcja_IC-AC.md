---
sidebar_position: 4
title: Návod IC-AC
description: Regulátor IC-AC přívodů vzduchu do prostorů pro chov hospodářských zvířat
  s přípustným výstupním proudem do 2A
keywords:
- eletor IC-AC
- regulátor přívodů vzduchu
- regulátor klimatu
- regulátor větrání vepřína
- regulátor mikroklimatu
- regulátor pro vepříny
- větrání vepřína
- regulátor pro odchovny
---


# Regulátor IC-AC

  Regulátor pohonů a zdvihacích mechanismů přívodů vzduchu založených na střídavých motorech s chodem vpravo/vlevo a s potenciometrem pro snímání aktuální polohy. Regulátor plní funkci převodníku signálu 0-10V na míru otevření přívodů vzduchu, navíc umožňuje ruční ovládání.

## Parametry a vlastnosti:  
- Provozní režimy:
  - MANUAL – ruční ovládání pomocí tlačítek „+“, „-“;
  - AUTO – automatický provoz v kalibrovaném rozsahu úměrný signálu 0-10V;
  - NOUZOVÝ – při ztrátě řídicího signálu se přívody vzduchu otevřou na úroveň nastavenou v procentech; 
- Reléový výstup (vpravo/vlevo) 2A;
- Řídicí signál: 0-10V;
- Možnost inverze řídicího signálu;
- Měření polohy pomocí potenciometru 1-100kΩ;
- Programovatelná hystereze a doba průměrování odečtů; 
- Hermetický kryt IP56;
- Napájecí napětí 230VAC 50Hz;
- Jazyk menu: 
  - polština
  - angličtina
  - ukrajinština
  - ruština

# Instalace regulátoru  
:::danger 
Při instalaci zařízení je bezpodmínečně nutné odpojit přívod elektrické energie, protože napětí na některých součástech je nebezpečné pro život a zdraví. Doporučuje se svěřit instalaci kvalifikované osobě.
:::

## Volba místa montáže  

  Místo montáže je nutné zvolit uvážlivě s ohledem na snadný přístup oprávněných osob k zařízení a jeho nepřístupnost pro zvířata a děti. Je nutné zohlednit také klimatické podmínky, tzn. zařízení musí pracovat v rozsahu teplot -10°C až 40 °C, na místě nevystaveném slunečnímu záření.

# Montáž

Zařízení může pracovat v agresivních klimatických podmínkách. Správně namontované zařízení je odolné vůči škodlivým vlivům prostředí. 

  Při montáži je nutné věnovat pozornost následujícím bodům: 
- víko musí být přitaženo všemi šrouby,
- kabely použité k připojení zařízení musí mít kruhový průřez,
- po připojení kabelu je nutné dotáhnout kabelové vývodky tak, aby byl kabel utěsněn a zajištěn proti pohybu, doporučuje se použití silikonu,
- nepoužité vývody (kabelové vývodky) je nutné zaslepit,
- spodní část krytu připevníme k rovné stěně 4 hmoždinkami.


# Elektrické připojení  

:::danger 
Před připojením systému se ujistěte, že je napájení vypnuté!
:::

  Po odšroubování zařízení je nutné sejmout přední panel. Za tímto účelem vytáhneme plochý kabel z konektoru označeného P1. Protáhneme kabely pryžovými kabelovými vývodkami a můžeme přistoupit k jejich připojení. Připojení je nutné provést podle popisu. Svorky regulátoru jsou znázorněny na následujícím obrázku.

![Připojení](./img/ic-acpołącz.png)

## Napájení 230V AC z rozváděče připojíme ke svorkám:  
 - **Svorka L** fázová svorka. Je vyžadováno použití jističe (typu „S“ B3) a svodičů přepětí.  
 - **Svorka N** neutrální svorka.  
 - **Svorka PE** ochranná svorka.

## Výstup pro pohon: 
 - **Svorku L** propojíme vodičem se svorkou C za účelem přivedení napětí na relé.  
 - **Svorka N** neutrální svorka pohonu.  
 - **Svorka PE** ochranná svorka pohonu – kryt.  
 - **Svorka NO** svorka pohonu pro směr otevírání přívodů vzduchu.  
 - **Svorka NC** svorka pohonu pro směr zavírání přívodů vzduchu.
 - **Konektor potenciometru** – je nutné připojit podle označení ve schématu pohonu. Polarita napájení potenciometru musí být zvolena tak, aby jednotky polohy při otevírání přívodů vzduchu rostly a při zavírání klesaly. Pokud je tomu jinak, je nutné zaměnit vodiče napájení potenciometru.  
 - **Konektor In** – je nutné připojit k regulátoru za účelem přivedení řídicího signálu do systémů zdvihacích mechanismů.  


# Princip činnosti  

  Regulátor v automatickém režimu převádí řídicí signál z rozsahu 0-10V na odpovídající  polohu pohonu přívodů vzduchu. Je nutné provést kalibraci pohonu v poloze maximálního otevření a zavření přívodů vzduchu. Během kalibrace je nutné dbát na to, aby lana  vedoucí k přívodům vzduchu zůstávala trvale napnutá. Při kalibraci musí tlačítko „+“ otevírat přívody vzduchu a tlačítko „-“ je musí zavírat. Pokud je tomu jinak, je nutné zaměnit vodiče na svorkách NO a NC.
  Polohy odečtené z potenciometru pro otevření a zavření se musí lišit o více než 100 jednotek. Jednotky polohy odečítané z potenciometru musí při otevírání přívodů vzduchu růst a při zavírání klesat. Pokud je tomu jinak, je nutné zaměnit vodiče napájení potenciometru.
  Po správné kalibraci je regulátor připraven k automatickému provozu a bude řídit polohu pohonu. Přivedení řídicího signálu na úrovni nižší než 1,5V způsobí nastavení přívodů vzduchu do nouzové polohy. 

## Používání 

  Regulátor přívodů vzduchu může pracovat v jednom ze dvou režimů: ručním nebo automatickém. Zvolený provozní režim se ukládá do paměti a je nezávislý na výpadku napájení – regulátor se po zapnutí napájení vrátí do režimu, ve kterém naposledy pracoval. Aktuálně zvolený provozní režim je označen na displeji:  
   - **MANUAL** - dlouhým podržením "+" nebo "-" se zapne ruční režim. V tomto režimu se přívody vzduchu ovládají ručně tlačítky: „+“ - otevírání, „-“ - zavírání.           
   - **AUTO**   - dlouhým podržením "Esc" se zapne automatický režim. V tomto režimu pracují přívody vzduchu automaticky a jsou řízeny signálem 0-10V z konektoru In.

## Funkce základního menu  

| MENU                       | Popis | 
|:---:                       |:---|
|MANUAL  STOP    POT 539  |  **„Informační režim”** – ručního provozu. Zobrazované informace:  - **STOP** – pohon zastaven;  - **OPEN** – otevírání přívodů vzduchu po stisknutí tlačítka „+“;  - **CLOSE** – zavírání přívodů vzduchu po stisknutí tlačítka „-“;  - **POT 539** – parametr aktuální polohy pohonu určený potenciometrem.  •Přechod do automatického provozního režimu po podržení tlačítka „Esc“| 
|AUTO  20 % = In 3,70 POT 511       |  **„Informační režim”**  automatického provozu. Zobrazované informace:    **20 %**  Hodnota požadované polohy otevření přívodů vzduchu    **"="**   přívody vzduchu v nastavené poloze    **"–"**    zavírání přívodů vzduchu do stanovené polohy    **"+"**    otevírání přívodů vzduchu do stanovené polohy    **In 3,70**  měření řídicího napětí na svorkách In     **POT 511**  parametr aktuální polohy pohonu určený potenciometrem.  Přechod do ručního provozního režimu po podržení tlačítka „+“ nebo „-“ | 
|Klapky nouzově 30 %  |**„Klapky nouzově”** – nastavení hodnoty nouzového otevření klapek (přívodů vzduchu) při ztrátě řídicího signálu. Přívody vzduchu se otevřou na nastavenou úroveň při poruše regulátoru nebo signálového kabelu.| 
|Kalibrace Otevř 671 -> 311        |**„Kalibrace otevření”** – kalibrace otevření přívodů vzduchu se provádí nastavením maximálního otevření (krajní polohy) přívodů vzduchu pomocí tlačítek „+“ a „-“. První zobrazená hodnota představuje naposledy uložené nastavení, druhá hodnota aktuální polohu pohonu. Tlačítko „Ok“ uloží zadaná nastavení do paměti, „Esc“ ukončí režim kalibrace bez uložení.   | 
|Kalibrace Zavř 281 -> 311      |**„Kalibrace zavření”** – kalibrace zavření přívodů vzduchu se provádí nastavením minimální polohy přívodů vzduchu pomocí tlačítek „+“ a „-“. První zobrazená hodnota představuje naposledy uložené nastavení, druhá hodnota aktuální polohu pohonu. Tlačítko „Ok“ uloží zadaná nastavení do paměti, „Esc“ ukončí režim kalibrace bez uložení.|  
|Doba průměrování 5 s       |**„Doba průměrování”** – doba průměrování řídicího signálu z konektoru In, chrání před oscilacemi na řídicím vstupu.  | 
|Inverze   Ne |**„Inverze”** – zapnutí této funkce přizpůsobí regulátor řídicímu signálu 10-0V  | 
|Jazyk   Polština |**„Jazyk”** – výběr jazyka menu  | 
|Hystereze Pot  5   | **„Hystereze potenciometru”** – změna parametru polohy pohonu menší než nastavená hodnota se při polohování nezohledňuje. Parametr slouží k eliminaci velmi malých pohybů pohonu a rušení z potenciometru. | 
 

# Poznámky a varování  

:::danger 
Při instalaci zařízení je bezpodmínečně nutné odpojit přívod elektrické energie, protože napětí na některých součástech je nebezpečné pro život a zdraví. Doporučuje se svěřit instalaci kvalifikované osobě.
:::

- Aby se předešlo problémům s provozem zařízení, je nutné se před zahájením instalace a používání seznámit s návodem. Není dovoleno zasahovat do konstrukce ani provádět vlastní opravy. To se týká zejména provádění změn prvků a součástí.
- Údržbu nebo servis smí provádět oprávněný personál (instalační technik nebo firemní servis). V budovách pro chov hospodářských zvířat s nuceným větráním je vyžadován poplachový systém. 
- Výrobce zařízení neodpovídá za škody způsobené nesprávnou instalací, nesprávným naprogramováním funkcí, následky nahodilých událostí a vnějšími faktory.
- Zařízení vyžaduje nastavení parametrů podle podmínek v chovném prostoru. Tato nastavení jsou individuální záležitostí závislou na rozhodnutí chovatele. Výrobce zařízení si vyhrazuje právo na změny konstrukce zařízení a softwaru.  


:::caution
![alt](./img/trash.svg) Po ukončení používání výrobku jej nevyhazujte společně s netříděným komunálním odpadem, ale zlikvidujte jej v souladu s platnými předpisy (směrnice WEEE Evropské unie 2012/19/EU).  Výrobek byl vyroben v souladu s požadavky RoHS (směrnice Evropské unie 2011/65/EU).
:::

<!-- \newpage -->
# Technické údaje regulátoru  

|Parametr                        |	POPIS      |
|:-----------                    |:---------- |
|Střídavé napájecí napětí|	230VAC 50Hz|
|Maximální výstupní proud|	2A|
|Výstupní odrušovací filtr|	RC|
|Vstupní impedance|	100kΩ|
|Přepěťová ochrana vstupů a výstupů|	ANO|
|Napájení potenciometru|	10VDC|
|Maximální proud výstupů potenciometru|	30mA|
|Rozsah provozních teplot|	-10 +40oC|
|Rozměry zařízení|	20x15x8 cm |
|Stupeň krytí krytu|	IP65|

:::info
Regulátor IC-AC obsahuje v sadě:
- 4 hmoždinky,
- 2 kabelovou vývodku PG11,
- 2 kabelovou vývodku PG9.
:::

