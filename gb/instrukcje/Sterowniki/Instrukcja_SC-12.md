---
sidebar_position: 2
---

# Sterownik SC-12

Mikroprocesorowy sterownik klimatu należący do serii SPEED CONTROL. Wszechstronność urządzenia gwarantuje bogata ilość wejść/wyjść układu oraz intuicyjne oprogramowanie w języku polskim oraz angielskim. Program sterownika poza podstawowymi nastawami temperatur, przewietrzania, dogrzewania, poziomów min./max. wentylacji i alarmów, umożliwia testowanie oraz zapis kalibracji urządzeń wykonawczych współpracujących ze sterownikiem.

## Parametry i cechy:
- Wentylacja I grupy: **max. prąd wyjścia płynnej regulacji 12A,zabezpieczenie termiczne układu, łagodny rozruch wentylacji – soft start, przekaźnik obejściowy przy pełnym wysterowaniu, kalibracja minimalnych obrotów, program oszczędzania energii z systemem klap otwieranych z wyprzedzeniem.**
- Wentylacja II grupy, separowany styk do 6A.
- Dogrzewanie, separowany styk do 6A
- Wyjścia alarmowe NO i NC: **sygnalizacja zaniku zasilania,sygnalizacja przekroczonego progu temperatury min. lub max.,wbudowany sygnalizator akustyczny.**
- Niezależne 3 wyjścia 0..10V:**współpraca z modułami rozszerzeń, sterowanie systemem klap, regulacja ogrzewaniem o zmiennej wydajności.**
- Dwa wejścia analogowe do pomiaru temperatury.
- Cyfrowy port do pomiaru temperatury (do 4 czujników).
- Dwa wyjścia przekaźnikowe funkcyjne (do wyboru):**współpraca z siłownikami liniowymi, III i IV grupa wentylacji**
- Dwa wejścia analogowe 0-10V.
- Zasilanie do potencjometru DC 10V.
- Zasilanie dodatkowe DC 12V.
- Możliwość współpracy z komputerem do 1200m.
- Moc pobierana przez układ <10W.
- Hermetyczna obudowa IP65.
- Napięcie zasilania 230VAC 50Hz.

## Instalacja sterownika
:::danger 
 W trakcie instalowania urządzenia dopływ energii elektrycznej należy bezwzględnie odłączyć, ponieważ napięcie na niektórych podzespołach jest niebezpieczne dla życia i zdrowia. Zaleca się powierzenie instalacji wykwalifikowanej osobie.

Ta akcja jest niebezpieczna

:::
## Wybór miejsca montażu
Miejsce montażu należy wybierać racjonalnie uwzględniając względy łatwego dostępu do przyrządu osobom powołanym, a niedostępnym dla zwierząt oraz dzieci. Należy uwzględnić także warunki klimatyczne, tzn. urządzenie powinno pracować w zakresie temperatur -10°C do 40 °C, w miejscu nienasłonecznionym. Wokoło urządzenia powinien być swobodny przepływ powietrza. W skład urządzenia wchodzi czujnik temperatury. Obowiązuje kilka zasad montażu czujnika temperatury:
- czujnik nie powinien być montowany w miejscu bez cyrkulacji powietrza lub bezpośrednio nasłonecznionym,
- czujnik nie powinien być montowany na ścianie nośnej (zewnętrznej) budynku,
- unikać bliskości urządzeń emitujących ciepło, takich jak grzejniki, lampy,
- nie należy umieszczać czujnika bezpośrednio przy drzwiach oraz otworach wentylacyjnych,
- nie należy umieszczać czujnika w miejscach dostępnych dla zwierząt,
- zalecane jest ułożenie przewodu łączącego czujnik z dala od przewodów zasilających.

## Montaż
Urządzenie może pracować w agresywnych warunkach klimatycznych. Prawidłowo zamontowany sterownik i czujnik temperatury jest odporny na szkodliwe działanie środowiska.
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

Ta akcja jest niebezpieczna

:::
Przed przystąpieniem do połączenia sterownika należy odkręcić i zdjąć pokrywę. Wprowadzamy przewody przez gumowe dławice i możemy przystąpić do ich łączenia. Zaciski sterownika przestawione są na poniższym rysunku.

![Docs Version Dropdown](./img/Sc-s2.png)

**Złącze AC 230V** łączymy z zasilaniem (rozdzielnią). Wymagane jest zastosowanie wyłącznika nadprądowego 1P-B6 oraz ograniczników przepięć typu T1 T2. Dobrą praktyką przy łączeniu kilku urządzeń jest pogrupowanie sterowników na różnych „fazach” (L1, L2, L3), celem równomiernego obciążenia linii zasilającej.
**Złącze FAN** należy połączyć bezpośrednio z wentylatorem, w przypadku sterowania kilkoma wentylatorami sumaryczne obciążenie nie może przekraczać 6A, każdy wentylator musi być osobno zabezpieczony. Nie należy wyprowadzać PE oraz N z zasilania (rozdzielni), koniecznie należy je połączyć z wyprowadzeniami sterownika.
**Złącze FAN 2** wykorzystane może być do połączenia wentylatorów 2 grupy lub układów zraszania. Wyjście jest separowane, maksymalny prąd styku to 6A (wymagany zewnętrzny wyłącznik nadprądowy typu 1P-B6 w przypadku sterowania bezpośredniego obciążeniem), styk załącza się, gdy temperatura mierzona jest wyższa od sumy temperatury zadanej i pasma wentylacji.
**Złącze HOT** wykorzystane może być do połączenia nagrzewnicy. Wyjście jest separowane, maksymalny prąd styku to 6A (wymagany zewnętrzny wyłącznik nadprądowy 1P-B6 w przypadku sterowania bezpośredniego obciążeniem), styk załącza się przy spodku temperatury mierzonej poniżej nastawy.
**Złącze ALARM** o separowane wyjścia NC, C i NO służące do połączenia z centralką alarmową. Alarm załącza się w następujących przypadkach:
- temperatura jest za niska lub za wysoka,
- uległ uszkodzeniu sterownik lub czujnik temperatury,
- zanikło napięcie zasilające sterownik,
- wystąpiła nieprawidłowa praca sterownika (np. przegrzanie sterownika)
Poniższy rysunek przedstawia sposób połączenia wentylatora z centralką alarmową.

![Docs Version Dropdown](./img/2grupa.png)

**Złącze FUNC1 i FUNC2** służy do połączenia windy do otwierania wlotów powietrza opartej na silniku prawo/lewo. Przekaźnik FUNC1 załącza prąd dla siłownika a FUNC2 przełącza kierunek obrotów silnika. Przykładowy schemat połączenia widy (wymagany zewnętrzny wyłącznik nadprądowy 1P-B6):
Dezaktywując funkcję windy wyjścia FUNC1 i FUNC2 pracują jako styki kolejno 3 i 4 grupy wentylacji.

![Docs Version Dropdown framed](./img/alarmsc-s.png)

**Złącze 12V** przeznaczone jest do zasilania zewnętrznych czujników.
**Złącze V1 0-10V** służy do połączenia modułów rozszerzających moc. Napięcie na tym zacisku jest proporcjonalne do poziomu wentylacji.
**Złącze V2 0-10V** służy do połączenia siłownika otwierającego klapy dolotowe powietrza.
**Złącze V3 0-10V** służy do połączenia układu grzewczego o płynnie regulowanej wydajności. Napięcia na tym wyjściu wzrasta proporcjonalnie do spadku temperatury począwszy od temperatury dogrzewania.
**Złącze 10V** służy do zasilania potencjometru windy lub innych układów typu 0-10V.
**Złącze SENS1 (SENS2)** łączymy z 1 czujnikiem temperatury TS3 lub TS5, biegunowość nie ma znaczenia. W przypadku połączenia 2 czujników naraz mierzone temperatury są uśredniane. Dobrą praktyką jest oddalenie przewodów pomiarowych od przewodów zasilających.
**Złącze 1-WIRE** wykorzystane może być do połączenia większej liczby cyfrowych czujników temperatury, maksymalnie 4, łączonych równolegle (należy zachować odpowiednią polaryzacja). Maksymalna długość przewodu łączącego czujniki to 150m (długość nie ma wpływu na pomiar temperatury), zalecane jest użycie przewodu ekranowanego.
**Złącze RS-485** wykorzystywane być może do budowy systemów wentylacyjnych oraz komunikacji z komputerem PC.
**Złącze IN1 0-10** służy do wprowadzania sygnału sprzężenia zwrotnego od systemu wlotów powietrza – określa aktualną pozycję wlotów.
**Złącze IN2 0-10** służy do połączenia sterownika z innymi czujnikami np. wilgotności, CO2 lub pracy sterownika jako rozszerzenia mocy.
## Zasada działania
Głównym zadaniem sterownika jest utrzymanie temperatury w pomieszczeniu hodowlanym na poziomie ustalonym przez hodowcę. Należy pamiętać, że sterownik jest jedynie narzędziem, które ma pomóc w zapewnieniu optymalnych warunków klimatycznych w pomieszczeniu hodowlanym. Nadrzędną jednak rolę w tym procesie pełni hodowca, który powinien dostosowywać ustawienia urządzenia do zmieniających się warunków klimatycznych panujących na dworze, a przede wszystkim do wymagań zwierząt w budynku inwentarskim oraz monitorować stan pracy urządzenia za pomocą centralki alarmowej.

## Pierwsze uruchomienie sterownika
:::danger 
 Przy pierwszym uruchomieniu sterownika należy bezwzględnie dokonać ustawienia pasma zabronionego pracy silnika.

:::
Sterownik współpracuje z wentylatorami opartymi o jednofazowy silnik asynchroniczny o maksymalnym sumarycznym poborze prądu 12A. Użytkownik po podłączeniu wybranych przez siebie wentylatorów musi dostosować je do współpracy ze sterownikiem. Innymi słowy konieczne jest ustawienie minimalnego poziomu pracy (obrotów) wentylatora. Funkcja ta nosi nazwę **„Pasmo Zabronione”** i ustawiana jest przez użytkownika jednorazowo z poziomu **„Ustawień zaawansowanych”**. Aby czynność tę wykonać prawidłowo wskazana jest pomoc drugiej osoby, która mogłaby stale obserwować zachowanie wentylatora podczas, gdy inna osoba będzie ustawiała wartość **„Pasma Zabronionego”** (fabrycznie wartość ta wynosi 0). Brak ustawienia pasma zabronionego może prowadzić do nieprawidłowej pracy urządzenia. Wartość **„Pasma zabronionego”** można uznać za prawidłową w momencie, gdy ciśnienie wytworzone przez wentylator zacznie minimalnie unosić klapy komina wentylacyjnego. Czynność ustawiania **„Pasma zabronionego”** należy wykonać powtórnie, gdy zmieniany jest wentylator podłączony do sterownika.
## Okresowe przewietrzanie
Przewietrzanie jest funkcją wykonywaną przez sterownik, która zostaje uruchomiona w momencie, gdy temperatura w pomieszczeniu spadnie poniżej temperatury zadanej. Funkcja ta zapewnia zwierzętom cykliczny dopływ świeżego powietrza. W menu Przewietrzanie możemy znaleźć 3 parametry:
- **„Czas pracy”** - określa na ile minut ma zostać załączony wentylator;
- **„Czas przerwy”** - określa czas postoju wentylatora;
- **„Poziom przewietrzania”** - określa moc wentylacji w „Czasie pracy”.
Wszystkie wymienione wyżej parametry ustawiane są przez użytkownika. Należy pamiętać o kilku zasadach podczas ustawiania parametrów przewietrzania:
- przewietrzenie włączane jest tylko i wyłącznie w sytuacji, gdy temperatura w chlewni spadnie poniżej temperatury zadanej,
- podstawową funkcją przewietrzania jest zapewnienie zwierzętom cyklicznego dopływu świeżego powietrza, a nie utrzymywanie zadanej temperatury w pomieszczeniu,
- zaleca się, aby przewietrzać pomieszczenia krótko, ale często,
- należy wystrzegać się długich okresów przewietrzania, ponieważ może prowadzić to do zbyt dużych wahań temperatury,
- bezwzględnie należy dostosowywać ustawiane parametry do zachowania zwierząt i warunków panujących zarówno wewnątrz jak i na zewnątrz pomieszczenia,

## Sposób działania urządzenia
Sterownik płynnie reguluje wentylację od **„Min.1” do „Max.1”** w zakresie od **„Temperatury zadanej”** do sumy **„Temperatur zadanej”** i **„Pasma wentylacji 1gr.”**. Powyżej tego przedziału zostaje załączona 2 grupy wentylacji, a 1 grupa zmieni poziom na **„Min.2”**, przy dalszym wzroście temperatury wentylacji będzie rosła do **„Max.2”**, na końcu zakresu **„Pasma wentylacji 2 gr.”**. W przypadku, gdy **„Pasmo wentylacji 2 gr.”** jest ustawione na zero a wentylacja pracuje na **„Max.1”**, załączy się 2 grupa wentylacji a dalszy wzrost temperatury nie wprowadza już żadnych zmian wentylacji (wykropkowana część wykresu). W przypadku, gdy temperatura w pomieszczeniu spadnie poniżej **„Temperatury zadanej”**, sterownik okresowo przewietrza pomieszczenie, przy dalszym spadku zostaje załączone dogrzewanie. Wszystko uzależnione jest od ustawień wprowadzonych przez użytkownika. W programie sterownika uwzględniono również współpracę z centralką alarmową, która może być aktywowana w sytuacji, gdy temperatura w chlewni odbiega od zadanych parametrów. 

![Docs Version Dropdown](./img/wentylacjia.png)  

## Programowanie sterownika
Sterownik posiada pewien zbiór domyślnych ustawień, które są wpisywane do nieulotnej pamięci w dwóch przypadkach:
1. Pierwsze uruchomienie urządzenia,
2. Błąd w pamięci danych.
W przypadku braku lub zaniku zasilania sterownik nie traci wcześniej wprowadzonych i zapisanych ustawień użytkownika.
## Panel przedni – wskaźniki, przyciski i wyświetlacz
    1. Czerwona kontrolka sygnalizująca przekroczenie maksymalnej dopuszczalnej temperatury.
    2. Czerwona kontrolka sygnalizująca przekroczenie minimalnej dopuszczalnej temperatury.
    3. Żółta kontrolka sygnalizująca dogrzewanie.
    4. Żółta kontrolka sygnalizująca wentylację 2 grupy.
    5. Zielona kontrolka sygnalizująca ręczne zadawanie poziomu wentylacji.
    6. Zielona kontrolka sygnalizująca pracę komunikacji RS485.
    7. Wyświetlacz menu, w normalnym stanie pracy przedstawia temperaturę.
    8. Bargraf sygnalizujący poziom wentylacji.
    9. Klawisz poruszania się w górę w menu lub zmiany wartości parametru.
    10. Klawisz ESC - wyjścia z menu lub danego parametru bez zapamiętania wartości.
    11. Klawisz OK - wejścia do menu lub zatwierdzenia (zapamiętania) danego parametru.
    12. Klawisz poruszania się w dół w menu lub zmiany wartości parametru.

![Docs Version Dropdown](./img/wentylacjia.png)  

## Korzystanie z menu
Sterownik wyposażony jest w szereg funkcji, które pozwalają dostosować go do danej aplikacji. Funkcje te pogrupowane są w menu, do którego dostęp uzyskuje się przez naciśniecie jednego z klawiszy **(„+”, „-” lub „OK”)**. Klawisze **„+”** i **„-”** służą do wyboru funkcji, a edycję, zapis danych lub kolejne zagłębienie można wykonać za pomocą klawisza **„OK”**. Klawisz **„Esc”** służy do powrotu do nadrzędnego menu lub rezygnacji z zapisu danego parametru naciśnij.
## Funkcje menu podstawowego
| MENU                          | Opis       | 
|:-----------                   |:---------- |
| Temperatura 20,8o C W16% A    | „Tryb informacyjny” - normalnej pracy. Na wyświetlaczu znajduje się wskazanie aktualnej           temperatury oraz gdy uruchomiony jest wentylator wartość poziomu wentylacji. Znaczenie dodatkowych symboli:A-oznacza załączony alarm,D  - oznacza załączone ogrzewanie, W - oznacza dodatkową wentylację| 
|   Temp. zadana   20,0o C      | „Temperatura zadana” – Określa temperaturę, od której rozpoczyna się proces wentylacji płynnej. Należy dobrać odpowiednią wartość w zależności od rodzaju zwierząt inwentarskich.
.| 
| Przewietrzanie     | „Przewietrzanie” – ustawiane są dwa wartości czasów 1 „Czas pracy” Określa liczbę minut pracy wentylacji, 2 „Czas przerwy” Określa liczbę minut przestoju wentylacji pomiędzy kolejnymi cyklami pracy, 3 „Poziom przewietrzania” - Określa siłę wentylacji w czasie pracy przewietrzania.| 
| Alarm | 1.„Alarm aktywny Tak ” - Aktywacja/Dezaktywacja styku alarmowego, aby sterownik nie wystawiał sygnału alarmowego na wyjściu (do centralki alarmowej) wybieramy „NIE” w menu. 2.„Temp. Min. 15,0o C ” - Określa bezwzględną minimalną temperaturę, przy której zostanie załączony alarm. 
3."Temp. Max. 25,0o C" - Określa bezwzględną maksymalną temperaturę, przy której zostanie załączony alarm. 4.„Sygnal alarmu Tak” - Aktywacja/Dezaktywacja sygnału akustycznego wewnątrz sterownika. | 
|    Wentylacja        | 1.**Pasmo went. 1 5,0o C**   - Określa szybkość reakcji sterownika (zmiany poziomu wentylacji od minimum 1 do maksimum 1) na wzrastającą temperaturę, 2.**Poziom min. 1 1 %** - Określa poziom wentylacji odpowiadający temperaturze zadanej. 3.**Poziom max. 1 100 %**-Określa stały poziom wentylacji dla temperatury przekraczającej zakres płynnej regulacji, gdy „Pasmo went. 2gr.” = 0, w przeciwnym wypadku maksymalny poziom regulowanej wentylacji dla temperatury będącej sumą T. zadanej i pasma 1 grupy. 4.**Pasmo went. 2 0,0o C**-Określa szybkość reakcji sterownika (zmiany poziomu wentylacji od minimum 2 do maksimum 2) na wzrastającą temperaturę dla 2 grupy. Funkcja nieaktywna, gdy pasmo równa się zeru. 5.**Poziom min. 2 1 %**-Określa minimalny poziom wentylacji 1 grupy w punkcie załączenia się styków 2 grupy.  6.**Poziom max. 2 100 %**-Określa stały poziom wentylacji dla temperatury przekraczającej zakres płynnej regulacji, gdy 2 grupa jest załączona. 7.**Grupa 3  5,0o C**-Określa stały poziom wentylacji dla temperatury przekraczającej zakres płynnej regulacji, gdy 2 grupa jest załączona. 8.**Grupa 4 7,0o C**-Określa temperaturę względem temperatury zadanej, załączenia się 4 grupy wentylacji (funkcja windy musi być dezaktywowana).| 
|    Dogrzewanie  |  **- „Temp. Dogrzew. 15,0o C”**-Określa temperaturę załączenia dogrzewania. **„Pasmo dogrzew. 5,0o C ”** -Określa proporcję mocy układów dogrzewających (na wyjściu V3 0-10V) w zależności od temperatury. | 

## Funkcje menu zaawansowanego
Menu zaawansowane przeznaczone jest głównie dla instalatorów, pozwala dopasować sterownik do instalacji oraz wentylatora, testować obwody, wybrać język menu. Przejście do ustawień zaawansowanych dokonuje się przez przyciśniecie i przytrzymanie dwóch klawiszy menu, przez czas około 10s. 
| MENU                          | Opis       | 
|:-----------                   |:---------- |
|Testowanie  |Funkcja ta służy sprawdzaniu poszczególnych obwodów wykonawczych sterownika, wszystkie ustawienia mają charakter chwilowy do czasu przebywania w danej pozycji menu, po naciśnięciu „ESC” lub „OK” dane wyjście powraca do stanu jaki wynika z pracy sterownika.  
**Wentylacja  0 %**  Umożliwia ręcznie wprowadzamy poziom wentylacji w celu sprawdzenia układu wentylacji. Po zatwierdzeniu funkcji zapali się zielona kontrolka (łapka)    
**Alarm     Nie** Aktywacja powoduje włączenie 2 czerwonych kontrolek, sygnału dźwiękowego oraz obwodu alarmu.    
**Dogrzewanie Nie** Aktywacja powoduje włączenie żółtej kontrolki (płomyka), oraz obwodu dogrzewania.   
**Went. 2 stopnia Nie** Aktywacja powoduje włączenie żółtej kontrolki (wentylatora), oraz obwodu 2 grupy. 
**Wyjscie V1 0,0 V  Wyjscie V2  0,0 V Wyjscie V3  0,0 V**-Test wyjść 0-10V, za pomocą klawiszy „+” lub „-” można zadać wybrane napięcie na układ kolejno: modułów rozszerzeń, klap dolotowych, płynnego dogrzewania. Funkcja szczególnie przydatna przy kalibracji Wyjście V2 klap dolotowych.    
**Winda 0** Umożliwia sprawdzanie systemu klap dolotowych „+” - otwiera wloty, „-” - zamyka wloty, na wyświetlaczu prezentowana jest aktualna pozycja siłownika odczytana z potencjometru.             
**Grupa 3 Nie**  Aktywacja powoduje włączenie obwodu 3 grupy wentylacji. (funkcja windy musi być dezaktywowana)    
**Grupa 4 Nie**  Aktywacja powoduje włączenie obwodu 4 grupy wentylacji. (funkcja windy musi być dezaktywowana)|
|Jezyk        | Wybór języka menu. Do wyboru jest język polski lub angielski. | 
|Wentylator         | 
**Pasmo Zabronione 0**- Kalibracja minimalnych obrotów wentylatorów dołączonych bezpośrednio do sterownika, parametr ten odpowiada poziomowi wentylacji „1%”. Dodatnia wartość parametru zwiększa obroty, ujemna zmniejsza,
**Modul roz. Min. 1,9 V** -Minimalne napięcie podawane na moduł rozszerzenia mocy (wyjście V1 0-10V).
**Modul roz. Max. 10,0 V** -Maksymalne napięcie podawane na moduł rozszerzenia mocy (wyjście V1 0-10V).
**Modul odciecie Nie** - Rozłączenie modułu rozszerzenia mocy, gdy jest wybrane „TAK” napięcie na wyjściu sterującym modułami rozszerzeń (V1 0-10V) spadnie do poziomu 0V a nie ustawionej wartości minimalnej, gdy poziom wentylacji wyniesie 0%.
**Inwersja  Nie**-Aktywacja powoduje odwrócenie charakterystyki wyjścia V1. Napięcie będzie spadało wraz ze wzrostem poziomu wentylacji w zadanym przez min.-max. przedziale. Sygnał na wyjściu V1 będzie typu 10-0V.| 
| Klapy dolotowe       |  **Wyprzedzenie 0,0o C**-Wcześniejsze otwarcie klap dolotowych. Zadawany parametr określa o jaką temperaturę wcześniej od „Temperatury zadanej” mają otworzyć się klapy dolotowe. 
**Domkniecie  Nie**- Aktywacja powoduje, że napięcie na wyjściu sterującym klapami dolotowymi (V2 0-10V) spadnie do poziomu 0V, a nie ustawionej wartości minimalnej. W przypadku braku wentylacji (poziom wentylacji 0%).     
**Klapy min.  1,9 V**- Minimalne napięcie podawane na klapy dolotowe (wyjście V2 0-10V).    
**Klapy max.  10,0 V**- Maksymalne napięcie podawane na klapy dolotowe (wyjście V2 0-10V).   
**Inwersja   Nie**-Aktywacja powoduje odwrócenie charakterystyki wyjścia V2. Napięcie będzie spadało wraz ze wzrostem poziomu wentylacji w zadanym przez min.-max. przedziale. Sygnał na wyjściu V2 będzie typu 10-0V. |  
| Pomiar temperatury  |   **Kalibracja **S1** 23,0o C -> 23,5o C Kalibracja **S2** 23,0o C -> 23,2o C**-Kalibracja dla wejść analogowych umożliwia przeskalowanie odczytanej temperatury z czujników S1 i S2
**Czas Usredniania 60 s**- Parametr ten deklaruje okres czas w jakim są uśredniane bieżące odczyty temperatury. Wartości średniej temperatury jest parametrem podstawowym funkcji sterownika. Zmiany stanu wyjść (wentylacji, dogrzewania, klap, kolejnych grup wentylacji, alarmów,...) są ściśle powiązane z tym parametrem i nie mogą wystąpić częściej niż określony tutaj czas. | 
| Winda      | **Kalibracja Otwar 1024 -> 853 / Kalibracja Zamkn 0 -> 324** -Kalibracja windy, jest niezbędna do prawidłowej pracy systemu wlotów powietrza. Klawisz „+” otwiera wloty, klawisz „-” zamyka wloty. Podczas otwierania wlotów parametr pozycji powinien rosnąć, podczas zamykania maleć, w innym przypadku należy zweryfikować połączenie siłownika (zasilanie i potencjometr). W kalibracji otwarcia otwieramy wloty do maximum i zatwierdzamy pozycję klawiszem „OK”. W kalibracji zamknięcia zamykamy wloty i zatwierdzamy pozycję klawiszem „OK”. Klawisz „ESC” powoduje wyjście z funkcji bez zapisu. Różnica między pozycją otwarcia a zamknięcia powinna wynosić min. 100 jednostek. 
**Dezaktywacja Nie**-Dezaktywacja zwalnia obsługę windy ze styków FUNC1 i FUNC2, styki te pełnią wtedy role wentylacji grupy 3 i 4.| 
| Soft Start               | Parametry w tej grupie menu odpowiadają za rozruch wentylacji. Załączenie się wentylacji w płynnej grupie poprzedzone jest stopniowym rozruchem do 100%, chwilą pracy na 100%  i spadkiem do wymaganego poziomu wentylacji. Sprawia to, że przy starcie wentylacji powstaje przedmuch ułatwiający otwarcie zaworów motylowych w kominach.   Wartości wyrażone są w okresach napięcia zasilającego na 1% wentylacji.  **Czas Rozbiegu 5**- Parametr określa szybkość narastania obrotów wentylacji z poziomu zerowego do maksymalnego – łagodne włączenie się wentylatorów. Wartość 0 wyłącza łagodny rozbieg.     
**Czas 100%   100**- Parametr określa czas pracy na starcie na 100% poziomu wentylacji. Ustawienie czasu rozbiegu i 100% na 0 wyłącza całkowicie przedmuch przy starcie wentylacji.  
**Czas Wybiegu 5**-  Parametr określa szybkość zmian poziomu wentylacji. | 
|Dogrzewanie              |	 **Inwersja styku Nie**-Aktywacja powoduje odwrócenie charakterystyki wyjścia HOT. Styk będzie  rozwierany wraz ze spadkiem temperatury mierzonej.      
**Histereza  0,5o C** - Określa poziom histerezy temperatury dla styku dogrzewania.    
**Praca wzgledna Nie**- Aktywacja powoduje względne zadawanie temperatury dogrzewania względem temperatury zadanej. Zmianie ulega menu podstawowe dogrzewania w którym to podaje się różnicę od temperatury zadanej.      
**Dogrzewanie min. 1,9 V** - Minimalne napięcie podawane na płynne sterowani ogrzewaniem – nagrzewnica ze zmienną wydajnością wentylatora (wyjście V3 0-10V).   
**Dogrzewanie max. 10,0 V** - Maksymalne napięcie podawane na płynne sterowani ogrzewaniem – nagrzewnica ze zmienną wydajnością wentylatora (wyjście V3 0-10V).| 
| Program 	|  **ver. 2.4  Apr 13 2018** - 	Odczyt wersji oprogramowania i daty kompilacji|

## Komunikaty błędów i ostrzeżeń

Komunikaty błędów służą do poinformowania użytkownika o nieprawidłowościach w pracy sterownika. Poniżej zamieszczone są możliwe komunikaty błędów

|BŁĄD                            |	OPIS      |
|:-----------                    |:---------- |
|Alarm     Przeciazeniowy 	     |Alarm przeciążeniowy, aktywowany przy 75°C. Urządzenie wstrzymuje pracę do czasu ostygnięcia.|
|Alarm  Brak czujnika|Sygnalizuje brak lub uszkodzenie czujnika albo przewodu połączeniowego.|

## Uwagi i ostrzeżenia 
:::danger 
 W trakcie instalowania urządzenia dopływ energii elektrycznej należy bezwzględnie odłączyć, ponieważ napięcie na niektórych podzespołach jest niebezpieczne dla życia i zdrowia. Zaleca się powierzenie instalacji wykwalifikowanej osobie.

:::
- Aby uniknąć problemów z eksploatacją urządzenia wymagane jest zapoznanie się z instrukcją przed przystąpieniem do instalacji oraz użytkowania.
- Nie wolno ingerować w konstrukcję, bądź przeprowadzać samodzielnych napraw. Dotyczy to w szczególności dokonywania zmian elementów i podzespołów. 
- Czynności konserwacyjne bądź serwisowe powinien wykonywać uprawniony personel (instalator bądź serwis firmowy). W budynkach inwentarskich z wentylacją wymuszoną wymagany jest system alarmowy. Producent urządzenia nie odpowiada za szkody spowodowane nieprawidłową instalacją, nieprawidłowym zaprogramowaniem funkcji, następstwami zdarzeń losowych oraz zewnętrznymi czynnikami. 
- Sterownik wentylacji wymaga ustawienia parametrów zgodnie z warunkami panującymi w pomieszczeniu hodowlanym. Ustawienia te są sprawą indywidualną zależną od decyzji hodowcy. Producent urządzenia zastrzega sobie prawo do zmian w konstrukcji urządzenia oraz oprogramowania.

:::caution
 Po zakończeniu użytkowania produktu nie należy wyrzucać go razem z niesortowanymi odpadami komunalnymi, lecz zutylizować w sposób zgodny z obowiązującymi przepisami (dyrektywy WEEE Unii Europejskiej 2012/19/UE).
Produkt został wykonany zgodnie z wymogami RoHS (dyrektywą Unii Europejskiej 2011/65/UE).
:::
:::caution
<div class="warning-container">
  <img src="/img/uwaga.png" alt="Icon" class="warning-corner-icon" />
  <p>
    <strong></strong> Po zakończeniu użytkowania produktu nie należy wyrzucać go razem z niesortowanymi odpadami komunalnymi, lecz zutylizować w sposób zgodny z obowiązującymi przepisami (dyrektywy WEEE Unii Europejskiej 2012/19/UE).
Produkt został wykonany zgodnie z wymogami RoHS (dyrektywą Unii Europejskiej 2011/65/UE).
  </p>
</div>
:::
:::tip
## Dane techniczne sterownika
|Parametr                        |	OPIS      |
|:-----------                    |:---------- |
|Napięcie zasilania|	230VAC 50Hz|
|Maksymalny prąd wyjścia płynnej regulacji FAN|	12A|
|Zakres regulacji napięcia wyjściowego|	70V ÷ 230V|
|Maksymalny prąd wyjścia (styku) FAN 2|	6A|
|Maksymalny prąd wyjścia (styku) HOT|	6A|
|Maksymalny prąd wyjścia (styku) ALARM|	4A|
|Maksymalny prąd wyjścia (styku) FUNC1 i FUNC2|	4A|
|Zakres temperatury pracy|	-10 +40oC|
|Zakres pomiarowy temperatury|	0 +50oC|
|Rozdzielczość pomiaru temperatur|	0,1oC|
|Wykrywanie uszkodzeń czujnika temperatury|	TAK|
|Maksymalna liczba czujników analogowych|	2|
|Dokładność pomiaru temperatury – wejście analogowe|	1oC|
|Zależność pomiaru od rezystancji przewodów – wejście analogowe|	15,8Ω/oC|
|Maksymalna liczba czujników cyfrowych|	4|
|Dokładność pomiaru temperatury – wejście cyfrowe|	0,5oC|
|Zależność pomiaru od rezystancji przewodów – wejście cyfrowe|	Brak|
|Maksymalna długość linii łączącej czujniki cyfrowe|	150m|
|Wytrzymałość na przepięcia (max E)|	210J|
|Zabezpieczenie przeciążeniowe|	75oC|
|Wymiary urządzenia|	34x29x12 [cm]|
|Klasa szczelności obudowy|	IP56|
:::


 :::info
 ```js
 Sterownik SPEED CONTROL-12 v2  zawiera w zestawie:
- 1 czujnik temperatury,
- 4 kołki rozporowe,
- 2 dławnice PG13,5.
- 3 dławnice PG11,
- 4 dławnice PG9.
```
:::


































Have **5 more minutes**? Take a look at **[versioning](../tutorial-extras/manage-docs-versions.md)** and **[i18n](../tutorial-extras/translate-your-site.md)**.

















































Anything **unclear** or **buggy** in this tutorial? [Please report it!](https://github.com/facebook/docusaurus/discussions/4610)

## What's next?

- Read the [official documentation](https://docusaurus.io/)
- Modify your site configuration with [`docusaurus.config.js`](https://docusaurus.io/docs/api/docusaurus-config)
- Add navbar and footer items with [`themeConfig`](https://docusaurus.io/docs/api/themes/configuration)
- Add a custom [Design and Layout](https://docusaurus.io/docs/styling-layout)
- Add a [search bar](https://docusaurus.io/docs/search)
- Find inspirations in the [Docusaurus showcase](https://docusaurus.io/showcase)
- Get involved in the [Docusaurus Community](https://docusaurus.io/community/support)
