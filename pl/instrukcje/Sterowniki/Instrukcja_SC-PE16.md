---
id: sc-pe16
title: SC-PE16 — instrukcja obsługi
sidebar_label: SC-PE16
sidebar_position: 5
description: Instrukcja rozszerzenia mocy SC-PE16 — montaż, podłączenie, uruchomienie, menu i zabezpieczenia.
slug: /sc-pe16
toc_min_heading_level: 2
toc_max_heading_level: 3
---


Rozszerzenie mocy SC-PE16 służy do sterowania wentylatorami, gdy obciążenie przekracza możliwości sterownika nadrzędnego. Urządzenie reguluje napięcie zasilające wentylatory na podstawie sygnału analogowego lub nastawy ręcznej. Maksymalny sumaryczny prąd wyjścia wynosi 16 A.

![Rozszerzenie mocy ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Parametry i cechy

- tryby AUTO i MANUAL oraz uśpienie urządzenia;
- wyświetlacz graficzny i klawiatura dotykowa;
- sterowanie analogowe 2–10 V lub 4–20 mA;
- programowany próg załączenia 2. grupy wentylacji;
- byPASS przy ustalonym poziomie 100%;
- zabezpieczenie termiczne układu mocy;
- safeRUN: nastawiany poziom pracy awaryjnej;
- kalibracja minimalnego poziomu wentylacji;
- test wentylacji, przekaźnika i alarmu;
- blokada klawiatury i blokada do czyszczenia;
- język polski, angielski lub ukraiński;
- zasilanie 230 V AC, 50 Hz; obudowa IP65.

:::info Wersja oprogramowania

Opis funkcji dotyczy dostarczonego oprogramowania **ver. 2.1**. Dostępność funkcji należy odnosić do wersji zainstalowanej w urządzeniu.

:::

## Instalacja sterownika

:::danger Odłącz zasilanie

W trakcie instalowania urządzenia dopływ energii elektrycznej należy bezwzględnie odłączyć, ponieważ napięcie na niektórych podzespołach jest niebezpieczne dla życia i zdrowia. Zaleca się powierzenie instalacji wykwalifikowanej osobie.

:::

### Wybór miejsca montażu

Urządzenie należy zamontować w miejscu dostępnym dla obsługi, poza zasięgiem dzieci i zwierząt, bez bezpośredniego nasłonecznienia. Zakres temperatury otoczenia wynosi od −10°C do +40°C. Wokół obudowy i radiatora należy zapewnić swobodny przepływ powietrza. Nie zasłaniać radiatora ani nie montować urządzenia przy źródłach ciepła.

### Montaż

Spodnią część obudowy zamocować do płaskiej ściany czterema kołkami, wykorzystując otwory montażowe poza uszczelnioną komorą. Pokrywę zamontować z zawiasem dołączonym do zestawu. Przed zamknięciem sprawdzić stan i ułożenie uszczelki.

Stosować przewody o okrągłym przekroju zewnętrznym, dopasowane do dławnic. Dławnice dokręcić tak, aby uszczelniały i unieruchamiały przewód. Niewykorzystane przepusty zaślepić. Pokrywę dokręcić wszystkimi śrubami. Szczelność zależy od prawidłowego montażu obudowy i przepustów.

### Przygotowanie połączeń

Wszystkie prace wewnątrz obudowy wykonywać po odłączeniu zasilania i sprawdzeniu braku napięcia. Jeżeli zdjęcie panelu wymaga odłączenia taśmy, odłączyć ją ostrożnie i ponownie osadzić przed zamknięciem obudowy. Nie podłączać ani nie odłączać taśmy przy załączonym zasilaniu.

Przewody sygnałowe INPUT i ENABLE prowadzić oddzielnie od przewodów zasilających oraz wyjściowych. Stosować oznaczenia zacisków naniesione na konkretnym egzemplarzu urządzenia. Masa wejść sygnałowych i zacisk ochronny PE pełnią różne funkcje i nie są zamienne.

## Połączenie elektryczne

:::danger Odłącz zasilanie

Przed podłączeniem układu należy się upewnić, czy zasilanie jest wyłączone!

:::

![Zaciski zasilania, wentylatorów, GR 2, ENABLE, CAN i INPUT](./img/sc-pe16/zaciski.png)

| ZACISK | PRZEZNACZENIE |
| --- | --- |
| L, N, PE — zasilanie | Zasilanie 230 V AC, 50 Hz: L — faza, N — przewód neutralny, PE — przewód ochronny. W pierwotnej dokumentacji wskazano zabezpieczenie B20; dobór zabezpieczeń i przewodów powinien uwzględniać instalację oraz obciążenie. |
| U, N, PE — wentylatory | U — regulowane wyjście fazowe; N i PE — odpowiednie zaciski wspólne urządzenia. Suma prądów wentylatorów nie może przekraczać 16 A. Każdy wentylator wymaga osobnego zabezpieczenia. Stosować silniki dopuszczone do regulacji napięciowej. |
| GR 2: C, NO | Separowany styk przekaźnika 2. grupy. Załącza się, gdy zadany poziom wentylacji jest równy progowi „Grupa 2 wentylacji” lub wyższy. Maksymalny prąd styku według dostarczonej instrukcji: 6 A. Przy bezpośrednim sterowaniu obciążeniem dokumentacja wskazuje zewnętrzne zabezpieczenie B6. |
| INPUT: V, masa | Wejście napięciowe. Wybrać „Typ sterowania → Wejscie V”. W analizowanym programie zakres regulacji wynosi 2–10 V. Nie podłączać do tego wejścia napięcia sieciowego ani regulowanego wyjścia zasilania wentylatorów. |
| INPUT: I, masa | Wejście prądowe 4–20 mA. Wybrać „Typ sterowania → Wejscie I”. Podłączać sygnał zgodnie z oznaczeniami źródła i odbiornika. |

Do sterowania używać wybranego wejścia V albo I. SC-PE16 wymaga własnego zasilania sieciowego; wejście analogowe przekazuje jedynie wartość sterującą.

## Wejście ENABLE i komunikacja

### ENABLE: E i masa

Wejście współpracuje ze stykiem bezpotencjałowym. Zaciski E i masę wolno jedynie zwierać lub rozwierać; nie podawać zewnętrznego napięcia. Zwarcie zezwala na pracę, rozwarcie zadaje poziom 0%. Zatrzymanie podlega nastawie „Czas Wybiegu”.

Obsługę ENABLE włącza się osobno dla AUTO i MANUAL w menu „Zaawansowane → Wentylator”. Obie funkcje są fabrycznie wyłączone, więc zworka nie jest wtedy potrzebna. Rozwarcie ENABLE nie jest tym samym co uśpienie: panel pozostaje aktywny. W AUTO, przy aktywnej blokadzie ENABLE, program pomija odczyt sygnału sterującego i nie uruchamia safeRUN.

### CAN i Wi-Fi

Pozycje „Wejscie CAN” i „Wejscie WiFi” występują w menu, lecz w oprogramowaniu ver. 2.1 nie realizują sterowania: obie funkcje zwracają poziom 0%. Do uruchomienia urządzenia z tym programem wybrać wejście V lub I. Nie konfigurować instalacji w oparciu o CAN lub Wi-Fi bez potwierdzenia obsługi w zainstalowanej wersji oprogramowania.

## Zasada działania

SC-PE16 jest regulatorem mocy wykonującym polecenia sterownika nadrzędnego albo operatora. Nie mierzy temperatury pomieszczenia i nie ma własnych nastaw temperatury, przewietrzania, dogrzewania ani klap dolotowych. Procentowy poziom wentylacji oznacza wartość sterującą, a nie pomiar rzeczywistych obrotów silnika.

| SYGNAŁ NOMINALNY | ZADANY POZIOM WENTYLACJI |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

Pomiędzy wartościami granicznymi program wyznacza poziom liniowo i zaokrągla do pełnych procentów. Dla wejścia V wzrost zaczyna się po przekroczeniu odczytu 2,04 V, a dla wejścia I — 4,04 mA. Ostateczny stan wyjścia zależy również od ENABLE, rozruchu i zabezpieczenia termicznego.

## Praca awaryjna i zabezpieczenia

### safeRUN — zanik sygnału wejściowego

W trybie AUTO alarm „Wejscie” pojawia się przy odczycie napięcia poniżej 1,50 V albo prądu poniżej 2,00 mA, zależnie od wybranego wejścia. Program zadaje wtedy poziom „Praca awaryjna” w zakresie 0–100%; fabrycznie 30%. Po powrocie sygnału do progu wykrywania lub powyżej niego alarm wejścia ustępuje i urządzenie wraca do sterowania analogowego.

Zakres 1,50–2,04 V oraz 2,00–4,04 mA daje poziom 0% bez alarmu wejścia. Sygnał 0 V nie jest w tej wersji zwykłym poleceniem zatrzymania — uruchamia pracę awaryjną. Sterownik nadrzędny z wyjściem 0–10 V należy skonfigurować do zakresu 2–10 V bez odcięcia do 0 V. W MANUAL sygnał analogowy nie steruje wentylacją, a alarm wejścia jest kasowany.

### Zabezpieczenie termiczne

Alarm „Przegrzanie” zostaje ustawiony, gdy odczyt temperatury radiatora przekroczy 87°C. Kasuje się po spadku poniżej 80°C. Podczas alarmu program zmienia zadany poziom: dla wartości co najmniej 50% zadaje 100%, a dla wartości poniżej 50% zadaje 0%. Zmiana wyjścia podlega algorytmowi rozruchu i wybiegu. Zabezpieczenie nie gwarantuje ciągłej pracy wentylacji w każdym przypadku.

Przekaźnik GR 2 jest wyznaczany przed korektą termiczną: jego stan zależy od poziomu sprzed wymuszenia 0% lub 100%. Poziom pracy awaryjnej również podlega korekcie termicznej. W razie przegrzania sprawdzić warunki chłodzenia, zabrudzenie radiatora i obciążenie; prace wewnątrz obudowy zlecić uprawnionej osobie.

### byPASS i łagodny rozruch

Przy ustalonym poziomie wyjściowym 100% program załącza przekaźnik obejścia układu regulacji fazowej. Rozruch może obejmować narastanie do 100%, podtrzymanie na 100% i przejście do zadanego poziomu. Parametry „Soft Start” wpływają również na szybkość reakcji wyjścia na zmianę żądania.

## Pierwsze uruchomienie sterownika

:::warning Kalibracja wentylatorów

Uwaga! Przy pierwszym uruchomieniu urządzenia należy bezwzględnie dokonać ustawienia pasma zabronionego pracy silnika.

:::

1. Przy odłączonym zasilaniu sprawdzić podłączenie zasilania, PE, wentylatorów i sygnału analogowego. Potwierdzić dopuszczenie silników do regulacji napięciowej i sumaryczny prąd do 16 A.
2. Załączyć zasilanie. W razie propozycji wyboru języka nacisnąć OK i wybrać język. Odblokować klawiaturę przyciskiem z symbolem kłódki.
3. W „Typ sterowania” wybrać „Wejscie V” albo „Wejscie I”. Ustawić poziom „Praca awaryjna” i próg „Grupa 2 wentylacji”. W razie potrzeby aktywować ENABLE osobno dla odpowiedniego trybu.
4. Wejść do „Zaawansowane → Wentylator → Pasmo Zabronione”. W tej pozycji program wymusza poziom 1%, a zmiana parametru od razu wpływa na wyjście. Zakres wynosi od −20 do 200, fabrycznie 0. Dodatnia wartość zwiększa minimalny poziom sterowania, ujemna go zmniejsza.
5. Dobrać wartość tak, aby wszystkie wentylatory obracały się stabilnie, bez zatrzymywania i nadmiernego nagrzewania. Obserwować każdy wentylator, najlepiej z pomocą drugiej osoby. Samo uniesienie klapy nie zastępuje sprawdzenia poprawnej pracy silnika. Zatwierdzić OK; ESC przywraca poprzednią nastawę.
6. Sprawdzić wyjście przy kilku poziomach, w tym 0%, małym poziomie i 100%. Powtórzyć kalibrację po wymianie wentylatorów lub zmianie ich konfiguracji.
7. W AUTO sprawdzić reakcję na sygnał minimalny i maksymalny. Następnie sprawdzić przerwę sygnału i przejście na pracę awaryjną oraz powrót po przywróceniu sygnału. Jeżeli ENABLE jest aktywne, sprawdzić również jego działanie.
8. Sprawdzić GR 2 oraz sygnalizację alarmu w menu „Testowanie”. Po zakończeniu testów wyjść z tej pozycji i wybrać docelowy tryb pracy.

:::warning Rzeczywiste uruchomienie wyjść

Testowanie oraz kalibracja sterują rzeczywistymi wyjściami. Mogą uruchomić wentylatory, a test wentylacji wymusza poziom niezależnie od normalnego sterowania. Zapewnić bezpieczne warunki próby i stały nadzór.

:::

## Programowanie sterownika

### Panel przedni — wskaźniki i przyciski

| ELEMENT | OBSŁUGA |
| --- | --- |
| Zasilanie / uśpienie | Przycisk z symbolem zasilania wyświetla potwierdzenie uśpienia; zatwierdzić OK. Ponowne naciśnięcie wybudza urządzenie. Uśpienie zadaje wyjściom stan wyłączony; nie odłącza napięcia sieciowego. |
| Kłódka | Włącza lub wyłącza blokadę klawiatury. Po odblokowaniu kontrolka przy kłódce świeci. Na ekranie głównym blokada wraca po około 30 s bezczynności. |
| A — AUTO | Wybiera sterowanie z wejścia analogowego po zatwierdzeniu OK. Kontrolka A wskazuje wybrany tryb. |
| M — MANUAL | Wybiera ręczne sterowanie po zatwierdzeniu OK. Na ekranie głównym klawisze + i − zmieniają nastawę 0–100%. Kontrolka M wskazuje wybrany tryb. |
| +, −, OK, ESC | OK otwiera menu, wchodzi do pozycji i zatwierdza wartość. + i − wybierają pozycję lub zmieniają wartość. ESC wraca do poprzedniego poziomu albo anuluje edycję. |
| Alarm i grupa 2 | Czerwona kontrolka sygnalizuje alarm. Kontrolka przy symbolu wentylatora „2” sygnalizuje załączenie przekaźnika GR 2. |
| Wyświetlacz | W AUTO pokazuje zadany poziom wentylacji, odczyt wybranego wejścia, bargraf oraz alarmy. Przy aktywnym ENABLE pokazuje też jego stan. W MANUAL główna wartość oznacza nastawę ręczną; zabezpieczenia mogą zmienić wyjście. |

### Zapamiętywanie nastaw

Parametry menu zapisują się w pamięci nieulotnej po zatwierdzeniu OK. Zmiany poziomu MANUAL działają od razu, a zapis następuje po krótkiej bezczynności. Po zaniku zasilania przywracane są zapisane ustawienia, w tym tryb AUTO/MANUAL, poziom ręczny i stan uśpienia. Nie wyłączać zasilania bezpośrednio po zmianie nastawy ręcznej.

W razie błędnej sumy kontrolnej lub wartości poza zakresem program przywraca wartości fabryczne. Należy wtedy ponownie sprawdzić wszystkie ustawienia, w szczególności kalibrację wentylatorów, wejście sterujące i pracę awaryjną.

## Funkcje menu podstawowego

| MENU | ZAKRES / FABRYCZNIE | OPIS |
| --- | --- | --- |
| Typ sterowania | Wejscie V | Wybór V, I, CAN lub Wi-Fi. Dla analizowanej wersji używać V (2–10 V) albo I (4–20 mA). CAN i Wi-Fi nie realizują sterowania. |
| Grupa 2 wentylacji | 1–100% / 100% | Próg załączenia styku GR 2. Styk jest załączony przy poziomie równym progowi lub wyższym, wyłączony poniżej progu. Program nie definiuje osobnej histerezy. |
| Praca awaryjna | 0–100% / 30% | Poziom zadawany przy zaniku wybranego sygnału analogowego w AUTO. Wartość 0% oznacza zatrzymanie w razie utraty sygnału. |
| Blokada czyszczenie | 60 s | Na 60 sekund blokuje obsługę klawiszy i wyświetla odliczanie. Regulacja wentylacji działa dalej. Funkcja służy do przetarcia panelu, nie do prac elektrycznych ani mycia wnętrza. |
| Zaawansowane | Podmenu | Dostęp do testów, języka, kalibracji wentylatora, ENABLE, Soft Start, dźwięku alarmu, ustawień fabrycznych i informacji o programie. |

## Funkcje menu zaawansowanego

| MENU / PARAMETR | ZAKRES / FABRYCZNIE | OPIS |
| --- | --- | --- |
| Testowanie → Wentylacja | 0–100% | Chwilowe wymuszenie wyjścia regulowanego. Zmiany działają w trakcie edycji. Po wyjściu OK lub ESC wraca normalne sterowanie. |
| Testowanie → Went. 2 stopnia | Nie / Tak | Chwilowe wymuszenie styku GR 2 i jego kontrolki. |
| Testowanie → Alarm | Nie / Tak | Chwilowy test sygnalizacji alarmowej, również dźwięku, niezależnie od normalnej nastawy „Sygnal alarmu”. |
| Jezyk | Polski | Do wyboru polski, angielski i ukraiński. |
| Wentylator → Pasmo Zabronione | −20–200 / 0 | Kalibracja poziomu 1%. Podczas edycji wymuszane jest rzeczywiste wyjście 1%. Parametr nie jest wyrażony w procentach ani w sekundach. |
| Wentylator → Aktywacja EN AUTO | Nie / Tak; Nie | Włącza zależność trybu AUTO od wejścia ENABLE. |
| Wentylator → Aktywacja EN MANUAL | Nie / Tak; Nie | Włącza zależność trybu MANUAL od wejścia ENABLE. |
| Soft Start → Czas Rozbiegu | 0–50 / 5 | Szybkość narastania poziomu przy rozruchu do 100%. Większa wartość oznacza wolniejszą zmianę. Wartość 0 pomija etap narastania. |
| Soft Start → Czas 100% | 0–250 / 100 | Podtrzymanie poziomu 100% podczas rozruchu. Wartość 0 pomija etap podtrzymania. Łączne ustawienie rozbiegu i podtrzymania na 0 pomija przedmuch do 100%. |
| Soft Start → Czas Wybiegu | 0–50 / 5 | Szybkość dochodzenia do żądanego poziomu, także przy jego zmianie. Wartość 0 oznacza zmianę bez stopniowego dochodzenia. |
| Sygnal alarmu | Nie / Tak; Nie | Włącza dźwięk sygnalizujący alarm. Ustawienie Nie nie usuwa komunikatu na ekranie ani sygnalizacji kontrolką. |
| Ustawienia fabryczne | Nie / Tak | Po wybraniu Tak przywraca i zapisuje domyślne wartości, także kalibrację 0, wejście V, AUTO, pracę awaryjną 30%, próg GR 2 równy 100% i wyłączone ENABLE. Po operacji ponownie skonfigurować i sprawdzić urządzenie. |
| Program | ver. 2.1 + data kompilacji | Wyświetla wersję i datę kompilacji programu. Niniejszy opis opracowano na podstawie dostarczonych źródeł SC_PX16_v02. |

Parametry Soft Start są bezjednostkowymi nastawami liczników programu, a nie czasami podanymi w sekundach. Przy 50 Hz pojedynczy krok odpowiada w przybliżeniu (nastawa + 1) × 20 ms: dla rozbiegu i wybiegu jest to czas zmiany o 1 punkt procentowy, dla „Czas 100%” — czas podtrzymania. Wartość 0 ma znaczenie opisane w tabeli. Czasy rzeczywiste zależą od fazy algorytmu.

## Komunikaty błędów i ostrzeżeń

| KOMUNIKAT | ZNACZENIE I POSTĘPOWANIE |
| --- | --- |
| Wejscie | Za niski odczyt wybranego sygnału w AUTO. Urządzenie zadaje pracę awaryjną. Sprawdzić źródło sygnału, przewody, wspólną masę i wybór V/I. |
| Przegrzanie | Odczyt radiatora &gt;87°C; kasowanie &lt;80°C. Wentylacja zadawana jako 0% albo 100%, zgodnie z opisem zabezpieczenia termicznego. Sprawdzić chłodzenie i obciążenie. |
| Zasilanie | Zakłócenie synchronizacji układu mocy z siecią. Sprawdzić zasilanie i instalację. Przy całkowitym zaniku zasilania wyświetlacz nie działa. |
| Pamiec CRC | Błąd sumy kontrolnej lub zakresu zapisanych nastaw. Program przywraca domyślne wartości. Sprawdzić konfigurację i powtórzyć kalibrację; przy ponownym błędzie skontaktować się z serwisem. |

## Uwagi i ostrzeżenia

:::danger Odłącz zasilanie

W trakcie instalowania urządzenia dopływ energii elektrycznej należy bezwzględnie odłączyć, ponieważ napięcie na niektórych podzespołach jest niebezpieczne dla życia i zdrowia. Zaleca się powierzenie instalacji wykwalifikowanej osobie.

:::

Przed instalacją i użytkowaniem należy zapoznać się z instrukcją. Naprawy i prace wewnątrz urządzenia powierzać uprawnionemu personelowi. Uśpienie, blokada klawiatury, ENABLE oraz nastawa 0% nie stanowią odłączenia zasilania i nie zapewniają bezpiecznych warunków prac elektrycznych.

Nastawy wentylacji i pracy awaryjnej dobierać do potrzeb zwierząt oraz instalacji. Regularnie kontrolować rzeczywistą pracę wszystkich wentylatorów. Sygnalizacja SC-PE16 nie zastępuje niezależnego monitorowania warunków w obiekcie i zaniku zasilania. Na przedstawionej listwie zaciskowej nie ma osobnego styku ALARM do centralki.

:::note Utylizacja urządzenia

Po zakończeniu użytkowania produktu nie należy wyrzucać go razem z niesortowanymi odpadami komunalnymi, lecz zutylizować w sposób zgodny z obowiązującymi przepisami (dyrektywy WEEE Unii Europejskiej 2012/19/UE).

:::

Produkt został wykonany zgodnie z wymogami RoHS (dyrektywą Unii Europejskiej 2011/65/UE).

## Dane techniczne sterownika

| PARAMETR | WARTOŚĆ |
| --- | --- |
| Zasilanie / pobór własny | 230 V AC, 50 Hz / &lt;10 W |
| Maksymalny sumaryczny prąd wyjścia U | 16 A |
| Maksymalny prąd styku GR 2 | 6 A; styk C–NO, separowany |
| Wejście V / wejście I | 2–10 V / 4–20 mA, wybierane w menu |
| Próg zaniku sygnału (odczyt programu) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Styk bezpotencjałowy E–masa; aktywacja osobno dla AUTO/MANUAL |
| Zabezpieczenie termiczne (odczyt radiatora) | Alarm &gt;87°C; powrót &lt;80°C |
| Temperatura otoczenia / obudowa | −10°C do +40°C / IP65 |
| Wymiary / wytrzymałość przepięciowa | 34 × 29 × 12 cm / 210 J |
| Języki menu | Polski, angielski, ukraiński |

Zawartość zestawu według dostarczonej dokumentacji: 4 kołki rozporowe, 2 dławnice PG13,5, 1 dławnica PG9 i 1 zawias.

## Warunki gwarancji

Treść warunków gwarancji zachowano z dostarczonego dokumentu producenta.

1. Producent ELETOR z siedzibą w Polsce, adres: Pod Sosno 28, 87-305 Zbiczno (dalej zwany jako gwarant), udziela Nabywcy gwarancji jakości towaru, na który została wystawiona niniejsza karta gwarancyjna, pod warunkiem użytkowania go zgodnie z przeznaczeniem oraz zasadami określonymi w instrukcji obsługi doręczonej Nabywcy wraz z tym towarem.
2. Okres gwarancji wynosi 24 miesiące od daty sprzedaży. Usterki lub wady towaru ujawnione w tym okresie będą usuwane bezpłatnie. Po upływie okresu gwarancyjnego lub w przypadku utraty uprawnień gwarancyjnych usterki lub wady będą usuwane odpłatnie.
3. Gwarancją nie są objęte:

   - jakiekolwiek wady, które wystąpiły ze względu na niewłaściwe posługiwanie się towarem (obejmuje to wykonywanie operacji, które nie są opisane w instrukcji obsługi, itp.);

   - jakiekolwiek defekty powstałe w wyniku naprawy, modyfikacji itp. wykonywanych przez osobę inną niż gwarant;

   - jakiekolwiek wady lub uszkodzenia, które nastąpiły w wyniku transportowania lub upadku towaru, jeśli zdarzenia te miały miejsce już po zakupie towaru oraz uszkodzeń mechanicznych powstałych na skutek nieprawidłowej obsługi użytkownika;

   - jakiekolwiek wady lub uszkodzenia, które wystąpiły na skutek pożaru, trzęsienia ziemi, powodzi, uderzenia pioruna bądź innych klęsk żywiołowych, zanieczyszczenia środowiska, oddziaływania zewnętrznego promieniowania jonizującego lub pola magnetycznego oraz nieregularnych dostaw prądu lub prądu o parametrach niezgodnych z wymaganymi;

   - jakiekolwiek wady wynikające z nieprawidłowego przechowywania (np. przechowywania towaru poza podanym w specyfikacji zakresem temperatur lub wilgotności, w pobliżu środków chemicznych), niewłaściwej konserwacji lub czyszczeniem itp.;

   - jakiekolwiek wady wynikające z wyczerpania się baterii zasilających itp.;

   - jakiekolwiek wady spowodowane przez piasek, błoto, pyły, wodę i inne płyny, itp., które dostały się do wnętrza obudowy towaru;

   - uszkodzenia powstałe wskutek naturalnego, częściowego lub całkowitego zużycia towaru zgodnie z właściwościami albo przeznaczeniem towaru;

   - czynności wskazane w instrukcji obsługi, do których wykonania zobowiązany jest użytkownik we własnym zakresie.

4. Nabywca traci uprawnienia gwarancyjne na skutek:

   - dokonania jakiejkolwiek naprawy, modyfikacji towaru przez osobę inną niż gwarant;

   - stwierdzenia naruszenia, uszkodzenia lub zerwania którejkolwiek z plomb;

   - stwierdzenie uszkodzenia, naruszenia, zakrycia lub usunięcia numerów seryjnych bądź innych oznaczeń identyfikujących towar.

5. Termin naprawy wynosi do 21 dni roboczych od daty zgłoszenia wady i dostarczenia kompletnego towaru do punktu serwisowego gwaranta. W szczególnie uzasadnionych wypadkach, związanych z koniecznością sprowadzenia z zagranicy elementów lub podzespołów bądź ze szczególnie skomplikowanym lub trudnym do naprawy albo zdiagnozowania uszkodzeniem, termin naprawy może ulec przedłużeniu o okres niezbędny do wykonania obowiązków gwarancyjnych.
6. Uprawnienia Nabywcy z tytułu gwarancji mogą być realizowane jedynie po przedstawieniu przez niego ważnej i prawidłowo wypełnionej w dniu zakupu karty gwarancyjnej oraz dowodu zakupu (faktura, paragon, itp.). Samowolne zmiany wpisów na karcie gwarancyjnej (w tym przekreślenia, wytarcia, dopiski itp.) powodują utratę uprawnień z tytułu gwarancji. Karta gwarancyjna bez nazwy, modelu, numeru seryjnego towaru, daty i miejsca zakupu towaru oraz czytelnego stempla i podpisu Sprzedawcy jest nieważna i nie stanowi podstawy do skutecznego zgłoszenia reklamacji.
7. Nabywca jest zobowiązany do dostarczenia towaru na swój koszt w odpowiednim dla danego sprzętu opakowaniu zapewniającym bezpieczny i prawidłowy transport i przechowywanie lub pokrycia kosztów dojazdu gwaranta. W przypadku stwierdzenia, że oddany do naprawy towar jest sprawy technicznie i wolny od wad lub gdy stwierdzona usterka nie jest objęta gwarancją, Nabywca zostaje obciążony kosztami usług i transportu.
8. Nabywca jest zobowiązany do odebrania naprawionego towaru w terminie 90 dni od dnia dokonania przez gwaranta powiadomienia o naprawie. Jeżeli kupujący nie odbierze towaru w tym terminie, ponosi ryzyko przypadkowej utraty lub uszkodzenia towaru.
9. Okres gwarancji ulega przedłużeniu o czas trwania naprawy licząc od daty dostarczenia towaru do ustalonego terminu odbioru po naprawie. Gwarant zobowiązany jest do wydania dokumentu stwierdzającego okres oraz zakres usuniętych wad towaru.

10. Roszczenia Nabywca zgłasza za pośrednictwem Sprzedawcy towaru lub bezpośrednio, na adres gwaranta: ELETOR, Pod Sosno 28, 87-305 Zbiczno, Polska.

11. Gwarant nie ponosi odpowiedzialności:

    - za utracone dochody w rezultacie ujawnienia się wady i czasu jej usunięcia;

    - za straty powstałe w rezultacie ujawnienia się wady oraz wszelkie szkody wynikłe z nieprawidłowego zainstalowania, użytkowania lub zaprogramowania funkcji urządzenia.
