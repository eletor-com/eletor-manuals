---
id: sc-pe16
title: SC-PE16 — instrucțiuni de utilizare
sidebar_label: SC-PE16
sidebar_position: 5
description: Instrucțiuni pentru modulul de extensie de putere SC-PE16 — montaj, conectare,
  punere în funcțiune, meniu și protecții.
slug: /sc-pe16
toc_min_heading_level: 2
toc_max_heading_level: 3
---


Modulul de extensie de putere SC-PE16 este destinat comenzii ventilatoarelor atunci când sarcina depășește capacitatea controlerului principal. Dispozitivul reglează tensiunea de alimentare a ventilatoarelor pe baza unui semnal analogic sau a unei setări manuale. Curentul total maxim de ieșire este de 16 A.

![Modul de extensie de putere ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Parametri și caracteristici

- modurile AUTO și MANUAL și modul de repaus al dispozitivului;
- afișaj grafic și tastatură tactilă;
- comandă analogică 2–10 V sau 4–20 mA;
- prag programabil de activare a grupei de ventilație 2.;
- byPASS la un nivel stabilizat de 100%;
- protecție termică a circuitului de putere;
- safeRUN: nivel reglabil de funcționare de urgență;
- calibrarea nivelului minim de ventilație;
- testarea ventilației, a releului și a alarmei;
- blocarea tastaturii și blocarea pentru curățare;
- limba polonă, engleză sau ucraineană;
- alimentare 230 V CA, 50 Hz; carcasă IP65.

:::info Versiunea software-ului

Descrierea funcțiilor se referă la software-ul furnizat **vers. 2.1**. Disponibilitatea funcțiilor trebuie raportată la versiunea instalată în dispozitiv.

:::

## Instalarea controlerului

:::danger Deconectați alimentarea

În timpul instalării dispozitivului, alimentarea cu energie electrică trebuie obligatoriu deconectată, deoarece tensiunea prezentă pe unele componente este periculoasă pentru viață și sănătate. Se recomandă încredințarea instalării unei persoane calificate.

:::

### Alegerea locului de montaj

Dispozitivul trebuie montat într-un loc accesibil personalului de exploatare, inaccesibil copiilor și animalelor, fără expunere directă la soare. Intervalul temperaturii ambiante este de la −10°C la +40°C. În jurul carcasei și al radiatorului trebuie asigurată circulația liberă a aerului. Nu acoperiți radiatorul și nu montați dispozitivul în apropierea surselor de căldură.

### Montaj

Fixați partea inferioară a carcasei pe un perete plan cu patru dibluri, utilizând orificiile de montaj situate în afara compartimentului etanș. Montați capacul cu balamaua inclusă în set. Înainte de închidere, verificați starea și poziționarea garniturii.

Utilizați cabluri cu secțiune exterioară circulară, adaptate presetupelor. Strângeți presetupele astfel încât să etanșeze și să imobilizeze cablul. Obturați trecerile neutilizate. Strângeți capacul cu toate șuruburile. Etanșeitatea depinde de montarea corectă a carcasei și a trecerilor de cablu.

### Pregătirea conexiunilor

Efectuați toate lucrările în interiorul carcasei după deconectarea alimentării și verificarea absenței tensiunii. Dacă demontarea panoului necesită deconectarea cablului panglică, deconectați-l cu grijă și reconectați-l înainte de închiderea carcasei. Nu conectați și nu deconectați cablul panglică atunci când alimentarea este pornită.

Pozați cablurile de semnal INPUT și ENABLE separat de cablurile de alimentare și de ieșire. Respectați marcajele bornelor aplicate pe exemplarul respectiv al dispozitivului. Masa intrărilor de semnal și borna de protecție PE au funcții diferite și nu sunt interschimbabile.

## Conexiunea electrică

:::danger Deconectați alimentarea

Înainte de conectarea circuitului, asigurați-vă că alimentarea este oprită!

:::

![Bornele de alimentare, ale ventilatoarelor, GR 2, ENABLE, CAN și INPUT](./img/sc-pe16/zaciski.png)

| BORNĂ | DESTINAȚIE |
| --- | --- |
| L, N, PE — alimentare | Alimentare 230 V CA, 50 Hz: L — fază, N — conductor neutru, PE — conductor de protecție. În documentația inițială este indicată protecția B20; alegerea protecțiilor și a cablurilor trebuie să țină cont de instalație și de sarcină. |
| U, N, PE — ventilatoare | U — ieșire de fază reglată; N și PE — bornele comune corespunzătoare ale dispozitivului. Suma curenților ventilatoarelor nu poate depăși 16 A. Fiecare ventilator necesită o protecție separată. Utilizați motoare aprobate pentru reglarea prin tensiune. |
| GR 2: C, NO | Contact izolat al releului grupei 2. Se închide când nivelul de ventilație impus este egal cu pragul „Grupa 2 de ventilație” sau mai mare. Curentul maxim al contactului conform instrucțiunilor furnizate: 6 A. Pentru comanda directă a sarcinii, documentația indică o protecție externă B6. |
| INPUT: V, masă | Intrare de tensiune. Selectați „Tip de comandă → Intrare V”. În programul analizat, intervalul de reglare este 2–10 V. Nu conectați la această intrare tensiunea rețelei sau ieșirea reglată de alimentare a ventilatoarelor. |
| INPUT: I, masă | Intrare de curent 4–20 mA. Selectați „Tip de comandă → Intrare I”. Conectați semnalul conform marcajelor sursei și receptorului. |

Pentru comandă, utilizați intrarea selectată V sau I. SC-PE16 necesită alimentare proprie de la rețea; intrarea analogică transmite doar valoarea de comandă.

## Intrarea ENABLE și comunicația

### ENABLE: E și masă

Intrarea funcționează cu un contact fără potențial. Bornele E și masă pot fi doar scurtcircuitate sau deschise; nu aplicați tensiune externă. Scurtcircuitarea permite funcționarea, iar deschiderea impune nivelul 0%. Oprirea este supusă setării „Timp de decelerare”.

Funcția ENABLE se activează separat pentru AUTO și MANUAL în meniul „Avansat → Ventilator”. Ambele funcții sunt dezactivate din fabrică, astfel încât în acest caz nu este necesară o punte. Deschiderea ENABLE nu este echivalentă cu modul de repaus: panoul rămâne activ. În AUTO, cu blocarea ENABLE activă, programul omite citirea semnalului de comandă și nu activează safeRUN.

### CAN și Wi-Fi

Opțiunile „Intrare CAN” și „Intrare WiFi” sunt prezente în meniu, însă în software-ul vers. 2.1 nu realizează comanda: ambele funcții returnează nivelul 0%. Pentru punerea în funcțiune a dispozitivului cu acest program, selectați intrarea V sau I. Nu configurați instalația pe baza CAN sau Wi-Fi fără confirmarea compatibilității în versiunea de software instalată.

## Principiul de funcționare

SC-PE16 este un regulator de putere care execută comenzile controlerului principal sau ale operatorului. Nu măsoară temperatura încăperii și nu are setări proprii pentru temperatură, aerisire, încălzire suplimentară sau clapete de admisie a aerului. Nivelul procentual de ventilație reprezintă o valoare de comandă, nu o măsurare a turației reale a motorului.

| SEMNAL NOMINAL | NIVEL DE VENTILAȚIE IMPUS |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

Între valorile limită, programul determină nivelul liniar și îl rotunjește la procente întregi. Pentru intrarea V, creșterea începe după depășirea valorii citite 2,04 V, iar pentru intrarea I — 4,04 mA. Starea finală a ieșirii depinde și de ENABLE, de pornire și de protecția termică.

## Funcționare de urgență și protecții

### safeRUN — pierderea semnalului de intrare

În modul AUTO, alarma „Intrare” apare la o valoare a tensiunii citite sub 1,50 V sau a curentului sub 2,00 mA, în funcție de intrarea selectată. Programul impune atunci nivelul „Funcționare de urgență” în intervalul 0–100%; setarea din fabrică este 30%. După revenirea semnalului la pragul de detectare sau peste acesta, alarma de intrare dispare și dispozitivul revine la comanda analogică.

Intervalele 1,50–2,04 V și 2,00–4,04 mA produc nivelul 0% fără alarmă de intrare. În această versiune, semnalul 0 V nu este o comandă obișnuită de oprire — activează funcționarea de urgență. Controlerul principal cu ieșire 0–10 V trebuie configurat pentru intervalul 2–10 V fără reducere la 0 V. În MANUAL, semnalul analogic nu comandă ventilația, iar alarma de intrare este resetată.

### Protecție termică

Alarma „Supraîncălzire” este activată când temperatura citită a radiatorului depășește 87°C. Se resetează după scăderea sub 80°C. În timpul alarmei, programul modifică nivelul impus: pentru valori de cel puțin 50% impune 100%, iar pentru valori sub 50% impune 0%. Modificarea ieșirii este supusă algoritmului de pornire și decelerare. Protecția nu garantează funcționarea continuă a ventilației în toate cazurile.

Starea releului GR 2 este determinată înainte de corecția termică: aceasta depinde de nivelul anterior impunerii valorii 0% sau 100%. Nivelul de funcționare de urgență este, de asemenea, supus corecției termice. În caz de supraîncălzire, verificați condițiile de răcire, murdărirea radiatorului și sarcina; încredințați lucrările din interiorul carcasei unei persoane autorizate.

### byPASS și pornirea lină

La un nivel de ieșire stabilizat de 100%, programul activează releul de ocolire a circuitului de reglare de fază. Pornirea poate include creșterea până la 100%, menținerea la 100% și trecerea la nivelul impus. Parametrii „Pornire lină” influențează și viteza de reacție a ieșirii la modificarea comenzii.

## Prima punere în funcțiune a controlerului

:::warning Calibrarea ventilatoarelor

Atenție! La prima punere în funcțiune a dispozitivului, este obligatorie setarea benzii interzise de funcționare a motorului.

:::

1. Cu alimentarea deconectată, verificați conexiunile alimentării, PE, ventilatoarelor și semnalului analogic. Confirmați că motoarele sunt aprobate pentru reglarea prin tensiune și că valoarea curentului total nu depășește 16 A.
2. Porniți alimentarea. Dacă vi se propune selectarea limbii, apăsați OK și selectați limba. Deblocați tastatura cu butonul cu simbolul lacătului.
3. În „Tip de comandă”, selectați „Intrare V” sau „Intrare I”. Setați nivelul „Funcționare de urgență” și pragul „Grupa 2 de ventilație”. Dacă este necesar, activați ENABLE separat pentru modul corespunzător.
4. Accesați „Avansat → Ventilator → Bandă interzisă”. În această opțiune, programul impune nivelul 1%, iar modificarea parametrului influențează imediat ieșirea. Intervalul este de la −20 la 200, cu setarea din fabrică 0. O valoare pozitivă mărește nivelul minim de comandă, iar una negativă îl reduce.
5. Alegeți valoarea astfel încât toate ventilatoarele să se rotească stabil, fără opriri și fără încălzire excesivă. Observați fiecare ventilator, de preferință cu ajutorul unei a doua persoane. Simpla ridicare a clapetei nu înlocuiește verificarea funcționării corecte a motorului. Confirmați cu OK; ESC restabilește setarea anterioară.
6. Verificați ieșirea la mai multe niveluri, inclusiv 0%, la un nivel scăzut și la 100%. Repetați calibrarea după înlocuirea ventilatoarelor sau modificarea configurației acestora.
7. În AUTO, verificați reacția la semnalul minim și maxim. Apoi verificați întreruperea semnalului și trecerea la funcționarea de urgență, precum și revenirea după restabilirea semnalului. Dacă ENABLE este activ, verificați și funcționarea acestuia.
8. Verificați GR 2 și semnalizarea alarmei în meniul „Testare”. După finalizarea testelor, ieșiți din această opțiune și selectați modul de funcționare final.

:::warning Activarea efectivă a ieșirilor

Testarea și calibrarea comandă ieșirile reale. Acestea pot porni ventilatoarele, iar testul de ventilație impune un nivel independent de comanda normală. Asigurați condiții sigure de testare și supraveghere permanentă.

:::

## Programarea controlerului

### Panoul frontal — indicatoare și butoane

| ELEMENT | UTILIZARE |
| --- | --- |
| Alimentare / repaus | Butonul cu simbolul de alimentare afișează confirmarea trecerii în repaus; confirmați cu OK. O nouă apăsare reactivează dispozitivul. Modul de repaus impune ieșirilor starea oprită; nu deconectează tensiunea rețelei. |
| Lacăt | Activează sau dezactivează blocarea tastaturii. După deblocare, indicatorul de lângă lacăt este aprins. Pe ecranul principal, blocarea se reactivează după aproximativ 30 s de inactivitate. |
| A — AUTO | Selectează comanda de la intrarea analogică după confirmarea cu OK. Indicatorul A indică modul selectat. |
| M — MANUAL | Selectează comanda manuală după confirmarea cu OK. Pe ecranul principal, tastele + și − modifică setarea 0–100%. Indicatorul M indică modul selectat. |
| +, −, OK, ESC | OK deschide meniul, accesează o opțiune și confirmă valoarea. + și − selectează opțiunea sau modifică valoarea. ESC revine la nivelul anterior sau anulează editarea. |
| Alarmă și grupă 2 | Indicatorul roșu semnalizează o alarmă. Indicatorul de lângă simbolul ventilatorului „2” semnalizează activarea releului GR 2. |
| Afișaj | În AUTO, afișează nivelul de ventilație impus, valoarea citită a intrării selectate, graficul cu bare și alarmele. Când ENABLE este activ, afișează și starea acestuia. În MANUAL, valoarea principală reprezintă setarea manuală; protecțiile pot modifica ieșirea. |

### Memorarea setărilor

Parametrii meniului sunt salvați în memoria nevolatilă după confirmarea cu OK. Modificările nivelului MANUAL se aplică imediat, iar salvarea are loc după o scurtă perioadă de inactivitate. După o întrerupere a alimentării, sunt restabilite setările salvate, inclusiv modul AUTO/MANUAL, nivelul manual și starea de repaus. Nu opriți alimentarea imediat după modificarea setării manuale.

În cazul unei sume de control incorecte sau al unei valori în afara intervalului, programul restabilește valorile din fabrică. În acest caz, verificați din nou toate setările, în special calibrarea ventilatoarelor, intrarea de comandă și funcționarea de urgență.

## Funcțiile meniului de bază

| MENIU | INTERVAL / SETARE DIN FABRICĂ | DESCRIERE |
| --- | --- | --- |
| Tip de comandă | Intrare V | Selectarea V, I, CAN sau Wi-Fi. Pentru versiunea analizată, utilizați V (2–10 V) sau I (4–20 mA). CAN și Wi-Fi nu realizează comanda. |
| Grupa 2 de ventilație | 1–100% / 100% | Pragul de închidere a contactului GR 2. Contactul este închis la un nivel egal cu pragul sau mai mare și deschis sub prag. Programul nu definește un histerezis separat. |
| Funcționare de urgență | 0–100% / 30% | Nivelul impus la pierderea semnalului analogic selectat în AUTO. Valoarea 0% înseamnă oprire în cazul pierderii semnalului. |
| Blocare pentru curățare | 60 s | Blochează utilizarea tastelor timp de 60 secunde și afișează numărătoarea inversă. Reglarea ventilației continuă să funcționeze. Funcția este destinată ștergerii panoului, nu lucrărilor electrice sau spălării interiorului. |
| Avansat | Submeniu | Acces la teste, limbă, calibrarea ventilatorului, ENABLE, Pornire lină, sunetul alarmei, setările din fabrică și informații despre program. |

## Funcțiile meniului avansat

| MENIU / PARAMETRU | INTERVAL / SETARE DIN FABRICĂ | DESCRIERE |
| --- | --- | --- |
| Testare → Ventilație | 0–100% | Forțarea temporară a ieșirii reglate. Modificările se aplică în timpul editării. După ieșirea cu OK sau ESC, se revine la comanda normală. |
| Testare → Vent. treapta 2 | Nu / Da | Forțarea temporară a contactului GR 2 și a indicatorului acestuia. |
| Testare → Alarmă | Nu / Da | Test temporar al semnalizării de alarmă, inclusiv al sunetului, independent de setarea normală „Semnal de alarmă”. |
| Limbă | Polonă | Se pot selecta limbile polonă, engleză și ucraineană. |
| Ventilator → Bandă interzisă | −20–200 / 0 | Calibrarea nivelului 1%. În timpul editării, este forțată ieșirea reală 1%. Parametrul nu este exprimat în procente sau în secunde. |
| Ventilator → Activare EN AUTO | Nu / Da; Nu | Activează dependența modului AUTO de intrarea ENABLE. |
| Ventilator → Activare EN MANUAL | Nu / Da; Nu | Activează dependența modului MANUAL de intrarea ENABLE. |
| Pornire lină → Timp de accelerare | 0–50 / 5 | Viteza de creștere a nivelului la pornire până la 100%. O valoare mai mare înseamnă o modificare mai lentă. Valoarea 0 omite etapa de creștere. |
| Pornire lină → Timp 100% | 0–250 / 100 | Menținerea nivelului 100% în timpul pornirii. Valoarea 0 omite etapa de menținere. Setarea atât a accelerării, cât și a menținerii la 0 omite suflarea până la 100%. |
| Pornire lină → Timp de decelerare | 0–50 / 5 | Viteza de atingere a nivelului solicitat, inclusiv la modificarea acestuia. Valoarea 0 înseamnă o modificare fără tranziție treptată. |
| Semnal de alarmă | Nu / Da; Nu | Activează sunetul care semnalizează alarma. Setarea Nu nu elimină mesajul de pe ecran sau semnalizarea prin indicator. |
| Setări din fabrică | Nu / Da | După selectarea Da, restabilește și salvează valorile implicite, inclusiv calibrarea 0, intrarea V, AUTO, funcționarea de urgență 30%, pragul GR 2 egal cu 100% și ENABLE dezactivat. După operație, configurați și verificați din nou dispozitivul. |
| Program | vers. 2.1 + data compilării | Afișează versiunea și data compilării programului. Această descriere a fost elaborată pe baza surselor furnizate SC_PX16_v02. |

Parametrii Pornire lină sunt setări adimensionale ale contoarelor programului, nu durate exprimate în secunde. La 50 Hz, un pas corespunde aproximativ cu (setare + 1) × 20 ms: pentru accelerare și decelerare, aceasta este durata unei modificări cu 1 punct procentual, iar pentru „Timp 100%” — durata menținerii. Valoarea 0 are semnificația descrisă în tabel. Duratele reale depind de faza algoritmului.

## Mesaje de eroare și avertizare

| MESAJ | SEMNIFICAȚIE ȘI ACȚIUNI |
| --- | --- |
| Intrare | Valoare citită prea scăzută a semnalului selectat în AUTO. Dispozitivul impune funcționarea de urgență. Verificați sursa semnalului, cablurile, masa comună și selectarea V/I. |
| Supraîncălzire | Valoare citită a radiatorului &gt;87°C; resetare &lt;80°C. Ventilația este impusă la 0% sau 100%, conform descrierii protecției termice. Verificați răcirea și sarcina. |
| Alimentare | Perturbare a sincronizării circuitului de putere cu rețeaua. Verificați alimentarea și instalația. La întreruperea completă a alimentării, afișajul nu funcționează. |
| Memorie CRC | Eroare a sumei de control sau a intervalului setărilor salvate. Programul restabilește valorile implicite. Verificați configurația și repetați calibrarea; dacă eroarea reapare, contactați serviciul de asistență tehnică. |

## Observații și avertismente

:::danger Deconectați alimentarea

În timpul instalării dispozitivului, alimentarea cu energie electrică trebuie obligatoriu deconectată, deoarece tensiunea prezentă pe unele componente este periculoasă pentru viață și sănătate. Se recomandă încredințarea instalării unei persoane calificate.

:::

Înainte de instalare și utilizare, citiți instrucțiunile. Încredințați reparațiile și lucrările în interiorul dispozitivului personalului autorizat. Modul de repaus, blocarea tastaturii, ENABLE și setarea 0% nu reprezintă o deconectare a alimentării și nu asigură condiții sigure pentru lucrările electrice.

Alegeți setările ventilației și ale funcționării de urgență în funcție de necesitățile animalelor și ale instalației. Verificați periodic funcționarea reală a tuturor ventilatoarelor. Semnalizarea SC-PE16 nu înlocuiește monitorizarea independentă a condițiilor din incintă și a întreruperii alimentării. Pe regleta de borne prezentată nu există un contact ALARM separat pentru centrală.

:::note Eliminarea dispozitivului

La sfârșitul utilizării produsului, acesta nu trebuie aruncat împreună cu deșeurile municipale nesortate, ci eliminat în conformitate cu reglementările în vigoare (directivele WEEE ale Uniunii Europene 2012/19/UE).

:::

Produsul a fost fabricat în conformitate cu cerințele RoHS (Directiva Uniunii Europene 2011/65/UE).

## Date tehnice ale controlerului

| PARAMETRU | VALOARE |
| --- | --- |
| Alimentare / consum propriu | 230 V CA, 50 Hz / &lt;10 W |
| Curent total maxim al ieșirii U | 16 A |
| Curent maxim al contactului GR 2 | 6 A; contact C–NO, izolat |
| Intrare V / intrare I | 2–10 V / 4–20 mA, selectabile din meniu |
| Prag de pierdere a semnalului (valoare citită de program) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Contact fără potențial E–masă; activare separată pentru AUTO/MANUAL |
| Protecție termică (valoare citită a radiatorului) | Alarmă &gt;87°C; revenire &lt;80°C |
| Temperatură ambiantă / carcasă | −10°C până la +40°C / IP65 |
| Dimensiuni / rezistență la supratensiuni | 34 × 29 × 12 cm / 210 J |
| Limbile meniului | Polonă, engleză, ucraineană |

Conținutul setului conform documentației furnizate: 4 dibluri de expansiune, 2 presetupe PG13,5, 1 presetupă PG9 și 1 balama.

## Condiții de garanție

Conținutul condițiilor de garanție a fost păstrat din documentul furnizat de producător.

1. Producătorul ELETOR cu sediul în Polonia, la adresa: Pod Sosno 28, 87-305 Zbiczno (denumit în continuare garant), acordă Cumpărătorului o garanție de calitate pentru produsul pentru care a fost emis prezentul certificat de garanție, cu condiția utilizării acestuia conform destinației și regulilor stabilite în instrucțiunile de utilizare înmânate Cumpărătorului împreună cu produsul.
2. Perioada de garanție este de 24 luni de la data vânzării. Defecțiunile sau defectele produsului constatate în această perioadă vor fi remediate gratuit. După expirarea perioadei de garanție sau în cazul pierderii drepturilor de garanție, defecțiunile sau defectele vor fi remediate contra cost.
3. Garanția nu acoperă:

   - orice defecte apărute din cauza utilizării necorespunzătoare a produsului (inclusiv efectuarea unor operațiuni care nu sunt descrise în instrucțiunile de utilizare etc.);

   - orice defecte rezultate din reparații, modificări etc. efectuate de o altă persoană decât garantul;

   - orice defecte sau deteriorări rezultate din transportul sau căderea produsului, dacă aceste evenimente au avut loc după achiziționarea produsului, precum și deteriorările mecanice cauzate de manipularea necorespunzătoare de către utilizator;

   - orice defecte sau deteriorări apărute ca urmare a unui incendiu, cutremur, inundații, trăsnet sau a altor dezastre naturale, a poluării mediului, a acțiunii radiațiilor ionizante externe sau a câmpului magnetic, precum și a alimentării neregulate cu energie electrică sau a energiei electrice cu parametri neconformi cerințelor;

   - orice defecte rezultate din depozitarea necorespunzătoare (de exemplu, depozitarea produsului în afara intervalului de temperatură sau umiditate indicat în specificații, în apropierea substanțelor chimice), întreținerea sau curățarea necorespunzătoare etc.;

   - orice defecte rezultate din epuizarea bateriilor de alimentare etc.;

   - orice defecte cauzate de nisip, noroi, praf, apă și alte lichide etc. care au pătruns în interiorul carcasei produsului;

   - deteriorările rezultate din uzura naturală, parțială sau totală a produsului, în conformitate cu proprietățile sau destinația acestuia;

   - operațiunile indicate în instrucțiunile de utilizare pe care utilizatorul este obligat să le efectueze pe cont propriu.

4. Cumpărătorul își pierde drepturile de garanție ca urmare a:

   - efectuării oricărei reparații sau modificări a produsului de către o altă persoană decât garantul;

   - constatării violării, deteriorării sau ruperii oricăruia dintre sigilii;

   - constatării deteriorării, alterării, acoperirii sau îndepărtării numerelor de serie ori a altor marcaje de identificare a produsului.

5. Termenul de reparație este de până la 21 zile lucrătoare de la data notificării defectului și a livrării produsului complet la punctul de service al garantului. În cazuri deosebit de justificate, legate de necesitatea procurării din străinătate a unor elemente sau subansambluri ori de o defecțiune deosebit de complexă sau dificil de reparat ori de diagnosticat, termenul de reparație poate fi prelungit cu perioada necesară îndeplinirii obligațiilor de garanție.
6. Drepturile Cumpărătorului în temeiul garanției pot fi exercitate numai după prezentarea unui certificat de garanție valabil și completat corect în ziua achiziției, precum și a dovezii de achiziție (factură, bon fiscal etc.). Modificările neautorizate ale înscrierilor din certificatul de garanție (inclusiv tăieri, ștersături, adăugiri etc.) duc la pierderea drepturilor de garanție. Certificatul de garanție fără denumirea, modelul, numărul de serie al produsului, data și locul achiziției produsului, precum și fără ștampila lizibilă și semnătura Vânzătorului este nevalabil și nu constituie temei pentru depunerea valabilă a unei reclamații.
7. Cumpărătorul este obligat să livreze produsul pe cheltuiala sa, într-un ambalaj adecvat echipamentului respectiv, care să asigure transportul și depozitarea în condiții sigure și corespunzătoare, sau să acopere costurile deplasării garantului. În cazul în care se constată că produsul predat pentru reparație este funcțional din punct de vedere tehnic și lipsit de defecte sau dacă defecțiunea constatată nu este acoperită de garanție, Cumpărătorului îi vor fi imputate costurile serviciilor și ale transportului.
8. Cumpărătorul este obligat să ridice produsul reparat în termen de 90 zile de la data notificării de către garant a efectuării reparației. Dacă cumpărătorul nu ridică produsul în acest termen, acesta suportă riscul pierderii sau deteriorării accidentale a produsului.
9. Perioada de garanție se prelungește cu durata reparației, calculată de la data livrării produsului până la termenul stabilit pentru ridicarea acestuia după reparație. Garantul este obligat să emită un document care să ateste perioada și amploarea remedierii defectelor produsului.

10. Cumpărătorul depune reclamațiile prin intermediul Vânzătorului produsului sau direct, la adresa garantului: ELETOR, Pod Sosno 28, 87-305 Zbiczno, Polonia.

11. Garantul nu răspunde:

    - pentru veniturile pierdute ca urmare a apariției defectului și a duratei remedierii acestuia;

    - pentru pierderile rezultate din apariția defectului și pentru orice daune rezultate din instalarea, utilizarea sau programarea necorespunzătoare a funcțiilor dispozitivului.
