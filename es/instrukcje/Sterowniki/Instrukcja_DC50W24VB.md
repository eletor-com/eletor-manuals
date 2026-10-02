---
sidebar_position: 4
title: Manual de la fuente de alimentación DC50W24VB
description: Fuente de alimentación DC50W24VB  de emergencia para el sistema de entradas
  de aire.
keywords:
- eletor IC-AC
- controlador de entradas de aire
- controlador climático
- controlador de ventilación de porquerizas
- controlador de microclima
- controlador para porquerizas
- ventilación de porquerizas
- controlador para instalaciones de recría
---


# Fuente de alimentación DC50W24VB

Fuente de alimentación de emergencia con función de apertura automática y manual de las entradas y salidas de aire. Se utiliza para garantizar la seguridad de los animales de cría en caso de corte del suministro eléctrico o avería del controlador. Tras detectar una anomalía, el dispositivo activará una alarma y abrirá los elevadores hasta el nivel establecido.

## Parámetros y características: 
-  Selector del modo de funcionamiento: 
    - MANUAL
    - AUTO.
-  Mando giratorio del grado de apertura de las entradas de aire.
-  Estándares compatibles:
    - 0-10, 2-10, 10-0, 10-2.
-  Posibilidad de inversión de la señal de control.
-  Salidas de alarma NO y NC.
-  Indicación de pérdida de alimentación.
-  Supervisión de la tensión de control 2-10V.
-  Supervisión de cortocircuitos en las salidas 24VDC.
-  Supervisión de cortocircuitos en las salidas 0-10V.
-  2 entrada 0-10V.
-  2 salidas 0-10V.
-  Protecciones electrónicas de las entradas, salidas y línea 24V.
-  Banco de baterías 24V 4.0 Ah.
-  Carcasa hermética IP65.
-  Tensión de alimentación 85~264VAC 47~63Hz.

# Instalación del controlador  
:::danger 
Durante la instalación del dispositivo, es obligatorio desconectar el suministro eléctrico, ya que la tensión presente en algunos componentes supone un peligro para la vida y la salud. Se recomienda encargar la instalación a una persona cualificada.
:::

## Elección del lugar de montaje  

El lugar de montaje debe elegirse de forma razonada, teniendo en cuenta que el dispositivo debe ser fácilmente accesible para las personas autorizadas e inaccesible para los animales y los niños. También deben tenerse en cuenta las condiciones climáticas, es decir, el dispositivo debe funcionar en un intervalo de temperaturas de -10°C a 40 °C, en un lugar sin exposición directa al sol. Debe haber una circulación libre de aire alrededor del dispositivo.

# Montaje  

El dispositivo puede funcionar en condiciones climáticas agresivas. Si se monta correctamente, el dispositivo es resistente a los efectos perjudiciales del entorno.

### Durante el montaje debe prestarse atención a los siguientes aspectos: 
 - la tapa debe fijarse apretando todos los tornillos,
 - los cables utilizados para conectar el dispositivo deben tener una sección transversal circular,
 - tras conectar el cable, deben apretarse los prensaestopas para que el cable quede sellado e inmovilizado; se recomienda utilizar silicona,
 - las salidas de cables (prensaestopas) no utilizadas deben obturarse,
 - la parte inferior de la carcasa se fija a una pared plana con 4 tacos de expansión.


# Conexión eléctrica  

:::danger 
¡Antes de conectar el sistema, asegúrese de que la alimentación esté desconectada!
:::

Tras desatornillar el dispositivo, debe retirarse el panel frontal. Para ello, se extrae el cable plano del conector identificado como P1. Se introducen los cables a través de los prensaestopas de goma y se puede proceder a conectarlos. La conexión debe realizarse de acuerdo con la descripción.

![Conexión](./img/DC50W24VB.png)

**Alimentación 230V AC:** se conecta a la alimentación (cuadro de distribución). Es obligatorio utilizar un interruptor automático de sobreintensidad (tipo «S» B6) y limitadores de sobretensión de clase «C». El dispositivo puede alimentarse en un amplio intervalo de tensiones, de 85V a 264V, y de frecuencias, de 47 a 63Hz, sin que ello afecte a su funcionamiento.  

**Conector In1 e In2** debe conectarse al controlador para proporcionar la señal de control a los sistemas de elevadores. El dispositivo puede funcionar con dos controladores o con uno solo con secciones separadas de entradas y salidas de aire (los bornes I1 y I2 deben puentearse).  

**Conector ALARM** se conecta a la central de alarmas, según el sistema: contacto cerrado (NO y C), contacto abierto (NC y C). La alarma se activa en los siguientes casos:  •se ha perdido la tensión de alimentación del dispositivo,  •se ha perdido la señal de control 2-10V en al menos una de las entradas,  •se ha producido un cortocircuito de la señal de salida o su valor difiere del medido,  •se ha producido un cortocircuito en la barra +24V que alimenta los elevadores.  

**Conector Ouput 1 y Ouput 2** se conectan al actuador (elevador) de la forma requerida por el dispositivo utilizado; la descripción de la conexión debe figurar en el manual del actuador (elevador) correspondiente.  

**Selector del modo de funcionamiento S1** debe seleccionarse el modo de funcionamiento adecuado en función del actuador (elevador) utilizado. Por defecto, los interruptores 1,2,3,4,5,6 están en la posición off: funcionamiento 2-10V.
 
| Canal 1 | Canal 2| Función |
|------|------|----------|
| 1 – off | 4 – off | Modo de funcionamiento en el intervalo de señales 2-10V; una tensión de control inferior a 1,5V genera una alarma.   |
| 1 – on| 4 – on  | Modo de funcionamiento en el intervalo de señales 0-10V; sin reacción de alarma ante una señal inferior a 1,5V.   |
| 2 – off | 5 – off  | Modo de funcionamiento proporcional, señales de salida en el intervalo 0-10V o 2-10V.  |
| 2 – on | 5 – on  | Modo de funcionamiento invertido, señales de salida en el intervalo 10-0V o 10-2V.   |
| 3 – off | 6 – off  | Inversión de entrada desactivada.  |
| 3 – on | 6 – on   | Inversión de entrada activada.   |

# Principio de funcionamiento  

La fuente de alimentación de emergencia, en el modo de funcionamiento normal, alimenta los actuadores (elevadores) 24V y carga o mantiene cargadas las baterías, que suministrarán alimentación en caso de corte del suministro eléctrico.  El selector AUTO/MANUAL determina el modo de funcionamiento del dispositivo.  

**Modo MANUAL** permite controlar directamente los actuadores (elevadores) mediante el mando giratorio del panel del dispositivo.  

**Modo AUTO** – modo de funcionamiento principal; transmite la señal de control de la entrada a la salida, realizando el procesamiento correspondiente según los ajustes del interruptor «S1», y supervisa el nivel de la señal de entrada.  Si se detecta una anomalía en una entrada determinada, el dispositivo suministrará en su salida la señal del mando giratorio del panel frontal.  El relé de alarma se activará en los siguientes casos:  •señal de entrada demasiado baja (Uin < 1,5V) – interruptor «S1» 1-off, 4-off,  •cortocircuito de la señal de salida a masa o a 24V,  •ausencia de tensión de alimentación,  •cortocircuito de la tensión 24V.

## Uso 

El usuario selecciona el modo MANUAL mediante el selector y, mediante el mando giratorio, el grado de apertura de las entradas de aire adecuado a las necesidades: los actuadores funcionan de acuerdo con la posición del mando giratorio. Una vez finalizado el ajuste de las entradas de aire, se selecciona el modo AUTO mediante el selector y se deja el dispositivo en funcionamiento: las entradas de aire se situarán en el nivel requerido por el controlador de ventilación. En una situación de emergencia, las entradas de aire se situarán de acuerdo con la posición del mando giratorio.  

## Panel frontal 

| MENÚ                       | Descripción | 
|:---:                       |:---|
|![Conexión](./img/paneldcw50.png) |**Indicador luminoso POWER** – indica la presencia de alimentación y la carga de las baterías.  1.**Indicador luminoso CHECK** – permanece encendido en modo automático cuando se transmite a la salida la señal del controlador; parpadea cuando se suministra a la salida la señal del mando giratorio.  2.**OUT 1** – informa de anomalías en el canal 1.  3.**OUT 2** – informa de anomalías en el canal 2.  4.**AUTO** – modo de funcionamiento automático.  5.**MANUAL** – modo de funcionamiento manual.  6.**Mando giratorio 0%-100%** - selección del grado de apertura de las entradas de aire.| 

# Mensajes de error y advertencia

Los mensajes de error sirven para informar al usuario de anomalías en el funcionamiento del dispositivo. A continuación se indican los posibles mensajes de error:
 -  Indicador luminoso POWER – no se enciende en verde – ausencia de alimentación de red.
 -  Indicador luminoso CHECK – parpadea en amarillo – se ha suministrado a las salidas la señal del potenciómetro.
 -  Indicador luminoso OUT 1 – se enciende en rojo - detección de una anomalía (ausencia de señal de control, cortocircuito en la salida o cortocircuito en la barra 24VDC) en el primer canal.
 -  Indicador luminoso OUT 2 – se enciende en rojo - detección de una anomalía (ausencia de señal de control, cortocircuito en la salida o cortocircuito en la barra 24VDC) en el segundo canal.

# Observaciones y advertencias  

:::danger 
Durante la instalación del dispositivo, es obligatorio desconectar el suministro eléctrico, ya que la tensión presente en algunos componentes supone un peligro para la vida y la salud. Se recomienda encargar la instalación a una persona cualificada.
:::

 - Para evitar problemas durante el funcionamiento del dispositivo, es obligatorio leer el manual antes de proceder a su instalación y uso. No se permite modificar la construcción ni realizar reparaciones por cuenta propia. Esto se aplica especialmente a las modificaciones de elementos y componentes.
 - Las operaciones de mantenimiento o servicio deben ser realizadas por personal autorizado (instalador o servicio técnico de la empresa). En los edificios ganaderos con ventilación forzada es obligatorio disponer de un sistema de alarma. 
 - El fabricante del dispositivo no se responsabiliza de los daños causados por una instalación incorrecta, una programación incorrecta de las funciones, las consecuencias de sucesos fortuitos o factores externos. El dispositivo requiere ajustar los parámetros de acuerdo con las condiciones existentes en el recinto de cría.Estos ajustes son individuales y dependen de la decisión del ganadero. 
 - El fabricante del dispositivo se reserva el derecho a modificar la construcción del dispositivo y el software.
El dispositivo incluye un banco de baterías; no debe permitirse su descarga excesiva, ya que podría dañar el banco de baterías. 
Un cortocircuito entre los polos de la batería puede provocar un incendio.  


:::caution
![texto alternativo](./img/trash.svg) Al finalizar la vida útil del producto, no debe desecharse junto con los residuos municipales sin clasificar, sino gestionarse de acuerdo con la normativa vigente (directivas WEEE de la Unión Europea 2012/19/UE).  El producto se ha fabricado de acuerdo con los requisitos RoHS (directiva de la Unión Europea 2011/65/UE).
:::

<!-- \newpage -->
# Datos técnicos del controlador  

|Parámetro                        |	DESCRIPCIÓN      |
|:-----------                    |:---------- |
|Tensión de alimentación alterna|	85~264VAC 47~63Hz|
|Tensión de alimentación continua|	120~370VDC|
|Tensión de salida|	27,6VDC|
|Corriente máxima de salida|	1,8A|
|Rendimiento|	85%|
|Corriente máxima de las salidas de control 0-10V|	30mA|
|Corriente máxima de la salida (contacto) ALARM|	3A|
|Protección contra sobretensiones de las entradas y salidas|	SÍ|
|Protección contra cortocircuitos|	Automática |
|Banco de baterías|	4Ah 24V|
|Intervalo de temperatura de funcionamiento|	-10 +40oC|
|Dimensiones del dispositivo|	20x15x8 cm|
|Grado de estanqueidad de la carcasa|	IP65|

:::info
El controlador IC-AC incluye en el conjunto:
 - tacos de expansión - 	4 uds., 
 - baterías 12V 4Ah - 	2 uds., 
 - prensaestopas PG13,5 -	1 uds.,
 - prensaestopas PG11 -	3 uds., 
 - prensaestopas PG9 -	3 uds.
:::

