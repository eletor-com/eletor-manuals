---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: "Najczęstsze pytania dotyczące doboru, konfiguracji, diagnostyki i serwisu urządzeń ELETOR."
keywords:
  - ELETOR
  - FAQ
  - sterowniki wentylacji
  - regulatory
  - wentylatory
  - siłowniki
  - alarmy
  - falowniki
  - serwis
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Najczęściej zadawane pytania

FAQ powstało na podstawie zanonimizowanej analizy rzeczywistych rozmów z użytkownikami i klientami ELETOR. Odpowiedzi zostały uogólnione tak, aby pomagały w typowych przypadkach i nie zawierały danych konkretnych osób ani instalacji.

:::note Zakres FAQ

Odpowiedzi dotyczą typowych przypadków. Oznaczenia zacisków, funkcje i sposób podłączenia mogą różnić się pomiędzy modelami oraz wersjami urządzeń. W przypadku wątpliwości korzystaj z dokumentacji właściwej dla konkretnego produktu.

:::

:::warning Bezpieczeństwo

Prace przy instalacji elektrycznej wykonuj zgodnie z dokumentacją urządzenia i obowiązującymi zasadami bezpieczeństwa. Prace przy napięciu sieciowym powinny być wykonywane przez osobę posiadającą odpowiednie kwalifikacje.

:::

## Dobór sterownika i mocy

### Jak dobrać sterownik do wentylatorów?

Podstawą doboru jest przede wszystkim łączny prąd wentylatorów, a nie wyłącznie ich liczba.

:::tip Przygotuj dane przed doborem

Im dokładniejsze dane o silnikach i sposobie pracy instalacji, tym pewniejszy dobór sterownika.

:::

Przed doborem warto przygotować:

- liczbę wentylatorów,
- napięcie zasilania,
- moc lub prąd znamionowy każdego wentylatora,
- informację, czy wszystkie wentylatory mają pracować płynnie,
- informację, czy wentylatory mogą być podzielone na grupy,
- informacje o dodatkowych urządzeniach, np. nagrzewnicach lub wlotach powietrza.

Sterownika nie należy dobierać dokładnie „na styk”. Należy zachować odpowiedni zapas względem maksymalnego obciążenia.

### Czy wystarczy zsumować moc wentylatorów w watach?

Do wstępnego oszacowania można wykorzystać moc, ale ostateczny dobór powinien opierać się na prądzie znamionowym urządzeń oraz charakterze obciążenia.

Silnik podczas rozruchu może pobierać więcej prądu niż podczas normalnej pracy. Z tego powodu dwa zestawy wentylatorów o podobnej mocy znamionowej nie zawsze są równoważnym obciążeniem dla sterownika.

### Mam kilka małych wentylatorów. Czy mogę podłączyć je równolegle do jednego wyjścia?

Tak, jeżeli:

- są przeznaczone do takiego sposobu sterowania,
- mają pracować razem,
- suma obciążeń nie przekracza dopuszczalnego prądu wyjścia,
- sposób połączenia jest zgodny z dokumentacją sterownika.

Przy większej liczbie wentylatorów warto rozważyć podział na grupy lub zastosowanie rozszerzenia mocy.

### Kiedy potrzebne jest rozszerzenie mocy?

Rozszerzenie mocy stosuje się wtedy, gdy obciążenie przekracza możliwości wyjścia sterownika albo gdy instalacja ma być rozbudowana o większą liczbę wentylatorów.

Sterownik przekazuje wtedy sygnał sterujący, natomiast właściwe obciążenie obsługiwane jest przez dodatkowy moduł.

### Czy instalację można później rozbudować o dodatkowe wentylatory?

W wielu instalacjach tak. Najczęściej stosuje się:

- dodatkowe rozszerzenie mocy,
- dodatkową grupę wentylacji,
- stycznik załączający kolejną grupę,
- falownik w przypadku silników trójfazowych.

Najlepiej przewidzieć planowaną rozbudowę już podczas pierwszego doboru sterownika.

### Czy wszystkie wentylatory muszą pracować płynnie?

Nie. Typowe są dwa rozwiązania:

1. wszystkie wentylatory pracują płynnie,
2. pierwsza grupa pracuje płynnie, a kolejne grupy są dołączane stopniowo, np. przez styczniki.

Drugie rozwiązanie pozwala obsłużyć większą instalację bez płynnej regulacji każdego wentylatora.

### Mam 10 wentylatorów. Czy potrzebuję bardzo dużego sterownika?

Nie zawsze. Można zastosować kilka sposobów sterowania:

- podział na grupy,
- rozszerzenia mocy,
- styczniki,
- falownik.

Ostateczny dobór zależy od parametrów elektrycznych wentylatorów oraz od tego, czy wszystkie mają zmieniać obroty jednocześnie.

### Czy sterownik 6 A i 12 A różnią się tylko dopuszczalnym obciążeniem?

Nie należy zakładać, że jedyną różnicą jest wartość prądu. Poszczególne wersje i generacje urządzeń mogą różnić się wyposażeniem lub sposobem wykonania.

Przy wymianie urządzenia należy sprawdzić dokładny model i aktualną dokumentację.


## Wentylatory i sterowanie wentylacją

### Czy sterownik reguluje wentylatory płynnie?

W sterownikach przeznaczonych do płynnej regulacji wentylacji prędkość wentylatorów jest zmieniana w zależności od zapotrzebowania wynikającego m.in. z temperatury.

Należy jednak sprawdzić, czy dany typ silnika nadaje się do stosowanego sposobu regulacji.

### Co oznacza temperatura zadana?

Temperatura zadana jest wartością, do której sterownik odnosi aktualny pomiar temperatury.

Na jej podstawie sterownik zwiększa lub zmniejsza intensywność wentylacji zgodnie z pozostałymi ustawieniami, np. pasmem regulacji, poziomem minimalnym i maksymalnym.

### Co oznacza minimalny poziom wentylacji?

Jest to minimalna wartość sterowania wentylatorem podczas pracy automatycznej.

Ustawienie zapobiega pracy poniżej poziomu, przy którym wentylator mógłby działać niestabilnie lub zapewniać zbyt małą wymianę powietrza.

### Co oznacza maksymalny poziom wentylacji?

Jest to górne ograniczenie wartości sterowania wentylacją.

Przykładowo ustawienie wartości poniżej 100% może ograniczyć maksymalne obroty wentylatora, jeżeli wymaga tego instalacja.

### Co oznacza pasmo wentylacji?

Pasmo wentylacji określa zakres temperatur, w którym sterownik przechodzi od minimalnego do maksymalnego poziomu wentylacji.

Im mniejsze pasmo, tym szybciej sterowanie reaguje wzrostem wydajności na zmianę temperatury.

### Wentylator po uruchomieniu najpierw wchodzi na 100%, a dopiero później zwalnia. Dlaczego?

Może być aktywna funkcja rozruchu, której zadaniem jest chwilowe uruchomienie silnika z większą mocą.

W zależności od wersji sterownika należy sprawdzić ustawienia związane z:

- funkcją Soft Start,
- czasem rozbiegu,
- czasem pracy przy 100%,
- czasem wybiegu.

Jeżeli funkcja nie jest potrzebna w danej instalacji, odpowiednie parametry można zmienić zgodnie z instrukcją urządzenia.

### Po co wentylator przy starcie może być chwilowo uruchamiany z pełną mocą?

Taki rozruch może pomagać w pewnym uruchomieniu wentylatora oraz w instalacjach, w których elementy mechaniczne mogą stawiać większy opór podczas startu.

Nie w każdej instalacji jest to jednak potrzebne.

### Co oznaczają czas rozbiegu i czas wybiegu?

**Czas rozbiegu** określa sposób narastania sterowania podczas uruchamiania wentylatora.

**Czas wybiegu** określa sposób zmniejszania prędkości.

Oba parametry pozwalają ograniczyć gwałtowne zmiany obrotów i pracy instalacji.

### Dlaczego dwa identyczne sterowniki mogą inaczej uruchamiać wentylatory?

Najczęstszą przyczyną są różne ustawienia.

Warto porównać przede wszystkim:

- temperaturę zadaną,
- pasmo wentylacji,
- minimum i maksimum,
- ustawienia Soft Start,
- czasy rozbiegu i wybiegu,
- konfigurację grup wentylacyjnych.

### Czy sterownik może okresowo uruchamiać wentylację niezależnie od temperatury?

W zależności od modelu dostępna jest funkcja przewietrzania okresowego.

Może ona uruchamiać wentylację na określony czas w zadanych odstępach, nawet gdy regulacja temperaturowa nie wymaga zwiększenia wentylacji.

### Do czego służą grupy wentylacji?

Grupy umożliwiają stopniowe zwiększanie wydajności instalacji.

Przykładowo:

- grupa 1 pracuje płynnie,
- grupa 2 uruchamia kolejne wentylatory,
- następna grupa uruchamia się przy jeszcze większym zapotrzebowaniu.

Pozwala to sterować dużą liczbą wentylatorów bez płynnej regulacji każdego z nich.

### Czy dodatkową grupę wentylatorów można załączać przez stycznik?

Tak. Wyjście przekaźnikowe sterownika może sterować cewką odpowiednio dobranego stycznika.

Obciążenie wentylatorów nie powinno być wtedy prowadzone bezpośrednio przez mały styk sterujący.

### Co oznacza symbol wentylatora lub żółta kontrolka na sterowniku?

W zależności od modelu kontrolki informują o aktualnym stanie wyjść i funkcji.

Żółta sygnalizacja może oznaczać aktywną funkcję roboczą, np. pracę wentylacji, ogrzewania lub kolejnej grupy.

Dokładne znaczenie należy sprawdzić w instrukcji danego modelu.

### Co oznacza symbol trybu ręcznego?

Tryb ręczny oznacza, że wartość sterowania została wymuszona przez użytkownika i nie jest w danej chwili wyliczana automatycznie na podstawie temperatury.

Po zakończeniu testów należy upewnić się, że sterownik został przywrócony do właściwego trybu automatycznego.


## Wloty powietrza i siłowniki

### Czy sterownik może sterować wlotami powietrza?

Tak, wybrane sterowniki umożliwiają współpracę z napędami wlotów powietrza.

Sposób podłączenia zależy od typu siłownika i sposobu jego sterowania.

### Jakie typy siłowników można stosować do wlotów?

W rozmowach technicznych najczęściej występowały dwa rozwiązania:

- siłownik sterowany sygnałem analogowym 0–10 V lub 2–10 V,
- siłownik rewersyjny otwórz/zamknij z sygnałem sprzężenia zwrotnego, np. z potencjometru.

Przed zakupem należy sprawdzić kompatybilność konkretnego modelu z posiadanym sterownikiem.

### Czy napięcie zasilania siłownika 24 V lub 230 V ma znaczenie dla sygnału 0–10 V?

Sygnał sterujący i zasilanie siłownika są odrębnymi parametrami.

Siłownik może być zasilany innym napięciem niż napięcie sygnału sterującego. Oba parametry muszą być zgodne z dokumentacją siłownika i sterownika.

### Co oznacza sterowanie 0–10 V?

Sterownik wysyła napięciowy sygnał analogowy reprezentujący żądane położenie lub poziom sterowania.

W typowym zastosowaniu niższa wartość oznacza mniejsze otwarcie, a wyższa większe, ale rzeczywistą charakterystykę należy sprawdzić w dokumentacji siłownika.

### Czym różni się 0–10 V od 2–10 V?

W obu przypadkach położenie jest zadawane sygnałem analogowym.

W standardzie 2–10 V dolna część zakresu jest przesunięta i może umożliwiać urządzeniu rozróżnienie sygnału sterującego od jego braku.

Sterownik i siłownik muszą obsługiwać zgodny zakres.

### Jak dobierać siłownik do liczby wlotów?

Nie należy dobierać siłownika wyłącznie na podstawie liczby klap.

Trzeba uwzględnić:

- wymaganą siłę lub moment,
- długość i sposób prowadzenia mechanizmu,
- opory klap,
- długość skoku,
- prędkość działania,
- napięcie zasilania,
- typ sterowania,
- wymagane sprzężenie zwrotne.

### Czy jeden siłownik może obsługiwać wiele klap?

Tak, jeżeli mechanika instalacji pozwala połączyć klapy wspólnym układem i wymagany moment lub siła nie przekracza możliwości siłownika.

W praktyce o doborze decydują opory całego mechanizmu, a nie sama liczba klap.

### Czy kilka siłowników można połączyć równolegle i sterować jednym sygnałem?

W niektórych systemach jest to możliwe, ale należy zweryfikować dokumentację siłowników oraz dopuszczalne obciążenie wyjścia sterującego.

W przypadku napędów rewersyjnych bez niezależnego sprzężenia zwrotnego może również dojść do stopniowego rozjechania pozycji poszczególnych siłowników.

### Dlaczego kilka siłowników może z czasem ustawiać się w różnych pozycjach?

Nawet identyczne silniki mogą pracować z nieco inną prędkością ze względu na:

- różne obciążenie,
- opory mechaniczne,
- tolerancję parametrów silnika,
- różnice przekładni.

Dlatego przy wymaganej dokładnej synchronizacji potrzebne jest właściwe sprzężenie zwrotne lub indywidualna kontrola pozycji.

### Czy wloty mogą być sterowane proporcjonalnie do wentylacji?

Tak. W odpowiednio skonfigurowanych systemach pozycja wlotów może być powiązana z aktualnym poziomem wentylacji.

Dzięki temu wraz ze wzrostem wydajności wentylatorów zwiększane jest również otwarcie wlotów.

### Czy siłownik 24 V wymaga osobnego zasilacza?

Jeżeli sterownik nie posiada odpowiedniego wyjścia zasilającego o wymaganej mocy, potrzebny jest osobny zasilacz.

Jego moc należy dobrać do poboru prądu siłownika oraz innych urządzeń zasilanych z tego samego źródła.

### Czy można zastosować siłownik innej firmy?

Często tak, jeżeli jego parametry elektryczne i sposób sterowania są zgodne z wyjściami sterownika.

Przed podłączeniem należy sprawdzić:

- napięcie,
- typ sygnału,
- schemat przewodów,
- kierunki pracy,
- sygnał położenia,
- dopuszczalne obciążenie.


## Czujniki temperatury i wilgotności

### Gdzie podłączyć czujnik temperatury?

Czujnik należy podłączyć do wejścia czujnikowego przewidzianego przez producenta, wejścia czujnikowego wskazanego w dokumentacji danego modelu.

Nie należy zakładać, że oznaczenia zacisków są identyczne we wszystkich wersjach urządzeń.

### Czujnik temperatury pokazuje inną wartość niż termometr wzorcowy. Co zrobić?

Jeżeli sterownik posiada funkcję kalibracji czujnika, można skorygować wskazanie po porównaniu go z wiarygodnym termometrem wzorcowym.

Przed zmianą kalibracji warto upewnić się, że:

- oba czujniki znajdują się w tym samym miejscu,
- pomiar został ustabilizowany,
- czujnik nie jest nagrzewany przez słońce lub urządzenia,
- nie znajduje się bezpośrednio w strumieniu zimnego lub gorącego powietrza.

### Czujnik wilgotności pokazuje złą wartość. Czy można go skalibrować?

Zależy to od wersji sterownika, czujnika oraz oprogramowania.

W niektórych rozwiązaniach korekta może wymagać odpowiedniej funkcji programowej lub zgodnego typu czujnika. Jeżeli różnica jest duża i powtarzalna, należy sprawdzić wersję urządzenia i skontaktować się z pomocą techniczną.

### Czy błędny pomiar zawsze oznacza uszkodzony czujnik?

Nie.

Przyczyną może być również:

- nieprawidłowa lokalizacja czujnika,
- przewód,
- połączenie elektryczne,
- konfiguracja,
- niewłaściwy typ czujnika,
- konieczność kalibracji,
- wilgoć lub korozja.


## Alarmy i powiadomienia

### Czy do wyjścia alarmowego sterownika można podłączyć bezpośrednio syrenę?

Nie należy tego zakładać.

Wyjście alarmowe sterownika jest zwykle wyjściem sterującym lub stykiem przekaźnikowym. Syrena może wymagać osobnego zasilania oraz centrali alarmowej.

### Po co stosuje się centralę alarmową?

Centrala może:

- odbierać sygnały alarmowe ze sterowników,
- zasilać sygnalizator,
- podtrzymać działanie podczas zaniku zasilania,
- sygnalizować alarm dźwiękiem lub światłem,
- wysyłać powiadomienia GSM w wersjach posiadających taką funkcję.

### Czy centrala może alarmować o zaniku zasilania sterownika?

Tak, jeżeli system został odpowiednio podłączony.

Rozwiązanie może wykrywać nie tylko przekroczenie temperatury, ale również utratę sygnału ze sterownika spowodowaną zanikiem jego zasilania.

### Gdzie ustawia się minimalną i maksymalną temperaturę alarmu?

W typowej konfiguracji progi alarmowe ustawia się w sterowniku obsługującym daną komorę lub pomieszczenie.

Centrala alarmowa odbiera następnie informację, że sterownik zgłosił alarm.

### Czy centrala GSM wymaga karty SIM?

Do wysyłania połączeń i wiadomości przez sieć komórkową potrzebna jest aktywna karta SIM lub inne rozwiązanie komunikacyjne przewidziane w danym modelu.

Bez aktywnego połączenia z siecią komórkową funkcje telefoniczne i SMS nie będą działały.

### Czy alarm może wysłać informację, z którego sterownika pochodzi zdarzenie?

W odpowiednio skonfigurowanym systemie tak.

Wejścia centrali mogą być przypisane do konkretnych pomieszczeń lub sterowników, dzięki czemu komunikat pozwala określić źródło alarmu.

### Ile sterowników można podłączyć do jednej centrali alarmowej?

Zależy to od modelu centrali.

W transkrypcjach występowały centrale obsługujące do ośmiu wejść, jednak przed wykonaniem instalacji należy sprawdzić aktualną specyfikację konkretnego urządzenia.

### Jaki akumulator stosowany jest w centrali alarmowej?

W części urządzeń omawianych w rozmowach stosowany był akumulator 12 V 7 Ah.

Przed zakupem zamiennika należy sprawdzić oznaczenie na istniejącym akumulatorze oraz specyfikację centrali, ponieważ inne wersje urządzeń mogą wymagać innego akumulatora.

### Centrala wysyła komunikaty o niskim napięciu. Co sprawdzić?

W pierwszej kolejności należy sprawdzić:

- stan akumulatora,
- jego wiek,
- połączenia akumulatora,
- obecność zasilania sieciowego,
- działanie ładowarki lub zasilacza centrali.

Zużyty akumulator może powodować cykliczne komunikaty o niskim napięciu.

### Jak często wymieniać akumulator w centrali alarmowej?

Nie ma jednej wartości odpowiedniej dla wszystkich warunków.

Akumulator należy okresowo testować, szczególnie w instalacjach, w których alarm podczas zaniku zasilania ma znaczenie krytyczne. Wraz z wiekiem jego rzeczywista pojemność maleje.

### Czy sama syrena wystarczy jako zabezpieczenie?

Syrena działa tylko wtedy, gdy ktoś może ją usłyszeć.

W obiektach pozostających czasowo bez nadzoru warto stosować również zdalne powiadomienie oraz podtrzymanie akumulatorowe.


## Falowniki

### Jak dobrać falownik do wentylatorów?

Należy znać:

- napięcie zasilania,
- liczbę faz,
- moc i prąd wszystkich silników,
- sposób ich połączenia,
- warunki pracy,
- wymagany sposób sterowania.

Falownik powinien mieć odpowiedni zapas względem obciążenia, szczególnie gdy kilka silników pracuje równolegle.

### Czy falownik powinien mieć dokładnie taką samą moc jak suma mocy silników?

Nie powinno się dobierać falownika wyłącznie na podstawie prostego zsumowania mocy i wybierać urządzenia pracującego dokładnie na granicy parametrów.

Należy uwzględnić prądy znamionowe, charakter obciążenia i zalecenia producenta falownika.

### Falownik zatrzymał wentylatory i wyświetlił błąd. Co zrobić?

Najważniejsze jest zapisanie pełnego kodu błędu przed resetem.

:::tip Zrób zdjęcie ekranu

Jeżeli sytuacja na to pozwala, przed resetem wykonaj zdjęcie wyświetlacza. Pełny kod błędu znacznie ułatwia diagnozę.

:::

Sam początek komunikatu często nie wystarcza do ustalenia przyczyny. Pełny kod pozwala rozróżnić m.in.:

- przeciążenie,
- przekroczenie prądu,
- przegrzanie,
- nieprawidłowe napięcie,
- inne błędy napędu.

### Czy można po prostu zresetować błąd falownika?

Reset może przywrócić pracę, ale nie usuwa przyczyny alarmu.

Po zdarzeniu należy sprawdzić kod błędu i ustalić przyczynę przed ponownym długotrwałym uruchomieniem instalacji.

### Falownik pracuje w zapylonym pomieszczeniu. Czy trzeba go czyścić?

Tak.

Kurz i osady na radiatorze lub wentylatorze chłodzącym mogą pogarszać odprowadzanie ciepła i doprowadzić do przegrzewania falownika.

Czyszczenie należy wykonywać zgodnie z instrukcją producenta, po bezpiecznym odłączeniu zasilania.

### Co może powodować przegrzewanie falownika?

Najczęstsze przyczyny to:

- zabrudzone elementy chłodzące,
- niedrożny przepływ powietrza,
- zbyt wysoka temperatura otoczenia,
- przeciążenie,
- uszkodzenie wentylatora chłodzącego,
- nieprawidłowy montaż.

### Czy podwyższone napięcie sieci może wywołać alarm falownika?

Tak. Falowniki kontrolują napięcie obwodu zasilania i mogą zgłaszać błąd po przekroczeniu dopuszczalnego poziomu.

Jeżeli problem się powtarza, należy skontrolować instalację i jakość zasilania.


## Awarie i diagnostyka

### Sterownik działa, ale wyświetlacz nic nie pokazuje. Co może być przyczyną?

Możliwe przyczyny obejmują m.in.:

- uszkodzenie wyświetlacza,
- problem z regulacją kontrastu w starszych rozwiązaniach,
- uszkodzenie połączenia,
- korozję,
- uszkodzenie płyty głównej.

Jeżeli urządzenie przez długi czas nie było używane albo pracowało w wilgotnym środowisku, warto również sprawdzić stan płyty.

### Sterownik po kilku latach nieużywania ma problem z wyświetlaczem. Dlaczego?

Długotrwały postój w wilgotnym lub agresywnym środowisku może doprowadzić do:

- utlenienia złączy,
- korozji,
- pogorszenia styków,
- uszkodzeń elementów elektronicznych.

W takim przypadku warto przeprowadzić pełny przegląd, a nie wymieniać elementów bez wcześniejszej diagnozy.

### Sterownik jest osmolony po przepięciu. Czy to oznacza, że płyta jest do wymiany?

Nie zawsze.

Element zabezpieczający może ulec uszkodzeniu i pozostawić dużo osadu, mimo że pozostała część płyty jest możliwa do naprawy.

Jeżeli jednak laminat jest zwęglony, wypalony lub uszkodzone są ścieżki, naprawa może być nieopłacalna lub nietrwała.

### Co może uszkodzić kilka sterowników jednocześnie?

Jeżeli wiele urządzeń ulega awarii w tym samym czasie, należy sprawdzić instalację zasilającą.

Jedną z możliwych przyczyn jest problem z przewodem neutralnym, który w instalacji trójfazowej może doprowadzić do pojawienia się nieprawidłowych napięć na odbiornikach jednofazowych.

Możliwe są również przepięcia pochodzące z sieci lub agregatu.

### Co zrobić po awarii związanej z przepięciem?

Przed podłączeniem naprawionego lub nowego sterownika należy ustalić przyczynę problemu.

:::danger Nie podłączaj urządzenia ponownie bez sprawdzenia instalacji

Jeżeli przyczyną awarii było nieprawidłowe napięcie, uszkodzony przewód neutralny lub przepięcie, naprawiony albo nowy sterownik może zostać ponownie uszkodzony.

:::

### Co to jest element przeciwprzepięciowy na płycie?

W urządzeniach elektronicznych stosowane są elementy ograniczające przepięcia, np. warystory.

Ich zadaniem jest przejęcie części energii przepięcia i ochrona dalszych obwodów. Po silnym zdarzeniu taki element może ulec trwałemu uszkodzeniu.

### Czy można uruchomić urządzenie po usunięciu spalonego elementu zabezpieczającego?

Nie należy traktować tego jako normalnej naprawy.

Po usunięciu zabezpieczenia urządzenie może utracić ochronę przed kolejnym przepięciem. Takie działania mogą być wykonywane wyłącznie jako świadoma procedura serwisowa przez osobę posiadającą odpowiednie kwalifikacje i po usunięciu przyczyny pierwotnej awarii.

### Sterownik został zalany lub mocno skorodował. Czy warto go naprawiać?

To zależy od stopnia uszkodzeń.

Powierzchowną korozję i pojedyncze uszkodzenia często można usunąć. Jeżeli korozja objęła ścieżki, złącza i wiele elementów, naprawa może być czasochłonna, niepewna i ekonomicznie nieuzasadniona.

### Czy mycie urządzenia ciśnieniowo może uszkodzić sterownik?

Tak.

Elektronika nie powinna być narażana na bezpośrednie działanie wody ani środka myjącego, jeżeli obudowa i sposób montażu nie są do tego przeznaczone.

Wilgoć dostająca się do środka może doprowadzić do korozji i późniejszych, trudnych do zdiagnozowania usterek.

### Dlaczego usterki po zalaniu mogą wracać po naprawie?

Korozja może postępować również w miejscach niewidocznych podczas pierwszej kontroli.

Uszkodzone przelotki, ścieżki i połączenia mogą działać podczas testu, a później ponownie stracić kontakt.

Dlatego przy mocno skorodowanej płycie serwis może zalecić wymianę zamiast dalszych napraw.

### Urządzenie raz działa, a raz nie. Od czego zacząć?

Warto zebrać przed kontaktem z serwisem:

- dokładny model,
- opis objawu,
- moment wystąpienia,
- wartości pokazywane na ekranie,
- kod alarmu lub błędu,
- informacje o ostatnich zmianach w instalacji,
- zdjęcie wnętrza i zacisków, jeżeli można je wykonać bezpiecznie.

Im dokładniejszy opis, tym łatwiejsza diagnoza.


## Serwis i naprawy

### Co wysłać do serwisu, jeśli sterownik jest uszkodzony?

Najlepiej wysłać komplet pozwalający odtworzyć problem.

Do przesyłki należy dołączyć krótki opis:

- co nie działa,
- kiedy pojawia się problem,
- czy awaria jest stała czy okresowa,
- czy przed awarią wystąpiło przepięcie, zalanie lub inne zdarzenie,
- dane potrzebne do kontaktu i zwrotu urządzenia.

:::note Dane do zgłoszenia serwisowego

Dane kontaktowe i wysyłkowe przekazuj bezpośrednio do serwisu. Nie publikuj ich w otwartych zgłoszeniach ani materiałach publicznych.

:::

### Czy trzeba wysyłać cały sterownik czy tylko płytę?

Zależy od usterki.

Przy problemach z wyświetlaczem, przyciskami, zasilaniem lub niejednoznacznym zachowaniem najlepiej wysłać cały zestaw potrzebny do odtworzenia objawu.

Przy wcześniej uzgodnionej naprawie konkretnego modułu serwis może poprosić tylko o płytę.

### Czy ELETOR naprawia sterowniki zamiast od razu je wymieniać?

Z transkrypcji wynika, że urządzenia są najpierw diagnozowane.

Jeżeli naprawa jest możliwa i ma sens, wymieniane są uszkodzone elementy lub moduły. W przypadku poważnego uszkodzenia serwis może zaproponować wymianę płyty lub całego urządzenia.

### Co się dzieje, jeśli uszkodzonej płyty nie da się naprawić?

Możliwa jest wymiana uszkodzonego modułu na nowy, o ile odpowiednia część jest dostępna i kompatybilna z urządzeniem.

W starszych urządzeniach serwis powinien najpierw potwierdzić zgodność wersji.

### Czy warto kupować od razu nową płytę po przepięciu?

Nie zawsze.

Jeżeli uszkodzenie dotyczy elementu ochronnego lub niewielkiej części układu, naprawa może być uzasadniona. Najpierw warto przeprowadzić diagnozę.

### Czy serwis może sprawdzić również wyświetlacz i przyciski?

Tak, jeżeli elementy zostaną dostarczone wraz z urządzeniem lub modułem.

Jest to szczególnie przydatne wtedy, gdy nie wiadomo, czy problem znajduje się na płycie głównej czy w panelu użytkownika.

### Czy mocno skorodowany sterownik zawsze warto ratować?

Nie.

Jeżeli koszt diagnozy i naprawy rośnie, a niezawodność po naprawie pozostaje niepewna, wymiana może być rozsądniejsza.

Szczególnie dotyczy to urządzeń, od których zależy wentylacja obiektu.

### Jak przyspieszyć diagnozę serwisową?

Dołącz dokładny opis objawu zamiast samego stwierdzenia „nie działa”.

Przydatne są również:

- zdjęcia,
- kod błędu,
- opis instalacji,
- typ podłączonych odbiorników,
- informacja o przepięciu lub zaniku zasilania,
- informacja o zalaniu lub myciu urządzenia.


## Instalacja i okablowanie

### Jak podłączać urządzenia do zacisków przekaźnikowych C i NO?

C i NO są typowymi oznaczeniami styku przekaźnikowego:

- C — styk wspólny,
- NO — styk normalnie otwarty.

Sposób wykorzystania zależy od urządzenia i schematu instalacji. Styk można wykorzystać np. do sterowania cewką stycznika, ale nie wolno przekraczać jego dopuszczalnych parametrów.

:::warning Prace elektryczne

Podłączenia do napięcia sieciowego powinny być wykonywane przez osobę z odpowiednimi kwalifikacjami, zgodnie ze schematem konkretnego urządzenia.

:::

### Czy wyjście przekaźnikowe może bezpośrednio zasilać duży wentylator?

Zwykle nie jest to właściwe zastosowanie małego wyjścia sterującego.

Do większych obciążeń stosuje się stycznik, przekaźnik mocy lub dedykowany moduł wykonawczy.

### Do czego służą zaciski A1 i A2 stycznika?

Są to zaciski cewki stycznika.

Po podaniu odpowiedniego napięcia na cewkę stycznik zmienia stan swoich styków mocy.

Napięcie cewki musi być zgodne z projektem instalacji i dokumentacją stycznika.

### Czy można montować dodatkowe aparaty wewnątrz obudowy sterownika?

Tylko wtedy, gdy konstrukcja konkretnej obudowy na to pozwala i nie pogarsza to:

- stopnia ochrony,
- izolacji,
- chłodzenia,
- bezpieczeństwa,
- dostępu serwisowego.

Wszelkie nowe otwory powinny być wykonane w sposób zachowujący wymaganą szczelność.

### Czy dodatkowe wyłączniki wentylatorów są przydatne?

Mogą ułatwić serwis i umożliwić niezależne odłączenie poszczególnych wentylatorów.

Sposób wykonania musi jednak uwzględniać zabezpieczenia elektryczne i nie może powodować niebezpiecznych stanów sterownika.

### Czy przewody sterujące można prowadzić razem z przewodami mocy?

Należy unikać prowadzenia wrażliwych przewodów sygnałowych równolegle i bardzo blisko przewodów dużej mocy, szczególnie na długich odcinkach.

Wymagania zależą od rodzaju sygnału i środowiska elektromagnetycznego.

### Jaki przewód stosować do połączeń sieciowych i urządzeń PoE?

W omawianych instalacjach jako minimum wskazywano skrętkę kategorii 5e.

Jeżeli przewód przebiega w środowisku o podwyższonym poziomie zakłóceń lub ryzyku ładunków elektrostatycznych, może być zasadne zastosowanie odpowiednio ekranowanego przewodu i prawidłowego systemu uziemienia.

### Czy do PoE potrzebny jest kabel krosowany?

W typowych instalacjach stosuje się standardowe połączenie proste.

Należy jednak zawsze sprawdzić wymagania urządzenia sieciowego i zastosowanego zasilacza PoE.


## Eksploatacja i konserwacja

### Jak ograniczyć ryzyko awarii sterowników w budynkach gospodarskich?

Najważniejsze jest ograniczenie wpływu:

- wilgoci,
- amoniaku i agresywnego środowiska,
- pyłu,
- bezpośredniego mycia wodą,
- przepięć,
- nieprawidłowego zasilania.

Warto również okresowo kontrolować stan przewodów, połączeń i obudów.

### Czy urządzenia elektroniczne powinny być regularnie czyszczone?

Tak, szczególnie urządzenia wyposażone w radiatory, wentylatory i otwory wentylacyjne.

Nagromadzony kurz pogarsza chłodzenie.

Czyszczenie należy wykonywać po odłączeniu zasilania i zgodnie z instrukcją urządzenia.

### Czy po kilku latach pracy warto wykonać przegląd sterownika?

Tak, szczególnie w trudnych warunkach środowiskowych.

Przegląd może obejmować:

- ocenę stanu złączy,
- kontrolę śladów wilgoci i korozji,
- sprawdzenie elementów chłodzących,
- sprawdzenie panelu i przycisków,
- test czujników,
- kontrolę akumulatorów w systemach alarmowych.

### Co warto zapisać po wystąpieniu awarii?

Najbardziej przydatne są:

- pełny komunikat,
- kod błędu,
- godzina zdarzenia,
- temperatura,
- stan wentylacji,
- informacja o zaniku zasilania,
- informacja o pracy agregatu,
- zdjęcie ekranu lub urządzenia.

Nie należy resetować urządzenia przed zapisaniem kodu, jeżeli sytuacja pozwala zrobić to bezpiecznie.

### Czy warto mieć alarm niezależny od sterownika wentylacji?

Tak, szczególnie tam, gdzie awaria wentylacji może szybko doprowadzić do niebezpiecznych warunków.

Niezależna centrala z własnym akumulatorem i zdalnym powiadamianiem daje dodatkową warstwę zabezpieczenia.

### Jakie informacje przygotować przed kontaktem z pomocą techniczną?

Najlepiej przygotować:

1. dokładny model urządzenia,
2. opis instalacji,
3. liczbę i parametry podłączonych urządzeń,
4. aktualne ustawienia związane z problemem,
5. dokładny objaw,
6. pełny kod błędu lub alarmu,
7. zdjęcia urządzenia i tabliczek znamionowych,
8. informację o ostatnich zmianach w instalacji.

Pozwala to znacznie skrócić diagnozę.


## Ważna uwaga dotycząca starszych urządzeń

Nazwy, oznaczenia zacisków i dostępne funkcje mogą różnić się pomiędzy wersjami urządzeń produkowanymi w różnych latach.

Jeżeli urządzenie ma kilka lub kilkanaście lat, przed zastosowaniem instrukcji z nowszego modelu należy potwierdzić:

- dokładne oznaczenie urządzenia,
- wersję płyty,
- rodzaj wyświetlacza,
- wersję oprogramowania,
- schemat zacisków.

:::warning Starsze wersje urządzeń

Nie zakładaj pełnej zgodności tylko na podstawie podobnego wyglądu obudowy. Przed użyciem schematu lub instrukcji potwierdź dokładny model i wersję urządzenia.

:::


## Kontakt z pomocą techniczną

Jeżeli FAQ nie rozwiązuje problemu, przygotuj przed kontaktem:

- zdjęcie sterownika,
- zdjęcie tabliczki znamionowej odbiornika,
- parametry silników lub siłowników,
- schemat połączeń,
- dokładny opis oczekiwanego sposobu działania.

Dzięki temu dobór urządzenia lub diagnoza problemu może być wykonana na podstawie rzeczywistych parametrów instalacji, a nie przypuszczeń.
