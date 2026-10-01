---
sidebar_position: 4

title: Instrukcja Zasilacz DC50W24VB
description: Zasilacz DC50W24VB  awaryjny do systemu wlotów powietrza.
keywords: [eletor IC-AC, sterownik wlotów powietrza, sterownik klimatu, sterownik wentylacji chlewni, sterownik mikroklimatu, sterownik na chlewnie, wentylacjia chlewni, sterownik na ochowalnie]
---


# Zasilacz DC50W24VB

Zasilacz awaryjny z funkcją automatycznego i ręcznego otwierania wlotów i wylotów powietrza. Stosowany do zapewnienia bezpieczeństwa zwierzętom hodowlanym w przypadku zaniku zasilania lub awarii sterownika. Urządzenie po wykryciu nieprawidłowości zgłosi alarm i otworzy windy na zadany poziom.

## Parametry i cechy: 
-  Przełącznik wyboru trybu pracy: 
    - MANUAL
    - AUTO.
-  Pokrętło stopnia otwarcia wlotów.
-  Obsługa standardów:
    - 0-10, 2-10, 10-0, 10-2.
-  Możliwość inwersji sygnału sterującego.
-  Wyjścia alarmowe NO i NC.
-  Sygnalizacja zaniku zasilania.
-  Kontrola napięcia sterującego 2-10V.
-  Kontrola przeciwzwarciowa wyjść 24VDC.
-  Kontrola przeciwzwarciowa wyjść 0-10V.
-  2 wejście 0-10V.
-  2 wyjścia 0-10V.
-  Elektroniczne zabezpieczenia wejść, wyjść i linii 24V.
-  Bateria akumulatorów 24V 4.0 Ah.
-  Hermetyczna obudowa IP65.
-  Napięcie zasilania 85~264VAC 47~63Hz.

# Instalacja sterownika  
:::danger 
W trakcie instalowania urządzenia, dopływ energii elektrycznej należy bezwzględnie odłączyć, ponieważ napięcie na niektórych podzespołach jest niebezpieczne dla życia i zdrowia. Zaleca się powierzenie instalacji wykwalifikowanej osobie.
:::

## Wybór miejsca montażu  

Miejsce montażu należy wybierać racjonalnie, uwzględniając względy łatwego dostępu do urządzenia osobom powołanym, a niedostępnym dla zwierząt oraz dzieci. Należy uwzględnić także warunki klimatyczne, tzn. urządzenie powinno pracować w zakresie temperatur -10°C do 40 °C, w miejscu nienasłonecznionym. Wokoło urządzenia powinien być swobodny przepływ powietrza.

# Montaż  

Urządzenie może pracować w agresywnych warunkach klimatycznych. Prawidłowo zamontowane urządzenie jest odporne na szkodliwe działanie środowiska.

### Podczas montażu trzeba zwrócić uwagę na następujące rzeczy: 
 - pokrywa musi być dokręcona na wszystkie śruby,
 - stosowane przewody do połączenia urządzenia powinny posiadać okrągły przekrój,
 - po połączeniu przewodu należy dokręcić dławnice tak, aby przewód został uszczelniony i unieruchomiony, zalecane jest użycie silikonu,
 - niewykorzystane wyprowadzenia (dławnice) należy zaślepić,
 - spodnią cześć obudowy mocujemy do płaskiej ściany 4 kołkami rozporowymi.


# Połączenie elektryczne  

:::danger 
Przed podłączeniem układu należy się upewnić, czy zasilanie jest wyłączone!
:::

Po rozkręceniu urządzenia, przedni panel należy zdjąć. W tym celu wyciągamy taśmę ze złącza, oznaczonego jako P1. Wprowadzamy przewody przez gumowe dławnice i możemy przystąpić do ich łączenia. Połączenie należy wykonać zgodnie z opisem.

![Połączenie](./img/DC50W24VB.png)

**Zasilanie 230V AC:** łączymy z zasilaniem (rozdzielnią). Wymagane jest stosowanie wyłącznika nadprądowego (typu „S” B6) oraz ograniczników przepięć klasy „C”. Urządzenie może być zasilane w szerokim zakresie napięć od 85V do 264V i częstotliwości od 47 do 63Hz, bez wpływu na pracę urządzenia.  

**Złącze In1 i In2** należy połączyć do sterownika, celem podania sygnału sterującego do systemów wind. Urządzenie może obsługiwać dwa sterowniki lub pojedynczy z rozdzieloną sekcją wlotów i wylotów (zacisk I1 i I2 należy mostkować).  

**Złącze ALARM** łączymy z centralką alarmową, w zależności od systemu – zwarty (NO i C), rozwarty (NC i C). Alarm załącza się w następujących przypadkach:  •zanikło napięcie zasilające urządzenie,  •zanikł sygnał sterujący 2-10V na co najmniej jednym z wejść,  •wystąpiło zwarcie sygnału wyjściowego lub jego wartość jest inna niż mierzona,  •wystąpiło zwarcie na szynie +24V zasilającej windy.  

**Złącze Ouput 1 i Ouput 2** łączymy z siłownikiem (windą) w sposób wymagany do posiadanego urządzenia, opis połączenia powinien znajdować się w instrukcji danego siłownika (windy).  

**Przełącznik trybu pracy S1** w zależności od posiadanego siłownika (windy) należy wybrać odpowiedni tryb pracy. Domyślnie przełączniki 1,2,3,4,5,6 w pozycji off – praca 2-10V.
 
| Kanał 1 | Kanał 2| Funkcja |
|------|------|----------|
| 1 – off | 4 – off | Tryb praca w zakresie sygnałów 2-10V, napięcie sterowania poniżej 1,5V generuje alarm.   |
| 1 – on| 4 – on  | Tryb praca w zakresie sygnałów 0-10V, brak reakcji alarmowej na sygnał poniżej 1,5V.   |
| 2 – off | 5 – off  | Tryb pracy proporcjonalny, sygnały na wyjściu w zakresie 0-10V lub 2-10V.  |
| 2 – on | 5 – on  | Tryb pracy obrócony, sygnały na wyjściu w zakresie 10-0V lub 10-2V.   |
| 3 – off | 6 – off  | Inwersja wejścia wyłączona.  |
| 3 – on | 6 – on   | Inwersja wejścia włączona.   |

# Zasada działania  

Zasilacz awaryjny, w trybie normalnej pracy, zasila siłowniki (windy) 24V i ładuje lub podtrzymuje naładowane akumulatory, które dostarczą zasilania w przypadku zaniku zasilania.  Przełącznik AUTO/MANUAL wyznacza tryb pracy urządzenia.  

**Tryb MANUAL** umożliwia bezpośrednie sterowanie siłownikami (windami) z pokrętła na panelu urządzenia.  

**Tryb AUTO** – podstawowy tryb pracy, przekazuje sygnał sterujący z wejścia na wyjście, dokonując stosownej obróbki w zależności od nastaw przełącznika „S1” oraz kontroluje poziom sygnału wejściowego.  W przypadku wykrycia nieprawidłowości na danym wejściu urządzenie poda na swoje wyjście sygnał z pokrętła na panelu przednim.  Przekaźnik alarmowy zadziała w przypadku:  •zbyt niskim sygnale wejściowym (Uin < 1,5V) – przełącznik „S1” 1-off, 4-off,  •zwarciu sygnału wyjściowego do masy lub 24V,  •braku napięcia zasilania,  •zwarcie napięcie 24V.

## Użytkowanie 

Użytkownik przełącznikiem wybiera tryb MANUAL, a pokrętłem stosowny do wymagań stopień otwarcia wlotów powietrza – siłowniki pracują zgodnie ze wskazaniem pokrętła. Po zakończeniu ustawień wlotów przełącznikiem wybieramy tryb AUTO i pozostawiamy urządzenie – wloty ustawią się na poziom wymagany przez sterownik wentylacji. W sytuacji awaryjnej wloty ustawią się zgodnie z wskazaniem pokrętła.  

## Panel przedni 

| MENU                       | Opis | 
|:---:                       |:---|
|![Połączenie](./img/paneldcw50.png) |**Kontrolka POWER** – sygnalizuje obecność zasilania i ładowanie akumulatorów.  1.**Kontrolka CHECK** – świeci ciągle w trybie automatycznym, gdy na wyjście przekazywany jest sygnał z sterownika, pulsuje w przypadku podawania na wyjście sygnału z pokrętła.  2.**OUT 1** – informuje o nieprawidłowościach w kanale 1.  3.**OUT 2** – informuje o nieprawidłowościach w kanale 2.  4.**AUTO** – tryb automatyczny pracy.  5.**MANUAL** – tryb manualny pracy.  6.**Pokrętło 0%-100%** - wybór stopnia otwarcia wlotów powietrza.| 

# Komunikaty błędów i ostrzeżeń

Komunikaty błędów służą do poinformowania użytkownika o nieprawidłowościach w pracy urządzenia. Poniżej zamieszczone są możliwe komunikaty błędów:
 -  Kontrolka POWER – nie świeci na zielono – brak zasilania sieciowego.
 -  Kontrolka CHECK – pulsuje na żółto – na wyjściach podano sygnał z potencjometru.
 -  Kontrolka OUT 1 – świeci na czerwono - wykrycie nieprawidłowości (brak sygnału sterującego, zwarcie na wyjściu lub zwarcie na szynie 24VDC) w kanale pierwszym.
 -  Kontrolka OUT 2 – świeci na czerwono - wykrycie nieprawidłowości (brak sygnału sterującego, zwarcie na wyjściu lub zwarcie na szynie 24VDC) w kanale drugim.

# Uwagi i ostrzeżenia  

:::danger 
W trakcie instalowania urządzenia, dopływ energii elektrycznej należy bezwzględnie odłączyć, ponieważ napięcie na niektórych podzespołach jest niebezpieczne dla życia i zdrowia. Zaleca się powierzenie instalacji wykwalifikowanej osobie.
:::

 - Aby uniknąć problemów z eksploatacją urządzenia, wymagane jest zapoznanie się z instrukcją przed przystąpieniem do instalacji oraz użytkowania. Nie wolno ingerować w konstrukcję, bądź przeprowadzać samodzielnych napraw. Dotyczy to w szczególności dokonywania zmian elementów i podzespołów.
 - Czynności konserwacyjne bądź serwisowe powinien wykonywać uprawniony personel (instalator bądź serwis firmowy). W budynkach inwentarskich z wentylacją wymuszoną wymagany jest system alarmowy. 
 - Producent urządzenia nie odpowiada za szkody spowodowane nieprawidłową instalacją, nieprawidłowym zaprogramowaniem funkcji, następstwami zdarzeń losowych oraz zewnętrznymi czynnikami. Urządzenie wymaga ustawienia parametrów zgodnie z warunkami panującymi w pomieszczeniu hodowlanym.Ustawienia te są sprawą indywidualną zależną od decyzji hodowcy. 
 - Producent urządzenia zastrzega sobie prawo do zmian w konstrukcji urządzenia oraz oprogramowania.
W skład urządzenia wchodzi bateria akumulatorów, nie należy dopuszczać do ich nadmiernego rozładowania, co może powodować uszkodzenie baterii. 
Zwarcie biegunów baterii może skutkować pożarem.  


:::caution
![alt](./img/trash.svg) Po zakończeniu użytkowania produktu nie należy wyrzucać go razem z niesortowanymi odpadami komunalnymi, lecz zutylizować w sposób zgodny z obowiązującymi przepisami (dyrektywy WEEE Unii Europejskiej 2012/19/UE).  Produkt został wykonany zgodnie z wymogami RoHS (dyrektywą Unii Europejskiej 2011/65/UE).
:::

<!-- \newpage -->
# Dane techniczne sterownika  

|Parametr                        |	OPIS      |
|:-----------                    |:---------- |
|Napięcie zasilania zmienne|	85~264VAC 47~63Hz|
|Napięcie zasilania stałe|	120~370VDC|
|Napięcie wyjściowe|	27,6VDC|
|Maksymalny prąd wyjściowy|	1,8A|
|Sprawność|	85%|
|Maksymalny prąd wyjść sterujących 0-10V|	30mA|
|Maksymalny prąd wyjścia (styku) ALARM|	3A|
|Zabezpieczenie przepięciowe wejść i wyjść|	TAK|
|Zabezpieczenie przeciwzwarciowe|	Automatyczne |
|Bateria akumulatorów|	4Ah 24V|
|Zakres temperatury pracy|	-10 +40oC|
|Wymiary urządzenia|	20x15x8 cm|
|Klasa szczelności obudowy|	IP65|

:::info
Sterownik IC-AC zawiera w zestawie:
 - kołki rozporowe - 	4 szt., 
 - akumulatory 12V 4Ah - 	2 szt., 
 - dławnicę PG13,5 -	1 szt.,
 - dławnicę PG11 -	3 szt., 
 - dławnicę PG9 -	3 szt.
:::

