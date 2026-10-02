---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Die häufigsten Fragen zur Auswahl, Konfiguration, Diagnose und Wartung
  von Geräten ELETOR.
keywords:
- ELETOR
- FAQ
- Lüftungsregler
- Regler
- Ventilatoren
- Stellantriebe
- Alarme
- Frequenzumrichter
- Service
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Häufig gestellte Fragen

Das FAQ wurde auf Grundlage einer anonymisierten Analyse realer Gespräche mit Benutzern und Kunden ELETOR erstellt. Die Antworten wurden verallgemeinert, damit sie in typischen Fällen helfen und keine Daten konkreter Personen oder Anlagen enthalten.

:::note Umfang des FAQ

Die Antworten betreffen typische Fälle. Klemmenbezeichnungen, Funktionen und Anschlussart können sich zwischen Modellen und Geräteversionen unterscheiden. Verwenden Sie im Zweifelsfall die Dokumentation des jeweiligen konkreten Produkts.

:::

:::warning Sicherheit

Arbeiten an der elektrischen Anlage sind gemäß der Gerätedokumentation und den geltenden Sicherheitsregeln auszuführen. Arbeiten an Netzspannung sollten von einer Person mit entsprechender Qualifikation durchgeführt werden.

:::

## Auswahl des Reglers und der Leistung

### Wie wählt man den Regler für Ventilatoren aus?

Grundlage der Auswahl ist vor allem der Gesamtstrom der Ventilatoren und nicht ausschließlich deren Anzahl.

:::tip Daten vor der Auswahl vorbereiten

Je genauer die Daten zu den Motoren und zur Betriebsweise der Anlage, desto sicherer die Reglerauswahl.

:::

Vor der Auswahl sollten folgende Daten vorbereitet werden:

- Anzahl der Ventilatoren,
- Versorgungsspannung,
- Nennleistung oder Nennstrom jedes Ventilators,
- Information, ob alle Ventilatoren stufenlos arbeiten sollen,
- Information, ob die Ventilatoren in Gruppen aufgeteilt werden können,
- Informationen zu zusätzlichen Geräten, z. B. Heizgeräten oder Lufteinlässen.

Der Regler sollte nicht exakt „auf Kante“ ausgewählt werden. Es ist eine angemessene Reserve gegenüber der maximalen Last einzuhalten.

### Reicht es aus, die Ventilatorleistungen in Watt zu addieren?

Für eine vorläufige Abschätzung kann die Leistung verwendet werden, die endgültige Auswahl sollte sich jedoch auf den Nennstrom der Geräte und den Charakter der Last stützen.

Der Motor kann beim Anlauf mehr Strom aufnehmen als im Normalbetrieb. Deshalb sind zwei Ventilatorsätze mit ähnlicher Nennleistung nicht immer eine gleichwertige Last für den Regler.

### Ich habe mehrere kleine Ventilatoren. Kann ich sie parallel an einen Ausgang anschließen?

Ja, wenn:

- sie für diese Art der Ansteuerung vorgesehen sind,
- sie gemeinsam arbeiten sollen,
- die Summe der Lasten den zulässigen Ausgangsstrom nicht überschreitet,
- die Anschlussart mit der Dokumentation des Reglers übereinstimmt.

Bei einer größeren Anzahl von Ventilatoren sollte eine Aufteilung in Gruppen oder der Einsatz einer Leistungserweiterung erwogen werden.

### Wann ist eine Leistungserweiterung erforderlich?

Eine Leistungserweiterung wird verwendet, wenn die Last die Möglichkeiten des Reglerausgangs übersteigt oder wenn die Anlage um eine größere Anzahl von Ventilatoren erweitert werden soll.

Der Regler gibt dann das Steuersignal aus, während die eigentliche Last von einem zusätzlichen Modul übernommen wird.

### Kann die Anlage später um zusätzliche Ventilatoren erweitert werden?

In vielen Anlagen ja. Am häufigsten verwendet werden:

- eine zusätzliche Leistungserweiterung,
- eine zusätzliche Lüftungsgruppe,
- ein Schütz zum Zuschalten einer weiteren Gruppe,
- ein Frequenzumrichter bei Drehstrommotoren.

Die geplante Erweiterung sollte bereits bei der ersten Auswahl des Reglers berücksichtigt werden.

### Müssen alle Ventilatoren stufenlos arbeiten?

Nein. Typisch sind zwei Lösungen:

1. alle Ventilatoren arbeiten stufenlos,
2. die erste Gruppe arbeitet stufenlos, und weitere Gruppen werden schrittweise zugeschaltet, z. B. über Schütze.

Die zweite Lösung ermöglicht die Ansteuerung einer größeren Anlage ohne stufenlose Regelung jedes einzelnen Ventilators.

### Ich habe 10 Ventilatoren. Benötige ich einen sehr großen Regler?

Nicht immer. Es können mehrere Steuerungsarten eingesetzt werden:

- Aufteilung in Gruppen,
- Leistungserweiterungen,
- Schütze,
- Frequenzumrichter.

Die endgültige Auswahl hängt von den elektrischen Parametern der Ventilatoren sowie davon ab, ob alle gleichzeitig ihre Drehzahl ändern sollen.

### Unterscheiden sich der Regler 6 A und 12 A nur in der zulässigen Belastung?

Es sollte nicht angenommen werden, dass der einzige Unterschied der Stromwert ist. Einzelne Versionen und Generationen der Geräte können sich in der Ausstattung oder Ausführung unterscheiden.

Beim Austausch des Geräts sind das genaue Modell und die aktuelle Dokumentation zu prüfen.


## Ventilatoren und Lüftungssteuerung

### Regelt der Regler die Ventilatoren stufenlos?

Bei Reglern, die für die stufenlose Lüftungsregelung vorgesehen sind, wird die Ventilatordrehzahl in Abhängigkeit vom Bedarf geändert, der sich u. a. aus der Temperatur ergibt.

Es ist jedoch zu prüfen, ob der jeweilige Motortyp für die verwendete Regelungsart geeignet ist.

### Was bedeutet Solltemperatur?

Die Solltemperatur ist der Wert, auf den der Regler die aktuelle Temperaturmessung bezieht.

Auf dieser Grundlage erhöht oder verringert der Regler die Lüftungsintensität entsprechend den übrigen Einstellungen, z. B. Regelband, Mindest- und Höchstwert.

### Was bedeutet minimaler Lüftungsgrad?

Dies ist der minimale Wert der Ventilatoransteuerung im Automatikbetrieb.

Diese Einstellung verhindert den Betrieb unterhalb eines Niveaus, bei dem der Ventilator instabil arbeiten oder einen zu geringen Luftaustausch gewährleisten könnte.

### Was bedeutet maximaler Lüftungsgrad?

Dies ist die obere Begrenzung des Lüftungssteuerwerts.

Beispielsweise kann die Einstellung eines Werts unter 100% die maximale Drehzahl des Ventilators begrenzen, wenn dies von der Anlage gefordert wird.

### Was bedeutet Lüftungsband?

Das Lüftungsband legt den Temperaturbereich fest, in dem der Regler vom minimalen zum maximalen Lüftungsgrad übergeht.

Je kleiner das Band, desto schneller reagiert die Regelung mit einer Leistungssteigerung auf eine Temperaturänderung.

### Der Ventilator geht nach dem Start zunächst auf 100% und wird erst danach langsamer. Warum?

Es kann eine Anlauffunktion aktiv sein, deren Aufgabe darin besteht, den Motor kurzzeitig mit höherer Leistung zu starten.

Je nach Reglerausführung sind Einstellungen in Bezug auf Folgendes zu prüfen:

- die Funktion Soft Start,
- die Hochlaufzeit,
- die Betriebszeit bei 100%,
- die Auslaufzeit.

Wenn die Funktion in der betreffenden Anlage nicht erforderlich ist, können die entsprechenden Parameter gemäß der Geräteanleitung geändert werden.

### Wozu kann der Ventilator beim Start kurzzeitig mit voller Leistung anlaufen?

Ein solcher Anlauf kann einen sicheren Start des Ventilators unterstützen sowie in Anlagen hilfreich sein, in denen mechanische Elemente beim Start einen höheren Widerstand verursachen können.

Dies ist jedoch nicht in jeder Anlage erforderlich.

### Was bedeuten Hochlaufzeit und Auslaufzeit?

**Hochlaufzeit** bestimmt, wie die Ansteuerung beim Start des Ventilators ansteigt.

**Auslaufzeit** bestimmt, wie die Drehzahl verringert wird.

Beide Parameter ermöglichen es, abrupte Änderungen der Drehzahl und des Anlagenbetriebs zu begrenzen.

### Warum können zwei identische Regler die Ventilatoren unterschiedlich starten?

Die häufigste Ursache sind unterschiedliche Einstellungen.

Insbesondere sollten folgende Punkte verglichen werden:

- Solltemperatur,
- Lüftungsband,
- Minimum und Maximum,
- Einstellungen für Soft Start,
- Hochlauf- und Auslaufzeiten,
- die Konfiguration der Lüftungsgruppen.

### Kann der Regler die Lüftung in regelmäßigen Abständen unabhängig von der Temperatur einschalten?

Je nach Modell ist eine Funktion für periodisches Lüften verfügbar.

Sie kann die Lüftung in festgelegten Intervallen für eine bestimmte Zeit einschalten, auch wenn die Temperaturregelung keine Erhöhung der Lüftung erfordert.

### Wozu dienen Lüftungsgruppen?

Gruppen ermöglichen eine schrittweise Erhöhung der Anlagenleistung.

Beispielsweise:

- Gruppe 1 arbeitet stufenlos,
- Gruppe 2 schaltet weitere Ventilatoren ein,
- die nächste Gruppe wird bei noch höherem Bedarf eingeschaltet.

Dies ermöglicht die Steuerung einer großen Anzahl von Ventilatoren ohne stufenlose Regelung jedes einzelnen.

### Kann eine zusätzliche Ventilatorgruppe über ein Schütz zugeschaltet werden?

Ja. Der Relaisausgang des Reglers kann die Spule eines entsprechend ausgewählten Schützes ansteuern.

Die Ventilatorlast sollte dann nicht direkt über den kleinen Steuerkontakt geführt werden.

### Was bedeutet das Ventilatorsymbol oder die gelbe Kontrollleuchte am Regler?

Je nach Modell informieren die Kontrollleuchten über den aktuellen Zustand der Ausgänge und Funktionen.

Die gelbe Signalisierung kann eine aktive Betriebsfunktion bedeuten, z. B. Lüftung, Heizung oder die nächste Gruppe.

Die genaue Bedeutung ist in der Anleitung des jeweiligen Modells nachzulesen.

### Was bedeutet das Symbol des Handbetriebs?

Handbetrieb bedeutet, dass der Steuerwert vom Benutzer erzwungen wurde und derzeit nicht automatisch auf Grundlage der Temperatur berechnet wird.

Nach Abschluss der Tests ist sicherzustellen, dass der Regler in den korrekten Automatikbetrieb zurückversetzt wurde.


## Lufteinlässe und Stellantriebe

### Kann der Regler Lufteinlässe steuern?

Ja, ausgewählte Regler ermöglichen die Zusammenarbeit mit Antrieben für Lufteinlässe.

Die Anschlussart hängt vom Typ des Stellantriebs und von seiner Ansteuerungsart ab.

### Welche Arten von Stellantrieben können für Lufteinlässe verwendet werden?

In technischen Gesprächen traten am häufigsten zwei Lösungen auf:

- Stellantrieb, gesteuert durch ein analoges Signal 0–10 V oder 2–10 V,
- reversierender Auf/Zu-Stellantrieb mit Rückmeldesignal, z. B. von einem Potentiometer.

Vor dem Kauf ist die Kompatibilität des konkreten Modells mit dem vorhandenen Regler zu prüfen.

### Ist die Versorgungsspannung des Stellantriebs 24 V oder 230 V für das Signal 0–10 V von Bedeutung?

Steuersignal und Versorgung des Stellantriebs sind getrennte Parameter.

Der Stellantrieb kann mit einer anderen Spannung versorgt werden als der Spannung des Steuersignals. Beide Parameter müssen mit der Dokumentation des Stellantriebs und des Reglers übereinstimmen.

### Was bedeutet Steuerung 0–10 V?

Der Regler sendet ein analoges Spannungssignal, das die gewünschte Position oder den gewünschten Steuergrad repräsentiert.

In der typischen Anwendung bedeutet ein niedrigerer Wert eine geringere Öffnung und ein höherer Wert eine größere Öffnung, die tatsächliche Kennlinie ist jedoch in der Dokumentation des Stellantriebs zu prüfen.

### Worin unterscheidet sich 0–10 V von 2–10 V?

In beiden Fällen wird die Position durch ein analoges Signal vorgegeben.

Beim Standard 2–10 V ist der untere Bereich verschoben und kann es dem Gerät ermöglichen, das Steuersignal von dessen Fehlen zu unterscheiden.

Regler und Stellantrieb müssen denselben Bereich unterstützen.

### Wie ist ein Stellantrieb entsprechend der Anzahl der Einlässe auszuwählen?

Der Stellantrieb darf nicht ausschließlich auf Grundlage der Anzahl der Klappen ausgewählt werden.

Zu berücksichtigen sind:

- erforderliche Kraft oder erforderliches Drehmoment,
- Länge und Führung der Mechanik,
- Widerstände der Klappen,
- Hublänge,
- Arbeitsgeschwindigkeit,
- Versorgungsspannung,
- Steuerungsart,
- erforderliche Rückmeldung.

### Kann ein Stellantrieb mehrere Klappen betätigen?

Ja, wenn die Mechanik der Anlage es erlaubt, die Klappen über ein gemeinsames System zu verbinden, und das erforderliche Drehmoment bzw. die erforderliche Kraft die Möglichkeiten des Stellantriebs nicht überschreitet.

In der Praxis entscheiden die Widerstände des gesamten Mechanismus über die Auswahl und nicht allein die Anzahl der Klappen.

### Können mehrere Stellantriebe parallel geschaltet und mit einem Signal angesteuert werden?

In einigen Systemen ist dies möglich, jedoch sind die Dokumentation der Stellantriebe sowie die zulässige Belastung des Steuerausgangs zu prüfen.

Bei reversierenden Antrieben ohne unabhängige Rückmeldung kann es außerdem zu einem allmählichen Auseinanderlaufen der Positionen der einzelnen Stellantriebe kommen.

### Warum können mehrere Stellantriebe sich im Laufe der Zeit in unterschiedliche Positionen einstellen?

Selbst identische Motoren können mit leicht unterschiedlicher Geschwindigkeit arbeiten aufgrund von:

- unterschiedlicher Belastung,
- mechanischen Widerständen,
- Toleranzen der Motorparameter,
- Unterschieden im Getriebe.

Deshalb sind bei erforderlicher genauer Synchronisation eine geeignete Rückmeldung oder eine individuelle Positionskontrolle erforderlich.

### Können die Einlässe proportional zur Lüftung gesteuert werden?

Ja. In entsprechend konfigurierten Systemen kann die Position der Einlässe mit dem aktuellen Lüftungsgrad verknüpft werden.

Dadurch wird zusammen mit der steigenden Ventilatorleistung auch die Öffnung der Einlässe vergrößert.

### Benötigt der Stellantrieb 24 V ein separates Netzteil?

Wenn der Regler keinen geeigneten Versorgungsausgang mit der erforderlichen Leistung besitzt, ist ein separates Netzteil erforderlich.

Seine Leistung ist auf die Stromaufnahme des Stellantriebs sowie anderer Geräte auszulegen, die aus derselben Quelle versorgt werden.

### Kann ein Stellantrieb eines anderen Herstellers verwendet werden?

Häufig ja, wenn seine elektrischen Parameter und die Art der Ansteuerung mit den Ausgängen des Reglers kompatibel sind.

Vor dem Anschluss sind zu prüfen:

- Spannung,
- Signaltyp,
- Verdrahtungsplan,
- Bewegungsrichtungen,
- Positionssignal,
- zulässige Belastung.


## Temperatur- und Feuchtesensoren

### Wo ist der Temperatursensor anzuschließen?

Der Sensor ist an den vom Hersteller vorgesehenen Sensoreingang anzuschließen, also an den in der Dokumentation des jeweiligen Modells angegebenen Sensoreingang.

Es darf nicht angenommen werden, dass die Klemmenbezeichnungen in allen Geräteversionen identisch sind.

### Der Temperatursensor zeigt einen anderen Wert als ein Referenzthermometer. Was ist zu tun?

Wenn der Regler über eine Funktion zur Sensorkalibrierung verfügt, kann die Anzeige korrigiert werden, nachdem sie mit einem zuverlässigen Referenzthermometer verglichen wurde.

Vor der Änderung der Kalibrierung ist sicherzustellen, dass:

- sich beide Sensoren am selben Ort befinden,
- sich der Messwert stabilisiert hat,
- der Sensor nicht durch Sonne oder Geräte erwärmt wird,
- er sich nicht direkt im Strom kalter oder heißer Luft befindet.

### Der Feuchtesensor zeigt einen falschen Wert an. Kann er kalibriert werden?

Dies hängt von der Version des Reglers, des Sensors und der Software ab.

Bei einigen Lösungen kann die Korrektur eine entsprechende Softwarefunktion oder einen kompatiblen Sensortyp erfordern. Wenn die Abweichung groß und reproduzierbar ist, sind die Geräteversion zu prüfen und der technische Support zu kontaktieren.

### Bedeutet eine fehlerhafte Messung immer einen defekten Sensor?

Nein.

Die Ursache kann auch sein:

- eine falsche Sensorposition,
- die Leitung,
- die elektrische Verbindung,
- die Konfiguration,
- ein ungeeigneter Sensortyp,
- die Notwendigkeit einer Kalibrierung,
- Feuchtigkeit oder Korrosion.


## Alarme und Benachrichtigungen

### Kann an den Alarmausgang des Reglers direkt eine Sirene angeschlossen werden?

Davon sollte nicht ausgegangen werden.

Der Alarmausgang des Reglers ist in der Regel ein Steuerausgang oder ein Relaiskontakt. Die Sirene kann eine separate Versorgung sowie eine Alarmzentrale erfordern.

### Wozu wird eine Alarmzentrale eingesetzt?

Die Zentrale kann:

- Alarmsignale von Reglern empfangen,
- den Signalgeber versorgen,
- den Betrieb bei Netzausfall aufrechterhalten,
- einen Alarm akustisch oder optisch signalisieren,
- GSM-Benachrichtigungen senden, sofern diese Funktion in der jeweiligen Version vorhanden ist.

### Kann die Zentrale einen Netzausfall des Reglers melden?

Ja, wenn das System entsprechend angeschlossen wurde.

Die Lösung kann nicht nur eine Temperaturüberschreitung, sondern auch den Signalverlust des Reglers infolge eines Versorgungsausfalls erkennen.

### Wo werden die minimale und maximale Alarmtemperatur eingestellt?

In der typischen Konfiguration werden die Alarmschwellen im Regler eingestellt, der die betreffende Kammer oder den betreffenden Raum überwacht.

Die Alarmzentrale erhält dann die Information, dass der Regler einen Alarm gemeldet hat.

### Benötigt die GSM-Zentrale eine SIM-Karte?

Für das Senden von Anrufen und Nachrichten über das Mobilfunknetz ist eine aktive SIM-Karte oder eine andere im jeweiligen Modell vorgesehene Kommunikationslösung erforderlich.

Ohne aktive Verbindung zum Mobilfunknetz funktionieren Telefon- und SMS-Funktionen nicht.

### Kann der Alarm Informationen darüber senden, von welchem Regler das Ereignis stammt?

In einem entsprechend konfigurierten System ja.

Die Eingänge der Zentrale können bestimmten Räumen oder Reglern zugeordnet werden, sodass die Meldung die Bestimmung der Alarmquelle ermöglicht.

### Wie viele Regler können an eine Alarmzentrale angeschlossen werden?

Das hängt vom Modell der Zentrale ab.

In den Transkripten kamen Zentralen mit bis zu acht Eingängen vor, vor der Installation ist jedoch die aktuelle Spezifikation des konkreten Geräts zu prüfen.

### Welcher Akku wird in der Alarmzentrale verwendet?

In einem Teil der in Gesprächen behandelten Geräte wurde ein Akku 12 V 7 Ah verwendet.

Vor dem Kauf eines Ersatzakkus sind die Bezeichnung auf dem vorhandenen Akku sowie die Spezifikation der Zentrale zu prüfen, da andere Geräteversionen einen anderen Akku erfordern können.

### Die Zentrale sendet Meldungen über niedrige Spannung. Was ist zu prüfen?

Zunächst sind zu prüfen:

- der Zustand des Akkus,
- sein Alter,
- die Akkuverbindungen,
- das Vorhandensein der Netzversorgung,
- die Funktion des Ladegeräts oder Netzteils der Zentrale.

Ein verbrauchter Akku kann zyklische Meldungen über niedrige Spannung verursachen.

### Wie oft ist der Akku in der Alarmzentrale auszutauschen?

Es gibt keinen einheitlichen Wert, der für alle Bedingungen geeignet ist.

Der Akku ist regelmäßig zu testen, insbesondere in Anlagen, in denen ein Alarm bei Versorgungsausfall von kritischer Bedeutung ist. Mit zunehmendem Alter sinkt seine tatsächliche Kapazität.

### Reicht die Sirene allein als Absicherung aus?

Die Sirene wirkt nur dann, wenn sie jemand hören kann.

In Objekten, die zeitweise unbeaufsichtigt sind, sollten zusätzlich eine Fernbenachrichtigung und eine Akku-Pufferung eingesetzt werden.


## Frequenzumrichter

### Wie ist ein Frequenzumrichter für Ventilatoren auszuwählen?

Folgende Angaben müssen bekannt sein:

- Versorgungsspannung,
- Anzahl der Phasen,
- Leistung und Strom aller Motoren,
- Art ihrer Verschaltung,
- Betriebsbedingungen,
- erforderliche Steuerungsart.

Der Frequenzumrichter sollte eine angemessene Reserve gegenüber der Last haben, insbesondere wenn mehrere Motoren parallel arbeiten.

### Sollte der Frequenzumrichter genau die gleiche Leistung wie die Summe der Motorleistungen haben?

Ein Frequenzumrichter sollte nicht ausschließlich auf der Grundlage der einfachen Summierung der Leistung ausgewählt werden, und es sollte kein Gerät gewählt werden, das exakt an der Grenze seiner Parameter arbeitet.

Zu berücksichtigen sind Nennströme, Lastcharakter und die Empfehlungen des Herstellers des Frequenzumrichters.

### Der Frequenzumrichter hat die Ventilatoren gestoppt und einen Fehler angezeigt. Was ist zu tun?

Am wichtigsten ist es, vor dem Reset den vollständigen Fehlercode zu notieren.

:::tip Machen Sie ein Foto des Bildschirms

Wenn es die Situation zulässt, machen Sie vor dem Reset ein Foto des Displays. Der vollständige Fehlercode erleichtert die Diagnose erheblich.

:::

Der reine Anfang der Meldung reicht oft nicht aus, um die Ursache festzustellen. Der vollständige Code ermöglicht unter anderem die Unterscheidung zwischen:

- Überlast,
- Stromüberschreitung,
- Überhitzung,
- unzulässiger Spannung,
- anderen Antriebsfehlern.

### Kann der Fehler des Frequenzumrichters einfach zurückgesetzt werden?

Ein Reset kann den Betrieb wiederherstellen, beseitigt jedoch nicht die Ursache des Alarms.

Nach dem Ereignis sind der Fehlercode zu prüfen und die Ursache zu ermitteln, bevor die Anlage erneut über längere Zeit in Betrieb genommen wird.

### Der Frequenzumrichter arbeitet in einem staubigen Raum. Muss er gereinigt werden?

Ja.

Staub und Ablagerungen am Kühlkörper oder am Kühlventilator können die Wärmeabfuhr verschlechtern und zu einer Überhitzung des Frequenzumrichters führen.

Die Reinigung ist gemäß der Anleitung des Herstellers nach sicherer Trennung der Versorgung durchzuführen.

### Was kann die Überhitzung des Frequenzumrichters verursachen?

Die häufigsten Ursachen sind:

- verschmutzte Kühlelemente,
- ein behinderter Luftstrom,
- zu hohe Umgebungstemperatur,
- Überlast,
- Schaden am Kühlventilator,
- fehlerhafte Montage.

### Kann erhöhte Netzspannung einen Alarm des Frequenzumrichters auslösen?

Ja. Frequenzumrichter überwachen die Spannung des Versorgungskreises und können bei Überschreitung des zulässigen Niveaus einen Fehler melden.

Wenn das Problem wiederholt auftritt, sind die Installation und die Versorgungsqualität zu überprüfen.


## Störungen und Diagnose

### Der Regler funktioniert, aber das Display zeigt nichts an. Was kann die Ursache sein?

Mögliche Ursachen sind unter anderem:

- ein beschädigtes Display,
- ein Problem mit der Kontrasteinstellung in älteren Lösungen,
- eine beschädigte Verbindung,
- Korrosion,
- eine beschädigte Hauptplatine.

Wenn das Gerät über längere Zeit nicht verwendet wurde oder in einer feuchten Umgebung betrieben wurde, sollte auch der Zustand der Platine geprüft werden.

### Der Regler hat nach mehreren Jahren ohne Nutzung Probleme mit dem Display. Warum?

Längerer Stillstand in feuchter oder aggressiver Umgebung kann führen zu:

- Oxidation der Steckverbinder,
- Korrosion,
- Verschlechterung der Kontakte,
- Schäden an elektronischen Bauteilen.

In einem solchen Fall sollte eine vollständige Inspektion durchgeführt und nicht ohne vorherige Diagnose Komponenten ausgetauscht werden.

### Der Regler ist nach einer Überspannung verrußt. Bedeutet das, dass die Platine ersetzt werden muss?

Nicht immer.

Ein Schutzelement kann beschädigt werden und viel Rückstand hinterlassen, obwohl der übrige Teil der Platine reparierbar ist.

Wenn jedoch das Laminat verkohlt, ausgebrannt ist oder Leiterbahnen beschädigt sind, kann eine Reparatur unwirtschaftlich oder nicht dauerhaft sein.

### Was kann mehrere Regler gleichzeitig beschädigen?

Wenn mehrere Geräte gleichzeitig ausfallen, ist die Versorgungsinstallation zu prüfen.

Eine mögliche Ursache ist ein Problem mit dem Neutralleiter, das in einer Drehstrominstallation zum Auftreten unzulässiger Spannungen an einphasigen Verbrauchern führen kann.

Auch Überspannungen aus dem Netz oder von einem Aggregat sind möglich.

### Was ist nach einer Störung infolge einer Überspannung zu tun?

Vor dem Anschluss eines reparierten oder neuen Reglers ist die Ursache des Problems zu ermitteln.

:::danger Schließen Sie das Gerät nicht erneut an, ohne die Installation zu prüfen

Wenn die Ursache der Störung eine unzulässige Spannung, ein beschädigter Neutralleiter oder eine Überspannung war, kann der reparierte oder neue Regler erneut beschädigt werden.

:::

### Was ist ein Überspannungsschutzelement auf der Platine?

In elektronischen Geräten werden Elemente zur Begrenzung von Überspannungen eingesetzt, z. B. Varistoren.

Ihre Aufgabe besteht darin, einen Teil der Überspannungsenergie aufzunehmen und nachgeschaltete Schaltungen zu schützen. Nach einem starken Ereignis kann ein solches Element dauerhaft beschädigt sein.

### Kann das Gerät nach dem Entfernen des verbrannten Schutzelements in Betrieb genommen werden?

Dies sollte nicht als normale Reparatur betrachtet werden.

Nach dem Entfernen des Schutzes kann das Gerät den Schutz gegen die nächste Überspannung verlieren. Solche Maßnahmen dürfen ausschließlich als bewusste Serviceprozedur von einer Person mit entsprechender Qualifikation und nach Beseitigung der ursprünglichen Störungsursache durchgeführt werden.

### Der Regler wurde überflutet oder ist stark korrodiert. Lohnt sich eine Reparatur?

Das hängt vom Schadensgrad ab.

Oberflächliche Korrosion und einzelne Schäden können häufig beseitigt werden. Wenn die Korrosion Leiterbahnen, Steckverbinder und viele Bauteile erfasst hat, kann die Reparatur zeitaufwendig, unsicher und wirtschaftlich nicht gerechtfertigt sein.

### Kann das Reinigen des Geräts mit Hochdruck den Regler beschädigen?

Ja.

Elektronik sollte keiner direkten Einwirkung von Wasser oder Reinigungsmittel ausgesetzt werden, wenn Gehäuse und Montageart dafür nicht vorgesehen sind.

Feuchtigkeit, die ins Innere eindringt, kann zu Korrosion und späteren, schwer zu diagnostizierenden Störungen führen.

### Warum können Störungen nach einer Durchfeuchtung nach der Reparatur erneut auftreten?

Korrosion kann auch an Stellen fortschreiten, die bei der ersten Kontrolle nicht sichtbar sind.

Beschädigte Durchkontaktierungen, Leiterbahnen und Verbindungen können beim Test funktionieren und später erneut den Kontakt verlieren.

Deshalb kann der Service bei einer stark korrodierten Platine eher einen Austausch als weitere Reparaturen empfehlen.

### Das Gerät funktioniert manchmal und manchmal nicht. Womit sollte begonnen werden?

Vor der Kontaktaufnahme mit dem Service sollten folgende Informationen gesammelt werden:

- das genaue Modell,
- eine Beschreibung des Symptoms,
- der Zeitpunkt des Auftretens,
- die auf dem Bildschirm angezeigten Werte,
- der Alarm- oder Fehlercode,
- Informationen über die letzten Änderungen in der Anlage,
- ein Foto des Innenraums und der Klemmen, wenn es sicher angefertigt werden kann.

Je genauer die Beschreibung, desto einfacher die Diagnose.


## Service und Reparaturen

### Was sollte an den Service gesendet werden, wenn der Regler defekt ist?

Am besten wird ein vollständiger Satz gesendet, mit dem sich das Problem nachvollziehen lässt.

Der Sendung ist eine kurze Beschreibung beizufügen:

- was nicht funktioniert,
- wann das Problem auftritt,
- ob die Störung dauerhaft oder periodisch ist,
- ob vor der Störung eine Überspannung, eine Durchfeuchtung oder ein anderes Ereignis aufgetreten ist,
- die für die Kontaktaufnahme und die Rücksendung des Geräts erforderlichen Daten.

:::note Daten für die Serviceanfrage

Kontakt- und Versanddaten sind direkt an den Service zu übermitteln. Veröffentlichen Sie diese nicht in offenen Anfragen oder öffentlichen Materialien.

:::

### Muss der gesamte Regler gesendet werden oder nur die Platine?

Das hängt von der Störung ab.

Bei Problemen mit Display, Tasten, Versorgung oder uneindeutigem Verhalten sollte am besten das gesamte Set gesendet werden, das zur Reproduktion des Symptoms erforderlich ist.

Bei einer zuvor abgestimmten Reparatur eines bestimmten Moduls kann der Service nur um die Platine bitten.

### Repariert ELETOR Regler, anstatt sie sofort auszutauschen?

Aus den Transkripten ergibt sich, dass die Geräte zunächst diagnostiziert werden.

Wenn eine Reparatur möglich und sinnvoll ist, werden beschädigte Bauteile oder Module ausgetauscht. Bei schwerer Beschädigung kann der Service den Austausch der Platine oder des gesamten Geräts vorschlagen.

### Was geschieht, wenn die beschädigte Platine nicht repariert werden kann?

Ein Austausch des beschädigten Moduls gegen ein neues ist möglich, sofern das entsprechende Teil verfügbar und mit dem Gerät kompatibel ist.

Bei älteren Geräten sollte der Service zunächst die Versionskompatibilität bestätigen.

### Lohnt es sich, nach einer Überspannung sofort eine neue Platine zu kaufen?

Nicht immer.

Wenn der Schaden ein Schutzelement oder einen kleinen Teil der Schaltung betrifft, kann eine Reparatur sinnvoll sein. Zunächst sollte eine Diagnose durchgeführt werden.

### Kann der Service auch Display und Tasten prüfen?

Ja, wenn die Elemente zusammen mit dem Gerät oder Modul geliefert werden.

Dies ist besonders nützlich, wenn unklar ist, ob sich das Problem auf der Hauptplatine oder im Benutzerpanel befindet.

### Lohnt es sich immer, einen stark korrodierten Regler zu retten?

Nein.

Wenn die Kosten für Diagnose und Reparatur steigen und die Zuverlässigkeit nach der Reparatur unsicher bleibt, kann ein Austausch sinnvoller sein.

Dies gilt insbesondere für Geräte, von denen die Lüftung des Objekts abhängt.

### Wie lässt sich die Servicediagnose beschleunigen?

Fügen Sie statt der bloßen Aussage „funktioniert nicht“ eine genaue Beschreibung des Symptoms bei.

Hilfreich sind auch:

- Fotos,
- der Fehlercode,
- eine Beschreibung der Anlage,
- der Typ der angeschlossenen Verbraucher,
- Informationen über Überspannung oder Versorgungsausfall,
- Informationen über Durchfeuchtung oder Reinigung des Geräts.


## Installation und Verkabelung

### Wie werden Geräte an die Relaisklemmen C und NO angeschlossen?

C und NO sind typische Bezeichnungen eines Relaiskontakts:

- C — gemeinsamer Kontakt,
- NO — normalerweise offener Kontakt.

Die Art der Nutzung hängt vom Gerät und vom Installationsschema ab. Der Kontakt kann z. B. zur Ansteuerung der Spule eines Schützes verwendet werden, seine zulässigen Parameter dürfen jedoch nicht überschritten werden.

:::warning Elektrische Arbeiten

Anschlüsse an Netzspannung sollten von einer Person mit entsprechender Qualifikation gemäß dem Schaltplan des konkreten Geräts ausgeführt werden.

:::

### Kann der Relaisausgang direkt einen großen Ventilator versorgen?

In der Regel ist dies keine geeignete Anwendung für einen kleinen Steuerausgang.

Für größere Lasten werden ein Schütz, ein Leistungsrelais oder ein dediziertes Ausgangsmodul verwendet.

### Wozu dienen die Klemmen A1 und A2 des Schützes?

Dies sind die Klemmen der Schützspule.

Wird die entsprechende Spannung an die Spule angelegt, ändert das Schütz den Zustand seiner Leistungskontakte.

Die Spulenspannung muss mit dem Anlagenentwurf und der Dokumentation des Schützes übereinstimmen.

### Können zusätzliche Geräte im Inneren des Reglergehäuses montiert werden?

Nur wenn die Konstruktion des konkreten Gehäuses dies zulässt und dadurch Folgendes nicht beeinträchtigt wird:

- die Schutzart,
- die Isolierung,
- die Kühlung,
- die Sicherheit,
- der Servicezugang.

Alle neuen Öffnungen sollten so ausgeführt werden, dass die erforderliche Dichtheit erhalten bleibt.

### Sind zusätzliche Ventilatorschalter sinnvoll?

Sie können den Service erleichtern und eine unabhängige Trennung einzelner Ventilatoren ermöglichen.

Die Ausführung muss jedoch elektrische Schutzmaßnahmen berücksichtigen und darf keine gefährlichen Zustände des Reglers verursachen.

### Können Steuerleitungen zusammen mit Leistungsleitungen verlegt werden?

Es sollte vermieden werden, empfindliche Signalleitungen parallel und in sehr geringem Abstand zu leistungsstarken Leitungen zu verlegen, insbesondere auf langen Strecken.

Die Anforderungen hängen von der Art des Signals und der elektromagnetischen Umgebung ab.

### Welches Kabel ist für Netzwerkverbindungen und PoE-Geräte zu verwenden?

In den besprochenen Installationen wurde mindestens ein verdrilltes Kabel der Kategorie 5e angegeben.

Wenn das Kabel in einer Umgebung mit erhöhtem Störpegel oder dem Risiko elektrostatischer Aufladungen verläuft, kann der Einsatz eines entsprechend geschirmten Kabels und eines korrekten Erdungssystems sinnvoll sein.

### Wird für PoE ein Crossover-Kabel benötigt?

In typischen Installationen wird eine standardmäßige gerade Verbindung verwendet.

Es sind jedoch immer die Anforderungen des Netzwerkgeräts und des verwendeten PoE-Netzteils zu prüfen.


## Betrieb und Wartung

### Wie lässt sich das Ausfallrisiko von Reglern in landwirtschaftlichen Gebäuden begrenzen?

Am wichtigsten ist die Begrenzung des Einflusses von:

- Feuchtigkeit,
- Ammoniak und aggressiver Umgebung,
- Staub,
- direkter Reinigung mit Wasser,
- Überspannungen,
- fehlerhafter Versorgung.

Außerdem sollten Zustand von Leitungen, Verbindungen und Gehäusen regelmäßig kontrolliert werden.

### Sollten elektronische Geräte regelmäßig gereinigt werden?

Ja, insbesondere Geräte mit Kühlkörpern, Ventilatoren und Lüftungsöffnungen.

Angesammelter Staub verschlechtert die Kühlung.

Die Reinigung ist nach dem Trennen der Versorgung und gemäß der Geräteanleitung durchzuführen.

### Lohnt sich nach einigen Betriebsjahren eine Inspektion des Reglers?

Ja, insbesondere unter schwierigen Umgebungsbedingungen.

Die Inspektion kann Folgendes umfassen:

- Beurteilung des Zustands der Steckverbinder,
- Kontrolle auf Spuren von Feuchtigkeit und Korrosion,
- Prüfung der Kühlelemente,
- Prüfung des Panels und der Tasten,
- Test der Sensoren,
- Kontrolle der Akkus in Alarmsystemen.

### Was sollte nach dem Auftreten einer Störung notiert werden?

Am nützlichsten sind:

- die vollständige Meldung,
- der Fehlercode,
- die Uhrzeit des Ereignisses,
- die Temperatur,
- der Lüftungszustand,
- Informationen über einen Versorgungsausfall,
- Informationen über den Betrieb des Aggregats,
- ein Foto des Bildschirms oder des Geräts.

Das Gerät sollte vor dem Notieren des Codes nicht zurückgesetzt werden, sofern die Situation dies sicher zulässt.

### Ist ein vom Lüftungsregler unabhängiger Alarm sinnvoll?

Ja, insbesondere dort, wo ein Lüftungsausfall schnell zu gefährlichen Bedingungen führen kann.

Eine unabhängige Zentrale mit eigenem Akku und Fernbenachrichtigung bietet eine zusätzliche Schutzebene.

### Welche Informationen sollten vor der Kontaktaufnahme mit dem technischen Support vorbereitet werden?

Am besten werden folgende Informationen vorbereitet:

1. das genaue Gerätemodell,
2. eine Beschreibung der Anlage,
3. die Anzahl und Parameter der angeschlossenen Geräte,
4. die aktuellen mit dem Problem verbundenen Einstellungen,
5. das genaue Symptom,
6. der vollständige Fehler- oder Alarmcode,
7. Fotos des Geräts und der Typenschilder,
8. Informationen über die letzten Änderungen in der Anlage.

Dadurch kann die Diagnose erheblich verkürzt werden.


## Wichtiger Hinweis zu älteren Geräten

Namen, Klemmenbezeichnungen und verfügbare Funktionen können sich zwischen Geräteversionen unterscheiden, die in verschiedenen Jahren hergestellt wurden.

Wenn das Gerät mehrere oder ein Dutzend Jahre alt ist, sind vor der Anwendung einer Anleitung eines neueren Modells folgende Punkte zu bestätigen:

- die genaue Gerätebezeichnung,
- die Platinenversion,
- die Art des Displays,
- die Softwareversion,
- das Klemmenbelegungsschema.

:::warning Ältere Geräteversionen

Gehen Sie nicht allein aufgrund eines ähnlichen Aussehens des Gehäuses von vollständiger Kompatibilität aus. Bestätigen Sie vor der Verwendung eines Schemas oder einer Anleitung das genaue Modell und die Version des Geräts.

:::


## Kontakt mit dem technischen Support

Wenn das FAQ das Problem nicht löst, bereiten Sie vor der Kontaktaufnahme Folgendes vor:

- ein Foto des Reglers,
- ein Foto des Typenschilds des Verbrauchers,
- die Parameter der Motoren oder Stellantriebe,
- das Anschlussdiagramm,
- eine genaue Beschreibung der gewünschten Funktionsweise.

Dadurch kann die Geräteauswahl oder die Problemdiagnose anhand der tatsächlichen Parameter der Anlage und nicht auf Grundlage von Vermutungen durchgeführt werden.
