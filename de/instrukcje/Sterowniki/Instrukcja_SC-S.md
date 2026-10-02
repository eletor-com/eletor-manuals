---
sidebar_position: 2
title: Anleitung SC-S
description: Klimaregler für Stallräume mit einem zulässigen Ausgangsstrom bis 5A
keywords:
- eletor sc-s
- Lüftungsregler
- Klimaregler
- Lüftungsregler für Schweineställe
- Mikroklimaregler
- Regler für Schweineställe
- Schweinestalllüftung
- Regler für Aufzuchträume
---


# Regler SC-S

Mikroprozessor-Klimaregler aus der Produktfamilie SPEED CONTROL. Zuverlässiger, einfach zu montierender und zu bedienender Regler mit Software in polnischer, englischer, russischer und deutscher Sprache. Das Reglerprogramm ermöglicht die intuitive Einstellung der Parameter: Temperaturen, Intervalllüftung, Zusatzheizung, min./max. Lüftungsstufen und Alarme.

**Parameter und Merkmale:**  
- Lüftung der Gruppe I:
  - max. Strom des Ausgangs für die stufenlose Regelung 6A,
  - thermischer Schutz der Schaltung,
  - Sanftanlauf der Lüftung,
  - Kalibrierung der Mindestdrehzahl
- Lüftung der Gruppe II, potentialfreier Kontakt bis 3A (1 optional)
- Zusatzheizung, potentialfreier Kontakt bis 3A (1 optional)
- Alarmausgänge NO und NC:
  - Meldung eines Ausfalls der Stromversorgung,
  - Meldung der Unter- bzw. Überschreitung der min. oder max. Temperaturschwelle
- 1 Analogeingang zur Temperaturmessung
- 2 Ausgänge 0-10V
- Leistungsaufnahme der Schaltung < 3W
- Hermetisches Gehäuse IP56
- Versorgungsspannung 230VAC 50Hz

## Installation des Reglers  
:::danger 
Während der Installation des Geräts muss die Stromversorgung unbedingt abgeschaltet werden, da die Spannung an einigen Baugruppen lebens- und gesundheitsgefährlich ist.  
Es wird empfohlen, die Installation einer qualifizierten Person zu übertragen.
:::

### Wahl des Montageortes  

Der Montageort ist unter Berücksichtigung der leichten Zugänglichkeit des Geräts für befugte Personen sowie der Unzugänglichkeit für Tiere und Kinder zweckmäßig zu wählen. Auch die klimatischen Bedingungen sind zu berücksichtigen, d. h. das Gerät sollte im Temperaturbereich von -10°C bis 40°C an einem Ort ohne direkte Sonneneinstrahlung betrieben werden. Um das Gerät herum muss die Luft frei zirkulieren können. Zum Gerät gehört ein Temperatursensor. Für die Montage des Temperatursensors gelten einige Regeln:  
- Der Sensor sollte nicht an einem Ort ohne Luftzirkulation oder mit direkter Sonneneinstrahlung montiert werden
- der Sensor sollte nicht an einer tragenden Wand (Außenwand) des Gebäudes montiert werden,
- die Nähe zu wärmeabgebenden Geräten wie Heizkörpern und Lampen ist zu vermeiden,
- der Sensor darf nicht unmittelbar an Türen oder Lüftungsöffnungen angebracht werden,
- der Sensor darf nicht an für Tiere zugänglichen Stellen angebracht werden,
- es wird empfohlen, die Anschlussleitung des Sensors mit Abstand zu den Versorgungsleitungen zu verlegen.

### Montage  

Das Gerät kann unter schwierigen klimatischen Bedingungen betrieben werden. Bei ordnungsgemäßer Montage sind der Regler und der Temperatursensor gegen Umwelteinflüsse beständig.
Bei der Montage sind folgende Punkte zu beachten:  
- vor dem Verschrauben ist die Deckeldichtung zu prüfen,
- der Deckel muss mit allen Schrauben festgeschraubt werden,
- die für den Anschluss des Reglers verwendeten Leitungen sollten rund sein,
- nach dem Anschließen der Leitung sind die Kabelverschraubungen so festzuziehen, dass die Leitung abgedichtet und fixiert wird; die Verwendung von Silikon wird empfohlen,
- nicht verwendete Durchführungen (Kabelverschraubungen) sind zu verschließen,
- der Regler (das Gehäuseunterteil) wird mit 4 Spreizdübeln an einer ebenen Wand befestigt.

## Elektrischer Anschluss  

:::danger 
Vor dem Anschließen der Schaltung ist sicherzustellen, dass die Stromversorgung abgeschaltet ist!
:::

Vor dem Anschließen des Reglers muss der Deckel abgeschraubt und abgenommen werden. Die Leitungen werden durch die Gummiverschraubungen geführt und können anschließend angeschlossen werden. Die Klemmen des Reglers sind in der nachstehenden Abbildung dargestellt.

![Anschluss](./img/Sc-s2.png)

**Der Anschluss AC 230V** wird mit der Stromversorgung (Verteilung) verbunden. Ein Leitungsschutzschalter 1P-B6 sowie Überspannungsableiter des Typs T1 T2 sind erforderlich. Beim Anschluss mehrerer Geräte empfiehlt es sich, die Regler auf verschiedene „Phasen“ (L1, L2, L3) zu verteilen, um die Versorgungsleitung gleichmäßig zu belasten.  
**Der Anschluss FAN** ist direkt mit dem Ventilator zu verbinden; bei der Steuerung mehrerer Ventilatoren darf die Gesamtbelastung 6A nicht überschreiten, und jeder Ventilator muss separat abgesichert sein. PE und N dürfen nicht von der Stromversorgung (Verteilung) abgeführt werden, sondern müssen unbedingt mit den Anschlüssen des Reglers verbunden werden.  
**Der Anschluss FUNCTION** ist ein potentialfreier Relaisausgang; der maximale Kontaktstrom beträgt 6A (bei direkter Steuerung einer Last ist ein externer Leitungsschutzschalter 1P-B6 erforderlich),
er kann für folgende Funktionen verwendet werden:  
- **Zusatzheizung** – der Kontakt schließt, wenn die gemessene Temperatur unter den eingestellten Wert fällt.  
- **Lüftung der Gruppe 2 oder von Berieselungsanlagen** – der Kontakt schließt, wenn die gemessene Temperatur höher als die Summe aus Solltemperatur und Lüftungsband ist.  Der Kontakt schließt, wenn die gemessene Temperatur höher als die Summe aus Solltemperatur und Lüftungsband ist.  

Die nachstehende Abbildung zeigt den Anschluss eines Ventilators der Gruppe 2 oder eines Heizgeräts.  

![Zweite Gruppe](./img/2grupa.png)

**Der Anschluss ALARM** umfasst die potentialfreien Ausgänge NC, C und NO zum Anschluss an eine Alarmzentrale. Der Alarm wird in folgenden Fällen aktiviert:  
- die Temperatur ist zu niedrig oder zu hoch,
- der Regler oder der Temperatursensor ist beschädigt,
- die Versorgungsspannung des Reglers ist ausgefallen;
- der Regler arbeitet fehlerhaft (z. B. Überhitzung des Reglers)  

![Alarm](./img/alarmsc-s.png)  

**Der Anschluss V1 0-10V** dient zum Anschluss von Leistungserweiterungsmodulen oder Ventilatoren mit integrierter Drehzahlregelung. Die Spannung an dieser Klemme ist proportional zur Lüftungsstufe.  
**Der Anschluss V2 0-10V** dient zum Anschluss eines Stellantriebs zum Öffnen der Zuluftklappen.  
**Der Anschluss SENSOR** wird mit 1 Temperatursensor TS3 oder TS5 verbunden; die Polarität spielt keine Rolle.  Es empfiehlt sich, die Messleitungen mit Abstand zu den Versorgungsleitungen zu verlegen.  
**Der Anschluss RS-485** kann zum Aufbau von Lüftungssystemen sowie zur Kommunikation mit einem PC verwendet werden.  

## Funktionsprinzip  

Die Hauptaufgabe des Reglers besteht darin, die Temperatur im Tierhaltungsraum auf dem vom Tierhalter festgelegten Niveau zu halten. Es ist zu beachten, dass der Regler lediglich ein Hilfsmittel zur Gewährleistung optimaler klimatischer Bedingungen im Tierhaltungsraum ist. Die übergeordnete Rolle in diesem Prozess übernimmt jedoch der Tierhalter, der die Geräteeinstellungen an die sich ändernden klimatischen Außenbedingungen und vor allem an die Anforderungen der Tiere im Stallgebäude anpassen sowie den Betriebszustand des Geräts mithilfe der Alarmzentrale überwachen sollte.  

### Erste Inbetriebnahme des Reglers  

:::danger
Bei der ersten Inbetriebnahme des Reglers muss unbedingt der Sperrbereich für den Motorbetrieb eingestellt werden.
:::

Der Regler arbeitet mit Ventilatoren mit einphasigem Asynchronmotor und einer maximalen Gesamtstromaufnahme von 5A zusammen. Nach dem Anschluss der ausgewählten Ventilatoren muss der Benutzer diese auf den Betrieb mit dem Regler abstimmen. Mit anderen Worten ist es erforderlich, die minimale Betriebsstufe (Drehzahl) des Ventilators einzustellen. Diese Funktion heißt **„Sperrbereich“** und wird vom Benutzer einmalig in den **„Erweiterten Einstellungen“** eingestellt. Zur korrekten Durchführung dieses Vorgangs empfiehlt sich die Hilfe einer zweiten Person, die das Verhalten des Ventilators ständig beobachten kann, während die andere Person den Wert des **„Sperrbereichs“** einstellt. Wird der Sperrbereich nicht eingestellt, kann dies zu einem fehlerhaften Betrieb des Geräts führen. Der Wert des **„Sperrbereichs“** kann als korrekt angesehen werden, sobald der vom Ventilator erzeugte Druck die Klappen des Lüftungsschachts leicht anzuheben beginnt. Die Einstellung des **„Sperrbereichs“** muss erneut vorgenommen werden, wenn der an den Regler angeschlossene Ventilator ausgetauscht wird.  

### Periodische Intervalllüftung  

Die Intervalllüftung ist eine vom Regler ausgeführte Funktion, die aktiviert wird, sobald die Raumtemperatur unter die Solltemperatur fällt. Diese Funktion gewährleistet eine zyklische Frischluftzufuhr für die Tiere. Die Intervalllüftung wird durch 3 Parameter definiert:
- **„Betriebszeit“** - legt fest, für wie viele Sekunden der Ventilator eingeschaltet wird,
- **„Pausenzeit“** - legt die Stillstandszeit des Ventilators in Sekunden fest,
- **„Intervalllüftungsstufe“** - legt die Lüftungsleistung während der „Betriebszeit“ fest.  

Die Beispieleinstellung **60s/120s** bedeutet, dass der Ventilator für 60s eingeschaltet wird, mit einer Pause von 120s zwischen den aufeinanderfolgenden Einschaltungen. 

Alle oben genannten Parameter werden vom Benutzer eingestellt. Bei der Einstellung der Intervalllüftungsparameter sind einige Regeln zu beachten:
- die Intervalllüftung wird ausschließlich dann eingeschaltet, wenn die Temperatur im Schweinestall unter die Solltemperatur fällt,
- die grundlegende Funktion der Intervalllüftung besteht darin, den Tieren zyklisch Frischluft zuzuführen, und nicht darin, die Solltemperatur im Raum aufrechtzuerhalten,
- es wird empfohlen, die Räume kurz, aber häufig zu lüften,
- lange Intervalllüftungszeiten sind zu vermeiden, da sie zu übermäßigen Temperaturschwankungen führen können,
- die eingestellten Parameter müssen unbedingt an das Verhalten der Tiere und die Bedingungen sowohl innerhalb als auch außerhalb des Raumes angepasst werden,
- die Intervalllüftungsfunktion kann ausgeschaltet werden; hierzu sind sowohl im Prozentmodus als auch im Zeitmodus an der Stelle für die Intervalllüftungszeit Nullwerte einzustellen, z. B.: 0/120s  

### Stufenlose Lüftung  

Der Regler regelt die Lüftung stufenlos von „Mindestdrehzahl“ bis **„Maximaldrehzahl“** im Bereich von **„Solltemperatur“** bis zur Summe aus **„Solltemperatur“** und **„Lüftungsband“**. Oberhalb dieses Bereichs wird die Lüftung der Gruppe 2 eingeschaltet.  

![Lüftung](./img/wentylacjia.png)  

Oberhalb dieses Bereichs wird die Lüftung der Gruppe 2 eingeschaltet, Wenn die Raumtemperatur unter die **„Solltemperatur“** fällt, führt der Regler eine periodische Intervalllüftung des Raumes durch; bei einem weiteren Temperaturabfall wird die Zusatzheizung eingeschaltet. Alles hängt von den vom Benutzer vorgenommenen Einstellungen ab. Das Reglerprogramm berücksichtigt auch die Zusammenarbeit mit einer Alarmzentrale, die aktiviert werden kann, wenn die Temperatur im Schweinestall von den eingestellten Parametern abweicht.  

## Programmierung des Reglers  

Der Regler verfügt über einen Satz von Standardeinstellungen, die in zwei Fällen in den nichtflüchtigen Speicher geschrieben werden:  
1. Erste Inbetriebnahme des Geräts,  
2. Fehler im Datenspeicher.  
Bei fehlender oder ausgefallener Stromversorgung verliert der Regler die zuvor eingegebenen und gespeicherten Benutzereinstellungen nicht.  

### Bedienung des Menüs  

Der Regler ist mit einer Reihe von Funktionen ausgestattet, die seine Anpassung an die jeweilige Anwendung ermöglichen. Diese Funktionen sind in einem Menü zusammengefasst, das durch Drücken einer der Tasten **(„ Pfeil rechts“, „Pfeil links“)** aufgerufen wird. Die Parameter werden mit den Tasten **„+“ und „-“** geändert; der bearbeitete Parameter wird nach Ablauf von **30s** seit dem letzten Tastendruck automatisch im nichtflüchtigen Speicher gespeichert.  

### Funktionen des Grundmenüs  

| MENÜ                       | Beschreibung | 
|:---:                       |:---|
|Temperatur  <br />20,8°C W16% A  |**„Informationsmodus“** - normaler Betrieb. Auf dem Display werden die aktuelle Temperatur und, bei eingeschaltetem Ventilator, der Wert der Lüftungsstufe angezeigt. Bedeutung der zusätzlichen Symbole: A-bedeutet aktivierter Alarm, D  - bedeutet eingeschaltete Heizung, W - bedeutet zusätzliche Lüftung| 
|Solltemp.  <br />20,0°C        |**„Solltemperatur“** – Temperaturwert, der den Beginn der stufenlosen Lüftung festlegt.   | 
|Intervalllüftung  <br />20s / 200s  |**„Intervalllüftung“** – es werden zwei Zeitwerte eingestellt: 1 „Betriebszeit“, 2 „Pausenzeit“ zwischen den aufeinanderfolgenden zyklischen Einschaltungen der Lüftung.| 
|Intervalllüftungsstufe  <br />20%        |**„Intervalllüftungsstufe“** - Lüftungsstufe während des Betriebs der Intervalllüftung   | 
|Minimumalarm  <br />12,0°C       |**„Minimumalarm“** - legt die absolute Mindesttemperatur fest, bei der der Alarm aktiviert wird. 
|Maximumalarm  <br />28,0°C       |**"Maximumalarm"** - legt die absolute Höchsttemperatur fest, bei der der Alarm aktiviert wird.  | 
|Zusatzheizung  <br />12,0°C         |Je nach Konfiguration werden folgende Funktionen ausgeführt: **„Zusatzheizung“** - der Kontakt schließt, wenn die Temperatur unter den angezeigten Wert fällt. | 
|Lüftung der Stufe 2  <br />25,0  |**„Lüftung der Stufe 2“** - der Kontakt schließt, wenn die gemessene Temperatur die Summe aus Solltemperatur und Lüftungsband überschreitet. | 
|Lüftungsband  <br />5,0°C     |**„Lüftungsband“** - legt die Reaktionsgeschwindigkeit des Reglers (Änderung der Lüftungsstufe vom Minimum 1 bis zum Maximum 1) auf eine steigende Temperatur fest. | 
|Mindestdrehzahl  <br />1%        |**„Mindestdrehzahl“** – dies ist ein Zustand, in dem das Gerät für unbestimmte Zeit verbleibt und am Ausgang eine Spannung mit dem eingestellten Wert ausgibt. Dient zur Kalibrierung des Geräts mit dem Motor und dem Klappenmechanismus.   | 
|Maximaldrehzahl  <br />100%      |**„Maximaldrehzahl“** – dies ist ein Zustand, in dem das Gerät für unbestimmte Zeit verbleibt und am Ausgang eine Spannung mit dem eingestellten Wert ausgibt. Dient zur Begrenzung der für die Lüftung vorgesehenen Leistung| 

### Erweitertes Menü  

Das erweiterte Menü ist hauptsächlich für Installateure vorgesehen und ermöglicht die Anpassung des Reglers an die Anlage und den Ventilator. Die erweiterten Einstellungen werden durch gleichzeitiges Drücken und Halten der beiden Menütasten für etwa 10s aufgerufen.  

| MENÜ                                 | Beschreibung| 
|:---:                                 |:--- |
|Keine erweiterten  <br />Einstellungen   |Diese Meldung zeigt an, dass der Regler nicht auf die Lüftung kalibriert wurde und möglicherweise nicht ordnungsgemäß arbeitet. Das erweiterte Menü muss aufgerufen und der „Sperrbereich“ eingestellt werden.|
|Erweiterte <br />Einstellungen         |Anzeige des Aufrufs der erweiterten Einstellungen. | 
|Software Ver:  <br />1907       |Information zur Softwareversion.| 
|Sperrbereich  <br />1000 us       |Kalibrierung der Mindestdrehzahl der direkt an den Regler angeschlossenen Ventilatoren; dieser Parameter entspricht der Lüftungsstufe „1%“|  
|Kontaktfunktion  <br />Zusatzheizung     |Auswahl der Kontaktfunktion:  <br />• Zusatzheizung (Standard)<br />• Lüftungsgruppe 2 | 
|Intervalllüftung  <br />Zeitgesteuert         |Auswahl der Art der Intervalllüftung: <br />• Zeitgesteuert (Standard) <br />• Prozentual| 
|Bereich V1  <br />von 2,0 bis 10,0       |Einstellung des Spannungsänderungsbereichs am Ausgang V1 0÷10V. Die Einstellungen betreffen den minimalen und maximalen Spannungswert. Die Einstellung dient zur Anpassung des Reglers an eine Leistungserweiterung oder einen Frequenzumrichter.| 
|Invertierung V1  <br />Nein                |Die Aktivierung bewirkt eine Umkehrung der Kennlinie des Ausgangs V1. Die Spannung sinkt mit steigender Lüftungsstufe innerhalb des durch Min.-Max. vorgegebenen Bereichs. Das Signal am Ausgang V1 ist vom Typ 10-0V.| 
|Abschaltung V1  <br />Nein                |Die Aktivierung bewirkt, dass am Ausgang  V1 0-10V der Pegel 0V anstelle des eingestellten Mindestwerts ausgegeben wird, wenn die Lüftungsstufe 0% beträgt.| 
|Bereich V2  <br />von 2,0 bis 10,0       |Einstellung des Spannungsänderungsbereichs am Ausgang V2 0÷10V. Die Einstellungen betreffen den minimalen und maximalen Spannungswert. Die Einstellung dient zur Kalibrierung des Klappensystems.|
|Invertierung V2  <br />Nein      	       |Die Aktivierung bewirkt eine Umkehrung der Kennlinie des Ausgangs V2. Die Spannung sinkt mit steigender Lüftungsstufe innerhalb des durch Min.-Max. vorgegebenen Bereichs. Das Signal am Ausgang V2 ist vom Typ 10-0V.|
|Temp.-Kalibrierung  <br />21,0°C -> 22,0°C|Die Kalibrierung des Temperatursensors ermöglicht eine Neuskalierung des abgelesenen Werts.|
|Sanftanlauf  <br />50%      	           |Festlegung der Lüftungsstufe bei jedem Start des Ventilators; der Ventilator wird auf den angegebenen Wert beschleunigt und wechselt anschließend auf die eingestellte Stufe.| 
|Sprache  <br />Polnisch    	           |Auswahl der Menüsprache: Polnisch, Englisch, Deutsch, Russisch|
|Beenden                               |Verlassen des erweiterten Menüs mit der Taste „+“; die vorgenommenen Änderungen werden im nichtflüchtigen Speicher gespeichert.|

### Fehler- und Warnmeldungen  

Fehlermeldungen dienen dazu, den Benutzer über Unregelmäßigkeiten im Betrieb des Reglers zu informieren. Nachstehend sind die möglichen Fehlermeldungen aufgeführt.  

|FEHLER                                    | BESCHREIBUNG |
|:---:                                   |:--- |
|Überlast-  <br />alarm 	         |Überlastalarm, aktiviert bei 75°C. Das Gerät stellt den Betrieb bis zum Abkühlen ein.|
|SENSOR UNTERBROCHEN!  <br />Sensor prüfen|Sensor unterbrochen; weist auf eine Beschädigung des Sensors oder der Anschlussleitung hin.|
|SENSOR KURZGESCHLOSSEN!  <br />Sensor prüfen  |Sensor kurzgeschlossen; weist auf eine Beschädigung des Sensors oder der Anschlussleitung hin.|
|Ausfall der  <br />Stromversorgung                  |Ausfall der Stromversorgung, zu niedrige Versorgungsspannung, falsche Frequenz oder stark verzerrte Versorgungsspannung.| 

## Hinweise und Warnungen  

:::danger 
Während der Installation des Geräts muss die Stromversorgung unbedingt abgeschaltet werden, da die Spannung an einigen Baugruppen lebens- und gesundheitsgefährlich ist. Es wird empfohlen, die Installation einer qualifizierten Person zu übertragen.
:::

- Um Probleme beim Betrieb des Geräts zu vermeiden, muss die Anleitung vor der Installation und Verwendung gelesen werden.  
- Eingriffe in die Konstruktion oder eigenständige Reparaturen sind nicht zulässig. Dies gilt insbesondere für Änderungen an Bauteilen und Baugruppen.  
- Wartungs- oder Servicearbeiten sind von befugtem Personal (Installateur oder Werkskundendienst) durchzuführen. In Stallgebäuden mit Zwangslüftung ist ein Alarmsystem erforderlich. Der Gerätehersteller haftet nicht für Schäden, die durch unsachgemäße Installation, fehlerhafte Programmierung der Funktionen, Folgen unvorhersehbarer Ereignisse oder äußere Faktoren verursacht werden.  
- Die Parameter des Lüftungsreglers müssen entsprechend den Bedingungen im Tierhaltungsraum eingestellt werden. Diese Einstellungen sind individuell und hängen von der Entscheidung des Tierhalters ab. Der Gerätehersteller behält sich das Recht vor, Änderungen an der Gerätekonstruktion und der Software vorzunehmen.  


:::caution
![Alternativtext](./img/trash.svg) Nach dem Ende der Nutzungsdauer darf das Produkt nicht zusammen mit unsortierten Siedlungsabfällen entsorgt werden, sondern muss gemäß den geltenden Vorschriften entsorgt werden (WEEE-Richtlinien der Europäischen Union 2012/19/EU). <br />Das Produkt wurde gemäß den RoHS-Anforderungen hergestellt (Richtlinie der Europäischen Union 2011/65/EU).
:::

<!-- \newpage -->
## Technische Daten des Reglers  

|Parameter                        |	BESCHREIBUNG      |
|:-----------                    |:---------- |
|Versorgungsspannung|	230VAC 50Hz|
|Maximaler Strom des Ausgangs für die stufenlose Regelung FAN|	6A|
|Regelbereich der Ausgangsspannung|	70V ÷ (Uz-5)V|
|Maximaler Ausgangsstrom (Kontaktstrom) ALARM|	3A|
|Maximaler Ausgangsstrom (Kontaktstrom) FUNCTION|	3A|
|Betriebstemperaturbereich|	-20 +40oC|
|Temperaturmessbereich|	0 +50°C|
|Auflösung der Temperaturmessung|	0,1°C|
|Erkennung von Schäden am Temperatursensor|	JA|
|Maximale Anzahl analoger Sensoren|	1|
|Genauigkeit der Temperaturmessung – Analogeingang|	1°C|
|Abhängigkeit der Messung vom Leitungswiderstand – Analogeingang|	15,8Ω/°C|
|Überspannungsfestigkeit (max E)|	210J|
|Überlastschutz|	75°C|
|Geräteabmessungen|	20x15x8 [cm]|
|Schutzart des Gehäuses|	IP56|
  


:::info
Der Lieferumfang des Reglers SPEED CONTROL SERVOMOTOR umfasst:
- 1 Temperatursensor + Zubehör,
- 4 Spreizdübel,
- 1 Sicherung 10A.
:::

