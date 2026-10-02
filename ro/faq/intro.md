---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Cele mai frecvente întrebări privind alegerea, configurarea, diagnosticarea
  și service-ul dispozitivelor ELETOR.
keywords:
- ELETOR
- FAQ
- controlere de ventilație
- regulatoare
- ventilatoare
- actuatoare
- alarme
- invertoare de frecvență
- service
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Întrebări frecvente

Documentul FAQ a fost elaborat pe baza unei analize anonimizate a conversațiilor reale cu utilizatorii și clienții ELETOR. Răspunsurile au fost generalizate astfel încât să ajute în cazurile tipice și să nu conțină date ale unor persoane sau instalații concrete.

:::note Domeniul de aplicare al FAQ

Răspunsurile se referă la cazuri tipice. Marcajele bornelor, funcțiile și modul de conectare pot diferi între modelele și versiunile dispozitivelor. În caz de îndoială, utilizați documentația corespunzătoare produsului concret.

:::

:::warning Siguranță

Efectuați lucrările la instalația electrică în conformitate cu documentația dispozitivului și cu normele de siguranță aplicabile. Lucrările la tensiunea de rețea trebuie efectuate de o persoană care deține calificările corespunzătoare.

:::

## Alegerea controlerului și a puterii

### Cum se alege un controler pentru ventilatoare?

Baza alegerii este în primul rând curentul total al ventilatoarelor, nu doar numărul lor.

:::tip Pregătiți datele înainte de alegere

Cu cât datele despre motoare și modul de funcționare al instalației sunt mai exacte, cu atât alegerea controlerului este mai sigură.

:::

Înainte de alegere, merită să pregătiți:

- numărul ventilatoarelor,
- tensiunea de alimentare,
- puterea sau curentul nominal al fiecărui ventilator,
- informația dacă toate ventilatoarele trebuie să funcționeze cu reglare continuă,
- informația dacă ventilatoarele pot fi împărțite pe grupuri,
- informații despre dispozitive suplimentare, de ex. încălzitoare sau admisii de aer.

Controlerul nu trebuie ales exact „la limită”. Trebuie menținută o rezervă corespunzătoare față de sarcina maximă.

### Este suficient să se însumeze puterea ventilatoarelor în wați?

Pentru o estimare preliminară se poate folosi puterea, însă alegerea finală trebuie să se bazeze pe curentul nominal al echipamentelor și pe caracterul sarcinii.

Motorul poate consuma la pornire mai mult curent decât în timpul funcționării normale. Din acest motiv, două seturi de ventilatoare cu putere nominală similară nu reprezintă întotdeauna sarcini echivalente pentru controler.

### Am câteva ventilatoare mici. Le pot conecta în paralel la o singură ieșire?

Da, dacă:

- sunt destinate acestui mod de comandă,
- trebuie să funcționeze împreună,
- suma sarcinilor nu depășește curentul admis al ieșirii,
- modul de conectare este conform cu documentația controlerului.

Pentru un număr mai mare de ventilatoare, merită luată în considerare împărțirea pe grupuri sau utilizarea unei extensii de putere.

### Când este necesară o extensie de putere?

Extensia de putere se utilizează atunci când sarcina depășește capacitățile ieșirii controlerului sau când instalația urmează să fie extinsă cu un număr mai mare de ventilatoare.

Controlerul transmite atunci semnalul de comandă, iar sarcina propriu-zisă este preluată de un modul suplimentar.

### Instalația poate fi extinsă ulterior cu ventilatoare suplimentare?

În multe instalații, da. Cel mai des se utilizează:

- extensie de putere suplimentară,
- grupă de ventilație suplimentară,
- un contactor care conectează următoarea grupă,
- invertor de frecvență în cazul motoarelor trifazate.

Cel mai bine este să prevedeți extinderea planificată încă de la prima alegere a controlerului.

### Toate ventilatoarele trebuie să funcționeze cu reglare continuă?

Nu. Două soluții sunt tipice:

1. toate ventilatoarele funcționează cu reglare continuă,
2. prima grupă funcționează cu reglare continuă, iar grupele următoare sunt conectate treptat, de ex. prin contactoare.

A doua soluție permite deservirea unei instalații mai mari fără reglarea continuă a fiecărui ventilator.

### Am 10 ventilatoare. Am nevoie de un controler foarte mare?

Nu întotdeauna. Se pot aplica mai multe modalități de comandă:

- împărțirea pe grupuri,
- extensii de putere,
- contactoare,
- invertor de frecvență.

Alegerea finală depinde de parametrii electrici ai ventilatoarelor și de faptul dacă toate trebuie să își schimbe turația simultan.

### Controlerul 6 A și 12 A diferă doar prin sarcina admisă?

Nu trebuie presupus că singura diferență este valoarea curentului. Diferitele versiuni și generații ale dispozitivelor pot diferi prin dotare sau modul de execuție.

La înlocuirea dispozitivului trebuie verificate modelul exact și documentația actuală.


## Ventilatoare și comanda ventilației

### Controlerul reglează ventilatoarele continuu?

În controlerele destinate reglării continue a ventilației, viteza ventilatoarelor este modificată în funcție de necesar, rezultat inclusiv din temperatură.

Totuși, trebuie verificat dacă tipul respectiv de motor este adecvat pentru metoda de reglare utilizată.

### Ce înseamnă temperatura setată?

Temperatura setată este valoarea la care controlerul raportează măsurarea curentă a temperaturii.

Pe baza acesteia, controlerul mărește sau reduce intensitatea ventilației în conformitate cu celelalte setări, de ex. banda de reglare, nivelul minim și maxim.

### Ce înseamnă nivelul minim de ventilație?

Este valoarea minimă a comenzii ventilatorului în timpul funcționării automate.

Această setare previne funcționarea sub nivelul la care ventilatorul ar putea funcționa instabil sau ar asigura un schimb de aer prea mic.

### Ce înseamnă nivelul maxim de ventilație?

Este limita superioară a valorii de comandă a ventilației.

De exemplu, setarea unei valori sub 100% poate limita turația maximă a ventilatorului, dacă instalația o impune.

### Ce înseamnă banda de ventilație?

Banda de ventilație definește intervalul de temperatură în care controlerul trece de la nivelul minim la cel maxim de ventilație.

Cu cât banda este mai mică, cu atât comanda reacționează mai rapid prin creșterea debitului la schimbarea temperaturii.

### Ventilatorul, după pornire, urcă mai întâi la 100% și abia apoi încetinește. De ce?

Poate fi activă funcția de pornire, al cărei rol este să pornească temporar motorul cu o putere mai mare.

În funcție de versiunea controlerului, trebuie verificate setările legate de:

- funcția Soft Start,
- timpul de accelerare,
- timpul de funcționare la 100%,
- timpul de decelerare.

Dacă funcția nu este necesară în instalația respectivă, parametrii corespunzători pot fi modificați conform instrucțiunii dispozitivului.

### De ce ventilatorul poate fi pornit temporar la putere maximă la start?

O astfel de pornire poate ajuta la pornirea sigură a ventilatorului și în instalațiile în care elementele mecanice pot opune o rezistență mai mare la pornire.

Totuși, acest lucru nu este necesar în fiecare instalație.

### Ce înseamnă timpul de accelerare și timpul de decelerare?

**Timpul de accelerare** definește modul de creștere a comenzii în timpul pornirii ventilatorului.

**Timpul de decelerare** definește modul de reducere a vitezei.

Ambii parametri permit limitarea variațiilor bruște de turație și de funcționare ale instalației.

### De ce două controlere identice pot porni ventilatoarele diferit?

Cea mai frecventă cauză o reprezintă setările diferite.

Merită comparate în primul rând:

- temperatura setată,
- banda de ventilație,
- minimul și maximul,
- setările Soft Start,
- timpii de accelerare și decelerare,
- configurația grupelor de ventilație.

### Controlerul poate porni periodic ventilația independent de temperatură?

În funcție de model, este disponibilă funcția de ventilare periodică.

Aceasta poate porni ventilația pentru un timp determinat, la intervale stabilite, chiar dacă reglarea în funcție de temperatură nu necesită creșterea ventilației.

### La ce folosesc grupele de ventilație?

Grupele permit creșterea treptată a capacității instalației.

De exemplu:

- grupa 1 funcționează cu reglare continuă,
- grupa 2 pornește ventilatoarele următoare,
- următoarea grupă pornește la o cerere și mai mare.

Acest lucru permite comandarea unui număr mare de ventilatoare fără reglarea continuă a fiecăruia dintre ele.

### O grupă suplimentară de ventilatoare poate fi cuplată prin contactor?

Da. Ieșirea cu releu a controlerului poate comanda bobina unui contactor ales corespunzător.

În acest caz, sarcina ventilatoarelor nu trebuie trecută direct prin contactul mic de comandă.

### Ce înseamnă simbolul ventilatorului sau indicatorul galben de pe controler?

În funcție de model, indicatoarele semnalizează starea curentă a ieșirilor și funcțiilor.

Semnalizarea galbenă poate indica o funcție de lucru activă, de ex. funcționarea ventilației, a încălzirii sau a următoarei grupe.

Semnificația exactă trebuie verificată în instrucțiunea modelului respectiv.

### Ce înseamnă simbolul modului manual?

Modul manual înseamnă că valoarea de comandă a fost impusă de utilizator și în acel moment nu este calculată automat pe baza temperaturii.

După finalizarea testelor, trebuie să vă asigurați că controlerul a fost readus în modul automat corespunzător.


## Admisii de aer și actuatoare

### Controlerul poate comanda admisiile de aer?

Da, anumite controlere permit funcționarea împreună cu acționările admisiilor de aer.

Modul de conectare depinde de tipul actuatorului și de modul lui de comandă.

### Ce tipuri de actuatoare se pot utiliza pentru admisii?

În discuțiile tehnice au apărut cel mai des două soluții:

- actuator comandat prin semnal analogic 0–10 V sau 2–10 V,
- actuator reversibil deschidere/închidere cu semnal de reacție, de ex. de la un potențiometru.

Înainte de achiziție, trebuie verificată compatibilitatea modelului concret cu controlerul existent.

### Tensiunea de alimentare a actuatorului 24 V sau 230 V are importanță pentru semnalul 0–10 V?

Semnalul de comandă și alimentarea actuatorului sunt parametri separați.

Actuatorul poate fi alimentat la o tensiune diferită de tensiunea semnalului de comandă. Ambii parametri trebuie să fie conformi cu documentația actuatorului și a controlerului.

### Ce înseamnă comanda 0–10 V?

Controlerul trimite un semnal analogic de tensiune care reprezintă poziția solicitată sau nivelul de comandă.

În aplicația tipică, o valoare mai mică înseamnă o deschidere mai redusă, iar una mai mare o deschidere mai mare, însă caracteristica reală trebuie verificată în documentația actuatorului.

### Care este diferența dintre 0–10 V și 2–10 V?

În ambele cazuri, poziția este setată prin semnal analogic.

În standardul 2–10 V, partea inferioară a domeniului este decalată și poate permite dispozitivului să distingă semnalul de comandă de absența acestuia.

Controlerul și actuatorul trebuie să suporte același domeniu.

### Cum se alege actuatorul în funcție de numărul admisiilor?

Actuatorul nu trebuie ales exclusiv pe baza numărului de clapete.

Trebuie avute în vedere:

- forța sau cuplul necesar,
- lungimea și modul de ghidare al mecanismului,
- rezistențele clapetelor,
- lungimea cursei,
- viteza de acționare,
- tensiunea de alimentare,
- tipul de comandă,
- semnalul de reacție necesar.

### Un singur actuator poate deservi mai multe clapete?

Da, dacă mecanica instalației permite conectarea clapetelor la un mecanism comun, iar cuplul sau forța necesară nu depășește capacitățile actuatorului.

În practică, alegerea este determinată de rezistențele întregului mecanism, nu de simplul număr de clapete.

### Mai multe actuatoare pot fi conectate în paralel și comandate cu un singur semnal?

În anumite sisteme acest lucru este posibil, dar trebuie verificate documentația actuatoarelor și sarcina admisă a ieșirii de comandă.

În cazul acționărilor reversibile fără reacție independentă, poate apărea de asemenea o decalare treptată a pozițiilor actuatoarelor individuale.

### De ce mai multe actuatoare se pot poziționa în timp în poziții diferite?

Chiar și motoarele identice pot funcționa cu viteze ușor diferite din cauza:

- sarcină diferită,
- rezistențe mecanice,
- toleranței parametrilor motorului,
- diferențelor ale transmisiei.

De aceea, atunci când este necesară o sincronizare precisă, sunt necesare reacția corespunzătoare sau controlul individual al poziției.

### Admisia poate fi comandată proporțional cu ventilația?

Da. În sistemele configurate corespunzător, poziția admisiilor poate fi corelată cu nivelul actual de ventilație.

Astfel, odată cu creșterea debitului ventilatoarelor, este mărită și deschiderea admisiilor.

### Actuatorul 24 V necesită o sursă de alimentare separată?

Dacă controlerul nu dispune de o ieșire de alimentare adecvată, cu puterea necesară, este necesară o sursă de alimentare separată.

Puterea acesteia trebuie aleasă în funcție de consumul de curent al actuatorului și al altor dispozitive alimentate din aceeași sursă.

### Se poate utiliza un actuator al altui producător?

Adesea da, dacă parametrii săi electrici și modul de comandă sunt compatibile cu ieșirile controlerului.

Înainte de conectare, trebuie verificate:

- tensiunea,
- tipul semnalului,
- schema conductoarelor,
- sensurile de funcționare,
- semnalul de poziție,
- sarcina admisă.


## Senzori de temperatură și umiditate

### Unde se conectează senzorul de temperatură?

Senzorul trebuie conectat la intrarea pentru senzor prevăzută de producător, la intrarea pentru senzor indicată în documentația modelului respectiv.

Nu trebuie presupus că marcajele bornelor sunt identice în toate versiunile dispozitivelor.

### Senzorul de temperatură indică o valoare diferită de cea a termometrului de referință. Ce trebuie făcut?

Dacă controlerul dispune de funcția de calibrare a senzorului, indicația poate fi corectată după compararea acesteia cu un termometru de referință fiabil.

Înainte de modificarea calibrării, merită să vă asigurați că:

- ambii senzori se află în același loc,
- măsurarea s-a stabilizat,
- senzorul nu este încălzit de soare sau de echipamente,
- nu se află direct în fluxul de aer rece sau cald.

### Senzorul de umiditate indică o valoare incorectă. Poate fi calibrat?

Acest lucru depinde de versiunea controlerului, a senzorului și a software-ului.

În unele soluții, corecția poate necesita o funcție software corespunzătoare sau un tip de senzor compatibil. Dacă diferența este mare și repetabilă, trebuie verificată versiunea dispozitivului și contactat suportul tehnic.

### O măsurare eronată înseamnă întotdeauna un senzor defect?

Nu.

Cauza poate fi și:

- amplasarea necorespunzătoare a senzorului,
- conductorul,
- conexiunea electrică,
- configurația,
- tipul necorespunzător de senzor,
- necesitatea calibrării,
- umezeala sau coroziunea.


## Alarme și notificări

### O sirenă poate fi conectată direct la ieșirea de alarmă a controlerului?

Nu trebuie presupus acest lucru.

Ieșirea de alarmă a controlerului este de obicei o ieșire de comandă sau un contact de releu. Sirena poate necesita o alimentare separată și o centrală de alarmă.

### La ce se utilizează centrala de alarmă?

Centrala poate:

- primi semnale de alarmă de la controlere,
- alimenta semnalizatorul,
- menține funcționarea în timpul întreruperii alimentării,
- semnaliza alarma acustic sau luminos,
- trimite notificări GSM în versiunile care dispun de această funcție.

### Centrala poate alarma în cazul pierderii alimentării controlerului?

Da, dacă sistemul a fost conectat corespunzător.

Soluția poate detecta nu doar depășirea temperaturii, ci și pierderea semnalului de la controler cauzată de întreruperea alimentării acestuia.

### Unde se setează temperatura minimă și maximă de alarmă?

În configurația tipică, pragurile de alarmă se setează în controlerul care deservește camera sau încăperea respectivă.

Centrala de alarmă primește apoi informația că controlerul a semnalat o alarmă.

### Centrala GSM necesită cartelă SIM?

Pentru trimiterea apelurilor și mesajelor prin rețeaua celulară este necesară o cartelă SIM activă sau o altă soluție de comunicație prevăzută pentru modelul respectiv.

Fără o conexiune activă la rețeaua celulară, funcțiile telefonice și SMS nu vor funcționa.

### Alarma poate transmite informația din care controler provine evenimentul?

Într-un sistem configurat corespunzător, da.

Intrările centralei pot fi atribuite unor încăperi sau controlere concrete, astfel încât mesajul să permită identificarea sursei alarmei.

### Câte controlere pot fi conectate la o singură centrală de alarmă?

Depinde de modelul centralei.

În transcrieri au apărut centrale care suportă până la opt intrări, însă înainte de realizarea instalației trebuie verificată specificația actuală a dispozitivului concret.

### Ce acumulator se utilizează în centrala de alarmă?

În unele dintre dispozitivele discutate în conversații se utiliza un acumulator 12 V 7 Ah.

Înainte de achiziționarea unui înlocuitor, trebuie verificat marcajul de pe acumulatorul existent și specificația centralei, deoarece alte versiuni ale dispozitivelor pot necesita un alt acumulator.

### Centrala trimite mesaje privind tensiunea scăzută. Ce trebuie verificat?

În primul rând, trebuie verificate:

- starea acumulatorului,
- vechimea acestuia,
- conexiunile acumulatorului,
- prezența alimentării de rețea,
- funcționarea încărcătorului sau a sursei de alimentare a centralei.

Un acumulator uzat poate provoca mesaje ciclice privind tensiunea scăzută.

### Cât de des trebuie înlocuit acumulatorul din centrala de alarmă?

Nu există o valoare unică potrivită pentru toate condițiile.

Acumulatorul trebuie testat periodic, în special în instalațiile în care alarma la întreruperea alimentării are importanță critică. Odată cu vârsta, capacitatea sa reală scade.

### Este suficientă doar sirena ca protecție?

Sirena este utilă doar atunci când există cineva care o poate auzi.

În obiectivele rămase temporar fără supraveghere, merită utilizate și notificarea la distanță, precum și alimentarea de rezervă cu acumulator.


## Invertoare de frecvență

### Cum se alege un invertor de frecvență pentru ventilatoare?

Trebuie cunoscute:

- tensiunea de alimentare,
- numărul de faze,
- puterea și curentul tuturor motoarelor,
- modul de conectare a acestora,
- condițiile de funcționare,
- modul de comandă necesar.

Invertorul de frecvență trebuie să aibă o rezervă corespunzătoare față de sarcină, în special când mai multe motoare funcționează în paralel.

### Invertorul de frecvență ar trebui să aibă exact aceeași putere ca suma puterilor motoarelor?

Invertorul de frecvență nu trebuie ales exclusiv pe baza unei însumări simple a puterilor și nu trebuie selectat un dispozitiv care funcționează exact la limita parametrilor.

Trebuie luați în considerare curenții nominali, caracterul sarcinii și recomandările producătorului invertorului de frecvență.

### Invertorul de frecvență a oprit ventilatoarele și a afișat o eroare. Ce trebuie făcut?

Cel mai important este să notați codul complet de eroare înainte de resetare.

:::tip Faceți o fotografie a ecranului

Dacă situația permite, înainte de resetare faceți o fotografie a afișajului. Codul complet de eroare facilitează considerabil diagnosticul.

:::

Doar începutul mesajului adesea nu este suficient pentru a stabili cauza. Codul complet permite diferențierea, printre altele, a:

- suprasarcinii,
- depășirii curentului,
- supraîncălzirii,
- tensiunii necorespunzătoare,
- altor erori ale acționării.

### Se poate pur și simplu reseta eroarea invertorului de frecvență?

Resetarea poate restabili funcționarea, dar nu înlătură cauza alarmei.

După eveniment, trebuie verificat codul de eroare și stabilită cauza înainte de repornirea de lungă durată a instalației.

### Invertorul de frecvență funcționează într-o încăpere cu praf. Trebuie curățat?

Da.

Praful și depunerile de pe radiator sau ventilatorul de răcire pot reduce disiparea căldurii și pot duce la supraîncălzirea invertorului de frecvență.

Curățarea trebuie efectuată conform instrucțiunilor producătorului, după deconectarea în siguranță a alimentării.

### Ce poate provoca supraîncălzirea invertorului de frecvență?

Cele mai frecvente cauze sunt:

- elementele de răcire murdare,
- fluxul de aer obstrucționat,
- temperatura ambientală prea ridicată,
- suprasarcina,
- defectarea ventilatorului de răcire,
- montajul necorespunzător.

### Tensiunea ridicată a rețelei poate declanșa o alarmă a invertorului de frecvență?

Da. Invertoarele de frecvență monitorizează tensiunea circuitului de alimentare și pot semnala o eroare la depășirea nivelului admis.

Dacă problema se repetă, trebuie verificate instalația și calitatea alimentării.


## Defecțiuni și diagnosticare

### Controlerul funcționează, dar afișajul nu arată nimic. Care poate fi cauza?

Cauzele posibile includ, printre altele:

- defectarea afișajului,
- problemă de reglare a contrastului în soluțiile mai vechi,
- defectarea conexiunii,
- coroziunea,
- defectarea plăcii principale.

Dacă dispozitivul nu a fost utilizat o perioadă îndelungată sau a funcționat într-un mediu umed, merită de asemenea verificată starea plăcii.

### Controlerul are o problemă cu afișajul după câțiva ani de neutilizare. De ce?

Staționarea îndelungată într-un mediu umed sau agresiv poate duce la:

- oxidarea conectorilor,
- coroziune,
- deteriorarea contactelor,
- deteriorarea componentelor electronice.

În acest caz, merită efectuată o inspecție completă, nu înlocuirea componentelor fără un diagnostic prealabil.

### Controlerul este înnegrit de fum după o supratensiune. Înseamnă aceasta că placa trebuie înlocuită?

Nu întotdeauna.

Elementul de protecție se poate deteriora și poate lăsa multe depuneri, chiar dacă restul plăcii poate fi reparat.

Dacă însă laminatul este carbonizat, ars sau traseele sunt deteriorate, reparația poate fi neeconomică sau puțin durabilă.

### Ce poate deteriora simultan mai multe controlere?

Dacă mai multe dispozitive se defectează în același timp, trebuie verificată instalația de alimentare.

Una dintre cauzele posibile este o problemă a conductorului neutru, care într-o instalație trifazată poate duce la apariția unor tensiuni necorespunzătoare la receptoarele monofazate.

Sunt posibile și supratensiuni provenite din rețea sau de la generator.

### Ce trebuie făcut după o defecțiune legată de supratensiune?

Înainte de conectarea controlerului reparat sau nou, trebuie stabilită cauza problemei.

:::danger Nu reconectați dispozitivul fără verificarea instalației

Dacă defecțiunea a fost cauzată de o tensiune necorespunzătoare, un conductor neutru deteriorat sau o supratensiune, controlerul reparat ori nou poate fi deteriorat din nou.

:::

### Ce este elementul de protecție la supratensiune de pe placă?

În dispozitivele electronice se folosesc elemente de limitare a supratensiunilor, de ex. varistoare.

Rolul lor este de a prelua o parte din energia supratensiunii și de a proteja circuitele ulterioare. După un eveniment puternic, un astfel de element se poate deteriora permanent.

### Se poate porni dispozitivul după îndepărtarea elementului de protecție ars?

Acest lucru nu trebuie considerat o reparație normală.

După îndepărtarea protecției, dispozitivul poate pierde protecția împotriva unei noi supratensiuni. Astfel de acțiuni pot fi efectuate exclusiv ca procedură de service conștientă de către o persoană cu calificările corespunzătoare și după eliminarea cauzei primare a defecțiunii.

### Controlerul a fost inundat sau a corodat puternic. Merită reparat?

Depinde de gradul deteriorărilor.

Coroziunea superficială și deteriorările izolate pot fi adesea îndepărtate. Dacă coroziunea a afectat traseele, conectorii și multe componente, reparația poate fi consumatoare de timp, incertă și nejustificată economic.

### Spălarea sub presiune a dispozitivului poate deteriora controlerul?

Da.

Electronica nu trebuie expusă direct la apă sau agent de spălare, dacă carcasa și modul de montaj nu sunt prevăzute pentru aceasta.

Umezeala care pătrunde în interior poate duce la coroziune și la defecte ulterioare greu de diagnosticat.

### De ce defectele după inundare pot reapărea după reparație?

Coroziunea poate progresa și în locuri invizibile la prima inspecție.

Trecerile metalizate, traseele și conexiunile deteriorate pot funcționa în timpul testului, iar ulterior pot pierde din nou contactul.

De aceea, în cazul unei plăci puternic corodate, service-ul poate recomanda înlocuirea în locul reparațiilor ulterioare.

### Dispozitivul uneori funcționează, alteori nu. De unde să începeți?

Înainte de a contacta service-ul, merită să pregătiți:

- modelul exact,
- descrierea simptomului,
- momentul apariției,
- valorile afișate pe ecran,
- codul de alarmă sau de eroare,
- informații despre ultimele modificări ale instalației,
- o fotografie a interiorului și a bornelor, dacă poate fi realizată în siguranță.

Cu cât descrierea este mai exactă, cu atât diagnosticul este mai ușor.


## Service și reparații

### Ce trebuie trimis la service dacă controlerul este defect?

Cel mai bine este să trimiteți ansamblul care permite reproducerea problemei.

La expediere trebuie anexată o scurtă descriere:

- ce nu funcționează,
- când apare problema,
- dacă defecțiunea este permanentă sau periodică,
- dacă înainte de defecțiune a avut loc o supratensiune, inundare sau alt eveniment,
- datele necesare pentru contact și returul dispozitivului.

:::note Date pentru solicitarea de service

Datele de contact și de expediere trebuie transmise direct către service. Nu le publicați în solicitări deschise sau în materiale publice.

:::

### Trebuie trimis întregul controler sau doar placa?

Depinde de defecțiune.

În cazul problemelor cu afișajul, butoanele, alimentarea sau al unui comportament ambiguu, cel mai bine este să trimiteți întregul set necesar pentru reproducerea simptomului.

În cazul unei reparații convenite în prealabil pentru un anumit modul, service-ul poate solicita doar placa.

### ELETOR repară controlerele în loc să le înlocuiască imediat?

Din transcrieri rezultă că dispozitivele sunt diagnosticate mai întâi.

Dacă reparația este posibilă și justificată, se înlocuiesc elementele sau modulele defecte. În cazul unei deteriorări grave, service-ul poate propune înlocuirea plăcii sau a întregului dispozitiv.

### Ce se întâmplă dacă placa defectă nu poate fi reparată?

Este posibilă înlocuirea modulului defect cu unul nou, cu condiția ca piesa corespunzătoare să fie disponibilă și compatibilă cu dispozitivul.

În cazul dispozitivelor mai vechi, service-ul ar trebui mai întâi să confirme compatibilitatea versiunii.

### Merită să cumpărați imediat o placă nouă după o supratensiune?

Nu întotdeauna.

Dacă deteriorarea privește un element de protecție sau o parte mică a circuitului, reparația poate fi justificată. Mai întâi merită efectuat un diagnostic.

### Service-ul poate verifica și afișajul și butoanele?

Da, dacă elementele sunt livrate împreună cu dispozitivul sau modulul.

Acest lucru este deosebit de util atunci când nu se știe dacă problema se află pe placa principală sau în panoul utilizatorului.

### Merită întotdeauna salvat un controler puternic corodat?

Nu.

Dacă costul diagnosticului și al reparației crește, iar fiabilitatea după reparație rămâne incertă, înlocuirea poate fi mai rezonabilă.

Acest lucru este valabil în special pentru dispozitivele de care depinde ventilația obiectivului.

### Cum se poate accelera diagnosticul de service?

Atașați o descriere exactă a simptomului în locul simplei afirmații „nu funcționează”.

Sunt utile și:

- fotografiile,
- codul de eroare,
- descrierea instalației,
- tipul consumatorilor conectați,
- informația despre supratensiune sau întreruperea alimentării,
- informația despre inundarea sau spălarea dispozitivului.


## Instalație și cablare

### Cum se conectează dispozitivele la bornele de releu C și NO?

C și NO sunt marcaje tipice ale contactului de releu:

- C — contact comun,
- NO — contact normal deschis.

Modul de utilizare depinde de dispozitiv și de schema instalației. Contactul poate fi utilizat, de ex., pentru comanda bobinei unui contactor, însă parametrii lui admiși nu trebuie depășiți.

:::warning Lucrări electrice

Conexiunile la tensiunea de rețea trebuie executate de o persoană cu calificările corespunzătoare, în conformitate cu schema dispozitivului concret.

:::

### Ieșirea cu releu poate alimenta direct un ventilator mare?

De regulă, aceasta nu este o utilizare corectă a unei mici ieșiri de comandă.

Pentru sarcini mai mari se utilizează un contactor, un releu de putere sau un modul de execuție dedicat.

### La ce servesc bornele A1 și A2 ale contactorului?

Acestea sunt bornele bobinei contactorului.

După aplicarea tensiunii corespunzătoare pe bobină, contactorul își schimbă starea contactelor de putere.

Tensiunea bobinei trebuie să fie conformă cu proiectul instalației și cu documentația contactorului.

### Se pot monta aparate suplimentare în interiorul carcasei controlerului?

Numai dacă construcția carcasei respective permite acest lucru și dacă nu se deteriorează:

- gradul de protecție,
- izolația,
- răcirea,
- siguranța,
- accesul pentru service.

Orice orificii noi trebuie executate astfel încât să fie menținută etanșeitatea necesară.

### Sunt utile întrerupătoarele suplimentare pentru ventilatoare?

Acestea pot facilita service-ul și pot permite deconectarea independentă a ventilatoarelor individuale.

Totuși, modul de execuție trebuie să țină seama de protecțiile electrice și nu poate provoca stări periculoase ale controlerului.

### Conductoarele de comandă pot fi trase împreună cu conductoarele de putere?

Trebuie evitată pozarea conductoarelor de semnal sensibile în paralel și foarte aproape de conductoarele de mare putere, în special pe distanțe lungi.

Cerințele depind de tipul semnalului și de mediul electromagnetic.

### Ce cablu trebuie utilizat pentru conexiunile de rețea și dispozitivele PoE?

În instalațiile discutate, ca minim era indicat cablul torsadat de categoria 5e.

Dacă cablul este instalat într-un mediu cu un nivel ridicat de perturbații sau cu risc de sarcini electrostatice, poate fi justificată utilizarea unui cablu ecranat corespunzător și a unui sistem corect de împământare.

### Pentru PoE este necesar un cablu crossover?

În instalațiile tipice se utilizează o conexiune directă standard.

Totuși, trebuie verificate întotdeauna cerințele dispozitivului de rețea și ale sursei PoE utilizate.


## Exploatare și întreținere

### Cum se poate limita riscul de defectare a controlerelor în clădiri agricole?

Cel mai important este limitarea influenței:

- umezelii,
- amoniacului și mediului agresiv,
- prafului,
- spălării directe cu apă,
- supratensiunilor,
- alimentării necorespunzătoare.

Merită de asemenea să se controleze periodic starea conductoarelor, conexiunilor și carcaselor.

### Dispozitivele electronice trebuie curățate regulat?

Da, în special dispozitivele echipate cu radiatoare, ventilatoare și orificii de ventilație.

Praful acumulat reduce eficiența răcirii.

Curățarea trebuie efectuată după deconectarea alimentării și conform instrucțiunii dispozitivului.

### După câțiva ani de funcționare, merită efectuată o inspecție a controlerului?

Da, în special în condiții de mediu dificile.

Inspecția poate include:

- evaluarea stării conectorilor,
- controlul urmelor de umezeală și coroziune,
- verificarea elementelor de răcire,
- verificarea panoului și a butoanelor,
- testarea senzorilor,
- verificarea acumulatorilor din sistemele de alarmă.

### Ce merită notat după apariția unei defecțiuni?

Cele mai utile sunt:

- mesajul complet,
- codul de eroare,
- ora evenimentului,
- temperatura,
- starea ventilației,
- informația privind întreruperea alimentării,
- informația privind funcționarea generatorului,
- o fotografie a ecranului sau a dispozitivului.

Dispozitivul nu trebuie resetat înainte de notarea codului, dacă situația permite acest lucru în siguranță.

### Merită să existe o alarmă independentă de controlerul de ventilație?

Da, în special acolo unde o defecțiune a ventilației poate duce rapid la condiții periculoase.

O centrală independentă, cu propriul acumulator și notificare la distanță, oferă un nivel suplimentar de protecție.

### Ce informații trebuie pregătite înainte de contactarea suportului tehnic?

Cel mai bine este să pregătiți:

1. modelul exact al dispozitivului,
2. descrierea instalației,
3. numărul și parametrii dispozitivelor conectate,
4. setările actuale legate de problemă,
5. simptomul exact,
6. codul complet de eroare sau de alarmă,
7. fotografii ale dispozitivului și ale plăcuțelor de identificare,
8. informația despre ultimele modificări ale instalației.

Acest lucru permite scurtarea considerabilă a diagnosticului.


## Notă importantă privind dispozitivele mai vechi

Denumirile, marcajele bornelor și funcțiile disponibile pot diferi între versiunile dispozitivelor fabricate în ani diferiți.

Dacă dispozitivul are câțiva sau mai mult de zece ani, înainte de utilizarea instrucțiunii unui model mai nou trebuie confirmate:

- marcajul exact al dispozitivului,
- versiunea plăcii,
- tipul afișajului,
- versiunea software-ului,
- schema bornelor.

:::warning Versiuni mai vechi ale dispozitivelor

Nu presupuneți compatibilitate totală doar pe baza aspectului similar al carcasei. Înainte de a utiliza o schemă sau o instrucțiune, confirmați modelul exact și versiunea dispozitivului.

:::


## Contact cu suportul tehnic

Dacă FAQ-ul nu rezolvă problema, pregătiți înainte de contact:

- fotografia controlerului,
- fotografia plăcuței de identificare a echipamentului,
- parametrii motoarelor sau ai actuatoarelor,
- schema conexiunilor,
- descrierea exactă a modului de funcționare așteptat.

Astfel, alegerea dispozitivului sau diagnosticul problemei poate fi realizat pe baza parametrilor reali ai instalației, nu a presupunerilor.
