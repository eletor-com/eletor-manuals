---
sidebar_position: 4
title: Instrucțiuni IC-AC
description: Controler IC-AC pentru admisiile de aer din spațiile zootehnice, cu un
  curent de ieșire admisibil de până la 2A
keywords:
- eletor IC-AC
- controler pentru admisiile de aer
- controler climatic
- controler pentru ventilația adăposturilor de porcine
- controler de microclimat
- controler pentru adăposturi de porcine
- ventilația adăposturilor de porcine
- controler pentru spații de creștere a tineretului
---


# Controler IC-AC

  Controler pentru actuatoare și mecanisme de ridicare ale admisiilor de aer, bazate pe motoare AC cu rotație dreapta/stânga și potențiometru pentru citirea poziției curente. Controlerul îndeplinește funcția de convertor al semnalului 0-10V în nivelul de deschidere al admisiilor și permite, de asemenea, controlul manual.

## Parametri și caracteristici:  
- Moduri de funcționare:
  - MANUAL – control manual cu ajutorul butoanelor „+”, „-”;
  - AUTO – funcționare automată în intervalul calibrat, proporțională cu semnalul 0-10V;
  - DE URGENȚĂ – în cazul pierderii semnalului de comandă, admisiile de aer se deschid la nivelul setat în procente; 
- Ieșire de releu (dreapta/stânga) 2A;
- Semnal de comandă: 0-10V;
- Posibilitatea inversării semnalului de comandă;
- Măsurarea poziției cu ajutorul unui potențiometru 1-100kΩ;
- Histerezis și timp de mediere a citirilor programabile; 
- Carcasă etanșă IP56;
- Tensiune de alimentare 230VAC 50Hz;
- Meniu în limba: 
  - polonă
  - engleză
  - ucraineană
  - rusă

# Instalarea controlerului  
:::danger 
În timpul instalării dispozitivului, alimentarea cu energie electrică trebuie obligatoriu deconectată, deoarece tensiunea prezentă pe unele componente este periculoasă pentru viață și sănătate. Se recomandă încredințarea instalării unei persoane calificate.
:::

## Alegerea locului de montaj  

  Locul de montaj trebuie ales în mod rațional, ținând cont de accesul ușor la dispozitiv al persoanelor autorizate și de inaccesibilitatea acestuia pentru animale și copii. Trebuie luate în considerare și condițiile climatice, adică dispozitivul trebuie să funcționeze în intervalul de temperatură de la -10°C la 40 °C, într-un loc ferit de lumina directă a soarelui.

# Montaj

Dispozitivul poate funcționa în condiții climatice agresive. Dispozitivul montat corect este rezistent la acțiunea nocivă a mediului. 

  În timpul montajului trebuie acordată atenție următoarelor aspecte: 
- capacul trebuie strâns cu toate șuruburile,
- cablurile utilizate pentru conectarea dispozitivului trebuie să aibă secțiune transversală circulară,
- după conectarea cablului, presetupele trebuie strânse astfel încât cablul să fie etanșat și imobilizat; se recomandă utilizarea siliconului,
- trecerile neutilizate (presetupele) trebuie obturate,
- partea inferioară a carcasei se fixează pe un perete plan cu 4 dibluri de expansiune.


# Conectarea electrică  

:::danger 
Înainte de conectarea sistemului, asigurați-vă că alimentarea este oprită!
:::

  După deșurubarea dispozitivului, panoul frontal trebuie îndepărtat. În acest scop, scoateți cablul panglică din conectorul marcat P1. Introduceți cablurile prin presetupele de cauciuc și puteți începe conectarea acestora. Conectarea trebuie efectuată conform descrierii. Bornele controlerului sunt prezentate în figura de mai jos.

![Conectare](./img/ic-acpołącz.png)

## Alimentarea 230V AC de la tabloul de distribuție se conectează la bornele:  
 - **Conector L** bornă de fază. Este obligatorie utilizarea unui întreruptor automat de protecție la supracurent (de tip „S” B3) și a descărcătoarelor de supratensiune.  
 - **Conector N** bornă de neutru.  
 - **Conector PE** bornă de protecție.

## Ieșire către actuator: 
 - **Conector L** se conectează printr-un conductor la conectorul C, pentru a aplica tensiune releelor.  
 - **Conector N** bornă de neutru a actuatorului.  
 - **Conector PE** bornă de protecție a actuatorului – carcasă.  
 - **Conector NO** bornă a actuatorului pentru sensul de deschidere a admisiilor de aer.  
 - **Conector NC** bornă a actuatorului pentru sensul de închidere a admisiilor de aer.
 - **Conectorul potențiometrului** – trebuie conectat conform marcajelor din schema actuatorului. Polaritatea alimentării potențiometrului trebuie aleasă astfel încât unitățile de poziție să crească la deschiderea admisiilor de aer și să scadă la închiderea acestora. În caz contrar, trebuie inversate conductoarele de alimentare ale potențiometrului.  
 - **Conector In** – trebuie conectat la controler pentru a furniza semnalul de comandă către sistemele mecanismelor de ridicare.  


# Principiul de funcționare  

  În modul automat, controlerul convertește semnalul de comandă din intervalul 0-10V în poziția corespunzătoare  a actuatorului admisiilor de aer. Este necesară calibrarea actuatorului în pozițiile de deschidere maximă și de închidere a admisiilor de aer. În cursul calibrării, trebuie acordată atenție menținerii permanente sub tensiune a cablurilor  care duc la admisiile de aer. În timpul calibrării, butonul „+” trebuie să deschidă admisiile, iar butonul „-” trebuie să închidă admisiile de aer. În caz contrar, trebuie inversate conductoarele de la bornele NO și NC.
  Pozițiile citite de la potențiometru, pentru deschidere și închidere, trebuie să difere cu mai mult de 100 unități. Unitățile de poziție citite de la potențiometru trebuie să crească la deschiderea admisiilor și să scadă la închidere. În caz contrar, trebuie inversate conductoarele de alimentare ale potențiometrului.
  După calibrarea corectă, controlerul este pregătit pentru funcționarea automată și va controla poziția actuatorului. Aplicarea unui semnal de comandă la un nivel mai mic de 1,5V determină aducerea admisiilor de aer în poziția de urgență. 

## Utilizare 

  Controlerul admisiilor de aer poate funcționa în unul dintre cele două moduri: manual sau automat. Modul de funcționare selectat este memorat și nu este afectat de întreruperea alimentării – după pornirea alimentării, controlerul va reveni la modul în care a funcționat ultima dată. Modul de funcționare selectat în prezent este indicat pe afișaj:  
   - **MANUAL** - menținerea apăsată a butonului "+" sau "-" activează modul manual. În acest mod, admisiile de aer sunt controlate manual cu butoanele: „+” - deschidere, „-” - închidere.           
   - **AUTO**   - menținerea apăsată a butonului "Esc" activează modul automat. În acest mod, admisiile funcționează automat, fiind controlate de semnalul 0-10V de la conectorul In.

## Funcțiile meniului de bază  

| MENIU                       | Descriere | 
|:---:                       |:---|
|MANUAL  STOP    POT 539  |  **„Mod informativ”** – pentru funcționarea manuală. Informații afișate:  - **STOP** – actuator imobilizat;  - **OPEN** – deschiderea admisiilor de aer după apăsarea butonului „+”;  - **CLOSE** – închiderea admisiilor după apăsarea butonului „-”;  - **POT 539** – parametrul poziției curente a actuatorului, determinat de potențiometru.  •Trecerea la modul de funcționare automată prin menținerea apăsată a tastei „Esc”| 
|AUTO  20 % = In 3,70 POT 511       |  **„Mod informativ”**  pentru funcționarea automată. Informații afișate:    **20 %**  Valoarea poziției de deschidere setate a admisiilor de aer    **"="**   admisiile de aer în poziția stabilită    **"–"**    închiderea admisiilor până la poziția specificată    **"+"**    deschiderea admisiilor până la poziția specificată    **In 3,70**  măsurarea tensiunii de comandă la bornele In     **POT 511**  parametrul poziției curente a actuatorului, determinat de potențiometru.  Trecerea la modul de funcționare manuală prin menținerea apăsată a tastei „+” sau „-” | 
|Clapete urgență 30 %  |**„Clapete urgență”** – setarea valorii de deschidere de urgență a clapetelor (admisiilor de aer) în cazul pierderii semnalului de comandă. Admisiile de aer se vor deschide la nivelul setat în cazul unei defecțiuni a controlerului sau a cablului de semnal.| 
|Calibrare Desch 671 -> 311        |**„Calibrarea deschiderii”** – calibrarea deschiderii admisiilor de aer se efectuează prin setarea deschiderii maxime (poziției extreme) a admisiilor cu ajutorul butoanelor „+” și „-”. Prima valoare afișată reprezintă ultima setare salvată, iar a doua valoare reprezintă poziția curentă a actuatorului. Tasta „Ok” salvează în memorie setările introduse, iar „Esc” părăsește modul de calibrare fără salvare.   | 
|Calibrare Înch 281 -> 311      |**„Calibrarea închiderii”** – calibrarea închiderii admisiilor de aer se efectuează prin setarea poziției minime a admisiilor cu ajutorul butoanelor „+” și „-”. Prima valoare afișată reprezintă ultima setare salvată, iar a doua valoare reprezintă poziția curentă a actuatorului. Tasta „Ok” salvează în memorie setările introduse, iar „Esc” părăsește modul de calibrare fără salvare.|  
|Timp de mediere 5 s       |**„Timp de mediere”** – timpul de mediere a semnalului de comandă de la conectorul In, asigură protecție împotriva oscilațiilor la intrarea de comandă.  | 
|Inversare   Nu |**„Inversare”** – activarea acestei funcții adaptează controlerul la semnalul de comandă 10-0V  | 
|Limbă   Polonă |**„Limbă”** – selectarea limbii meniului  | 
|Histerezis Pot  5   | **„Histerezisul potențiometrului”** – o modificare a parametrului poziției actuatorului mai mică decât valoarea setată nu este luată în considerare la poziționare. Parametrul are rolul de a elimina mișcările foarte mici ale actuatorului și perturbațiile provenite de la potențiometru. | 
 

# Observații și avertismente  

:::danger 
În timpul instalării dispozitivului, alimentarea cu energie electrică trebuie obligatoriu deconectată, deoarece tensiunea prezentă pe unele componente este periculoasă pentru viață și sănătate. Se recomandă încredințarea instalării unei persoane calificate.
:::

- Pentru a evita problemele de exploatare a dispozitivului, este obligatorie citirea instrucțiunilor înainte de instalare și utilizare. Nu este permisă intervenția asupra construcției sau efectuarea reparațiilor pe cont propriu. Aceasta se referă în special la modificarea elementelor și componentelor.
- Operațiunile de întreținere sau service trebuie efectuate de personal autorizat (instalator sau serviciul de asistență al firmei). În clădirile zootehnice cu ventilație forțată este obligatoriu un sistem de alarmă. 
- Producătorul dispozitivului nu răspunde pentru daunele cauzate de instalarea incorectă, programarea incorectă a funcțiilor, consecințele evenimentelor fortuite și factorii externi.
- Dispozitivul necesită setarea parametrilor în conformitate cu condițiile existente în spațiul de creștere a animalelor. Aceste setări sunt individuale și depind de decizia crescătorului. Producătorul dispozitivului își rezervă dreptul de a modifica construcția dispozitivului și software-ul.  


:::caution
![text alternativ](./img/trash.svg) La încheierea utilizării produsului, acesta nu trebuie aruncat împreună cu deșeurile municipale nesortate, ci eliminat în conformitate cu reglementările în vigoare (directivele WEEE ale Uniunii Europene 2012/19/UE).  Produsul a fost fabricat în conformitate cu cerințele RoHS (Directiva Uniunii Europene 2011/65/UE).
:::

<!-- \newpage -->
# Date tehnice ale controlerului  

|Parametru                        |	DESCRIERE      |
|:-----------                    |:---------- |
|Tensiune alternativă de alimentare|	230VAC 50Hz|
|Curent maxim de ieșire|	2A|
|Filtru antiparazit la ieșire|	RC|
|Impedanță de intrare|	100kΩ|
|Protecție la supratensiune a intrărilor și ieșirilor|	DA|
|Alimentarea potențiometrului|	10VDC|
|Curent maxim al ieșirilor potențiometrului|	30mA|
|Interval de temperatură de funcționare|	-10 +40oC|
|Dimensiunile dispozitivului|	20x15x8 cm |
|Grad de protecție al carcasei|	IP65|

:::info
Controlerul IC-AC include în set:
- 4 dibluri de expansiune,
- 2 presetupă PG11,
- 2 presetupă PG9.
:::

