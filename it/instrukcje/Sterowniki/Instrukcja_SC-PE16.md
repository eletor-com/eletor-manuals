---
id: sc-pe16
title: SC-PE16 — manuale d'uso
sidebar_label: SC-PE16
sidebar_position: 5
description: Manuale del modulo di espansione di potenza SC-PE16 — montaggio, collegamento,
  messa in funzione, menu e protezioni.
slug: /sc-pe16
toc_min_heading_level: 2
toc_max_heading_level: 3
---


Il modulo di espansione di potenza SC-PE16 serve a controllare i ventilatori quando il carico supera la capacità del controllore principale. Il dispositivo regola la tensione di alimentazione dei ventilatori in base a un segnale analogico o a un'impostazione manuale. La corrente totale massima di uscita è 16 A.

![Modulo di espansione di potenza ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Parametri e caratteristiche

- modalità AUTO e MANUAL e sospensione del dispositivo;
- display grafico e tastiera touch;
- controllo analogico 2–10 V o 4–20 mA;
- soglia programmabile di attivazione del gruppo di ventilazione 2;
- byPASS al livello stabilizzato 100%;
- protezione termica del circuito di potenza;
- safeRUN: livello di funzionamento di emergenza impostabile;
- calibrazione del livello minimo di ventilazione;
- test della ventilazione, del relè e dell'allarme;
- blocco della tastiera e blocco per la pulizia;
- lingua polacca, inglese o ucraina;
- alimentazione 230 V AC, 50 Hz; involucro IP65.

:::info Versione del software

La descrizione delle funzioni si riferisce al software fornito **ver. 2.1**. La disponibilità delle funzioni deve essere verificata in relazione alla versione installata nel dispositivo.

:::

## Installazione del controllore

:::danger Scollegare l'alimentazione

Durante l'installazione del dispositivo è tassativamente necessario scollegare l'alimentazione elettrica, poiché la tensione presente su alcuni componenti è pericolosa per la vita e la salute. Si raccomanda di affidare l'installazione a una persona qualificata.

:::

### Scelta del luogo di montaggio

Il dispositivo deve essere montato in un luogo accessibile al personale addetto, fuori dalla portata di bambini e animali, non esposto alla luce solare diretta. L'intervallo di temperatura ambiente va da −10°C a +40°C. Attorno all'involucro e al dissipatore deve essere garantita la libera circolazione dell'aria. Non coprire il dissipatore e non montare il dispositivo vicino a fonti di calore.

### Montaggio

Fissare la parte inferiore dell'involucro a una parete piana mediante quattro tasselli, utilizzando i fori di montaggio esterni al vano a tenuta. Montare il coperchio con la cerniera inclusa nel kit. Prima della chiusura, verificare lo stato e il posizionamento della guarnizione.

Utilizzare cavi con sezione esterna circolare, adatti ai pressacavi. Serrare i pressacavi in modo da garantire la tenuta e il bloccaggio del cavo. Chiudere i passaggi inutilizzati con tappi. Serrare tutte le viti del coperchio. La tenuta dipende dal corretto montaggio dell'involucro e dei passaggi per i cavi.

### Preparazione dei collegamenti

Eseguire tutti gli interventi all'interno dell'involucro dopo aver scollegato l'alimentazione e verificato l'assenza di tensione. Se la rimozione del pannello richiede di scollegare il cavo piatto, scollegarlo con cautela e reinserirlo prima di chiudere l'involucro. Non collegare né scollegare il cavo piatto con l'alimentazione inserita.

Posare i cavi di segnale INPUT e ENABLE separatamente dai cavi di alimentazione e di uscita. Attenersi alle sigle dei morsetti riportate sullo specifico esemplare del dispositivo. La massa degli ingressi di segnale e il morsetto di protezione PE svolgono funzioni diverse e non sono intercambiabili.

## Collegamento elettrico

:::danger Scollegare l'alimentazione

Prima di collegare il sistema, assicurarsi che l'alimentazione sia disinserita!

:::

![Morsetti di alimentazione, ventilatori, GR 2, ENABLE, CAN e INPUT](./img/sc-pe16/zaciski.png)

| MORSETTO | FUNZIONE |
| --- | --- |
| L, N, PE — alimentazione | Alimentazione 230 V AC, 50 Hz: L — fase, N — conduttore neutro, PE — conduttore di protezione. Nella documentazione originale è indicata una protezione B20; la scelta delle protezioni e dei cavi deve tenere conto dell'impianto e del carico. |
| U, N, PE — ventilatori | U — uscita di fase regolata; N e PE — rispettivi morsetti comuni del dispositivo. La somma delle correnti dei ventilatori non deve superare 16 A. Ogni ventilatore richiede una protezione separata. Utilizzare motori idonei alla regolazione della tensione. |
| GR 2: C, NO | Contatto isolato del relè del gruppo 2. Si chiude quando il livello di ventilazione impostato è pari o superiore alla soglia «Gruppo di ventilazione 2». Corrente massima del contatto secondo il manuale fornito: 6 A. In caso di comando diretto del carico, la documentazione indica una protezione esterna B6. |
| INPUT: V, massa | Ingresso in tensione. Selezionare «Tipo di controllo → Ingresso V». Nel programma analizzato l'intervallo di regolazione è 2–10 V. Non collegare a questo ingresso la tensione di rete né l'uscita di alimentazione regolata dei ventilatori. |
| INPUT: I, massa | Ingresso in corrente 4–20 mA. Selezionare «Tipo di controllo → Ingresso I». Collegare il segnale secondo le indicazioni della sorgente e del ricevitore. |

Per il controllo utilizzare l'ingresso V oppure I selezionato. SC-PE16 richiede una propria alimentazione di rete; l'ingresso analogico trasmette esclusivamente il valore di comando.

## Ingresso ENABLE e comunicazione

### ENABLE: E e massa

L'ingresso funziona con un contatto privo di potenziale. I morsetti E e massa possono essere esclusivamente cortocircuitati o aperti; non applicare tensioni esterne. Il cortocircuito abilita il funzionamento, l'apertura imposta il livello 0%. L'arresto è soggetto all'impostazione «Tempo di decelerazione».

La gestione di ENABLE si attiva separatamente per AUTO e MANUAL nel menu «Avanzate → Ventilatore». Entrambe le funzioni sono disattivate di fabbrica, pertanto in tale condizione non è necessario alcun ponticello. L'apertura di ENABLE non equivale alla sospensione: il pannello rimane attivo. In AUTO, con il blocco ENABLE attivo, il programma omette la lettura del segnale di comando e non attiva safeRUN.

### CAN e Wi-Fi

Le voci «Ingresso CAN» e «Ingresso WiFi» sono presenti nel menu, ma nel software ver. 2.1 non eseguono il controllo: entrambe le funzioni restituiscono il livello 0%. Per mettere in funzione il dispositivo con questo programma, selezionare l'ingresso V o I. Non configurare l'impianto basandosi su CAN o Wi-Fi senza averne confermato il supporto nella versione del software installata.

## Principio di funzionamento

SC-PE16 è un regolatore di potenza che esegue i comandi del controllore principale o dell'operatore. Non misura la temperatura del locale e non dispone di proprie impostazioni di temperatura, ricambio d'aria, riscaldamento supplementare o serrande di ingresso dell'aria. Il livello percentuale di ventilazione indica un valore di comando e non una misura della velocità effettiva del motore.

| SEGNALE NOMINALE | LIVELLO DI VENTILAZIONE IMPOSTATO |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

Tra i valori limite, il programma determina il livello in modo lineare e lo arrotonda a percentuali intere. Per l'ingresso V l'aumento inizia al superamento della lettura 2,04 V, mentre per l'ingresso I al superamento di 4,04 mA. Lo stato finale dell'uscita dipende anche da ENABLE, dall'avviamento e dalla protezione termica.

## Funzionamento di emergenza e protezioni

### safeRUN — perdita del segnale di ingresso

In modalità AUTO, l'allarme «Ingresso» compare quando la lettura della tensione scende al di sotto di 1,50 V oppure quella della corrente al di sotto di 2,00 mA, a seconda dell'ingresso selezionato. Il programma imposta quindi il livello «Funzionamento di emergenza» nell'intervallo 0–100%; valore di fabbrica 30%. Quando il segnale torna alla soglia di rilevamento o la supera, l'allarme di ingresso cessa e il dispositivo torna al controllo analogico.

Gli intervalli 1,50–2,04 V e 2,00–4,04 mA producono il livello 0% senza allarme di ingresso. In questa versione il segnale 0 V non costituisce un normale comando di arresto, ma attiva il funzionamento di emergenza. Il controllore principale con uscita 0–10 V deve essere configurato per l'intervallo 2–10 V senza discesa a 0 V. In MANUAL il segnale analogico non controlla la ventilazione e l'allarme di ingresso viene cancellato.

### Protezione termica

L'allarme «Surriscaldamento» viene attivato quando la lettura della temperatura del dissipatore supera 87°C. Si cancella quando scende al di sotto di 80°C. Durante l'allarme il programma modifica il livello impostato: per valori pari o superiori a 50% imposta 100%, mentre per valori inferiori a 50% imposta 0%. La variazione dell'uscita è soggetta all'algoritmo di avviamento e decelerazione. La protezione non garantisce il funzionamento continuo della ventilazione in ogni circostanza.

Lo stato del relè GR 2 viene determinato prima della correzione termica: dipende dal livello precedente alla forzatura a 0% o 100%. Anche il livello di funzionamento di emergenza è soggetto alla correzione termica. In caso di surriscaldamento, verificare le condizioni di raffreddamento, la presenza di sporco sul dissipatore e il carico; affidare gli interventi all'interno dell'involucro a una persona abilitata.

### byPASS e avviamento graduale

Al livello di uscita stabilizzato 100% il programma attiva il relè di bypass del circuito di regolazione di fase. L'avviamento può comprendere una rampa fino a 100%, un mantenimento a 100% e il passaggio al livello impostato. I parametri «Soft Start» influiscono anche sulla velocità di risposta dell'uscita alle variazioni della richiesta.

## Prima messa in funzione del controllore

:::warning Calibrazione dei ventilatori

Attenzione! Alla prima messa in funzione del dispositivo è tassativamente necessario impostare la banda di funzionamento vietata del motore.

:::

1. Con l'alimentazione scollegata, verificare il collegamento dell'alimentazione, del PE, dei ventilatori e del segnale analogico. Confermare l'idoneità dei motori alla regolazione della tensione e una corrente totale non superiore a 16 A.
2. Inserire l'alimentazione. Se viene proposta la selezione della lingua, premere OK e selezionare la lingua. Sbloccare la tastiera con il pulsante con il simbolo del lucchetto.
3. In «Tipo di controllo» selezionare «Ingresso V» oppure «Ingresso I». Impostare il livello «Funzionamento di emergenza» e la soglia «Gruppo di ventilazione 2». Se necessario, attivare ENABLE separatamente per la modalità interessata.
4. Accedere a «Avanzate → Ventilatore → Banda vietata». In questa voce il programma forza il livello 1% e la modifica del parametro influisce immediatamente sull'uscita. L'intervallo va da −20 a 200, con valore di fabbrica 0. Un valore positivo aumenta il livello minimo di comando, un valore negativo lo riduce.
5. Scegliere il valore in modo che tutti i ventilatori ruotino stabilmente, senza arresti e senza riscaldamento eccessivo. Osservare ogni ventilatore, preferibilmente con l'aiuto di una seconda persona. Il solo sollevamento della serranda non sostituisce la verifica del corretto funzionamento del motore. Confermare con OK; ESC ripristina l'impostazione precedente.
6. Verificare l'uscita a diversi livelli, inclusi 0%, un livello basso e 100%. Ripetere la calibrazione dopo la sostituzione dei ventilatori o una modifica della loro configurazione.
7. In AUTO verificare la risposta al segnale minimo e massimo. Successivamente verificare l'interruzione del segnale e il passaggio al funzionamento di emergenza, nonché il ritorno dopo il ripristino del segnale. Se ENABLE è attivo, verificarne anche il funzionamento.
8. Verificare GR 2 e la segnalazione dell'allarme nel menu «Test». Al termine dei test uscire da questa voce e selezionare la modalità di funzionamento definitiva.

:::warning Attivazione effettiva delle uscite

I test e la calibrazione comandano le uscite reali. Possono avviare i ventilatori e il test della ventilazione forza il livello indipendentemente dal controllo normale. Garantire condizioni di prova sicure e una sorveglianza costante.

:::

## Programmazione del controllore

### Pannello frontale — indicatori e pulsanti

| ELEMENTO | UTILIZZO |
| --- | --- |
| Alimentazione / sospensione | Il pulsante con il simbolo di alimentazione visualizza la richiesta di conferma della sospensione; confermare con OK. Una nuova pressione riattiva il dispositivo. La sospensione imposta le uscite sullo stato disattivato; non scollega la tensione di rete. |
| Lucchetto | Attiva o disattiva il blocco della tastiera. Dopo lo sblocco, la spia accanto al lucchetto è accesa. Nella schermata principale il blocco si riattiva dopo circa 30 s di inattività. |
| A — AUTO | Seleziona il controllo dall'ingresso analogico dopo la conferma con OK. La spia A indica la modalità selezionata. |
| M — MANUAL | Seleziona il controllo manuale dopo la conferma con OK. Nella schermata principale i tasti + e − modificano l'impostazione 0–100%. La spia M indica la modalità selezionata. |
| +, −, OK, ESC | OK apre il menu, accede alla voce e conferma il valore. + e − selezionano la voce o modificano il valore. ESC torna al livello precedente oppure annulla la modifica. |
| Allarme e gruppo 2 | La spia rossa segnala un allarme. La spia accanto al simbolo del ventilatore «2» segnala l'attivazione del relè GR 2. |
| Display | In AUTO mostra il livello di ventilazione impostato, la lettura dell'ingresso selezionato, il grafico a barre e gli allarmi. Con ENABLE attivo ne mostra anche lo stato. In MANUAL il valore principale indica l'impostazione manuale; le protezioni possono modificare l'uscita. |

### Memorizzazione delle impostazioni

I parametri del menu vengono salvati nella memoria non volatile dopo la conferma con OK. Le modifiche del livello MANUAL hanno effetto immediato e il salvataggio avviene dopo un breve periodo di inattività. Dopo un'interruzione dell'alimentazione vengono ripristinate le impostazioni salvate, comprese la modalità AUTO/MANUAL, il livello manuale e lo stato di sospensione. Non disinserire l'alimentazione subito dopo aver modificato l'impostazione manuale.

In caso di checksum errato o di valori fuori intervallo, il programma ripristina i valori di fabbrica. Occorre quindi verificare nuovamente tutte le impostazioni, in particolare la calibrazione dei ventilatori, l'ingresso di comando e il funzionamento di emergenza.

## Funzioni del menu di base

| MENU | INTERVALLO / VALORE DI FABBRICA | DESCRIZIONE |
| --- | --- | --- |
| Tipo di controllo | Ingresso V | Selezione di V, I, CAN o Wi-Fi. Per la versione analizzata utilizzare V (2–10 V) oppure I (4–20 mA). CAN e Wi-Fi non eseguono il controllo. |
| Gruppo di ventilazione 2 | 1–100% / 100% | Soglia di chiusura del contatto GR 2. Il contatto è chiuso a un livello pari o superiore alla soglia e aperto al di sotto della soglia. Il programma non definisce un'isteresi separata. |
| Funzionamento di emergenza | 0–100% / 30% | Livello impostato in caso di perdita del segnale analogico selezionato in AUTO. Il valore 0% indica l'arresto in caso di perdita del segnale. |
| Blocco per la pulizia | 60 s | Blocca l'uso dei tasti per 60 secondi e visualizza il conto alla rovescia. La regolazione della ventilazione continua a funzionare. La funzione serve per pulire il pannello con un panno, non per interventi elettrici né per lavare l'interno. |
| Avanzate | Sottomenu | Accesso ai test, alla lingua, alla calibrazione del ventilatore, a ENABLE, a Soft Start, al suono di allarme, alle impostazioni di fabbrica e alle informazioni sul programma. |

## Funzioni del menu avanzato

| MENU / PARAMETRO | INTERVALLO / VALORE DI FABBRICA | DESCRIZIONE |
| --- | --- | --- |
| Test → Ventilazione | 0–100% | Forzatura temporanea dell'uscita regolata. Le modifiche hanno effetto durante l'impostazione. Uscendo con OK o ESC si ripristina il controllo normale. |
| Test → Vent. stadio 2 | No / Sì | Forzatura temporanea del contatto GR 2 e della relativa spia. |
| Test → Allarme | No / Sì | Test temporaneo della segnalazione di allarme, compreso il suono, indipendentemente dalla normale impostazione «Segnale di allarme». |
| Lingua | Polacco | Sono selezionabili polacco, inglese e ucraino. |
| Ventilatore → Banda vietata | −20–200 / 0 | Calibrazione del livello 1%. Durante la modifica viene forzata l'uscita reale 1%. Il parametro non è espresso né in percentuale né in secondi. |
| Ventilatore → Attivazione EN AUTO | No / Sì; No | Attiva la dipendenza della modalità AUTO dall'ingresso ENABLE. |
| Ventilatore → Attivazione EN MANUAL | No / Sì; No | Attiva la dipendenza della modalità MANUAL dall'ingresso ENABLE. |
| Soft Start → Tempo di accelerazione | 0–50 / 5 | Velocità di aumento del livello all'avviamento fino a 100%. Un valore maggiore indica una variazione più lenta. Il valore 0 salta la fase di aumento. |
| Soft Start → Tempo 100% | 0–250 / 100 | Mantenimento del livello 100% durante l'avviamento. Il valore 0 salta la fase di mantenimento. Impostando sia l'accelerazione sia il mantenimento su 0 si salta la ventilazione iniziale fino a 100%. |
| Soft Start → Tempo di decelerazione | 0–50 / 5 | Velocità di raggiungimento del livello richiesto, anche quando questo viene modificato. Il valore 0 indica una variazione senza avvicinamento graduale. |
| Segnale di allarme | No / Sì; No | Attiva il suono di segnalazione dell'allarme. L'impostazione No non elimina il messaggio sullo schermo né la segnalazione tramite spia. |
| Impostazioni di fabbrica | No / Sì | Selezionando Sì ripristina e salva i valori predefiniti, inclusi la calibrazione 0, l'ingresso V, AUTO, il funzionamento di emergenza 30%, la soglia GR 2 pari a 100% e ENABLE disattivato. Dopo l'operazione, configurare e verificare nuovamente il dispositivo. |
| Programma | ver. 2.1 + data di compilazione | Visualizza la versione e la data di compilazione del programma. La presente descrizione è stata redatta sulla base dei sorgenti forniti SC_PX16_v02. |

I parametri Soft Start sono impostazioni adimensionali dei contatori del programma, non tempi espressi in secondi. A 50 Hz un singolo passo corrisponde approssimativamente a (impostazione + 1) × 20 ms: per l'accelerazione e la decelerazione si tratta del tempo di variazione di 1 punto percentuale, per «Tempo 100%» del tempo di mantenimento. Il valore 0 ha il significato descritto nella tabella. I tempi effettivi dipendono dalla fase dell'algoritmo.

## Messaggi di errore e avvertenze

| MESSAGGIO | SIGNIFICATO E INTERVENTO |
| --- | --- |
| Ingresso | Lettura troppo bassa del segnale selezionato in AUTO. Il dispositivo imposta il funzionamento di emergenza. Verificare la sorgente del segnale, i cavi, la massa comune e la selezione V/I. |
| Surriscaldamento | Lettura del dissipatore &gt;87°C; cancellazione &lt;80°C. Ventilazione impostata su 0% oppure 100%, secondo la descrizione della protezione termica. Verificare il raffreddamento e il carico. |
| Alimentazione | Disturbo della sincronizzazione del circuito di potenza con la rete. Verificare l'alimentazione e l'impianto. In caso di interruzione totale dell'alimentazione il display non funziona. |
| Memoria CRC | Errore di checksum o di intervallo delle impostazioni salvate. Il programma ripristina i valori predefiniti. Verificare la configurazione e ripetere la calibrazione; se l'errore si ripete, contattare l'assistenza. |

## Note e avvertenze

:::danger Scollegare l'alimentazione

Durante l'installazione del dispositivo è tassativamente necessario scollegare l'alimentazione elettrica, poiché la tensione presente su alcuni componenti è pericolosa per la vita e la salute. Si raccomanda di affidare l'installazione a una persona qualificata.

:::

Prima dell'installazione e dell'uso, leggere il manuale. Affidare le riparazioni e gli interventi all'interno del dispositivo a personale abilitato. La sospensione, il blocco della tastiera, ENABLE e l'impostazione 0% non costituiscono uno scollegamento dell'alimentazione e non garantiscono condizioni sicure per gli interventi elettrici.

Scegliere le impostazioni di ventilazione e di funzionamento di emergenza in base alle esigenze degli animali e dell'impianto. Controllare regolarmente il funzionamento effettivo di tutti i ventilatori. La segnalazione SC-PE16 non sostituisce il monitoraggio indipendente delle condizioni nell'edificio e delle interruzioni di alimentazione. Nella morsettiera illustrata non è presente un contatto ALARM separato per la centralina.

:::note Smaltimento del dispositivo

Al termine dell'utilizzo, il prodotto non deve essere gettato insieme ai rifiuti urbani indifferenziati, ma deve essere smaltito in conformità alle disposizioni vigenti (direttive WEEE dell'Unione europea 2012/19/UE).

:::

Il prodotto è stato realizzato in conformità ai requisiti RoHS (direttiva dell'Unione europea 2011/65/UE).

## Dati tecnici del controllore

| PARAMETRO | VALORE |
| --- | --- |
| Alimentazione / consumo proprio | 230 V AC, 50 Hz / &lt;10 W |
| Corrente totale massima dell'uscita U | 16 A |
| Corrente massima del contatto GR 2 | 6 A; contatto C–NO, isolato |
| Ingresso V / ingresso I | 2–10 V / 4–20 mA, selezionabili nel menu |
| Soglia di perdita del segnale (lettura del programma) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Contatto privo di potenziale E–massa; attivazione separata per AUTO/MANUAL |
| Protezione termica (lettura del dissipatore) | Allarme &gt;87°C; ripristino &lt;80°C |
| Temperatura ambiente / involucro | −10°C a +40°C / IP65 |
| Dimensioni / resistenza alle sovratensioni | 34 × 29 × 12 cm / 210 J |
| Lingue del menu | Polacco, inglese, ucraino |

Contenuto del kit secondo la documentazione fornita: 4 tasselli a espansione, 2 pressacavi PG13,5, 1 pressacavo PG9 e 1 cerniera.

## Condizioni di garanzia

Il testo delle condizioni di garanzia è stato mantenuto dal documento fornito dal produttore.

1. Il produttore ELETOR con sede in Polonia, indirizzo: Pod Sosno 28, 87-305 Zbiczno (di seguito denominato garante), concede all'Acquirente una garanzia di qualità della merce per la quale è stato emesso il presente certificato di garanzia, a condizione che sia utilizzata conformemente alla destinazione d'uso e alle regole indicate nel manuale d'uso consegnato all'Acquirente insieme alla merce.
2. Il periodo di garanzia è di 24 mesi dalla data di vendita. I guasti o difetti della merce emersi durante tale periodo saranno eliminati gratuitamente. Dopo la scadenza del periodo di garanzia o in caso di decadenza dai diritti di garanzia, i guasti o difetti saranno eliminati a pagamento.
3. La garanzia non copre:

   - qualsiasi difetto verificatosi a causa di un uso improprio della merce (incluse operazioni non descritte nel manuale d'uso, ecc.);

   - qualsiasi difetto derivante da riparazioni, modifiche, ecc. eseguite da persone diverse dal garante;

   - qualsiasi difetto o danno verificatosi durante il trasporto o a seguito della caduta della merce, se tali eventi si sono verificati dopo l'acquisto, nonché i danni meccanici causati da un uso scorretto da parte dell'utente;

   - qualsiasi difetto o danno causato da incendio, terremoto, alluvione, fulminazione o altre calamità naturali, inquinamento ambientale, azione di radiazioni ionizzanti esterne o di campi magnetici, nonché da forniture irregolari di energia elettrica o da corrente con parametri non conformi a quelli richiesti;

   - qualsiasi difetto derivante da conservazione non corretta (ad es. conservazione della merce al di fuori degli intervalli di temperatura o umidità indicati nelle specifiche, in prossimità di sostanze chimiche), manutenzione o pulizia inadeguate, ecc.;

   - qualsiasi difetto derivante dall'esaurimento delle batterie di alimentazione, ecc.;

   - qualsiasi difetto causato da sabbia, fango, polvere, acqua e altri liquidi, ecc. penetrati all'interno dell'involucro della merce;

   - danni derivanti dall'usura naturale, parziale o totale, della merce in conformità alle sue caratteristiche o alla sua destinazione d'uso;

   - le operazioni indicate nel manuale d'uso che l'utente è tenuto a eseguire autonomamente.

4. L'Acquirente decade dai diritti di garanzia in seguito a:

   - esecuzione di qualsiasi riparazione o modifica della merce da parte di persone diverse dal garante;

   - accertamento della manomissione, del danneggiamento o della rottura di uno qualsiasi dei sigilli;

   - accertamento del danneggiamento, della manomissione, dell'occultamento o della rimozione dei numeri di serie o di altri contrassegni identificativi della merce.

5. Il termine di riparazione è fino a 21 giorni lavorativi dalla data di segnalazione del difetto e di consegna della merce completa al centro di assistenza del garante. In casi particolarmente giustificati, legati alla necessità di reperire dall'estero elementi o sottogruppi oppure a danni particolarmente complessi o difficili da riparare o diagnosticare, il termine di riparazione può essere prolungato del periodo necessario per adempiere agli obblighi di garanzia.
6. I diritti dell'Acquirente derivanti dalla garanzia possono essere esercitati solo previa presentazione di un certificato di garanzia valido e correttamente compilato il giorno dell'acquisto e della prova d'acquisto (fattura, scontrino, ecc.). Le modifiche non autorizzate alle annotazioni sul certificato di garanzia (incluse cancellature, abrasioni, aggiunte, ecc.) comportano la decadenza dai diritti di garanzia. Il certificato di garanzia privo di denominazione, modello, numero di serie della merce, data e luogo di acquisto della merce, nonché del timbro leggibile e della firma del Venditore, non è valido e non costituisce una base per presentare validamente un reclamo.
7. L'Acquirente è tenuto a consegnare la merce a proprie spese in un imballaggio adeguato all'apparecchiatura, che garantisca un trasporto e una conservazione sicuri e corretti, oppure a sostenere i costi di trasferta del garante. Qualora si accerti che la merce consegnata per la riparazione è tecnicamente funzionante e priva di difetti, oppure che il guasto riscontrato non è coperto dalla garanzia, all'Acquirente saranno addebitati i costi dei servizi e del trasporto.
8. L'Acquirente è tenuto a ritirare la merce riparata entro 90 giorni dalla comunicazione dell'avvenuta riparazione da parte del garante. Se l'acquirente non ritira la merce entro tale termine, assume il rischio di perdita o danneggiamento accidentale della merce.
9. Il periodo di garanzia viene prolungato per la durata della riparazione, calcolata dalla data di consegna della merce fino al termine concordato per il ritiro dopo la riparazione. Il garante è tenuto a rilasciare un documento attestante il periodo e l'entità dei difetti della merce eliminati.

10. L'Acquirente presenta le richieste tramite il Venditore della merce oppure direttamente all'indirizzo del garante: ELETOR, Pod Sosno 28, 87-305 Zbiczno, Polonia.

11. Il garante non è responsabile:

    - del mancato guadagno conseguente alla comparsa del difetto e al tempo necessario per eliminarlo;

    - delle perdite conseguenti alla comparsa del difetto e di qualsiasi danno derivante da installazione, uso o programmazione non corretti delle funzioni del dispositivo.
