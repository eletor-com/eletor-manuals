---
sidebar_position: 4
title: Anleitung Netzteil DC50W24VB
description: Notstromnetzteil DC50W24VB  für das Lufteinlasssystem.
keywords:
- eletor IC-AC
- Lufteinlasssteuergerät
- Klimasteuergerät
- Lüftungssteuergerät für Schweineställe
- Mikroklimasteuergerät
- Steuergerät für Schweineställe
- Schweinestalllüftung
- Steuergerät für Aufzuchtställe
---


# Netzteil DC50W24VB

Notstromnetzteil mit automatischer und manueller Öffnungsfunktion für Lufteinlässe und Luftauslässe. Dient der Sicherheit von Nutztieren bei Stromausfall oder Ausfall des Steuergeräts. Nach Erkennung einer Störung meldet das Gerät einen Alarm und öffnet die Winden auf den vorgegebenen Öffnungsgrad.

## Parameter und Merkmale: 
-  Betriebsartenwahlschalter: 
    - MANUAL
    - AUTO.
-  Drehknopf für den Öffnungsgrad der Lufteinlässe.
-  Unterstützte Standards:
    - 0-10, 2-10, 10-0, 10-2.
-  Möglichkeit zur Invertierung des Steuersignals.
-  Alarmausgänge NO und NC.
-  Anzeige eines Stromausfalls.
-  Überwachung der Steuerspannung 2-10V.
-  Kurzschlussüberwachung der Ausgänge 24VDC.
-  Kurzschlussüberwachung der Ausgänge 0-10V.
-  2 Eingang 0-10V.
-  2 Ausgänge 0-10V.
-  Elektronische Schutzvorrichtungen für Eingänge, Ausgänge und die Leitung 24V.
-  Akkumulatorbatterie 24V 4.0 Ah.
-  Hermetisches Gehäuse IP65.
-  Versorgungsspannung 85~264VAC 47~63Hz.

# Installation des Steuergeräts  
:::danger 
Während der Installation des Geräts muss die Stromversorgung unbedingt abgeschaltet werden, da die Spannung an einigen Bauteilen lebens- und gesundheitsgefährlich ist. Es wird empfohlen, die Installation einer qualifizierten Person zu übertragen.
:::

## Wahl des Montageorts  

Der Montageort ist unter Berücksichtigung eines einfachen Zugangs für befugte Personen und der Unzugänglichkeit für Tiere und Kinder zweckmäßig zu wählen. Auch die klimatischen Bedingungen sind zu berücksichtigen, d. h. das Gerät sollte in einem Temperaturbereich von -10°C bis 40 °C an einem Ort ohne direkte Sonneneinstrahlung betrieben werden. Um das Gerät herum muss eine freie Luftzirkulation gewährleistet sein.

# Montage  

Das Gerät kann unter aggressiven klimatischen Bedingungen betrieben werden. Ein ordnungsgemäß montiertes Gerät ist gegen schädliche Umwelteinflüsse beständig.

### Bei der Montage ist Folgendes zu beachten: 
 - der Deckel muss mit sämtlichen Schrauben festgeschraubt sein,
 - die zum Anschluss des Geräts verwendeten Kabel müssen einen runden Querschnitt aufweisen,
 - nach dem Anschluss des Kabels sind die Kabelverschraubungen so festzuziehen, dass das Kabel abgedichtet und fixiert wird; die Verwendung von Silikon wird empfohlen,
 - nicht verwendete Durchführungen (Kabelverschraubungen) sind mit Blindstopfen zu verschließen,
 - das Gehäuseunterteil wird mit 4 Spreizdübeln an einer ebenen Wand befestigt.


# Elektrischer Anschluss  

:::danger 
Vor dem Anschluss der Anlage muss sichergestellt werden, dass die Stromversorgung ausgeschaltet ist!
:::

Nach dem Aufschrauben des Geräts ist die Frontplatte abzunehmen. Hierzu wird das Flachbandkabel aus dem mit P1 gekennzeichneten Steckverbinder gezogen. Die Kabel werden durch die Gummikabelverschraubungen geführt und können anschließend angeschlossen werden. Der Anschluss ist gemäß der Beschreibung auszuführen.

![Anschluss](./img/DC50W24VB.png)

**Stromversorgung 230V AC:** wird an die Stromversorgung (Verteilung) angeschlossen. Die Verwendung eines Leitungsschutzschalters (Typ „S“ B6) sowie von Überspannungsableitern der Klasse „C“ ist erforderlich. Das Gerät kann in einem weiten Spannungsbereich von 85V bis 264V und Frequenzbereich von 47 bis 63Hz versorgt werden, ohne dass der Betrieb des Geräts beeinträchtigt wird.  

**Anschluss In1 und In2** ist mit dem Steuergerät zu verbinden, um das Steuersignal an die Windensysteme zu übermitteln. Das Gerät kann zwei Steuergeräte oder ein einzelnes Steuergerät mit getrennten Bereichen für Lufteinlässe und Luftauslässe unterstützen (die Klemmen I1 und I2 sind zu überbrücken).  

**Anschluss ALARM** wird je nach System mit der Alarmzentrale verbunden – geschlossen (NO und C), geöffnet (NC und C). Der Alarm wird in folgenden Fällen ausgelöst:  •die Versorgungsspannung des Geräts ist ausgefallen,  •das Steuersignal 2-10V ist an mindestens einem Eingang ausgefallen,  •das Ausgangssignal ist kurzgeschlossen oder sein Wert weicht vom gemessenen Wert ab,  •auf der Versorgungsschiene +24V der Winden ist ein Kurzschluss aufgetreten.  

**Anschluss Ouput 1 und Ouput 2** werden entsprechend den Anforderungen des vorhandenen Geräts mit dem Stellantrieb (der Winde) verbunden; die Anschlussbeschreibung sollte in der Anleitung des jeweiligen Stellantriebs (der Winde) enthalten sein.  

**Betriebsartenwahlschalter S1** je nach vorhandenem Stellantrieb (Winde) ist die passende Betriebsart auszuwählen. Standardmäßig befinden sich die Schalter 1,2,3,4,5,6 in der Stellung off – Betrieb 2-10V.
 
| Kanal 1 | Kanal 2| Funktion |
|------|------|----------|
| 1 – off | 4 – off | Betriebsart im Signalbereich 2-10V, eine Steuerspannung unter 1,5V löst einen Alarm aus.   |
| 1 – on| 4 – on  | Betriebsart im Signalbereich 0-10V, keine Alarmreaktion auf ein Signal unter 1,5V.   |
| 2 – off | 5 – off  | Proportionale Betriebsart, Ausgangssignale im Bereich 0-10V oder 2-10V.  |
| 2 – on | 5 – on  | Umgekehrte Betriebsart, Ausgangssignale im Bereich 10-0V oder 10-2V.   |
| 3 – off | 6 – off  | Eingangsinvertierung ausgeschaltet.  |
| 3 – on | 6 – on   | Eingangsinvertierung eingeschaltet.   |

# Funktionsprinzip  

Das Notstromnetzteil versorgt im Normalbetrieb die Stellantriebe (Winden) 24V und lädt die Akkumulatoren oder hält deren Ladezustand aufrecht; diese übernehmen bei einem Stromausfall die Versorgung.  Der Schalter AUTO/MANUAL legt die Betriebsart des Geräts fest.  

**Betriebsart MANUAL** ermöglicht die direkte Steuerung der Stellantriebe (Winden) über den Drehknopf auf der Gerätefrontplatte.  

**Betriebsart AUTO** – die grundlegende Betriebsart überträgt das Steuersignal vom Eingang zum Ausgang, verarbeitet es entsprechend den Einstellungen des Schalters „S1“ und überwacht den Eingangssignalpegel.  Wird am jeweiligen Eingang eine Störung erkannt, gibt das Gerät an seinem Ausgang das Signal des Drehknopfs auf der Frontplatte aus.  Das Alarmrelais spricht in folgenden Fällen an:  •bei einem zu niedrigen Eingangssignal (Uin < 1,5V) – Schalter „S1“ 1-off, 4-off,  •bei einem Kurzschluss des Ausgangssignals gegen Masse oder 24V,  •bei fehlender Versorgungsspannung,  •bei einem Kurzschluss der Spannung 24V.

## Bedienung 

Der Benutzer wählt mit dem Schalter die Betriebsart MANUAL und mit dem Drehknopf den erforderlichen Öffnungsgrad der Lufteinlässe – die Stellantriebe arbeiten entsprechend der Stellung des Drehknopfs. Nach Abschluss der Einstellung der Lufteinlässe wird mit dem Schalter die Betriebsart AUTO gewählt und das Gerät in dieser Einstellung belassen – die Lufteinlässe stellen sich auf den vom Lüftungssteuergerät geforderten Öffnungsgrad ein. Im Notfall stellen sich die Lufteinlässe entsprechend der Stellung des Drehknopfs ein.  

## Frontplatte 

| MENÜ                       | Beschreibung | 
|:---:                       |:---|
|![Anschluss](./img/paneldcw50.png) |**Kontrollleuchte POWER** – zeigt das Vorhandensein der Stromversorgung und das Laden der Akkumulatoren an.  1.**Kontrollleuchte CHECK** – leuchtet im Automatikbetrieb dauerhaft, wenn das Signal des Steuergeräts an den Ausgang übertragen wird, und blinkt, wenn das Signal des Drehknopfs am Ausgang ausgegeben wird.  2.**OUT 1** – zeigt Störungen im Kanal 1 an.  3.**OUT 2** – zeigt Störungen im Kanal 2 an.  4.**AUTO** – automatischer Betrieb.  5.**MANUAL** – manueller Betrieb.  6.**Drehknopf 0%-100%** - Auswahl des Öffnungsgrads der Lufteinlässe.| 

# Fehler- und Warnmeldungen

Fehlermeldungen dienen dazu, den Benutzer über Störungen im Betrieb des Geräts zu informieren. Nachfolgend sind die möglichen Fehlermeldungen aufgeführt:
 -  Kontrollleuchte POWER – leuchtet nicht grün – keine Netzversorgung.
 -  Kontrollleuchte CHECK – blinkt gelb – an den Ausgängen wird das Signal des Potentiometers ausgegeben.
 -  Kontrollleuchte OUT 1 – leuchtet rot - Erkennung einer Störung (fehlendes Steuersignal, Kurzschluss am Ausgang oder Kurzschluss auf der Schiene 24VDC) im ersten Kanal.
 -  Kontrollleuchte OUT 2 – leuchtet rot - Erkennung einer Störung (fehlendes Steuersignal, Kurzschluss am Ausgang oder Kurzschluss auf der Schiene 24VDC) im zweiten Kanal.

# Hinweise und Warnungen  

:::danger 
Während der Installation des Geräts muss die Stromversorgung unbedingt abgeschaltet werden, da die Spannung an einigen Bauteilen lebens- und gesundheitsgefährlich ist. Es wird empfohlen, die Installation einer qualifizierten Person zu übertragen.
:::

 - Um Probleme beim Betrieb des Geräts zu vermeiden, muss die Anleitung vor der Installation und Verwendung gelesen werden. Eingriffe in die Konstruktion oder eigenständige Reparaturen sind nicht zulässig. Dies gilt insbesondere für Änderungen an Bauteilen und Baugruppen.
 - Wartungs- oder Servicearbeiten dürfen nur von befugtem Personal (Installateur oder Herstellerkundendienst) durchgeführt werden. In Stallgebäuden mit Zwangslüftung ist ein Alarmsystem erforderlich. 
 - Der Hersteller des Geräts haftet nicht für Schäden, die durch unsachgemäße Installation, fehlerhafte Programmierung der Funktionen, Folgen unvorhersehbarer Ereignisse sowie äußere Einflüsse verursacht werden. Die Parameter des Geräts müssen entsprechend den im Stallraum herrschenden Bedingungen eingestellt werden.Diese Einstellungen sind individuell und hängen von der Entscheidung des Tierhalters ab. 
 - Der Hersteller des Geräts behält sich Änderungen an der Konstruktion des Geräts und an der Software vor.
Das Gerät enthält eine Akkumulatorbatterie; eine übermäßige Entladung der Akkumulatoren ist zu vermeiden, da sie die Batterie beschädigen kann. 
Ein Kurzschluss der Batteriepole kann einen Brand verursachen.  


:::caution
![alt](./img/trash.svg) Nach Ende der Nutzungsdauer darf das Produkt nicht mit unsortierten Siedlungsabfällen entsorgt werden, sondern muss gemäß den geltenden Vorschriften entsorgt werden (WEEE-Richtlinie der Europäischen Union 2012/19/EU).  Das Produkt wurde gemäß den RoHS-Anforderungen hergestellt (Richtlinie der Europäischen Union 2011/65/EU).
:::

<!-- \newpage -->
# Technische Daten des Steuergeräts  

|Parameter                        |	BESCHREIBUNG      |
|:-----------                    |:---------- |
|Versorgungswechselspannung|	85~264VAC 47~63Hz|
|Versorgungsgleichspannung|	120~370VDC|
|Ausgangsspannung|	27,6VDC|
|Maximaler Ausgangsstrom|	1,8A|
|Wirkungsgrad|	85%|
|Maximaler Strom der Steuerausgänge 0-10V|	30mA|
|Maximaler Strom des Ausgangs (Kontakts) ALARM|	3A|
|Überspannungsschutz der Eingänge und Ausgänge|	JA|
|Kurzschlussschutz|	Automatisch |
|Akkumulatorbatterie|	4Ah 24V|
|Betriebstemperaturbereich|	-10 +40oC|
|Geräteabmessungen|	20x15x8 cm|
|Gehäuseschutzart|	IP65|

:::info
Zum Lieferumfang des Steuergeräts IC-AC gehören:
 - Spreizdübel - 	4 St., 
 - Akkumulatoren 12V 4Ah - 	2 St., 
 - Kabelverschraubung PG13,5 -	1 St.,
 - Kabelverschraubung PG11 -	3 St., 
 - Kabelverschraubung PG9 -	3 St.
:::

