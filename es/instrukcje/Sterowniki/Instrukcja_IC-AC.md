---
sidebar_position: 4
title: Manual IC-AC
description: Controlador IC-AC de entradas de aire para recintos ganaderos con una
  corriente de salida admisible de hasta 2A
keywords:
- eletor IC-AC
- controlador de entradas de aire
- controlador climático
- controlador de ventilación de naves porcinas
- controlador de microclima
- controlador para naves porcinas
- ventilación de naves porcinas
- controlador para instalaciones de recría
---


# Controlador IC-AC

  Controlador de actuadores y mecanismos de elevación de entradas de aire basados en motores de CA con giro a derecha/izquierda y potenciómetro para la lectura de la posición actual. El controlador convierte la señal 0-10V en el grado de apertura de las entradas de aire y, además, permite el control manual.

## Parámetros y características:  
- Modos de funcionamiento:
  - MANUAL – control manual mediante los botones «+», «-»;
  - AUTO – funcionamiento automático dentro del rango calibrado, proporcional a la señal 0-10V;
  - EMERGENCIA – en caso de pérdida de la señal de control, las entradas de aire se abren hasta el nivel establecido en porcentaje; 
- Salida de relé (derecha/izquierda) 2A;
- Señal de control: 0-10V;
- Posibilidad de inversión de la señal de control;
- Medición de la posición mediante un potenciómetro 1-100kΩ;
- Histéresis y tiempo de promediado de las lecturas programables; 
- Carcasa hermética IP56;
- Tensión de alimentación 230VAC 50Hz;
- Idiomas del menú: 
  - polaco
  - inglés
  - ucraniano
  - ruso

# Instalación del controlador  
:::danger 
Durante la instalación del dispositivo es imprescindible desconectar la alimentación eléctrica, ya que la tensión presente en algunos componentes supone un peligro para la vida y la salud. Se recomienda encargar la instalación a una persona cualificada.
:::

## Elección del lugar de montaje  

  El lugar de montaje debe elegirse de forma razonada, teniendo en cuenta la facilidad de acceso al dispositivo para las personas autorizadas y evitando el acceso de animales y niños. También deben tenerse en cuenta las condiciones climáticas, es decir, el dispositivo debe funcionar en un rango de temperaturas de -10°C a 40 °C, en un lugar no expuesto al sol.

# Montaje

El dispositivo puede funcionar en condiciones climáticas agresivas. Si está correctamente montado, el dispositivo es resistente a los efectos nocivos del entorno. 

  Durante el montaje deben tenerse en cuenta los siguientes aspectos: 
- la tapa debe fijarse apretando todos los tornillos,
- los cables utilizados para conectar el dispositivo deben tener una sección transversal circular,
- después de conectar el cable, deben apretarse los prensaestopas de modo que el cable quede sellado e inmovilizado; se recomienda utilizar silicona,
- las salidas no utilizadas (prensaestopas) deben obturarse,
- la parte inferior de la carcasa se fija a una pared plana con 4 tacos de expansión.


# Conexión eléctrica  

:::danger 
¡Antes de conectar el sistema, asegúrese de que la alimentación esté desconectada!
:::

  Después de desatornillar el dispositivo, debe retirarse el panel frontal. Para ello, extraiga el cable plano del conector identificado como P1. Introduzca los cables a través de los prensaestopas de goma y proceda a conectarlos. La conexión debe realizarse conforme a la descripción. Los bornes del controlador se muestran en la siguiente figura.

![Conexión](./img/ic-acpołącz.png)

## La alimentación de 230V CA procedente del cuadro de distribución se conecta a los bornes:  
 - **Conector L** borne de fase. Es obligatorio utilizar un interruptor automático de protección contra sobreintensidades (tipo «S» B3) y limitadores de sobretensión.  
 - **Conector N** borne de neutro.  
 - **Conector PE** borne de protección.

## Salida al actuador: 
 - **Conector L** se conecta mediante un cable al conector C para suministrar tensión a los relés.  
 - **Conector N** borne de neutro del actuador.  
 - **Conector PE** borne de protección del actuador – carcasa.  
 - **Conector NO** borne del actuador en el sentido de apertura de las entradas de aire.  
 - **Conector NC** borne del actuador en el sentido de cierre de las entradas de aire.
 - **Conector del potenciómetro** – debe conectarse conforme a las indicaciones del esquema del actuador. La polaridad de la alimentación del potenciómetro debe seleccionarse de modo que las unidades de posición aumenten al abrirse las entradas de aire y disminuyan al cerrarse. Si ocurre lo contrario, deben intercambiarse los cables de alimentación del potenciómetro.  
 - **Conector In** – debe conectarse al controlador para suministrar la señal de control a los sistemas de elevación.  


# Principio de funcionamiento  

  En modo automático, el controlador convierte la señal de control del rango 0-10V en la posición correspondiente del actuador de las entradas de aire. Es necesario calibrar el actuador en las posiciones de apertura máxima y cierre de las entradas de aire. Durante la calibración, debe prestarse atención a que los cables  que van a las entradas de aire permanezcan constantemente tensados. Durante la calibración, el botón «+» debe abrir las entradas y el botón «-» debe cerrar las entradas de aire. Si ocurre lo contrario, deben intercambiarse los cables de los bornes NO y NC.
  Las posiciones leídas del potenciómetro para la apertura y el cierre deben diferir en más de 100 unidades. Las unidades de posición leídas del potenciómetro deben aumentar al abrirse las entradas y disminuir al cerrarse. Si ocurre lo contrario, deben intercambiarse los cables de alimentación del potenciómetro.
  Tras una calibración correcta, el controlador está listo para el funcionamiento automático y controlará la posición del actuador. Si se aplica una señal de control de nivel inferior a 1,5V, las entradas de aire se sitúan en la posición de emergencia. 

## Uso 

  El controlador de entradas de aire puede funcionar en uno de dos modos: manual o automático. El modo de funcionamiento seleccionado se guarda y no se ve afectado por una interrupción de la alimentación: al restablecerse la alimentación, el controlador vuelve al modo en el que funcionó por última vez. El modo de funcionamiento seleccionado actualmente se indica en la pantalla:  
   - **MANUAL** - mantener pulsado "+" o "-" durante un tiempo prolongado activa el modo manual. En este modo, las entradas de aire se controlan manualmente con los botones: «+» - apertura, «-» - cierre.           
   - **AUTO**   - mantener pulsado "Esc" durante un tiempo prolongado activa el modo automático. En este modo, las entradas funcionan automáticamente, controladas por la señal 0-10V del conector In.

## Funciones del menú básico  

| MENÚ                       | Descripción | 
|:---:                       |:---|
|MANUAL  STOP    POT 539  |  **«Modo informativo»** – del funcionamiento manual. Información mostrada:  - **STOP** – actuador detenido;  - **OPEN** – apertura de las entradas de aire al pulsar el botón «+»;  - **CLOSE** – cierre de las entradas al pulsar el botón «-»;  - **POT 539** – parámetro de la posición actual del actuador determinado por el potenciómetro.  •Cambio al modo de funcionamiento automático al mantener pulsada la tecla «Esc»| 
|AUTO  20 % = In 3,70 POT 511       |  **«Modo informativo»**  del funcionamiento automático. Información mostrada:    **20 %**  Valor de consigna de la posición de apertura de las entradas de aire    **"="**   entradas de aire en la posición establecida    **"–"**    cierre de las entradas hasta la posición especificada    **"+"**    apertura de las entradas hasta la posición especificada    **In 3,70**  medición de la tensión de control en los bornes In     **POT 511**  parámetro de la posición actual del actuador determinado por el potenciómetro.  Cambio al modo de funcionamiento manual al mantener pulsada la tecla «+» o «-» | 
|Compuertas en emergencia 30 %  |**«Compuertas en emergencia»** – ajuste del valor de apertura de emergencia de las compuertas (entradas de aire) en caso de pérdida de la señal de control. Las entradas de aire se abrirán hasta el nivel establecido en caso de fallo del controlador o del cable de señal.| 
|Calibración Apert 671 -> 311        |**«Calibración de apertura»** – la calibración de la apertura de las entradas de aire se realiza ajustando la apertura máxima (posición extrema) de las entradas mediante los botones «+» y «-». El primer valor mostrado representa el último ajuste guardado y el segundo valor, la posición actual del actuador. La tecla «Ok» guarda en la memoria los ajustes introducidos; «Esc» sale del modo de calibración sin guardar.   | 
|Calibración Cierre 281 -> 311      |**«Calibración de cierre»** – la calibración del cierre de las entradas de aire se realiza ajustando la posición mínima de las entradas mediante los botones «+» y «-». El primer valor mostrado representa el último ajuste guardado y el segundo valor, la posición actual del actuador. La tecla «Ok» guarda en la memoria los ajustes introducidos; «Esc» sale del modo de calibración sin guardar.|  
|Tiempo de promediado 5 s       |**«Tiempo de promediado»** – tiempo de promediado de la señal de control del conector In; protege contra las oscilaciones en la entrada de control.  | 
|Inversión   No |**«Inversión»** – la activación de esta función adapta el controlador a la señal de control 10-0V  | 
|Idioma   Polaco |**«Idioma»** – selección del idioma del menú  | 
|Histéresis Pot  5   | **«Histéresis del potenciómetro»** – una variación del parámetro de posición del actuador inferior al valor establecido no se tiene en cuenta para el posicionamiento. Este parámetro tiene como finalidad eliminar los movimientos muy pequeños del actuador y las interferencias del potenciómetro. | 
 

# Observaciones y advertencias  

:::danger 
Durante la instalación del dispositivo es imprescindible desconectar la alimentación eléctrica, ya que la tensión presente en algunos componentes supone un peligro para la vida y la salud. Se recomienda encargar la instalación a una persona cualificada.
:::

- Para evitar problemas durante el funcionamiento del dispositivo, es necesario leer las instrucciones antes de proceder a su instalación y uso. No se permite modificar la estructura ni realizar reparaciones por cuenta propia. Esto se aplica especialmente a la modificación de elementos y componentes.
- Las tareas de mantenimiento o servicio deben ser realizadas por personal autorizado (instalador o servicio técnico de la empresa). En las instalaciones ganaderas con ventilación forzada es obligatorio disponer de un sistema de alarma. 
- El fabricante del dispositivo no se responsabiliza de los daños causados por una instalación incorrecta, una programación incorrecta de las funciones, las consecuencias de sucesos fortuitos ni factores externos.
- El dispositivo requiere que los parámetros se ajusten de acuerdo con las condiciones existentes en el recinto de cría. Estos ajustes son individuales y dependen de la decisión del ganadero. El fabricante del dispositivo se reserva el derecho de realizar cambios en la estructura del dispositivo y en el software.  


:::caution
![alt](./img/trash.svg) Al finalizar la vida útil del producto, no debe desecharse junto con los residuos municipales sin clasificar, sino eliminarse de acuerdo con la normativa vigente (directivas WEEE de la Unión Europea 2012/19/UE).  El producto se ha fabricado conforme a los requisitos RoHS (Directiva de la Unión Europea 2011/65/UE).
:::

<!-- \newpage -->
# Datos técnicos del controlador  

|Parámetro                        |	DESCRIPCIÓN      |
|:-----------                    |:---------- |
|Tensión de alimentación alterna|	230VAC 50Hz|
|Corriente máxima de salida|	2A|
|Filtro antiparasitario de salida|	RC|
|Impedancia de entrada|	100kΩ|
|Protección contra sobretensiones de entradas y salidas|	SÍ|
|Alimentación del potenciómetro|	10VDC|
|Corriente máxima de las salidas del potenciómetro|	30mA|
|Rango de temperatura de funcionamiento|	-10 +40oC|
|Dimensiones del dispositivo|	20x15x8 cm |
|Grado de protección de la carcasa|	IP65|

:::info
El controlador IC-AC incluye en el conjunto:
- 4 tacos de expansión,
- 2 prensaestopas PG11,
- 2 prensaestopas PG9.
:::

