---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Le domande più frequenti sulla scelta, la configurazione, la diagnostica
  e l'assistenza dei dispositivi ELETOR.
keywords:
- ELETOR
- FAQ
- controllori della ventilazione
- regolatori
- ventilatori
- attuatori
- allarmi
- inverter
- assistenza
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Domande frequenti

Le FAQ sono state elaborate sulla base di un'analisi anonimizzata di conversazioni reali con utenti e clienti di ELETOR. Le risposte sono state generalizzate per fornire assistenza nei casi tipici e non contengono dati relativi a persone o impianti specifici.

:::note Ambito delle FAQ

Le risposte riguardano casi tipici. Le designazioni dei morsetti, le funzioni e le modalità di collegamento possono variare tra i modelli e le versioni dei dispositivi. In caso di dubbi, consultare la documentazione relativa al prodotto specifico.

:::

:::warning Sicurezza

Eseguire gli interventi sull'impianto elettrico in conformità alla documentazione del dispositivo e alle norme di sicurezza vigenti. Gli interventi sulla tensione di rete devono essere eseguiti da una persona in possesso delle qualifiche appropriate.

:::

## Scelta del controllore e della potenza

### Come scegliere il controllore per i ventilatori?

Il criterio principale di scelta è soprattutto la corrente totale dei ventilatori, non soltanto il loro numero.

:::tip Preparare i dati prima della scelta

Quanto più precisi sono i dati sui motori e sul funzionamento dell'impianto, tanto più affidabile sarà la scelta del controllore.

:::

Prima della scelta è opportuno preparare:

- il numero di ventilatori,
- la tensione di alimentazione,
- la potenza o la corrente nominale di ciascun ventilatore,
- l'informazione se tutti i ventilatori devono funzionare con regolazione continua,
- l'informazione se i ventilatori possono essere suddivisi in gruppi,
- le informazioni sui dispositivi aggiuntivi, ad esempio riscaldatori o prese d'aria.

Il controllore non deve essere dimensionato esattamente al limite. Occorre mantenere un adeguato margine rispetto al carico massimo.

### È sufficiente sommare la potenza dei ventilatori in watt?

La potenza può essere utilizzata per una stima preliminare, ma la scelta definitiva deve basarsi sulla corrente nominale dei dispositivi e sulla natura del carico.

Durante l'avviamento, il motore può assorbire più corrente rispetto al funzionamento normale. Per questo motivo, due insiemi di ventilatori con potenza nominale simile non costituiscono sempre un carico equivalente per il controllore.

### Ho diversi ventilatori piccoli. Posso collegarli in parallelo a una sola uscita?

Sì, a condizione che:

- siano progettati per questo tipo di comando,
- debbano funzionare insieme,
- la somma dei carichi non superi la corrente ammissibile dell'uscita,
- il collegamento sia conforme alla documentazione del controllore.

Con un numero maggiore di ventilatori, è opportuno valutare la suddivisione in gruppi o l'impiego di un'espansione di potenza.

### Quando è necessaria un'espansione di potenza?

L'espansione di potenza si utilizza quando il carico supera la capacità dell'uscita del controllore oppure quando l'impianto deve essere ampliato con un numero maggiore di ventilatori.

In questo caso, il controllore trasmette il segnale di comando, mentre il carico effettivo viene gestito da un modulo aggiuntivo.

### È possibile ampliare successivamente l'impianto con ulteriori ventilatori?

In molti impianti sì. Le soluzioni più utilizzate sono:

- un'ulteriore espansione di potenza,
- un gruppo di ventilazione aggiuntivo,
- un contattore che inserisce un altro gruppo,
- un inverter nel caso di motori trifase.

È preferibile prevedere l'ampliamento pianificato già durante la scelta iniziale del controllore.

### Tutti i ventilatori devono funzionare con regolazione continua?

No. Le soluzioni tipiche sono due:

1. tutti i ventilatori funzionano con regolazione continua,
2. il primo gruppo funziona con regolazione continua e i gruppi successivi vengono inseriti gradualmente, ad esempio mediante contattori.

La seconda soluzione consente di gestire un impianto più grande senza regolare in modo continuo ogni ventilatore.

### Ho 10 ventilatori. Ho bisogno di un controllore molto grande?

Non sempre. È possibile utilizzare diverse modalità di comando:

- suddivisione in gruppi,
- espansioni di potenza,
- contattori,
- inverter.

La scelta definitiva dipende dai parametri elettrici dei ventilatori e dal fatto che tutti debbano variare contemporaneamente la velocità di rotazione.

### I controllori 6 A e 12 A differiscono soltanto per il carico ammissibile?

Non si deve presumere che l'unica differenza sia il valore della corrente. Le singole versioni e generazioni dei dispositivi possono differire per dotazione o realizzazione costruttiva.

Quando si sostituisce un dispositivo, occorre verificare il modello esatto e la documentazione aggiornata.


## Ventilatori e controllo della ventilazione

### Il controllore regola i ventilatori in modo continuo?

Nei controllori destinati alla regolazione continua della ventilazione, la velocità dei ventilatori varia in funzione del fabbisogno determinato, tra l'altro, dalla temperatura.

Occorre tuttavia verificare che il tipo di motore sia adatto alla modalità di regolazione utilizzata.

### Che cosa significa temperatura impostata?

La temperatura impostata è il valore con cui il controllore confronta la misurazione attuale della temperatura.

In base a tale valore, il controllore aumenta o diminuisce l'intensità della ventilazione secondo le altre impostazioni, ad esempio la banda di regolazione e i livelli minimo e massimo.

### Che cosa significa livello minimo di ventilazione?

È il valore minimo del comando del ventilatore durante il funzionamento automatico.

Questa impostazione impedisce il funzionamento al di sotto del livello al quale il ventilatore potrebbe funzionare in modo instabile o garantire un ricambio d'aria insufficiente.

### Che cosa significa livello massimo di ventilazione?

È il limite superiore del valore del comando della ventilazione.

Ad esempio, impostare un valore inferiore a 100% può limitare la velocità massima del ventilatore, se l'impianto lo richiede.

### Che cosa significa banda di ventilazione?

La banda di ventilazione definisce l'intervallo di temperature nel quale il controllore passa dal livello minimo al livello massimo di ventilazione.

Quanto più stretta è la banda, tanto più rapidamente il comando reagisce a una variazione della temperatura aumentando la portata.

### Dopo l'avviamento, il ventilatore raggiunge prima 100% e soltanto successivamente rallenta. Perché?

Potrebbe essere attiva una funzione di avviamento che ha lo scopo di avviare temporaneamente il motore con una potenza maggiore.

A seconda della versione del controllore, occorre verificare le impostazioni relative a:

- funzione di avviamento graduale,
- tempo di accelerazione,
- tempo di funzionamento a 100%,
- tempo di decelerazione.

Se la funzione non è necessaria nell'impianto, i relativi parametri possono essere modificati secondo le istruzioni del dispositivo.

### Perché il ventilatore può essere avviato temporaneamente a piena potenza?

Questo tipo di avviamento può favorire un avvio affidabile del ventilatore ed essere utile negli impianti in cui gli elementi meccanici possono opporre una maggiore resistenza durante l'avviamento.

Non è tuttavia necessario in tutti gli impianti.

### Che cosa significano tempo di accelerazione e tempo di decelerazione?

**Il tempo di accelerazione** definisce la modalità di incremento del comando durante l'avviamento del ventilatore.

**Il tempo di decelerazione** definisce la modalità di riduzione della velocità.

Entrambi i parametri consentono di limitare le variazioni brusche della velocità di rotazione e del funzionamento dell'impianto.

### Perché due controllori identici possono avviare i ventilatori in modo diverso?

La causa più frequente è la differenza nelle impostazioni.

È opportuno confrontare soprattutto:

- la temperatura impostata,
- la banda di ventilazione,
- il minimo e il massimo,
- le impostazioni di avviamento graduale,
- i tempi di accelerazione e decelerazione,
- la configurazione dei gruppi di ventilazione.

### Il controllore può avviare periodicamente la ventilazione indipendentemente dalla temperatura?

A seconda del modello, è disponibile una funzione di aerazione periodica.

Questa funzione può avviare la ventilazione per un tempo determinato a intervalli impostati, anche quando la regolazione della temperatura non richiede un aumento della ventilazione.

### A che cosa servono i gruppi di ventilazione?

I gruppi consentono di aumentare gradualmente la portata dell'impianto.

Ad esempio:

- il gruppo 1 funziona con regolazione continua,
- il gruppo 2 avvia altri ventilatori,
- il gruppo successivo si avvia quando il fabbisogno aumenta ulteriormente.

Ciò consente di controllare un numero elevato di ventilatori senza regolare in modo continuo ciascuno di essi.

### È possibile inserire un gruppo aggiuntivo di ventilatori mediante un contattore?

Sì. L'uscita a relè del controllore può comandare la bobina di un contattore opportunamente dimensionato.

In questo caso, il carico dei ventilatori non deve transitare direttamente attraverso il piccolo contatto di comando.

### Che cosa indica il simbolo del ventilatore o la spia gialla sul controllore?

A seconda del modello, le spie indicano lo stato attuale delle uscite e delle funzioni.

La segnalazione gialla può indicare una funzione operativa attiva, ad esempio il funzionamento della ventilazione, del riscaldamento o di un altro gruppo.

Il significato esatto deve essere verificato nel manuale del modello specifico.

### Che cosa indica il simbolo della modalità manuale?

La modalità manuale indica che il valore del comando è stato forzato dall'utente e non viene, in quel momento, calcolato automaticamente in base alla temperatura.

Al termine delle prove, accertarsi che il controllore sia stato riportato alla corretta modalità automatica.


## Prese d'aria e attuatori

### Il controllore può comandare le prese d'aria?

Sì, alcuni controllori consentono di interfacciarsi con gli azionamenti delle prese d'aria.

La modalità di collegamento dipende dal tipo di attuatore e dalla sua modalità di comando.

### Quali tipi di attuatori si possono utilizzare per le prese d'aria?

Nelle conversazioni tecniche sono emerse principalmente due soluzioni:

- attuatore comandato da un segnale analogico 0–10 V oppure 2–10 V,
- attuatore reversibile apri/chiudi con segnale di retroazione, ad esempio da un potenziometro.

Prima dell'acquisto, verificare la compatibilità del modello specifico con il controllore in uso.

### La tensione di alimentazione dell'attuatore 24 V oppure 230 V influisce sul segnale 0–10 V?

Il segnale di comando e l'alimentazione dell'attuatore sono parametri distinti.

L'attuatore può essere alimentato con una tensione diversa da quella del segnale di comando. Entrambi i parametri devono essere conformi alla documentazione dell'attuatore e del controllore.

### Che cosa significa comando 0–10 V?

Il controllore invia un segnale analogico in tensione che rappresenta la posizione o il livello di comando richiesto.

In un'applicazione tipica, un valore inferiore indica un'apertura minore e un valore superiore un'apertura maggiore, ma la caratteristica effettiva deve essere verificata nella documentazione dell'attuatore.

### Qual è la differenza tra 0–10 V e 2–10 V?

In entrambi i casi, la posizione viene impostata mediante un segnale analogico.

Nello standard 2–10 V, la parte inferiore dell'intervallo è traslata e può consentire al dispositivo di distinguere il segnale di comando dalla sua assenza.

Il controllore e l'attuatore devono supportare un intervallo compatibile.

### Come scegliere l'attuatore in base al numero di prese d'aria?

L'attuatore non deve essere scelto esclusivamente in base al numero di serrande.

Occorre considerare:

- la forza o la coppia richiesta,
- la lunghezza e la disposizione del meccanismo,
- le resistenze delle serrande,
- la lunghezza della corsa,
- la velocità di azionamento,
- la tensione di alimentazione,
- il tipo di comando,
- la retroazione richiesta.

### Un solo attuatore può azionare più serrande?

Sì, se la meccanica dell'impianto consente di collegare le serrande mediante un sistema comune e la coppia o la forza richiesta non supera la capacità dell'attuatore.

In pratica, la scelta dipende dalle resistenze dell'intero meccanismo, non soltanto dal numero di serrande.

### È possibile collegare più attuatori in parallelo e comandarli con un solo segnale?

In alcuni sistemi è possibile, ma occorre verificare la documentazione degli attuatori e il carico ammissibile dell'uscita di comando.

Nel caso di azionamenti reversibili senza retroazione indipendente, può inoltre verificarsi un progressivo disallineamento delle posizioni dei singoli attuatori.

### Perché più attuatori possono assumere posizioni diverse nel tempo?

Anche motori identici possono funzionare a velocità leggermente diverse a causa di:

- carichi diversi,
- resistenze meccaniche,
- tolleranze dei parametri del motore,
- differenze nei riduttori.

Pertanto, quando è richiesta una sincronizzazione precisa, è necessaria una retroazione adeguata o un controllo individuale della posizione.

### Le prese d'aria possono essere comandate proporzionalmente alla ventilazione?

Sì. Nei sistemi configurati correttamente, la posizione delle prese d'aria può essere collegata al livello attuale di ventilazione.

In questo modo, all'aumentare della portata dei ventilatori aumenta anche l'apertura delle prese d'aria.

### L'attuatore 24 V richiede un alimentatore separato?

Se il controllore non dispone di un'uscita di alimentazione adeguata con la potenza richiesta, è necessario un alimentatore separato.

La sua potenza deve essere dimensionata in base all'assorbimento di corrente dell'attuatore e degli altri dispositivi alimentati dalla stessa sorgente.

### È possibile utilizzare un attuatore di un altro produttore?

Spesso sì, se i suoi parametri elettrici e la modalità di comando sono compatibili con le uscite del controllore.

Prima del collegamento, verificare:

- la tensione,
- il tipo di segnale,
- lo schema dei conduttori,
- le direzioni di funzionamento,
- il segnale di posizione,
- il carico ammissibile.


## Sensori di temperatura e umidità

### Dove collegare il sensore di temperatura?

Il sensore deve essere collegato all'ingresso per sensori previsto dal produttore, all'ingresso per sensori indicato nella documentazione del modello specifico.

Non si deve presumere che le designazioni dei morsetti siano identiche in tutte le versioni dei dispositivi.

### Il sensore di temperatura indica un valore diverso dal termometro di riferimento. Che cosa fare?

Se il controllore dispone di una funzione di calibrazione del sensore, è possibile correggere l'indicazione dopo averla confrontata con un termometro di riferimento affidabile.

Prima di modificare la calibrazione, è opportuno accertarsi che:

- entrambi i sensori si trovino nello stesso punto,
- la misurazione si sia stabilizzata,
- il sensore non venga riscaldato dal sole o da dispositivi,
- non si trovi direttamente in un flusso d'aria fredda o calda.

### Il sensore di umidità indica un valore errato. È possibile calibrarlo?

Dipende dalla versione del controllore, del sensore e del software.

In alcune soluzioni, la correzione può richiedere un'apposita funzione software o un tipo di sensore compatibile. Se la differenza è elevata e ripetibile, verificare la versione del dispositivo e contattare l'assistenza tecnica.

### Una misurazione errata indica sempre un sensore danneggiato?

No.

La causa può essere anche:

- una posizione errata del sensore,
- il cavo,
- il collegamento elettrico,
- la configurazione,
- un tipo di sensore non corretto,
- la necessità di calibrazione,
- l'umidità o la corrosione.


## Allarmi e notifiche

### È possibile collegare direttamente una sirena all'uscita di allarme del controllore?

Non si deve darlo per scontato.

L'uscita di allarme del controllore è generalmente un'uscita di comando o un contatto a relè. La sirena può richiedere un'alimentazione separata e una centrale di allarme.

### Perché si utilizza una centrale di allarme?

La centrale può:

- ricevere segnali di allarme dai controllori,
- alimentare il segnalatore,
- mantenere il funzionamento in caso di interruzione dell'alimentazione,
- segnalare l'allarme mediante suono o luce,
- inviare notifiche GSM nelle versioni dotate di questa funzione.

### La centrale può segnalare un allarme in caso di interruzione dell'alimentazione del controllore?

Sì, se il sistema è stato collegato correttamente.

La soluzione può rilevare non soltanto il superamento della temperatura, ma anche la perdita del segnale del controllore causata dall'interruzione della sua alimentazione.

### Dove si impostano la temperatura minima e massima di allarme?

Nella configurazione tipica, le soglie di allarme vengono impostate nel controllore che gestisce la camera o il locale specifico.

La centrale di allarme riceve quindi l'informazione che il controllore ha segnalato un allarme.

### La centrale GSM richiede una scheda SIM?

Per effettuare chiamate e inviare messaggi tramite la rete mobile, è necessaria una scheda SIM attiva o un'altra soluzione di comunicazione prevista nel modello specifico.

Senza una connessione attiva alla rete mobile, le funzioni telefoniche e SMS non funzioneranno.

### Il sistema di allarme può inviare informazioni sul controllore da cui proviene l'evento?

Sì, in un sistema configurato correttamente.

Gli ingressi della centrale possono essere assegnati a locali o controllori specifici, consentendo al messaggio di identificare l'origine dell'allarme.

### Quanti controllori si possono collegare a una sola centrale di allarme?

Dipende dal modello della centrale.

Nelle trascrizioni erano presenti centrali in grado di gestire fino a otto ingressi; tuttavia, prima di realizzare l'impianto, occorre verificare le specifiche aggiornate del dispositivo specifico.

### Quale batteria viene utilizzata nella centrale di allarme?

In alcuni dei dispositivi trattati nelle conversazioni veniva utilizzata una batteria 12 V 7 Ah.

Prima di acquistare una batteria sostitutiva, verificare la designazione riportata sulla batteria esistente e le specifiche della centrale, poiché altre versioni dei dispositivi possono richiedere una batteria diversa.

### La centrale invia messaggi di bassa tensione. Che cosa verificare?

Innanzitutto, occorre verificare:

- lo stato della batteria,
- la sua età,
- i collegamenti della batteria,
- la presenza dell'alimentazione di rete,
- il funzionamento del caricabatteria o dell'alimentatore della centrale.

Una batteria usurata può causare messaggi ciclici di bassa tensione.

### Con quale frequenza sostituire la batteria nella centrale di allarme?

Non esiste un unico intervallo adatto a tutte le condizioni.

La batteria deve essere sottoposta a prove periodiche, soprattutto negli impianti in cui l'allarme durante un'interruzione dell'alimentazione è di importanza critica. Con l'invecchiamento, la sua capacità effettiva diminuisce.

### La sola sirena è sufficiente come protezione?

La sirena è efficace soltanto quando qualcuno può sentirla.

Negli edifici che rimangono temporaneamente senza sorveglianza, è opportuno utilizzare anche notifiche remote e un'alimentazione di riserva a batteria.


## Inverter

### Come scegliere l'inverter per i ventilatori?

Occorre conoscere:

- la tensione di alimentazione,
- il numero di fasi,
- la potenza e la corrente di tutti i motori,
- la loro modalità di collegamento,
- le condizioni di funzionamento,
- la modalità di comando richiesta.

L'inverter deve avere un adeguato margine rispetto al carico, soprattutto quando più motori funzionano in parallelo.

### L'inverter deve avere esattamente la stessa potenza della somma delle potenze dei motori?

Non si deve scegliere l'inverter soltanto sulla base della semplice somma delle potenze, selezionando un dispositivo che funzioni esattamente al limite dei suoi parametri.

Occorre considerare le correnti nominali, la natura del carico e le raccomandazioni del produttore dell'inverter.

### L'inverter ha arrestato i ventilatori e visualizzato un errore. Che cosa fare?

La cosa più importante è annotare il codice di errore completo prima del ripristino.

:::tip Fotografare lo schermo

Se la situazione lo consente, fotografare il display prima del ripristino. Il codice di errore completo facilita notevolmente la diagnosi.

:::

La sola parte iniziale del messaggio spesso non è sufficiente per stabilire la causa. Il codice completo consente di distinguere, tra l'altro:

- sovraccarico,
- sovracorrente,
- surriscaldamento,
- tensione non corretta,
- altri errori dell'azionamento.

### È possibile semplicemente ripristinare l'errore dell'inverter?

Il ripristino può ristabilire il funzionamento, ma non elimina la causa dell'allarme.

Dopo l'evento, occorre verificare il codice di errore e determinare la causa prima di riavviare l'impianto per un funzionamento prolungato.

### L'inverter funziona in un locale polveroso. Deve essere pulito?

Sì.

La polvere e i depositi sul dissipatore o sulla ventola di raffreddamento possono compromettere la dissipazione del calore e causare il surriscaldamento dell'inverter.

La pulizia deve essere eseguita secondo le istruzioni del produttore, dopo aver scollegato l'alimentazione in sicurezza.

### Che cosa può causare il surriscaldamento dell'inverter?

Le cause più frequenti sono:

- elementi di raffreddamento sporchi,
- flusso d'aria ostruito,
- temperatura ambiente troppo elevata,
- sovraccarico,
- guasto della ventola di raffreddamento,
- montaggio non corretto.

### Una tensione di rete elevata può attivare un allarme dell'inverter?

Sì. Gli inverter monitorano la tensione del circuito di alimentazione e possono segnalare un errore quando viene superato il livello ammissibile.

Se il problema si ripete, occorre controllare l'impianto e la qualità dell'alimentazione.


## Guasti e diagnostica

### Il controllore funziona, ma il display non mostra nulla. Quale può essere la causa?

Le possibili cause comprendono, tra l'altro:

- un guasto del display,
- un problema con la regolazione del contrasto nelle soluzioni più datate,
- un collegamento danneggiato,
- la corrosione,
- un guasto della scheda principale.

Se il dispositivo non è stato utilizzato per molto tempo oppure ha funzionato in un ambiente umido, è opportuno verificare anche lo stato della scheda.

### Dopo diversi anni di inutilizzo, il controllore presenta un problema al display. Perché?

Un lungo periodo di inattività in un ambiente umido o aggressivo può causare:

- ossidazione dei connettori,
- corrosione,
- deterioramento dei contatti,
- danni ai componenti elettronici.

In questo caso, è opportuno eseguire una verifica completa anziché sostituire componenti senza una diagnosi preliminare.

### Il controllore è annerito dopo una sovratensione. Significa che la scheda deve essere sostituita?

Non sempre.

Un componente di protezione può danneggiarsi e lasciare molti residui, anche se la parte restante della scheda può essere riparata.

Tuttavia, se il laminato è carbonizzato o bruciato oppure le piste sono danneggiate, la riparazione potrebbe non essere conveniente o duratura.

### Che cosa può danneggiare più controllori contemporaneamente?

Se molti dispositivi si guastano nello stesso momento, occorre verificare l'impianto di alimentazione.

Una delle possibili cause è un problema con il conduttore di neutro che, in un impianto trifase, può determinare tensioni non corrette sulle utenze monofase.

Sono possibili anche sovratensioni provenienti dalla rete o dal gruppo elettrogeno.

### Che cosa fare dopo un guasto legato a una sovratensione?

Prima di collegare un controllore riparato o nuovo, occorre determinare la causa del problema.

:::danger Non ricollegare il dispositivo senza aver verificato l'impianto

Se il guasto è stato causato da una tensione non corretta, da un conduttore di neutro danneggiato o da una sovratensione, il controllore riparato o nuovo potrebbe danneggiarsi nuovamente.

:::

### Che cos'è il componente di protezione contro le sovratensioni sulla scheda?

Nei dispositivi elettronici si utilizzano componenti che limitano le sovratensioni, ad esempio varistori.

Il loro compito è assorbire parte dell'energia della sovratensione e proteggere i circuiti a valle. Dopo un evento di forte intensità, tale componente può subire danni permanenti.

### È possibile avviare il dispositivo dopo aver rimosso il componente di protezione bruciato?

Questa operazione non deve essere considerata una normale riparazione.

Dopo la rimozione della protezione, il dispositivo può perdere la protezione contro una successiva sovratensione. Tali interventi possono essere eseguiti esclusivamente come procedura di assistenza consapevole, da una persona in possesso delle qualifiche appropriate e dopo aver eliminato la causa del guasto iniziale.

### Il controllore ha subito un'infiltrazione di liquidi o è fortemente corroso. Conviene ripararlo?

Dipende dall'entità dei danni.

La corrosione superficiale e i singoli danni possono spesso essere eliminati. Se la corrosione ha interessato le piste, i connettori e molti componenti, la riparazione può richiedere molto tempo, risultare incerta e non essere economicamente giustificata.

### Il lavaggio a pressione del dispositivo può danneggiare il controllore?

Sì.

L'elettronica non deve essere esposta direttamente all'acqua o al detergente se l'involucro e la modalità di montaggio non sono progettati per questo.

L'umidità che penetra all'interno può causare corrosione e guasti successivi difficili da diagnosticare.

### Perché i guasti dovuti a infiltrazioni di liquidi possono ripresentarsi dopo la riparazione?

La corrosione può progredire anche in punti non visibili durante il primo controllo.

I fori metallizzati, le piste e i collegamenti danneggiati possono funzionare durante la prova e successivamente perdere nuovamente il contatto.

Pertanto, in presenza di una scheda fortemente corrosa, il servizio di assistenza può raccomandare la sostituzione anziché ulteriori riparazioni.

### Il dispositivo funziona in modo intermittente. Da dove iniziare?

Prima di contattare il servizio di assistenza, è opportuno raccogliere:

- il modello esatto,
- la descrizione del sintomo,
- il momento in cui si manifesta,
- i valori visualizzati sullo schermo,
- il codice di allarme o di errore,
- le informazioni sulle ultime modifiche all'impianto,
- una fotografia dell'interno e dei morsetti, se può essere scattata in sicurezza.

Quanto più precisa è la descrizione, tanto più semplice sarà la diagnosi.


## Assistenza e riparazioni

### Che cosa inviare al servizio di assistenza se il controllore è danneggiato?

È preferibile inviare un insieme completo che consenta di riprodurre il problema.

Alla spedizione deve essere allegata una breve descrizione di:

- che cosa non funziona,
- quando si presenta il problema,
- se il guasto è permanente o intermittente,
- se prima del guasto si è verificata una sovratensione, un'infiltrazione di liquidi o un altro evento,
- i dati necessari per il contatto e la restituzione del dispositivo.

:::note Dati per la richiesta di assistenza

Trasmettere i dati di contatto e di spedizione direttamente al servizio di assistenza. Non pubblicarli in segnalazioni aperte o in materiali pubblici.

:::

### È necessario inviare l'intero controllore o soltanto la scheda?

Dipende dal guasto.

In caso di problemi con il display, i pulsanti, l'alimentazione o di un comportamento non chiaramente definito, è preferibile inviare l'intero insieme necessario a riprodurre il sintomo.

Per una riparazione di un modulo specifico concordata in precedenza, il servizio di assistenza può richiedere soltanto la scheda.

### ELETOR ripara i controllori anziché sostituirli immediatamente?

Dalle trascrizioni risulta che i dispositivi vengono prima sottoposti a diagnosi.

Se la riparazione è possibile e ragionevole, vengono sostituiti i componenti o i moduli danneggiati. In caso di danni gravi, il servizio di assistenza può proporre la sostituzione della scheda o dell'intero dispositivo.

### Che cosa succede se la scheda danneggiata non può essere riparata?

È possibile sostituire il modulo danneggiato con uno nuovo, purché il ricambio appropriato sia disponibile e compatibile con il dispositivo.

Per i dispositivi più datati, il servizio di assistenza deve prima confermare la compatibilità delle versioni.

### Conviene acquistare subito una nuova scheda dopo una sovratensione?

Non sempre.

Se il danno riguarda un componente di protezione o una piccola parte del circuito, la riparazione può essere giustificata. È opportuno eseguire prima una diagnosi.

### Il servizio di assistenza può verificare anche il display e i pulsanti?

Sì, se questi elementi vengono forniti insieme al dispositivo o al modulo.

È particolarmente utile quando non è noto se il problema si trovi sulla scheda principale o nel pannello utente.

### Conviene sempre recuperare un controllore fortemente corroso?

No.

Se il costo della diagnosi e della riparazione aumenta e l'affidabilità dopo la riparazione rimane incerta, la sostituzione può essere più ragionevole.

Questo vale in particolare per i dispositivi da cui dipende la ventilazione dell'edificio.

### Come accelerare la diagnosi del servizio di assistenza?

Allegare una descrizione precisa del sintomo anziché la sola affermazione «non funziona».

Sono utili anche:

- fotografie,
- il codice di errore,
- la descrizione dell'impianto,
- il tipo di utenze collegate,
- l'informazione su una sovratensione o un'interruzione dell'alimentazione,
- l'informazione su un'infiltrazione di liquidi o sul lavaggio del dispositivo.


## Installazione e cablaggio

### Come collegare i dispositivi ai morsetti del relè C e NO?

C e NO sono designazioni tipiche dei contatti di un relè:

- C — contatto comune,
- NO — contatto normalmente aperto.

La modalità di utilizzo dipende dal dispositivo e dallo schema dell'impianto. Il contatto può essere utilizzato, ad esempio, per comandare la bobina di un contattore, ma non è consentito superare i suoi parametri ammissibili.

:::warning Interventi elettrici

I collegamenti alla tensione di rete devono essere eseguiti da una persona in possesso delle qualifiche appropriate, secondo lo schema del dispositivo specifico.

:::

### L'uscita a relè può alimentare direttamente un ventilatore di grandi dimensioni?

In genere, questo non è un utilizzo appropriato di una piccola uscita di comando.

Per carichi maggiori si utilizza un contattore, un relè di potenza o un modulo di attuazione dedicato.

### A che cosa servono i morsetti A1 e A2 del contattore?

Sono i morsetti della bobina del contattore.

Quando alla bobina viene applicata la tensione appropriata, il contattore cambia lo stato dei propri contatti di potenza.

La tensione della bobina deve essere conforme al progetto dell'impianto e alla documentazione del contattore.

### È possibile montare apparecchi aggiuntivi all'interno dell'involucro del controllore?

Soltanto se la struttura dell'involucro specifico lo consente e non compromette:

- il grado di protezione,
- l'isolamento,
- il raffreddamento,
- la sicurezza,
- l'accesso per la manutenzione.

Qualsiasi nuovo foro deve essere realizzato in modo da mantenere la tenuta richiesta.

### Gli interruttori aggiuntivi per i ventilatori sono utili?

Possono facilitare la manutenzione e consentire lo scollegamento indipendente dei singoli ventilatori.

La realizzazione deve tuttavia tenere conto delle protezioni elettriche e non deve causare stati pericolosi del controllore.

### È possibile posare i cavi di comando insieme ai cavi di potenza?

Occorre evitare di posare cavi di segnale sensibili parallelamente e molto vicino a cavi di elevata potenza, soprattutto su tratti lunghi.

I requisiti dipendono dal tipo di segnale e dall'ambiente elettromagnetico.

### Quale cavo utilizzare per i collegamenti di rete e i dispositivi PoE?

Negli impianti trattati veniva indicato come requisito minimo un cavo a coppie intrecciate di categoria 5e.

Se il cavo attraversa un ambiente con un livello elevato di disturbi o con rischio di cariche elettrostatiche, può essere opportuno utilizzare un cavo adeguatamente schermato e un corretto sistema di messa a terra.

### Per il PoE è necessario un cavo incrociato?

Negli impianti tipici si utilizza un collegamento diretto standard.

Occorre tuttavia verificare sempre i requisiti del dispositivo di rete e dell'alimentatore PoE utilizzato.


## Utilizzo e manutenzione

### Come limitare il rischio di guasti dei controllori negli edifici agricoli?

La cosa più importante è limitare l'influenza di:

- umidità,
- ammoniaca e ambiente aggressivo,
- polvere,
- lavaggio diretto con acqua,
- sovratensioni,
- alimentazione non corretta.

È inoltre opportuno controllare periodicamente lo stato dei cavi, dei collegamenti e degli involucri.

### I dispositivi elettronici devono essere puliti regolarmente?

Sì, soprattutto i dispositivi dotati di dissipatori, ventole e aperture di ventilazione.

La polvere accumulata compromette il raffreddamento.

La pulizia deve essere eseguita dopo aver scollegato l'alimentazione e secondo le istruzioni del dispositivo.

### Dopo alcuni anni di funzionamento, è opportuno eseguire una verifica del controllore?

Sì, soprattutto in condizioni ambientali difficili.

La verifica può comprendere:

- la valutazione dello stato dei connettori,
- il controllo di tracce di umidità e corrosione,
- la verifica degli elementi di raffreddamento,
- la verifica del pannello e dei pulsanti,
- la prova dei sensori,
- il controllo delle batterie nei sistemi di allarme.

### Che cosa è opportuno annotare dopo un guasto?

Le informazioni più utili sono:

- il messaggio completo,
- il codice di errore,
- l'ora dell'evento,
- la temperatura,
- lo stato della ventilazione,
- l'informazione su un'interruzione dell'alimentazione,
- l'informazione sul funzionamento del gruppo elettrogeno,
- una fotografia dello schermo o del dispositivo.

Non ripristinare il dispositivo prima di aver annotato il codice, se la situazione consente di farlo in sicurezza.

### È opportuno avere un allarme indipendente dal controllore della ventilazione?

Sì, soprattutto dove un guasto della ventilazione può determinare rapidamente condizioni pericolose.

Una centrale indipendente, con una propria batteria e notifiche remote, offre un ulteriore livello di protezione.

### Quali informazioni preparare prima di contattare l'assistenza tecnica?

È preferibile preparare:

1. il modello esatto del dispositivo,
2. la descrizione dell'impianto,
3. il numero e i parametri dei dispositivi collegati,
4. le impostazioni attuali relative al problema,
5. il sintomo preciso,
6. il codice completo di errore o di allarme,
7. fotografie del dispositivo e delle targhette identificative,
8. l'informazione sulle ultime modifiche all'impianto.

Questo consente di ridurre notevolmente i tempi della diagnosi.


## Nota importante sui dispositivi più datati

I nomi, le designazioni dei morsetti e le funzioni disponibili possono variare tra le versioni dei dispositivi prodotte in anni diversi.

Se il dispositivo ha diversi anni o più di dieci anni, prima di applicare le istruzioni di un modello più recente occorre confermare:

- la designazione esatta del dispositivo,
- la versione della scheda,
- il tipo di display,
- la versione del software,
- lo schema dei morsetti.

:::warning Versioni più datate dei dispositivi

Non presumere la piena compatibilità soltanto sulla base di un aspetto simile dell'involucro. Prima di utilizzare uno schema o un manuale, confermare il modello esatto e la versione del dispositivo.

:::


## Contatto con l'assistenza tecnica

Se le FAQ non risolvono il problema, preparare prima del contatto:

- una fotografia del controllore,
- una fotografia della targhetta identificativa dell'utenza,
- i parametri dei motori o degli attuatori,
- lo schema dei collegamenti,
- una descrizione precisa del funzionamento atteso.

In questo modo, la scelta del dispositivo o la diagnosi del problema può essere effettuata sulla base dei parametri effettivi dell'impianto, anziché di supposizioni.
