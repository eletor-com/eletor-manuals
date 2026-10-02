---
sidebar_position: 4
title: Instrucțiuni Sursă de alimentare DC50W24VB
description: Sursă de alimentare DC50W24VB  de rezervă pentru sistemul de admisie
  a aerului.
keywords:
- eletor IC-AC
- controler pentru admisiile de aer
- controler climatic
- controler de ventilație pentru adăposturi de porcine
- controler de microclimat
- controler pentru adăposturi de porcine
- ventilația adăposturilor de porcine
- controler pentru spații de creștere a animalelor tinere
---


# Sursă de alimentare DC50W24VB

Sursă de alimentare de rezervă cu funcție de deschidere automată și manuală a admisiilor și evacuărilor de aer. Utilizată pentru a asigura siguranța animalelor de fermă în cazul întreruperii alimentării sau al defectării controlerului. La detectarea unei anomalii, dispozitivul va semnaliza o alarmă și va deschide mecanismele de ridicare la nivelul setat.

## Parametri și caracteristici: 
-  Comutator de selectare a modului de funcționare: 
    - MANUAL
    - AUTO.
-  Buton rotativ pentru gradul de deschidere a admisiilor.
-  Standarde acceptate:
    - 0-10, 2-10, 10-0, 10-2.
-  Posibilitatea inversării semnalului de comandă.
-  Ieșiri de alarmă NO și NC.
-  Semnalizarea întreruperii alimentării.
-  Monitorizarea tensiunii de comandă 2-10V.
-  Monitorizarea scurtcircuitelor la ieșirile 24VDC.
-  Monitorizarea scurtcircuitelor la ieșirile 0-10V.
-  2 intrare 0-10V.
-  2 ieșiri 0-10V.
-  Protecții electronice ale intrărilor, ieșirilor și liniei 24V.
-  Baterie de acumulatoare 24V 4.0 Ah.
-  Carcasă etanșă IP65.
-  Tensiune de alimentare 85~264VAC 47~63Hz.

# Instalarea controlerului  
:::danger 
În timpul instalării dispozitivului, alimentarea cu energie electrică trebuie obligatoriu deconectată, deoarece tensiunea prezentă pe unele componente este periculoasă pentru viață și sănătate. Se recomandă încredințarea instalării unei persoane calificate.
:::

## Alegerea locului de montaj  

Locul de montaj trebuie ales în mod rațional, ținând cont de accesul facil la dispozitiv pentru persoanele autorizate și de inaccesibilitatea acestuia pentru animale și copii. Trebuie luate în considerare și condițiile climatice, adică dispozitivul trebuie să funcționeze în intervalul de temperatură de la -10°C la 40 °C, într-un loc ferit de lumina solară. În jurul dispozitivului trebuie asigurată circulația liberă a aerului.

# Montaj  

Dispozitivul poate funcționa în condiții climatice agresive. Un dispozitiv montat corect este rezistent la acțiunea nocivă a mediului.

### În timpul montajului trebuie acordată atenție următoarelor aspecte: 
 - capacul trebuie fixat prin strângerea tuturor șuruburilor,
 - cablurile utilizate pentru conectarea dispozitivului trebuie să aibă secțiune circulară,
 - după conectarea cablului, presetupele trebuie strânse astfel încât cablul să fie etanșat și imobilizat; se recomandă utilizarea siliconului,
 - trecerile neutilizate (presetupele) trebuie obturate,
 - partea inferioară a carcasei se fixează pe un perete plan cu 4 dibluri de expansiune.


# Conectarea electrică  

:::danger 
Înainte de conectarea sistemului, asigurați-vă că alimentarea este oprită!
:::

După deșurubarea dispozitivului, panoul frontal trebuie îndepărtat. În acest scop, se scoate cablul panglică din conectorul marcat P1. Se introduc cablurile prin presetupele din cauciuc și se poate începe conectarea acestora. Conectarea trebuie efectuată conform descrierii.

![Conectare](./img/DC50W24VB.png)

**Alimentare 230V AC:** se conectează la alimentare (tabloul de distribuție). Este obligatorie utilizarea unui întreruptor automat de protecție la supracurent (de tip „S” B6) și a descărcătoarelor de supratensiune din clasa „C”. Dispozitivul poate fi alimentat într-un interval larg de tensiuni de la 85V la 264V și de frecvențe de la 47 la 63Hz, fără a afecta funcționarea dispozitivului.  

**Conectorul In1 și In2** trebuie conectat la controler pentru a furniza semnalul de comandă sistemelor de ridicare. Dispozitivul poate deservi două controlere sau un singur controler cu secțiuni separate pentru admisii și evacuări (bornele I1 și I2 trebuie șuntate).  

**Conectorul ALARM** se conectează la centrala de alarmă, în funcție de sistem – contact închis (NO și C), contact deschis (NC și C). Alarma se activează în următoarele cazuri:  •a dispărut tensiunea de alimentare a dispozitivului,  •a dispărut semnalul de comandă 2-10V la cel puțin una dintre intrări,  •a apărut un scurtcircuit al semnalului de ieșire sau valoarea acestuia diferă de cea măsurată,  •a apărut un scurtcircuit pe bara +24V care alimentează mecanismele de ridicare.  

**Conectorul Ouput 1 și Ouput 2** se conectează la actuator (mecanismul de ridicare) în modul cerut de dispozitivul deținut; descrierea conectării trebuie să se găsească în instrucțiunile actuatorului (mecanismului de ridicare) respectiv.  

**Comutatorul modului de funcționare S1** în funcție de actuatorul (mecanismul de ridicare) deținut, trebuie selectat modul de funcționare corespunzător. Implicit, comutatoarele 1,2,3,4,5,6 sunt în poziția off – funcționare 2-10V.
 
| Canal 1 | Canal 2| Funcție |
|------|------|----------|
| 1 – off | 4 – off | Mod de funcționare în intervalul de semnale 2-10V, tensiunea de comandă sub 1,5V generează o alarmă.   |
| 1 – on| 4 – on  | Mod de funcționare în intervalul de semnale 0-10V, fără reacție de alarmă la un semnal sub 1,5V.   |
| 2 – off | 5 – off  | Mod de funcționare proporțional, semnale la ieșire în intervalul 0-10V sau 2-10V.  |
| 2 – on | 5 – on  | Mod de funcționare inversat, semnale la ieșire în intervalul 10-0V sau 10-2V.   |
| 3 – off | 6 – off  | Inversarea intrării dezactivată.  |
| 3 – on | 6 – on   | Inversarea intrării activată.   |

# Principiul de funcționare  

Sursa de alimentare de rezervă, în modul de funcționare normală, alimentează actuatoarele (mecanismele de ridicare) 24V și încarcă sau menține încărcate acumulatoarele, care vor furniza energie în cazul întreruperii alimentării.  Comutatorul AUTO/MANUAL stabilește modul de funcționare al dispozitivului.  

**Modul MANUAL** permite comanda directă a actuatoarelor (mecanismelor de ridicare) de la butonul rotativ de pe panoul dispozitivului.  

**Modul AUTO** – modul de funcționare de bază, transmite semnalul de comandă de la intrare la ieșire, efectuând prelucrarea corespunzătoare în funcție de setările comutatorului „S1” și monitorizează nivelul semnalului de intrare.  În cazul detectării unei anomalii la intrarea respectivă, dispozitivul va furniza la ieșirea sa semnalul de la butonul rotativ de pe panoul frontal.  Releul de alarmă se va activa în cazul:  •unui semnal de intrare prea scăzut (Uin < 1,5V) – comutatorul „S1” 1-off, 4-off,  •unui scurtcircuit al semnalului de ieșire la masă sau la 24V,  •lipsei tensiunii de alimentare,  •unui scurtcircuit al tensiunii 24V.

## Utilizare 

Utilizatorul selectează cu ajutorul comutatorului modul MANUAL, iar cu butonul rotativ gradul de deschidere a admisiilor de aer corespunzător cerințelor – actuatoarele funcționează conform poziției indicate de butonul rotativ. După finalizarea setărilor admisiilor, se selectează cu ajutorul comutatorului modul AUTO și se lasă dispozitivul în această stare – admisiile se vor poziționa la nivelul cerut de controlerul de ventilație. Într-o situație de urgență, admisiile se vor poziționa conform poziției indicate de butonul rotativ.  

## Panoul frontal 

| MENIU                       | Descriere | 
|:---:                       |:---|
|![Conectare](./img/paneldcw50.png) |**Indicator luminos POWER** – semnalizează prezența alimentării și încărcarea acumulatoarelor.  1.**Indicator luminos CHECK** – luminează continuu în modul automat, atunci când la ieșire este transmis semnalul de la controler, și luminează intermitent în cazul furnizării la ieșire a semnalului de la butonul rotativ.  2.**OUT 1** – informează despre anomaliile din canalul 1.  3.**OUT 2** – informează despre anomaliile din canalul 2.  4.**AUTO** – mod de funcționare automat.  5.**MANUAL** – mod de funcționare manual.  6.**Buton rotativ 0%-100%** - selectarea gradului de deschidere a admisiilor de aer.| 

# Mesaje de eroare și avertizare

Mesajele de eroare au rolul de a informa utilizatorul despre anomaliile în funcționarea dispozitivului. Mai jos sunt prezentate mesajele de eroare posibile:
 -  Indicatorul luminos POWER – nu luminează verde – lipsa alimentării de la rețea.
 -  Indicatorul luminos CHECK – luminează intermitent galben – la ieșiri a fost furnizat semnalul de la potențiometru.
 -  Indicatorul luminos OUT 1 – luminează roșu - detectarea unei anomalii (lipsa semnalului de comandă, scurtcircuit la ieșire sau scurtcircuit pe bara 24VDC) în primul canal.
 -  Indicatorul luminos OUT 2 – luminează roșu - detectarea unei anomalii (lipsa semnalului de comandă, scurtcircuit la ieșire sau scurtcircuit pe bara 24VDC) în al doilea canal.

# Observații și avertismente  

:::danger 
În timpul instalării dispozitivului, alimentarea cu energie electrică trebuie obligatoriu deconectată, deoarece tensiunea prezentă pe unele componente este periculoasă pentru viață și sănătate. Se recomandă încredințarea instalării unei persoane calificate.
:::

 - Pentru a evita problemele de exploatare a dispozitivului, este obligatorie consultarea instrucțiunilor înainte de începerea instalării și utilizării. Nu este permisă modificarea construcției sau efectuarea de reparații pe cont propriu. Aceasta se referă în special la modificarea elementelor și componentelor.
 - Operațiunile de întreținere sau de service trebuie efectuate de personal autorizat (instalator sau serviciul de asistență tehnică al producătorului). În adăposturile pentru animale cu ventilație forțată este obligatoriu un sistem de alarmă. 
 - Producătorul dispozitivului nu răspunde pentru daunele cauzate de instalarea incorectă, programarea incorectă a funcțiilor, consecințele evenimentelor fortuite și factorii externi. Dispozitivul necesită setarea parametrilor în conformitate cu condițiile existente în spațiul de creștere a animalelor.Aceste setări sunt individuale și depind de decizia crescătorului. 
 - Producătorul dispozitivului își rezervă dreptul de a modifica construcția dispozitivului și software-ul.
Dispozitivul include o baterie de acumulatoare; nu trebuie permisă descărcarea excesivă a acestora, deoarece aceasta poate provoca deteriorarea bateriei. 
Scurtcircuitarea bornelor bateriei poate provoca un incendiu.  


:::caution
![text alternativ](./img/trash.svg) La sfârșitul utilizării produsului, acesta nu trebuie aruncat împreună cu deșeurile municipale nesortate, ci eliminat în conformitate cu reglementările în vigoare (directivele WEEE ale Uniunii Europene 2012/19/UE).  Produsul a fost fabricat în conformitate cu cerințele RoHS (Directiva Uniunii Europene 2011/65/UE).
:::

<!-- \newpage -->
# Date tehnice ale controlerului  

|Parametru                        |	DESCRIERE      |
|:-----------                    |:---------- |
|Tensiune de alimentare alternativă|	85~264VAC 47~63Hz|
|Tensiune de alimentare continuă|	120~370VDC|
|Tensiune de ieșire|	27,6VDC|
|Curent maxim de ieșire|	1,8A|
|Randament|	85%|
|Curent maxim al ieșirilor de comandă 0-10V|	30mA|
|Curent maxim al ieșirii (contactului) ALARM|	3A|
|Protecție la supratensiune a intrărilor și ieșirilor|	DA|
|Protecție la scurtcircuit|	Automată |
|Baterie de acumulatoare|	4Ah 24V|
|Interval de temperatură de funcționare|	-10 +40oC|
|Dimensiunile dispozitivului|	20x15x8 cm|
|Grad de protecție al carcasei|	IP65|

:::info
Controlerul IC-AC include în set:
 - dibluri de expansiune - 	4 buc., 
 - acumulatoare 12V 4Ah - 	2 buc., 
 - presetupă PG13,5 -	1 buc.,
 - presetupă PG11 -	3 buc., 
 - presetupă PG9 -	3 buc.
:::

