---
sidebar_position: 2
title: Instrucciones SC-S
description: Controlador de clima para recintos ganaderos con una corriente de salida
  admisible de hasta 5A
keywords:
- eletor sc-s
- controlador de ventilación
- controlador de clima
- controlador de ventilación de nave porcina
- controlador de microclima
- controlador para naves porcinas
- ventilación de nave porcina
- controlador para recintos de recría
---


# Controlador SC-S

Controlador de clima con microprocesador perteneciente a la familia SPEED CONTROL. Controlador fiable, fácil de instalar y utilizar, con software en polaco, inglés, ruso y alemán. El programa del controlador permite ajustar de forma intuitiva los parámetros: temperaturas, renovación de aire, calefacción auxiliar, niveles mín./máx. de ventilación y alarmas.

**Parámetros y características:**  
- Ventilación del grupo I:
  - corriente máx. de la salida de regulación continua 6A,
  - protección térmica del sistema,
  - arranque suave de la ventilación,
  - calibración de la velocidad mínima
- Ventilación del grupo II, contacto aislado hasta 3A (1 como opción)
- Calefacción auxiliar, contacto aislado hasta 3A (1 como opción)
- Salidas de alarma NO y NC:
  - señalización de pérdida de alimentación,
  - señalización de superación del umbral de temperatura mín. o máx.
- 1 entrada analógica para la medición de temperatura
- 2 salidas 0-10V
- Potencia consumida por el sistema < 3W
- Carcasa hermética IP56
- Tensión de alimentación 230VAC 50Hz

## Instalación del controlador  
:::danger 
Durante la instalación del dispositivo es obligatorio desconectar la alimentación eléctrica, ya que la tensión presente en algunos componentes supone un peligro para la vida y la salud.  
Se recomienda encargar la instalación a una persona cualificada.
:::

### Elección del lugar de montaje  

El lugar de montaje debe elegirse de forma racional, teniendo en cuenta que el dispositivo sea fácilmente accesible para las personas autorizadas e inaccesible para los animales y los niños. También deben tenerse en cuenta las condiciones climáticas, es decir, el dispositivo debe funcionar en un intervalo de temperaturas de -10°C a 40°C, en un lugar no expuesto al sol. Debe haber una circulación libre de aire alrededor del dispositivo. El dispositivo incluye un sensor de temperatura. Deben respetarse varias reglas de montaje del sensor de temperatura:  
- el sensor no debe montarse en un lugar sin circulación de aire ni expuesto directamente al sol
- el sensor no debe montarse en una pared portante (exterior) del edificio,
- evitar la proximidad de dispositivos que emitan calor, como radiadores y lámparas,
- no debe colocarse el sensor directamente junto a puertas ni aberturas de ventilación,
- no debe colocarse el sensor en lugares accesibles para los animales,
- se recomienda tender el cable de conexión del sensor lejos de los cables de alimentación.

### Montaje  

El dispositivo puede funcionar en condiciones climáticas adversas. El controlador y el sensor de temperatura, correctamente montados, son resistentes a las condiciones ambientales.
Durante el montaje debe prestarse atención a los siguientes aspectos:  
- antes de atornillar, debe comprobarse la junta de la tapa,
- la tapa debe fijarse apretando todos los tornillos,
- los cables utilizados para conectar el controlador deben ser redondos,
- tras conectar el cable, deben apretarse los prensaestopas de forma que el cable quede sellado e inmovilizado; se recomienda utilizar silicona,
- las salidas no utilizadas (prensaestopas) deben obturarse,
- el controlador (la parte inferior de la carcasa) se fija a una pared plana con 4 tacos de expansión.

## Conexión eléctrica  

:::danger 
¡Antes de conectar el sistema, asegúrese de que la alimentación esté desconectada!
:::

Antes de proceder a la conexión del controlador, debe desatornillarse y retirarse la tapa. Introduzca los cables a través de los prensaestopas de goma y proceda a conectarlos. Los bornes del controlador se muestran en la siguiente figura.

![Conexión](./img/Sc-s2.png)

**El conector AC 230V** se conecta a la alimentación (cuadro de distribución). Es obligatorio utilizar un interruptor magnetotérmico 1P-B6 y dispositivos de protección contra sobretensiones de tipo T1 T2. Una buena práctica al conectar varios dispositivos es agrupar los controladores en distintas «fases» (L1, L2, L3), para distribuir uniformemente la carga de la línea de alimentación.  
**El conector FAN** debe conectarse directamente al ventilador; si se controlan varios ventiladores, la carga total no puede superar 6A y cada ventilador debe protegerse por separado. No deben tomarse PE y N de la alimentación (cuadro de distribución); es obligatorio conectarlos a los terminales del controlador.  
**El conector FUNCTION** es una salida de relé aislada; la corriente máxima del contacto es 6A (se requiere un interruptor magnetotérmico externo 1P-B6 en caso de control directo de la carga),
puede utilizarse como:  
- **Calefacción auxiliar** – el contacto se cierra cuando la temperatura medida desciende por debajo del valor ajustado.  
- **Ventilación del grupo 2 o de sistemas de aspersión** – el contacto se cierra cuando la temperatura medida es superior a la suma de la temperatura de consigna y la banda de ventilación.  el contacto se cierra cuando la temperatura medida es superior a la suma de la temperatura de consigna y la banda de ventilación.  

La siguiente figura muestra cómo conectar el ventilador del grupo 2 o el calefactor.  

![Segundo grupo](./img/2grupa.png)

**El conector ALARM** dispone de salidas aisladas NC, C y NO para la conexión a una central de alarma. La alarma se activa en los siguientes casos:  
- la temperatura es demasiado baja o demasiado alta,
- el controlador o el sensor de temperatura se ha averiado,
- se ha perdido la tensión de alimentación del controlador;
- se ha producido un funcionamiento incorrecto del controlador (p. ej., sobrecalentamiento del controlador)  

![Alarma](./img/alarmsc-s.png)  

**El conector V1 0-10V** sirve para conectar módulos de ampliación de potencia o ventiladores con un sistema integrado de regulación de velocidad. La tensión en este borne es proporcional al nivel de ventilación.  
**El conector V2 0-10V** sirve para conectar el actuador que abre las compuertas de entrada de aire.  
**El conector SENSOR** se conecta al sensor de temperatura 1 TS3 o TS5; la polaridad no importa.  Una buena práctica es mantener los cables de medición alejados de los cables de alimentación.  
**El conector RS-485** puede utilizarse para construir sistemas de ventilación y para la comunicación con un PC.  

## Principio de funcionamiento  

La función principal del controlador es mantener la temperatura del recinto de cría al nivel establecido por el ganadero. Debe recordarse que el controlador es únicamente una herramienta que ayuda a garantizar unas condiciones climáticas óptimas en el recinto de cría. No obstante, el papel principal en este proceso corresponde al ganadero, que debe adaptar los ajustes del dispositivo a las condiciones climáticas cambiantes del exterior y, sobre todo, a las necesidades de los animales alojados en el edificio ganadero, así como supervisar el estado de funcionamiento del dispositivo mediante la central de alarma.  

### Primera puesta en marcha del controlador  

:::danger
En la primera puesta en marcha del controlador es obligatorio ajustar la banda prohibida de funcionamiento del motor.
:::

El controlador funciona con ventiladores basados en un motor asíncrono monofásico con un consumo total máximo de corriente de 5A. Tras conectar los ventiladores seleccionados, el usuario debe adaptarlos para que funcionen con el controlador. En otras palabras, es necesario ajustar el nivel mínimo de funcionamiento (velocidad) del ventilador. Esta función se denomina **«Banda prohibida»** y el usuario la ajusta una sola vez desde los **«Ajustes avanzados»**. Para realizar correctamente esta operación, se recomienda contar con la ayuda de una segunda persona que pueda observar continuamente el comportamiento del ventilador mientras la otra ajusta el valor de la **«Banda prohibida»**. Si no se ajusta la banda prohibida, el dispositivo puede funcionar incorrectamente. El valor de la **«Banda prohibida»** puede considerarse correcto cuando la presión generada por el ventilador empieza a levantar ligeramente las compuertas de la chimenea de ventilación. El ajuste de la **«Banda prohibida»** debe repetirse cuando se cambie el ventilador conectado al controlador.  

### Renovación periódica de aire  

La renovación de aire es una función ejecutada por el controlador que se activa cuando la temperatura del recinto desciende por debajo de la temperatura de consigna. Esta función garantiza un suministro cíclico de aire fresco a los animales. La renovación de aire se define mediante 3 parámetros:
- **«Tiempo de funcionamiento»** - determina durante cuántos segundos debe activarse el ventilador,
- **«Tiempo de pausa»** - determina el tiempo en segundos durante el que el ventilador permanece detenido,
- **«Nivel de renovación de aire»** - determina la potencia de ventilación durante el «Tiempo de funcionamiento».  

El ajuste de ejemplo **60s/120s** significa que el ventilador se activa durante 60s con una pausa de 120s entre activaciones sucesivas. 

Todos los parámetros mencionados anteriormente son ajustados por el usuario. Deben tenerse en cuenta varias reglas al ajustar los parámetros de renovación de aire:
- la renovación de aire se activa única y exclusivamente cuando la temperatura de la nave porcina desciende por debajo de la temperatura de consigna,
- la función principal de la renovación de aire es garantizar un suministro cíclico de aire fresco a los animales, no mantener la temperatura de consigna en el recinto,
- se recomienda renovar el aire de los recintos durante períodos cortos, pero frecuentes,
- deben evitarse períodos largos de renovación de aire, ya que pueden provocar fluctuaciones excesivas de temperatura,
- es obligatorio adaptar los parámetros ajustados al comportamiento de los animales y a las condiciones existentes tanto en el interior como en el exterior del recinto,
- la función de renovación de aire puede desactivarse; en ese caso, tanto en el modo porcentual como en el temporizado, deben ajustarse valores cero en el campo correspondiente al tiempo de renovación de aire, p. ej.: 0/120s  

### Ventilación con regulación continua  

El controlador regula de forma continua la ventilación desde la «Velocidad mínima» hasta la **«Velocidad máxima»** en el intervalo comprendido entre la **«Temperatura de consigna»** y la suma de la **«Temperatura de consigna»** y la **«Banda de ventilación»**. Por encima de este intervalo se activa el grupo 2 de ventilación.  

![ventilación](./img/wentylacjia.png)  

Por encima de este intervalo se activa el grupo 2 de ventilación, Si la temperatura del recinto desciende por debajo de la **«Temperatura de consigna»**, el controlador renueva periódicamente el aire del recinto; si continúa descendiendo, se activa la calefacción auxiliar. Todo depende de los ajustes introducidos por el usuario. El programa del controlador también contempla el funcionamiento conjunto con una central de alarma, que puede activarse cuando la temperatura de la nave porcina se desvía de los parámetros establecidos.  

## Programación del controlador  

El controlador dispone de un conjunto de ajustes predeterminados que se escriben en la memoria no volátil en dos casos:  
1. Primera puesta en marcha del dispositivo,  
2. Error en la memoria de datos.  
En caso de ausencia o pérdida de alimentación, el controlador no pierde los ajustes del usuario introducidos y guardados previamente.  

### Uso del menú  

El controlador está equipado con una serie de funciones que permiten adaptarlo a una aplicación determinada. Estas funciones están agrupadas en un menú al que se accede pulsando una de las teclas **(« Flecha derecha», «Flecha izquierda»)**. Los parámetros se modifican mediante las teclas **«+» y «-»**; el parámetro editado se guardará automáticamente en la memoria no volátil una vez transcurridos **30s** desde la última pulsación de una tecla.  

### Funciones del menú básico  

| MENÚ                       | Descripción | 
|:---:                       |:---|
|Temperatura  <br />20,8°C W16% A  |**«Modo informativo»** - de funcionamiento normal. La pantalla muestra la temperatura actual y, cuando el ventilador está en funcionamiento, el valor del nivel de ventilación. Significado de los símbolos adicionales: A-indica alarma activada, D  - indica calefacción activada, W - indica ventilación adicional| 
|Temp. de consigna  <br />20,0°C        |**«Temperatura de consigna»** – valor de temperatura que determina el inicio del proceso de ventilación con regulación continua.   | 
|Renovación de aire  <br />20s / 200s  |**«Renovación de aire»** – se ajustan dos valores de tiempo 1 «Tiempo de funcionamiento», 2 «Tiempo de pausa» entre activaciones cíclicas sucesivas de la ventilación.| 
|Nivel de renov.  <br />20%        |**«Nivel de renovación de aire»** - nivel de ventilación durante el funcionamiento de la renovación de aire   | 
|Alarma mínima  <br />12,0°C       |**«Alarma mínima»** - determina la temperatura mínima absoluta a la que se activará la alarma. 
|Alarma máxima  <br />28,0°C       |**"Alarma máxima"** - determina la temperatura máxima absoluta a la que se activará la alarma.  | 
|Calefacción auxiliar  <br />12,0°C         |En función de la configuración, se ejecutan las funciones: **«Calefacción auxiliar»** - el contacto se cierra si la temperatura desciende por debajo del valor indicado. | 
|Ventilación de etapa 2  <br />25,0  |**«Ventilación de etapa 2»** - el contacto se cierra cuando la temperatura medida supera la suma de la temperatura de consigna y la banda de ventilación. | 
|Banda de ventilación  <br />5,0°C     |**«Banda de ventilación»** - determina la rapidez de respuesta del controlador (cambio del nivel de ventilación desde el mínimo 1 hasta el máximo 1) al aumento de temperatura. | 
|Velocidad mínima  <br />1%        |**«Velocidad mínima»** – es un estado en el que el dispositivo permanece durante un tiempo indefinido, suministrando a la salida una tensión del valor ajustado. Sirve para calibrar el dispositivo con el motor y el mecanismo de compuertas.   | 
|Velocidad máxima  <br />100%      |**«Velocidad máxima»** – es un estado en el que el dispositivo permanece durante un tiempo indefinido, suministrando a la salida una tensión del valor ajustado. Sirve para limitar la potencia destinada a la ventilación| 

### Menú avanzado  

El menú avanzado está destinado principalmente a los instaladores y permite adaptar el controlador a la instalación y al ventilador. Para acceder a los ajustes avanzados, mantenga pulsadas las dos teclas de menú durante aproximadamente 10s.  

| MENÚ                                 | Descripción| 
|:---:                                 |:--- |
|Sin ajustes  <br />avanzados   |Este mensaje indica que el controlador no se ha calibrado con la ventilación y que su funcionamiento puede ser incorrecto Es necesario acceder al menú avanzado y realizar los ajustes de la «Banda prohibida».|
|Ajustes <br />Avanzados         |Indicación de acceso a los ajustes avanzados. | 
|Software Ver:  <br />1907       |Información sobre la versión del software.| 
|Banda prohibida  <br />1000 us       |Calibración de la velocidad mínima de los ventiladores conectados directamente al controlador; este parámetro corresponde al nivel de ventilación «1%»|  
|Función de contactos  <br />Calefacción auxiliar     |Selección de la función de los contactos:  <br />• Calefacción auxiliar (predeterminada)<br />• Grupo 2 de ventilación | 
|Renovación de aire  <br />Temporizada         |Selección del tipo de renovación de aire: <br />• Temporizada (predeterminada) <br />• Porcentual| 
|Intervalo V1  <br />de 2,0 a 10,0       |Ajuste del intervalo de variación de tensión en la salida V1 0÷10V. Los ajustes corresponden a los valores mínimo y máximo de tensión. Este ajuste se utiliza para adaptar el controlador a la ampliación de potencia o al variador de frecuencia.| 
|Inversión V1  <br />No                |Su activación invierte la característica de la salida V1. La tensión disminuirá a medida que aumente el nivel de ventilación, dentro del intervalo definido por mín.-máx. La señal de la salida V1 será de tipo 10-0V.| 
|Corte V1  <br />No                |Su activación hace que se suministre a la salida  V1 0-10V el nivel 0V en lugar del valor mínimo ajustado, cuando el nivel de ventilación sea 0%.| 
|Intervalo V2  <br />de 2,0 a 10,0       |Ajuste del intervalo de variación de tensión en la salida V2 0÷10V. Los ajustes corresponden a los valores mínimo y máximo de tensión. Este ajuste se utiliza para calibrar el sistema de compuertas.|
|Inversión V2  <br />No      	       |Su activación invierte la característica de la salida V2. La tensión disminuirá a medida que aumente el nivel de ventilación, dentro del intervalo definido por mín.-máx. La señal de la salida V2 será de tipo 10-0V.|
|Calibración de temp.  <br />21,0°C -> 22,0°C|La calibración del sensor de temperatura permite modificar la escala del valor leído.|
|Arranque suave  <br />50%      	           |Determinación del nivel de ventilación en cada arranque del ventilador; el ventilador acelera hasta el valor indicado y después pasa al nivel de consigna.| 
|Idioma  <br />Polaco    	           |Selección del idioma del menú: polaco, inglés, alemán, ruso|
|Salir                               |Salida del menú avanzado mediante la tecla «+»; los cambios introducidos se guardarán en la memoria no volátil.|

### Mensajes de error y advertencia  

Los mensajes de error sirven para informar al usuario de anomalías en el funcionamiento del controlador. A continuación se indican los posibles mensajes de error.  

|ERROR                                    | DESCRIPCIÓN |
|:---:                                   |:--- |
|Alarma  <br />de sobrecarga 	         |Alarma de sobrecarga, activada a 75°C. El dispositivo suspende su funcionamiento hasta que se enfríe.|
|¡SENSOR EN CIRCUITO ABIERTO!  <br />Compruebe el sensor|Sensor en circuito abierto; indica una avería del sensor o del cable de conexión.|
|¡SENSOR EN CORTOCIRCUITO!  <br />Compruebe el sensor  |Sensor en cortocircuito; indica una avería del sensor o del cable de conexión.|
|Pérdida  <br />de alimentación                  |Pérdida de alimentación, tensión de alimentación demasiado baja, frecuencia incorrecta o tensión de alimentación muy distorsionada.| 

## Notas y advertencias  

:::danger 
Durante la instalación del dispositivo es obligatorio desconectar la alimentación eléctrica, ya que la tensión presente en algunos componentes supone un peligro para la vida y la salud. Se recomienda encargar la instalación a una persona cualificada.
:::

- Para evitar problemas durante el uso del dispositivo, es obligatorio leer las instrucciones antes de proceder a su instalación y utilización.  
- No se permite modificar la estructura ni efectuar reparaciones por cuenta propia. Esto se aplica, en particular, a la modificación de elementos y componentes.  
- Las tareas de mantenimiento o servicio deben ser realizadas por personal autorizado (instalador o servicio técnico del fabricante). En los edificios ganaderos con ventilación forzada es obligatorio disponer de un sistema de alarma. El fabricante del dispositivo no se responsabiliza de los daños causados por una instalación incorrecta, una programación incorrecta de las funciones, las consecuencias de sucesos fortuitos o factores externos.  
- El controlador de ventilación requiere que los parámetros se ajusten de acuerdo con las condiciones existentes en el recinto de cría. Estos ajustes son individuales y dependen de la decisión del ganadero. El fabricante del dispositivo se reserva el derecho a modificar la estructura del dispositivo y el software.  


:::caution
![texto alternativo](./img/trash.svg) Al finalizar la vida útil del producto, no debe desecharse junto con los residuos municipales sin clasificar, sino gestionarse conforme a la normativa vigente (directivas WEEE de la Unión Europea 2012/19/UE). <br />El producto se ha fabricado conforme a los requisitos RoHS (directiva de la Unión Europea 2011/65/UE).
:::

<!-- \newpage -->
## Datos técnicos del controlador  

|Parámetro                        |	DESCRIPCIÓN      |
|:-----------                    |:---------- |
|Tensión de alimentación|	230VAC 50Hz|
|Corriente máxima de la salida de regulación continua FAN|	6A|
|Intervalo de regulación de la tensión de salida|	70V ÷ (Uz-5)V|
|Corriente máxima de la salida (contacto) ALARM|	3A|
|Corriente máxima de la salida (contacto) FUNCTION|	3A|
|Intervalo de temperatura de funcionamiento|	-20 +40oC|
|Intervalo de medición de temperatura|	0 +50°C|
|Resolución de la medición de temperatura|	0,1°C|
|Detección de averías del sensor de temperatura|	SÍ|
|Número máximo de sensores analógicos|	1|
|Exactitud de la medición de temperatura – entrada analógica|	1°C|
|Dependencia de la medición respecto a la resistencia de los cables – entrada analógica|	15,8Ω/°C|
|Resistencia a sobretensiones (máx. E)|	210J|
|Protección contra sobrecarga|	75°C|
|Dimensiones del dispositivo|	20x15x8 [cm]|
|Grado de protección de la carcasa|	IP56|
  


:::info
El controlador SPEED CONTROL SERVOMOTOR incluye en el conjunto:
- 1 sensor de temperatura + accesorios,
- 4 tacos de expansión,
- 1 fusible 10A.
:::

