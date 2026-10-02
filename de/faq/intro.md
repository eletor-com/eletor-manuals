---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Häufige Fragen zur Auswahl, Konfiguration, Diagnose und zum Service von
  Geräten von ELETOR.
keywords:
- ELETOR
- FAQ
- Lüftungssteuergeräte
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

Die FAQ wurden auf Grundlage einer anonymisierten Analyse tatsächlicher Gespräche mit Nutzern und Kunden von ELETOR erstellt. Die Antworten wurden verallgemeinert, damit sie in typischen Fällen helfen und keine Daten bestimmter Personen oder Anlagen enthalten.

:::note Geltungsbereich der FAQ

Die Antworten beziehen sich auf typische Fälle. Klemmenbezeichnungen, Funktionen und Anschlussweise können sich je nach Modell und Geräteversion unterscheiden. Verwenden Sie im Zweifelsfall die Dokumentation des jeweiligen Produkts.

:::

:::warning Sicherheit

Führen Sie Arbeiten an der elektrischen Anlage gemäß der Gerätedokumentation und den geltenden Sicherheitsvorschriften durch. Arbeiten an Netzspannung sollten von einer entsprechend qualifizierten Person durchgeführt werden.

:::

## Auswahl des Steuergeräts und der Leistung

### Wie wird das Steuergerät für die Ventilatoren ausgewählt?

Grundlage der Auswahl ist vor allem der Gesamtstrom der Ventilatoren und nicht ausschließlich deren Anzahl.

:::tip Bereiten Sie die Daten vor der Auswahl vor

Je genauer die Angaben zu den Motoren und zur Betriebsweise der Anlage sind, desto zuverlässiger ist die Auswahl des Steuergeräts.

:::

Vor der Auswahl sollten folgende Angaben vorbereitet werden:

- Anzahl der Ventilatoren,
- Versorgungsspannung,
- Nennleistung oder Nennstrom jedes Ventilators,
- Angabe, ob alle Ventilatoren stufenlos geregelt werden sollen,
- Angabe, ob die Ventilatoren in Gruppen aufgeteilt werden können,
- Angaben zu zusätzlichen Geräten, z. B. Heizgeräten oder Lufteinlässen.

Das Steuergerät darf nicht genau an der Belastungsgrenze ausgelegt werden. Gegenüber der maximalen Belastung ist eine ausreichende Reserve vorzusehen.

### Reicht es aus, die Leistung der Ventilatoren in Watt zu addieren?

Für eine erste Abschätzung kann die Leistung herangezogen werden. Die endgültige Auswahl sollte jedoch auf dem Nennstrom der Geräte und der Art der Last beruhen.

Ein Motor kann beim Anlaufen mehr Strom aufnehmen als im Normalbetrieb. Aus diesem Grund stellen zwei Ventilatorgruppen mit ähnlicher Nennleistung nicht immer eine gleichwertige Last für das Steuergerät dar.

### Ich habe mehrere kleine Ventilatoren. Kann ich sie parallel an einen Ausgang anschließen?

Ja, sofern:

- sie für diese Art der Ansteuerung vorgesehen sind,
- sie gemeinsam betrieben werden sollen,
- die Summe der Lasten den zulässigen Ausgangsstrom nicht überschreitet,
- die Anschlussweise der Dokumentation des Steuergeräts entspricht.

Bei einer größeren Anzahl von Ventilatoren sollte eine Aufteilung in Gruppen oder der Einsatz einer Leistungserweiterung erwogen werden.

### Wann ist eine Leistungserweiterung erforderlich?

Eine Leistungserweiterung wird eingesetzt, wenn die Last die Kapazität des Steuergeräteausgangs überschreitet oder wenn die Anlage um weitere Ventilatoren erweitert werden soll.

Das Steuergerät liefert dann das Steuersignal, während die eigentliche Last von einem zusätzlichen Modul versorgt wird.

### Kann die Anlage später um zusätzliche Ventilatoren erweitert werden?

Bei vielen Anlagen ist dies möglich. Am häufigsten werden eingesetzt:

- eine zusätzliche Leistungserweiterung,
- eine zusätzliche Lüftungsgruppe,
- ein Schütz zum Zuschalten einer weiteren Gruppe,
- ein Frequenzumrichter bei Drehstrommotoren.

Die geplante Erweiterung sollte möglichst bereits bei der ersten Auswahl des Steuergeräts berücksichtigt werden.

### Müssen alle Ventilatoren stufenlos geregelt werden?

Nein. Zwei Lösungen sind üblich:

1. alle Ventilatoren werden stufenlos geregelt,
2. die erste Gruppe wird stufenlos geregelt, weitere Gruppen werden schrittweise zugeschaltet, z. B. über Schütze.

Die zweite Lösung ermöglicht die Steuerung einer größeren Anlage, ohne jeden Ventilator stufenlos regeln zu müssen.

### Ich habe 10 Ventilatoren. Benötige ich ein sehr großes Steuergerät?

Nicht immer. Es können mehrere Steuerungsverfahren eingesetzt werden:

- Aufteilung in Gruppen,
- Leistungserweiterungen,
- Schütze,
- Frequenzumrichter.

Die endgültige Auswahl hängt von den elektrischen Kenndaten der Ventilatoren und davon ab, ob alle ihre Drehzahl gleichzeitig ändern sollen.

### Unterscheiden sich die Steuergeräte 6 A und 12 A nur hinsichtlich der zulässigen Belastung?

Es darf nicht angenommen werden, dass der Stromwert der einzige Unterschied ist. Einzelne Geräteversionen und -generationen können sich hinsichtlich Ausstattung oder Ausführung unterscheiden.

Beim Austausch eines Geräts müssen das genaue Modell und die aktuelle Dokumentation geprüft werden.


## Ventilatoren und Lüftungssteuerung

### Regelt das Steuergerät die Ventilatoren stufenlos?

Bei Steuergeräten für die stufenlose Lüftungsregelung wird die Drehzahl der Ventilatoren abhängig vom Bedarf verändert, der sich unter anderem aus der Temperatur ergibt.

Es muss jedoch geprüft werden, ob der jeweilige Motortyp für das eingesetzte Regelverfahren geeignet ist.

### Was bedeutet Solltemperatur?

Die Solltemperatur ist der Wert, mit dem das Steuergerät den aktuellen Temperaturmesswert vergleicht.

Auf dieser Grundlage erhöht oder verringert das Steuergerät die Lüftungsintensität entsprechend den übrigen Einstellungen, z. B. dem Regelband sowie dem Minimal- und Maximalniveau.

### Was bedeutet minimales Lüftungsniveau?

Dies ist der minimale Ansteuerwert des Ventilators im Automatikbetrieb.

Die Einstellung verhindert den Betrieb unterhalb eines Niveaus, bei dem der Ventilator instabil laufen oder einen zu geringen Luftaustausch gewährleisten könnte.

### Was bedeutet maximales Lüftungsniveau?

Dies ist die obere Begrenzung des Ansteuerwerts der Lüftung.

Beispielsweise kann eine Einstellung unter 100% die maximale Ventilatordrehzahl begrenzen, wenn die Anlage dies erfordert.

### Was bedeutet Lüftungsband?

Das Lüftungsband legt den Temperaturbereich fest, in dem das Steuergerät vom minimalen zum maximalen Lüftungsniveau übergeht.

Je kleiner das Band, desto schneller reagiert die Steuerung mit einer Leistungssteigerung auf eine Temperaturänderung.

### Nach dem Start läuft der Ventilator zunächst mit 100% und wird erst danach langsamer. Warum?

Möglicherweise ist eine Anlauffunktion aktiviert, die den Motor kurzzeitig mit höherer Leistung starten soll.

Je nach Steuergeräteversion müssen die Einstellungen für folgende Funktionen geprüft werden:

- Soft-Start-Funktion,
- Hochlaufzeit,
- Betriebsdauer bei 100%,
- Auslaufzeit.

Wenn die Funktion in der jeweiligen Anlage nicht benötigt wird, können die entsprechenden Parameter gemäß der Geräteanleitung geändert werden.

### Warum kann der Ventilator beim Start kurzzeitig mit voller Leistung betrieben werden?

Ein solcher Anlauf kann einen zuverlässigen Start des Ventilators unterstützen, auch in Anlagen, in denen mechanische Komponenten beim Start einen höheren Widerstand aufweisen können.

Dies ist jedoch nicht in jeder Anlage erforderlich.

### Was bedeuten Hochlaufzeit und Auslaufzeit?

**Hochlaufzeit** legt fest, wie die Ansteuerung beim Starten des Ventilators erhöht wird.

**Auslaufzeit** legt fest, wie die Drehzahl verringert wird.

Beide Parameter ermöglichen es, abrupte Änderungen der Drehzahl und des Anlagenbetriebs zu begrenzen.

### Warum können zwei identische Steuergeräte die Ventilatoren unterschiedlich starten?

Die häufigste Ursache sind unterschiedliche Einstellungen.

Vor allem sollten folgende Einstellungen verglichen werden:

- Solltemperatur,
- Lüftungsband,
- Minimum und Maximum,
- Soft-Start-Einstellungen,
- Hochlauf- und Auslaufzeiten,
- Konfiguration der Lüftungsgruppen.

### Kann das Steuergerät die Lüftung unabhängig von der Temperatur in regelmäßigen Abständen starten?

Je nach Modell steht eine Funktion zur periodischen Durchlüftung zur Verfügung.

Sie kann die Lüftung in festgelegten Abständen für eine bestimmte Dauer starten, auch wenn die Temperaturregelung keine Erhöhung der Lüftung erfordert.

### Wozu dienen Lüftungsgruppen?

Die Gruppen ermöglichen eine schrittweise Erhöhung der Anlagenleistung.

Beispielsweise:

- Gruppe 1 wird stufenlos geregelt,
- Gruppe 2 schaltet weitere Ventilatoren ein,
- die nächste Gruppe startet bei einem noch höheren Bedarf.

Dadurch lässt sich eine große Anzahl von Ventilatoren steuern, ohne jeden einzelnen stufenlos regeln zu müssen.

### Kann eine zusätzliche Ventilatorgruppe über ein Schütz zugeschaltet werden?

Ja. Der Relaisausgang des Steuergeräts kann die Spule eines entsprechend ausgewählten Schützes ansteuern.

Der Laststrom der Ventilatoren sollte dann nicht direkt über den kleinen Steuerkontakt geführt werden.

### Was bedeutet das Ventilatorsymbol oder die gelbe Kontrollleuchte am Steuergerät?

Je nach Modell informieren die Kontrollleuchten über den aktuellen Zustand der Ausgänge und Funktionen.

Die gelbe Anzeige kann eine aktive Betriebsfunktion anzeigen, z. B. den Betrieb der Lüftung, der Heizung oder einer weiteren Gruppe.

Die genaue Bedeutung ist in der Anleitung des jeweiligen Modells nachzulesen.

### Was bedeutet das Symbol für den Handbetrieb?

Handbetrieb bedeutet, dass der Ansteuerwert vom Nutzer vorgegeben wurde und momentan nicht automatisch anhand der Temperatur berechnet wird.

Nach Abschluss der Tests muss sichergestellt werden, dass das Steuergerät wieder in den korrekten Automatikbetrieb versetzt wurde.


## Lufteinlässe und Stellantriebe

### Kann das Steuergerät Lufteinlässe steuern?

Ja, ausgewählte Steuergeräte ermöglichen die Zusammenarbeit mit Antrieben für Lufteinlässe.

Die Anschlussweise hängt vom Typ des Stellantriebs und dessen Ansteuerung ab.

### Welche Arten von Stellantrieben können für Lufteinlässe verwendet werden?

In den technischen Gesprächen kamen am häufigsten zwei Lösungen vor:

- ein Stellantrieb mit analogem Steuersignal 0–10 V oder 2–10 V,
- ein reversierbarer Stellantrieb mit Auf/Zu-Ansteuerung und Rückmeldesignal, z. B. von einem Potenziometer.

Vor dem Kauf muss die Kompatibilität des jeweiligen Modells mit dem vorhandenen Steuergerät geprüft werden.

### Ist die Versorgungsspannung des Stellantriebs 24 V oder 230 V für das Signal 0–10 V von Bedeutung?

Das Steuersignal und die Spannungsversorgung des Stellantriebs sind getrennte Parameter.

Der Stellantrieb kann mit einer anderen Spannung versorgt werden als der Spannung des Steuersignals. Beide Parameter müssen der Dokumentation des Stellantriebs und des Steuergeräts entsprechen.

### Was bedeutet die Ansteuerung 0–10 V?

Das Steuergerät sendet ein analoges Spannungssignal, das die gewünschte Position oder den Ansteuerwert darstellt.

In einer typischen Anwendung bedeutet ein niedrigerer Wert eine kleinere Öffnung und ein höherer Wert eine größere Öffnung. Die tatsächliche Kennlinie muss jedoch in der Dokumentation des Stellantriebs geprüft werden.

### Worin unterscheidet sich 0–10 V von 2–10 V?

In beiden Fällen wird die Position durch ein analoges Signal vorgegeben.

Beim Standard 2–10 V ist der untere Bereich verschoben, wodurch das Gerät ein Steuersignal von dessen Fehlen unterscheiden kann.

Steuergerät und Stellantrieb müssen denselben Signalbereich unterstützen.

### Wie wird ein Stellantrieb für die Anzahl der Lufteinlässe ausgewählt?

Ein Stellantrieb darf nicht ausschließlich anhand der Anzahl der Klappen ausgewählt werden.

Zu berücksichtigen sind:

- erforderliche Kraft oder erforderliches Drehmoment,
- Länge und Führung des Mechanismus,
- Widerstände der Klappen,
- Hublänge,
- Stellgeschwindigkeit,
- Versorgungsspannung,
- Art der Ansteuerung,
- erforderliche Rückmeldung.

### Kann ein Stellantrieb mehrere Klappen betätigen?

Ja, wenn die Mechanik der Anlage eine Verbindung der Klappen über einen gemeinsamen Mechanismus ermöglicht und das erforderliche Drehmoment oder die erforderliche Kraft die Leistungsfähigkeit des Stellantriebs nicht überschreitet.

In der Praxis sind die Widerstände des gesamten Mechanismus für die Auswahl maßgebend, nicht allein die Anzahl der Klappen.

### Können mehrere Stellantriebe parallel geschaltet und mit einem Signal angesteuert werden?

In einigen Systemen ist dies möglich. Die Dokumentation der Stellantriebe und die zulässige Belastung des Steuerausgangs müssen jedoch geprüft werden.

Bei reversierbaren Antrieben ohne unabhängige Rückmeldung können die Positionen der einzelnen Stellantriebe außerdem mit der Zeit auseinanderdriften.

### Warum können sich mehrere Stellantriebe mit der Zeit auf unterschiedliche Positionen einstellen?

Auch identische Motoren können mit geringfügig unterschiedlicher Geschwindigkeit laufen, bedingt durch:

- unterschiedliche Belastung,
- mechanische Widerstände,
- Toleranzen der Motorparameter,
- Unterschiede der Getriebe.

Wenn eine genaue Synchronisierung erforderlich ist, wird daher eine geeignete Rückmeldung oder eine individuelle Positionskontrolle benötigt.

### Können die Lufteinlässe proportional zur Lüftung angesteuert werden?

Ja. In entsprechend konfigurierten Systemen kann die Position der Lufteinlässe mit dem aktuellen Lüftungsniveau verknüpft werden.

Dadurch wird mit zunehmender Ventilatorleistung auch die Öffnung der Lufteinlässe vergrößert.

### Benötigt der Stellantrieb 24 V ein separates Netzteil?

Wenn das Steuergerät keinen geeigneten Versorgungsausgang mit der erforderlichen Leistung besitzt, ist ein separates Netzteil erforderlich.

Dessen Leistung muss auf die Stromaufnahme des Stellantriebs und weiterer Geräte abgestimmt werden, die aus derselben Quelle versorgt werden.

### Kann ein Stellantrieb eines anderen Herstellers eingesetzt werden?

Häufig ja, wenn seine elektrischen Kenndaten und seine Ansteuerung mit den Ausgängen des Steuergeräts kompatibel sind.

Vor dem Anschluss sind folgende Angaben zu prüfen:

- Spannung,
- Signaltyp,
- Verdrahtungsplan,
- Betätigungsrichtungen,
- Positionssignal,
- zulässige Belastung.


## Temperatur- und Feuchtesensoren

### Wo wird der Temperatursensor angeschlossen?

Der Sensor muss an den vom Hersteller vorgesehenen Sensoreingang angeschlossen werden, den in der Dokumentation des jeweiligen Modells angegebenen Sensoreingang.

Es darf nicht angenommen werden, dass die Klemmenbezeichnungen bei allen Geräteversionen identisch sind.

### Der Temperatursensor zeigt einen anderen Wert als das Referenzthermometer an. Was ist zu tun?

Wenn das Steuergerät über eine Sensorkalibrierungsfunktion verfügt, kann die Anzeige nach einem Vergleich mit einem zuverlässigen Referenzthermometer korrigiert werden.

Vor einer Änderung der Kalibrierung sollte sichergestellt werden, dass:

- sich beide Sensoren am selben Ort befinden,
- sich der Messwert stabilisiert hat,
- der Sensor nicht durch die Sonne oder Geräte erwärmt wird,
- er sich nicht direkt in einem kalten oder heißen Luftstrom befindet.

### Der Feuchtesensor zeigt einen falschen Wert an. Kann er kalibriert werden?

Dies hängt von der Version des Steuergeräts, des Sensors und der Software ab.

Bei einigen Lösungen kann die Korrektur eine entsprechende Softwarefunktion oder einen kompatiblen Sensortyp erfordern. Wenn die Abweichung groß und reproduzierbar ist, muss die Geräteversion geprüft und der technische Support kontaktiert werden.

### Bedeutet ein falscher Messwert immer, dass der Sensor defekt ist?

Nein.

Die Ursache kann auch sein:

- falsche Platzierung des Sensors,
- Leitung,
- elektrische Verbindung,
- Konfiguration,
- falscher Sensortyp,
- erforderliche Kalibrierung,
- Feuchtigkeit oder Korrosion.


## Alarme und Benachrichtigungen

### Kann eine Sirene direkt an den Alarmausgang des Steuergeräts angeschlossen werden?

Dies darf nicht vorausgesetzt werden.

Der Alarmausgang des Steuergeräts ist in der Regel ein Steuerausgang oder ein Relaiskontakt. Die Sirene kann eine separate Spannungsversorgung und eine Alarmzentrale benötigen.

### Wozu wird eine Alarmzentrale eingesetzt?

Die Zentrale kann:

- Alarmsignale von Steuergeräten empfangen,
- einen Signalgeber mit Spannung versorgen,
- den Betrieb bei einem Stromausfall aufrechterhalten,
- einen Alarm akustisch oder optisch signalisieren,
- bei Versionen mit entsprechender Funktion GSM-Benachrichtigungen versenden.

### Kann die Zentrale einen Ausfall der Spannungsversorgung des Steuergeräts melden?

Ja, wenn das System entsprechend angeschlossen wurde.

Die Lösung kann nicht nur eine Temperaturüberschreitung erkennen, sondern auch den Verlust des Signals vom Steuergerät infolge eines Ausfalls seiner Spannungsversorgung.

### Wo werden die minimale und maximale Alarmtemperatur eingestellt?

In einer typischen Konfiguration werden die Alarmschwellen im Steuergerät eingestellt, das die jeweilige Kammer oder den jeweiligen Raum steuert.

Die Alarmzentrale empfängt anschließend die Information, dass das Steuergerät einen Alarm gemeldet hat.

### Benötigt die GSM-Zentrale eine SIM-Karte?

Für Anrufe und Nachrichten über das Mobilfunknetz ist eine aktive SIM-Karte oder eine andere, für das jeweilige Modell vorgesehene Kommunikationslösung erforderlich.

Ohne aktive Verbindung zum Mobilfunknetz funktionieren die Telefon- und SMS-Funktionen nicht.

### Kann das Alarmsystem mitteilen, von welchem Steuergerät das Ereignis stammt?

In einem entsprechend konfigurierten System ist dies möglich.

Die Eingänge der Zentrale können bestimmten Räumen oder Steuergeräten zugeordnet werden, sodass anhand der Meldung die Alarmquelle festgestellt werden kann.

### Wie viele Steuergeräte können an eine Alarmzentrale angeschlossen werden?

Dies hängt vom Modell der Zentrale ab.

In den Transkriptionen wurden Zentralen mit bis zu acht Eingängen erwähnt. Vor der Installation muss jedoch die aktuelle Spezifikation des jeweiligen Geräts geprüft werden.

### Welcher Akku wird in der Alarmzentrale verwendet?

In einigen der in den Gesprächen behandelten Geräte wurde ein Akku mit 12 V 7 Ah verwendet.

Vor dem Kauf eines Ersatzakkus müssen die Kennzeichnung des vorhandenen Akkus und die Spezifikation der Zentrale geprüft werden, da andere Geräteversionen einen anderen Akku erfordern können.

### Die Zentrale sendet Meldungen über niedrige Spannung. Was ist zu prüfen?

Zunächst sollten folgende Punkte geprüft werden:

- Zustand des Akkus,
- Alter des Akkus,
- Akkuanschlüsse,
- Vorhandensein der Netzversorgung,
- Funktion des Ladegeräts oder des Netzteils der Zentrale.

Ein verschlissener Akku kann wiederkehrende Meldungen über niedrige Spannung verursachen.

### Wie oft muss der Akku in der Alarmzentrale ausgetauscht werden?

Es gibt kein einheitliches Intervall, das für alle Bedingungen geeignet ist.

Der Akku muss regelmäßig getestet werden, insbesondere in Anlagen, in denen ein Alarm bei Stromausfall von entscheidender Bedeutung ist. Mit zunehmendem Alter nimmt seine tatsächliche Kapazität ab.

### Reicht eine Sirene allein als Schutz aus?

Eine Sirene ist nur wirksam, wenn jemand sie hören kann.

In zeitweise unbeaufsichtigten Objekten sollten zusätzlich eine Fernbenachrichtigung und eine Akku-Pufferung eingesetzt werden.


## Frequenzumrichter

### Wie wird ein Frequenzumrichter für Ventilatoren ausgewählt?

Folgende Angaben müssen bekannt sein:

- Versorgungsspannung,
- Anzahl der Phasen,
- Leistung und Strom aller Motoren,
- Art ihrer Verschaltung,
- Betriebsbedingungen,
- erforderliche Art der Ansteuerung.

Der Frequenzumrichter sollte gegenüber der Last eine ausreichende Reserve aufweisen, insbesondere wenn mehrere Motoren parallel betrieben werden.

### Sollte der Frequenzumrichter genau dieselbe Leistung wie die Summe der Motorleistungen haben?

Der Frequenzumrichter sollte nicht ausschließlich anhand einer einfachen Addition der Leistungen ausgewählt werden. Ebenso sollte kein Gerät gewählt werden, das genau an der Grenze seiner Kenndaten arbeitet.

Nennströme, Art der Last und Empfehlungen des Frequenzumrichterherstellers müssen berücksichtigt werden.

### Der Frequenzumrichter hat die Ventilatoren angehalten und einen Fehler angezeigt. Was ist zu tun?

Am wichtigsten ist es, den vollständigen Fehlercode vor dem Zurücksetzen zu notieren.

:::tip Fotografieren Sie die Anzeige

Wenn die Situation es erlaubt, fotografieren Sie die Anzeige vor dem Zurücksetzen. Der vollständige Fehlercode erleichtert die Diagnose erheblich.

:::

Der Anfang der Meldung allein reicht häufig nicht aus, um die Ursache festzustellen. Der vollständige Code ermöglicht unter anderem die Unterscheidung zwischen:

- Überlastung,
- Überstrom,
- Überhitzung,
- unzulässiger Spannung,
- anderen Antriebsfehlern.

### Kann der Fehler des Frequenzumrichters einfach zurückgesetzt werden?

Das Zurücksetzen kann den Betrieb wiederherstellen, beseitigt aber nicht die Ursache des Alarms.

Nach dem Ereignis muss der Fehlercode geprüft und die Ursache festgestellt werden, bevor die Anlage erneut dauerhaft betrieben wird.

### Der Frequenzumrichter arbeitet in einem staubigen Raum. Muss er gereinigt werden?

Ja.

Staub und Ablagerungen auf dem Kühlkörper oder dem Kühlventilator können die Wärmeabfuhr beeinträchtigen und zu einer Überhitzung des Frequenzumrichters führen.

Die Reinigung muss gemäß der Herstelleranleitung nach sicherer Trennung von der Spannungsversorgung erfolgen.

### Was kann eine Überhitzung des Frequenzumrichters verursachen?

Die häufigsten Ursachen sind:

- verschmutzte Kühlkomponenten,
- behinderter Luftstrom,
- zu hohe Umgebungstemperatur,
- Überlastung,
- defekter Kühlventilator,
- unsachgemäße Montage.

### Kann eine erhöhte Netzspannung einen Alarm des Frequenzumrichters auslösen?

Ja. Frequenzumrichter überwachen die Spannung des Versorgungskreises und können bei Überschreitung des zulässigen Werts einen Fehler melden.

Wenn das Problem wiederholt auftritt, müssen die Anlage und die Qualität der Spannungsversorgung überprüft werden.


## Störungen und Diagnose

### Das Steuergerät funktioniert, aber die Anzeige zeigt nichts an. Was kann die Ursache sein?

Mögliche Ursachen sind unter anderem:

- eine defekte Anzeige,
- ein Problem mit der Kontrasteinstellung bei älteren Ausführungen,
- eine beschädigte Verbindung,
- Korrosion,
- eine defekte Hauptplatine.

Wenn das Gerät längere Zeit nicht verwendet wurde oder in einer feuchten Umgebung betrieben wurde, sollte auch der Zustand der Platine geprüft werden.

### Nach mehreren Jahren ohne Nutzung hat das Steuergerät ein Problem mit der Anzeige. Warum?

Ein längerer Stillstand in einer feuchten oder aggressiven Umgebung kann zu Folgendem führen:

- Oxidation der Steckverbindungen,
- Korrosion,
- Verschlechterung der Kontakte,
- Schäden an elektronischen Bauteilen.

In diesem Fall sollte eine vollständige Überprüfung durchgeführt werden, statt Bauteile ohne vorherige Diagnose auszutauschen.

### Das Steuergerät ist nach einer Überspannung verrußt. Bedeutet dies, dass die Platine ausgetauscht werden muss?

Nicht immer.

Ein Schutzbauteil kann beschädigt werden und viele Ablagerungen hinterlassen, obwohl der übrige Teil der Platine repariert werden kann.

Wenn das Leiterplattenmaterial jedoch verkohlt oder ausgebrannt ist oder Leiterbahnen beschädigt sind, kann eine Reparatur unwirtschaftlich oder nicht dauerhaft sein.

### Was kann mehrere Steuergeräte gleichzeitig beschädigen?

Wenn mehrere Geräte gleichzeitig ausfallen, muss die Versorgungsanlage überprüft werden.

Eine mögliche Ursache ist ein Problem mit dem Neutralleiter, das in einer Drehstromanlage zu unzulässigen Spannungen an einphasigen Verbrauchern führen kann.

Auch Überspannungen aus dem Netz oder vom Stromaggregat sind möglich.

### Was ist nach einem durch Überspannung verursachten Ausfall zu tun?

Vor dem Anschluss eines reparierten oder neuen Steuergeräts muss die Ursache des Problems festgestellt werden.

:::danger Schließen Sie das Gerät nicht erneut an, ohne die Anlage zu überprüfen

Wenn die Ursache des Ausfalls eine unzulässige Spannung, ein beschädigter Neutralleiter oder eine Überspannung war, kann das reparierte oder neue Steuergerät erneut beschädigt werden.

:::

### Was ist ein Überspannungsschutzbauteil auf der Platine?

In elektronischen Geräten werden Bauteile zur Begrenzung von Überspannungen eingesetzt, z. B. Varistoren.

Ihre Aufgabe ist es, einen Teil der Überspannungsenergie aufzunehmen und nachgeschaltete Schaltungen zu schützen. Nach einem starken Ereignis kann ein solches Bauteil dauerhaft beschädigt sein.

### Kann das Gerät nach dem Entfernen eines durchgebrannten Schutzbauteils in Betrieb genommen werden?

Dies darf nicht als normale Reparatur betrachtet werden.

Nach dem Entfernen des Schutzbauteils kann das Gerät seinen Schutz vor einer weiteren Überspannung verlieren. Solche Maßnahmen dürfen ausschließlich als bewusst durchgeführtes Serviceverfahren von einer entsprechend qualifizierten Person und nach Beseitigung der Ursache des ursprünglichen Ausfalls vorgenommen werden.

### Das Steuergerät wurde mit Flüssigkeit überflutet oder ist stark korrodiert. Lohnt sich eine Reparatur?

Dies hängt vom Ausmaß der Schäden ab.

Oberflächliche Korrosion und einzelne Schäden können häufig beseitigt werden. Wenn die Korrosion Leiterbahnen, Steckverbindungen und viele Bauteile erfasst hat, kann die Reparatur zeitaufwendig, unsicher und wirtschaftlich nicht gerechtfertigt sein.

### Kann eine Hochdruckreinigung des Geräts das Steuergerät beschädigen?

Ja.

Die Elektronik darf weder Wasser noch Reinigungsmitteln direkt ausgesetzt werden, wenn Gehäuse und Montageweise nicht dafür vorgesehen sind.

Eindringende Feuchtigkeit kann zu Korrosion und späteren, schwer zu diagnostizierenden Fehlern führen.

### Warum können Störungen nach einem Flüssigkeitsschaden trotz Reparatur erneut auftreten?

Korrosion kann auch an Stellen fortschreiten, die bei der ersten Prüfung nicht sichtbar sind.

Beschädigte Durchkontaktierungen, Leiterbahnen und Verbindungen können während des Tests funktionieren und später erneut den Kontakt verlieren.

Deshalb kann der Service bei einer stark korrodierten Platine einen Austausch anstelle weiterer Reparaturen empfehlen.

### Das Gerät funktioniert nur zeitweise. Womit sollte begonnen werden?

Vor der Kontaktaufnahme mit dem Service sollten folgende Angaben zusammengestellt werden:

- genaues Modell,
- Beschreibung des Fehlerbilds,
- Zeitpunkt des Auftretens,
- auf der Anzeige dargestellte Werte,
- Alarm- oder Fehlercode,
- Angaben zu den letzten Änderungen an der Anlage,
- ein Foto des Innenraums und der Klemmen, sofern es sicher aufgenommen werden kann.

Je genauer die Beschreibung, desto einfacher die Diagnose.


## Service und Reparaturen

### Was sollte an den Service gesendet werden, wenn das Steuergerät defekt ist?

Am besten wird eine vollständige Zusammenstellung gesendet, mit der sich das Problem reproduzieren lässt.

Der Sendung muss eine kurze Beschreibung mit folgenden Angaben beigefügt werden:

- was nicht funktioniert,
- wann das Problem auftritt,
- ob der Fehler dauerhaft oder zeitweise auftritt,
- ob vor dem Ausfall eine Überspannung, ein Flüssigkeitsschaden oder ein anderes Ereignis aufgetreten ist,
- die für die Kontaktaufnahme und Rücksendung des Geräts erforderlichen Daten.

:::note Daten für die Serviceanfrage

Übermitteln Sie Kontakt- und Versanddaten direkt an den Service. Veröffentlichen Sie diese nicht in öffentlich zugänglichen Anfragen oder Materialien.

:::

### Muss das gesamte Steuergerät oder nur die Platine eingesendet werden?

Dies hängt vom Fehler ab.

Bei Problemen mit der Anzeige, den Tasten, der Spannungsversorgung oder einem nicht eindeutigen Verhalten sollte die gesamte Zusammenstellung eingesendet werden, die zur Reproduktion des Fehlerbilds erforderlich ist.

Bei einer zuvor vereinbarten Reparatur eines bestimmten Moduls kann der Service lediglich um die Platine bitten.

### Repariert ELETOR Steuergeräte, statt sie sofort auszutauschen?

Aus den Transkriptionen geht hervor, dass die Geräte zunächst diagnostiziert werden.

Wenn eine Reparatur möglich und sinnvoll ist, werden beschädigte Bauteile oder Module ausgetauscht. Bei schweren Schäden kann der Service den Austausch der Platine oder des gesamten Geräts vorschlagen.

### Was geschieht, wenn die beschädigte Platine nicht repariert werden kann?

Das beschädigte Modul kann durch ein neues ersetzt werden, sofern das entsprechende Ersatzteil verfügbar und mit dem Gerät kompatibel ist.

Bei älteren Geräten sollte der Service zunächst die Kompatibilität der Versionen bestätigen.

### Sollte nach einer Überspannung sofort eine neue Platine gekauft werden?

Nicht immer.

Wenn der Schaden ein Schutzbauteil oder einen kleinen Teil der Schaltung betrifft, kann eine Reparatur gerechtfertigt sein. Zunächst sollte eine Diagnose durchgeführt werden.

### Kann der Service auch die Anzeige und die Tasten prüfen?

Ja, wenn diese Komponenten zusammen mit dem Gerät oder Modul geliefert werden.

Dies ist besonders hilfreich, wenn unklar ist, ob das Problem auf der Hauptplatine oder im Bedienfeld liegt.

### Lohnt es sich immer, ein stark korrodiertes Steuergerät zu retten?

Nein.

Wenn die Kosten für Diagnose und Reparatur steigen und die Zuverlässigkeit nach der Reparatur ungewiss bleibt, kann ein Austausch sinnvoller sein.

Dies gilt insbesondere für Geräte, von denen die Lüftung des Objekts abhängt.

### Wie lässt sich die Servicediagnose beschleunigen?

Fügen Sie eine genaue Beschreibung des Fehlerbilds bei, statt lediglich anzugeben, dass das Gerät „nicht funktioniert“.

Hilfreich sind außerdem:

- Fotos,
- Fehlercode,
- Beschreibung der Anlage,
- Typ der angeschlossenen Verbraucher,
- Angaben zu Überspannungen oder Stromausfällen,
- Angaben zu Flüssigkeitsschäden oder zur Reinigung des Geräts.


## Installation und Verkabelung

### Wie werden Geräte an die Relaisklemmen C und NO angeschlossen?

C und NO sind typische Bezeichnungen eines Relaiskontakts:

- C — gemeinsamer Kontakt,
- NO — im Ruhezustand offener Kontakt.

Die Verwendung hängt vom Gerät und vom Schaltplan der Anlage ab. Der Kontakt kann beispielsweise zur Ansteuerung einer Schützspule verwendet werden. Seine zulässigen Kenndaten dürfen jedoch nicht überschritten werden.

:::warning Elektroarbeiten

Anschlüsse an Netzspannung sollten von einer entsprechend qualifizierten Person gemäß dem Schaltplan des jeweiligen Geräts ausgeführt werden.

:::

### Kann ein Relaisausgang einen großen Ventilator direkt versorgen?

Dies ist in der Regel keine geeignete Verwendung eines kleinen Steuerausgangs.

Für größere Lasten werden ein Schütz, ein Leistungsrelais oder ein spezielles Leistungsmodul eingesetzt.

### Wozu dienen die Klemmen A1 und A2 des Schützes?

Dies sind die Anschlüsse der Schützspule.

Wenn die entsprechende Spannung an die Spule angelegt wird, ändert das Schütz den Zustand seiner Leistungskontakte.

Die Spulenspannung muss der Anlagenplanung und der Dokumentation des Schützes entsprechen.

### Können zusätzliche Schaltgeräte im Gehäuse des Steuergeräts montiert werden?

Nur wenn die Konstruktion des jeweiligen Gehäuses dies zulässt und dadurch folgende Eigenschaften nicht beeinträchtigt werden:

- Schutzart,
- Isolierung,
- Kühlung,
- Sicherheit,
- Zugänglichkeit für Servicearbeiten.

Alle neuen Öffnungen sollten so ausgeführt werden, dass die erforderliche Dichtheit erhalten bleibt.

### Sind zusätzliche Ventilatorschalter hilfreich?

Sie können Servicearbeiten erleichtern und das unabhängige Abschalten einzelner Ventilatoren ermöglichen.

Die Ausführung muss jedoch die elektrischen Schutzmaßnahmen berücksichtigen und darf keine gefährlichen Zustände des Steuergeräts verursachen.

### Können Steuerleitungen zusammen mit Leistungsleitungen verlegt werden?

Empfindliche Signalleitungen sollten nicht parallel und in unmittelbarer Nähe zu Leitungen hoher Leistung verlegt werden, insbesondere über längere Strecken.

Die Anforderungen hängen von der Signalart und der elektromagnetischen Umgebung ab.

### Welche Leitung sollte für Netzwerkverbindungen und PoE-Geräte verwendet werden?

In den besprochenen Anlagen wurde als Mindestanforderung eine Twisted-Pair-Leitung der Kategorie 5e angegeben.

Wenn die Leitung in einer Umgebung mit erhöhtem Störpegel oder einem Risiko elektrostatischer Aufladungen verläuft, kann der Einsatz einer entsprechend geschirmten Leitung und eines ordnungsgemäßen Erdungssystems sinnvoll sein.

### Wird für PoE ein Crossover-Kabel benötigt?

In typischen Installationen wird eine standardmäßige, nicht gekreuzte Verbindung verwendet.

Die Anforderungen des Netzwerkgeräts und des eingesetzten PoE-Netzteils müssen jedoch immer geprüft werden.


## Betrieb und Wartung

### Wie lässt sich das Ausfallrisiko von Steuergeräten in Wirtschaftsgebäuden begrenzen?

Am wichtigsten ist die Begrenzung des Einflusses von:

- Feuchtigkeit,
- Ammoniak und aggressiven Umgebungsbedingungen,
- Staub,
- direkter Reinigung mit Wasser,
- Überspannungen,
- fehlerhafter Spannungsversorgung.

Außerdem sollte der Zustand der Leitungen, Verbindungen und Gehäuse regelmäßig kontrolliert werden.

### Sollten elektronische Geräte regelmäßig gereinigt werden?

Ja, insbesondere Geräte mit Kühlkörpern, Ventilatoren und Lüftungsöffnungen.

Angesammelter Staub beeinträchtigt die Kühlung.

Die Reinigung muss nach dem Trennen der Spannungsversorgung und gemäß der Geräteanleitung erfolgen.

### Ist nach mehreren Betriebsjahren eine Überprüfung des Steuergeräts sinnvoll?

Ja, insbesondere unter schwierigen Umgebungsbedingungen.

Die Überprüfung kann Folgendes umfassen:

- Beurteilung des Zustands der Steckverbindungen,
- Kontrolle auf Feuchtigkeits- und Korrosionsspuren,
- Prüfung der Kühlkomponenten,
- Prüfung des Bedienfelds und der Tasten,
- Test der Sensoren,
- Kontrolle der Akkus in Alarmsystemen.

### Was sollte nach einem Ausfall notiert werden?

Am hilfreichsten sind:

- vollständige Meldung,
- Fehlercode,
- Uhrzeit des Ereignisses,
- Temperatur,
- Zustand der Lüftung,
- Angabe zu einem Stromausfall,
- Angabe zum Betrieb des Stromaggregats,
- Foto der Anzeige oder des Geräts.

Das Gerät sollte nicht zurückgesetzt werden, bevor der Code notiert wurde, sofern die Situation dies sicher zulässt.

### Ist ein von der Lüftungssteuerung unabhängiges Alarmsystem sinnvoll?

Ja, insbesondere dort, wo ein Ausfall der Lüftung schnell zu gefährlichen Bedingungen führen kann.

Eine unabhängige Zentrale mit eigenem Akku und Fernbenachrichtigung bietet eine zusätzliche Schutzebene.

### Welche Informationen sollten vor der Kontaktaufnahme mit dem technischen Support vorbereitet werden?

Am besten werden folgende Angaben vorbereitet:

1. genaues Gerätemodell,
2. Beschreibung der Anlage,
3. Anzahl und Kenndaten der angeschlossenen Geräte,
4. aktuelle Einstellungen im Zusammenhang mit dem Problem,
5. genaues Fehlerbild,
6. vollständiger Fehler- oder Alarmcode,
7. Fotos des Geräts und der Typenschilder,
8. Angaben zu den letzten Änderungen an der Anlage.

Dadurch kann die Diagnose erheblich verkürzt werden.


## Wichtiger Hinweis zu älteren Geräten

Namen, Klemmenbezeichnungen und verfügbare Funktionen können sich zwischen Geräteversionen unterscheiden, die in verschiedenen Jahren hergestellt wurden.

Wenn das Gerät mehrere Jahre oder über zehn Jahre alt ist, müssen vor der Anwendung einer Anleitung für ein neueres Modell folgende Angaben bestätigt werden:

- genaue Gerätebezeichnung,
- Platinenversion,
- Anzeigetyp,
- Softwareversion,
- Klemmenplan.

:::warning Ältere Geräteversionen

Gehen Sie nicht allein aufgrund eines ähnlichen Gehäuseaussehens von vollständiger Kompatibilität aus. Bestätigen Sie vor der Verwendung eines Schaltplans oder einer Anleitung das genaue Modell und die Geräteversion.

:::


## Kontakt mit dem technischen Support

Wenn die FAQ das Problem nicht lösen, bereiten Sie vor der Kontaktaufnahme Folgendes vor:

- ein Foto des Steuergeräts,
- ein Foto des Typenschilds des Verbrauchers,
- Kenndaten der Motoren oder Stellantriebe,
- Anschlussplan,
- eine genaue Beschreibung der gewünschten Funktionsweise.

Dadurch kann die Auswahl des Geräts oder die Diagnose des Problems auf Grundlage der tatsächlichen Anlagenparameter statt auf Vermutungen erfolgen.
