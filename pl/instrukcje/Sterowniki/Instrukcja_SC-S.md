---
sidebar_position: 2

title: Instrukcja SC-S
description: Sterownik klimatu do pomieszczeń inwentarskich o dopuszczalnym prądzie wyjściowym do 5A
keywords: [eletor sc-s, sterownik wentylacji, sterownik klimatu, sterownik wentylacji chlewni, sterownik mikroklimatu, sterownik na chlewnie, wentylacjia chlewni, sterownik na ochowalnie]
---


# Sterownik SC-S

Mikroprocesorowy sterownik klimatu należący do rodziny SPEED CONTROL. Niezawodny, prosty w montażu oraz eksploatacji sterownik, z oprogramowaniem w języku polskim, angielskim, rosyjskim i niemieckim. Program sterownika umożliwia intuicyjne zadawanie parametrów: temperatur, przewietrzania, dogrzewania, poziomów min./max. wentylacji i alarmów.

**Parametry i cechy:**  
- Wentylacja I grupy:
  - max. prąd wyjścia płynnej regulacji 6A,
  - zabezpieczenie termiczne układu,
  - łagodny rozruch wentylacji,
  - kalibracja minimalnych obrotów
- Wentylacja II grupy, separowany styk do 3A (1 z opcji)
- Dogrzewanie, separowany styk do 3A (1 z opcji)
- Wyjścia alarmowe NO i NC:
  - sygnalizacja zaniku zasilania,
  - sygnalizacja przekroczonego progu temperatury min. lub max.
- 1 wejście analogowe do pomiaru temperatury
- 2 wyjścia 0-10V
- Moc pobierana przez układ < 3W
- Hermetyczna obudowa IP56
- Napięcie zasilania 230VAC 50Hz

## Instalacja sterownika  
:::danger 
W trakcie instalowania urządzenia dopływ energii elektrycznej należy bezwzględnie odłączyć, ponieważ napięcie na niektórych podzespołach jest niebezpieczne dla życia i zdrowia.  
Zaleca się powierzenie instalacji wykwalifikowanej osobie.
:::

### Wybór miejsca montażu  

Miejsce montażu należy wybierać racjonalnie uwzględniając względy łatwego dostępu do przyrządu osobom powołanym, a niedostępnym dla zwierząt oraz dzieci. Należy uwzględnić także warunki klimatyczne, tzn. urządzenie powinno pracować w zakresie temperatur -10°C do 40°C, w miejscu nienasłonecznionym. Wokoło urządzenia powinien być swobodny przepływ powietrza. W skład urządzenia wchodzi czujnik temperatury. Obowiązuje kilka zasad montażu czujnika temperatury:  
- zujnik nie powinien być montowany w miejscu bez cyrkulacji powietrza lub bezpośrednio nasłonecznionym
- czujnik nie powinien być montowany na ścianie nośnej (zewnętrznej) budynku,
- unikać bliskości urządzeń emitujących ciepło, takich jak grzejniki, lampy,
- nie należy umieszczać czujnika bezpośrednio przy drzwiach oraz otworach wentylacyjnych,
- nie należy umieszczać czujnika w miejscach dostępnych dla zwierząt,
- zalecane jest ułożenie przewodu łączącego czujnik z dala od przewodów zasilających.

### Montaż  

Urządzenie może pracować w trudnych warunkach klimatycznych. Prawidłowo zamontowany sterownik i czujnik temperatury jest odporny na działanie środowiska.
Podczas montażu trzeba zwrócić uwagę na następujące rzeczy:  
- przed skręceniem należy sprawdzić uszczelkę pokrywy,
- pokrywa musi być dokręcona na wszystkie śruby,
- stosowane przewody do połączenia sterownika powinny być okrągłe,
- po połączeniu przewodu należy dokręcić dławice tak, aby przewód został uszczelniony i unieruchomiony, zalecane jest użycie silikonu,
- niewykorzystane wyprowadzenia (dławice) należy zaślepić,
- sterownik (spodnią cześć obudowy) mocujemy do płaskiej ściany 4 kołkami rozporowymi.

## Połączenie elektryczne  

:::danger 
Przed podłączeniem układu należy się upewnić, czy zasilanie jest wyłączone!
:::

Przed przystąpieniem do połączenia sterownika należy odkręcić i zdjąć pokrywę. Wprowadzamy przewody przez gumowe dławice i możemy przystąpić do ich łączenia. Zaciski sterownika przestawione są na poniższym rysunku.

![Połączenie](./img/Sc-s2.png)

**Złącze AC 230V** łączymy z zasilaniem (rozdzielnią). Wymagane jest zastosowanie wyłącznika nadprądowego 1P-B6 oraz ograniczników przepięć typu T1 T2. Dobrą praktyką przy łączeniu kilku urządzeń jest pogrupowanie sterowników na różnych „fazach” (L1, L2, L3), celem równomiernego obciążenia linii zasilającej.  
**Złącze FAN** należy połączyć bezpośrednio z wentylatorem, w przypadku sterowania kilkoma wentylatorami sumaryczne obciążenie nie może przekraczać 6A, każdy wentylator musi być osobno zabezpieczony. Nie należy wyprowadzać PE oraz N z zasilania (rozdzielni), koniecznie należy je połączyć z wyprowadzeniami sterownika.  
**Złącze FUNCTION** wyjście przekaźnikowe separowane, maksymalny prąd styku to 6A (wymagany zewnętrzny wyłącznik nadprądowy 1P-B6 w przypadku sterowania bezpośredniego obciążeniem),
wykorzystane może być jako:  
- **Dogrzewanie** – styk załącza się przy spodku temperatury mierzonej poniżej nastawy.  
- **Wentylacja 2 grupy lub układów zraszania** – styk załącza się, gdy temperatura mierzona jest wyższa od sumy temperatury zadanej i pasma wentylacji.  styk załącza się, gdy temperatura mierzona jest wyższa od sumy temperatury zadanej i pasma wentylacji.  

Poniższy rysunek przedstawia sposób połączenia wentylatora 2 grupy lub nagrzewnicy.  

![Druga grupa](./img/2grupa.png)

**Złącze ALARM** to separowane wyjścia NC, C i NO służące do połączenia z centralką alarmową. Alarm załącza się w następujących przypadkach:  
- temperatura jest za niska lub za wysoka,
- uległ uszkodzeniu sterownik lub czujnik temperatury,
- zanikło napięcie zasilające sterownik;
- wystąpiła nieprawidłowa praca sterownika (np. przegrzanie sterownika)  

![Alarm](./img/alarmsc-s.png)  

**Złącze V1 0-10V** służy do połączenia modułów rozszerzających moc lub wentylatorów z wbudowanym układem regulacji prędkości. Napięcie na tym zacisku jest proporcjonalne do poziomu wentylacji.  
**Złącze V2 0-10V** służy do połączenia siłownika otwierającego klapy dolotowe powietrza.  
**Złącze SENSOR** łączymy z 1 czujnikiem temperatury TS3 lub TS5, biegunowość nie ma znaczenia.  Dobrą praktyką jest oddalenie przewodów pomiarowych od przewodów zasilających.  
**Złącze RS-485** wykorzystywane być może do budowy systemów wentylacyjnych oraz komunikacji z komputerem PC.  

## Zasada działania  

Głównym zadaniem sterownika jest utrzymanie temperatury w pomieszczeniu hodowlanym na poziomie ustalonym przez hodowcę. Należy pamiętać, że sterownik jest jedynie narzędziem, które ma pomóc w zapewnieniu optymalnych warunków klimatycznych w pomieszczeniu hodowlanym. Nadrzędną jednak rolę w tym procesie pełni hodowca, który powinien dostosowywać ustawienia urządzenia do zmieniających się warunków klimatycznych panujących na dworze, a przede wszystkim do wymagań zwierząt w budynku inwentarskim oraz monitorować stan pracy urządzenia za pomocą centralki alarmowej.  

### Pierwsze uruchomienie sterownika  

:::danger
Przy pierwszym uruchomieniu sterownika należy bezwzględnie dokonać ustawienia pasma zabronionego pracy silnika.
:::

Sterownik współpracuje z wentylatorami opartymi o jednofazowy silnik asynchroniczny o maksymalnym sumarycznym poborze prądu 5A. Użytkownik po podłączeniu wybranych przez siebie wentylatorów musi dostosować je do współpracy ze sterownikiem. Innymi słowy konieczne jest ustawienie minimalnego poziomu pracy (obrotów) wentylatora. Funkcja ta nosi nazwę **„Pasmo Zabronione”** i ustawiana jest przez użytkownika jednorazowo z poziomu **„Ustawień zaawansowanych”**. Aby czynność tę wykonać prawidłowo wskazana jest pomoc drugiej osoby, która mogłaby stale obserwować zachowanie wentylatora podczas, gdy inna osoba będzie ustawiała wartość **„Pasma Zabronionego”**. Brak ustawienia pasma zabronionego może prowadzić do nieprawidłowej pracy urządzenia. Wartość **„Pasma zabronionego”** można uznać za prawidłową w momencie, gdy ciśnienie wytworzone przez wentylator zacznie minimalnie unosić klapy komina wentylacyjnego. Czynność ustawiania **„Pasma zabronionego”** należy wykonać powtórnie, gdy zmieniany jest wentylator podłączony do sterownika.  

### Okresowe przewietrzanie  

Przewietrzanie jest funkcją wykonywaną przez sterownik, która zostaje uruchomiona w momencie, gdy temperatura w pomieszczeniu spadnie poniżej temperatury zadanej. Funkcja ta zapewnia zwierzętom cykliczny dopływ świeżego powietrza. Przewietrzanie definiują 3 parametry:
- **„Czas pracy”** - określa na ile sekund ma zostać załączony wentylator,
- **„Czas przerwy”** - określa czas w sekundach postoju wentylatora,
- **„Poziom przewietrzania”** - określa moc wentylacji w „Czasie pracy”.  

Przykładowe ustawienie **60s/120s** oznacza, że wentylator załączany jest na 60s z przerwą między kolejnymi włączeniami 120s. 

Wszystkie wymienione wyżej parametry ustawiane są przez użytkownika. Należy pamiętać o kilku zasadach podczas ustawiania parametrów przewietrzania:
- przewietrzenie włączane jest tylko i wyłącznie w sytuacji, gdy temperatura w chlewni spadnie poniżej temperatury zadanej,
- podstawową funkcją przewietrzania jest zapewnienie zwierzętom cyklicznego dopływu świeżego powietrza, a nie utrzymywanie zadanej temperatury w pomieszczeniu,
- zaleca się, aby przewietrzać pomieszczenia krótko, ale często,
- należy wystrzegać się długich okresów przewietrzania, ponieważ może prowadzić to do zbyt dużych wahań temperatury,
- bezwzględnie należy dostosowywać ustawiane parametry do zachowania zwierząt i warunków panujących zarówno wewnątrz jak i na zewnątrz pomieszczenia,
- istnieje możliwość wyłączenia funkcji przewietrzania; w tej sytuacji zarówno w trybie procentowym jak i czasowym należy ustawić wartości zerowe w miejscu odpowiadającym wartości czasu przewietrzania, np.: 0/120s  

### Płynna wentylacja  

Sterownik płynnie reguluje wentylację od „Obroty minimalne” do **„Obroty maksymalne”** w zakresie od **„Temperatury zadanej”** do sumy **„Temperatur zadanej”** i **„Pasma wentylacji”**. Powyżej tego przedziału zostaje załączona 2 grupy wentylacji.  

![wentylacja](./img/wentylacjia.png)  

Powyżej tego przedziału zostaje załączona 2 grupy wentylacji, W przypadku, gdy temperatura w pomieszczeniu spadnie poniżej **„Temperatury zadanej”**, sterownik okresowo przewietrza pomieszczenie, przy dalszym spadku zostaje załączone dogrzewanie. Wszystko uzależnione jest od ustawień wprowadzonych przez użytkownika. W programie sterownika uwzględniono również współpracę z centralką alarmową, która może być aktywowana w sytuacji, gdy temperatura w chlewni odbiega od zadanych parametrów.  

## Programowanie sterownika  

Sterownik posiada pewien zbiór domyślnych ustawień, które są wpisywane do nieulotnej pamięci w dwóch przypadkach:  
1. Pierwsze uruchomienie urządzenia,  
2. Błąd w pamięci danych.  
W przypadku braku lub zaniku zasilania sterownik nie traci wcześniej wprowadzonych i zapisanych ustawień użytkownika.  

### Korzystanie z menu  

Sterownik wyposażony jest w szereg funkcji, które pozwalają dostosować go do danej aplikacji. Funkcje te pogrupowane są w menu, do którego dostęp uzyskuje się przez naciśniecie jednego z klawiszy **(„ Strzałka Prawo”, „Strzałka Lewo”)**. Zmiany parametrów dokonuje się za pomocą klawiszy **„+” i „-”**, edytowany parametr zostanie automatycznie zapisany w nieulotnej pamięci po upływie **30s** od ostatnio wciśniętego przycisku.  

### Funkcje menu podstawowego  

| MENU                       | Opis | 
|:---:                       |:---|
|Temperatura  <br />20,8°C W16% A  |**„Tryb informacyjny”** - normalnej pracy. Na wyświetlaczu znajduje się wskazanie aktualnej temperatury oraz gdy uruchomiony jest wentylator wartość poziomu wentylacji. Znaczenie dodatkowych symboli: A-oznacza załączony alarm, D  - oznacza załączone ogrzewanie, W - oznacza dodatkową wentylację| 
|Temp. zadana  <br />20,0°C        |**„Temperatura zadana”** – wartość temperatury określającej początek procesu płynnej wentylacji.   | 
|Przewietrzanie  <br />20s / 200s  |**„Przewietrzanie”** – ustawiane są dwa wartości czasów 1 „Czas pracy”, 2 „Czas przerwy” pomiędzy kolejnymi cyklicznymi załączeniami wentylacji.| 
|Poziom przewie.  <br />20%        |**„Poziom przewietrzania”** - poziom wentylacji w czasie pracy przewietrzania   | 
|Alarm minimum  <br />12,0°C       |**„Alarm minimum”** - określa bezwzględną minimalną temperaturę, przy której zostanie załączony alarm. 
|Alarm maximum  <br />28,0°C       |**"Alarm maximum"** - określa bezwzględną maksymalną temperaturę, przy której zostanie załączony alarm.  | 
|Dogrzewanie  <br />12,0°C         |W zależności od konfiguracji realizowane są funkcje: **„Dogrzewania”** - styk załącza się, jeśli temperatura spadnie poniżej wskazania. | 
|Wentylacja 2 stopnia  <br />25,0  |**„Wentylacja 2 stopnia”** - styk załącza się gdy temperatura mierzona przekracza sumę temperatury zadanej i pasma wentylacji. | 
|Pasmo wentylacji  <br />5,0°C     |**„Pasmo wentylacji”** - określa szybkość reakcji sterownika (zmiany poziomu wentylacji od minimum 1 do maksimum 1) na wzrastającą temperaturę. | 
|Obroty minimalne  <br />1%        |**„Obrotów minimalnych”** – jest to stan, w którym urządzenie pozostaje przez czas nieokreślony, podając na wyjście napięcie o zadanej wartości. Służy do kalibracji urządzenia z silnikiem i mechanizmem klap.   | 
|Obroty maxymalne  <br />100%      |**„Obrotów maksymalnych”** – jest to stan, w którym urządzenie pozostaje przez czas nieokreślony, podając na wyjście napięcie o zadanej wartości. Służy do ograniczenia mocy przeznaczanej na wentylację| 

### Menu zaawansowanego  

Menu zaawansowane przeznaczone jest głównie dla instalatorów, pozwala dopasować sterownik do instalacji oraz wentylatora. Przejście do ustawień zaawansowanych dokonuje się przez przyciśniecie i przytrzymanie dwóch klawiszy menu, przez czas około 10s.  

| MENU                                 | Opis| 
|:---:                                 |:--- |
|Brak ustawien  <br />zaawansowanych   |Komunikat ten świadczy to że sterownik nie został skalibrowany z wentylacją i jego działanie może być nieprawidłowe Konieczne jest wejście do menu zaawansowanego i przeprowadzenie ustawień „Pasma zabronionego”.|
|Ustawienia <br />Zaawansowane         |Sygnalizacja wejścia w ustawienia zaawansowane. | 
|Oprogramowanie Ver:  <br />1907       |Informacja o wersji oprogramowania.| 
|Pasmo zabronione  <br />1000 us       |Kalibracja minimalnych obrotów wentylatorów dołączonych bezpośrednio do sterownika, parametr ten odpowiada poziomowi wentylacji „1%”|  
|Funkcja stykow  <br />Dogrzewanie     |Wybór funkcji styków:  <br />• Dogrzewanie (domyślne)<br />• 2 grupa wentylacji | 
|Przewietrzanie  <br />Czasowe         |Wybór rodzaju przewietrzania: <br />• Czasowe (domyślne) <br />• Procentowe| 
|Zakres V1  <br />od 2,0 do 10,0       |Regulacja zakresu zmian napięcia na wyjściu V1 0÷10V. Nastawy dotyczą minimalnej i maksymalnej wartości napięcia. Regulację stosuje się w celu dopasowania sterownika do rozszerzenia mocy lub falownika.| 
|Inwersja V1  <br />Nie                |Aktywacja powoduje odwrócenie charakterystyki wyjścia V1. Napięcie będzie spadało wraz ze wzrostem poziomu wentylacji w zadanym przez min.-max. przedziale. Sygnał na wyjściu V1 będzie typu 10-0V.| 
|Odciecie V1  <br />Nie                |Aktywacja powoduje podawaniem na wyjście  V1 0-10V poziomu 0V a nie ustawionej wartości minimalnej, gdy poziom wentylacji wyniesie 0%.| 
|Zakres V2  <br />od 2,0 do 10,0       |Regulacja zakresu zmian napięcia na wyjściu V2 0÷10V. Nastawy dotyczą minimalnej i maksymalnej wartości napięcia. Regulację stosuje się w celu kalibracji układu klap.|
|Inwersja V2  <br />Nie      	       |Aktywacja powoduje odwrócenie charakterystyki wyjścia V2. Napięcie będzie spadało wraz ze wzrostem poziomu wentylacji w zadanym przez min.-max. przedziale. Sygnał na wyjściu V2 będzie typu 10-0V.|
|Kalibracja temp  <br />21,0°C -> 22,0°C|Kalibracja czujnika temperatury umożliwia przeskalowanie odczytanej wartości.|
|Softstart  <br />50%      	           |Określenie poziomu wentylacji przy każdym starcie wentylatora, na wskazaną wartość rozpędzany jest wentylator po czym przechodzi do zadanego poziomu.| 
|Jezyk  <br />Polski    	           |Wybór języka menu: polski, angielski, niemiecki, rosyjski|
|Wyjscie                               |Wyjście z menu zaawansowanego za pomocą klawisza „+”, wprowadzone zmiany zostaną zapisane w nieulotnej pamięci.|

### Komunikaty błędów i ostrzeżeń  

Komunikaty błędów służą do poinformowania użytkownika o nieprawidłowościach w pracy sterownika. Poniżej zamieszczone są możliwe komunikaty błędów.  

|BŁĄD                                    | OPIS |
|:---:                                   |:--- |
|Alarm  <br />Przeciazeniowy 	         |Alarm przeciążeniowy, aktywowany przy 75°C. Urządzenie wstrzymuje pracę do czasu ostygnięcia.|
|CZUJNIK ROZWARTY!  <br />Sprawdz czujnik|Czujnik rozwarty, sygnalizuje uszkodzenie czujnika lub przewodu połączeniowego.|
|CZUJNIK ZWARTY!  <br />Sprawdz czujnik  |Czujnik zwarty, sygnalizuje uszkodzenie czujnika lub przewodu połączeniowego.|
|Zanik  <br />Zasilania                  |Zanik zasilani, zbyt niskiej wartości napięcie zasilania, zła częstotliwość lub mocno odkształcone napięcie zasilania.| 

## Uwagi i ostrzeżenia  

:::danger 
W trakcie instalowania urządzenia dopływ energii elektrycznej należy bezwzględnie odłączyć, ponieważ napięcie na niektórych podzespołach jest niebezpieczne dla życia i zdrowia. Zaleca się powierzenie instalacji wykwalifikowanej osobie.
:::

- Aby uniknąć problemów z eksploatacją urządzenia wymagane jest zapoznanie się z instrukcją przed przystąpieniem do instalacji oraz użytkowania.  
- Nie wolno ingerować w konstrukcję, bądź przeprowadzać samodzielnych napraw. Dotyczy to w szczególności dokonywania zmian elementów i podzespołów.  
- Czynności konserwacyjne bądź serwisowe powinien wykonywać uprawniony personel (instalator bądź serwis firmowy). W budynkach inwentarskich z wentylacją wymuszoną wymagany jest system alarmowy. Producent urządzenia nie odpowiada za szkody spowodowane nieprawidłową instalacją, nieprawidłowym zaprogramowaniem funkcji, następstwami zdarzeń losowych oraz zewnętrznymi czynnikami.  
- Sterownik wentylacji wymaga ustawienia parametrów zgodnie z warunkami panującymi w pomieszczeniu hodowlanym. Ustawienia te są sprawą indywidualną zależną od decyzji hodowcy. Producent urządzenia zastrzega sobie prawo do zmian w konstrukcji urządzenia oraz oprogramowania.  


:::caution
![alt](./img/trash.svg) Po zakończeniu użytkowania produktu nie należy wyrzucać go razem z niesortowanymi odpadami komunalnymi, lecz zutylizować w sposób zgodny z obowiązującymi przepisami (dyrektywy WEEE Unii Europejskiej 2012/19/UE). <br />Produkt został wykonany zgodnie z wymogami RoHS (dyrektywą Unii Europejskiej 2011/65/UE).
:::

<!-- \newpage -->
## Dane techniczne sterownika  

|Parametr                        |	OPIS      |
|:-----------                    |:---------- |
|Napięcie zasilania|	230VAC 50Hz|
|Maksymalny prąd wyjścia płynnej regulacji FAN|	6A|
|Zakres regulacji napięcia wyjściowego|	70V ÷ (Uz-5)V|
|Maksymalny prąd wyjścia (styku) ALARM|	3A|
|Maksymalny prąd wyjścia (styku) FUNCTION|	3A|
|Zakres temperatury pracy|	-20 +40oC|
|Zakres pomiarowy temperatury|	0 +50°C|
|Rozdzielczość pomiaru temperatur|	0,1°C|
|Wykrywanie uszkodzeń czujnika temperatury|	TAK|
|Maksymalna liczba czujników analogowych|	1|
|Dokładność pomiaru temperatury – wejście analogowe|	1°C|
|Zależność pomiaru od rezystancji przewodów – wejście analogowe|	15,8Ω/°C|
|Wytrzymałość na przepięcia (max E)|	210J|
|Zabezpieczenie przeciążeniowe|	75°C|
|Wymiary urządzenia|	20x15x8 [cm]|
|Klasa szczelności obudowy|	IP56|
  


:::info
Sterownik SPEED CONTROL SERVOMOTOR zawiera w zestawie:
- 1 czujnik temperatury + akcesoria,
- 4 kołki rozporowe,
- 1 bezpiecznik 10A.
:::

