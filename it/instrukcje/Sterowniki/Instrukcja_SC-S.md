---
sidebar_position: 2
title: Istruzioni SC-S
description: Regolatore climatico per locali zootecnici con corrente di uscita ammessa
  fino a 5A
keywords:
- eletor sc-s
- regolatore di ventilazione
- regolatore climatico
- regolatore di ventilazione del porcile
- regolatore del microclima
- regolatore per porcili
- ventilazione del porcile
- regolatore per locali di accrescimento
---


# Regolatore SC-S

Regolatore climatico a microprocessore appartenente alla famiglia SPEED CONTROL. Regolatore affidabile, semplice da installare e utilizzare, con software in polacco, inglese, russo e tedesco. Il programma del regolatore consente di impostare in modo intuitivo i parametri: temperature, ricambio d'aria, riscaldamento integrativo, livelli min./max. di ventilazione e allarmi.

**Parametri e caratteristiche:**  
- Ventilazione del gruppo I:
  - corrente max. dell'uscita a regolazione continua 6A,
  - protezione termica del circuito,
  - avviamento graduale della ventilazione,
  - calibrazione della velocità minima di rotazione
- Ventilazione del gruppo II, contatto isolato fino a 3A (1 opzionale)
- Riscaldamento integrativo, contatto isolato fino a 3A (1 opzionale)
- Uscite di allarme NO e NC:
  - segnalazione della mancanza di alimentazione,
  - segnalazione del superamento della soglia di temperatura min. o max.
- 1 ingresso analogico per la misurazione della temperatura
- 2 uscite 0-10V
- Potenza assorbita dal circuito < 3W
- Involucro ermetico IP56
- Tensione di alimentazione 230VAC 50Hz

## Installazione del regolatore  
:::danger 
Durante l'installazione del dispositivo è obbligatorio scollegare l'alimentazione elettrica, poiché la tensione presente su alcuni componenti è pericolosa per la vita e la salute.  
Si raccomanda di affidare l'installazione a una persona qualificata.
:::

### Scelta del luogo di montaggio  

Il luogo di montaggio deve essere scelto in modo razionale, tenendo conto della facilità di accesso al dispositivo per le persone autorizzate e dell'inaccessibilità per animali e bambini. Occorre considerare anche le condizioni climatiche, ossia il dispositivo deve funzionare nell'intervallo di temperatura da -10°C a 40°C, in un luogo non esposto alla luce solare diretta. Attorno al dispositivo deve essere garantita la libera circolazione dell'aria. Il dispositivo comprende un sensore di temperatura. Per il montaggio del sensore di temperatura valgono alcune regole:  
- il sensore non deve essere montato in un luogo privo di circolazione dell'aria o esposto alla luce solare diretta
- il sensore non deve essere montato sulla parete portante (esterna) dell'edificio,
- evitare la vicinanza a dispositivi che emettono calore, quali radiatori e lampade,
- non collocare il sensore direttamente accanto a porte e aperture di ventilazione,
- non collocare il sensore in luoghi accessibili agli animali,
- si raccomanda di posare il cavo di collegamento del sensore lontano dai cavi di alimentazione.

### Montaggio  

Il dispositivo può funzionare in condizioni climatiche difficili. Il regolatore e il sensore di temperatura, se montati correttamente, sono resistenti agli effetti dell'ambiente.
Durante il montaggio occorre prestare attenzione ai seguenti aspetti:  
- prima di avvitare, verificare la guarnizione del coperchio,
- il coperchio deve essere serrato con tutte le viti,
- i cavi utilizzati per il collegamento del regolatore devono essere tondi,
- dopo aver collegato il cavo, serrare i pressacavi in modo da garantire la tenuta e l'immobilizzazione del cavo; si raccomanda l'uso di silicone,
- i passaggi non utilizzati (pressacavi) devono essere chiusi con tappi,
- fissare il regolatore (la parte inferiore dell'involucro) a una parete piana con 4 tasselli a espansione.

## Collegamento elettrico  

:::danger 
Prima di collegare il circuito, accertarsi che l'alimentazione sia disinserita!
:::

Prima di procedere al collegamento del regolatore, svitare e rimuovere il coperchio. Inserire i cavi attraverso i pressacavi in gomma, quindi procedere al loro collegamento. I morsetti del regolatore sono illustrati nella figura seguente.

![Collegamento](./img/Sc-s2.png)

**Collegare il connettore AC 230V** all'alimentazione (quadro di distribuzione). È obbligatorio utilizzare un interruttore magnetotermico 1P-B6 e scaricatori di sovratensione di tipo T1 T2. Quando si collegano più dispositivi, è buona prassi raggruppare i regolatori su diverse «fasi» (L1, L2, L3), al fine di distribuire uniformemente il carico sulla linea di alimentazione.  
**Il connettore FAN** deve essere collegato direttamente al ventilatore; in caso di comando di più ventilatori, il carico complessivo non deve superare 6A e ciascun ventilatore deve essere protetto separatamente. Non prelevare PE e N dall'alimentazione (quadro di distribuzione); è obbligatorio collegarli ai terminali del regolatore.  
**Connettore FUNCTION** uscita a relè isolata, la corrente massima del contatto è 6A (è richiesto un interruttore magnetotermico esterno 1P-B6 in caso di comando diretto del carico),
può essere utilizzata come:  
- **Riscaldamento integrativo** – il contatto si chiude quando la temperatura misurata scende al di sotto del valore impostato.  
- **Ventilazione del gruppo 2 o di sistemi di nebulizzazione** – il contatto si chiude quando la temperatura misurata è superiore alla somma della temperatura impostata e della banda di ventilazione.  il contatto si chiude quando la temperatura misurata è superiore alla somma della temperatura impostata e della banda di ventilazione.  

La figura seguente illustra il collegamento del ventilatore del gruppo 2 o del riscaldatore.  

![Secondo gruppo](./img/2grupa.png)

**Il connettore ALARM** comprende le uscite isolate NC, C e NO per il collegamento alla centrale di allarme. L'allarme si attiva nei seguenti casi:  
- la temperatura è troppo bassa o troppo alta,
- il regolatore o il sensore di temperatura è danneggiato,
- è venuta a mancare la tensione di alimentazione del regolatore;
- si è verificato un funzionamento anomalo del regolatore (ad es. surriscaldamento del regolatore)  

![Allarme](./img/alarmsc-s.png)  

**Il connettore V1 0-10V** serve per collegare moduli di espansione della potenza o ventilatori con circuito integrato di regolazione della velocità. La tensione su questo morsetto è proporzionale al livello di ventilazione.  
**Il connettore V2 0-10V** serve per collegare l'attuatore che apre le serrande di ingresso dell'aria.  
**Collegare il connettore SENSOR** al sensore di temperatura 1 TS3 o TS5; la polarità non è rilevante.  È buona prassi mantenere i cavi di misura lontani dai cavi di alimentazione.  
**Il connettore RS-485** può essere utilizzato per realizzare sistemi di ventilazione e per comunicare con un PC.  

## Principio di funzionamento  

Il compito principale del regolatore è mantenere la temperatura nel locale di allevamento al livello stabilito dall'allevatore. Occorre ricordare che il regolatore è soltanto uno strumento che contribuisce a garantire condizioni climatiche ottimali nel locale di allevamento. Il ruolo principale in questo processo spetta tuttavia all'allevatore, che deve adeguare le impostazioni del dispositivo alle variazioni delle condizioni climatiche esterne e, soprattutto, alle esigenze degli animali presenti nell'edificio zootecnico, nonché monitorare lo stato di funzionamento del dispositivo tramite la centrale di allarme.  

### Prima messa in servizio del regolatore  

:::danger
Alla prima messa in servizio del regolatore è obbligatorio impostare la banda di funzionamento vietata del motore.
:::

Il regolatore funziona con ventilatori basati su un motore asincrono monofase con assorbimento massimo complessivo di corrente pari a 5A. Dopo aver collegato i ventilatori scelti, l'utente deve adattarli al funzionamento con il regolatore. In altre parole, è necessario impostare il livello minimo di funzionamento (velocità di rotazione) del ventilatore. Questa funzione è denominata **«Banda vietata»** e viene impostata dall'utente una sola volta tramite le **«Impostazioni avanzate»**. Per eseguire correttamente questa operazione, è consigliabile l'aiuto di una seconda persona, che possa osservare costantemente il comportamento del ventilatore mentre l'altra persona imposta il valore della **«Banda vietata»**. La mancata impostazione della banda vietata può causare un funzionamento anomalo del dispositivo. Il valore della **«Banda vietata»** può essere considerato corretto quando la pressione generata dal ventilatore inizia a sollevare leggermente le serrande del camino di ventilazione. L'impostazione della **«Banda vietata»** deve essere ripetuta quando viene sostituito il ventilatore collegato al regolatore.  

### Ricambio d'aria periodico  

Il ricambio d'aria è una funzione eseguita dal regolatore, che si avvia quando la temperatura nel locale scende al di sotto della temperatura impostata. Questa funzione garantisce agli animali un apporto ciclico di aria fresca. Il ricambio d'aria è definito da 3 parametri:
- **«Tempo di funzionamento»** - definisce per quanti secondi deve essere attivato il ventilatore,
- **«Tempo di pausa»** - definisce il tempo di arresto del ventilatore in secondi,
- **«Livello di ricambio d'aria»** - definisce la potenza di ventilazione durante il «Tempo di funzionamento».  

L'impostazione esemplificativa **60s/120s** significa che il ventilatore viene attivato per 60s con una pausa tra le attivazioni successive di 120s. 

Tutti i parametri sopra elencati sono impostati dall'utente. Durante l'impostazione dei parametri di ricambio d'aria, occorre ricordare alcune regole:
- il ricambio d'aria si attiva esclusivamente quando la temperatura nel porcile scende al di sotto della temperatura impostata,
- la funzione principale del ricambio d'aria è garantire agli animali un apporto ciclico di aria fresca, non mantenere la temperatura impostata nel locale,
- si raccomanda di effettuare il ricambio d'aria nei locali per periodi brevi ma frequenti,
- evitare periodi prolungati di ricambio d'aria, poiché possono causare oscillazioni eccessive della temperatura,
- è obbligatorio adattare i parametri impostati al comportamento degli animali e alle condizioni presenti sia all'interno sia all'esterno del locale,
- è possibile disattivare la funzione di ricambio d'aria; in questo caso, sia nella modalità percentuale sia in quella temporizzata, impostare valori pari a zero nel campo corrispondente al tempo di ricambio d'aria, ad es.: 0/120s  

### Ventilazione a regolazione continua  

Il regolatore regola in modo continuo la ventilazione dalla «Velocità minima» alla **«Velocità massima»** nell'intervallo compreso tra la **«Temperatura impostata»** e la somma della **«Temperatura impostata»** e della **«Banda di ventilazione»**. Al di sopra di questo intervallo viene attivato il gruppo 2 di ventilazione.  

![ventilazione](./img/wentylacjia.png)  

Al di sopra di questo intervallo viene attivato il gruppo 2 di ventilazione, Quando la temperatura nel locale scende al di sotto della **«Temperatura impostata»**, il regolatore effettua periodicamente il ricambio d'aria nel locale; in caso di ulteriore diminuzione viene attivato il riscaldamento integrativo. Tutto dipende dalle impostazioni inserite dall'utente. Il programma del regolatore prevede anche il funzionamento con una centrale di allarme, che può essere attivata quando la temperatura nel porcile si discosta dai parametri impostati.  

## Programmazione del regolatore  

Il regolatore dispone di un insieme di impostazioni predefinite che vengono scritte nella memoria non volatile in due casi:  
1. Prima messa in servizio del dispositivo,  
2. Errore nella memoria dati.  
In caso di assenza o interruzione dell'alimentazione, il regolatore non perde le impostazioni dell'utente precedentemente inserite e salvate.  

### Utilizzo del menu  

Il regolatore è dotato di numerose funzioni che consentono di adattarlo a una determinata applicazione. Queste funzioni sono raggruppate in un menu, al quale si accede premendo uno dei tasti **(« Freccia destra», «Freccia sinistra»)**. I parametri si modificano mediante i tasti **«+» e «-»**; il parametro modificato viene salvato automaticamente nella memoria non volatile dopo **30s** dall'ultima pressione di un tasto.  

### Funzioni del menu di base  

| MENU                       | Descrizione | 
|:---:                       |:---|
|Temperatura  <br />20,8°C W16% A  |**«Modalità informativa»** - di funzionamento normale. Il display mostra la temperatura attuale e, quando il ventilatore è in funzione, il valore del livello di ventilazione. Significato dei simboli aggiuntivi: A-indica l'allarme attivo, D  - indica il riscaldamento attivo, W - indica la ventilazione aggiuntiva| 
|Temp. impostata  <br />20,0°C        |**«Temperatura impostata»** – valore di temperatura che definisce l'inizio del processo di ventilazione a regolazione continua.   | 
|Ricambio d'aria  <br />20s / 200s  |**«Ricambio d'aria»** – vengono impostati due valori temporali 1 «Tempo di funzionamento», 2 «Tempo di pausa» tra le successive attivazioni cicliche della ventilazione.| 
|Livello ricambio aria  <br />20%        |**«Livello di ricambio d'aria»** - livello di ventilazione durante il funzionamento del ricambio d'aria   | 
|Allarme minimo  <br />12,0°C       |**«Allarme minimo»** - definisce la temperatura minima assoluta alla quale viene attivato l'allarme. 
|Allarme massimo  <br />28,0°C       |**"Allarme massimo"** - definisce la temperatura massima assoluta alla quale viene attivato l'allarme.  | 
|Riscaldamento integrativo  <br />12,0°C         |A seconda della configurazione vengono eseguite le funzioni: **«Riscaldamento integrativo»** - il contatto si chiude se la temperatura scende al di sotto del valore indicato. | 
|Ventilazione stadio 2  <br />25,0  |**«Ventilazione stadio 2»** - il contatto si chiude quando la temperatura misurata supera la somma della temperatura impostata e della banda di ventilazione. | 
|Banda di ventilazione  <br />5,0°C     |**«Banda di ventilazione»** - definisce la rapidità di risposta del regolatore (variazione del livello di ventilazione dal minimo 1 al massimo 1) all'aumento della temperatura. | 
|Velocità minima  <br />1%        |**«Velocità minima»** – è lo stato in cui il dispositivo rimane per un tempo indefinito, fornendo all'uscita una tensione del valore impostato. Serve per calibrare il dispositivo con il motore e il meccanismo delle serrande.   | 
|Velocità massima  <br />100%      |**«Velocità massima»** – è lo stato in cui il dispositivo rimane per un tempo indefinito, fornendo all'uscita una tensione del valore impostato. Serve per limitare la potenza destinata alla ventilazione| 

### Menu avanzato  

Il menu avanzato è destinato principalmente agli installatori e consente di adattare il regolatore all'impianto e al ventilatore. Si accede alle impostazioni avanzate tenendo premuti i due tasti del menu per circa 10s.  

| MENU                                 | Descrizione| 
|:---:                                 |:--- |
|Impostazioni  <br />avanzate assenti   |Questo messaggio indica che il regolatore non è stato calibrato con la ventilazione e il suo funzionamento potrebbe essere anomalo È necessario accedere al menu avanzato e impostare la «Banda vietata».|
|Impostazioni <br />avanzate         |Segnalazione dell'accesso alle impostazioni avanzate. | 
|Software Ver:  <br />1907       |Informazioni sulla versione del software.| 
|Banda vietata  <br />1000 us       |Calibrazione della velocità minima di rotazione dei ventilatori collegati direttamente al regolatore; questo parametro corrisponde al livello di ventilazione «1%»|  
|Funzione contatti  <br />Riscaldamento integrativo     |Selezione della funzione dei contatti:  <br />• Riscaldamento integrativo (predefinito)<br />• Gruppo 2 di ventilazione | 
|Ricambio d'aria  <br />Temporizzato         |Selezione del tipo di ricambio d'aria: <br />• Temporizzato (predefinito) <br />• Percentuale| 
|Intervallo V1  <br />da 2,0 a 10,0       |Regolazione dell'intervallo di variazione della tensione sull'uscita V1 0÷10V. Le impostazioni riguardano il valore minimo e massimo della tensione. La regolazione viene utilizzata per adattare il regolatore all'espansione di potenza o all'inverter.| 
|Inversione V1  <br />No                |L'attivazione inverte la caratteristica dell'uscita V1. La tensione diminuisce all'aumentare del livello di ventilazione nell'intervallo definito dai valori min.-max. Il segnale sull'uscita V1 sarà di tipo 10-0V.| 
|Disinserimento V1  <br />No                |L'attivazione fa sì che sull'uscita  V1 0-10V venga fornito il livello 0V anziché il valore minimo impostato, quando il livello di ventilazione è pari a 0%.| 
|Intervallo V2  <br />da 2,0 a 10,0       |Regolazione dell'intervallo di variazione della tensione sull'uscita V2 0÷10V. Le impostazioni riguardano il valore minimo e massimo della tensione. La regolazione viene utilizzata per calibrare il sistema delle serrande.|
|Inversione V2  <br />No      	       |L'attivazione inverte la caratteristica dell'uscita V2. La tensione diminuisce all'aumentare del livello di ventilazione nell'intervallo definito dai valori min.-max. Il segnale sull'uscita V2 sarà di tipo 10-0V.|
|Calibrazione temp  <br />21,0°C -> 22,0°C|La calibrazione del sensore di temperatura consente di riscalare il valore letto.|
|Avviamento graduale  <br />50%      	           |Definizione del livello di ventilazione a ogni avviamento del ventilatore; il ventilatore viene accelerato fino al valore indicato, dopodiché passa al livello impostato.| 
|Lingua  <br />Polacco    	           |Selezione della lingua del menu: polacco, inglese, tedesco, russo|
|Uscita                               |Uscita dal menu avanzato mediante il tasto «+»; le modifiche apportate vengono salvate nella memoria non volatile.|

### Messaggi di errore e avvertimento  

I messaggi di errore informano l'utente delle anomalie nel funzionamento del regolatore. Di seguito sono riportati i possibili messaggi di errore.  

|ERRORE                                    | DESCRIZIONE |
|:---:                                   |:--- |
|Allarme  <br />sovraccarico 	         |Allarme di sovraccarico, attivato a 75°C. Il dispositivo sospende il funzionamento fino al raffreddamento.|
|SENSORE A CIRCUITO APERTO!  <br />Controllare il sensore|Sensore a circuito aperto, segnala un guasto del sensore o del cavo di collegamento.|
|SENSORE IN CORTOCIRCUITO!  <br />Controllare il sensore  |Sensore in cortocircuito, segnala un guasto del sensore o del cavo di collegamento.|
|Mancanza  <br />di alimentazione                  |Mancanza di alimentazione, tensione di alimentazione troppo bassa, frequenza errata o tensione di alimentazione fortemente distorta.| 

## Note e avvertenze  

:::danger 
Durante l'installazione del dispositivo è obbligatorio scollegare l'alimentazione elettrica, poiché la tensione presente su alcuni componenti è pericolosa per la vita e la salute. Si raccomanda di affidare l'installazione a una persona qualificata.
:::

- Per evitare problemi durante il funzionamento del dispositivo, è necessario leggere le istruzioni prima di procedere all'installazione e all'utilizzo.  
- È vietato intervenire sulla struttura o effettuare riparazioni autonomamente. Ciò riguarda in particolare le modifiche a elementi e componenti.  
- Le operazioni di manutenzione o assistenza devono essere eseguite da personale autorizzato (installatore o servizio di assistenza del produttore). Negli edifici zootecnici con ventilazione forzata è obbligatorio un sistema di allarme. Il produttore del dispositivo non risponde dei danni causati da installazione non corretta, programmazione non corretta delle funzioni, conseguenze di eventi fortuiti e fattori esterni.  
- Il regolatore di ventilazione richiede l'impostazione dei parametri in base alle condizioni presenti nel locale di allevamento. Tali impostazioni sono individuali e dipendono dalle decisioni dell'allevatore. Il produttore del dispositivo si riserva il diritto di apportare modifiche alla struttura del dispositivo e al software.  


:::caution
![alt](./img/trash.svg) Al termine dell'utilizzo, il prodotto non deve essere gettato insieme ai rifiuti urbani non differenziati, ma deve essere smaltito conformemente alle disposizioni vigenti (direttive WEEE dell'Unione Europea 2012/19/UE). <br />Il prodotto è stato realizzato conformemente ai requisiti RoHS (direttiva dell'Unione Europea 2011/65/UE).
:::

<!-- \newpage -->
## Dati tecnici del regolatore  

|Parametro                        |	DESCRIZIONE      |
|:-----------                    |:---------- |
|Tensione di alimentazione|	230VAC 50Hz|
|Corrente massima dell'uscita a regolazione continua FAN|	6A|
|Intervallo di regolazione della tensione di uscita|	70V ÷ (Uz-5)V|
|Corrente massima dell'uscita (contatto) ALARM|	3A|
|Corrente massima dell'uscita (contatto) FUNCTION|	3A|
|Intervallo di temperatura di funzionamento|	-20 +40oC|
|Intervallo di misurazione della temperatura|	0 +50°C|
|Risoluzione della misurazione della temperatura|	0,1°C|
|Rilevamento dei guasti del sensore di temperatura|	SÌ|
|Numero massimo di sensori analogici|	1|
|Accuratezza della misurazione della temperatura – ingresso analogico|	1°C|
|Dipendenza della misurazione dalla resistenza dei cavi – ingresso analogico|	15,8Ω/°C|
|Resistenza alle sovratensioni (max E)|	210J|
|Protezione da sovraccarico|	75°C|
|Dimensioni del dispositivo|	20x15x8 [cm]|
|Grado di protezione dell'involucro|	IP56|
  


:::info
Il regolatore SPEED CONTROL SERVOMOTOR comprende nella dotazione:
- 1 sensore di temperatura + accessori,
- 4 tasselli a espansione,
- 1 fusibile 10A.
:::

