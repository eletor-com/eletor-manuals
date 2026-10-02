---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Le domande più frequenti relative alla selezione, alla configurazione,
  alla diagnostica e all'assistenza dei dispositivi ELETOR.
keywords:
- ELETOR
- FAQ
- controllori di ventilazione
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

Le FAQ sono state create sulla base di un'analisi anonimizzata di conversazioni reali con utenti e clienti ELETOR. Le risposte sono state generalizzate in modo da essere utili nei casi tipici e da non contenere dati di persone o installazioni specifiche.

:::note Ambito delle FAQ

Le risposte riguardano casi tipici. Le sigle dei morsetti, le funzioni e la modalità di collegamento possono variare tra modelli e versioni dei dispositivi. In caso di dubbi, fare riferimento alla documentazione specifica del prodotto.

:::

:::warning Sicurezza

Eseguire i lavori sull'impianto elettrico in conformità alla documentazione del dispositivo e alle norme di sicurezza vigenti. I lavori sotto tensione di rete devono essere eseguiti da una persona con qualifiche adeguate.

:::

## Selezione del controllore e della potenza

### Come selezionare il controllore per i ventilatori?

Il criterio fondamentale di selezione è soprattutto la corrente totale dei ventilatori, non soltanto il loro numero.

:::tip Preparare i dati prima della selezione

Quanto più precisi sono i dati sui motori e sulla modalità di funzionamento dell'impianto, tanto più affidabile sarà la selezione del controllore.

:::

Prima della selezione è opportuno predisporre:

- il numero di ventilatori,
- la tensione di alimentazione,
- la potenza o la corrente nominale di ciascun ventilatore,
- l'indicazione se tutti i ventilatori devono funzionare con regolazione continua,
- l'indicazione se i ventilatori possono essere suddivisi in gruppi,
- le informazioni sui dispositivi aggiuntivi, ad esempio riscaldatori o prese d'aria.

Il controllore non deve essere selezionato esattamente «al limite». È necessario mantenere un adeguato margine rispetto al carico massimo.

### È sufficiente sommare la potenza dei ventilatori in watt?

Per una stima preliminare si può utilizzare la potenza, ma la selezione finale deve basarsi sulla corrente nominale dei dispositivi e sulla natura del carico.

Durante l'avviamento il motore può assorbire più corrente rispetto al normale funzionamento. Per questo motivo, due gruppi di ventilatori con potenza nominale simile non costituiscono sempre un carico equivalente per il controllore.

### Ho alcuni ventilatori di piccole dimensioni. Posso collegarli in parallelo a un'unica uscita?

Sì, se:

- sono predisposti per tale modalità di controllo,
- devono funzionare insieme,
- la somma dei carichi non supera la corrente ammessa dell'uscita,
- la modalità di collegamento è conforme alla documentazione del controllore.

Con un numero maggiore di ventilatori, è opportuno valutare la suddivisione in gruppi o l'impiego di un'estensione di potenza.

### Quando è necessaria un'estensione di potenza?

L'estensione di potenza si utilizza quando il carico supera la capacità dell'uscita del controllore oppure quando l'impianto deve essere ampliato con un maggior numero di ventilatori.

In tal caso il controllore fornisce il segnale di comando, mentre il carico effettivo è gestito da un modulo aggiuntivo.

### È possibile ampliare successivamente l'impianto con ventilatori aggiuntivi?

In molti impianti sì. Le soluzioni più comuni sono:

- un'estensione di potenza aggiuntiva,
- un gruppo di ventilazione aggiuntivo,
- un contattore che inserisce un gruppo successivo,
- un inverter nel caso di motori trifase.

È preferibile prevedere l'ampliamento programmato già in fase di prima selezione del controllore.

### Tutti i ventilatori devono funzionare con regolazione continua?

No. Sono tipiche due soluzioni:

1. tutti i ventilatori funzionano con regolazione continua,
2. il primo gruppo funziona con regolazione continua, mentre i gruppi successivi vengono inseriti gradualmente, ad esempio tramite contattori.

La seconda soluzione consente di gestire un impianto più grande senza regolazione continua di ogni singolo ventilatore.

### Ho 10 ventilatori. Ho bisogno di un controllore molto grande?

Non sempre. Si possono utilizzare diversi metodi di controllo:

- suddivisione in gruppi,
- estensioni di potenza,
- contattori,
- inverter.

La selezione finale dipende dai parametri elettrici dei ventilatori e dal fatto che tutti debbano variare la velocità contemporaneamente.

### Il controllore 6 A ed 12 A si differenziano solo per il carico ammissibile?

Non si deve presumere che l'unica differenza sia il valore di corrente. Le singole versioni e generazioni dei dispositivi possono differire per dotazione o realizzazione.

Quando si sostituisce un dispositivo, occorre verificare il modello esatto e la documentazione aggiornata.


## Ventilatori e controllo della ventilazione

### Il controllore regola i ventilatori in modo continuo?

Nei controllori destinati alla regolazione continua della ventilazione, la velocità dei ventilatori varia in funzione della richiesta, determinata tra l'altro dalla temperatura.

Occorre tuttavia verificare che il tipo di motore in questione sia idoneo al metodo di regolazione utilizzato.

### Che cosa significa temperatura impostata?

La temperatura impostata è il valore rispetto al quale il controllore confronta la misurazione attuale della temperatura.

Su questa base il controllore aumenta o riduce l'intensità della ventilazione in funzione delle altre impostazioni, ad esempio banda di regolazione, livello minimo e massimo.

### Che cosa significa livello minimo di ventilazione?

È il valore minimo di comando del ventilatore durante il funzionamento automatico.

Questa impostazione impedisce il funzionamento al di sotto del livello al quale il ventilatore potrebbe lavorare in modo instabile o garantire un ricambio d'aria insufficiente.

### Che cosa significa livello massimo di ventilazione?

È il limite superiore del valore di comando della ventilazione.

Ad esempio, impostare un valore inferiore a 100% può limitare la velocità massima del ventilatore, se richiesto dall'impianto.

### Che cosa significa banda di ventilazione?

La banda di ventilazione definisce l'intervallo di temperatura nel quale il controllore passa dal livello minimo al livello massimo di ventilazione.

Quanto più stretta è la banda, tanto più rapidamente il controllo reagisce con un aumento della capacità a una variazione di temperatura.

### Dopo l'avvio, il ventilatore raggiunge prima 100% e solo successivamente rallenta. Perché?

Potrebbe essere attiva una funzione di avviamento il cui scopo è avviare temporaneamente il motore con maggiore potenza.

A seconda della versione del controllore, occorre verificare le impostazioni relative a:

- funzione Soft Start,
- tempo di accelerazione,
- tempo di funzionamento a 100%,
- tempo di decelerazione.

Se la funzione non è necessaria in un determinato impianto, i relativi parametri possono essere modificati secondo il manuale del dispositivo.

### Perché il ventilatore all'avvio può essere temporaneamente avviato a piena potenza?

Questo tipo di avviamento può favorire un avvio sicuro del ventilatore e risultare utile negli impianti in cui gli elementi meccanici possono opporre maggiore resistenza durante la partenza.

Tuttavia, non è necessario in tutti gli impianti.

### Che cosa significano il tempo di accelerazione e il tempo di decelerazione?

**Tempo di accelerazione** definisce la modalità con cui il comando aumenta durante l'avviamento del ventilatore.

**Tempo di decelerazione** definisce la modalità di riduzione della velocità.

Entrambi i parametri consentono di limitare variazioni brusche della velocità di rotazione e del funzionamento dell'impianto.

### Perché due controllori identici possono avviare i ventilatori in modo diverso?

La causa più frequente sono impostazioni differenti.

Vale la pena confrontare soprattutto:

- la temperatura impostata,
- la banda di ventilazione,
- i valori minimo e massimo,
- le impostazioni Soft Start,
- i tempi di accelerazione e decelerazione,
- la configurazione dei gruppi di ventilazione.

### Il controllore può avviare periodicamente la ventilazione indipendentemente dalla temperatura?

A seconda del modello è disponibile la funzione di aerazione periodica.

Può attivare la ventilazione per un tempo definito a intervalli prestabiliti, anche quando la regolazione in temperatura non richiede un aumento della ventilazione.

### A cosa servono i gruppi di ventilazione?

I gruppi consentono di aumentare gradualmente la capacità dell'impianto.

Ad esempio:

- il gruppo 1 funziona con regolazione continua,
- il gruppo 2 avvia i ventilatori successivi,
- il gruppo successivo si attiva in presenza di una richiesta ancora maggiore.

Ciò consente di controllare un numero elevato di ventilatori senza regolare in modo continuo ciascuno di essi.

### È possibile inserire un gruppo aggiuntivo di ventilatori tramite contattore?

Sì. L'uscita a relè del controllore può comandare la bobina di un contattore opportunamente dimensionato.

Il carico dei ventilatori non deve quindi essere instradato direttamente attraverso il piccolo contatto di comando.

### Che cosa significa il simbolo del ventilatore o la spia gialla sul controllore?

A seconda del modello, le spie indicano lo stato attuale delle uscite e delle funzioni.

L'indicazione gialla può significare una funzione operativa attiva, ad esempio il funzionamento della ventilazione, del riscaldamento o di un gruppo successivo.

Il significato esatto va verificato nel manuale del modello specifico.

### Che cosa significa il simbolo della modalità manuale?

La modalità manuale significa che il valore di comando è stato forzato dall'utente e in quel momento non viene calcolato automaticamente sulla base della temperatura.

Al termine delle prove occorre assicurarsi che il controllore sia stato ripristinato nella corretta modalità automatica.


## Prese d'aria e attuatori

### Il controllore può gestire le prese d'aria?

Sì, alcuni controllori consentono il funzionamento con gli attuatori delle prese d'aria.

La modalità di collegamento dipende dal tipo di attuatore e dal metodo di comando.

### Quali tipi di attuatori si possono usare per le prese d'aria?

Nelle discussioni tecniche ricorrevano più spesso due soluzioni:

- attuatore comandato da segnale analogico 0–10 V oppure 2–10 V,
- attuatore reversibile apri/chiudi con segnale di retroazione, ad esempio da potenziometro.

Prima dell'acquisto occorre verificare la compatibilità del modello specifico con il controllore disponibile.

### La tensione di alimentazione dell'attuatore 24 V o 230 V ha importanza per il segnale 0–10 V?

Il segnale di comando e l'alimentazione dell'attuatore sono parametri distinti.

L'attuatore può essere alimentato con una tensione diversa da quella del segnale di comando. Entrambi i parametri devono essere conformi alla documentazione dell'attuatore e del controllore.

### Che cosa significa comando 0–10 V?

Il controllore invia un segnale analogico in tensione che rappresenta la posizione richiesta o il livello di comando.

Nell'applicazione tipica un valore più basso indica un'apertura minore e un valore più alto un'apertura maggiore, ma la caratteristica effettiva deve essere verificata nella documentazione dell'attuatore.

### In che cosa si differenziano 0–10 V ed 2–10 V?

In entrambi i casi la posizione è impostata mediante segnale analogico.

Nello standard 2–10 V la parte inferiore del campo è spostata e può consentire al dispositivo di distinguere il segnale di comando dalla sua assenza.

Il controllore e l'attuatore devono supportare un intervallo compatibile.

### Come selezionare l'attuatore in funzione del numero di prese d'aria?

L'attuatore non deve essere selezionato esclusivamente in base al numero di serrande.

Occorre tenere conto di:

- la forza o la coppia richiesta,
- la lunghezza e la modalità di guida del meccanismo,
- le resistenze delle serrande,
- la corsa,
- la velocità di azionamento,
- la tensione di alimentazione,
- il tipo di comando,
- la retroazione richiesta.

### Un solo attuatore può azionare più serrande?

Sì, se la meccanica dell'impianto consente di collegare le serrande mediante un sistema comune e la coppia o la forza richiesta non supera la capacità dell'attuatore.

In pratica, la selezione è determinata dalla resistenza dell'intero meccanismo, non dal solo numero di serrande.

### È possibile collegare in parallelo più attuatori e comandarli con un solo segnale?

In alcuni sistemi è possibile, ma occorre verificare la documentazione degli attuatori e il carico ammesso dell'uscita di comando.

Nel caso di attuatori reversibili senza retroazione indipendente, può inoltre verificarsi un progressivo disallineamento delle posizioni dei singoli attuatori.

### Perché più attuatori possono disporsi nel tempo in posizioni diverse?

Anche motori identici possono funzionare a velocità leggermente diverse a causa di:

- carichi diversi,
- resistenze meccaniche,
- tolleranze dei parametri del motore,
- differenze del riduttore.

Per questo motivo, quando è richiesta una sincronizzazione precisa, sono necessari un'adeguata retroazione o un controllo individuale della posizione.

### Le prese d'aria possono essere comandate in modo proporzionale alla ventilazione?

Sì. Nei sistemi opportunamente configurati, la posizione delle prese d'aria può essere collegata al livello attuale di ventilazione.

In questo modo, all'aumentare della capacità dei ventilatori aumenta anche l'apertura delle prese d'aria.

### L'attuatore 24 V richiede un alimentatore separato?

Se il controllore non dispone di un'uscita di alimentazione adeguata con la potenza richiesta, è necessario un alimentatore separato.

La sua potenza deve essere dimensionata in base all'assorbimento di corrente dell'attuatore e degli altri dispositivi alimentati dalla stessa sorgente.

### È possibile utilizzare un attuatore di un altro produttore?

Spesso sì, se i suoi parametri elettrici e il metodo di comando sono compatibili con le uscite del controllore.

Prima del collegamento occorre verificare:

- la tensione,
- il tipo di segnale,
- lo schema dei conduttori,
- i sensi di funzionamento,
- il segnale di posizione,
- il carico ammesso.


## Sensori di temperatura e umidità

### Dove collegare il sensore di temperatura?

Il sensore deve essere collegato all'ingresso sensore previsto dal produttore, all'ingresso sensore indicato nella documentazione del modello specifico.

Non si deve presumere che le sigle dei morsetti siano identiche in tutte le versioni dei dispositivi.

### Il sensore di temperatura mostra un valore diverso rispetto al termometro campione. Cosa fare?

Se il controllore dispone della funzione di calibrazione del sensore, l'indicazione può essere corretta dopo averla confrontata con un termometro campione affidabile.

Prima di modificare la calibrazione, è opportuno verificare che:

- entrambi i sensori si trovino nello stesso punto,
- la misurazione si sia stabilizzata,
- il sensore non venga riscaldato dal sole o da dispositivi,
- non si trovi direttamente nel flusso di aria fredda o calda.

### Il sensore di umidità mostra un valore errato. È possibile calibrarlo?

Dipende dalla versione del controllore, del sensore e del software.

In alcune soluzioni, la correzione può richiedere un'apposita funzione software o un tipo di sensore compatibile. Se la differenza è elevata e ripetibile, occorre verificare la versione del dispositivo e contattare il supporto tecnico.

### Una misurazione errata indica sempre un sensore guasto?

No.

La causa può essere anche:

- una posizione non corretta del sensore,
- il cavo,
- il collegamento elettrico,
- la configurazione,
- un tipo di sensore non idoneo,
- la necessità di calibrazione,
- umidità o corrosione.


## Allarmi e notifiche

### È possibile collegare direttamente una sirena all'uscita di allarme del controllore?

Non lo si deve presumere.

L'uscita di allarme del controllore è di norma un'uscita di comando o un contatto a relè. La sirena può richiedere un'alimentazione separata e una centrale di allarme.

### Perché si utilizza una centrale di allarme?

La centrale può:

- ricevere segnali di allarme dai controllori,
- alimentare il segnalatore,
- mantenere il funzionamento in caso di interruzione dell'alimentazione,
- segnalare l'allarme tramite suono o luce,
- inviare notifiche GSM nelle versioni dotate di tale funzione.

### La centrale può segnalare la perdita di alimentazione del controllore?

Sì, se il sistema è stato collegato correttamente.

La soluzione può rilevare non solo il superamento della temperatura, ma anche la perdita del segnale proveniente dal controllore causata dall'assenza della sua alimentazione.

### Dove si impostano la temperatura minima e massima di allarme?

Nella configurazione tipica, le soglie di allarme si impostano nel controllore che gestisce la relativa camera o il relativo locale.

La centrale di allarme riceve poi l'informazione che il controllore ha segnalato un allarme.

### La centrale GSM richiede una scheda SIM?

Per inviare chiamate e messaggi tramite rete cellulare è necessaria una scheda SIM attiva o un'altra soluzione di comunicazione prevista dal modello specifico.

Senza una connessione attiva alla rete cellulare, le funzioni telefoniche e SMS non funzioneranno.

### L'allarme può inviare l'informazione da quale controllore proviene l'evento?

In un sistema opportunamente configurato sì.

Gli ingressi della centrale possono essere assegnati a locali o controllori specifici, in modo che il messaggio consenta di determinare l'origine dell'allarme.

### Quanti controllori si possono collegare a una sola centrale di allarme?

Dipende dal modello della centrale.

Nelle trascrizioni comparivano centrali che gestivano fino a otto ingressi, tuttavia prima di realizzare l'impianto occorre verificare la specifica aggiornata del dispositivo specifico.

### Quale batteria viene utilizzata nella centrale di allarme?

In alcuni dispositivi discussi nelle conversazioni veniva utilizzata una batteria 12 V 7 Ah.

Prima di acquistare una batteria sostitutiva, occorre verificare la sigla sulla batteria esistente e la specifica della centrale, poiché altre versioni dei dispositivi possono richiedere una batteria diversa.

### La centrale invia messaggi di bassa tensione. Cosa controllare?

Per prima cosa occorre controllare:

- lo stato della batteria,
- la sua anzianità,
- i collegamenti della batteria,
- la presenza dell'alimentazione di rete,
- il funzionamento del caricabatteria o dell'alimentatore della centrale.

Una batteria usurata può causare messaggi ciclici di bassa tensione.

### Con quale frequenza sostituire la batteria nella centrale di allarme?

Non esiste un unico valore adatto a tutte le condizioni.

La batteria deve essere testata periodicamente, soprattutto negli impianti in cui l'allarme in caso di interruzione dell'alimentazione ha importanza critica. Con il passare del tempo la sua capacità reale diminuisce.

### La sola sirena è sufficiente come protezione?

La sirena è utile solo se qualcuno può sentirla.

Negli impianti che rimangono temporaneamente senza sorveglianza, è opportuno utilizzare anche la notifica remota e il mantenimento a batteria.


## Inverter

### Come selezionare l'inverter per i ventilatori?

Occorre conoscere:

- la tensione di alimentazione,
- il numero di fasi,
- la potenza e la corrente di tutti i motori,
- la modalità del loro collegamento,
- le condizioni di funzionamento,
- il metodo di comando richiesto.

L'inverter deve avere un adeguato margine rispetto al carico, soprattutto quando più motori funzionano in parallelo.

### L'inverter deve avere esattamente la stessa potenza della somma delle potenze dei motori?

L'inverter non dovrebbe essere selezionato esclusivamente sulla base della semplice somma delle potenze né scegliendo un dispositivo che lavori esattamente al limite dei parametri.

Occorre tenere conto delle correnti nominali, della natura del carico e delle raccomandazioni del produttore dell'inverter.

### L'inverter ha arrestato i ventilatori e ha visualizzato un errore. Cosa fare?

La cosa più importante è annotare il codice di errore completo prima del reset.

:::tip Scattare una foto dello schermo

Se la situazione lo consente, prima del reset scattare una foto del display. Il codice di errore completo facilita notevolmente la diagnosi.

:::

Spesso l'inizio del messaggio non basta per individuare la causa. Il codice completo permette di distinguere tra l'altro:

- sovraccarico,
- sovracorrente,
- surriscaldamento,
- tensione non corretta,
- altri errori dell'azionamento.

### È possibile semplicemente resettare l'errore dell'inverter?

Il reset può ripristinare il funzionamento, ma non elimina la causa dell'allarme.

Dopo l'evento occorre verificare il codice di errore e determinarne la causa prima di rimettere in funzione l'impianto per un periodo prolungato.

### L'inverter funziona in un locale polveroso. Deve essere pulito?

Sì.

Polvere e depositi sul dissipatore o sul ventilatore di raffreddamento possono peggiorare la dissipazione del calore e portare al surriscaldamento dell'inverter.

La pulizia deve essere eseguita secondo le istruzioni del produttore, dopo aver disinserito l'alimentazione in condizioni di sicurezza.

### Che cosa può causare il surriscaldamento dell'inverter?

Le cause più frequenti sono:

- componenti di raffreddamento sporchi,
- flusso d'aria ostruito,
- temperatura ambiente troppo elevata,
- sovraccarico,
- guasto del ventilatore di raffreddamento,
- montaggio non corretto.

### Una tensione di rete elevata può provocare un allarme dell'inverter?

Sì. Gli inverter monitorano la tensione del circuito di alimentazione e possono segnalare un errore al superamento del livello consentito.

Se il problema si ripete, occorre controllare l'impianto e la qualità dell'alimentazione.


## Guasti e diagnostica

### Il controllore funziona, ma il display non mostra nulla. Quale può essere la causa?

Le possibili cause includono, tra l'altro:

- guasto del display,
- problema di regolazione del contrasto nelle soluzioni più vecchie,
- guasto del collegamento,
- corrosione,
- guasto della scheda principale.

Se il dispositivo non è stato utilizzato per lungo tempo oppure ha lavorato in un ambiente umido, vale la pena controllare anche lo stato della scheda.

### Il controllore, dopo diversi anni di inutilizzo, presenta problemi al display. Perché?

Un fermo prolungato in un ambiente umido o aggressivo può portare a:

- ossidazione dei connettori,
- corrosione,
- peggioramento dei contatti,
- guasti dei componenti elettronici.

In tal caso, è opportuno effettuare un controllo completo anziché sostituire componenti senza una diagnosi preliminare.

### Il controllore è annerito dopo una sovratensione. Significa che la scheda è da sostituire?

Non sempre.

Un componente di protezione può danneggiarsi e lasciare molti residui, anche se il resto della scheda è ancora riparabile.

Se tuttavia il laminato è carbonizzato, bruciato oppure le piste sono danneggiate, la riparazione può non essere conveniente o duratura.

### Che cosa può danneggiare più controllori contemporaneamente?

Se più dispositivi si guastano contemporaneamente, occorre controllare l'impianto di alimentazione.

Una delle possibili cause è un problema al conduttore di neutro, che in un impianto trifase può provocare tensioni non corrette sui carichi monofase.

Sono possibili anche sovratensioni provenienti dalla rete o dal gruppo elettrogeno.

### Che cosa fare dopo un guasto legato a una sovratensione?

Prima di collegare il controllore riparato o nuovo, occorre individuare la causa del problema.

:::danger Non ricollegare il dispositivo senza aver verificato l'impianto

Se la causa del guasto è stata una tensione non corretta, un conduttore di neutro danneggiato o una sovratensione, il controllore riparato o nuovo può danneggiarsi nuovamente.

:::

### Che cos'è il componente di protezione contro le sovratensioni sulla scheda?

Nei dispositivi elettronici si utilizzano componenti limitatori di sovratensione, ad esempio varistori.

Il loro compito è assorbire parte dell'energia della sovratensione e proteggere i circuiti successivi. Dopo un evento grave, un tale componente può subire un guasto permanente.

### È possibile avviare il dispositivo dopo aver rimosso il componente di protezione bruciato?

Non si deve considerare questo come una normale riparazione.

Dopo la rimozione della protezione, il dispositivo può perdere la protezione contro una successiva sovratensione. Tali operazioni possono essere eseguite esclusivamente come procedura di assistenza consapevole da una persona con qualifiche adeguate e dopo avere eliminato la causa primaria del guasto.

### Il controllore è stato allagato oppure è fortemente corroso. Vale la pena ripararlo?

Dipende dall'entità del danno.

La corrosione superficiale e singoli danni spesso possono essere rimossi. Se la corrosione ha interessato piste, connettori e molti componenti, la riparazione può richiedere molto tempo, essere incerta e non economicamente giustificata.

### Il lavaggio del dispositivo ad alta pressione può danneggiare il controllore?

Sì.

L'elettronica non dovrebbe essere esposta direttamente all'acqua o al detergente, se l'involucro e il metodo di montaggio non sono previsti a tale scopo.

L'umidità che penetra all'interno può provocare corrosione e guasti successivi difficili da diagnosticare.

### Perché i guasti dopo un allagamento possono ripresentarsi dopo la riparazione?

La corrosione può progredire anche in punti non visibili durante il primo controllo.

Via, piste e collegamenti danneggiati possono funzionare durante il test e successivamente perdere di nuovo il contatto.

Per questo motivo, in caso di scheda fortemente corrosa, l'assistenza può consigliare la sostituzione anziché ulteriori riparazioni.

### Il dispositivo a volte funziona e a volte no. Da dove iniziare?

Prima di contattare l'assistenza è opportuno raccogliere:

- il modello esatto,
- la descrizione del sintomo,
- il momento in cui si verifica,
- i valori visualizzati sullo schermo,
- il codice di allarme o di errore,
- le informazioni sulle ultime modifiche dell'impianto,
- una foto dell'interno e dei morsetti, se può essere eseguita in sicurezza.

Quanto più precisa è la descrizione, tanto più semplice sarà la diagnosi.


## Assistenza e riparazioni

### Che cosa inviare all'assistenza se il controllore è guasto?

È preferibile inviare un insieme completo che consenta di riprodurre il problema.

Alla spedizione va allegata una breve descrizione:

- che cosa non funziona,
- quando si presenta il problema,
- se il guasto è permanente o intermittente,
- se prima del guasto si sono verificati una sovratensione, un allagamento o un altro evento,
- i dati necessari per il contatto e la restituzione del dispositivo.

:::note Dati per la richiesta di assistenza

Comunicare i dati di contatto e di spedizione direttamente all'assistenza. Non pubblicarli in segnalazioni aperte o materiali pubblici.

:::

### È necessario inviare l'intero controllore o solo la scheda?

Dipende dal guasto.

In caso di problemi con display, pulsanti, alimentazione o comportamento non univoco, è preferibile inviare l'intero set necessario a riprodurre il sintomo.

Per una riparazione di uno specifico modulo concordata in precedenza, l'assistenza può richiedere solo la scheda.

### ELETOR ripara i controllori invece di sostituirli subito?

Dalle trascrizioni risulta che i dispositivi vengono prima diagnosticati.

Se la riparazione è possibile e giustificata, vengono sostituiti gli elementi o i moduli danneggiati. In caso di danni gravi, l'assistenza può proporre la sostituzione della scheda o dell'intero dispositivo.

### Che cosa succede se la scheda danneggiata non può essere riparata?

È possibile sostituire il modulo danneggiato con uno nuovo, purché il componente corrispondente sia disponibile e compatibile con il dispositivo.

Nei dispositivi più vecchi, l'assistenza dovrebbe prima confermare la compatibilità della versione.

### Vale la pena acquistare subito una nuova scheda dopo una sovratensione?

Non sempre.

Se il danno riguarda un componente di protezione o una piccola parte del circuito, la riparazione può essere giustificata. Conviene prima eseguire una diagnosi.

### L'assistenza può verificare anche il display e i pulsanti?

Sì, se gli elementi vengono forniti insieme al dispositivo o al modulo.

Questo è particolarmente utile quando non è chiaro se il problema si trovi sulla scheda principale o nel pannello utente.

### Vale sempre la pena recuperare un controllore fortemente corroso?

No.

Se il costo della diagnosi e della riparazione aumenta, mentre l'affidabilità dopo la riparazione resta incerta, la sostituzione può essere più ragionevole.

Ciò vale in particolare per i dispositivi da cui dipende la ventilazione dell'edificio.

### Come accelerare la diagnosi di assistenza?

Allegare una descrizione precisa del sintomo invece della sola affermazione «non funziona».

Sono utili anche:

- foto,
- il codice di errore,
- la descrizione dell'impianto,
- il tipo di carichi collegati,
- l'informazione su una sovratensione o un'interruzione dell'alimentazione,
- l'informazione su un allagamento o sul lavaggio del dispositivo.


## Installazione e cablaggio

### Come collegare i dispositivi ai morsetti del relè C e NO?

C ed NO sono sigle tipiche di un contatto a relè:

- C — contatto comune,
- NO — contatto normalmente aperto.

La modalità di utilizzo dipende dal dispositivo e dallo schema dell'impianto. Il contatto può essere usato ad esempio per comandare la bobina di un contattore, ma non si devono superare i suoi parametri ammessi.

:::warning Lavori elettrici

I collegamenti alla tensione di rete devono essere eseguiti da una persona con adeguate qualifiche, in conformità allo schema del dispositivo specifico.

:::

### L'uscita a relè può alimentare direttamente un ventilatore di grandi dimensioni?

Di norma non si tratta di un impiego corretto di una piccola uscita di comando.

Per carichi maggiori si utilizzano un contattore, un relè di potenza o un modulo attuatore dedicato.

### A che cosa servono i morsetti A1 ed A2 del contattore?

Sono i morsetti della bobina del contattore.

Applicando alla bobina la tensione corretta, il contattore cambia lo stato dei suoi contatti di potenza.

La tensione della bobina deve essere conforme al progetto dell'impianto e alla documentazione del contattore.

### È possibile montare apparecchi aggiuntivi all'interno dell'involucro del controllore?

Solo se la struttura dell'involucro specifico lo consente e ciò non peggiora:

- il grado di protezione,
- l'isolamento,
- il raffreddamento,
- la sicurezza,
- l'accesso per l'assistenza.

Eventuali nuovi fori devono essere realizzati in modo da mantenere il grado di tenuta richiesto.

### Gli interruttori aggiuntivi dei ventilatori sono utili?

Possono facilitare l'assistenza e consentire l'esclusione indipendente dei singoli ventilatori.

Tuttavia, la modalità di realizzazione deve tenere conto delle protezioni elettriche e non può provocare stati pericolosi del controllore.

### È possibile posare i cavi di comando insieme ai cavi di potenza?

Occorre evitare di posare cavi di segnale sensibili in parallelo e molto vicino a cavi di elevata potenza, in particolare su lunghe distanze.

I requisiti dipendono dal tipo di segnale e dall'ambiente elettromagnetico.

### Quale cavo utilizzare per i collegamenti di rete e i dispositivi PoE?

Nelle installazioni discusse, come minimo veniva indicato un cavo a coppie ritorte di categoria 5e.

Se il cavo passa in un ambiente con livello elevato di disturbi o rischio di cariche elettrostatiche, può essere opportuno utilizzare un cavo adeguatamente schermato e un corretto sistema di messa a terra.

### Per PoE è necessario un cavo incrociato?

Negli impianti tipici si utilizza un collegamento diretto standard.

Tuttavia, occorre sempre verificare i requisiti del dispositivo di rete e dell'alimentatore PoE utilizzato.


## Esercizio e manutenzione

### Come ridurre il rischio di guasti dei controllori negli edifici agricoli?

La cosa più importante è limitare l'influenza di:

- umidità,
- ammoniaca e ambiente aggressivo,
- polvere,
- lavaggio diretto con acqua,
- sovratensioni,
- alimentazione non corretta.

Vale inoltre la pena controllare periodicamente lo stato dei cavi, dei collegamenti e degli involucri.

### I dispositivi elettronici devono essere puliti regolarmente?

Sì, in particolare i dispositivi dotati di dissipatori, ventilatori e aperture di ventilazione.

La polvere accumulata peggiora il raffreddamento.

La pulizia deve essere eseguita dopo aver scollegato l'alimentazione e secondo le istruzioni del dispositivo.

### Dopo alcuni anni di funzionamento vale la pena eseguire un controllo del controllore?

Sì, soprattutto in condizioni ambientali difficili.

Il controllo può comprendere:

- la valutazione dello stato dei connettori,
- il controllo delle tracce di umidità e corrosione,
- la verifica dei componenti di raffreddamento,
- la verifica del pannello e dei pulsanti,
- il test dei sensori,
- il controllo delle batterie nei sistemi di allarme.

### Che cosa vale la pena annotare dopo il verificarsi di un guasto?

Le informazioni più utili sono:

- il messaggio completo,
- il codice di errore,
- l'ora dell'evento,
- la temperatura,
- lo stato della ventilazione,
- l'informazione sull'interruzione dell'alimentazione,
- l'informazione sul funzionamento del gruppo elettrogeno,
- una foto dello schermo o del dispositivo.

Il dispositivo non deve essere resettato prima di annotare il codice, se la situazione consente di farlo in sicurezza.

### Vale la pena disporre di un allarme indipendente dal controllore di ventilazione?

Sì, soprattutto nei casi in cui un guasto della ventilazione può portare rapidamente a condizioni pericolose.

Una centrale indipendente con propria batteria e notifica remota fornisce un ulteriore livello di protezione.

### Quali informazioni preparare prima di contattare il supporto tecnico?

È preferibile preparare:

1. il modello esatto del dispositivo,
2. la descrizione dell'impianto,
3. il numero e i parametri dei dispositivi collegati,
4. le impostazioni attuali relative al problema,
5. il sintomo esatto,
6. il codice completo di errore o di allarme,
7. le foto del dispositivo e delle targhette dati,
8. l'informazione sulle ultime modifiche dell'impianto.

Ciò consente di ridurre notevolmente i tempi di diagnosi.


## Nota importante relativa ai dispositivi più vecchi

I nomi, le sigle dei morsetti e le funzioni disponibili possono variare tra le versioni dei dispositivi prodotte in anni diversi.

Se il dispositivo ha diversi o più di dieci anni, prima di applicare le istruzioni di un modello più recente occorre confermare:

- la sigla esatta del dispositivo,
- la versione della scheda,
- il tipo di display,
- la versione del software,
- lo schema dei morsetti.

:::warning Versioni precedenti dei dispositivi

Non presumere una piena compatibilità basandosi soltanto sull'aspetto simile dell'involucro. Prima di utilizzare uno schema o un'istruzione, confermare il modello esatto e la versione del dispositivo.

:::


## Contatto con il supporto tecnico

Se le FAQ non risolvono il problema, prima del contatto preparare:

- una foto del controllore,
- una foto della targhetta dati del carico,
- i parametri dei motori o degli attuatori,
- lo schema dei collegamenti,
- una descrizione precisa della modalità di funzionamento attesa.

In questo modo la selezione del dispositivo o la diagnosi del problema possono essere effettuate sulla base dei parametri reali dell'impianto, e non di supposizioni.
