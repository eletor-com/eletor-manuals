---
sidebar_position: 4
title: Istruzioni Alimentatore DC50W24VB
description: Alimentatore DC50W24VB  di emergenza per il sistema di prese d'aria.
keywords:
- eletor IC-AC
- controllore delle prese d'aria
- controllore climatico
- controllore di ventilazione della porcilaia
- controllore del microclima
- controllore per porcilaie
- ventilazione della porcilaia
- controllore per locali di accrescimento
---


# Alimentatore DC50W24VB

Alimentatore di emergenza con funzione di apertura automatica e manuale delle prese e delle uscite dell'aria. Utilizzato per garantire la sicurezza degli animali da allevamento in caso di interruzione dell'alimentazione o guasto del controllore. Quando rileva un'anomalia, il dispositivo segnala un allarme e apre i sollevatori al livello impostato.

## Parametri e caratteristiche: 
-  Selettore della modalità di funzionamento: 
    - MANUAL
    - AUTO.
-  Manopola del grado di apertura delle prese d'aria.
-  Standard supportati:
    - 0-10, 2-10, 10-0, 10-2.
-  Possibilità di inversione del segnale di comando.
-  Uscite di allarme NO e NC.
-  Segnalazione dell'interruzione dell'alimentazione.
-  Monitoraggio della tensione di comando 2-10V.
-  Monitoraggio dei cortocircuiti sulle uscite 24VDC.
-  Monitoraggio dei cortocircuiti sulle uscite 0-10V.
-  2 ingresso 0-10V.
-  2 uscite 0-10V.
-  Protezioni elettroniche degli ingressi, delle uscite e della linea 24V.
-  Batteria di accumulatori 24V 4.0 Ah.
-  Involucro ermetico IP65.
-  Tensione di alimentazione 85~264VAC 47~63Hz.

# Installazione del controllore  
:::danger 
Durante l'installazione del dispositivo, l'alimentazione elettrica deve essere tassativamente scollegata, poiché la tensione presente su alcuni componenti è pericolosa per la vita e la salute. Si raccomanda di affidare l'installazione a una persona qualificata.
:::

## Scelta del luogo di montaggio  

Il luogo di montaggio deve essere scelto in modo razionale, tenendo conto della facilità di accesso al dispositivo per le persone autorizzate e dell'inaccessibilità per animali e bambini. Occorre considerare anche le condizioni climatiche, ossia il dispositivo deve funzionare nell'intervallo di temperatura da -10°C a 40 °C, in un luogo non esposto alla luce solare. Intorno al dispositivo deve essere garantita la libera circolazione dell'aria.

# Montaggio  

Il dispositivo può funzionare in condizioni climatiche aggressive. Se montato correttamente, il dispositivo è resistente agli effetti nocivi dell'ambiente.

### Durante il montaggio occorre prestare attenzione ai seguenti aspetti: 
 - il coperchio deve essere serrato con tutte le viti,
 - i cavi utilizzati per collegare il dispositivo devono avere una sezione circolare,
 - dopo aver collegato il cavo, serrare i pressacavi in modo da garantire la tenuta e l'immobilizzazione del cavo; si raccomanda l'uso di silicone,
 - i passaggi non utilizzati (pressacavi) devono essere chiusi con tappi,
 - fissare la parte inferiore dell'involucro a una parete piana con 4 tasselli a espansione.


# Collegamento elettrico  

:::danger 
Prima di collegare il sistema, assicurarsi che l'alimentazione sia disinserita!
:::

Dopo aver svitato il dispositivo, rimuovere il pannello anteriore. A tal fine, estrarre il cavo piatto dal connettore contrassegnato come P1. Introdurre i cavi attraverso i pressacavi in gomma e procedere al loro collegamento. Eseguire il collegamento secondo la descrizione.

![Collegamento](./img/DC50W24VB.png)

**Alimentazione 230V AC:** collegare all'alimentazione (quadro di distribuzione). È obbligatorio utilizzare un interruttore magnetotermico (tipo «S» B6) e limitatori di sovratensione di classe «C». Il dispositivo può essere alimentato in un ampio intervallo di tensioni da 85V a 264V e di frequenze da 47 a 63Hz, senza influire sul suo funzionamento.  

**Connettore In1 e In2** collegare al controllore per fornire il segnale di comando ai sistemi di sollevatori. Il dispositivo può supportare due controllori oppure un singolo controllore con sezioni separate per le prese e le uscite dell'aria (i morsetti I1 e I2 devono essere ponticellati).  

**Connettore ALARM** collegare alla centralina di allarme, a seconda del sistema – chiuso (NO e C), aperto (NC e C). L'allarme si attiva nei seguenti casi:  •interruzione della tensione di alimentazione del dispositivo,  •assenza del segnale di comando 2-10V su almeno uno degli ingressi,  •cortocircuito del segnale di uscita o valore diverso da quello misurato,  •cortocircuito sulla linea +24V che alimenta i sollevatori.  

**Connettore Ouput 1 e Ouput 2** collegare all'attuatore (sollevatore) nel modo richiesto dal dispositivo in uso; la descrizione del collegamento deve essere riportata nelle istruzioni del relativo attuatore (sollevatore).  

**Selettore della modalità di funzionamento S1** a seconda dell'attuatore (sollevatore) in uso, selezionare la modalità di funzionamento appropriata. Per impostazione predefinita, gli interruttori 1,2,3,4,5,6 sono in posizione off – funzionamento 2-10V.
 
| Canale 1 | Canale 2| Funzione |
|------|------|----------|
| 1 – off | 4 – off | Modalità di funzionamento nell'intervallo di segnali 2-10V, una tensione di comando inferiore a 1,5V genera un allarme.   |
| 1 – on| 4 – on  | Modalità di funzionamento nell'intervallo di segnali 0-10V, nessuna reazione di allarme a un segnale inferiore a 1,5V.   |
| 2 – off | 5 – off  | Modalità di funzionamento proporzionale, segnali in uscita nell'intervallo 0-10V o 2-10V.  |
| 2 – on | 5 – on  | Modalità di funzionamento inversa, segnali in uscita nell'intervallo 10-0V o 10-2V.   |
| 3 – off | 6 – off  | Inversione dell'ingresso disattivata.  |
| 3 – on | 6 – on   | Inversione dell'ingresso attivata.   |

# Principio di funzionamento  

L'alimentatore di emergenza, in modalità di funzionamento normale, alimenta gli attuatori (sollevatori) 24V e carica o mantiene carichi gli accumulatori, che forniranno l'alimentazione in caso di interruzione dell'alimentazione.  Il selettore AUTO/MANUAL determina la modalità di funzionamento del dispositivo.  

**La modalità MANUAL** consente il comando diretto degli attuatori (sollevatori) tramite la manopola sul pannello del dispositivo.  

**La modalità AUTO** – modalità di funzionamento principale, trasmette il segnale di comando dall'ingresso all'uscita, eseguendo l'elaborazione appropriata in base alle impostazioni dell'interruttore «S1» e monitorando il livello del segnale di ingresso.  In caso di rilevamento di anomalie su un determinato ingresso, il dispositivo fornisce alla propria uscita il segnale della manopola sul pannello anteriore.  Il relè di allarme interviene in caso di:  •segnale di ingresso troppo basso (Uin < 1,5V) – interruttore «S1» 1-off, 4-off,  •cortocircuito del segnale di uscita verso massa o 24V,  •assenza della tensione di alimentazione,  •cortocircuito della tensione 24V.

## Utilizzo 

L'utente seleziona con il selettore la modalità MANUAL e, con la manopola, il grado di apertura delle prese d'aria adeguato alle esigenze – gli attuatori funzionano in base all'impostazione della manopola. Dopo aver completato le impostazioni delle prese d'aria, selezionare con il selettore la modalità AUTO e lasciare il dispositivo in funzione – le prese d'aria si posizionano al livello richiesto dal controllore di ventilazione. In una situazione di emergenza, le prese d'aria si posizionano in base all'impostazione della manopola.  

## Pannello anteriore 

| MENU                       | Descrizione | 
|:---:                       |:---|
|![Collegamento](./img/paneldcw50.png) |**Spia POWER** – segnala la presenza dell'alimentazione e la carica degli accumulatori.  1.**Spia CHECK** – rimane accesa in modalità automatica quando all'uscita viene trasmesso il segnale del controllore, lampeggia quando all'uscita viene fornito il segnale della manopola.  2.**OUT 1** – segnala anomalie nel canale 1.  3.**OUT 2** – segnala anomalie nel canale 2.  4.**AUTO** – modalità di funzionamento automatica.  5.**MANUAL** – modalità di funzionamento manuale.  6.**Manopola 0%-100%** - selezione del grado di apertura delle prese d'aria.| 

# Messaggi di errore e di avvertimento

I messaggi di errore servono a informare l'utente delle anomalie nel funzionamento del dispositivo. Di seguito sono riportati i possibili messaggi di errore:
 -  Spia POWER – non si accende in verde – assenza di alimentazione di rete.
 -  Spia CHECK – lampeggia in giallo – alle uscite è stato fornito il segnale del potenziometro.
 -  Spia OUT 1 – si accende in rosso - rilevamento di anomalie (assenza del segnale di comando, cortocircuito sull'uscita o cortocircuito sulla linea 24VDC) nel primo canale.
 -  Spia OUT 2 – si accende in rosso - rilevamento di anomalie (assenza del segnale di comando, cortocircuito sull'uscita o cortocircuito sulla linea 24VDC) nel secondo canale.

# Note e avvertenze  

:::danger 
Durante l'installazione del dispositivo, l'alimentazione elettrica deve essere tassativamente scollegata, poiché la tensione presente su alcuni componenti è pericolosa per la vita e la salute. Si raccomanda di affidare l'installazione a una persona qualificata.
:::

 - Per evitare problemi durante l'utilizzo del dispositivo, è obbligatorio leggere le istruzioni prima di procedere all'installazione e all'utilizzo. Non è consentito intervenire sulla struttura né eseguire riparazioni autonomamente. Ciò riguarda in particolare le modifiche degli elementi e dei componenti.
 - Le operazioni di manutenzione o di assistenza devono essere eseguite da personale autorizzato (installatore o servizio di assistenza del produttore). Negli edifici zootecnici con ventilazione forzata è obbligatorio un sistema di allarme. 
 - Il produttore del dispositivo non risponde dei danni causati da un'installazione non corretta, da una programmazione non corretta delle funzioni, dalle conseguenze di eventi fortuiti e da fattori esterni. Il dispositivo richiede l'impostazione dei parametri in base alle condizioni presenti nel locale di allevamento.Tali impostazioni sono individuali e dipendono dalle decisioni dell'allevatore. 
 - Il produttore del dispositivo si riserva il diritto di apportare modifiche alla struttura del dispositivo e al software.
Il dispositivo comprende una batteria di accumulatori; occorre evitarne la scarica eccessiva, che può causare danni alla batteria. 
Il cortocircuito dei poli della batteria può provocare un incendio.  


:::caution
![testo alternativo](./img/trash.svg) Al termine dell'utilizzo del prodotto, non smaltirlo insieme ai rifiuti urbani indifferenziati, ma smaltirlo in conformità alle disposizioni vigenti (direttive WEEE dell'Unione Europea 2012/19/UE).  Il prodotto è stato realizzato in conformità ai requisiti RoHS (direttiva dell'Unione Europea 2011/65/UE).
:::

<!-- \newpage -->
# Dati tecnici del controllore  

|Parametro                        |	DESCRIZIONE      |
|:-----------                    |:---------- |
|Tensione di alimentazione alternata|	85~264VAC 47~63Hz|
|Tensione di alimentazione continua|	120~370VDC|
|Tensione di uscita|	27,6VDC|
|Corrente massima di uscita|	1,8A|
|Rendimento|	85%|
|Corrente massima delle uscite di comando 0-10V|	30mA|
|Corrente massima dell'uscita (contatto) ALARM|	3A|
|Protezione contro le sovratensioni degli ingressi e delle uscite|	SÌ|
|Protezione contro i cortocircuiti|	Automatica |
|Batteria di accumulatori|	4Ah 24V|
|Intervallo di temperatura di funzionamento|	-10 +40oC|
|Dimensioni del dispositivo|	20x15x8 cm|
|Grado di protezione dell'involucro|	IP65|

:::info
Il controllore IC-AC include nella confezione:
 - tasselli a espansione - 	4 pz., 
 - accumulatori 12V 4Ah - 	2 pz., 
 - pressacavo PG13,5 -	1 pz.,
 - pressacavo PG11 -	3 pz., 
 - pressacavo PG9 -	3 pz.
:::

