---
sidebar_position: 3
title: Anleitung SC-12
description: Klimasteuergerät für Stallräume mit einem zulässigen Ausgangsstrom bis
  12A
keywords:
- eletor sc-12
- Lüftungssteuergerät
- Klimasteuergerät
- Lüftungssteuergerät für Schweineställe
- Mikroklimasteuergerät
- Steuergerät für Schweineställe
- Schweinestalllüftung
- Steuergerät für Aufzuchtställe
---

# Steuergerät SC-12

Mikroprozessorgesteuertes Klimasteuergerät der Serie SPEED CONTROL. Die Vielseitigkeit des Geräts wird durch die große Anzahl an Ein- und Ausgängen sowie die intuitive Software in polnischer und englischer Sprache gewährleistet. Neben den grundlegenden Einstellungen für Temperaturen, Intervalllüftung, Zusatzheizung, minimale und maximale Lüftungsstufen und Alarme ermöglicht das Steuerprogramm das Testen sowie das Speichern der Kalibrierung der mit dem Steuergerät zusammenarbeitenden Aktoren.

**Parameter und Eigenschaften:** 
- Lüftung der Gruppe I: 
  - max. Strom des Ausgangs für die stufenlose Regelung 12A,
  - thermischer Schutz der Schaltung, 
  - sanfter Anlauf der Lüftung – Sanftanlauf,
  - Bypass-Relais bei voller Aussteuerung, 
  - Kalibrierung der Mindestdrehzahl, 
  - Energiesparprogramm mit einem System vorzeitig öffnender Klappen.
- Lüftung der Gruppe II, potentialfreier Kontakt bis 6A.
- Zusatzheizung, potentialfreier Kontakt bis 6A
- Alarmausgänge NO und NC: 
  - Meldung eines Stromausfalls,
  - Meldung einer Unter- oder Überschreitung des minimalen bzw. maximalen Temperaturgrenzwerts,
  - integrierter akustischer Signalgeber.
- Unabhängige 3 Ausgänge 0..10V:
  - Zusammenarbeit mit Erweiterungsmodulen,
  - Steuerung des Klappensystems, 
  - Regelung einer Heizung mit variabler Leistung.**
- Zwei Analogeingänge zur Temperaturmessung.
- Digitaler Anschluss zur Temperaturmessung (bis zu 4 Sensoren).
- Zwei Funktionsrelaisausgänge (wählbar):
  - Zusammenarbeit mit Linearantrieben, 
  - III und IV Lüftungsgruppe
- Zwei Analogeingänge 0-10V.
- Versorgung des Potentiometers mit DC 10V.
- Zusatzversorgung DC 12V.
- Möglichkeit der Zusammenarbeit mit einem Computer bis 1200m.
- Dichtes Gehäuse IP65.
- Versorgungsspannung 230VAC 50Hz.
- Leistungsaufnahme der Schaltung < 10V

# Installation des Steuergeräts
:::danger 
 Während der Installation des Geräts muss die Stromversorgung unbedingt abgeschaltet werden, da die Spannung an einigen Komponenten eine Gefahr für Leben und Gesundheit darstellt. Es wird empfohlen, die Installation einer qualifizierten Person zu übertragen.  Diese Tätigkeit ist gefährlich
:::

## Auswahl des Montageorts
Der Montageort ist unter Berücksichtigung eines leichten Zugangs zum Gerät für befugte Personen sowie der Unzugänglichkeit für Tiere und Kinder zweckmäßig auszuwählen. Auch die klimatischen Bedingungen sind zu berücksichtigen, d. h. das Gerät sollte im Temperaturbereich von -10°C bis 40 °C an einem Ort ohne direkte Sonneneinstrahlung betrieben werden. Um das Gerät herum muss eine ungehinderte Luftzirkulation gewährleistet sein. Zum Gerät gehört ein Temperatursensor.  

### Für die Montage des Temperatursensors gelten folgende Regeln:
 - Der Sensor darf nicht an einem Ort ohne Luftzirkulation oder mit direkter Sonneneinstrahlung montiert werden,
 - der Sensor darf nicht an einer tragenden Wand (Außenwand) des Gebäudes montiert werden,
 - die Nähe zu wärmeabgebenden Geräten wie Heizkörpern und Lampen ist zu vermeiden,
 - der Sensor darf nicht unmittelbar an Türen und Lüftungsöffnungen angebracht werden,
 - der Sensor darf nicht an für Tiere zugänglichen Stellen angebracht werden,
 - es wird empfohlen, die Anschlussleitung des Sensors mit Abstand zu den Versorgungsleitungen zu verlegen.

# Montage
Das Gerät kann unter aggressiven klimatischen Bedingungen betrieben werden. Bei ordnungsgemäßer Montage sind das Steuergerät und der Temperatursensor gegen schädliche Umwelteinflüsse beständig.  

### Bei der Montage ist auf Folgendes zu achten:
 - Vor dem Verschrauben ist die Deckeldichtung zu überprüfen,
 - der Deckel muss mit allen Schrauben festgezogen werden,
 - die zum Anschluss des Steuergeräts verwendeten Leitungen müssen rund sein,
 - nach dem Anschließen der Leitung sind die Kabelverschraubungen so festzuziehen, dass die Leitung abgedichtet und fixiert ist; die Verwendung von Silikon wird empfohlen,
 - nicht verwendete Durchführungen (Kabelverschraubungen) sind zu verschließen,
 - das Steuergerät (Gehäuseunterteil) wird mit 4 Spreizdübeln an einer ebenen Wand befestigt.

# Elektrischer Anschluss
:::danger 
 Vor dem Anschließen der Schaltung muss sichergestellt werden, dass die Stromversorgung ausgeschaltet ist!
Diese Tätigkeit ist gefährlich
:::

Vor dem Anschließen des Steuergeräts ist der Deckel abzuschrauben und abzunehmen. Die Leitungen werden durch die Gummikabelverschraubungen geführt und können anschließend angeschlossen werden. Die Anschlussklemmen des Steuergeräts sind in der nachstehenden Abbildung dargestellt.

![Anschluss ](./img/sc-12.png)

**Der Anschluss AC 230V** wird mit der Stromversorgung (Verteilung) verbunden. Die Verwendung eines Leitungsschutzschalters 1P-B6 sowie von Überspannungsableitern des Typs T1 T2 ist erforderlich. Beim Anschluss mehrerer Geräte empfiehlt es sich, die Steuergeräte auf verschiedene „Phasen“ (L1, L2, L3) zu verteilen, um eine gleichmäßige Belastung der Versorgungsleitung zu gewährleisten.

**Der Anschluss FAN** ist direkt mit dem Ventilator zu verbinden; bei der Steuerung mehrerer Ventilatoren darf die Gesamtbelastung 6A nicht überschreiten, und jeder Ventilator muss separat abgesichert sein. PE und N dürfen nicht von der Stromversorgung (Verteilung) abgegriffen werden, sondern müssen unbedingt mit den Anschlüssen des Steuergeräts verbunden werden.

**Der Anschluss FAN 2** kann zum Anschluss der Ventilatoren der Gruppe 2 oder von Sprühanlagen verwendet werden. Der Ausgang ist potentialfrei, der maximale Kontaktstrom beträgt 6A (bei direkter Ansteuerung einer Last ist ein externer Leitungsschutzschalter des Typs 1P-B6 erforderlich); der Kontakt schließt, wenn die gemessene Temperatur höher ist als die Summe aus Solltemperatur und Lüftungsband.

**Der Anschluss HOT** kann zum Anschluss eines Heizgeräts verwendet werden. Der Ausgang ist potentialfrei, der maximale Kontaktstrom beträgt 6A (bei direkter Ansteuerung einer Last ist ein externer Leitungsschutzschalter 1P-B6 erforderlich); der Kontakt schließt, wenn die gemessene Temperatur unter den eingestellten Wert fällt.

**Der Anschluss ALARM** verfügt über potentialfreie Ausgänge NC, C und NO zum Anschluss an eine Alarmzentrale. Der Alarm wird in folgenden Fällen aktiviert:
    - Die Temperatur ist zu niedrig oder zu hoch,
    - das Steuergerät oder der Temperatursensor ist beschädigt,
    - die Versorgungsspannung des Steuergeräts ist ausgefallen,
    - es liegt eine Fehlfunktion des Steuergeräts vor (z. B. Überhitzung des Steuergeräts)
Die nachstehende Abbildung zeigt den Anschluss des Ventilators an die Alarmzentrale.

![Alarmanschluss](./img/alarmsc-s.png)

**Die Anschlüsse FUNC1 und FUNC2** dienen zum Anschluss eines Hubantriebs zum Öffnen der Lufteinlässe, der auf einem Motor mit Rechts-/Linkslauf basiert. Das Relais FUNC1 schaltet den Strom für den Stellantrieb ein, während FUNC2 die Drehrichtung des Motors umschaltet. Beispiel eines Anschlussplans für den Hubantrieb (ein externer Leitungsschutzschalter 1P-B6 ist erforderlich):
Bei Deaktivierung der Hubantriebsfunktion arbeiten die Ausgänge FUNC1 und FUNC2 als Kontakte der Lüftungsgruppen 3 bzw. 4.

![Anschluss des Hubantriebs](./img/Sc-12fan.png)

**Der Anschluss 12V** ist zur Versorgung externer Sensoren vorgesehen.

**Der Anschluss V1 0-10V** dient zum Anschluss von Leistungserweiterungsmodulen. Die Spannung an dieser Klemme ist proportional zur Lüftungsstufe.

**Der Anschluss V2 0-10V** dient zum Anschluss des Stellantriebs zum Öffnen der Zuluftklappen.

**Der Anschluss V3 0-10V** dient zum Anschluss einer Heizungsanlage mit stufenlos regelbarer Leistung. Die Spannung an diesem Ausgang steigt proportional zum Temperaturabfall, ausgehend von der Zusatzheizungstemperatur.

**Der Anschluss 10V** dient zur Versorgung des Potentiometers des Hubantriebs oder anderer Schaltungen des Typs 0-10V.

**Der Anschluss SENS1 (SENS2)** wird mit 1 Temperatursensor TS3 oder TS5 verbunden; die Polarität spielt keine Rolle. Bei gleichzeitigem Anschluss von 2 Sensoren werden die gemessenen Temperaturen gemittelt. Es empfiehlt sich, die Messleitungen mit Abstand zu den Versorgungsleitungen zu verlegen.

**Der Anschluss 1-WIRE** kann zum Anschluss einer größeren Anzahl digitaler Temperatursensoren, maximal 4, in Parallelschaltung verwendet werden (die korrekte Polarität ist einzuhalten). Die maximale Länge der Sensorverbindungsleitung beträgt 150m (die Länge hat keinen Einfluss auf die Temperaturmessung); die Verwendung einer geschirmten Leitung wird empfohlen.

**Der Anschluss RS-485** kann zum Aufbau von Lüftungssystemen sowie zur Kommunikation mit einem PC verwendet werden.

**Der Anschluss IN1 0-10** dient zur Eingabe des Rückmeldesignals vom Lufteinlasssystem – es gibt die aktuelle Position der Einlässe an.

**Der Anschluss IN2 0-10** dient zum Anschluss des Steuergeräts an andere Sensoren, z. B. für Feuchtigkeit, CO2, oder zum Betrieb des Steuergeräts als Leistungserweiterung.

# Funktionsprinzip
Die Hauptaufgabe des Steuergeräts besteht darin, die Temperatur im Tierhaltungsraum auf dem vom Tierhalter festgelegten Niveau zu halten. Es ist zu beachten, dass das Steuergerät lediglich ein Hilfsmittel ist, das zur Gewährleistung optimaler klimatischer Bedingungen im Tierhaltungsraum beitragen soll. Die übergeordnete Rolle in diesem Prozess hat jedoch der Tierhalter, der die Geräteeinstellungen an die sich ändernden klimatischen Außenbedingungen und vor allem an die Bedürfnisse der Tiere im Stallgebäude anpassen sowie den Betriebszustand des Geräts mithilfe der Alarmzentrale überwachen muss.

## Erstinbetriebnahme des Steuergeräts
:::danger 
 Bei der Erstinbetriebnahme des Steuergeräts muss unbedingt der gesperrte Betriebsbereich des Motors eingestellt werden.

:::
Das Steuergerät arbeitet mit Ventilatoren mit einphasigem Asynchronmotor bei einer maximalen Gesamtstromaufnahme von 12A zusammen. Nach dem Anschluss der ausgewählten Ventilatoren muss der Benutzer diese für die Zusammenarbeit mit dem Steuergerät anpassen. Mit anderen Worten ist die Einstellung der Mindestbetriebsstufe (Drehzahl) des Ventilators erforderlich. Diese Funktion trägt die Bezeichnung „Sperrbereich“ und wird vom Benutzer einmalig unter „Erweiterte Einstellungen“ eingestellt. Zur korrekten Durchführung dieses Vorgangs empfiehlt sich die Unterstützung durch eine zweite Person, die das Verhalten des Ventilators fortlaufend beobachten kann, während die andere Person den Wert des „Sperrbereichs“ einstellt (werkseitig beträgt dieser Wert 0). Ein nicht eingestellter Sperrbereich kann zu Fehlfunktionen des Geräts führen. Der Wert des „Sperrbereichs“ kann als korrekt angesehen werden, sobald der vom Ventilator erzeugte Druck beginnt, die Klappen des Lüftungskamins geringfügig anzuheben. Die Einstellung des „Sperrbereichs“ ist erneut durchzuführen, wenn der an das Steuergerät angeschlossene Ventilator ausgetauscht wird.

## Periodische Intervalllüftung
Die Intervalllüftung ist eine vom Steuergerät ausgeführte Funktion, die aktiviert wird, wenn die Raumtemperatur unter die Solltemperatur fällt. Diese Funktion gewährleistet eine zyklische Frischluftzufuhr für die Tiere. Im Menü Intervalllüftung sind 3 Parameter verfügbar:
- **„Betriebszeit“** - legt fest, für wie viele Minuten der Ventilator eingeschaltet werden soll;
- **„Pausenzeit“** - legt die Stillstandszeit des Ventilators fest;
- **„Intervalllüftungsstufe“** - legt die Lüftungsleistung während der „Betriebszeit“ fest.

Alle oben genannten Parameter werden vom Benutzer eingestellt. 

### Bei der Einstellung der Intervalllüftungsparameter sind folgende Regeln zu beachten:
- Die Intervalllüftung wird ausschließlich dann eingeschaltet, wenn die Temperatur im Schweinestall unter die Solltemperatur fällt,
- die grundlegende Funktion der Intervalllüftung besteht darin, den Tieren eine zyklische Frischluftzufuhr zu gewährleisten, nicht jedoch darin, die Solltemperatur im Raum aufrechtzuerhalten,
- es wird empfohlen, die Räume kurz, aber häufig zu belüften,
- lange Intervalllüftungszeiten sind zu vermeiden, da sie zu übermäßigen Temperaturschwankungen führen können,
- die eingestellten Parameter müssen unbedingt an das Verhalten der Tiere sowie an die Bedingungen innerhalb und außerhalb des Raums angepasst werden.

## Funktionsweise des Geräts
Das Steuergerät regelt die Lüftung stufenlos von **„Min.1“ bis „Max.1“** im Bereich von der **„Solltemperatur“** bis zur Summe aus **„Solltemperatur“** und **„Lüftungsband 1Gr.“**. Oberhalb dieses Bereichs wird die Lüftungsgruppe 2 eingeschaltet, und die Gruppe 1 wechselt auf die Stufe **„Min.2“**; bei weiterem Temperaturanstieg steigt die Lüftung bis auf **„Max.2“** am Ende des Bereichs **„Lüftungsband 2 Gr.“**. Wenn **„Lüftungsband 2 Gr.“** auf null eingestellt ist und die Lüftung mit **„Max.1“** arbeitet, wird die Lüftungsgruppe 2 eingeschaltet, und ein weiterer Temperaturanstieg bewirkt keine weiteren Änderungen der Lüftung (gepunkteter Teil des Diagramms). Wenn die Raumtemperatur unter die **„Solltemperatur“** fällt, belüftet das Steuergerät den Raum periodisch; bei einem weiteren Abfall wird die Zusatzheizung eingeschaltet. Alles hängt von den vom Benutzer vorgenommenen Einstellungen ab. Das Steuerprogramm berücksichtigt auch die Zusammenarbeit mit einer Alarmzentrale, die aktiviert werden kann, wenn die Temperatur im Schweinestall von den eingestellten Parametern abweicht. 

![Lüftung](./img/Sc-12wentyl.png)  

## Programmierung des Steuergeräts
Das Steuergerät verfügt über eine Reihe von Standardeinstellungen, die in zwei Fällen in den nichtflüchtigen Speicher geschrieben werden:
1. Erstinbetriebnahme des Geräts,
2. Fehler im Datenspeicher.
Bei fehlender Stromversorgung oder einem Stromausfall verliert das Steuergerät die zuvor eingegebenen und gespeicherten Benutzereinstellungen nicht.

## Frontplatte – Anzeigen, Tasten und Display
![Bedienfeld](./img/SC-12panel.png)  
    1. Rote Kontrollleuchte zur Anzeige einer Überschreitung der maximal zulässigen Temperatur.
    2. Rote Kontrollleuchte zur Anzeige einer Unterschreitung der minimal zulässigen Temperatur.
    3. Gelbe Kontrollleuchte zur Anzeige der Zusatzheizung.
    4. Gelbe Kontrollleuchte zur Anzeige der Lüftung der Gruppe 2.
    5. Grüne Kontrollleuchte zur Anzeige der manuellen Vorgabe der Lüftungsstufe.
    6. Grüne Kontrollleuchte zur Anzeige des Kommunikationsbetriebs RS485.
    7. Menüdisplay, zeigt im normalen Betriebszustand die Temperatur an.
    8. Balkenanzeige zur Anzeige der Lüftungsstufe.
    9. Taste zum Navigieren nach oben im Menü oder zum Ändern eines Parameterwerts.
    10. Taste ESC - zum Verlassen des Menüs oder eines Parameters ohne Speichern des Werts.
    11. Taste OK - zum Aufrufen des Menüs oder zum Bestätigen (Speichern) eines Parameters.
    12. Taste zum Navigieren nach unten im Menü oder zum Ändern eines Parameterwerts.

## Bedienung des Menüs
Das Steuergerät verfügt über zahlreiche Funktionen, mit denen es an die jeweilige Anwendung angepasst werden kann. Diese Funktionen sind in einem Menü zusammengefasst, das durch Drücken einer der Tasten **(„+“, „-“ oder „OK“)** aufgerufen wird. Die Tasten **„+“** und **„-“** dienen zur Auswahl einer Funktion; Bearbeitung, Datenspeicherung oder der Wechsel in eine weitere Untermenüebene erfolgen mit der Taste **„OK“**. Zur Rückkehr zum übergeordneten Menü oder zum Abbrechen der Speicherung eines Parameters drücken Sie die Taste **„Esc“**.

## Funktionen des Basismenüs

| MENÜ                          | Beschreibung       | 
|:-----------                   |:---------- |
| Temperatur 20,8o C W16% A    | **Informationsmodus** - Normalbetrieb. Auf dem Display werden die aktuelle Temperatur und bei eingeschaltetem Ventilator die Lüftungsstufe angezeigt. Bedeutung der zusätzlichen Symbole:A-bedeutet aktivierter Alarm,D  - bedeutet eingeschaltete Heizung, W - bedeutet zusätzliche Lüftung| 
|   Solltemp.   20,0o C      |**„Solltemperatur“** – Legt die Temperatur fest, ab der die stufenlose Lüftungsregelung beginnt. Je nach Art der Nutztiere ist ein geeigneter Wert zu wählen.| 
| Intervalllüftung     | **Intervalllüftung** – es werden zwei Zeitwerte eingestellt.    1.**Betriebszeit** Legt die Anzahl der Minuten des Lüftungsbetriebs fest.    2.**Pausenzeit** Legt die Anzahl der Minuten des Lüftungsstillstands zwischen den einzelnen Betriebszyklen fest.    3.**Intervalllüftungsstufe** - Legt die Lüftungsleistung während des Intervalllüftungsbetriebs fest.| 
| Alarm |  1.**Alarm aktiv Ja** - Aktivierung/Deaktivierung des Alarmkontakts; damit das Steuergerät am Ausgang kein Alarmsignal ausgibt (an die Alarmzentrale), ist im Menü „NEIN“ auszuwählen.  2. **Temp. Min. 15,0o C** - Legt die absolute Mindesttemperatur fest, bei der der Alarm aktiviert wird.  3.**Temp. Max. 25,0o C** - Legt die absolute Höchsttemperatur fest, bei der der Alarm aktiviert wird.  4.**Alarmsignal Ja** - Aktivierung/Deaktivierung des akustischen Signals im Steuergerät. | 
|    Lüftung        |  1.**Lüftungsband 1 5,0o C**   - Legt die Reaktionsgeschwindigkeit des Steuergeräts (Änderung der Lüftungsstufe vom Minimum 1 bis zum Maximum 1) bei steigender Temperatur fest.  2.**Min. Stufe 1 1 %** - Legt die der Solltemperatur entsprechende Lüftungsstufe fest.  3.**Max. Stufe 1 100 %**-Legt die konstante Lüftungsstufe bei einer Temperatur oberhalb des stufenlosen Regelbereichs fest, wenn „Lüftungsband 2Gr.“ = 0; andernfalls die maximale Stufe der geregelten Lüftung bei einer Temperatur, die der Summe aus Solltemperatur und Band der Gruppe 1 entspricht.  4.**Lüftungsband 2 0,0o C**-Legt die Reaktionsgeschwindigkeit des Steuergeräts (Änderung der Lüftungsstufe vom Minimum 2 bis zum Maximum 2) bei steigender Temperatur für die Gruppe 2 fest. Die Funktion ist inaktiv, wenn das Band gleich null ist.  5.**Min. Stufe 2 1 %**-Legt die minimale Lüftungsstufe der Gruppe 1 am Einschaltpunkt der Kontakte der Gruppe 2 fest.  6.**Max. Stufe 2 100 %**-Legt die konstante Lüftungsstufe bei einer Temperatur oberhalb des stufenlosen Regelbereichs fest, wenn die Gruppe 2 eingeschaltet ist.  7.**Gruppe 3  5,0o C**-Legt die konstante Lüftungsstufe bei einer Temperatur oberhalb des stufenlosen Regelbereichs fest, wenn die Gruppe 2 eingeschaltet ist.  8.**Gruppe 4 7,0o C**-Legt die Temperatur relativ zur Solltemperatur fest, bei der die Lüftungsgruppe 4 eingeschaltet wird (die Hubantriebsfunktion muss deaktiviert sein).| 
|    Zusatzheizung  |  1.**Zusatzheiztemp. 15,0o C**-Legt die Einschalttemperatur der Zusatzheizung fest.  2.**Zusatzheizband 5,0o C** -Legt den Leistungsanteil der Zusatzheizanlagen (am Ausgang V3 0-10V) in Abhängigkeit von der Temperatur fest. | 

## Funktionen des erweiterten Menüs
Das erweiterte Menü ist hauptsächlich für Installateure vorgesehen und ermöglicht die Anpassung des Steuergeräts an die Anlage und den Ventilator, das Testen der Stromkreise sowie die Auswahl der Menüsprache. Der Wechsel zu den erweiterten Einstellungen erfolgt durch Drücken und Halten zweier Menütasten für etwa 10s. 

| MENÜ                          | Beschreibung       | 
|:-----------                   |:---------- |
|Testen  |Diese Funktion dient zur Überprüfung der einzelnen Ausgangsstromkreise des Steuergeräts; alle Einstellungen gelten nur vorübergehend, solange der jeweilige Menüpunkt aufgerufen ist. Nach dem Drücken von „ESC“ oder „OK“ kehrt der betreffende Ausgang in den Zustand zurück, der sich aus dem Betrieb des Steuergeräts ergibt.  1.**Lüftung 0 %**  Ermöglicht die manuelle Eingabe der Lüftungsstufe zur Überprüfung der Lüftungsanlage. Nach Bestätigung der Funktion leuchtet die grüne Kontrollleuchte (Handsymbol).  2.**Alarm Nein** Die Aktivierung schaltet 2 rote Kontrollleuchten, das akustische Signal sowie den Alarmstromkreis ein.  3.**Zusatzheizung Nein** Die Aktivierung schaltet die gelbe Kontrollleuchte (Flammensymbol) sowie den Zusatzheizstromkreis ein.  4.**Lüft. 2 Stufe Nein** Die Aktivierung schaltet die gelbe Kontrollleuchte (Ventilatorsymbol) sowie den Stromkreis der Gruppe 2 ein.  5.**Ausgang V1 0,0 V  Ausgang V2  0,0 V Ausgang V3  0,0 V**-Test der Ausgänge 0-10V; mit den Tasten „+“ oder „-“ kann die gewünschte Spannung für die folgenden Anlagen vorgegeben werden: Erweiterungsmodule, Zuluftklappen, stufenlose Zusatzheizung. Die Funktion ist besonders bei der Kalibrierung von Ausgang V2 der Zuluftklappen hilfreich.  6.**Hubantrieb 0** Ermöglicht die Überprüfung des Zuluftklappensystems: „+“ - öffnet die Einlässe, „-“ - schließt die Einlässe; auf dem Display wird die vom Potentiometer erfasste aktuelle Position des Stellantriebs angezeigt.  7.**Gruppe 3 Nein**  Die Aktivierung schaltet den Stromkreis der Lüftungsgruppe 3 ein. (Die Hubantriebsfunktion muss deaktiviert sein)  8.**Gruppe 4 Nein**  Die Aktivierung schaltet den Stromkreis der Lüftungsgruppe 4 ein. (Die Hubantriebsfunktion muss deaktiviert sein)|
|Sprache        | Auswahl der Menüsprache. Zur Auswahl stehen Polnisch und Englisch. | 
|Ventilator         |  1.**Sperrbereich 0**- Kalibrierung der Mindestdrehzahl der direkt an das Steuergerät angeschlossenen Ventilatoren; dieser Parameter entspricht der Lüftungsstufe „1%“. Ein positiver Parameterwert erhöht die Drehzahl, ein negativer verringert sie.  2.**Erw.modul Min. 1,9 V** -Minimale Spannung am Leistungserweiterungsmodul (Ausgang V1 0-10V).  3.**Erw.modul Max. 10,0 V** -Maximale Spannung am Leistungserweiterungsmodul (Ausgang V1 0-10V).  4.**Modulabschaltung Nein** - Abschaltung des Leistungserweiterungsmoduls; bei Auswahl von „JA“ fällt die Spannung am Steuerausgang für die Erweiterungsmodule (V1 0-10V) auf 0V und nicht auf den eingestellten Mindestwert, wenn die Lüftungsstufe 0% beträgt.  5.**Invertierung  Nein**-Die Aktivierung kehrt die Kennlinie des Ausgangs V1 um. Die Spannung sinkt bei steigender Lüftungsstufe innerhalb des durch Min.-Max. vorgegebenen Bereichs. Das Signal am Ausgang V1 ist vom Typ 10-0V.| 
| Zuluftklappen       |  1.**Vorlauf 0,0o C**-Vorzeitiges Öffnen der Zuluftklappen. Der vorgegebene Parameter legt fest, um welche Temperaturdifferenz vor Erreichen der „Solltemperatur“ sich die Zuluftklappen öffnen sollen.  2.**Vollständiges Schließen  Nein**- Die Aktivierung bewirkt, dass die Spannung am Steuerausgang für die Zuluftklappen (V2 0-10V) auf 0V und nicht auf den eingestellten Mindestwert fällt. Dies gilt bei fehlender Lüftung (Lüftungsstufe 0%).  3.**Klappen min.  1,9 V**- Minimale Spannung an den Zuluftklappen (Ausgang V2 0-10V).  4.**Klappen max.  10,0 V**- Maximale Spannung an den Zuluftklappen (Ausgang V2 0-10V).  5.**Invertierung   Nein**-Die Aktivierung kehrt die Kennlinie des Ausgangs V2 um. Die Spannung sinkt bei steigender Lüftungsstufe innerhalb des durch Min.-Max. vorgegebenen Bereichs. Das Signal am Ausgang V2 ist vom Typ 10-0V. |  
| Temperaturmessung  |  1.**Kalibrierung S1 23,0o C -> 23,5o C**,**Kalibrierung S2 23,0o C -> 23,2o C** - Die Kalibrierung der Analogeingänge ermöglicht eine Neuskalierung der von den Sensoren S1 und S2 erfassten Temperatur.  2.**Mittelungszeit 60 s**- Dieser Parameter legt den Zeitraum fest, über den die aktuellen Temperaturmesswerte gemittelt werden. Der Wert der mittleren Temperatur ist ein grundlegender Parameter der Steuergerätefunktionen. Zustandsänderungen der Ausgänge (Lüftung, Zusatzheizung, Klappen, weitere Lüftungsgruppen, Alarme,...) sind eng mit diesem Parameter verknüpft und können nicht häufiger auftreten als in dem hier festgelegten Zeitabstand. | 
| Hubantrieb      |  1.**Kalibrierung Öffnen 1024 -> 853**,**Kalibrierung Schließen 0 -> 324** -Die Kalibrierung des Hubantriebs ist für den ordnungsgemäßen Betrieb des Lufteinlasssystems erforderlich. Die Taste „+“ öffnet die Einlässe, die Taste „-“ schließt die Einlässe. Beim Öffnen der Einlässe muss der Positionsparameter steigen, beim Schließen sinken; andernfalls ist der Anschluss des Stellantriebs (Versorgung und Potentiometer) zu überprüfen. Bei der Öffnungskalibrierung werden die Einlässe vollständig geöffnet und die Position mit der Taste „OK“ bestätigt. Bei der Schließkalibrierung werden die Einlässe geschlossen und die Position mit der Taste „OK“ bestätigt. Die Taste „ESC“ beendet die Funktion ohne Speicherung. Die Differenz zwischen Öffnungs- und Schließposition muss mindestens 100 Einheiten betragen.  2.**Deaktivierung Nein**-Die Deaktivierung hebt die Steuerung des Hubantriebs über die Kontakte FUNC1 und FUNC2 auf; diese Kontakte übernehmen dann die Funktion der Lüftungsgruppen 3 und 4.| 
| Sanftanlauf               | Die Parameter in dieser Menügruppe bestimmen den Anlauf der Lüftung. Dem Einschalten der Lüftung in der stufenlos geregelten Gruppe gehen ein allmählicher Anlauf bis 100%, ein kurzzeitiger Betrieb mit 100%  und eine Absenkung auf die erforderliche Lüftungsstufe voraus. Dadurch entsteht beim Start der Lüftung ein Luftstoß, der das Öffnen der Schmetterlingsklappen in den Kaminen erleichtert.   Die Werte werden in Perioden der Versorgungsspannung bei 1% Lüftung angegeben.  1.**Hochlaufzeit 5**- Der Parameter legt die Geschwindigkeit des Drehzahlanstiegs der Lüftung von null bis zum Maximum fest – sanftes Einschalten der Ventilatoren. Der Wert 0 deaktiviert den sanften Hochlauf.  2.**Zeit 100%   100**- Der Parameter legt die Betriebszeit beim Start auf 100% der Lüftungsstufe fest. Die Einstellung der Hochlaufzeit und 100% auf 0 deaktiviert den Luftstoß beim Start der Lüftung vollständig.  3.**Auslaufzeit 5**-  Der Parameter legt die Änderungsgeschwindigkeit der Lüftungsstufe fest. | 
|Zusatzheizung              |  1.**Kontaktinvertierung Nein**-Die Aktivierung kehrt die Kennlinie des Ausgangs HOT um. Der Kontakt wird  bei sinkender gemessener Temperatur geöffnet.  2.**Hysterese  0,5o C** - Legt die Temperaturhysterese für den Zusatzheizkontakt fest.  3.**Relativer Betrieb Nein**-Die Aktivierung bewirkt die relative Vorgabe der Zusatzheizungstemperatur bezogen auf die Solltemperatur. Das Basismenü der Zusatzheizung wird geändert; darin wird dann die Differenz zur Solltemperatur angegeben.  4.**Zusatzheizung min. 1,9 V** - Minimale Spannung für die stufenlose Heizungssteuerung – Heizgerät mit variabler Ventilatorleistung (Ausgang V3 0-10V).  5.**Zusatzheizung max. 10,0 V** - Maximale Spannung für die stufenlose Heizungssteuerung – Heizgerät mit variabler Ventilatorleistung (Ausgang V3 0-10V).| 
| Programm 	|  **Version 2.4  Apr. 13 2018** - 	Anzeige der Softwareversion und des Kompilierungsdatums|

## Fehler- und Warnmeldungen

Fehlermeldungen dienen dazu, den Benutzer über Unregelmäßigkeiten im Betrieb des Steuergeräts zu informieren. Nachstehend sind die möglichen Fehlermeldungen aufgeführt

|FEHLER                            |	BESCHREIBUNG      |
|:-----------                    |:---------- |
|Überlastalarm 	     |Überlastalarm, aktiviert bei 75°C. Das Gerät unterbricht den Betrieb, bis es abgekühlt ist.|
|Alarm  Sensor fehlt|Zeigt einen fehlenden oder beschädigten Sensor oder eine beschädigte Anschlussleitung an.|

# Hinweise und Warnungen 
:::danger 
 Während der Installation des Geräts muss die Stromversorgung unbedingt abgeschaltet werden, da die Spannung an einigen Komponenten eine Gefahr für Leben und Gesundheit darstellt. Es wird empfohlen, die Installation einer qualifizierten Person zu übertragen.

:::
- Um Probleme beim Betrieb des Geräts zu vermeiden, muss die Anleitung vor Beginn der Installation und Nutzung gelesen werden.
- Eingriffe in die Konstruktion sowie eigenständige Reparaturen sind nicht zulässig. Dies gilt insbesondere für Änderungen an Bauteilen und Baugruppen. 
- Wartungs- und Servicearbeiten sind von befugtem Personal durchzuführen (Installateur oder Kundendienst des Herstellers). In Stallgebäuden mit Zwangslüftung ist ein Alarmsystem erforderlich. Der Gerätehersteller haftet nicht für Schäden, die durch fehlerhafte Installation, fehlerhafte Programmierung der Funktionen, Folgen zufälliger Ereignisse sowie äußere Einflüsse verursacht werden. 
- Die Parameter des Lüftungssteuergeräts müssen entsprechend den Bedingungen im Tierhaltungsraum eingestellt werden. Diese Einstellungen sind individuell und hängen von der Entscheidung des Tierhalters ab. Der Gerätehersteller behält sich das Recht vor, Änderungen an der Gerätekonstruktion und der Software vorzunehmen.

:::caution
<div class="warning-container">
  <p>
    <strong></strong> Nach dem Ende der Nutzungsdauer darf das Produkt nicht zusammen mit unsortierten Siedlungsabfällen entsorgt werden, sondern muss gemäß den geltenden Vorschriften entsorgt werden (WEEE-Richtlinien der Europäischen Union 2012/19/EU).
Das Produkt wurde gemäß den RoHS-Anforderungen hergestellt (Richtlinie der Europäischen Union 2011/65/EU).
  </p>
</div>
:::
:::tip

## Technische Daten des Steuergeräts
|Parameter                        |	BESCHREIBUNG      |
|:-----------                    |:---------- |
|Versorgungsspannung|	230VAC 50Hz|
|Maximaler Strom des Ausgangs für die stufenlose Regelung FAN|	12A|
|Regelbereich der Ausgangsspannung|	70V ÷ 230V|
|Maximaler Strom des Ausgangs (Kontakts) FAN 2|	6A|
|Maximaler Strom des Ausgangs (Kontakts) HOT|	6A|
|Maximaler Strom des Ausgangs (Kontakts) ALARM|	4A|
|Maximaler Strom des Ausgangs (Kontakts) FUNC1 und FUNC2|	4A|
|Betriebstemperaturbereich|	-10 +40oC|
|Temperaturmessbereich|	0 +50oC|
|Auflösung der Temperaturmessung|	0,1oC|
|Erkennung von Schäden am Temperatursensor|	JA|
|Maximale Anzahl analoger Sensoren|	2|
|Genauigkeit der Temperaturmessung – Analogeingang|	1oC|
|Abhängigkeit der Messung vom Leitungswiderstand – Analogeingang|	15,8Ω/oC|
|Maximale Anzahl digitaler Sensoren|	4|
|Genauigkeit der Temperaturmessung – Digitaleingang|	0,5oC|
|Abhängigkeit der Messung vom Leitungswiderstand – Digitaleingang|	Keine|
|Maximale Länge der Verbindungsleitung zwischen digitalen Sensoren|	150m|
|Überspannungsfestigkeit (max. E)|	210J|
|Überlastschutz|	75oC|
|Geräteabmessungen|	34x29x12 [cm]|
|Gehäuseschutzart|	IP56|
:::

:::info
Das Steuergerät SPEED CONTROL-12 v2  enthält im Lieferumfang:
 - 1 Temperatursensor,
 - 4 Spreizdübel,
 - 2 Kabelverschraubungen PG13,5.
 - 3 Kabelverschraubungen PG11,
 - 4 Kabelverschraubungen PG9.
:::















































































