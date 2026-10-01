---
sidebar_position: 4

title: Instrukcja IC-AC
description: Sterownik IC-AC wlotów powietrza do pomieszczeń inwentarskich o dopuszczalnym prądzie wyjściowym do 2A
keywords: [eletor IC-AC, sterownik wlotów powietrza, sterownik klimatu, sterownik wentylacji chlewni, sterownik mikroklimatu, sterownik na chlewnie, wentylacjia chlewni, sterownik na ochowalnie]
---


# Sterownik IC-AC

  Sterownik siłowników i wind wlotów powietrza opartych na silnikach AC prawo/lewo z potencjometrem do odczytu bieżącej pozycji. Sterownik pełni funkcję konwertera sygnału 0-10V na poziom otwarcia wlotów, dodatkowo umożliwia manualne sterowanie.

## Parametry i cechy:  
- Tryby pracy:
  - MANUAL – ręczne sterowanie za pomocą przycisków „+”, „-”;
  - AUTO – automatyczna praca w kalibrowanym zakresie proporcjonalna do sygnału 0-10V;
  - AWARYJNY – w przypadku zaniku sygnału sterującego wloty powietrza otwierają się na zadany w procentach poziom; 
- Wyjście przekaźnikowe (prawo/lewo) 2A;
- Sygnał sterujący: 0-10V;
- Możliwość inwersji sygnału sterującego;
- Pomiar położenia za pomocą potencjometru 1-100kΩ;
- Programowana histereza i czas uśredniania odczytów; 
- Hermetyczna obudowa IP56;
- Napięcie zasilania 230VAC 50Hz;
- Menu w języku: 
  - polskim
  - angielskim
  - ukraińskim
  - rosyjskim

# Instalacja sterownika  
:::danger 
W trakcie instalowania urządzenia, dopływ energii elektrycznej należy bezwzględnie odłączyć, ponieważ napięcie na niektórych podzespołach jest niebezpieczne dla życia i zdrowia. Zaleca się powierzenie instalacji wykwalifikowanej osobie.
:::

## Wybór miejsca montażu  

  Miejsce montażu należy wybierać racjonalnie, uwzględniając względy łatwego dostępu do urządzenia osobom powołanym, a niedostępnym dla zwierząt oraz dzieci. Należy uwzględnić także warunki klimatyczne, tzn. urządzenie powinno pracować w zakresie temperatur -10°C do 40 °C, w miejscu nienasłonecznionym.

# Montaż

Urządzenie może pracować w agresywnych warunkach klimatycznych. Prawidłowo zamontowane urządzenie jest odporne na szkodliwe działanie środowiska. 

  Podczas montażu trzeba zwrócić uwagę na następujące rzeczy: 
- pokrywa musi być dokręcona na wszystkie śruby,
- stosowane przewody do połączenia urządzenia powinny posiadać okrągły przekrój,
- po połączeniu przewodu należy dokręcić dławnice tak, aby przewód został uszczelniony i unieruchomiony, zalecane jest użycie silikonu,
- niewykorzystane wyprowadzenia (dławnice) należy zaślepić,
- spodnią cześć obudowy mocujemy do płaskiej ściany 4 kołkami rozporowymi.


# Połączenie elektryczne  

:::danger 
Przed podłączeniem układu należy się upewnić, czy zasilanie jest wyłączone!
:::

  Po rozkręceniu urządzenia, przedni panel należy zdjąć. W tym celu wyciągamy taśmę ze złącza, oznaczonego jako P1. Wprowadzamy przewody przez gumowe dławnice i możemy przystąpić do ich łączenia. Połączenie należy wykonać zgodnie z opisem. Zaciski sterownika przestawione są na poniższym rysunku.

![Połączenie](./img/ic-acpołącz.png)

## Zasilanie 230V AC z rozdzielni łączymy pod zaciski:  
 - **Złącze L** zacisk fazowy. Wymagane jest stosowanie wyłącznika nadprądowego (typu „S” B3) oraz ograniczników przepięć.  
 - **Złącze N** zacisk neutralny.  
 - **Złącze PE** zacisk ochronny.

## Wyjście na siłownik: 
 - **Złącze L** łączymy przewodem z złączem C, celem podania napięcia na przekaźniki.  
 - **Złącze N** zacisk neutralny siłownika.  
 - **Złącze PE** zacisk ochronny siłownika – obudowa.  
 - **Złącze NO** zacisk siłownika w kierunku otwierania wlotów powietrza.  
 - **Złącze NC** zacisk siłownika w kierunku zamykania wlotów powietrza.
 - **Złącze potencjometru** – należy połączyć zgodnie z oznaczeniem na schemacie siłownika. Polaryzacja zasilania potencjometru musi być dobrana w taki sposób, aby jednostki pozycji rosły, w przypadku otwierania wlotów powietrza, a malały w przypadku zamykania. Jeśli jest inaczej należy obrócić przewody na zasilaniu potencjometru.  
 - **Złącze In** – należy połączyć do sterownika celem podania sygnału sterującego do systemów wind.  


# Zasada działania  

  Sterownik w trybie automatycznym konwertuje sygnał sterujący z zakresu 0-10V na odpowiadającą  pozycje siłownika wlotów powietrza. Wymagane jest dokonanie kalibracji siłownika w pozycji maksymalnego otwarcia i zamknięcia wlotów powietrza. W toku kalibracji należy zwrócić uwagę, aby liny  biegnące do wlotów powietrza pozostawały w ciągłym napięciu. W czasie kalibracji przycisk „+” ma otwierać wloty, a przycisk „-” ma zamykać wloty powietrza. Jeśli jest inaczej należy zamienić przewody na zaciskach NO i NC.
  Pozycje odczytane z potencjometru, dla otwarcia i zamknięcia, powinny różnić się powyżej 100 jednostek. Jednostki pozycji odczytywane z potencjometru muszą rosnąć w przypadku otwierania wlotów, a maleć w przypadku zamykania. Jeśli jest inaczej trzeba zamienić przewody na zasilaniu potencjometru.
  Po poprawnej kalibracji sterownik jest gotowy do pracy automatycznej, będzie kontrolował pozycję siłownika. Podanie sygnału sterującego na poziomie poniżej 1,5V skutkuje ustawieniem wlotów powietrza na pozycji awaryjnej. 

## Użytkowanie 

  Sterownik wlotów powietrza może pracować w jednym z dwóch trybów: manualnym lub automatycznym. Wybrany tryb pracy jest zapamiętywany i niezależny od zaniku zasilania – sterownik po załączeniu zasilania powróci do trybu w jakim ostatnio pracował. Aktualnie wybrany tryb pracy oznaczony jest na wyświetlaczu:  
   - **MANUAL** - długie przytrzymanie "+" lub "-" powoduje załączenie trybu manualnego. W tym trybie wloty powietrza sterowane są ręcznie przyciskami: „+” - otwieranie, „-” - zamykanie.           
   - **AUTO**   - długie przytrzymanie "Esc" powoduje załączenie trybu automatycznego. W tym trybie wloty pracują automatycznie sterowane przez sygnał 0-10V ze złącza In.

## Funkcje menu podstawowego  

| MENU                       | Opis | 
|:---:                       |:---|
|MANUAL  STOP    POT 539  |  **„Tryb informacyjny”** – pracy manualnej. Wyświetlane informacje:  - **STOP** – siłownik unieruchomiony;  - **OPEN** – otwieranie wlotów powietrza po naciśnięciu przycisku „+”;  - **CLOSE** – zamykanie wlotów po naciśnięciu przycisku „-”;  - **POT 539** – parametr aktualnej pozycji siłownika określony przez potencjometr.  •Przejście do trybu pracy automatycznej po przytrzymaniu klawisza „Esc”| 
|AUTO  20 % = In 3,70 POT 511       |  **„Tryb informacyjny”**  pracy automatycznej. Wyświetlane informacje:    **20 %**  Wartość zadawanej pozycji otwarcia wlotów powietrza    **"="**   wloty powietrza na ustalonej pozycji    **"–"**    zamykanie wlotów do określonej pozycji    **"+"**    otwieranie wlotów do określonej pozycji    **In 3,70**  pomiar napięcia sterującego na zaciskach In     **POT 511**  parametr aktualnej pozycji siłownika określony przez potencjometr.  Przejście do trybu pracy manualnej po przytrzymaniu klawisza „+” lub „-” | 
|Klapy awaryjnie 30 %  |**„Klapy awaryjnie”** – zadanie wartości awaryjnego otwarcia klap (wlotów powietrza) w przypadku zaniku sygnału sterującego. Wloty powietrza otworzą się na zadany poziom w przypadku awarii sterownika lub przewodu sygnałowego.| 
|Kalibracja Otwar 671 -> 311        |**„Kalibracja otwarcia”** – kalibracja otwarcia wlotów powietrza dokonuje się przez ustawienie maksymalnego otwarcia (skrajnej pozycji) wlotów za pomocą przycisków „+” i „-”. Prezentowana pierwsza wartość reprezentuje ostatnio zapisaną nastawę, druga wartość bieżącą pozycję siłownika. Klawisz „Ok” zapisuje do pamięci wprowadzone ustawienia, „Esc” wychodzi z trybu kalibracji bez zapisu.   | 
|Kalibracja Zamkn 281 -> 311      |**„Kalibracja zamknięcia”** – kalibracja zamknięcia wlotów powietrza dokonuje się przez ustawienie minimalnej pozycji wlotów za pomocą przycisków „+” i „-”. Prezentowana pierwsza wartość reprezentuje ostatnio zapisaną nastawę, druga wartość bieżącą pozycję siłownika. Klawisz „Ok” zapisuje do pamięci wprowadzone ustawienia, „Esc” wychodzi z trybu kalibracji bez zapisu.|  
|Czas Usredniania 5 s       |**„Czas uśredniania”** – czas uśredniania sygnału sterującego ze złącza In, zabezpiecza przed oscylacjami na wejściu sterującym.  | 
|Inwersja   Nie |**„Inwersja”** – załączenie tej funkcji dopasowuje sterownik do sygnału sterującego 10-0V  | 
|Jezyk   Polski |**„Język”** – wybór języka menu  | 
|Histereza Pot  5   | **„Histereza potencjometru”** – zmiana parametru pozycji siłownika poniżej ustawionej wartości nie jest brana pod uwagę przy pozycjonowaniu. Parametr ma za zadanie likwidowanie bardzo małych ruchów siłownika oraz zakłóceń z potencjometru. | 
 

# Uwagi i ostrzeżenia  

:::danger 
W trakcie instalowania urządzenia dopływ energii elektrycznej należy bezwzględnie odłączyć, ponieważ napięcie na niektórych podzespołach jest niebezpieczne dla życia i zdrowia. Zaleca się powierzenie instalacji wykwalifikowanej osobie.
:::

- Aby uniknąć problemów z eksploatacją urządzenia, wymagane jest zapoznanie się z instrukcją przed przystąpieniem do instalacji oraz użytkowania. Nie wolno ingerować w konstrukcję, bądź przeprowadzać samodzielnych napraw. Dotyczy to w szczególności dokonywania zmian elementów i podzespołów.
- Czynności konserwacyjne bądź serwisowe powinien wykonywać uprawniony personel (instalator bądź serwis firmowy). W budynkach inwentarskich z wentylacją wymuszoną wymagany jest system alarmowy. 
- Producent urządzenia nie odpowiada za szkody spowodowane nieprawidłową instalacją, nieprawidłowym zaprogramowaniem funkcji, następstwami zdarzeń losowych oraz zewnętrznymi czynnikami.
- Urządzenie wymaga ustawienia parametrów zgodnie z warunkami panującymi w pomieszczeniu hodowlanym. Ustawienia te są sprawą indywidualną zależną od decyzji hodowcy. Producent urządzenia zastrzega sobie prawo do zmian w konstrukcji urządzenia oraz oprogramowania.  


:::caution
![alt](./img/trash.svg) Po zakończeniu użytkowania produktu nie należy wyrzucać go razem z niesortowanymi odpadami komunalnymi, lecz zutylizować w sposób zgodny z obowiązującymi przepisami (dyrektywy WEEE Unii Europejskiej 2012/19/UE).  Produkt został wykonany zgodnie z wymogami RoHS (dyrektywą Unii Europejskiej 2011/65/UE).
:::

<!-- \newpage -->
# Dane techniczne sterownika  

|Parametr                        |	OPIS      |
|:-----------                    |:---------- |
|Napięcie zasilania zmienne|	230VAC 50Hz|
|Maksymalny prąd wyjściowy|	2A|
|Filtr przeciwzakłóceniowy wyjściowy|	RC|
|Impedancja wejściowa|	100kΩ|
|Zabezpieczenie przepięciowe wejść i wyjść|	TAK|
|Zasilanie potencjometru|	10VDC|
|Maksymalny prąd wyjść potencjometru|	30mA|
|Zakres temperatury pracy|	-10 +40oC|
|Wymiary urządzenia|	20x15x8 cm |
|Klasa szczelności obudowy|	IP65|

:::info
Sterownik IC-AC zawiera w zestawie:
- 4 kołki rozporowe,
- 2 dławnicę PG11,
- 2 dławnicę PG9.
:::

