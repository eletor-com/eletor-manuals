---
sidebar_position: 3
title: Manuale SC-12
description: Regolatore climatico per locali zootecnici con corrente di uscita consentita
  fino a 12A
keywords:
- eletor sc-12
- regolatore di ventilazione
- regolatore climatico
- regolatore di ventilazione per porcili
- regolatore del microclima
- regolatore per porcili
- ventilazione dei porcili
- regolatore per locali di accrescimento
---

# Regolatore SC-12

Regolatore climatico a microprocessore appartenente alla serie SPEED CONTROL. La versatilità del dispositivo è garantita dall'elevato numero di ingressi/uscite del sistema e dal software intuitivo in lingua polacca e inglese. Il programma del regolatore, oltre alle impostazioni di base delle temperature, del ricambio d'aria, del riscaldamento supplementare, dei livelli min./max. di ventilazione e degli allarmi, consente di eseguire test e di memorizzare la calibrazione degli attuatori collegati al regolatore.

**Parametri e caratteristiche:** 
- Ventilazione del gruppo I: 
  - corrente max. dell'uscita a regolazione continua 12A,
  - protezione termica del sistema, 
  - avviamento graduale della ventilazione – soft start,
  - relè di bypass a comando massimo, 
  - calibrazione della velocità minima di rotazione, 
  - programma di risparmio energetico con sistema di serrande ad apertura anticipata.
- Ventilazione del gruppo II, contatto isolato fino a 6A.
- Riscaldamento supplementare, contatto isolato fino a 6A
- Uscite di allarme NO e NC: 
  - segnalazione di interruzione dell'alimentazione,
  - segnalazione del superamento della soglia di temperatura min. o max.,
  - segnalatore acustico integrato.
- 3 uscite indipendenti 0..10V:
  - compatibilità con moduli di espansione,
  - comando del sistema di serrande, 
  - regolazione del riscaldamento a potenza variabile.**
- Due ingressi analogici per la misurazione della temperatura.
- Porta digitale per la misurazione della temperatura (fino a 4 sensori).
- Due uscite a relè funzionali (a scelta):
  - compatibilità con attuatori lineari, 
  - III e IV gruppo di ventilazione
- Due ingressi analogici 0-10V.
- Alimentazione del potenziometro DC 10V.
- Alimentazione ausiliaria DC 12V.
- Possibilità di collegamento a un computer fino a 1200m.
- Involucro ermetico IP65.
- Tensione di alimentazione 230VAC 50Hz.
- Potenza assorbita dal sistema < 10V

# Installazione del regolatore
:::danger 
 Durante l'installazione del dispositivo è obbligatorio scollegare l'alimentazione elettrica, poiché la tensione presente su alcuni componenti è pericolosa per la vita e la salute. Si raccomanda di affidare l'installazione a una persona qualificata.  Questa operazione è pericolosa
:::

## Scelta del luogo di montaggio
Il luogo di montaggio deve essere scelto in modo razionale, tenendo conto della facilità di accesso al dispositivo per le persone autorizzate e dell'inaccessibilità per animali e bambini. Occorre inoltre considerare le condizioni climatiche, ossia il dispositivo deve funzionare nell'intervallo di temperatura da -10°C a 40 °C, in un luogo non esposto alla luce solare diretta. Attorno al dispositivo deve essere garantita la libera circolazione dell'aria. Il dispositivo comprende un sensore di temperatura.  

### Per il montaggio del sensore di temperatura si applicano alcune regole:
 - il sensore non deve essere montato in un luogo privo di circolazione dell'aria o esposto alla luce solare diretta,
 - il sensore non deve essere montato sulla parete portante (esterna) dell'edificio,
 - evitare la vicinanza a dispositivi che emettono calore, come radiatori e lampade,
 - non collocare il sensore direttamente accanto a porte e aperture di ventilazione,
 - non collocare il sensore in luoghi accessibili agli animali,
 - si raccomanda di posare il cavo di collegamento del sensore lontano dai cavi di alimentazione.

# Montaggio
Il dispositivo può funzionare in condizioni climatiche aggressive. Se montati correttamente, il regolatore e il sensore di temperatura sono resistenti agli effetti dannosi dell'ambiente.  

### Durante il montaggio occorre prestare attenzione ai seguenti aspetti:
 - prima di avvitare, controllare la guarnizione del coperchio,
 - il coperchio deve essere serrato con tutte le viti,
 - i cavi utilizzati per il collegamento del regolatore devono essere a sezione circolare,
 - dopo aver collegato il cavo, serrare i pressacavi in modo da garantire la tenuta e l'immobilizzazione del cavo; si raccomanda l'uso di silicone,
 - le uscite non utilizzate (pressacavi) devono essere chiuse con tappi,
 - fissare il regolatore (la parte inferiore dell'involucro) a una parete piana con 4 tasselli a espansione.

# Collegamento elettrico
:::danger 
 Prima di collegare il sistema, assicurarsi che l'alimentazione sia disinserita!
Questa operazione è pericolosa
:::

Prima di procedere al collegamento del regolatore, svitare e rimuovere il coperchio. Introdurre i cavi attraverso i pressacavi in gomma e procedere al loro collegamento. I morsetti del regolatore sono illustrati nella figura seguente.

![Collegamento ](./img/sc-12.png)

**Collegare il connettore AC 230V** all'alimentazione (quadro di distribuzione). È richiesto l'impiego di un interruttore di protezione da sovracorrente 1P-B6 e di scaricatori di sovratensione di tipo T1 T2. Quando si collegano più dispositivi, è buona prassi raggruppare i regolatori su diverse «fasi» (L1, L2, L3), al fine di distribuire uniformemente il carico sulla linea di alimentazione.

**Il connettore FAN** deve essere collegato direttamente al ventilatore; se si comandano più ventilatori, il carico totale non deve superare 6A e ciascun ventilatore deve essere protetto separatamente. Non prelevare PE e N dall'alimentazione (quadro di distribuzione); è obbligatorio collegarli ai terminali del regolatore.

**Il connettore FAN 2** può essere utilizzato per collegare i ventilatori del gruppo 2 o i sistemi di nebulizzazione. L'uscita è isolata, la corrente massima del contatto è 6A (è richiesto un interruttore esterno di protezione da sovracorrente di tipo 1P-B6 in caso di comando diretto del carico); il contatto si chiude quando la temperatura misurata è superiore alla somma della temperatura impostata e della banda di ventilazione.

**Il connettore HOT** può essere utilizzato per collegare un aerotermo. L'uscita è isolata, la corrente massima del contatto è 6A (è richiesto un interruttore esterno di protezione da sovracorrente 1P-B6 in caso di comando diretto del carico); il contatto si chiude quando la temperatura misurata scende al di sotto del valore impostato.

**Il connettore ALARM** dispone di uscite isolate NC, C e NO per il collegamento alla centralina di allarme. L'allarme si attiva nei seguenti casi:
    - la temperatura è troppo bassa o troppo alta,
    - il regolatore o il sensore di temperatura è danneggiato,
    - la tensione di alimentazione del regolatore è venuta a mancare,
    - si è verificato un funzionamento anomalo del regolatore (ad es. surriscaldamento del regolatore)
La figura seguente illustra il collegamento del ventilatore alla centralina di allarme.

![Collegamento di allarme](./img/alarmsc-s.png)

**Il connettore FUNC1 e FUNC2** serve a collegare il meccanismo di sollevamento per l'apertura delle prese d'aria basato su un motore a rotazione destra/sinistra. Il relè FUNC1 inserisce l'alimentazione dell'attuatore, mentre FUNC2 commuta il senso di rotazione del motore. Esempio di schema di collegamento del meccanismo di sollevamento (è richiesto un interruttore esterno di protezione da sovracorrente 1P-B6):
Disattivando la funzione del meccanismo di sollevamento, le uscite FUNC1 e FUNC2 funzionano come contatti, rispettivamente, del gruppo di ventilazione 3 e 4.

![Collegamento del meccanismo di sollevamento](./img/Sc-12fan.png)

**Il connettore 12V** è destinato all'alimentazione dei sensori esterni.

**Il connettore V1 0-10V** serve a collegare i moduli di espansione della potenza. La tensione su questo morsetto è proporzionale al livello di ventilazione.

**Il connettore V2 0-10V** serve a collegare l'attuatore che apre le serrande di ingresso dell'aria.

**Il connettore V3 0-10V** serve a collegare il sistema di riscaldamento a potenza regolabile in modo continuo. La tensione su questa uscita aumenta proporzionalmente alla diminuzione della temperatura, a partire dalla temperatura di riscaldamento supplementare.

**Il connettore 10V** serve ad alimentare il potenziometro del meccanismo di sollevamento o altri sistemi di tipo 0-10V.

**Collegare il connettore SENS1 (SENS2)** a 1 sensore di temperatura TS3 o TS5; la polarità non è rilevante. In caso di collegamento simultaneo di 2 sensori, viene calcolata la media delle temperature misurate. È buona prassi tenere i cavi di misura lontano dai cavi di alimentazione.

**Il connettore 1-WIRE** può essere utilizzato per collegare un numero maggiore di sensori digitali di temperatura, fino a un massimo di 4, collegati in parallelo (rispettare la corretta polarità). La lunghezza massima del cavo di collegamento dei sensori è 150m (la lunghezza non influisce sulla misurazione della temperatura); si raccomanda di utilizzare un cavo schermato.

**Il connettore RS-485** può essere utilizzato per realizzare sistemi di ventilazione e per la comunicazione con un PC.

**Il connettore IN1 0-10** serve a immettere il segnale di retroazione del sistema di prese d'aria – determina la posizione attuale delle prese.

**Il connettore IN2 0-10** serve a collegare il regolatore ad altri sensori, ad es. di umidità, CO2, oppure a utilizzare il regolatore come espansione della potenza.

# Principio di funzionamento
Il compito principale del regolatore è mantenere la temperatura nel locale di allevamento al livello stabilito dall'allevatore. Occorre ricordare che il regolatore è soltanto uno strumento che contribuisce a garantire condizioni climatiche ottimali nel locale di allevamento. Il ruolo principale in questo processo è tuttavia svolto dall'allevatore, che deve adattare le impostazioni del dispositivo alle variazioni delle condizioni climatiche esterne e, soprattutto, alle esigenze degli animali presenti nell'edificio zootecnico, nonché monitorare lo stato di funzionamento del dispositivo mediante la centralina di allarme.

## Prima messa in servizio del regolatore
:::danger 
 Alla prima messa in servizio del regolatore è obbligatorio impostare la banda vietata di funzionamento del motore.

:::
Il regolatore è compatibile con ventilatori dotati di motore asincrono monofase con un assorbimento massimo complessivo di corrente pari a 12A. Dopo aver collegato i ventilatori scelti, l'utente deve adattarli al funzionamento con il regolatore. In altre parole, è necessario impostare il livello minimo di funzionamento (velocità di rotazione) del ventilatore. Questa funzione è denominata «Banda vietata» e viene impostata dall'utente una sola volta nelle «Impostazioni avanzate». Per eseguire correttamente questa operazione, è consigliabile l'aiuto di una seconda persona che possa osservare costantemente il comportamento del ventilatore mentre l'altra persona imposta il valore della «Banda vietata» (il valore impostato in fabbrica è 0). La mancata impostazione della banda vietata può causare un funzionamento anomalo del dispositivo. Il valore della «Banda vietata» può essere considerato corretto quando la pressione generata dal ventilatore inizia a sollevare leggermente le serrande del camino di ventilazione. L'impostazione della «Banda vietata» deve essere ripetuta quando si sostituisce il ventilatore collegato al regolatore.

## Ricambio d'aria periodico
Il ricambio d'aria è una funzione eseguita dal regolatore che si attiva quando la temperatura nel locale scende al di sotto della temperatura impostata. Questa funzione garantisce agli animali un apporto ciclico di aria fresca. Nel menu Ricambio d'aria sono disponibili 3 parametri:
- **«Tempo di funzionamento»** - definisce per quanti minuti deve essere attivato il ventilatore;
- **«Tempo di pausa»** - definisce il tempo di arresto del ventilatore;
- **«Livello di ricambio d'aria»** - definisce la potenza di ventilazione durante il «Tempo di funzionamento».

Tutti i parametri sopra elencati sono impostati dall'utente. 

### Durante l'impostazione dei parametri del ricambio d'aria occorre ricordare alcune regole:
- il ricambio d'aria si attiva esclusivamente quando la temperatura nel porcile scende al di sotto della temperatura impostata,
- la funzione principale del ricambio d'aria è garantire agli animali un apporto ciclico di aria fresca e non mantenere la temperatura impostata nel locale,
- si raccomanda di effettuare ricambi d'aria brevi ma frequenti,
- evitare periodi prolungati di ricambio d'aria, poiché possono causare oscillazioni eccessive della temperatura,
- è obbligatorio adattare i parametri impostati al comportamento degli animali e alle condizioni presenti sia all'interno sia all'esterno del locale.

## Modalità di funzionamento del dispositivo
Il regolatore regola in modo continuo la ventilazione da **«Min.1» a «Max.1»** nell'intervallo compreso tra la **«Temperatura impostata»** e la somma della **«Temperatura impostata»** e della **«Banda di ventilazione del 1gr.»**. Al di sopra di questo intervallo viene attivato il gruppo di ventilazione 2, mentre il gruppo 1 passa al livello **«Min.2»**; con un ulteriore aumento della temperatura, la ventilazione aumenta fino a **«Max.2»**, al termine dell'intervallo della **«Banda di ventilazione del 2 gr.»**. Se la **«Banda di ventilazione del 2 gr.»** è impostata a zero e la ventilazione funziona al livello **«Max.1»**, si attiva il gruppo di ventilazione 2 e un ulteriore aumento della temperatura non comporta più alcuna variazione della ventilazione (parte tratteggiata del grafico). Se la temperatura nel locale scende al di sotto della **«Temperatura impostata»**, il regolatore effettua periodicamente il ricambio d'aria nel locale; in caso di ulteriore diminuzione, si attiva il riscaldamento supplementare. Tutto dipende dalle impostazioni inserite dall'utente. Il programma del regolatore prevede anche il collegamento a una centralina di allarme, che può essere attivata quando la temperatura nel porcile si discosta dai parametri impostati. 

![Ventilazione](./img/Sc-12wentyl.png)  

## Programmazione del regolatore
Il regolatore dispone di un insieme di impostazioni predefinite che vengono scritte nella memoria non volatile in due casi:
1. prima messa in servizio del dispositivo,
2. errore nella memoria dei dati.
In caso di assenza o interruzione dell'alimentazione, il regolatore non perde le impostazioni dell'utente precedentemente inserite e memorizzate.

## Pannello frontale – indicatori, pulsanti e display
![Pannello](./img/SC-12panel.png)  
    1. Spia rossa che segnala il superamento della temperatura massima consentita.
    2. Spia rossa che segnala il superamento della soglia minima di temperatura consentita.
    3. Spia gialla che segnala il riscaldamento supplementare.
    4. Spia gialla che segnala la ventilazione del gruppo 2.
    5. Spia verde che segnala l'impostazione manuale del livello di ventilazione.
    6. Spia verde che segnala il funzionamento della comunicazione RS485.
    7. Display del menu; in condizioni normali di funzionamento visualizza la temperatura.
    8. Indicatore a barre che segnala il livello di ventilazione.
    9. Tasto per spostarsi verso l'alto nel menu o modificare il valore del parametro.
    10. Tasto ESC - per uscire dal menu o dal parametro senza memorizzare il valore.
    11. Tasto OK - per accedere al menu o confermare (memorizzare) il parametro.
    12. Tasto per spostarsi verso il basso nel menu o modificare il valore del parametro.

## Uso del menu
Il regolatore è dotato di numerose funzioni che consentono di adattarlo all'applicazione specifica. Queste funzioni sono raggruppate in un menu, al quale si accede premendo uno dei tasti **(«+», «-» o «OK»)**. I tasti **«+»** e **«-»** servono a selezionare le funzioni, mentre la modifica, il salvataggio dei dati o l'accesso al livello successivo possono essere effettuati con il tasto **«OK»**. Premere il tasto **«Esc»** per tornare al menu superiore o annullare il salvataggio del parametro.

## Funzioni del menu di base

| MENU                          | Descrizione       | 
|:-----------                   |:---------- |
| Temperatura 20,8o C W16% A    | **Modalità informativa** - di funzionamento normale. Il display mostra la temperatura attuale e, quando il ventilatore è in funzione, il valore del livello di ventilazione. Significato dei simboli aggiuntivi:A-indica l'allarme attivo,D  - indica il riscaldamento attivo, W - indica la ventilazione supplementare| 
|   Temp. impostata   20,0o C      |**«Temperatura impostata»** – Definisce la temperatura a partire dalla quale inizia il processo di ventilazione a regolazione continua. Selezionare un valore adeguato in funzione del tipo di animali allevati.| 
| Ricambio d'aria     | **Ricambio d'aria** – vengono impostati due valori temporali.    1.**Tempo di funzionamento** Definisce il numero di minuti di funzionamento della ventilazione.    2.**Tempo di pausa** Definisce il numero di minuti di arresto della ventilazione tra i successivi cicli di funzionamento.    3.**Livello di ricambio d'aria** - Definisce l'intensità della ventilazione durante il ricambio d'aria.| 
| Allarme |  1.**Allarme attivo Sì** - Attivazione/Disattivazione del contatto di allarme; per impedire al regolatore di emettere un segnale di allarme sull'uscita (verso la centralina di allarme), selezionare «NO» nel menu.  2. **Temp. Min. 15,0o C** - Definisce la temperatura minima assoluta alla quale si attiva l'allarme.  3.**Temp. Max. 25,0o C** - Definisce la temperatura massima assoluta alla quale si attiva l'allarme.  4.**Segnale di allarme Sì** - Attivazione/Disattivazione del segnale acustico all'interno del regolatore. | 
|    Ventilazione        |  1.**Banda vent. 1 5,0o C**   - Definisce la velocità di risposta del regolatore (variazioni del livello di ventilazione dal minimo 1 al massimo 1) all'aumento della temperatura.  2.**Livello min. 1 1 %** - Definisce il livello di ventilazione corrispondente alla temperatura impostata.  3.**Livello max. 1 100 %**-Definisce il livello costante di ventilazione per una temperatura superiore all'intervallo di regolazione continua quando «Banda vent. 2gr.» = 0; in caso contrario, definisce il livello massimo della ventilazione regolata per una temperatura pari alla somma della T. impostata e della banda del gruppo 1.  4.**Banda vent. 2 0,0o C**-Definisce la velocità di risposta del regolatore (variazioni del livello di ventilazione dal minimo 2 al massimo 2) all'aumento della temperatura per il gruppo 2. La funzione è inattiva quando la banda è pari a zero.  5.**Livello min. 2 1 %**-Definisce il livello minimo di ventilazione del gruppo 1 nel punto di chiusura dei contatti del gruppo 2.  6.**Livello max. 2 100 %**-Definisce il livello costante di ventilazione per una temperatura superiore all'intervallo di regolazione continua quando il gruppo 2 è attivo.  7.**Gruppo 3  5,0o C**-Definisce il livello costante di ventilazione per una temperatura superiore all'intervallo di regolazione continua quando il gruppo 2 è attivo.  8.**Gruppo 4 7,0o C**-Definisce la temperatura, rispetto alla temperatura impostata, di attivazione del gruppo di ventilazione 4 (la funzione del meccanismo di sollevamento deve essere disattivata).| 
|    Riscaldamento supplementare  |  1.**Temp. risc. suppl. 15,0o C**-Definisce la temperatura di attivazione del riscaldamento supplementare.  2.**Banda risc. suppl. 5,0o C** -Definisce la proporzione della potenza dei sistemi di riscaldamento supplementare (sull'uscita V3 0-10V) in funzione della temperatura. | 

## Funzioni del menu avanzato
Il menu avanzato è destinato principalmente agli installatori e consente di adattare il regolatore all'impianto e al ventilatore, testare i circuiti e selezionare la lingua del menu. Per accedere alle impostazioni avanzate, premere e tenere premuti due tasti del menu per circa 10s. 

| MENU                          | Descrizione       | 
|:-----------                   |:---------- |
|Test  |Questa funzione serve a verificare i singoli circuiti di attuazione del regolatore; tutte le impostazioni sono temporanee e rimangono valide finché si resta nella relativa voce di menu. Dopo aver premuto «ESC» o «OK», l'uscita interessata ritorna allo stato determinato dal funzionamento del regolatore.  1.**Ventilazione 0 %**  Consente di inserire manualmente il livello di ventilazione per verificare il sistema di ventilazione. Dopo la conferma della funzione si accende la spia verde (mano).  2.**Allarme No** L'attivazione determina l'accensione di 2 spie rosse, l'emissione del segnale acustico e l'attivazione del circuito di allarme.  3.**Riscaldamento supplementare No** L'attivazione determina l'accensione della spia gialla (fiamma) e l'attivazione del circuito di riscaldamento supplementare.  4.**Vent. 2 stadio No** L'attivazione determina l'accensione della spia gialla (ventilatore) e l'attivazione del circuito del gruppo 2.  5.**Uscita V1 0,0 V  Uscita V2  0,0 V Uscita V3  0,0 V**-Test delle uscite 0-10V; mediante i tasti «+» o «-» è possibile impostare la tensione desiderata per i sistemi, nell'ordine: moduli di espansione, serrande di ingresso, riscaldamento supplementare a regolazione continua. La funzione è particolarmente utile per la calibrazione dell'Uscita V2 delle serrande di ingresso.  6.**Meccanismo di sollevamento 0** Consente di verificare il sistema di serrande di ingresso: «+» - apre le prese, «-» - chiude le prese; il display mostra la posizione attuale dell'attuatore rilevata dal potenziometro.  7.**Gruppo 3 No**  L'attivazione determina l'attivazione del circuito del gruppo di ventilazione 3. (la funzione del meccanismo di sollevamento deve essere disattivata)  8.**Gruppo 4 No**  L'attivazione determina l'attivazione del circuito del gruppo di ventilazione 4. (la funzione del meccanismo di sollevamento deve essere disattivata)|
|Lingua        | Selezione della lingua del menu. È possibile scegliere tra polacco e inglese. | 
|Ventilatore         |  1.**Banda vietata 0**- Calibrazione della velocità minima di rotazione dei ventilatori collegati direttamente al regolatore; questo parametro corrisponde al livello di ventilazione «1%». Un valore positivo del parametro aumenta la velocità di rotazione, uno negativo la diminuisce.  2.**Modulo esp. Min. 1,9 V** -Tensione minima fornita al modulo di espansione della potenza (uscita V1 0-10V).  3.**Modulo esp. Max. 10,0 V** -Tensione massima fornita al modulo di espansione della potenza (uscita V1 0-10V).  4.**Disinserimento modulo No** - Disinserimento del modulo di espansione della potenza; se si seleziona «SÌ», la tensione sull'uscita di comando dei moduli di espansione (V1 0-10V) scende al livello 0V anziché al valore minimo impostato quando il livello di ventilazione è pari a 0%.  5.**Inversione  No**-L'attivazione inverte la caratteristica dell'uscita V1. La tensione diminuisce all'aumentare del livello di ventilazione nell'intervallo impostato da min. a max. Il segnale sull'uscita V1 è di tipo 10-0V.| 
| Serrande di ingresso       |  1.**Anticipo 0,0o C**-Apertura anticipata delle serrande di ingresso. Il parametro impostato definisce di quanto, in termini di temperatura, le serrande di ingresso devono aprirsi prima della «Temperatura impostata».  2.**Chiusura completa  No**- L'attivazione fa sì che la tensione sull'uscita di comando delle serrande di ingresso (V2 0-10V) scenda al livello 0V anziché al valore minimo impostato. In caso di assenza di ventilazione (livello di ventilazione 0%).  3.**Serrande min.  1,9 V**- Tensione minima fornita alle serrande di ingresso (uscita V2 0-10V).  4.**Serrande max.  10,0 V**- Tensione massima fornita alle serrande di ingresso (uscita V2 0-10V).  5.**Inversione   No**-L'attivazione inverte la caratteristica dell'uscita V2. La tensione diminuisce all'aumentare del livello di ventilazione nell'intervallo impostato da min. a max. Il segnale sull'uscita V2 è di tipo 10-0V. |  
| Misurazione della temperatura  |  1.**Calibrazione S1 23,0o C -> 23,5o C**,**Calibrazione S2 23,0o C -> 23,2o C** - La calibrazione degli ingressi analogici consente di riscalare la temperatura rilevata dai sensori S1 e S2.  2.**Tempo di media 60 s**- Questo parametro definisce il periodo di tempo durante il quale viene calcolata la media delle letture correnti della temperatura. Il valore medio della temperatura è il parametro fondamentale delle funzioni del regolatore. Le variazioni dello stato delle uscite (ventilazione, riscaldamento supplementare, serrande, gruppi successivi di ventilazione, allarmi,...) sono strettamente correlate a questo parametro e non possono verificarsi con una frequenza superiore a quella determinata dal tempo qui impostato. | 
| Meccanismo di sollevamento      |  1.**Calibrazione apert. 1024 -> 853**,**Calibrazione chius. 0 -> 324** -La calibrazione del meccanismo di sollevamento è indispensabile per il corretto funzionamento del sistema di prese d'aria. Il tasto «+» apre le prese, il tasto «-» le chiude. Durante l'apertura delle prese, il parametro di posizione deve aumentare, durante la chiusura deve diminuire; in caso contrario, verificare il collegamento dell'attuatore (alimentazione e potenziometro). Nella calibrazione dell'apertura, aprire le prese al massimo e confermare la posizione con il tasto «OK». Nella calibrazione della chiusura, chiudere le prese e confermare la posizione con il tasto «OK». Il tasto «ESC» consente di uscire dalla funzione senza salvare. La differenza tra la posizione di apertura e quella di chiusura deve essere di almeno 100 unità.  2.**Disattivazione No**-La disattivazione libera i contatti FUNC1 e FUNC2 dal comando del meccanismo di sollevamento; tali contatti svolgono quindi la funzione di ventilazione dei gruppi 3 e 4.| 
| Avviamento graduale               | I parametri di questo gruppo di menu gestiscono l'avviamento della ventilazione. L'attivazione della ventilazione nel gruppo a regolazione continua è preceduta da un avviamento graduale fino a 100%, da un breve funzionamento a 100%  e dalla riduzione al livello di ventilazione richiesto. In questo modo, all'avvio della ventilazione si genera un soffio d'aria che facilita l'apertura delle valvole a farfalla nei camini.   I valori sono espressi in periodi della tensione di alimentazione a 1% di ventilazione.  1.**Tempo di accelerazione 5**- Il parametro definisce la velocità di aumento del regime di rotazione della ventilazione dal livello zero al massimo – avviamento graduale dei ventilatori. Il valore 0 disattiva l'accelerazione graduale.  2.**Tempo 100%   100**- Il parametro definisce il tempo di funzionamento all'avvio al livello di ventilazione 100%. L'impostazione del tempo di accelerazione e di 100% a 0 disattiva completamente il soffio d'aria all'avvio della ventilazione.  3.**Tempo di decelerazione 5**-  Il parametro definisce la velocità di variazione del livello di ventilazione. | 
|Riscaldamento supplementare              |  1.**Inversione contatto No**-L'attivazione inverte la caratteristica dell'uscita HOT. Il contatto viene  aperto al diminuire della temperatura misurata.  2.**Isteresi  0,5o C** - Definisce il livello di isteresi della temperatura per il contatto del riscaldamento supplementare.  3.**Funzionamento relativo No**-L'attivazione consente di impostare la temperatura del riscaldamento supplementare relativamente alla temperatura impostata. Il menu di base del riscaldamento supplementare viene modificato e vi si inserisce la differenza rispetto alla temperatura impostata.  4.**Riscaldamento suppl. min. 1,9 V** - Tensione minima fornita al comando continuo del riscaldamento – aerotermo con portata del ventilatore variabile (uscita V3 0-10V).  5.**Riscaldamento suppl. max. 10,0 V** - Tensione massima fornita al comando continuo del riscaldamento – aerotermo con portata del ventilatore variabile (uscita V3 0-10V).| 
| Programma 	|  **ver. 2.4  Apr 13 2018** - 	Lettura della versione del software e della data di compilazione|

## Messaggi di errore e avvertimento

I messaggi di errore servono a informare l'utente delle anomalie nel funzionamento del regolatore. Di seguito sono riportati i possibili messaggi di errore

|ERRORE                            |	DESCRIZIONE      |
|:-----------                    |:---------- |
|Allarme     Sovraccarico 	     |Allarme di sovraccarico, attivato a 75°C. Il dispositivo interrompe il funzionamento fino al raffreddamento.|
|Allarme  Sensore assente|Segnala l'assenza o il danneggiamento del sensore o del cavo di collegamento.|

# Note e avvertenze 
:::danger 
 Durante l'installazione del dispositivo è obbligatorio scollegare l'alimentazione elettrica, poiché la tensione presente su alcuni componenti è pericolosa per la vita e la salute. Si raccomanda di affidare l'installazione a una persona qualificata.

:::
- Per evitare problemi nell'utilizzo del dispositivo, è necessario leggere le istruzioni prima di procedere all'installazione e all'uso.
- È vietato intervenire sulla struttura del dispositivo o eseguire autonomamente riparazioni. Ciò riguarda in particolare le modifiche di elementi e componenti. 
- Le operazioni di manutenzione o assistenza devono essere eseguite da personale autorizzato (installatore o servizio di assistenza del produttore). Negli edifici zootecnici con ventilazione forzata è obbligatorio un sistema di allarme. Il produttore del dispositivo non risponde dei danni causati da un'installazione errata, da una programmazione errata delle funzioni, dalle conseguenze di eventi fortuiti e da fattori esterni. 
- Il regolatore di ventilazione richiede l'impostazione dei parametri in conformità alle condizioni presenti nel locale di allevamento. Queste impostazioni sono individuali e dipendono dalle decisioni dell'allevatore. Il produttore del dispositivo si riserva il diritto di apportare modifiche alla struttura del dispositivo e al software.

:::caution
<div class="warning-container">
  <p>
    <strong></strong> Al termine dell'utilizzo, il prodotto non deve essere smaltito insieme ai rifiuti urbani indifferenziati, ma deve essere smaltito conformemente alle normative vigenti (direttive WEEE dell'Unione Europea 2012/19/UE).
Il prodotto è stato realizzato conformemente ai requisiti RoHS (direttiva dell'Unione Europea 2011/65/UE).
  </p>
</div>
:::
:::tip

## Dati tecnici del regolatore
|Parametro                        |	DESCRIZIONE      |
|:-----------                    |:---------- |
|Tensione di alimentazione|	230VAC 50Hz|
|Corrente massima dell'uscita a regolazione continua FAN|	12A|
|Intervallo di regolazione della tensione di uscita|	70V ÷ 230V|
|Corrente massima dell'uscita (contatto) FAN 2|	6A|
|Corrente massima dell'uscita (contatto) HOT|	6A|
|Corrente massima dell'uscita (contatto) ALARM|	4A|
|Corrente massima dell'uscita (contatto) FUNC1 e FUNC2|	4A|
|Intervallo di temperatura di funzionamento|	-10 +40oC|
|Intervallo di misurazione della temperatura|	0 +50oC|
|Risoluzione della misurazione della temperatura|	0,1oC|
|Rilevamento dei guasti del sensore di temperatura|	SÌ|
|Numero massimo di sensori analogici|	2|
|Accuratezza della misurazione della temperatura – ingresso analogico|	1oC|
|Dipendenza della misurazione dalla resistenza dei cavi – ingresso analogico|	15,8Ω/oC|
|Numero massimo di sensori digitali|	4|
|Accuratezza della misurazione della temperatura – ingresso digitale|	0,5oC|
|Dipendenza della misurazione dalla resistenza dei cavi – ingresso digitale|	Nessuna|
|Lunghezza massima della linea di collegamento dei sensori digitali|	150m|
|Resistenza alle sovratensioni (max E)|	210J|
|Protezione da sovraccarico|	75oC|
|Dimensioni del dispositivo|	34x29x12 [cm]|
|Grado di protezione dell'involucro|	IP56|
:::

:::info
Il regolatore SPEED CONTROL-12 v2  comprende nella dotazione:
 - 1 sensore di temperatura,
 - 4 tasselli a espansione,
 - 2 pressacavi PG13,5.
 - 3 pressacavi PG11,
 - 4 pressacavi PG9.
:::















































































