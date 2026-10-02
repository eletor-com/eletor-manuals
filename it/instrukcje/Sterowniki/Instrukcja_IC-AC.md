---
sidebar_position: 4
title: Manuale IC-AC
description: Centralina IC-AC per prese d'aria di locali zootecnici con corrente di
  uscita ammissibile fino a 2A
keywords:
- eletor IC-AC
- centralina delle prese d'aria
- centralina climatica
- centralina di ventilazione per porcilaie
- centralina del microclima
- centralina per porcilaie
- ventilazione delle porcilaie
- centralina per locali di accrescimento
---


# Centralina IC-AC

  Centralina per attuatori e sistemi di sollevamento delle prese d'aria basati su motori AC con rotazione destra/sinistra e potenziometro per la lettura della posizione corrente. La centralina svolge la funzione di convertitore del segnale 0-10V nel livello di apertura delle prese d'aria e consente inoltre il comando manuale.

## Parametri e caratteristiche:  
- Modalità di funzionamento:
  - MANUAL – comando manuale mediante i pulsanti «+», «-»;
  - AUTO – funzionamento automatico nell'intervallo calibrato, proporzionale al segnale 0-10V;
  - EMERGENZA – in caso di perdita del segnale di comando, le prese d'aria si aprono al livello impostato in percentuale; 
- Uscita a relè (destra/sinistra) 2A;
- Segnale di comando: 0-10V;
- Possibilità di inversione del segnale di comando;
- Misurazione della posizione mediante potenziometro 1-100kΩ;
- Isteresi e tempo di media delle letture programmabili; 
- Involucro ermetico IP56;
- Tensione di alimentazione 230VAC 50Hz;
- Menu in lingua: 
  - polacca
  - inglese
  - ucraina
  - russa

# Installazione della centralina  
:::danger 
Durante l'installazione del dispositivo, è assolutamente necessario scollegare l'alimentazione elettrica, poiché la tensione presente su alcuni componenti è pericolosa per la vita e la salute. Si raccomanda di affidare l'installazione a una persona qualificata.
:::

## Scelta del luogo di montaggio  

  Il luogo di montaggio deve essere scelto in modo razionale, tenendo conto della facilità di accesso al dispositivo per le persone autorizzate e dell'inaccessibilità per animali e bambini. Occorre inoltre considerare le condizioni climatiche, ossia il dispositivo deve funzionare nell'intervallo di temperatura da -10°C a 40 °C, in un luogo non esposto al sole.

# Montaggio

Il dispositivo può funzionare in condizioni climatiche aggressive. Se montato correttamente, il dispositivo è resistente agli effetti dannosi dell'ambiente. 

  Durante il montaggio occorre prestare attenzione ai seguenti aspetti: 
- il coperchio deve essere serrato con tutte le viti,
- i cavi utilizzati per il collegamento del dispositivo devono avere una sezione circolare,
- dopo aver collegato il cavo, occorre serrare i pressacavi in modo da garantire la tenuta e l'immobilizzazione del cavo; si raccomanda l'uso di silicone,
- le uscite non utilizzate (pressacavi) devono essere chiuse con tappi,
- la parte inferiore dell'involucro deve essere fissata a una parete piana con 4 tasselli a espansione.


# Collegamento elettrico  

:::danger 
Prima di collegare il sistema, accertarsi che l'alimentazione sia disinserita!
:::

  Dopo aver svitato le viti del dispositivo, occorre rimuovere il pannello frontale. A tale scopo, estrarre il cavo piatto dal connettore contrassegnato come P1. Far passare i cavi attraverso i pressacavi in gomma e procedere al loro collegamento. Il collegamento deve essere eseguito conformemente alla descrizione. I morsetti della centralina sono illustrati nella figura seguente.

![Collegamento](./img/ic-acpołącz.png)

## Collegare l'alimentazione 230V AC proveniente dal quadro elettrico ai morsetti:  
 - **Connettore L** morsetto di fase. È obbligatorio utilizzare un interruttore di protezione contro le sovracorrenti (tipo «S» B3) e limitatori di sovratensione.  
 - **Connettore N** morsetto di neutro.  
 - **Connettore PE** morsetto di protezione.

## Uscita per l'attuatore: 
 - **Connettore L** collegare mediante un cavo al connettore C per fornire tensione ai relè.  
 - **Connettore N** morsetto di neutro dell'attuatore.  
 - **Connettore PE** morsetto di protezione dell'attuatore – involucro.  
 - **Connettore NO** morsetto dell'attuatore nella direzione di apertura delle prese d'aria.  
 - **Connettore NC** morsetto dell'attuatore nella direzione di chiusura delle prese d'aria.
 - **Connettore del potenziometro** – collegare conformemente alle indicazioni sullo schema dell'attuatore. La polarità di alimentazione del potenziometro deve essere scelta in modo che le unità di posizione aumentino durante l'apertura delle prese d'aria e diminuiscano durante la chiusura. In caso contrario, invertire i cavi di alimentazione del potenziometro.  
 - **Connettore In** – collegare alla centralina per fornire il segnale di comando ai sistemi di sollevamento.  


# Principio di funzionamento  

  In modalità automatica, la centralina converte il segnale di comando nell'intervallo 0-10V nella corrispondente  posizione dell'attuatore delle prese d'aria. È necessario calibrare l'attuatore nelle posizioni di massima apertura e chiusura delle prese d'aria. Durante la calibrazione, occorre assicurarsi che i cavi  diretti alle prese d'aria rimangano costantemente in tensione. Durante la calibrazione, il pulsante «+» deve aprire le prese d'aria e il pulsante «-» deve chiuderle. In caso contrario, scambiare i cavi sui morsetti NO e NC.
  Le posizioni lette dal potenziometro per l'apertura e la chiusura devono differire di oltre 100 unità. Le unità di posizione lette dal potenziometro devono aumentare durante l'apertura delle prese d'aria e diminuire durante la chiusura. In caso contrario, scambiare i cavi di alimentazione del potenziometro.
  Dopo una corretta calibrazione, la centralina è pronta per il funzionamento automatico e controllerà la posizione dell'attuatore. L'applicazione di un segnale di comando inferiore a 1,5V comporta il posizionamento delle prese d'aria nella posizione di emergenza. 

## Utilizzo 

  La centralina delle prese d'aria può funzionare in una delle due modalità: manuale o automatica. La modalità di funzionamento selezionata viene memorizzata e non è influenzata dall'interruzione dell'alimentazione: al ripristino dell'alimentazione, la centralina ritorna alla modalità in cui funzionava in precedenza. La modalità di funzionamento attualmente selezionata è indicata sul display:  
   - **MANUAL** - tenendo premuto a lungo "+" o "-" si attiva la modalità manuale. In questa modalità, le prese d'aria sono comandate manualmente con i pulsanti: «+» - apertura, «-» - chiusura.           
   - **AUTO**   - tenendo premuto a lungo "Esc" si attiva la modalità automatica. In questa modalità, le prese d'aria funzionano automaticamente, comandate dal segnale 0-10V proveniente dal connettore In.

## Funzioni del menu principale  

| MENU                       | Descrizione | 
|:---:                       |:---|
|MANUAL  STOP    POT 539  |  **«Modalità informativa»** – del funzionamento manuale. Informazioni visualizzate:  - **STOP** – attuatore fermo;  - **OPEN** – apertura delle prese d'aria dopo la pressione del pulsante «+»;  - **CLOSE** – chiusura delle prese d'aria dopo la pressione del pulsante «-»;  - **POT 539** – parametro della posizione corrente dell'attuatore determinato dal potenziometro.  •Passaggio alla modalità di funzionamento automatico tenendo premuto il tasto «Esc»| 
|AUTO  20 % = In 3,70 POT 511       |  **«Modalità informativa»**  del funzionamento automatico. Informazioni visualizzate:    **20 %**  Valore della posizione di apertura impostata delle prese d'aria    **"="**   prese d'aria nella posizione stabilita    **"–"**    chiusura delle prese d'aria fino alla posizione specificata    **"+"**    apertura delle prese d'aria fino alla posizione specificata    **In 3,70**  misurazione della tensione di comando sui morsetti In     **POT 511**  parametro della posizione corrente dell'attuatore determinato dal potenziometro.  Passaggio alla modalità di funzionamento manuale tenendo premuto il tasto «+» o «-» | 
|Serrande in emergenza 30 %  |**«Serrande in emergenza»** – impostazione del valore di apertura di emergenza delle serrande (prese d'aria) in caso di perdita del segnale di comando. Le prese d'aria si apriranno al livello impostato in caso di guasto della centralina o del cavo di segnale.| 
|Calibrazione Apertura 671 -> 311        |**«Calibrazione dell'apertura»** – la calibrazione dell'apertura delle prese d'aria si esegue impostando la massima apertura (posizione estrema) delle prese d'aria mediante i pulsanti «+» e «-». Il primo valore visualizzato rappresenta l'ultima impostazione salvata, il secondo valore la posizione corrente dell'attuatore. Il tasto «Ok» memorizza le impostazioni inserite, mentre «Esc» esce dalla modalità di calibrazione senza salvare.   | 
|Calibrazione Chiusura 281 -> 311      |**«Calibrazione della chiusura»** – la calibrazione della chiusura delle prese d'aria si esegue impostando la posizione minima delle prese d'aria mediante i pulsanti «+» e «-». Il primo valore visualizzato rappresenta l'ultima impostazione salvata, il secondo valore la posizione corrente dell'attuatore. Il tasto «Ok» memorizza le impostazioni inserite, mentre «Esc» esce dalla modalità di calibrazione senza salvare.|  
|Tempo di media 5 s       |**«Tempo di media»** – tempo di media del segnale di comando proveniente dal connettore In, protegge dalle oscillazioni all'ingresso di comando.  | 
|Inversione   No |**«Inversione»** – l'attivazione di questa funzione adatta la centralina al segnale di comando 10-0V  | 
|Lingua   Polacco |**«Lingua»** – selezione della lingua del menu  | 
|Isteresi Pot  5   | **«Isteresi del potenziometro»** – una variazione del parametro di posizione dell'attuatore inferiore al valore impostato non viene presa in considerazione durante il posizionamento. Il parametro ha lo scopo di eliminare i movimenti molto piccoli dell'attuatore e i disturbi provenienti dal potenziometro. | 
 

# Note e avvertenze  

:::danger 
Durante l'installazione del dispositivo, è assolutamente necessario scollegare l'alimentazione elettrica, poiché la tensione presente su alcuni componenti è pericolosa per la vita e la salute. Si raccomanda di affidare l'installazione a una persona qualificata.
:::

- Per evitare problemi durante l'utilizzo del dispositivo, è necessario leggere le istruzioni prima di procedere all'installazione e all'uso. È vietato intervenire sulla struttura o eseguire riparazioni autonomamente. Ciò riguarda in particolare la modifica di elementi e componenti.
- Le operazioni di manutenzione o assistenza devono essere eseguite da personale autorizzato (installatore o servizio di assistenza del produttore). Negli edifici zootecnici con ventilazione forzata è obbligatorio un sistema di allarme. 
- Il produttore del dispositivo non risponde dei danni causati da un'installazione non corretta, da una programmazione non corretta delle funzioni, dalle conseguenze di eventi fortuiti e da fattori esterni.
- Il dispositivo richiede l'impostazione dei parametri in base alle condizioni presenti nel locale di allevamento. Tali impostazioni sono individuali e dipendono dalla decisione dell'allevatore. Il produttore del dispositivo si riserva il diritto di apportare modifiche alla struttura del dispositivo e al software.  


:::caution
![testo alternativo](./img/trash.svg) Al termine dell'utilizzo del prodotto, non smaltirlo insieme ai rifiuti urbani indifferenziati, ma smaltirlo conformemente alle normative vigenti (direttive RAEE dell'Unione europea 2012/19/UE).  Il prodotto è stato realizzato conformemente ai requisiti RoHS (direttiva dell'Unione europea 2011/65/UE).
:::

<!-- \newpage -->
# Dati tecnici della centralina  

|Parametro                        |	DESCRIZIONE      |
|:-----------                    |:---------- |
|Tensione di alimentazione alternata|	230VAC 50Hz|
|Corrente massima di uscita|	2A|
|Filtro antidisturbo di uscita|	RC|
|Impedenza di ingresso|	100kΩ|
|Protezione contro le sovratensioni degli ingressi e delle uscite|	SÌ|
|Alimentazione del potenziometro|	10VDC|
|Corrente massima delle uscite del potenziometro|	30mA|
|Intervallo di temperatura di esercizio|	-10 +40oC|
|Dimensioni del dispositivo|	20x15x8 cm |
|Grado di protezione dell'involucro|	IP65|

:::info
La centralina IC-AC comprende nella confezione:
- 4 tasselli a espansione,
- 2 pressacavo PG11,
- 2 pressacavo PG9.
:::

