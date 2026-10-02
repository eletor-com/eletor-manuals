---
sidebar_position: 3
title: Instrucțiuni SC-12
description: Controler de climat pentru adăposturi pentru animale cu un curent de
  ieșire admis de până la 12A
keywords:
- eletor sc-12
- controler de ventilație
- controler de climat
- controler de ventilație pentru adăposturi pentru porcine
- controler de microclimat
- controler pentru adăposturi pentru porcine
- ventilația adăposturilor pentru porcine
- controler pentru adăposturi de creștere
---

# Controler SC-12

Controler de climat cu microprocesor din seria SPEED CONTROL. Versatilitatea dispozitivului este asigurată de numărul mare de intrări/ieșiri ale sistemului și de software-ul intuitiv în limbile polonă și engleză. Pe lângă setările de bază pentru temperaturi, aerisire, încălzire suplimentară, nivelurile min./max. de ventilație și alarme, programul controlerului permite testarea și salvarea calibrării actuatoarelor care funcționează împreună cu controlerul.

**Parametri și caracteristici:** 
- Ventilația grupei I: 
  - curentul max. al ieșirii cu reglare continuă 12A,
  - protecție termică a sistemului, 
  - pornire lină a ventilației – pornire progresivă,
  - releu de bypass la comandă maximă, 
  - calibrarea turației minime, 
  - program de economisire a energiei cu sistem de clapete deschise în avans.
- Ventilația grupei II, contact izolat până la 6A.
- Încălzire suplimentară, contact izolat până la 6A
- Ieșiri de alarmă NO și NC: 
  - semnalizarea întreruperii alimentării,
  - semnalizarea depășirii pragului de temperatură min. sau max.,
  - avertizor acustic încorporat.
- Ieșiri independente 3 0..10V:
  - funcționare împreună cu module de extensie,
  - comanda sistemului de clapete, 
  - reglarea încălzirii cu putere variabilă.**
- Două intrări analogice pentru măsurarea temperaturii.
- Port digital pentru măsurarea temperaturii (până la 4 senzori).
- Două ieșiri funcționale cu releu (la alegere):
  - funcționare împreună cu actuatoare liniare, 
  - III și IV grupe de ventilație
- Două intrări analogice 0-10V.
- Alimentare pentru potențiometru DC 10V.
- Alimentare suplimentară DC 12V.
- Posibilitate de conectare la un calculator până la 1200m.
- Carcasă etanșă IP65.
- Tensiune de alimentare 230VAC 50Hz.
- Puterea absorbită de sistem < 10V

# Instalarea controlerului
:::danger 
 În timpul instalării dispozitivului, alimentarea cu energie electrică trebuie deconectată obligatoriu, deoarece tensiunea de pe unele componente prezintă pericol pentru viață și sănătate. Se recomandă încredințarea instalării unei persoane calificate.  Această operațiune este periculoasă
:::

## Alegerea locului de montaj
Locul de montaj trebuie ales în mod rațional, ținând cont de accesul facil al persoanelor autorizate la aparat și de inaccesibilitatea acestuia pentru animale și copii. Trebuie luate în considerare și condițiile climatice, adică dispozitivul trebuie să funcționeze în intervalul de temperatură de la -10°C până la 40 °C, într-un loc neexpus la soare. În jurul dispozitivului trebuie să existe o circulație liberă a aerului. Dispozitivul include un senzor de temperatură.  

### Se aplică următoarele reguli pentru montarea senzorului de temperatură:
 - senzorul nu trebuie montat într-un loc fără circulație a aerului sau expus direct la soare,
 - senzorul nu trebuie montat pe un perete portant (exterior) al clădirii,
 - trebuie evitată apropierea de dispozitive care emit căldură, precum radiatoare și lămpi,
 - senzorul nu trebuie amplasat direct lângă uși și orificii de ventilație,
 - senzorul nu trebuie amplasat în locuri accesibile animalelor,
 - se recomandă amplasarea cablului de conectare a senzorului departe de cablurile de alimentare.

# Montaj
Dispozitivul poate funcționa în condiții climatice agresive. Controlerul și senzorul de temperatură montate corect sunt rezistente la acțiunea nocivă a mediului.  

### În timpul montajului trebuie acordată atenție următoarelor aspecte:
 - înainte de înșurubare trebuie verificată garnitura capacului,
 - capacul trebuie fixat prin strângerea tuturor șuruburilor,
 - cablurile utilizate pentru conectarea controlerului trebuie să fie rotunde,
 - după conectarea cablului trebuie strânse presetupele astfel încât cablul să fie etanșat și imobilizat, se recomandă utilizarea siliconului,
 - trecerile neutilizate (presetupele) trebuie obturate,
 - controlerul (partea inferioară a carcasei) se fixează pe un perete plan cu 4 dibluri de expansiune.

# Conectarea electrică
:::danger 
 Înainte de conectarea sistemului, asigurați-vă că alimentarea este oprită!
Această operațiune este periculoasă
:::

Înainte de conectarea controlerului trebuie deșurubat și îndepărtat capacul. Introduceți cablurile prin presetupele din cauciuc, apoi puteți trece la conectarea acestora. Bornele controlerului sunt prezentate în figura de mai jos.

![Conectare ](./img/sc-12.png)

**Conectorul AC 230V** se conectează la alimentare (tabloul de distribuție). Este necesară utilizarea unui întreruptor de protecție la supracurent 1P-B6 și a unor limitatoare de supratensiune de tip T1 T2. O bună practică la conectarea mai multor dispozitive este gruparea controlerelor pe „faze” diferite (L1, L2, L3), pentru încărcarea uniformă a liniei de alimentare.

**Conectorul FAN** trebuie conectat direct la ventilator; în cazul comenzii mai multor ventilatoare, sarcina totală nu poate depăși 6A, iar fiecare ventilator trebuie protejat separat. PE și N nu trebuie preluate de la alimentare (tabloul de distribuție), ci trebuie obligatoriu conectate la bornele controlerului.

**Conectorul FAN 2** poate fi utilizat pentru conectarea ventilatoarelor grupei 2 sau a sistemelor de stropire. Ieșirea este izolată, curentul maxim al contactului este 6A (este necesar un întreruptor extern de protecție la supracurent de tip 1P-B6 în cazul comenzii directe a sarcinii), contactul se închide atunci când temperatura măsurată este mai mare decât suma temperaturii setate și a benzii de ventilație.

**Conectorul HOT** poate fi utilizat pentru conectarea unui încălzitor de aer. Ieșirea este izolată, curentul maxim al contactului este 6A (este necesar un întreruptor extern de protecție la supracurent 1P-B6 în cazul comenzii directe a sarcinii), contactul se închide atunci când temperatura măsurată scade sub valoarea setată.

**Conectorul ALARM** are ieșiri izolate NC, C și NO destinate conectării la centrala de alarmă. Alarma se activează în următoarele cazuri:
    - temperatura este prea scăzută sau prea ridicată,
    - controlerul sau senzorul de temperatură s-a defectat,
    - tensiunea de alimentare a controlerului a fost întreruptă,
    - a apărut o funcționare necorespunzătoare a controlerului (de exemplu, supraîncălzirea controlerului)
Figura de mai jos prezintă modul de conectare a ventilatorului la centrala de alarmă.

![Conectarea alarmei](./img/alarmsc-s.png)

**Conectorii FUNC1 și FUNC2** servesc la conectarea mecanismului de ridicare pentru deschiderea admisiilor de aer, bazat pe un motor cu rotație dreapta/stânga. Releul FUNC1 conectează alimentarea actuatorului, iar FUNC2 comută sensul de rotație al motorului. Exemplu de schemă de conectare a mecanismului de ridicare (este necesar un întreruptor extern de protecție la supracurent 1P-B6):
La dezactivarea funcției mecanismului de ridicare, ieșirile FUNC1 și FUNC2 funcționează ca contacte ale grupelor de ventilație 3 și, respectiv, 4.

![Conectarea mecanismului de ridicare](./img/Sc-12fan.png)

**Conectorul 12V** este destinat alimentării senzorilor externi.

**Conectorul V1 0-10V** servește la conectarea modulelor de extensie a puterii. Tensiunea la această bornă este proporțională cu nivelul de ventilație.

**Conectorul V2 0-10V** servește la conectarea actuatorului care deschide clapetele de admisie a aerului.

**Conectorul V3 0-10V** servește la conectarea unui sistem de încălzire cu putere reglabilă continuu. Tensiunea la această ieșire crește proporțional cu scăderea temperaturii, începând de la temperatura de încălzire suplimentară.

**Conectorul 10V** servește la alimentarea potențiometrului mecanismului de ridicare sau a altor sisteme de tip 0-10V.

**Conectorul SENS1 (SENS2)** se conectează la senzorul de temperatură 1 TS3 sau TS5, polaritatea nu are importanță. În cazul conectării simultane a 2 senzori, se calculează media temperaturilor măsurate. O bună practică este amplasarea cablurilor de măsurare departe de cablurile de alimentare.

**Conectorul 1-WIRE** poate fi utilizat pentru conectarea unui număr mai mare de senzori digitali de temperatură, maximum 4, conectați în paralel (trebuie respectată polaritatea corespunzătoare). Lungimea maximă a cablului de conectare a senzorilor este 150m (lungimea nu influențează măsurarea temperaturii), se recomandă utilizarea unui cablu ecranat.

**Conectorul RS-485** poate fi utilizat pentru realizarea sistemelor de ventilație și pentru comunicarea cu un calculator PC.

**Conectorul IN1 0-10** servește la introducerea semnalului de reacție de la sistemul de admisii de aer – indică poziția actuală a admisiilor.

**Conectorul IN2 0-10** servește la conectarea controlerului la alți senzori, de exemplu de umiditate, CO2, sau la funcționarea controlerului ca extensie de putere.

# Principiul de funcționare
Sarcina principală a controlerului este menținerea temperaturii în adăpostul pentru animale la nivelul stabilit de crescător. Trebuie reținut că controlerul este doar un instrument care ajută la asigurarea condițiilor climatice optime în adăpostul pentru animale. Rolul principal în acest proces îi revine însă crescătorului, care trebuie să adapteze setările dispozitivului la condițiile climatice exterioare în schimbare și, mai ales, la cerințele animalelor din adăpost, precum și să monitorizeze starea de funcționare a dispozitivului prin intermediul centralei de alarmă.

## Prima punere în funcțiune a controlerului
:::danger 
 La prima punere în funcțiune a controlerului trebuie obligatoriu setată banda interzisă de funcționare a motorului.

:::
Controlerul funcționează împreună cu ventilatoare bazate pe un motor asincron monofazat, cu un consum total maxim de curent de 12A. După conectarea ventilatoarelor alese, utilizatorul trebuie să le adapteze pentru funcționarea împreună cu controlerul. Cu alte cuvinte, este necesară setarea nivelului minim de funcționare (turației) ventilatorului. Această funcție se numește „Bandă interzisă” și este setată o singură dată de către utilizator din „Setări avansate”. Pentru efectuarea corectă a acestei operațiuni, este indicat ajutorul unei a doua persoane, care să poată observa permanent comportamentul ventilatorului în timp ce cealaltă persoană setează valoarea „Benzii interzise” (valoarea din fabrică este 0). Lipsa setării benzii interzise poate duce la funcționarea necorespunzătoare a dispozitivului. Valoarea „Benzii interzise” poate fi considerată corectă atunci când presiunea produsă de ventilator începe să ridice ușor clapetele coșului de ventilație. Operațiunea de setare a „Benzii interzise” trebuie repetată atunci când se schimbă ventilatorul conectat la controler.

## Aerisire periodică
Aerisirea este o funcție executată de controler, care se activează atunci când temperatura din încăpere scade sub temperatura setată. Această funcție asigură animalelor un aport ciclic de aer proaspăt. În meniul Aerisire se găsesc 3 parametri:
- **„Timp de funcționare”** - stabilește pentru câte minute trebuie pornit ventilatorul;
- **„Timp de pauză”** - stabilește timpul de oprire a ventilatorului;
- **„Nivel de aerisire”** - stabilește puterea ventilației în „Timpul de funcționare”.

Toți parametrii enumerați mai sus sunt setați de utilizator. 

### La setarea parametrilor de aerisire trebuie reținute câteva reguli:
- aerisirea se activează exclusiv atunci când temperatura din adăpostul pentru porcine scade sub temperatura setată,
- funcția de bază a aerisirii este asigurarea unui aport ciclic de aer proaspăt pentru animale, nu menținerea temperaturii setate în încăpere,
- se recomandă aerisirea încăperilor pentru perioade scurte, dar frecvente,
- trebuie evitate perioadele lungi de aerisire, deoarece acestea pot duce la variații prea mari ale temperaturii,
- parametrii setați trebuie obligatoriu adaptați la comportamentul animalelor și la condițiile existente atât în interiorul, cât și în exteriorul încăperii.

## Modul de funcționare a dispozitivului
Controlerul reglează continuu ventilația de la **„Min.1” până la „Max.1”** în intervalul de la **„Temperatura setată”** până la suma **„Temperaturii setate”** și a **„Benzii de ventilație 1gr.”**. Peste acest interval se activează grupa de ventilație 2, iar grupa 1 își schimbă nivelul la **„Min.2”**; la creșterea ulterioară a temperaturii, ventilația va crește până la **„Max.2”**, la capătul intervalului **„Benzii de ventilație 2 gr.”**. În cazul în care **„Banda de ventilație 2 gr.”** este setată la zero, iar ventilația funcționează la **„Max.1”**, se activează grupa de ventilație 2, iar creșterea ulterioară a temperaturii nu mai produce nicio modificare a ventilației (partea punctată a graficului). În cazul în care temperatura din încăpere scade sub **„Temperatura setată”**, controlerul aerisește periodic încăperea, iar la o scădere ulterioară se activează încălzirea suplimentară. Totul depinde de setările introduse de utilizator. Programul controlerului prevede și funcționarea împreună cu o centrală de alarmă, care poate fi activată atunci când temperatura din adăpostul pentru porcine se abate de la parametrii setați. 

![Ventilație](./img/Sc-12wentyl.png)  

## Programarea controlerului
Controlerul are un set de setări implicite, care sunt scrise în memoria nevolatilă în două cazuri:
1. Prima punere în funcțiune a dispozitivului,
2. Eroare în memoria de date.
În cazul lipsei sau întreruperii alimentării, controlerul nu pierde setările utilizatorului introduse și salvate anterior.

## Panoul frontal – indicatoare, butoane și afișaj
![Panou](./img/SC-12panel.png)  
    1. Indicator luminos roșu care semnalizează depășirea temperaturii maxime admise.
    2. Indicator luminos roșu care semnalizează depășirea limitei inferioare a temperaturii admise.
    3. Indicator luminos galben care semnalizează încălzirea suplimentară.
    4. Indicator luminos galben care semnalizează ventilația grupei 2.
    5. Indicator luminos verde care semnalizează setarea manuală a nivelului de ventilație.
    6. Indicator luminos verde care semnalizează funcționarea comunicației RS485.
    7. Afișajul meniului, care indică temperatura în starea normală de funcționare.
    8. Indicator cu bare care semnalizează nivelul de ventilație.
    9. Tastă pentru deplasarea în sus în meniu sau modificarea valorii parametrului.
    10. Tasta ESC - ieșire din meniu sau dintr-un anumit parametru fără salvarea valorii.
    11. Tasta OK - intrare în meniu sau confirmarea (salvarea) unui anumit parametru.
    12. Tastă pentru deplasarea în jos în meniu sau modificarea valorii parametrului.

## Utilizarea meniului
Controlerul este echipat cu o serie de funcții care permit adaptarea acestuia la o anumită aplicație. Aceste funcții sunt grupate într-un meniu, accesibil prin apăsarea uneia dintre tastele **(„+”, „-” sau „OK”)**. Tastele **„+”** și **„-”** servesc la selectarea funcției, iar editarea, salvarea datelor sau accesarea unui nivel inferior se pot efectua cu tasta **„OK”**. Apăsați tasta **„Esc”** pentru revenirea la meniul superior sau pentru renunțarea la salvarea unui anumit parametru.

## Funcțiile meniului de bază

| MENIU                          | Descriere       | 
|:-----------                   |:---------- |
| Temperatura 20,8o C W16% A    | **Mod informativ** - de funcționare normală. Afișajul indică temperatura actuală și, atunci când ventilatorul este pornit, valoarea nivelului de ventilație. Semnificația simbolurilor suplimentare:A-indică alarma activată,D  - indică încălzirea activată, W - indică ventilația suplimentară| 
|   Temp. setată   20,0o C      |**„Temperatura setată”** – Stabilește temperatura de la care începe procesul de ventilație cu reglare continuă. Trebuie aleasă o valoare corespunzătoare în funcție de specia animalelor de fermă.| 
| Aerisire     | **Aerisire** – se setează două valori de timp.    1.**Timp de funcționare** Stabilește numărul de minute de funcționare a ventilației.    2.**Timp de pauză** Stabilește numărul de minute de oprire a ventilației între ciclurile succesive de funcționare.    3.**Nivel de aerisire** - Stabilește intensitatea ventilației în timpul funcționării aerisirii.| 
| Alarmă |  1.**Alarmă activă Da** - Activarea/Dezactivarea contactului de alarmă; pentru ca controlerul să nu emită semnal de alarmă la ieșire (către centrala de alarmă), selectați „NU” în meniu.  2. **Temp. Min. 15,0o C** - Stabilește temperatura minimă absolută la care se activează alarma.  3.**Temp. Max. 25,0o C** - Stabilește temperatura maximă absolută la care se activează alarma.  4.**Semnal alarmă Da** - Activarea/Dezactivarea semnalului acustic din interiorul controlerului. | 
|    Ventilație        |  1.**Bandă vent. 1 5,0o C**   - Stabilește viteza de reacție a controlerului (modificarea nivelului de ventilație de la minimum 1 până la maximum 1) la creșterea temperaturii.  2.**Nivel min. 1 1 %** - Stabilește nivelul de ventilație corespunzător temperaturii setate.  3.**Nivel max. 1 100 %**-Stabilește nivelul constant de ventilație pentru temperatura care depășește intervalul de reglare continuă, când „Banda vent. 2gr.” = 0, în caz contrar nivelul maxim al ventilației reglate pentru temperatura egală cu suma temperaturii setate și a benzii grupei 1.  4.**Bandă vent. 2 0,0o C**-Stabilește viteza de reacție a controlerului (modificarea nivelului de ventilație de la minimum 2 până la maximum 2) la creșterea temperaturii pentru grupa 2. Funcția este inactivă când banda este egală cu zero.  5.**Nivel min. 2 1 %**-Stabilește nivelul minim de ventilație al grupei 1 în punctul închiderii contactelor grupei 2.  6.**Nivel max. 2 100 %**-Stabilește nivelul constant de ventilație pentru temperatura care depășește intervalul de reglare continuă, când grupa 2 este activată.  7.**Grupa 3  5,0o C**-Stabilește nivelul constant de ventilație pentru temperatura care depășește intervalul de reglare continuă, când grupa 2 este activată.  8.**Grupa 4 7,0o C**-Stabilește temperatura raportată la temperatura setată pentru activarea grupei de ventilație 4 (funcția mecanismului de ridicare trebuie dezactivată).| 
|    Încălzire suplimentară  |  1.**Temp. încălz. supl. 15,0o C**-Stabilește temperatura de activare a încălzirii suplimentare.  2.**Bandă încălz. supl. 5,0o C** -Stabilește proporția puterii sistemelor de încălzire suplimentară (la ieșirea V3 0-10V) în funcție de temperatură. | 

## Funcțiile meniului avansat
Meniul avansat este destinat în principal instalatorilor și permite adaptarea controlerului la instalație și la ventilator, testarea circuitelor și selectarea limbii meniului. Accesarea setărilor avansate se face prin apăsarea și menținerea apăsată a două taste ale meniului timp de aproximativ 10s. 

| MENIU                          | Descriere       | 
|:-----------                   |:---------- |
|Testare  |Această funcție servește la verificarea fiecărui circuit de acționare al controlerului; toate setările sunt temporare, fiind valabile doar cât timp este accesată poziția respectivă din meniu; după apăsarea tastei „ESC” sau „OK”, ieșirea respectivă revine la starea determinată de funcționarea controlerului.  1.**Ventilație 0 %**  Permite introducerea manuală a nivelului de ventilație pentru verificarea sistemului de ventilație. După confirmarea funcției se aprinde indicatorul luminos verde (mână).  2.**Alarmă Nu** Activarea determină aprinderea a 2 indicatoare luminoase roșii, activarea semnalului sonor și a circuitului de alarmă.  3.**Încălzire suplimentară Nu** Activarea determină aprinderea indicatorului luminos galben (flacără) și activarea circuitului de încălzire suplimentară.  4.**Vent. 2 treaptă Nu** Activarea determină aprinderea indicatorului luminos galben (ventilator) și activarea circuitului grupei 2.  5.**Ieșire V1 0,0 V  Ieșire V2  0,0 V Ieșire V3  0,0 V**-Testarea ieșirilor 0-10V; cu tastele „+” sau „-” se poate seta tensiunea aleasă pentru sistemele, în ordine: module de extensie, clapete de admisie, încălzire suplimentară cu reglare continuă. Funcția este deosebit de utilă la calibrarea ieșirii V2 a clapetelor de admisie.  6.**Mecanism de ridicare 0** Permite verificarea sistemului de clapete de admisie: „+” - deschide admisiile, „-” - închide admisiile; afișajul prezintă poziția actuală a actuatorului, citită de la potențiometru.  7.**Grupa 3 Nu**  Activarea determină activarea circuitului grupei de ventilație 3. (funcția mecanismului de ridicare trebuie dezactivată)  8.**Grupa 4 Nu**  Activarea determină activarea circuitului grupei de ventilație 4. (funcția mecanismului de ridicare trebuie dezactivată)|
|Limbă        | Selectarea limbii meniului. Se poate alege limba polonă sau engleză. | 
|Ventilator         |  1.**Bandă interzisă 0**- Calibrarea turației minime a ventilatoarelor conectate direct la controler; acest parametru corespunde nivelului de ventilație „1%”. O valoare pozitivă a parametrului crește turația, iar o valoare negativă o reduce.  2.**Modul ext. Min. 1,9 V** -Tensiunea minimă aplicată modulului de extensie a puterii (ieșirea V1 0-10V).  3.**Modul ext. Max. 10,0 V** -Tensiunea maximă aplicată modulului de extensie a puterii (ieșirea V1 0-10V).  4.**Deconectare modul Nu** - Deconectarea modulului de extensie a puterii; când este selectat „DA”, tensiunea la ieșirea de comandă a modulelor de extensie (V1 0-10V) scade la nivelul 0V, nu la valoarea minimă setată, atunci când nivelul de ventilație este 0%.  5.**Inversare  Nu**-Activarea determină inversarea caracteristicii ieșirii V1. Tensiunea va scădea odată cu creșterea nivelului de ventilație în intervalul stabilit prin min.-max. Semnalul la ieșirea V1 va fi de tip 10-0V.| 
| Clapete de admisie       |  1.**Avans 0,0o C**-Deschiderea anticipată a clapetelor de admisie. Parametrul setat stabilește cu cât trebuie să fie temperatura mai mică decât „Temperatura setată” pentru deschiderea anticipată a clapetelor de admisie.  2.**Închidere completă  Nu**- Activarea determină scăderea tensiunii la ieșirea de comandă a clapetelor de admisie (V2 0-10V) la nivelul 0V, nu la valoarea minimă setată. În cazul lipsei ventilației (nivel de ventilație 0%).  3.**Clapete min.  1,9 V**- Tensiunea minimă aplicată clapetelor de admisie (ieșirea V2 0-10V).  4.**Clapete max.  10,0 V**- Tensiunea maximă aplicată clapetelor de admisie (ieșirea V2 0-10V).  5.**Inversare   Nu**-Activarea determină inversarea caracteristicii ieșirii V2. Tensiunea va scădea odată cu creșterea nivelului de ventilație în intervalul stabilit prin min.-max. Semnalul la ieșirea V2 va fi de tip 10-0V. |  
| Măsurarea temperaturii  |  1.**Calibrare S1 23,0o C -> 23,5o C**,**Calibrare S2 23,0o C -> 23,2o C** - Calibrarea pentru intrările analogice permite redimensionarea temperaturii citite de la senzorii S1 și S2.  2.**Timp de mediere 60 s**- Acest parametru stabilește intervalul de timp în care se calculează media citirilor curente de temperatură. Valoarea temperaturii medii este parametrul de bază al funcțiilor controlerului. Modificările stării ieșirilor (ventilație, încălzire suplimentară, clapete, grupe succesive de ventilație, alarme,...) sunt strâns legate de acest parametru și nu pot apărea mai frecvent decât intervalul de timp stabilit aici. | 
| Mecanism de ridicare      |  1.**Calibrare desch. 1024 -> 853**,**Calibrare înch. 0 -> 324** -Calibrarea mecanismului de ridicare este necesară pentru funcționarea corectă a sistemului de admisii de aer. Tasta „+” deschide admisiile, iar tasta „-” închide admisiile. În timpul deschiderii admisiilor, parametrul poziției trebuie să crească, iar în timpul închiderii să scadă; în caz contrar, trebuie verificată conectarea actuatorului (alimentare și potențiometru). La calibrarea deschiderii, deschideți admisiile la maximum și confirmați poziția cu tasta „OK”. La calibrarea închiderii, închideți admisiile și confirmați poziția cu tasta „OK”. Tasta „ESC” permite ieșirea din funcție fără salvare. Diferența dintre poziția de deschidere și cea de închidere trebuie să fie de min. 100 unități.  2.**Dezactivare Nu**-Dezactivarea eliberează contactele FUNC1 și FUNC2 de comanda mecanismului de ridicare; aceste contacte îndeplinesc atunci rolul de ventilație pentru grupele 3 și 4.| 
| Pornire progresivă               | Parametrii din această grupă de meniu sunt responsabili pentru pornirea ventilației. Activarea ventilației în grupa cu reglare continuă este precedată de o pornire treptată până la 100%, o scurtă funcționare la 100%  și o scădere până la nivelul de ventilație necesar. Astfel, la pornirea ventilației se produce un jet de aer care facilitează deschiderea clapetelor fluture din coșuri.   Valorile sunt exprimate în perioade ale tensiunii de alimentare la 1% ventilație.  1.**Timp de accelerare 5**- Parametrul stabilește viteza de creștere a turației ventilației de la nivelul zero până la cel maxim – pornirea lină a ventilatoarelor. Valoarea 0 dezactivează accelerarea lină.  2.**Timp 100%   100**- Parametrul stabilește timpul de funcționare la pornire la 100% din nivelul de ventilație. Setarea timpului de accelerare și a 100% la 0 dezactivează complet jetul de aer la pornirea ventilației.  3.**Timp de decelerare 5**-  Parametrul stabilește viteza modificărilor nivelului de ventilație. | 
|Încălzire suplimentară              |  1.**Inversare contact Nu**-Activarea determină inversarea caracteristicii ieșirii HOT. Contactul va fi  deschis odată cu scăderea temperaturii măsurate.  2.**Histerezis  0,5o C** - Stabilește nivelul histerezisului de temperatură pentru contactul de încălzire suplimentară.  3.**Funcționare relativă Nu**- Activarea determină setarea relativă a temperaturii de încălzire suplimentară în raport cu temperatura setată. Meniul de bază al încălzirii suplimentare se modifică, fiind introdusă diferența față de temperatura setată.  4.**Încălzire suplimentară min. 1,9 V** - Tensiunea minimă aplicată pentru comanda continuă a încălzirii – încălzitor de aer cu debit variabil al ventilatorului (ieșirea V3 0-10V).  5.**Încălzire suplimentară max. 10,0 V** - Tensiunea maximă aplicată pentru comanda continuă a încălzirii – încălzitor de aer cu debit variabil al ventilatorului (ieșirea V3 0-10V).| 
| Program 	|  **vers. 2.4  apr. 13 2018** - 	Citirea versiunii software-ului și a datei compilării|

## Mesaje de eroare și avertizare

Mesajele de eroare servesc la informarea utilizatorului despre neregulile în funcționarea controlerului. Mai jos sunt prezentate mesajele de eroare posibile

|EROARE                            |	DESCRIERE      |
|:-----------                    |:---------- |
|Alarmă     Suprasarcină 	     |Alarmă de suprasarcină, activată la 75°C. Dispozitivul își suspendă funcționarea până la răcire.|
|Alarmă  Lipsă senzor|Semnalizează lipsa sau defectarea senzorului ori a cablului de conectare.|

# Observații și avertizări 
:::danger 
 În timpul instalării dispozitivului, alimentarea cu energie electrică trebuie deconectată obligatoriu, deoarece tensiunea de pe unele componente prezintă pericol pentru viață și sănătate. Se recomandă încredințarea instalării unei persoane calificate.

:::
- Pentru a evita problemele de exploatare a dispozitivului, este necesară citirea instrucțiunilor înainte de instalare și utilizare.
- Este interzisă intervenția asupra construcției dispozitivului sau efectuarea reparațiilor pe cont propriu. Acest lucru se referă în special la modificarea elementelor și componentelor. 
- Operațiunile de întreținere sau service trebuie efectuate de personal autorizat (instalator sau serviciul de asistență tehnică al producătorului). În adăposturile pentru animale cu ventilație forțată este necesar un sistem de alarmă. Producătorul dispozitivului nu răspunde pentru daunele cauzate de instalarea necorespunzătoare, programarea incorectă a funcțiilor, consecințele evenimentelor fortuite și factorii externi. 
- Controlerul de ventilație necesită setarea parametrilor în conformitate cu condițiile existente în adăpostul pentru animale. Aceste setări sunt individuale și depind de decizia crescătorului. Producătorul dispozitivului își rezervă dreptul de a modifica construcția dispozitivului și software-ul.

:::caution
<div class="warning-container">
  <p>
    <strong></strong> La încheierea utilizării produsului, acesta nu trebuie aruncat împreună cu deșeurile municipale nesortate, ci eliminat în conformitate cu reglementările în vigoare (directivele WEEE ale Uniunii Europene 2012/19/UE).
Produsul a fost realizat în conformitate cu cerințele RoHS (Directiva Uniunii Europene 2011/65/UE).
  </p>
</div>
:::
:::tip

## Date tehnice ale controlerului
|Parametru                        |	DESCRIERE      |
|:-----------                    |:---------- |
|Tensiune de alimentare|	230VAC 50Hz|
|Curentul maxim al ieșirii cu reglare continuă FAN|	12A|
|Intervalul de reglare a tensiunii de ieșire|	70V ÷ 230V|
|Curentul maxim al ieșirii (contactului) FAN 2|	6A|
|Curentul maxim al ieșirii (contactului) HOT|	6A|
|Curentul maxim al ieșirii (contactului) ALARM|	4A|
|Curentul maxim al ieșirii (contactului) FUNC1 și FUNC2|	4A|
|Intervalul temperaturii de funcționare|	-10 +40oC|
|Intervalul de măsurare a temperaturii|	0 +50oC|
|Rezoluția măsurării temperaturii|	0,1oC|
|Detectarea defectării senzorului de temperatură|	DA|
|Numărul maxim de senzori analogici|	2|
|Precizia măsurării temperaturii – intrare analogică|	1oC|
|Dependența măsurării de rezistența cablurilor – intrare analogică|	15,8Ω/oC|
|Numărul maxim de senzori digitali|	4|
|Precizia măsurării temperaturii – intrare digitală|	0,5oC|
|Dependența măsurării de rezistența cablurilor – intrare digitală|	Niciuna|
|Lungimea maximă a liniei de conectare a senzorilor digitali|	150m|
|Rezistența la supratensiuni (max E)|	210J|
|Protecție la suprasarcină|	75oC|
|Dimensiunile dispozitivului|	34x29x12 [cm]|
|Gradul de etanșeitate al carcasei|	IP56|
:::

:::info
Controlerul SPEED CONTROL-12 v2  include în pachet:
 - 1 senzor de temperatură,
 - 4 dibluri de expansiune,
 - 2 presetupe PG13,5.
 - 3 presetupe PG11,
 - 4 presetupe PG9.
:::















































































