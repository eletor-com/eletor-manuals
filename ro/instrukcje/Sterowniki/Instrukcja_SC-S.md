---
sidebar_position: 2
title: Instrucțiuni SC-S
description: Controler de climat pentru adăposturi zootehnice cu un curent de ieșire
  admisibil de până la 5A
keywords:
- eletor sc-s
- controler de ventilație
- controler de climat
- controler de ventilație pentru adăposturi de porcine
- controler de microclimat
- controler pentru adăposturi de porcine
- ventilația adăposturilor de porcine
- controler pentru adăposturi de creștere
---


# Controler SC-S

Controler de climat cu microprocesor din familia SPEED CONTROL. Controler fiabil, simplu de instalat și de exploatat, cu software în limbile polonă, engleză, rusă și germană. Programul controlerului permite configurarea intuitivă a parametrilor: temperaturi, aerisire, încălzire suplimentară, niveluri min./max. de ventilație și alarme.

**Parametri și caracteristici:**  
- Ventilația grupei I:
  - curentul max. al ieșirii de reglare continuă 6A,
  - protecție termică a circuitului,
  - pornire lină a ventilației,
  - calibrarea turației minime
- Ventilația grupei II, contact izolat până la 3A (1 opțional)
- Încălzire suplimentară, contact izolat până la 3A (1 opțional)
- Ieșiri de alarmă NO și NC:
  - semnalizarea întreruperii alimentării,
  - semnalizarea depășirii pragului de temperatură min. sau max.
- 1 intrare analogică pentru măsurarea temperaturii
- 2 ieșiri 0-10V
- Puterea absorbită de circuit < 3W
- Carcasă etanșă IP56
- Tensiune de alimentare 230VAC 50Hz

## Instalarea controlerului  
:::danger 
În timpul instalării dispozitivului, alimentarea cu energie electrică trebuie obligatoriu deconectată, deoarece tensiunea prezentă pe unele componente este periculoasă pentru viață și sănătate.  
Se recomandă încredințarea instalării unei persoane calificate.
:::

### Alegerea locului de montaj  

Locul de montaj trebuie ales în mod rațional, ținând cont de accesul facil la aparat al persoanelor autorizate și de inaccesibilitatea acestuia pentru animale și copii. Trebuie avute în vedere și condițiile climatice, adică dispozitivul trebuie să funcționeze în intervalul de temperatură de la -10°C până la 40°C, într-un loc neexpus la soare. În jurul dispozitivului trebuie asigurată circulația liberă a aerului. Dispozitivul include un senzor de temperatură. Pentru montarea senzorului de temperatură se aplică următoarele reguli:  
- senzorul nu trebuie montat într-un loc fără circulație a aerului sau expus direct la soare
- senzorul nu trebuie montat pe peretele portant (exterior) al clădirii,
- evitați apropierea de dispozitive care emit căldură, precum radiatoare, lămpi,
- nu amplasați senzorul direct lângă uși și orificii de ventilație,
- nu amplasați senzorul în locuri accesibile animalelor,
- se recomandă pozarea cablului de conectare a senzorului la distanță de cablurile de alimentare.

### Montaj  

Dispozitivul poate funcționa în condiții climatice dificile. Controlerul și senzorul de temperatură montate corect sunt rezistente la acțiunea mediului.
În timpul montajului trebuie acordată atenție următoarelor aspecte:  
- înainte de înșurubare trebuie verificată garnitura capacului,
- capacul trebuie strâns cu toate șuruburile,
- cablurile utilizate pentru conectarea controlerului trebuie să fie rotunde,
- după conectarea cablului trebuie strânse presetupele, astfel încât cablul să fie etanșat și imobilizat; se recomandă utilizarea siliconului,
- trecerile neutilizate (presetupele) trebuie obturate,
- controlerul (partea inferioară a carcasei) se fixează pe un perete plan cu 4 dibluri de expansiune.

## Conectarea electrică  

:::danger 
Înainte de conectarea circuitului, asigurați-vă că alimentarea este oprită!
:::

Înainte de a începe conectarea controlerului, trebuie deșurubat și îndepărtat capacul. Introduceți cablurile prin presetupele din cauciuc, apoi puteți începe conectarea acestora. Bornele controlerului sunt prezentate în figura de mai jos.

![Conectare](./img/Sc-s2.png)

**Conectorul AC 230V** se conectează la alimentare (tabloul de distribuție). Este obligatorie utilizarea unui întreruptor automat de protecție la supracurent 1P-B6 și a unor limitatoare de supratensiune de tip T1 T2. O bună practică la conectarea mai multor dispozitive este gruparea controlerelor pe „faze” diferite (L1, L2, L3), pentru încărcarea uniformă a liniei de alimentare.  
**Conectorul FAN** trebuie conectat direct la ventilator; în cazul comandării mai multor ventilatoare, sarcina totală nu poate depăși 6A, iar fiecare ventilator trebuie protejat separat. PE și N nu trebuie preluate din alimentare (tabloul de distribuție), ci trebuie obligatoriu conectate la bornele controlerului.  
**Conectorul FUNCTION** este o ieșire cu releu izolată, curentul maxim al contactului fiind 6A (este necesar un întreruptor automat extern de protecție la supracurent 1P-B6 în cazul comandării directe a sarcinii),
putând fi utilizat pentru:  
- **Încălzire suplimentară** – contactul se închide când temperatura măsurată scade sub valoarea setată.  
- **Ventilația grupei 2 sau a sistemelor de pulverizare** – contactul se închide când temperatura măsurată este mai mare decât suma temperaturii setate și a benzii de ventilație.  contactul se închide când temperatura măsurată este mai mare decât suma temperaturii setate și a benzii de ventilație.  

Figura de mai jos prezintă modul de conectare a ventilatorului grupei 2 sau a aerotermei.  

![A doua grupă](./img/2grupa.png)

**Conectorul ALARM** reprezintă ieșirile izolate NC, C și NO, destinate conectării la centrala de alarmă. Alarma se activează în următoarele cazuri:  
- temperatura este prea scăzută sau prea ridicată,
- controlerul sau senzorul de temperatură s-a defectat,
- s-a întrerupt tensiunea de alimentare a controlerului;
- a apărut o funcționare necorespunzătoare a controlerului (de exemplu, supraîncălzirea controlerului)  

![Alarmă](./img/alarmsc-s.png)  

**Conectorul V1 0-10V** servește la conectarea modulelor de extindere a puterii sau a ventilatoarelor cu circuit integrat de reglare a turației. Tensiunea la această bornă este proporțională cu nivelul de ventilație.  
**Conectorul V2 0-10V** servește la conectarea actuatorului care deschide clapetele de admisie a aerului.  
**Conectorul SENSOR** se conectează la 1 senzor de temperatură TS3 sau TS5, polaritatea neavând importanță.  O bună practică este menținerea cablurilor de măsurare la distanță de cablurile de alimentare.  
**Conectorul RS-485** poate fi utilizat pentru realizarea sistemelor de ventilație și pentru comunicarea cu un computer PC.  

## Principiul de funcționare  

Sarcina principală a controlerului este menținerea temperaturii în adăpostul pentru animale la nivelul stabilit de crescător. Trebuie reținut că controlerul este doar un instrument care ajută la asigurarea condițiilor climatice optime în adăpostul pentru animale. Rolul principal în acest proces îi revine însă crescătorului, care trebuie să adapteze setările dispozitivului la condițiile climatice exterioare în schimbare și, mai ales, la cerințele animalelor din clădirea zootehnică, precum și să monitorizeze starea de funcționare a dispozitivului prin intermediul centralei de alarmă.  

### Prima punere în funcțiune a controlerului  

:::danger
La prima punere în funcțiune a controlerului, este obligatorie setarea benzii interzise de funcționare a motorului.
:::

Controlerul funcționează cu ventilatoare bazate pe un motor asincron monofazat, cu un consum total maxim de curent de 5A. După conectarea ventilatoarelor alese, utilizatorul trebuie să le adapteze pentru funcționarea cu controlerul. Cu alte cuvinte, este necesară setarea nivelului minim de funcționare (turației) al ventilatorului. Această funcție se numește **„Bandă interzisă”** și este setată de utilizator o singură dată din **„Setări avansate”**. Pentru efectuarea corectă a acestei operațiuni, se recomandă ajutorul unei a doua persoane, care să poată observa permanent comportamentul ventilatorului în timp ce cealaltă persoană setează valoarea **„Benzii interzise”**. Lipsa setării benzii interzise poate duce la funcționarea necorespunzătoare a dispozitivului. Valoarea **„Benzii interzise”** poate fi considerată corectă în momentul în care presiunea produsă de ventilator începe să ridice ușor clapetele coșului de ventilație. Operațiunea de setare a **„Benzii interzise”** trebuie repetată atunci când se schimbă ventilatorul conectat la controler.  

### Aerisire periodică  

Aerisirea este o funcție executată de controler, care se activează în momentul în care temperatura din încăpere scade sub temperatura setată. Această funcție asigură animalelor un aport ciclic de aer proaspăt. Aerisirea este definită de 3 parametri:
- **„Timp de funcționare”** - stabilește pentru câte secunde trebuie pornit ventilatorul,
- **„Timp de pauză”** - stabilește timpul de oprire a ventilatorului, în secunde,
- **„Nivel de aerisire”** - stabilește puterea ventilației în „Timpul de funcționare”.  

O setare exemplificativă **60s/120s** înseamnă că ventilatorul este pornit pentru 60s, cu o pauză între pornirile succesive de 120s. 

Toți parametrii menționați mai sus sunt setați de utilizator. La setarea parametrilor de aerisire trebuie respectate câteva reguli:
- aerisirea este activată exclusiv atunci când temperatura din adăpostul pentru porcine scade sub temperatura setată,
- funcția de bază a aerisirii este asigurarea unui aport ciclic de aer proaspăt pentru animale, nu menținerea temperaturii setate în încăpere,
- se recomandă aerisirea încăperilor pentru perioade scurte, dar frecvente,
- trebuie evitate perioadele lungi de aerisire, deoarece acestea pot duce la fluctuații prea mari ale temperaturii,
- parametrii setați trebuie obligatoriu adaptați la comportamentul animalelor și la condițiile existente atât în interiorul, cât și în exteriorul încăperii,
- funcția de aerisire poate fi dezactivată; în această situație, atât în modul procentual, cât și în modul temporizat, trebuie setate valori zero în câmpul corespunzător duratei de aerisire, de exemplu: 0/120s  

### Ventilație cu reglare continuă  

Controlerul reglează continuu ventilația de la „Turație minimă” până la **„Turație maximă”** în intervalul de la **„Temperatura setată”** până la suma **„Temperaturii setate”** și a **„Benzii de ventilație”**. Peste acest interval se activează grupa 2 de ventilație.  

![ventilație](./img/wentylacjia.png)  

Peste acest interval se activează grupa 2 de ventilație, În cazul în care temperatura din încăpere scade sub **„Temperatura setată”**, controlerul aerisește periodic încăperea, iar la o scădere suplimentară se activează încălzirea suplimentară. Totul depinde de setările introduse de utilizator. Programul controlerului prevede și funcționarea cu o centrală de alarmă, care poate fi activată atunci când temperatura din adăpostul pentru porcine se abate de la parametrii setați.  

## Programarea controlerului  

Controlerul dispune de un set de setări implicite, care sunt înscrise în memoria nevolatilă în două cazuri:  
1. Prima punere în funcțiune a dispozitivului,  
2. Eroare în memoria de date.  
În cazul lipsei sau întreruperii alimentării, controlerul nu pierde setările utilizatorului introduse și salvate anterior.  

### Utilizarea meniului  

Controlerul este echipat cu o serie de funcții care permit adaptarea acestuia la aplicația respectivă. Aceste funcții sunt grupate într-un meniu, accesibil prin apăsarea uneia dintre tastele **(„ Săgeată dreapta”, „Săgeată stânga”)**. Parametrii se modifică folosind tastele **„+” și „-”**, iar parametrul editat va fi salvat automat în memoria nevolatilă după trecerea a **30s** de la ultima apăsare a unui buton.  

### Funcțiile meniului de bază  

| MENIU                       | Descriere | 
|:---:                       |:---|
|Temperatură  <br />20,8°C W16% A  |**„Mod informativ”** - de funcționare normală. Pe afișaj sunt indicate temperatura actuală și, când ventilatorul este pornit, valoarea nivelului de ventilație. Semnificația simbolurilor suplimentare: A-indică alarma activată, D  - indică încălzirea activată, W - indică ventilația suplimentară| 
|Temp. setată  <br />20,0°C        |**„Temperatură setată”** – valoarea temperaturii care stabilește începutul procesului de ventilație cu reglare continuă.   | 
|Aerisire  <br />20s / 200s  |**„Aerisire”** – se setează două valori ale duratelor 1 „Timp de funcționare”, 2 „Timp de pauză” între activările ciclice succesive ale ventilației.| 
|Nivel aeris.  <br />20%        |**„Nivel de aerisire”** - nivelul de ventilație în timpul funcționării aerisirii   | 
|Alarmă minim  <br />12,0°C       |**„Alarmă minim”** - stabilește temperatura minimă absolută la care se activează alarma. 
|Alarmă maxim  <br />28,0°C       |**"Alarmă maxim"** - stabilește temperatura maximă absolută la care se activează alarma.  | 
|Încălzire suplimentară  <br />12,0°C         |În funcție de configurație, sunt realizate funcțiile: **„Încălzire suplimentară”** - contactul se închide dacă temperatura scade sub valoarea indicată. | 
|Ventilație treapta 2  <br />25,0  |**„Ventilație treapta 2”** - contactul se închide când temperatura măsurată depășește suma temperaturii setate și a benzii de ventilație. | 
|Bandă de ventilație  <br />5,0°C     |**„Bandă de ventilație”** - stabilește viteza de reacție a controlerului (modificarea nivelului de ventilație de la minim 1 până la maxim 1) la creșterea temperaturii. | 
|Turație minimă  <br />1%        |**„Turație minimă”** – este o stare în care dispozitivul rămâne pe o perioadă nedeterminată, furnizând la ieșire o tensiune cu valoarea setată. Servește la calibrarea dispozitivului cu motorul și mecanismul clapetelor.   | 
|Turație maximă  <br />100%      |**„Turație maximă”** – este o stare în care dispozitivul rămâne pe o perioadă nedeterminată, furnizând la ieșire o tensiune cu valoarea setată. Servește la limitarea puterii destinate ventilației| 

### Meniul avansat  

Meniul avansat este destinat în principal instalatorilor și permite adaptarea controlerului la instalație și la ventilator. Accesarea setărilor avansate se realizează prin apăsarea și menținerea apăsată a celor două taste de meniu timp de aproximativ 10s.  

| MENIU                                 | Descriere| 
|:---:                                 |:--- |
|Lipsă setări  <br />avansate   |Acest mesaj indică faptul că controlerul nu a fost calibrat cu ventilația și că funcționarea sa poate fi necorespunzătoare Este necesară accesarea meniului avansat și efectuarea setărilor „Benzii interzise”.|
|Setări <br />avansate         |Semnalizarea accesării setărilor avansate. | 
|Software Ver:  <br />1907       |Informații despre versiunea software-ului.| 
|Bandă interzisă  <br />1000 us       |Calibrarea turației minime a ventilatoarelor conectate direct la controler; acest parametru corespunde nivelului de ventilație „1%”|  
|Funcția contactelor  <br />Încălzire suplimentară     |Selectarea funcției contactelor:  <br />• Încălzire suplimentară (implicită)<br />• grupa 2 de ventilație | 
|Aerisire  <br />Temporizată         |Selectarea tipului de aerisire: <br />• Temporizată (implicită) <br />• Procentuală| 
|Interval V1  <br />de la 2,0 până la 10,0       |Reglarea intervalului de variație a tensiunii la ieșirea V1 0÷10V. Setările se referă la valorile minimă și maximă ale tensiunii. Reglarea se utilizează pentru adaptarea controlerului la modulul de extindere a puterii sau la convertizorul de frecvență.| 
|Inversare V1  <br />Nu                |Activarea determină inversarea caracteristicii ieșirii V1. Tensiunea va scădea odată cu creșterea nivelului de ventilație în intervalul definit de min.-max. Semnalul la ieșirea V1 va fi de tip 10-0V.| 
|Decuplare V1  <br />Nu                |Activarea determină furnizarea la ieșirea  V1 0-10V a nivelului 0V și nu a valorii minime setate, atunci când nivelul de ventilație este 0%.| 
|Interval V2  <br />de la 2,0 până la 10,0       |Reglarea intervalului de variație a tensiunii la ieșirea V2 0÷10V. Setările se referă la valorile minimă și maximă ale tensiunii. Reglarea se utilizează pentru calibrarea sistemului de clapete.|
|Inversare V2  <br />Nu      	       |Activarea determină inversarea caracteristicii ieșirii V2. Tensiunea va scădea odată cu creșterea nivelului de ventilație în intervalul definit de min.-max. Semnalul la ieșirea V2 va fi de tip 10-0V.|
|Calibrare temp  <br />21,0°C -> 22,0°C|Calibrarea senzorului de temperatură permite recalibrarea valorii citite.|
|Pornire lină  <br />50%      	           |Stabilirea nivelului de ventilație la fiecare pornire a ventilatorului; ventilatorul este accelerat până la valoarea indicată, după care trece la nivelul setat.| 
|Limbă  <br />Polonă    	           |Selectarea limbii meniului: polonă, engleză, germană, rusă|
|Ieșire                               |Ieșirea din meniul avansat cu ajutorul tastei „+”; modificările introduse vor fi salvate în memoria nevolatilă.|

### Mesaje de eroare și avertizare  

Mesajele de eroare au rolul de a informa utilizatorul despre neregulile din funcționarea controlerului. Mai jos sunt prezentate mesajele de eroare posibile.  

|EROARE                                    | DESCRIERE |
|:---:                                   |:--- |
|Alarmă  <br />de suprasarcină 	         |Alarmă de suprasarcină, activată la 75°C. Dispozitivul își suspendă funcționarea până la răcire.|
|SENZOR ÎN CIRCUIT DESCHIS!  <br />Verificați senzorul|Senzor în circuit deschis, semnalează defectarea senzorului sau a cablului de conectare.|
|SENZOR SCURTCIRCUITAT!  <br />Verificați senzorul  |Senzor scurtcircuitat, semnalează defectarea senzorului sau a cablului de conectare.|
|Întreruperea  <br />alimentării                  |Întreruperea alimentării, tensiune de alimentare prea scăzută, frecvență incorectă sau tensiune de alimentare puternic deformată.| 

## Observații și avertismente  

:::danger 
În timpul instalării dispozitivului, alimentarea cu energie electrică trebuie obligatoriu deconectată, deoarece tensiunea prezentă pe unele componente este periculoasă pentru viață și sănătate. Se recomandă încredințarea instalării unei persoane calificate.
:::

- Pentru a evita problemele de exploatare a dispozitivului, este necesară citirea instrucțiunilor înainte de instalare și utilizare.  
- Nu este permisă intervenția asupra construcției sau efectuarea reparațiilor pe cont propriu. Aceasta se referă în special la modificarea elementelor și componentelor.  
- Operațiunile de întreținere sau de service trebuie efectuate de personal autorizat (instalator sau service-ul producătorului). În clădirile zootehnice cu ventilație forțată este obligatoriu un sistem de alarmă. Producătorul dispozitivului nu răspunde pentru daunele cauzate de instalarea incorectă, programarea incorectă a funcțiilor, consecințele evenimentelor fortuite și factorii externi.  
- Controlerul de ventilație necesită setarea parametrilor în conformitate cu condițiile existente în adăpostul pentru animale. Aceste setări sunt individuale și depind de decizia crescătorului. Producătorul dispozitivului își rezervă dreptul de a modifica construcția dispozitivului și software-ul.  


:::caution
![text alternativ](./img/trash.svg) La încheierea utilizării produsului, acesta nu trebuie aruncat împreună cu deșeurile municipale nesortate, ci eliminat în conformitate cu reglementările în vigoare (directivele WEEE ale Uniunii Europene 2012/19/UE). <br />Produsul a fost realizat în conformitate cu cerințele RoHS (Directiva Uniunii Europene 2011/65/UE).
:::

<!-- \newpage -->
## Date tehnice ale controlerului  

|Parametru                        |	DESCRIERE      |
|:-----------                    |:---------- |
|Tensiune de alimentare|	230VAC 50Hz|
|Curentul maxim al ieșirii de reglare continuă FAN|	6A|
|Intervalul de reglare a tensiunii de ieșire|	70V ÷ (Uz-5)V|
|Curentul maxim al ieșirii (contactului) ALARM|	3A|
|Curentul maxim al ieșirii (contactului) FUNCTION|	3A|
|Intervalul temperaturii de funcționare|	-20 +40oC|
|Intervalul de măsurare a temperaturii|	0 +50°C|
|Rezoluția măsurării temperaturii|	0,1°C|
|Detectarea defectelor senzorului de temperatură|	DA|
|Numărul maxim de senzori analogici|	1|
|Precizia măsurării temperaturii – intrare analogică|	1°C|
|Dependența măsurării de rezistența cablurilor – intrare analogică|	15,8Ω/°C|
|Rezistență la supratensiuni (max E)|	210J|
|Protecție la suprasarcină|	75°C|
|Dimensiunile dispozitivului|	20x15x8 [cm]|
|Gradul de etanșeitate al carcasei|	IP56|
  


:::info
Controlerul SPEED CONTROL SERVOMOTOR include în set:
- 1 senzor de temperatură + accesorii,
- 4 dibluri de expansiune,
- 1 siguranță fuzibilă 10A.
:::

