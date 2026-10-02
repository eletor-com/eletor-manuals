---
sidebar_position: 4
title: Anleitung IC-AC
description: Steuergerät IC-AC für Lufteinlässe in Stallgebäuden mit einem zulässigen
  Ausgangsstrom bis 2A
keywords:
- eletor IC-AC
- Steuergerät für Lufteinlässe
- Klimasteuergerät
- Steuergerät für die Schweinestalllüftung
- Mikroklimasteuergerät
- Steuergerät für Schweineställe
- Schweinestalllüftung
- Steuergerät für Aufzuchtställe
---


# Steuergerät IC-AC

  Steuergerät für Stellantriebe und Hubvorrichtungen für Lufteinlässe mit AC-Motoren mit Rechts-/Linkslauf und Potentiometer zur Erfassung der aktuellen Position. Das Steuergerät wandelt das Signal 0-10V in den Öffnungsgrad der Lufteinlässe um und ermöglicht zusätzlich eine manuelle Steuerung.

## Parameter und Merkmale:  
- Betriebsarten:
  - MANUAL – manuelle Steuerung mit den Tasten „+“, „-“;
  - AUTO – automatischer Betrieb im kalibrierten Bereich proportional zum Signal 0-10V;
  - NOTBETRIEB – bei Ausfall des Steuersignals öffnen sich die Lufteinlässe auf den in Prozent vorgegebenen Öffnungsgrad; 
- Relaisausgang (Rechts-/Linkslauf) 2A;
- Steuersignal: 0-10V;
- Möglichkeit zur Invertierung des Steuersignals;
- Positionsmessung mittels Potentiometer 1-100kΩ;
- Programmierbare Hysterese und Mittelungszeit der Messwerte; 
- Hermetisch dichtes Gehäuse IP56;
- Versorgungsspannung 230VAC 50Hz;
- Menüsprache: 
  - Polnisch
  - Englisch
  - Ukrainisch
  - Russisch

# Installation des Steuergeräts  
:::danger 
Während der Installation des Geräts muss die Stromversorgung unbedingt unterbrochen werden, da die Spannung an einigen Bauteilen eine Gefahr für Leben und Gesundheit darstellt. Es wird empfohlen, die Installation einer qualifizierten Person zu übertragen.
:::

## Auswahl des Montageorts  

  Der Montageort ist zweckmäßig so zu wählen, dass das Gerät für befugte Personen leicht zugänglich, für Tiere und Kinder jedoch unzugänglich ist. Auch die klimatischen Bedingungen sind zu berücksichtigen, d. h. das Gerät muss im Temperaturbereich von -10°C bis 40 °C an einem Ort ohne direkte Sonneneinstrahlung betrieben werden.

# Montage

Das Gerät kann unter aggressiven klimatischen Bedingungen betrieben werden. Bei ordnungsgemäßer Montage ist das Gerät gegen schädliche Umwelteinflüsse beständig. 

  Bei der Montage ist Folgendes zu beachten: 
- der Deckel muss mit allen Schrauben festgeschraubt werden,
- die zum Anschluss des Geräts verwendeten Leitungen müssen einen runden Querschnitt aufweisen,
- nach dem Anschluss der Leitung sind die Kabelverschraubungen so festzuziehen, dass die Leitung abgedichtet und fixiert wird; die Verwendung von Silikon wird empfohlen,
- nicht verwendete Durchführungen (Kabelverschraubungen) sind zu verschließen,
- das Gehäuseunterteil wird mit 4 Spreizdübeln an einer ebenen Wand befestigt.


# Elektrischer Anschluss  

:::danger 
Vor dem Anschluss der Schaltung ist sicherzustellen, dass die Stromversorgung ausgeschaltet ist!
:::

  Nach dem Aufschrauben des Geräts ist die Frontplatte abzunehmen. Dazu wird das Flachbandkabel aus dem mit P1 gekennzeichneten Steckverbinder gezogen. Die Leitungen werden durch die Gummikabelverschraubungen geführt und können anschließend angeschlossen werden. Der Anschluss ist gemäß der Beschreibung auszuführen. Die Klemmen des Steuergeräts sind in der nachstehenden Abbildung dargestellt.

![Anschluss](./img/ic-acpołącz.png)

## Die Versorgung 230V AC aus dem Verteiler wird an folgende Klemmen angeschlossen:  
 - **Anschluss L** Außenleiterklemme. Die Verwendung eines Leitungsschutzschalters (Typ „S“ B3) sowie von Überspannungsableitern ist erforderlich.  
 - **Anschluss N** Neutralleiterklemme.  
 - **Anschluss PE** Schutzleiterklemme.

## Ausgang zum Stellantrieb: 
 - **Anschluss L** wird über eine Leitung mit Anschluss C verbunden, um die Relais mit Spannung zu versorgen.  
 - **Anschluss N** Neutralleiterklemme des Stellantriebs.  
 - **Anschluss PE** Schutzleiterklemme des Stellantriebs – Gehäuse.  
 - **Anschluss NO** Klemme des Stellantriebs für die Öffnungsrichtung der Lufteinlässe.  
 - **Anschluss NC** Klemme des Stellantriebs für die Schließrichtung der Lufteinlässe.
 - **Potentiometeranschluss** – gemäß der Kennzeichnung im Schaltplan des Stellantriebs anschließen. Die Polarität der Potentiometerversorgung muss so gewählt werden, dass die Positionswerte beim Öffnen der Lufteinlässe zunehmen und beim Schließen abnehmen. Ist dies nicht der Fall, müssen die Leitungen der Potentiometerversorgung vertauscht werden.  
 - **Anschluss In** – an das Steuergerät anschließen, um das Steuersignal für die Hubsysteme bereitzustellen.  


# Funktionsprinzip  

  Im Automatikbetrieb wandelt das Steuergerät das Steuersignal im Bereich 0-10V in die entsprechende Position des Stellantriebs der Lufteinlässe um. Der Stellantrieb muss in den Positionen für die maximale Öffnung und die Schließung der Lufteinlässe kalibriert werden. Während der Kalibrierung ist darauf zu achten, dass die zu den Lufteinlässen führenden Seile  ständig gespannt bleiben. Während der Kalibrierung muss die Taste „+“ die Lufteinlässe öffnen und die Taste „-“ die Lufteinlässe schließen. Ist dies nicht der Fall, müssen die Leitungen an den Klemmen NO und NC vertauscht werden.
  Die vom Potentiometer erfassten Positionswerte für Öffnung und Schließung müssen sich um mehr als 100 Einheiten unterscheiden. Die vom Potentiometer erfassten Positionswerte müssen beim Öffnen der Lufteinlässe zunehmen und beim Schließen abnehmen. Ist dies nicht der Fall, müssen die Leitungen der Potentiometerversorgung vertauscht werden.
  Nach ordnungsgemäßer Kalibrierung ist das Steuergerät für den Automatikbetrieb bereit und regelt die Position des Stellantriebs. Ein Steuersignal unter 1,5V bewirkt, dass die Lufteinlässe in die Notposition gefahren werden. 

## Bedienung 

  Das Steuergerät für Lufteinlässe kann in einer von zwei Betriebsarten betrieben werden: manuell oder automatisch. Die gewählte Betriebsart wird gespeichert und bleibt bei einem Stromausfall erhalten – nach dem Einschalten der Stromversorgung kehrt das Steuergerät in die zuletzt verwendete Betriebsart zurück. Die aktuell gewählte Betriebsart wird auf dem Display angezeigt:  
   - **MANUAL** - durch langes Drücken von "+" oder "-" wird der manuelle Betrieb aktiviert. In dieser Betriebsart werden die Lufteinlässe manuell mit den Tasten gesteuert: „+“ - Öffnen, „-“ - Schließen.           
   - **AUTO**   - durch langes Drücken von "Esc" wird der Automatikbetrieb aktiviert. In dieser Betriebsart werden die Lufteinlässe automatisch durch das Signal 0-10V vom Anschluss In gesteuert.

## Funktionen des Hauptmenüs  

| MENÜ                       | Beschreibung | 
|:---:                       |:---|
|MANUAL  STOPP    POT 539  |  **„Informationsmodus”** – für den manuellen Betrieb. Angezeigte Informationen:  - **STOPP** – Stellantrieb steht still;  - **ÖFFNEN** – Öffnen der Lufteinlässe nach Drücken der Taste „+“;  - **SCHLIESSEN** – Schließen der Lufteinlässe nach Drücken der Taste „-“;  - **POT 539** – Parameter der aktuellen Position des Stellantriebs, ermittelt durch das Potentiometer.  •Wechsel in den Automatikbetrieb durch langes Drücken der Taste „Esc”| 
|AUTO  20 % = In 3,70 POT 511       |  **„Informationsmodus”**  für den Automatikbetrieb. Angezeigte Informationen:    **20 %**  Sollwert der Öffnungsposition der Lufteinlässe    **"="**   Lufteinlässe in der festgelegten Position    **"–"**    Schließen der Lufteinlässe bis zur festgelegten Position    **"+"**    Öffnen der Lufteinlässe bis zur festgelegten Position    **In 3,70**  Messung der Steuerspannung an den Klemmen In     **POT 511**  Parameter der aktuellen Position des Stellantriebs, ermittelt durch das Potentiometer.  Wechsel in den manuellen Betrieb durch langes Drücken der Taste „+“ oder „-“ | 
|Klappen im Notbetrieb 30 %  |**„Klappen im Notbetrieb”** – Vorgabe des Öffnungswerts der Klappen (Lufteinlässe) im Notbetrieb bei Ausfall des Steuersignals. Bei Ausfall des Steuergeräts oder der Signalleitung öffnen sich die Lufteinlässe auf den vorgegebenen Öffnungsgrad.| 
|Kalibrierung Öffnen 671 -> 311        |**„Kalibrierung der Öffnung”** – die Öffnung der Lufteinlässe wird kalibriert, indem mit den Tasten „+“ und „-“ die maximale Öffnung (Endposition) der Lufteinlässe eingestellt wird. Der erste angezeigte Wert entspricht der zuletzt gespeicherten Einstellung, der zweite Wert der aktuellen Position des Stellantriebs. Die Taste „Ok“ speichert die vorgenommenen Einstellungen, „Esc“ beendet den Kalibriermodus ohne Speicherung.   | 
|Kalibrierung Schließen 281 -> 311      |**„Kalibrierung der Schließung”** – die Schließung der Lufteinlässe wird kalibriert, indem mit den Tasten „+“ und „-“ die minimale Position der Lufteinlässe eingestellt wird. Der erste angezeigte Wert entspricht der zuletzt gespeicherten Einstellung, der zweite Wert der aktuellen Position des Stellantriebs. Die Taste „Ok“ speichert die vorgenommenen Einstellungen, „Esc“ beendet den Kalibriermodus ohne Speicherung.|  
|Mittelungszeit 5 s       |**„Mittelungszeit”** – Zeit zur Mittelung des Steuersignals vom Anschluss In; schützt vor Schwankungen am Steuereingang.  | 
|Invertierung   Nein |**„Invertierung”** – durch Aktivierung dieser Funktion wird das Steuergerät an das Steuersignal 10-0V angepasst  | 
|Sprache   Polnisch |**„Sprache”** – Auswahl der Menüsprache  | 
|Hysterese Pot  5   | **„Potentiometerhysterese”** – eine Änderung des Positionsparameters des Stellantriebs unterhalb des eingestellten Werts wird bei der Positionierung nicht berücksichtigt. Der Parameter dient dazu, sehr kleine Bewegungen des Stellantriebs sowie Störungen des Potentiometers zu unterdrücken. | 
 

# Hinweise und Warnungen  

:::danger 
Während der Installation des Geräts muss die Stromversorgung unbedingt unterbrochen werden, da die Spannung an einigen Bauteilen eine Gefahr für Leben und Gesundheit darstellt. Es wird empfohlen, die Installation einer qualifizierten Person zu übertragen.
:::

- Um Probleme beim Betrieb des Geräts zu vermeiden, muss die Anleitung vor der Installation und Benutzung gelesen werden. Eingriffe in die Konstruktion oder eigenständige Reparaturen sind unzulässig. Dies gilt insbesondere für Änderungen an Bauteilen und Baugruppen.
- Wartungs- und Servicearbeiten dürfen nur von autorisiertem Personal (Installateur oder Werkskundendienst) durchgeführt werden. In Stallgebäuden mit Zwangslüftung ist ein Alarmsystem erforderlich. 
- Der Gerätehersteller haftet nicht für Schäden durch unsachgemäße Installation, fehlerhafte Programmierung der Funktionen, Folgen unvorhersehbarer Ereignisse sowie äußere Einflüsse.
- Die Parameter des Geräts müssen entsprechend den Bedingungen im Tierhaltungsraum eingestellt werden. Diese Einstellungen sind individuell und hängen von der Entscheidung des Tierhalters ab. Der Gerätehersteller behält sich Änderungen an der Konstruktion des Geräts und an der Software vor.  


:::caution
![alt](./img/trash.svg) Nach Ende der Nutzungsdauer darf das Produkt nicht zusammen mit unsortierten Siedlungsabfällen entsorgt werden, sondern muss gemäß den geltenden Vorschriften entsorgt werden (WEEE-Richtlinien der Europäischen Union 2012/19/EU).  Das Produkt wurde gemäß den RoHS-Anforderungen hergestellt (Richtlinie der Europäischen Union 2011/65/EU).
:::

<!-- \newpage -->
# Technische Daten des Steuergeräts  

|Parameter                        |	BESCHREIBUNG      |
|:-----------                    |:---------- |
|Versorgungswechselspannung|	230VAC 50Hz|
|Maximaler Ausgangsstrom|	2A|
|Ausgangsentstörfilter|	RC|
|Eingangsimpedanz|	100kΩ|
|Überspannungsschutz der Ein- und Ausgänge|	JA|
|Potentiometerversorgung|	10VDC|
|Maximaler Strom der Potentiometerausgänge|	30mA|
|Betriebstemperaturbereich|	-10 +40oC|
|Geräteabmessungen|	20x15x8 cm |
|Gehäuseschutzart|	IP65|

:::info
Zum Lieferumfang des Steuergeräts IC-AC gehören:
- 4 Spreizdübel,
- 2 Kabelverschraubung PG11,
- 2 Kabelverschraubung PG9.
:::

