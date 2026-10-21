---
id: sc-pe16
title: SC-PE16 — Bedienungsanleitung
sidebar_label: SC-PE16
sidebar_position: 5
description: Anleitung zur Leistungserweiterung SC-PE16 — Montage, Anschluss, Inbetriebnahme,
  Menü und Schutzfunktionen.
slug: /sc-pe16
toc_min_heading_level: 2
toc_max_heading_level: 3
---


Die Leistungserweiterung SC-PE16 dient zur Steuerung von Ventilatoren, wenn die Last die Leistungsfähigkeit des übergeordneten Steuergeräts überschreitet. Das Gerät regelt die Versorgungsspannung der Ventilatoren anhand eines Analogsignals oder einer manuellen Einstellung. Der maximale Gesamtausgangsstrom beträgt 16 A.

![Leistungserweiterung ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Parameter und Merkmale

- Betriebsarten AUTO und MANUAL sowie Ruhezustand des Geräts;
- Grafikdisplay und Touch-Tastatur;
- analoge Steuerung 2–10 V oder 4–20 mA;
- programmierbare Einschaltschwelle der 2. Lüftungsgruppe;
- byPASS bei einem stabilen Pegel von 100%;
- thermischer Schutz der Leistungsstufe;
- safeRUN: einstellbarer Notbetriebspegel;
- Kalibrierung des minimalen Lüftungspegels;
- Test von Lüftung, Relais und Alarm;
- Tastatursperre und Reinigungssperre;
- polnische, englische oder ukrainische Sprache;
- Versorgung 230 V AC, 50 Hz; Gehäuse IP65.

:::info Softwareversion

Die Funktionsbeschreibung bezieht sich auf die gelieferte Software **Vers. 2.1**. Die Verfügbarkeit der Funktionen ist anhand der im Gerät installierten Version zu beurteilen.

:::

## Installation des Steuergeräts

:::danger Stromversorgung trennen

Während der Installation des Geräts muss die Stromzufuhr unbedingt getrennt werden, da die Spannung an einigen Bauteilen eine Gefahr für Leben und Gesundheit darstellt. Es wird empfohlen, die Installation einer qualifizierten Person zu übertragen.

:::

### Wahl des Montageorts

Das Gerät ist an einem für das Bedienpersonal zugänglichen Ort außerhalb der Reichweite von Kindern und Tieren und ohne direkte Sonneneinstrahlung zu montieren. Der Umgebungstemperaturbereich beträgt −10°C bis +40°C. Um das Gehäuse und den Kühlkörper ist eine ungehinderte Luftströmung sicherzustellen. Den Kühlkörper nicht abdecken und das Gerät nicht in der Nähe von Wärmequellen montieren.

### Montage

Das Gehäuseunterteil mit vier Dübeln an einer ebenen Wand befestigen; dazu die Montageöffnungen außerhalb der abgedichteten Kammer verwenden. Den Deckel mit dem mitgelieferten Scharnier montieren. Vor dem Schließen den Zustand und den Sitz der Dichtung prüfen.

Leitungen mit rundem Außenquerschnitt verwenden, die zu den Kabelverschraubungen passen. Die Kabelverschraubungen so anziehen, dass sie die Leitung abdichten und fixieren. Nicht verwendete Durchführungen verschließen. Den Deckel mit allen Schrauben festziehen. Die Dichtheit hängt von der korrekten Montage des Gehäuses und der Durchführungen ab.

### Vorbereitung der Anschlüsse

Alle Arbeiten im Gehäuse nur nach Trennung der Stromversorgung und Prüfung der Spannungsfreiheit durchführen. Falls zum Abnehmen des Bedienfelds das Flachbandkabel getrennt werden muss, dieses vorsichtig abziehen und vor dem Schließen des Gehäuses wieder einstecken. Das Flachbandkabel nicht bei eingeschalteter Stromversorgung anschließen oder trennen.

Die Signalleitungen INPUT und ENABLE getrennt von den Versorgungs- und Ausgangsleitungen verlegen. Die am jeweiligen Gerät angebrachten Klemmenbezeichnungen beachten. Die Masse der Signaleingänge und die Schutzleiterklemme PE erfüllen unterschiedliche Funktionen und sind nicht austauschbar.

## Elektrischer Anschluss

:::danger Stromversorgung trennen

Vor dem Anschließen der Anlage sicherstellen, dass die Stromversorgung ausgeschaltet ist!

:::

![Klemmen für Versorgung, Ventilatoren, GR 2, ENABLE, CAN und INPUT](./img/sc-pe16/zaciski.png)

| KLEMME | FUNKTION |
| --- | --- |
| L, N, PE — Versorgung | Versorgung 230 V AC, 50 Hz: L — Außenleiter, N — Neutralleiter, PE — Schutzleiter. In der ursprünglichen Dokumentation wurde eine Absicherung B20 angegeben; bei der Auswahl der Schutzeinrichtungen und Leitungen sind die Installation und die Last zu berücksichtigen. |
| U, N, PE — Ventilatoren | U — geregelter Außenleiterausgang; N und PE — entsprechende gemeinsame Klemmen des Geräts. Die Summe der Ventilatorströme darf 16 A nicht überschreiten. Jeder Ventilator benötigt eine separate Absicherung. Für die Spannungsregelung zugelassene Motoren verwenden. |
| GR 2: C, NO | Galvanisch getrennter Relaiskontakt der 2. Gruppe. Er schaltet ein, wenn der vorgegebene Lüftungspegel gleich der Schwelle „Lüftungsgruppe 2“ oder höher ist. Maximaler Kontaktstrom gemäß der mitgelieferten Anleitung: 6 A. Bei direkter Ansteuerung einer Last sieht die Dokumentation eine externe Absicherung B6 vor. |
| INPUT: V, Masse | Spannungseingang. „Steuerungsart → Eingang V“ auswählen. In der untersuchten Software beträgt der Regelbereich 2–10 V. An diesen Eingang weder Netzspannung noch den geregelten Versorgungsausgang der Ventilatoren anschließen. |
| INPUT: I, Masse | Stromeingang 4–20 mA. „Steuerungsart → Eingang I“ auswählen. Das Signal entsprechend den Kennzeichnungen von Quelle und Empfänger anschließen. |

Zur Steuerung den ausgewählten Eingang V oder I verwenden. SC-PE16 benötigt eine eigene Netzversorgung; der Analogeingang überträgt lediglich den Steuerwert.

## ENABLE-Eingang und Kommunikation

### ENABLE: E und Masse

Der Eingang arbeitet mit einem potenzialfreien Kontakt. Die Klemmen E und Masse dürfen lediglich kurzgeschlossen oder geöffnet werden; keine externe Spannung anlegen. Ein Kurzschluss gibt den Betrieb frei, ein Öffnen gibt den Pegel 0% vor. Das Anhalten unterliegt der Einstellung „Auslaufzeit“.

Die ENABLE-Funktion wird für AUTO und MANUAL separat im Menü „Erweitert → Ventilator“ aktiviert. Beide Funktionen sind werkseitig deaktiviert, sodass dann keine Drahtbrücke erforderlich ist. Das Öffnen von ENABLE ist nicht mit dem Ruhezustand gleichzusetzen: Das Bedienfeld bleibt aktiv. In AUTO überspringt die Software bei aktiver ENABLE-Sperre das Einlesen des Steuersignals und aktiviert safeRUN nicht.

### CAN und Wi-Fi

Die Einträge „Eingang CAN“ und „Eingang WiFi“ sind im Menü vorhanden, führen jedoch in der Software Vers. 2.1 keine Steuerung aus: Beide Funktionen liefern den Pegel 0% zurück. Zur Inbetriebnahme des Geräts mit dieser Software den Eingang V oder I auswählen. Die Installation nicht auf Grundlage von CAN oder Wi-Fi konfigurieren, ohne die Unterstützung durch die installierte Softwareversion bestätigt zu haben.

## Funktionsprinzip

SC-PE16 ist ein Leistungsregler, der die Befehle des übergeordneten Steuergeräts oder des Bedieners ausführt. Er misst keine Raumtemperatur und verfügt über keine eigenen Einstellungen für Temperatur, Durchlüftung, Nachheizung oder Zuluftklappen. Der prozentuale Lüftungspegel bezeichnet einen Steuerwert und keine Messung der tatsächlichen Motordrehzahl.

| NENNSIGNAL | VORGEGEBENER LÜFTUNGSPEGEL |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

Zwischen den Grenzwerten ermittelt die Software den Pegel linear und rundet auf ganze Prozentwerte. Beim Eingang V beginnt der Anstieg nach Überschreiten des Messwerts 2,04 V, beim Eingang I nach Überschreiten von 4,04 mA. Der endgültige Ausgangszustand hängt auch von ENABLE, dem Anlauf und dem thermischen Schutz ab.

## Notbetrieb und Schutzfunktionen

### safeRUN — Ausfall des Eingangssignals

In der Betriebsart AUTO erscheint der Alarm „Eingang“, wenn der Spannungsmesswert unter 1,50 V oder der Strommesswert unter 2,00 mA liegt, abhängig vom ausgewählten Eingang. Die Software gibt dann den Pegel „Notbetrieb“ im Bereich 0–100% vor; werkseitig 30%. Sobald das Signal wieder die Erkennungsschwelle erreicht oder überschreitet, erlischt der Eingangsalarm und das Gerät kehrt zur analogen Steuerung zurück.

Die Bereiche 1,50–2,04 V und 2,00–4,04 mA ergeben den Pegel 0% ohne Eingangsalarm. Das Signal 0 V ist in dieser Version kein gewöhnlicher Stoppbefehl — es aktiviert den Notbetrieb. Das übergeordnete Steuergerät mit einem Ausgang 0–10 V ist auf den Bereich 2–10 V ohne Absenkung auf 0 V zu konfigurieren. In MANUAL steuert das Analogsignal die Lüftung nicht, und der Eingangsalarm wird zurückgesetzt.

### Thermischer Schutz

Der Alarm „Überhitzung“ wird gesetzt, wenn der Temperaturmesswert des Kühlkörpers 87°C überschreitet. Er wird nach einem Absinken unter 80°C zurückgesetzt. Während des Alarms ändert die Software den vorgegebenen Pegel: Bei Werten von mindestens 50% gibt sie 100% vor, bei Werten unter 50% gibt sie 0% vor. Die Änderung des Ausgangs unterliegt dem Anlauf- und Auslaufalgorithmus. Die Schutzfunktion gewährleistet nicht in jedem Fall einen unterbrechungsfreien Lüftungsbetrieb.

Der Zustand des Relais GR 2 wird vor der thermischen Korrektur bestimmt: Er hängt vom Pegel vor der erzwungenen Vorgabe von 0% oder 100% ab. Auch der Notbetriebspegel unterliegt der thermischen Korrektur. Bei Überhitzung die Kühlbedingungen, die Verschmutzung des Kühlkörpers und die Last prüfen; Arbeiten im Gehäuse einer befugten Person übertragen.

### byPASS und Sanftanlauf

Bei einem stabilen Ausgangspegel von 100% schaltet die Software das Relais zur Überbrückung der Phasenanschnittregelung ein. Der Anlauf kann einen Anstieg auf 100%, ein Halten bei 100% und den Übergang zum vorgegebenen Pegel umfassen. Die Parameter „Sanftanlauf“ beeinflussen auch die Reaktionsgeschwindigkeit des Ausgangs auf eine Änderung der Vorgabe.

## Erste Inbetriebnahme des Steuergeräts

:::warning Kalibrierung der Ventilatoren

Achtung! Bei der ersten Inbetriebnahme des Geräts muss unbedingt der unzulässige Betriebsbereich des Motors eingestellt werden.

:::

1. Bei getrennter Stromversorgung den Anschluss der Versorgung, von PE, der Ventilatoren und des Analogsignals prüfen. Die Zulassung der Motoren für die Spannungsregelung und einen Gesamtstrom von höchstens 16 A bestätigen.
2. Stromversorgung einschalten. Falls eine Sprachauswahl angeboten wird, OK drücken und die Sprache auswählen. Die Tastatur mit der Taste mit dem Schlosssymbol entsperren.
3. Unter „Steuerungsart“ „Eingang V“ oder „Eingang I“ auswählen. Den Pegel „Notbetrieb“ und die Schwelle „Lüftungsgruppe 2“ einstellen. Bei Bedarf ENABLE für die jeweilige Betriebsart separat aktivieren.
4. „Erweitert → Ventilator → Unzulässiger Bereich“ aufrufen. In diesem Menüpunkt erzwingt die Software den Pegel 1%, und eine Änderung des Parameters wirkt sich sofort auf den Ausgang aus. Der Bereich beträgt −20 bis 200, werkseitig 0. Ein positiver Wert erhöht den minimalen Steuerpegel, ein negativer verringert ihn.
5. Den Wert so wählen, dass sich alle Ventilatoren stabil drehen, ohne stehen zu bleiben oder sich übermäßig zu erwärmen. Jeden Ventilator beobachten, vorzugsweise mit Unterstützung einer zweiten Person. Das bloße Anheben der Klappe ersetzt nicht die Prüfung des korrekten Motorbetriebs. Mit OK bestätigen; ESC stellt die vorherige Einstellung wieder her.
6. Den Ausgang bei mehreren Pegeln prüfen, darunter 0%, ein niedriger Pegel und 100%. Die Kalibrierung nach dem Austausch von Ventilatoren oder einer Änderung ihrer Konfiguration wiederholen.
7. In AUTO die Reaktion auf das minimale und maximale Signal prüfen. Anschließend die Signalunterbrechung und den Übergang in den Notbetrieb sowie die Rückkehr nach Wiederherstellung des Signals prüfen. Wenn ENABLE aktiv ist, auch dessen Funktion prüfen.
8. GR 2 sowie die Alarmsignalisierung im Menü „Test“ prüfen. Nach Abschluss der Tests diesen Menüpunkt verlassen und die vorgesehene Betriebsart auswählen.

:::warning Tatsächliche Aktivierung der Ausgänge

Tests und Kalibrierung steuern die tatsächlichen Ausgänge an. Sie können die Ventilatoren starten, und der Lüftungstest erzwingt einen Pegel unabhängig von der normalen Steuerung. Sichere Testbedingungen und eine ständige Aufsicht gewährleisten.

:::

## Programmierung des Steuergeräts

### Frontbedienfeld — Anzeigen und Tasten

| ELEMENT | BEDIENUNG |
| --- | --- |
| Versorgung / Ruhezustand | Die Taste mit dem Ein/Aus-Symbol zeigt eine Bestätigungsabfrage für den Ruhezustand an; mit OK bestätigen. Erneutes Drücken weckt das Gerät auf. Der Ruhezustand gibt den Ausgängen den ausgeschalteten Zustand vor; er trennt nicht die Netzspannung. |
| Schloss | Aktiviert oder deaktiviert die Tastatursperre. Nach dem Entsperren leuchtet die Kontrollleuchte am Schloss. Auf dem Hauptbildschirm wird die Sperre nach etwa 30 s Inaktivität wieder aktiviert. |
| A — AUTO | Wählt nach Bestätigung mit OK die Steuerung über den Analogeingang aus. Die Kontrollleuchte A zeigt die ausgewählte Betriebsart an. |
| M — MANUAL | Wählt nach Bestätigung mit OK die manuelle Steuerung aus. Auf dem Hauptbildschirm ändern die Tasten + und − die Einstellung 0–100%. Die Kontrollleuchte M zeigt die ausgewählte Betriebsart an. |
| +, −, OK, ESC | OK öffnet das Menü, ruft einen Menüpunkt auf und bestätigt einen Wert. + und − wählen einen Menüpunkt aus oder ändern einen Wert. ESC kehrt zur vorherigen Ebene zurück oder bricht die Bearbeitung ab. |
| Alarm und Gruppe 2 | Die rote Kontrollleuchte signalisiert einen Alarm. Die Kontrollleuchte am Ventilatorsymbol „2“ signalisiert das Einschalten des Relais GR 2. |
| Display | Zeigt in AUTO den vorgegebenen Lüftungspegel, den Messwert des ausgewählten Eingangs, eine Balkenanzeige sowie Alarme an. Bei aktivem ENABLE wird auch dessen Zustand angezeigt. In MANUAL bezeichnet der Hauptwert die manuelle Einstellung; Schutzfunktionen können den Ausgang verändern. |

### Speichern der Einstellungen

Die Menüparameter werden nach Bestätigung mit OK im nichtflüchtigen Speicher gespeichert. Änderungen des Pegels MANUAL wirken sofort; die Speicherung erfolgt nach kurzer Inaktivität. Nach einem Stromausfall werden die gespeicherten Einstellungen wiederhergestellt, darunter die Betriebsart AUTO/MANUAL, der manuelle Pegel und der Ruhezustand. Die Stromversorgung nicht unmittelbar nach einer Änderung der manuellen Einstellung ausschalten.

Bei einer fehlerhaften Prüfsumme oder einem Wert außerhalb des zulässigen Bereichs stellt die Software die Werkseinstellungen wieder her. In diesem Fall sind alle Einstellungen erneut zu prüfen, insbesondere die Ventilatorkalibrierung, der Steuereingang und der Notbetrieb.

## Funktionen des Grundmenüs

| MENÜ | BEREICH / WERKSEINSTELLUNG | BESCHREIBUNG |
| --- | --- | --- |
| Steuerungsart | Eingang V | Auswahl von V, I, CAN oder Wi-Fi. Für die untersuchte Version V (2–10 V) oder I (4–20 mA) verwenden. CAN und Wi-Fi führen keine Steuerung aus. |
| Lüftungsgruppe 2 | 1–100% / 100% | Einschaltschwelle des Kontakts GR 2. Der Kontakt ist bei einem Pegel gleich der Schwelle oder darüber eingeschaltet und unterhalb der Schwelle ausgeschaltet. Die Software definiert keine separate Hysterese. |
| Notbetrieb | 0–100% / 30% | Pegel, der bei Ausfall des ausgewählten Analogsignals in AUTO vorgegeben wird. Der Wert 0% bedeutet Stillstand bei Signalverlust. |
| Reinigungssperre | 60 s | Sperrt die Tastenbedienung für 60 Sekunden und zeigt einen Countdown an. Die Lüftungsregelung arbeitet weiter. Die Funktion dient zum Abwischen des Bedienfelds, nicht für elektrische Arbeiten oder zum Waschen des Innenraums. |
| Erweitert | Untermenü | Zugriff auf Tests, Sprache, Ventilatorkalibrierung, ENABLE, Sanftanlauf, Alarmton, Werkseinstellungen und Softwareinformationen. |

## Funktionen des erweiterten Menüs

| MENÜ / PARAMETER | BEREICH / WERKSEINSTELLUNG | BESCHREIBUNG |
| --- | --- | --- |
| Test → Lüftung | 0–100% | Vorübergehende Zwangsansteuerung des geregelten Ausgangs. Änderungen wirken während der Bearbeitung. Nach Verlassen mit OK oder ESC wird die normale Steuerung wieder aufgenommen. |
| Test → Lüftung Stufe 2 | Nein / Ja | Vorübergehende Zwangsansteuerung des Kontakts GR 2 und seiner Kontrollleuchte. |
| Test → Alarm | Nein / Ja | Vorübergehender Test der Alarmsignalisierung einschließlich des Tons, unabhängig von der normalen Einstellung „Alarmsignal“. |
| Sprache | Polnisch | Zur Auswahl stehen Polnisch, Englisch und Ukrainisch. |
| Ventilator → Unzulässiger Bereich | −20–200 / 0 | Kalibrierung des Pegels 1%. Während der Bearbeitung wird der tatsächliche Ausgang 1% erzwungen. Der Parameter wird weder in Prozent noch in Sekunden angegeben. |
| Ventilator → Aktivierung EN AUTO | Nein / Ja; Nein | Aktiviert die Abhängigkeit der Betriebsart AUTO vom Eingang ENABLE. |
| Ventilator → Aktivierung EN MANUAL | Nein / Ja; Nein | Aktiviert die Abhängigkeit der Betriebsart MANUAL vom Eingang ENABLE. |
| Sanftanlauf → Anlaufzeit | 0–50 / 5 | Anstiegsgeschwindigkeit des Pegels beim Anlauf bis 100%. Ein größerer Wert bedeutet eine langsamere Änderung. Der Wert 0 überspringt die Anstiegsphase. |
| Sanftanlauf → Zeit 100% | 0–250 / 100 | Halten des Pegels 100% während des Anlaufs. Der Wert 0 überspringt die Haltephase. Werden Anlauf und Halten beide auf 0 eingestellt, wird das Durchlüften bis 100% übersprungen. |
| Sanftanlauf → Auslaufzeit | 0–50 / 5 | Geschwindigkeit der Annäherung an den gewünschten Pegel, auch bei dessen Änderung. Der Wert 0 bedeutet eine Änderung ohne schrittweise Annäherung. |
| Alarmsignal | Nein / Ja; Nein | Aktiviert den Alarmton. Die Einstellung Nein entfernt weder die Bildschirmmeldung noch die Signalisierung durch die Kontrollleuchte. |
| Werkseinstellungen | Nein / Ja | Stellt nach Auswahl von Ja die Standardwerte wieder her und speichert sie, darunter auch die Kalibrierung 0, Eingang V, AUTO, Notbetrieb 30%, die Schwelle GR 2 gleich 100% und deaktiviertes ENABLE. Nach dem Vorgang das Gerät erneut konfigurieren und prüfen. |
| Software | Vers. 2.1 + Kompilierungsdatum | Zeigt die Version und das Kompilierungsdatum der Software an. Diese Beschreibung wurde auf Grundlage der bereitgestellten Quelldateien SC_PX16_v02 erstellt. |

Die Sanftanlaufparameter sind dimensionslose Einstellungen der Softwarezähler und keine in Sekunden angegebenen Zeiten. Bei 50 Hz entspricht ein einzelner Schritt ungefähr (Einstellwert + 1) × 20 ms: Für Anlauf und Auslauf ist dies die Zeit für eine Änderung um 1 Prozentpunkt, für „Zeit 100%“ die Haltezeit. Der Wert 0 hat die in der Tabelle beschriebene Bedeutung. Die tatsächlichen Zeiten hängen von der Phase des Algorithmus ab.

## F ehler- und Warnmeldungen

| MELDUNG | BEDEUTUNG UND VORGEHEN |
| --- | --- |
| Eingang | Zu niedriger Messwert des ausgewählten Signals in AUTO. Das Gerät gibt den Notbetrieb vor. Signalquelle, Leitungen, gemeinsame Masse und die Auswahl V/I prüfen. |
| Überhitzung | Kühlkörpermesswert &gt;87°C; Rücksetzung &lt;80°C. Die Lüftung wird gemäß der Beschreibung des thermischen Schutzes mit 0% oder 100% vorgegeben. Kühlung und Last prüfen. |
| Versorgung | Störung der Synchronisierung der Leistungsstufe mit dem Netz. Versorgung und Installation prüfen. Bei vollständigem Ausfall der Stromversorgung funktioniert das Display nicht. |
| Speicher CRC | Prüfsummenfehler oder Bereichsfehler der gespeicherten Einstellungen. Die Software stellt die Standardwerte wieder her. Konfiguration prüfen und Kalibrierung wiederholen; bei erneutem Fehler den Kundendienst kontaktieren. |

## Hinweise und Warnungen

:::danger Stromversorgung trennen

Während der Installation des Geräts muss die Stromzufuhr unbedingt getrennt werden, da die Spannung an einigen Bauteilen eine Gefahr für Leben und Gesundheit darstellt. Es wird empfohlen, die Installation einer qualifizierten Person zu übertragen.

:::

Vor der Installation und Verwendung die Anleitung lesen. Reparaturen und Arbeiten im Geräteinneren befugtem Personal übertragen. Ruhezustand, Tastatursperre, ENABLE sowie die Einstellung 0% stellen keine Trennung der Stromversorgung dar und gewährleisten keine sicheren Bedingungen für elektrische Arbeiten.

Die Einstellungen für Lüftung und Notbetrieb an die Bedürfnisse der Tiere und der Installation anpassen. Den tatsächlichen Betrieb aller Ventilatoren regelmäßig kontrollieren. Die Signalisierung SC-PE16 ersetzt keine unabhängige Überwachung der Bedingungen im Gebäude und eines Stromausfalls. An der dargestellten Klemmleiste ist kein separater ALARM-Kontakt für eine Zentrale vorhanden.

:::note Entsorgung des Geräts

Nach Ende der Nutzungsdauer darf das Produkt nicht mit unsortiertem Siedlungsabfall entsorgt werden, sondern muss gemäß den geltenden Vorschriften entsorgt werden (WEEE-Richtlinien der Europäischen Union 2012/19/EU).

:::

Das Produkt wurde gemäß den RoHS-Anforderungen hergestellt (Richtlinie der Europäischen Union 2011/65/EU).

## Technische Daten des Steuergeräts

| PARAMETER | WERT |
| --- | --- |
| Versorgung / Eigenverbrauch | 230 V AC, 50 Hz / &lt;10 W |
| Maximaler Gesamtausgangsstrom U | 16 A |
| Maximaler Kontaktstrom GR 2 | 6 A; Kontakt C–NO, galvanisch getrennt |
| Eingang V / Eingang I | 2–10 V / 4–20 mA, im Menü auswählbar |
| Signalausfallschwelle (Softwaremesswert) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Potenzialfreier Kontakt E–Masse; Aktivierung separat für AUTO/MANUAL |
| Thermischer Schutz (Kühlkörpermesswert) | Alarm &gt;87°C; Rückkehr &lt;80°C |
| Umgebungstemperatur / Gehäuse | −10°C bis +40°C / IP65 |
| Abmessungen / Überspannungsfestigkeit | 34 × 29 × 12 cm / 210 J |
| Menüsprachen | Polnisch, Englisch, Ukrainisch |

Lieferumfang gemäß der mitgelieferten Dokumentation: 4 Spreizdübel, 2 Kabelverschraubungen PG13,5, 1 Kabelverschraubung PG9 und 1 Scharnier.

## Garantiebedingungen

Der Inhalt der Garantiebedingungen wurde aus dem bereitgestellten Dokument des Herstellers übernommen.

1. Der Hersteller ELETOR mit Sitz in Polen, Anschrift: Pod Sosno 28, 87-305 Zbiczno (nachfolgend Garantiegeber genannt), gewährt dem Käufer eine Qualitätsgarantie für die Ware, für die diese Garantiekarte ausgestellt wurde, unter der Voraussetzung, dass sie bestimmungsgemäß und gemäß den in der dem Käufer zusammen mit dieser Ware übergebenen Bedienungsanleitung festgelegten Regeln verwendet wird.
2. Die Garantiezeit beträgt 24 Monate ab dem Verkaufsdatum. Während dieses Zeitraums festgestellte Störungen oder Mängel der Ware werden kostenlos behoben. Nach Ablauf der Garantiezeit oder bei Verlust der Garantieansprüche werden Störungen oder Mängel kostenpflichtig behoben.
3. Von der Garantie ausgeschlossen sind:

   - sämtliche Mängel, die durch unsachgemäßen Umgang mit der Ware entstanden sind (einschließlich der Durchführung von Vorgängen, die nicht in der Bedienungsanleitung beschrieben sind, usw.);

   - sämtliche Defekte, die infolge von Reparaturen, Änderungen usw. durch eine andere Person als den Garantiegeber entstanden sind;

   - sämtliche Mängel oder Schäden, die durch Transport oder Herunterfallen der Ware entstanden sind, sofern diese Ereignisse nach dem Kauf der Ware eingetreten sind, sowie mechanische Schäden infolge unsachgemäßer Bedienung durch den Benutzer;

   - sämtliche Mängel oder Schäden, die durch Brand, Erdbeben, Überschwemmung, Blitzschlag oder andere Naturkatastrophen, Umweltverschmutzung, Einwirkung externer ionisierender Strahlung oder eines Magnetfelds sowie unregelmäßige Stromversorgung oder Strom mit von den Anforderungen abweichenden Parametern entstanden sind;

   - sämtliche Mängel infolge unsachgemäßer Lagerung (z. B. Lagerung der Ware außerhalb des in der Spezifikation angegebenen Temperatur- oder Feuchtigkeitsbereichs, in der Nähe von Chemikalien), unsachgemäßer Wartung oder Reinigung usw.;

   - sämtliche Mängel infolge erschöpfter Versorgungsbatterien usw.;

   - sämtliche Mängel, die durch Sand, Schlamm, Staub, Wasser und andere Flüssigkeiten usw. verursacht wurden, die in das Gehäuse der Ware gelangt sind;

   - Schäden infolge natürlicher, teilweiser oder vollständiger Abnutzung der Ware entsprechend ihren Eigenschaften oder ihrem Verwendungszweck;

   - in der Bedienungsanleitung aufgeführte Tätigkeiten, zu deren eigenständiger Durchführung der Benutzer verpflichtet ist.

4. Der Käufer verliert seine Garantieansprüche infolge:

   - jeglicher Reparatur oder Änderung der Ware durch eine andere Person als den Garantiegeber;

   - der Feststellung einer Manipulation, Beschädigung oder Entfernung einer der Plomben;

   - der Feststellung einer Beschädigung, Manipulation, Abdeckung oder Entfernung von Seriennummern oder anderen die Ware identifizierenden Kennzeichnungen.

5. Die Reparaturfrist beträgt bis zu 21 Werktage ab dem Datum der Mängelmeldung und der Lieferung der vollständigen Ware an die Servicestelle des Garantiegebers. In besonders begründeten Fällen, die mit der Notwendigkeit der Beschaffung von Bauteilen oder Baugruppen aus dem Ausland oder mit einem besonders komplexen bzw. schwer zu reparierenden oder zu diagnostizierenden Schaden zusammenhängen, kann die Reparaturfrist um den zur Erfüllung der Garantiepflichten erforderlichen Zeitraum verlängert werden.
6. Die Garantieansprüche des Käufers können nur nach Vorlage einer gültigen, am Kauftag ordnungsgemäß ausgefüllten Garantiekarte sowie eines Kaufbelegs (Rechnung, Kassenbon usw.) geltend gemacht werden. Eigenmächtige Änderungen der Einträge auf der Garantiekarte (einschließlich Durchstreichungen, Radierungen, Ergänzungen usw.) führen zum Verlust der Garantieansprüche. Eine Garantiekarte ohne Bezeichnung, Modell und Seriennummer der Ware, Kaufdatum und Kaufort sowie lesbaren Stempel und Unterschrift des Verkäufers ist ungültig und bildet keine Grundlage für eine wirksame Reklamation.
7. Der Käufer ist verpflichtet, die Ware auf eigene Kosten in einer für das jeweilige Gerät geeigneten Verpackung zu liefern, die einen sicheren und ordnungsgemäßen Transport und eine entsprechende Lagerung gewährleistet, oder die Anfahrtskosten des Garantiegebers zu übernehmen. Wird festgestellt, dass die zur Reparatur übergebene Ware technisch funktionsfähig und mangelfrei ist oder dass die festgestellte Störung nicht unter die Garantie fällt, werden dem Käufer die Kosten für Dienstleistungen und Transport in Rechnung gestellt.
8. Der Käufer ist verpflichtet, die reparierte Ware innerhalb von 90 Tagen ab dem Tag der Benachrichtigung über die Reparatur durch den Garantiegeber abzuholen. Holt der Käufer die Ware innerhalb dieser Frist nicht ab, trägt er das Risiko des zufälligen Verlusts oder der zufälligen Beschädigung der Ware.
9. Die Garantiezeit verlängert sich um die Dauer der Reparatur, gerechnet ab dem Datum der Lieferung der Ware bis zum vereinbarten Abholtermin nach der Reparatur. Der Garantiegeber ist verpflichtet, ein Dokument auszustellen, das den Zeitraum und den Umfang der behobenen Mängel der Ware bestätigt.

10. Der Käufer meldet seine Ansprüche über den Verkäufer der Ware oder direkt unter der Anschrift des Garantiegebers an: ELETOR, Pod Sosno 28, 87-305 Zbiczno, Polen.

11. Der Garantiegeber haftet nicht:

    - für entgangene Einnahmen infolge des Auftretens eines Mangels und der zu dessen Behebung erforderlichen Zeit;

    - für Verluste infolge des Auftretens eines Mangels sowie für sämtliche Schäden durch unsachgemäße Installation, Verwendung oder Programmierung der Gerätefunktionen.
