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
- convertizoare de frecvență
- service
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Întrebări frecvente

FAQ a fost elaborat pe baza unei analize anonimizate a conversațiilor reale cu utilizatorii și clienții ELETOR. Răspunsurile au fost generalizate pentru a fi utile în situațiile tipice și pentru a nu conține date despre persoane sau instalații concrete.

:::note Domeniul de aplicare al FAQ

Răspunsurile se referă la situații tipice. Marcajele bornelor, funcțiile și modul de conectare pot diferi între modelele și versiunile dispozitivelor. În caz de îndoială, consultați documentația corespunzătoare produsului respectiv.

:::

:::warning Siguranță

Efectuați lucrările la instalația electrică în conformitate cu documentația dispozitivului și cu normele de siguranță în vigoare. Lucrările la tensiunea de rețea trebuie efectuate de o persoană cu calificările corespunzătoare.

:::

## Alegerea controlerului și a puterii

### Cum se alege controlerul pentru ventilatoare?

Alegerea se bazează în primul rând pe curentul total al ventilatoarelor, nu doar pe numărul acestora.

:::tip Pregătiți datele înainte de alegere

Cu cât datele despre motoare și modul de funcționare al instalației sunt mai precise, cu atât alegerea controlerului este mai sigură.

:::

Înainte de alegere, este util să pregătiți:

- numărul ventilatoarelor,
- tensiunea de alimentare,
- puterea sau curentul nominal al fiecărui ventilator,
- informația dacă toate ventilatoarele trebuie să funcționeze cu reglare continuă,
- informația dacă ventilatoarele pot fi împărțite în grupuri,
- informații despre dispozitivele suplimentare, de exemplu aeroterme sau admisii de aer.

Controlerul nu trebuie ales exact „la limită”. Trebuie păstrată o rezervă corespunzătoare față de sarcina maximă.

### Este suficient să se însumeze puterea ventilatoarelor în wați?

Puterea poate fi utilizată pentru o estimare preliminară, însă alegerea finală trebuie să se bazeze pe curentul nominal al dispozitivelor și pe natura sarcinii.

La pornire, motorul poate absorbi un curent mai mare decât în timpul funcționării normale. Din acest motiv, două ansambluri de ventilatoare cu puteri nominale similare nu reprezintă întotdeauna sarcini echivalente pentru controler.

### Am mai multe ventilatoare mici. Le pot conecta în paralel la o singură ieșire?

Da, dacă:

- sunt concepute pentru acest mod de comandă,
- trebuie să funcționeze împreună,
- suma sarcinilor nu depășește curentul admisibil al ieșirii,
- modul de conectare este conform cu documentația controlerului.

În cazul unui număr mai mare de ventilatoare, este util să se ia în considerare împărțirea în grupuri sau utilizarea unui modul de extindere a puterii.

### Când este necesară o extindere a puterii?

Extinderea puterii se utilizează atunci când sarcina depășește capacitatea ieșirii controlerului sau când instalația urmează să fie extinsă cu un număr mai mare de ventilatoare.

În acest caz, controlerul transmite semnalul de comandă, iar sarcina propriu-zisă este gestionată de un modul suplimentar.

### Instalația poate fi extinsă ulterior cu ventilatoare suplimentare?

În multe instalații, da. Cel mai frecvent se utilizează:

- un modul suplimentar de extindere a puterii,
- un grup suplimentar de ventilație,
- un contactor care conectează un alt grup,
- un convertizor de frecvență în cazul motoarelor trifazate.

Este recomandat să se prevadă extinderea planificată încă de la alegerea inițială a controlerului.

### Toate ventilatoarele trebuie să funcționeze cu reglare continuă?

Nu. Sunt uzuale două soluții:

1. toate ventilatoarele funcționează cu reglare continuă,
2. primul grup funcționează cu reglare continuă, iar grupurile următoare sunt conectate treptat, de exemplu prin contactoare.

A doua soluție permite gestionarea unei instalații mai mari fără reglarea continuă a fiecărui ventilator.

### Am 10 ventilatoare. Am nevoie de un controler foarte mare?

Nu întotdeauna. Se pot utiliza mai multe metode de comandă:

- împărțirea în grupuri,
- module de extindere a puterii,
- contactoare,
- un convertizor de frecvență.

Alegerea finală depinde de parametrii electrici ai ventilatoarelor și de necesitatea ca toate să își modifice turația simultan.

### Controlerele 6 A și 12 A diferă doar prin sarcina admisibilă?

Nu trebuie presupus că singura diferență este valoarea curentului. Diferitele versiuni și generații ale dispozitivelor pot avea dotări sau construcții diferite.

La înlocuirea dispozitivului, trebuie verificat modelul exact și documentația actuală.


## Ventilatoare și comanda ventilației

### Controlerul reglează continuu ventilatoarele?

În controlerele destinate reglării continue a ventilației, viteza ventilatoarelor este modificată în funcție de necesarul determinat, printre altele, de temperatură.

Totuși, trebuie verificat dacă tipul respectiv de motor este adecvat pentru metoda de reglare utilizată.

### Ce înseamnă temperatura setată?

Temperatura setată este valoarea la care controlerul raportează măsurarea curentă a temperaturii.

Pe baza acesteia, controlerul mărește sau reduce intensitatea ventilației în conformitate cu celelalte setări, de exemplu banda de reglare, nivelul minim și cel maxim.

### Ce înseamnă nivelul minim de ventilație?

Este valoarea minimă a comenzii ventilatorului în timpul funcționării automate.

Setarea împiedică funcționarea sub nivelul la care ventilatorul ar putea funcționa instabil sau ar asigura un schimb de aer prea redus.

### Ce înseamnă nivelul maxim de ventilație?

Este limita superioară a valorii comenzii ventilației.

De exemplu, setarea unei valori sub 100% poate limita turația maximă a ventilatorului, dacă instalația impune acest lucru.

### Ce înseamnă banda de ventilație?

Banda de ventilație definește intervalul de temperatură în care controlerul trece de la nivelul minim la nivelul maxim de ventilație.

Cu cât banda este mai îngustă, cu atât comanda reacționează mai rapid la schimbarea temperaturii prin creșterea debitului.

### După pornire, ventilatorul ajunge mai întâi la 100% și abia apoi încetinește. De ce?

Poate fi activă funcția de pornire, al cărei rol este pornirea temporară a motorului la o putere mai mare.

În funcție de versiunea controlerului, trebuie verificate setările referitoare la:

- funcția Soft Start,
- timpul de accelerare,
- timpul de funcționare la 100%,
- timpul de decelerare.

Dacă funcția nu este necesară în instalația respectivă, parametrii corespunzători pot fi modificați în conformitate cu instrucțiunile dispozitivului.

### De ce poate fi pornit temporar ventilatorul la putere maximă?

O astfel de pornire poate contribui la pornirea sigură a ventilatorului și poate fi utilă în instalațiile în care elementele mecanice pot opune o rezistență mai mare la pornire.

Totuși, acest lucru nu este necesar în toate instalațiile.

### Ce înseamnă timpul de accelerare și timpul de decelerare?

**Timpul de accelerare** definește modul în care crește comanda în timpul pornirii ventilatorului.

**Timpul de decelerare** definește modul în care se reduce viteza.

Ambii parametri permit limitarea modificărilor bruște ale turației și ale funcționării instalației.

### De ce pot două controlere identice să pornească ventilatoarele diferit?

Cea mai frecventă cauză o reprezintă setările diferite.

Este util să se compare în primul rând:

- temperatura setată,
- banda de ventilație,
- minimul și maximul,
- setările Soft Start,
- timpii de accelerare și decelerare,
- configurația grupurilor de ventilație.

### Controlerul poate porni periodic ventilația independent de temperatură?

În funcție de model, este disponibilă funcția de aerisire periodică.

Aceasta poate porni ventilația pentru o durată determinată, la intervale setate, chiar și atunci când reglarea în funcție de temperatură nu necesită intensificarea ventilației.

### La ce servesc grupurile de ventilație?

Grupurile permit creșterea treptată a capacității instalației.

De exemplu:

- grupul 1 funcționează cu reglare continuă,
- grupul 2 pornește ventilatoare suplimentare,
- grupul următor pornește la un necesar și mai mare.

Acest lucru permite comanda unui număr mare de ventilatoare fără reglarea continuă a fiecăruia.

### Un grup suplimentar de ventilatoare poate fi conectat printr-un contactor?

Da. Ieșirea cu releu a controlerului poate comanda bobina unui contactor ales corespunzător.

În acest caz, sarcina ventilatoarelor nu trebuie să treacă direct prin contactul mic de comandă.

### Ce înseamnă simbolul ventilatorului sau indicatorul luminos galben de pe controler?

În funcție de model, indicatoarele luminoase informează despre starea curentă a ieșirilor și a funcțiilor.

Semnalizarea galbenă poate indica o funcție de lucru activă, de exemplu funcționarea ventilației, a încălzirii sau a unui alt grup.

Semnificația exactă trebuie verificată în instrucțiunile modelului respectiv.

### Ce înseamnă simbolul modului manual?

Modul manual înseamnă că valoarea comenzii a fost impusă de utilizator și nu este calculată automat, în acel moment, pe baza temperaturii.

După încheierea testelor, trebuie să vă asigurați că a fost restabilit modul automat corespunzător al controlerului.


## Admisii de aer și actuatoare

### Controlerul poate comanda admisiile de aer?

Da, anumite controlere permit funcționarea împreună cu mecanismele de acționare ale admisiilor de aer.

Modul de conectare depinde de tipul actuatorului și de modul de comandă al acestuia.

### Ce tipuri de actuatoare pot fi utilizate pentru admisii?

În conversațiile tehnice au apărut cel mai frecvent două soluții:

- actuator comandat prin semnal analogic 0–10 V sau 2–10 V,
- actuator reversibil deschidere/închidere cu semnal de reacție, de exemplu de la un potențiometru.

Înainte de achiziție, trebuie verificată compatibilitatea modelului respectiv cu controlerul deținut.

### Tensiunea de alimentare a actuatorului 24 V sau 230 V are importanță pentru semnalul 0–10 V?

Semnalul de comandă și alimentarea actuatorului sunt parametri separați.

Actuatorul poate fi alimentat la o tensiune diferită de tensiunea semnalului de comandă. Ambii parametri trebuie să fie conformi cu documentația actuatorului și a controlerului.

### Ce înseamnă comanda 0–10 V?

Controlerul transmite un semnal analogic de tensiune care reprezintă poziția dorită sau nivelul comenzii.

Într-o aplicație tipică, o valoare mai mică înseamnă o deschidere mai mică, iar o valoare mai mare, o deschidere mai mare, însă caracteristica reală trebuie verificată în documentația actuatorului.

### Care este diferența dintre 0–10 V și 2–10 V?

În ambele cazuri, poziția este setată printr-un semnal analogic.

În standardul 2–10 V, partea inferioară a intervalului este deplasată și poate permite dispozitivului să distingă semnalul de comandă de absența acestuia.

Controlerul și actuatorul trebuie să accepte un interval compatibil.

### Cum se alege actuatorul în funcție de numărul admisiilor?

Actuatorul nu trebuie ales exclusiv pe baza numărului de clapete.

Trebuie luate în considerare:

- forța sau cuplul necesar,
- lungimea și modul de ghidare al mecanismului,
- rezistențele opuse de clapete,
- lungimea cursei,
- viteza de acționare,
- tensiunea de alimentare,
- tipul de comandă,
- reacția necesară.

### Un singur actuator poate acționa mai multe clapete?

Da, dacă mecanica instalației permite conectarea clapetelor printr-un sistem comun și cuplul sau forța necesară nu depășește capacitatea actuatorului.

În practică, alegerea este determinată de rezistențele întregului mecanism, nu doar de numărul clapetelor.

### Mai multe actuatoare pot fi conectate în paralel și comandate printr-un singur semnal?

În unele sisteme, acest lucru este posibil, însă trebuie verificată documentația actuatoarelor și sarcina admisibilă a ieșirii de comandă.

În cazul mecanismelor de acționare reversibile fără reacție independentă, poate apărea și o desincronizare treptată a pozițiilor actuatoarelor individuale.

### De ce pot ajunge mai multe actuatoare, în timp, la poziții diferite?

Chiar și motoarele identice pot funcționa la viteze ușor diferite din cauza:

- sarcinilor diferite,
- rezistențelor mecanice,
- toleranțelor parametrilor motorului,
- diferențelor dintre reductoare.

Prin urmare, atunci când este necesară o sincronizare precisă, este nevoie de o reacție corespunzătoare sau de controlul individual al poziției.

### Admisiile pot fi comandate proporțional cu ventilația?

Da. În sistemele configurate corespunzător, poziția admisiilor poate fi corelată cu nivelul curent de ventilație.

Astfel, odată cu creșterea debitului ventilatoarelor, crește și deschiderea admisiilor.

### Actuatorul 24 V necesită o sursă de alimentare separată?

Dacă controlerul nu dispune de o ieșire de alimentare corespunzătoare, cu puterea necesară, este nevoie de o sursă de alimentare separată.

Puterea acesteia trebuie aleasă în funcție de curentul absorbit de actuator și de celelalte dispozitive alimentate din aceeași sursă.

### Se poate utiliza un actuator de la alt producător?

Adesea, da, dacă parametrii săi electrici și modul de comandă sunt compatibili cu ieșirile controlerului.

Înainte de conectare, trebuie verificate:

- tensiunea,
- tipul semnalului,
- schema conductoarelor,
- sensurile de acționare,
- semnalul de poziție,
- sarcina admisibilă.


## Senzori de temperatură și umiditate

### Unde se conectează senzorul de temperatură?

Senzorul trebuie conectat la intrarea pentru senzor prevăzută de producător, intrarea pentru senzor indicată în documentația modelului respectiv.

Nu trebuie presupus că marcajele bornelor sunt identice la toate versiunile dispozitivelor.

### Senzorul de temperatură indică o valoare diferită de termometrul etalon. Ce trebuie făcut?

Dacă controlerul dispune de o funcție de calibrare a senzorului, indicația poate fi corectată după compararea cu un termometru etalon fiabil.

Înainte de modificarea calibrării, este util să vă asigurați că:

- ambii senzori se află în același loc,
- măsurarea s-a stabilizat,
- senzorul nu este încălzit de soare sau de dispozitive,
- nu se află direct în fluxul de aer rece sau cald.

### Senzorul de umiditate indică o valoare incorectă. Poate fi calibrat?

Acest lucru depinde de versiunea controlerului, a senzorului și a software-ului.

În unele soluții, corecția poate necesita o funcție software corespunzătoare sau un tip compatibil de senzor. Dacă diferența este mare și repetabilă, trebuie verificată versiunea dispozitivului și contactat serviciul de asistență tehnică.

### O măsurare incorectă înseamnă întotdeauna că senzorul este defect?

Nu.

Cauza poate fi și:

- amplasarea incorectă a senzorului,
- cablul,
- conexiunea electrică,
- configurația,
- tipul necorespunzător de senzor,
- necesitatea calibrării,
- umiditatea sau coroziunea.


## Alarme și notificări

### Se poate conecta o sirenă direct la ieșirea de alarmă a controlerului?

Nu trebuie presupus acest lucru.

Ieșirea de alarmă a controlerului este de obicei o ieșire de comandă sau un contact de releu. Sirena poate necesita o alimentare separată și o centrală de alarmă.

### De ce se utilizează o centrală de alarmă?

Centrala poate:

- recepționa semnale de alarmă de la controlere,
- alimenta dispozitivul de semnalizare,
- menține funcționarea în timpul întreruperii alimentării,
- semnaliza alarma sonor sau luminos,
- trimite notificări GSM în versiunile care dispun de această funcție.

### Centrala poate semnaliza întreruperea alimentării controlerului?

Da, dacă sistemul a fost conectat corespunzător.

Soluția poate detecta nu doar depășirea temperaturii, ci și pierderea semnalului de la controler cauzată de întreruperea alimentării acestuia.

### Unde se setează temperatura minimă și maximă de alarmă?

Într-o configurație tipică, pragurile de alarmă se setează în controlerul care gestionează camera sau încăperea respectivă.

Centrala de alarmă primește apoi informația că respectivul controler a semnalat o alarmă.

### Centrala GSM necesită o cartelă SIM?

Pentru efectuarea apelurilor și trimiterea mesajelor prin rețeaua mobilă este necesară o cartelă SIM activă sau o altă soluție de comunicație prevăzută pentru modelul respectiv.

Fără o conexiune activă la rețeaua mobilă, funcțiile telefonice și SMS nu vor funcționa.

### Alarma poate transmite informații despre controlerul de la care provine evenimentul?

Într-un sistem configurat corespunzător, da.

Intrările centralei pot fi atribuite unor încăperi sau controlere concrete, astfel încât mesajul permite identificarea sursei alarmei.

### Câte controlere pot fi conectate la o singură centrală de alarmă?

Acest lucru depinde de modelul centralei.

În transcrieri au apărut centrale care acceptă până la opt intrări, însă înainte de realizarea instalației trebuie verificată specificația actuală a dispozitivului respectiv.

### Ce acumulator se utilizează în centrala de alarmă?

În unele dintre dispozitivele discutate în conversații se utiliza un acumulator 12 V 7 Ah.

Înainte de achiziționarea unui înlocuitor, trebuie verificat marcajul de pe acumulatorul existent și specificația centralei, deoarece alte versiuni ale dispozitivelor pot necesita un alt acumulator.

### Centrala trimite mesaje despre tensiune scăzută. Ce trebuie verificat?

În primul rând, trebuie verificate:

- starea acumulatorului,
- vechimea acestuia,
- conexiunile acumulatorului,
- prezența alimentării de la rețea,
- funcționarea încărcătorului sau a sursei de alimentare a centralei.

Un acumulator uzat poate provoca mesaje periodice despre tensiune scăzută.

### Cât de des trebuie înlocuit acumulatorul din centrala de alarmă?

Nu există un interval unic adecvat pentru toate condițiile.

Acumulatorul trebuie testat periodic, mai ales în instalațiile în care alarma în timpul întreruperii alimentării are o importanță critică. Pe măsură ce îmbătrânește, capacitatea sa reală scade.

### Este suficientă doar sirena ca măsură de protecție?

Sirena este eficientă doar atunci când cineva o poate auzi.

În obiectivele care rămân temporar nesupravegheate, este util să se utilizeze și notificarea la distanță, precum și alimentarea de rezervă cu acumulator.


## Convertizoare de frecvență

### Cum se alege convertizorul de frecvență pentru ventilatoare?

Trebuie cunoscute:

- tensiunea de alimentare,
- numărul de faze,
- puterea și curentul tuturor motoarelor,
- modul de conectare al acestora,
- condițiile de funcționare,
- modul de comandă necesar.

Convertizorul de frecvență trebuie să aibă o rezervă corespunzătoare față de sarcină, mai ales atunci când mai multe motoare funcționează în paralel.

### Convertizorul de frecvență trebuie să aibă exact aceeași putere ca suma puterilor motoarelor?

Convertizorul de frecvență nu trebuie ales exclusiv pe baza unei simple însumări a puterilor și nu trebuie selectat un dispozitiv care funcționează exact la limita parametrilor.

Trebuie luate în considerare curenții nominali, natura sarcinii și recomandările producătorului convertizorului de frecvență.

### Convertizorul de frecvență a oprit ventilatoarele și a afișat o eroare. Ce trebuie făcut?

Cel mai important este să notați codul complet al erorii înainte de resetare.

:::tip Fotografiați ecranul

Dacă situația permite, fotografiați afișajul înainte de resetare. Codul complet al erorii facilitează considerabil diagnosticarea.

:::

Doar începutul mesajului este adesea insuficient pentru stabilirea cauzei. Codul complet permite diferențierea, printre altele, a următoarelor situații:

- suprasarcină,
- depășirea curentului,
- supraîncălzire,
- tensiune necorespunzătoare,
- alte erori ale acționării.

### Se poate pur și simplu reseta eroarea convertizorului de frecvență?

Resetarea poate restabili funcționarea, dar nu elimină cauza alarmei.

După eveniment, trebuie verificat codul erorii și stabilită cauza înainte de repornirea instalației pentru o funcționare de lungă durată.

### Convertizorul de frecvență funcționează într-o încăpere cu praf. Trebuie curățat?

Da.

Praful și depunerile de pe radiator sau de pe ventilatorul de răcire pot afecta disiparea căldurii și pot duce la supraîncălzirea convertizorului de frecvență.

Curățarea trebuie efectuată în conformitate cu instrucțiunile producătorului, după deconectarea în siguranță a alimentării.

### Ce poate cauza supraîncălzirea convertizorului de frecvență?

Cele mai frecvente cauze sunt:

- elemente de răcire murdare,
- flux de aer obstrucționat,
- temperatură ambiantă prea ridicată,
- suprasarcină,
- defectarea ventilatorului de răcire,
- montaj incorect.

### O tensiune de rețea crescută poate declanșa o alarmă a convertizorului de frecvență?

Da. Convertizoarele de frecvență monitorizează tensiunea circuitului de alimentare și pot semnala o eroare la depășirea nivelului admisibil.

Dacă problema se repetă, trebuie verificată instalația și calitatea alimentării.


## Defecțiuni și diagnosticare

### Controlerul funcționează, dar afișajul nu indică nimic. Care poate fi cauza?

Cauzele posibile includ, printre altele:

- defectarea afișajului,
- o problemă cu reglarea contrastului la soluțiile mai vechi,
- deteriorarea conexiunii,
- coroziunea,
- defectarea plăcii principale.

Dacă dispozitivul nu a fost utilizat mult timp sau a funcționat într-un mediu umed, este util să se verifice și starea plăcii.

### După câțiva ani de neutilizare, controlerul are o problemă cu afișajul. De ce?

Neutilizarea îndelungată într-un mediu umed sau agresiv poate duce la:

- oxidarea conectorilor,
- coroziune,
- degradarea contactelor,
- deteriorarea componentelor electronice.

Într-un astfel de caz, este util să se efectueze o verificare completă, nu să se înlocuiască elementele fără o diagnosticare prealabilă.

### Controlerul este înnegrit după o supratensiune. Înseamnă că placa trebuie înlocuită?

Nu întotdeauna.

Un element de protecție se poate defecta și poate lăsa multe depuneri, deși restul plăcii poate fi reparat.

Totuși, dacă laminatul este carbonizat, ars sau traseele sunt deteriorate, reparația poate fi nerentabilă sau nedurabilă.

### Ce poate defecta mai multe controlere simultan?

Dacă mai multe dispozitive se defectează în același timp, trebuie verificată instalația de alimentare.

Una dintre cauzele posibile este o problemă cu conductorul neutru, care, într-o instalație trifazată, poate duce la apariția unor tensiuni necorespunzătoare la consumatorii monofazați.

Sunt posibile și supratensiuni provenite din rețea sau de la grupul electrogen.

### Ce trebuie făcut după o defecțiune legată de o supratensiune?

Înainte de conectarea unui controler reparat sau nou, trebuie stabilită cauza problemei.

:::danger Nu reconectați dispozitivul fără verificarea instalației

Dacă defecțiunea a fost cauzată de o tensiune necorespunzătoare, de un conductor neutru deteriorat sau de o supratensiune, controlerul reparat sau nou se poate defecta din nou.

:::

### Ce este elementul de protecție la supratensiune de pe placă?

În dispozitivele electronice se utilizează elemente care limitează supratensiunile, de exemplu varistoare.

Rolul acestora este să preia o parte din energia supratensiunii și să protejeze circuitele din aval. După un eveniment puternic, un astfel de element se poate deteriora permanent.

### Se poate porni dispozitivul după îndepărtarea elementului de protecție ars?

Acest lucru nu trebuie considerat o reparație normală.

După îndepărtarea protecției, dispozitivul poate pierde protecția împotriva unei supratensiuni ulterioare. Astfel de intervenții pot fi efectuate exclusiv ca procedură de service asumată, de către o persoană cu calificările corespunzătoare și după eliminarea cauzei defecțiunii inițiale.

### Controlerul a fost inundat sau este puternic corodat. Merită reparat?

Acest lucru depinde de gradul deteriorării.

Coroziunea superficială și defecțiunile izolate pot fi adesea remediate. Dacă coroziunea a afectat traseele, conectorii și numeroase componente, reparația poate necesita mult timp, poate fi nesigură și nejustificată economic.

### Spălarea sub presiune a dispozitivului poate deteriora controlerul?

Da.

Componentele electronice nu trebuie expuse acțiunii directe a apei sau a agentului de curățare dacă carcasa și modul de montaj nu sunt concepute pentru acest lucru.

Umiditatea care pătrunde în interior poate duce la coroziune și la defecțiuni ulterioare, dificil de diagnosticat.

### De ce pot reapărea după reparație defecțiunile cauzate de inundare?

Coroziunea poate progresa și în locuri care nu sunt vizibile la prima verificare.

Găurile metalizate de trecere, traseele și conexiunile deteriorate pot funcționa în timpul testului, iar ulterior pot pierde din nou contactul.

De aceea, în cazul unei plăci puternic corodate, service-ul poate recomanda înlocuirea în locul unor reparații suplimentare.

### Dispozitivul funcționează uneori, iar alteori nu. De unde trebuie început?

Înainte de contactarea service-ului, este util să colectați:

- modelul exact,
- descrierea simptomului,
- momentul apariției,
- valorile afișate pe ecran,
- codul alarmei sau al erorii,
- informații despre ultimele modificări ale instalației,
- o fotografie a interiorului și a bornelor, dacă poate fi realizată în siguranță.

Cu cât descrierea este mai precisă, cu atât diagnosticarea este mai ușoară.


## Service și reparații

### Ce trebuie trimis la service dacă controlerul este defect?

Este recomandat să trimiteți un ansamblu complet care permite reproducerea problemei.

Coletul trebuie să includă o scurtă descriere:

- ce nu funcționează,
- când apare problema,
- dacă defecțiunea este permanentă sau intermitentă,
- dacă înainte de defecțiune a avut loc o supratensiune, o inundare sau un alt eveniment,
- datele necesare pentru contact și returnarea dispozitivului.

:::note Date pentru solicitarea de service

Transmiteți datele de contact și de expediere direct către service. Nu le publicați în solicitări deschise sau în materiale publice.

:::

### Trebuie trimis întregul controler sau doar placa?

Depinde de defecțiune.

În cazul problemelor cu afișajul, butoanele, alimentarea sau al unui comportament neclar, este recomandat să trimiteți întregul ansamblu necesar pentru reproducerea simptomului.

În cazul unei reparații a unui anumit modul convenite în prealabil, service-ul poate solicita doar placa.

### ELETOR repară controlerele în loc să le înlocuiască imediat?

Din transcrieri reiese că dispozitivele sunt mai întâi diagnosticate.

Dacă reparația este posibilă și justificată, se înlocuiesc componentele sau modulele defecte. În cazul unei deteriorări grave, service-ul poate propune înlocuirea plăcii sau a întregului dispozitiv.

### Ce se întâmplă dacă placa defectă nu poate fi reparată?

Modulul defect poate fi înlocuit cu unul nou, dacă piesa corespunzătoare este disponibilă și compatibilă cu dispozitivul.

În cazul dispozitivelor mai vechi, service-ul trebuie să confirme mai întâi compatibilitatea versiunilor.

### Merită cumpărată imediat o placă nouă după o supratensiune?

Nu întotdeauna.

Dacă deteriorarea afectează un element de protecție sau o mică parte a circuitului, reparația poate fi justificată. Este util să se efectueze mai întâi o diagnosticare.

### Service-ul poate verifica și afișajul și butoanele?

Da, dacă elementele sunt livrate împreună cu dispozitivul sau modulul.

Acest lucru este deosebit de util atunci când nu se știe dacă problema se află pe placa principală sau în panoul utilizatorului.

### Merită întotdeauna recuperat un controler puternic corodat?

Nu.

Dacă costul diagnosticării și al reparației crește, iar fiabilitatea după reparație rămâne incertă, înlocuirea poate fi mai rezonabilă.

Acest lucru se aplică în special dispozitivelor de care depinde ventilația obiectivului.

### Cum se poate accelera diagnosticarea la service?

Includeți o descriere exactă a simptomului, nu doar afirmația „nu funcționează”.

Sunt utile și:

- fotografiile,
- codul erorii,
- descrierea instalației,
- tipul consumatorilor conectați,
- informația despre o supratensiune sau o întrerupere a alimentării,
- informația despre inundarea sau spălarea dispozitivului.


## Instalare și cablare

### Cum se conectează dispozitivele la bornele de releu C și NO?

C și NO sunt marcaje tipice ale contactului de releu:

- C — contact comun,
- NO — contact normal deschis.

Modul de utilizare depinde de dispozitiv și de schema instalației. Contactul poate fi utilizat, de exemplu, pentru comanda bobinei unui contactor, însă nu este permisă depășirea parametrilor săi admisibili.

:::warning Lucrări electrice

Conexiunile la tensiunea de rețea trebuie realizate de o persoană cu calificările corespunzătoare, în conformitate cu schema dispozitivului respectiv.

:::

### Ieșirea cu releu poate alimenta direct un ventilator mare?

De regulă, aceasta nu este o utilizare adecvată a unei ieșiri mici de comandă.

Pentru sarcini mai mari se utilizează un contactor, un releu de putere sau un modul de acționare dedicat.

### La ce servesc bornele A1 și A2 ale contactorului?

Acestea sunt bornele bobinei contactorului.

După aplicarea tensiunii corespunzătoare pe bobină, contactorul modifică starea contactelor sale de putere.

Tensiunea bobinei trebuie să fie conformă cu proiectul instalației și cu documentația contactorului.

### Se pot monta aparate suplimentare în interiorul carcasei controlerului?

Numai dacă construcția carcasei respective permite acest lucru și dacă nu sunt afectate:

- gradul de protecție,
- izolația,
- răcirea,
- siguranța,
- accesul pentru service.

Orice orificii noi trebuie realizate astfel încât să se mențină etanșeitatea necesară.

### Sunt utile întrerupătoarele suplimentare pentru ventilatoare?

Acestea pot facilita lucrările de service și pot permite deconectarea independentă a fiecărui ventilator.

Totuși, modul de realizare trebuie să țină cont de protecțiile electrice și nu trebuie să provoace stări periculoase ale controlerului.

### Cablurile de comandă pot fi pozate împreună cu cablurile de putere?

Trebuie evitată pozarea cablurilor de semnal sensibile în paralel și foarte aproape de cablurile de mare putere, mai ales pe distanțe lungi.

Cerințele depind de tipul semnalului și de mediul electromagnetic.

### Ce cablu trebuie utilizat pentru conexiunile de rețea și dispozitivele PoE?

În instalațiile discutate, a fost indicat ca cerință minimă un cablu cu perechi torsadate de categoria 5e.

Dacă cablul traversează un mediu cu un nivel ridicat de perturbații sau cu risc de sarcini electrostatice, poate fi justificată utilizarea unui cablu ecranat corespunzător și a unui sistem corect de împământare.

### Este necesar un cablu încrucișat pentru PoE?

În instalațiile tipice se utilizează o conexiune directă standard.

Totuși, trebuie verificate întotdeauna cerințele dispozitivului de rețea și ale sursei de alimentare PoE utilizate.


## Exploatare și întreținere

### Cum se poate reduce riscul de defectare a controlerelor în clădirile agricole?

Cel mai important este să se limiteze influența:

- umidității,
- amoniacului și a mediului agresiv,
- prafului,
- spălării directe cu apă,
- supratensiunilor,
- alimentării necorespunzătoare.

Este util să se verifice periodic și starea cablurilor, a conexiunilor și a carcaselor.

### Dispozitivele electronice trebuie curățate regulat?

Da, mai ales dispozitivele echipate cu radiatoare, ventilatoare și orificii de ventilație.

Praful acumulat afectează răcirea.

Curățarea trebuie efectuată după deconectarea alimentării și în conformitate cu instrucțiunile dispozitivului.

### După câțiva ani de funcționare, este utilă efectuarea unei revizii a controlerului?

Da, mai ales în condiții de mediu dificile.

Revizia poate include:

- evaluarea stării conectorilor,
- verificarea urmelor de umiditate și coroziune,
- verificarea elementelor de răcire,
- verificarea panoului și a butoanelor,
- testarea senzorilor,
- verificarea acumulatorilor din sistemele de alarmă.

### Ce este util să se noteze după apariția unei defecțiuni?

Cele mai utile sunt:

- mesajul complet,
- codul erorii,
- ora evenimentului,
- temperatura,
- starea ventilației,
- informația despre întreruperea alimentării,
- informația despre funcționarea grupului electrogen,
- o fotografie a ecranului sau a dispozitivului.

Dispozitivul nu trebuie resetat înainte de notarea codului, dacă situația permite efectuarea acestui lucru în siguranță.

### Este utilă o alarmă independentă de controlerul de ventilație?

Da, mai ales acolo unde defectarea ventilației poate duce rapid la condiții periculoase.

O centrală independentă, cu acumulator propriu și notificare la distanță, oferă un nivel suplimentar de protecție.

### Ce informații trebuie pregătite înainte de contactarea asistenței tehnice?

Este recomandat să pregătiți:

1. modelul exact al dispozitivului,
2. descrierea instalației,
3. numărul și parametrii dispozitivelor conectate,
4. setările actuale legate de problemă,
5. simptomul exact,
6. codul complet al erorii sau al alarmei,
7. fotografii ale dispozitivului și ale plăcuțelor cu date nominale,
8. informații despre ultimele modificări ale instalației.

Acest lucru permite scurtarea considerabilă a diagnosticării.


## Notă importantă privind dispozitivele mai vechi

Denumirile, marcajele bornelor și funcțiile disponibile pot diferi între versiunile dispozitivelor fabricate în ani diferiți.

Dacă dispozitivul are o vechime de câțiva ani sau de peste zece ani, înainte de aplicarea instrucțiunilor unui model mai nou trebuie confirmate:

- identificarea exactă a dispozitivului,
- versiunea plăcii,
- tipul afișajului,
- versiunea software-ului,
- schema bornelor.

:::warning Versiuni mai vechi ale dispozitivelor

Nu presupuneți o compatibilitate deplină doar pe baza unui aspect similar al carcasei. Înainte de utilizarea unei scheme sau a unor instrucțiuni, confirmați modelul exact și versiunea dispozitivului.

:::


## Contactarea asistenței tehnice

Dacă FAQ nu rezolvă problema, pregătiți înainte de contact:

- o fotografie a controlerului,
- o fotografie a plăcuței cu date nominale a consumatorului,
- parametrii motoarelor sau ai actuatoarelor,
- schema conexiunilor,
- o descriere exactă a modului de funcționare dorit.

Astfel, alegerea dispozitivului sau diagnosticarea problemei se poate realiza pe baza parametrilor reali ai instalației, nu a presupunerilor.
